<template>
    <div class="container-fluid pt-4">

        <div class="row">
            <div class="col-lg-1 text-end mt-2">
                <i class="bi bi-arrow-left-circle fs-2"></i>
            </div>
            <div class="col-lg-10">
                <h2 class="mt-3">Product</h2>
            </div>
        </div>

        <!--Categories-->
        <div class="row categories mt-5 mx-5 justify-content-center">
            <div class="col-lg-2 text-center">
                <img src="~/assets/birthday-cake.png" alt="img-kategori">
                <h6 class="mt-2">Birthday cake</h6>
            </div>
            <div class="col-lg-2 text-center">
                <img src="~/assets/wedding-cake.png" alt="img-kategori">
                <h6 class="mt-2">Wedding cake</h6>
            </div>
            <div class="col-lg-2 text-center">
                <img src="~/assets/bolu-jadoel.png" alt="img-kategori">
                <h6 class="mt-2">Bolu jadoel</h6>
            </div>
            <div class="col-lg-2 text-center">
                <img src="~/assets/dessert.png" alt="img-kategori">
                <h6 class="mt-2">Dessert</h6>
            </div>
            <div class="col-lg-2 text-center">
                <img src="~/assets/custom.png" alt="img-kategori">
                <h6 class="mt-2 costum rounded-5">Costum cake</h6>
            </div>
        </div>

        <!--Search-->
        <div class="row mt-5 d-flex justify-content-center">
            <div class="col-lg-6">
                <form class="input-group flex-nowrap">
                    <input type="text" class="form-control shadow rounded-5" placeholder="Cari nama atau harga kue" aria-label="Search"
                        aria-describedby="search-addon" />
                </form>
            </div>
        </div>

        <!--Catalogue-->
        <div class="catalogue p-5">
            <div class="row cake gy-5">
                <div class="col-lg-3 d-flex">
                    <div class="card flex-fill rounded-4 shadow">
                        <div class="card-body">
                            <img src="~/assets/redvelvet-cake.jpeg" alt="img-cake" class="card-img-top">
                            <h5 class="mt-3">Butterfly cake</h5>
                            <h3 class="fw-bold">Rp. 35.000</h3>
                            <div class="text-end my-2">
                                <nuxt-link to="../catalogue/detail">
                                    <button class="btn mt-3 rounded-5">Beli</button>
                                </nuxt-link>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 d-flex">
                    <div class="card flex-fill rounded-4 shadow">
                        <div class="card-body">
                            <img src="~/assets/redvelvet-cake.jpeg" alt="img-cake" class="card-img-top">
                            <h5 class="mt-3">Butterfly cake</h5>
                            <h3 class="fw-bold">Rp. 35.000</h3>
                            <div class="text-end my-2">
                                <button class="btn mt-3 rounded-5">Beli</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 d-flex">
                    <div class="card flex-fill rounded-4 shadow">
                        <div class="card-body">
                            <img src="~/assets/redvelvet-cake.jpeg" alt="img-cake" class="card-img-top">
                            <h5 class="mt-3">Butterfly cake</h5>
                            <h3 class="fw-bold">Rp. 35.000</h3>
                            <div class="text-end my-2">
                                <button class="btn mt-3 rounded-5">Beli</button>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="col-lg-3 d-flex">
                    <div class="card flex-fill rounded-4 shadow">
                        <div class="card-body">
                            <img src="~/assets/redvelvet-cake.jpeg" alt="img-cake" class="card-img-top">
                            <h5 class="mt-3">Butterfly cake</h5>
                            <h3 class="fw-bold">Rp. 35.000</h3>
                            <div class="text-end my-2">
                                <button class="btn mt-3 rounded-5">Beli</button>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>

    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Junge&display=swap');
@import url('https://fonts.googleapis.com/css2?family=Kavoon&family=Miltonian+Tattoo&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Red+Rose:wght@300..700&display=swap');


h2 {
    font-family: "Junge", cursive;
}

h3, h5, h6, input, .btn {
    font-family: "Poppins", sans-serif;
}

input {
    font-size: 14px;
    height: 45px;
    border: 1px solid #C6AC7B;
}

.form-control {
  border-right: none;
}

.costum {
    background-color: #C6AC7B;
    color: white;
    height: 20px;
}

.btn {
    width: 100px;
    margin-right: 10px;
    font-size: 17px;
    color: white;
    background-color: #C6AC7B
}

.cake {
    padding: 50px;
}

.categories img {
    width: 100px;
}

.card {
    border: 1px solid #C6AC7B;
}

</style>