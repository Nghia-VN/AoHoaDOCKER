<style scoped>
    .action-link {
        cursor: pointer;
    }
</style>

<template>
    <div>
        <div v-if="tokens.length > 0">
            <div class="card card-default">
                <div class="card-body">
                    <table class="table table-borderless mb-0">
                        <thead>
                            <tr>
                                <th>Tên</th>
                                <th>Phạm vi</th>
                                <th></th>
                            </tr>
                        </thead>

                        <tbody>
                            <tr v-for="token in tokens">
                                <!-- Client Name -->
                                <td style="vertical-align: middle;">
                                    {{ token.client.name }}
                                </td>

                                <!-- Scopes -->
                                <td style="vertical-align: middle;">
                                    <span v-if="token.scopes.length > 0">
                                        {{ token.scopes.join(', ') }}
                                    </span>
                                </td>

                                <!-- Revoke Button -->
                                <td style="vertical-align: middle;">
                                    <a class="action-link text-danger" @click="revoke(token)">
                                        Revoke
                                    </a>
                                </td>
                            </tr>
                        </tbody>
                    </table>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
       
        data() {
            return {
                tokens: []
            };
        },

        
        ready() {
            this.prepareComponent();
        },

        mounted() {
            this.prepareComponent();
        },

        methods: {
          
            prepareComponent() {
                this.getTokens();
            },

            getTokens() {
                axios.get('/oauth/tokens')
                        .then(response => {
                            this.tokens = response.data;
                        });
            },

            revoke(token) {
                axios.delete('/oauth/tokens/' + token.id)
                        .then(response => {
                            this.getTokens();
                        });
            }
        }
    }
</script>
