<template>
    <div class="container-fluid pt-4">
        
        <div class="row">
            <div class="col-lg-1 text-end mt-2">
                <i class="bi bi-arrow-left-circle fs-2"></i>
            </div>
            <div class="col-lg-10">
                <h2 class="mt-3">About</h2>
            </div>
        </div>

        <!--About-->
        <div class="row mt-5 justify-content-center">
            <div class="col-lg-6 text-about">
                <div class="text-center">
                    <h5>Kiana Cake and Cookies adalah sebuah bisnis rumahan yang mulai berdiri 
                    pada tahun 2019. Kami selalu berusaha untuk dapat dapat memberikan hasil karya 
                    kue yang menarik, enak dan memenuhi keinginan customer.</h5>
                </div>
            </div>
        </div>

        <div class="row about p-5 justify-content-center">
            <div class="col-lg-2 d-flex">
                <div class="card flex-fill">
                    <img src="~/assets/logo-rb.png" alt="img-logo" class="img-logo">
                    <div class="card-body text-center">
                        <h6 class="mt-3">Logo</h6>
                    </div>
                </div>
            </div>
            <div class="col-lg-2 d-flex">
                <div class="card flex-fill">
                    <img src="~/assets/owner.png" alt="img-owner" class="img-owner p-3">
                    <div class="card-body text-center">
                        <h6 class="mt-1">Owner</h6>
                    </div>
                </div>
            </div>
            <div class="col-lg-2 d-flex">
                <div class="card flex-fill">
                    <img src="~/assets/kitchen.jpeg" alt="img-kitchen" class="img-kitchen p-3">
                    <div class="card-body text-center">
                        <h6 class="mt-1">Dapur</h6>
                    </div>
                </div>
            </div>
            <div class="col-lg-2 d-flex">
                <div class="card flex-fill">
                    <img src="~/assets/redvelvet-cake.jpeg" alt="img-product" class="img-product p-3">
                    <div class="card-body text-center">
                        <h6 class="mt-1">Produk</h6>
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

h5, h6 {
    font-family: "Poppins", sans-serif;
}

.img-logo {
    width: 170px;
    margin: auto;
    margin-top: 10px;
}

.img-owner, .img-kitchen, .img-product {
    margin: auto;
    width: 183px;
}

.img-product {
    height: 183px;
}

.card {
    border: 1px solid #C6AC7B;
}

</style>