<template>
    <section class="content">
        <div class="container-fluid">
            <div class="row">
                <div class="col-md-8">
                    <div class="card">
                    <div class="card-body p-0">
                        <div class="table-responsive">
                        <table class="table m-0">
                            <thead>
                                <tr>
                                    <th>ID</th>
                                    <th>Sản Phẩm</th>
                                    <th>Trạng thái</th>
                                    <th>Giá tiền</th>
                                </tr>
                            </thead>
                            <tbody>
                                <tr>
                                    <td><a href="pages/examples/invoice.html">OR9842</a></td>
                                    <td>Call of Duty IV</td>
                                    <td><span class="badge badge-success">Đang vận chuyển</span></td>
                                    <td>
                                        <div class="sparkbar" data-color="#00a65a" data-height="20">000000vnđ</div>
                                    </td>
                                </tr>
                                <tr>
                                    <td><a href="pages/examples/invoice.html">OR1848</a></td>
                                    <td>Samsung Smart TV</td>
                                    <td><span class="badge badge-warning">Chờ xác nhận</span></td>
                                    <td>
                                        <div class="sparkbar" data-color="#f39c12" data-height="20">000000vnđ</div>
                                    </td>
                                </tr>
                                <tr>
                                    <td><a href="pages/examples/invoice.html">OR7429</a></td>
                                    <td>iPhone 6 Plus</td>
                                    <td><span class="badge badge-danger">Gián đoạn</span></td>
                                    <td>
                                        <div class="sparkbar" data-color="#f56954" data-height="20">000000vnđ</div>
                                    </td>
                                </tr>
                                <tr>
                                    <td><a href="pages/examples/invoice.html">OR7429</a></td>
                                    <td>Samsung Smart TV</td>
                                    <td><span class="badge badge-info">Lỗi</span></td>
                                    <td>
                                        <div class="sparkbar" data-color="#00c0ef" data-height="20">000000000đ</div>
                                    </td>
                                </tr>
                                <tr>
                                    <td><a href="pages/examples/invoice.html">OR1848</a></td>
                                    <td>Samsung Smart TV</td>
                                    <td><span class="badge badge-warning">Chờ xác nhận</span></td>
                                    <td>
                                        <div class="sparkbar" data-color="#f39c12" data-height="20">00000vnđ</div>
                                    </td>
                                </tr>
                                <tr>
                                    <td><a href="pages/examples/invoice.html">OR7429</a></td>
                                    <td>iPhone 6 Plus</td>
                                    <td><span class="badge badge-danger">Lỗi</span></td>
                                    <td>
                                        <div class="sparkbar" data-color="#f56954" data-height="20">00000000vnđ</div>
                                    </td>
                                </tr>
                            </tbody>
                        </table>
                        </div>
                    </div>
                </div>
            </div>
            </div>
        </div>
    </section>
</template>
<script>
    export default {
        mounted() {
            console.log('Component mounted.')
        }
    }
</script>
