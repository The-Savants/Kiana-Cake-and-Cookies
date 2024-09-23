<template>
    <nav class="navbar navbar-expand-lg bg-light">
        <div class="container-fluid">
            <img src="../assets/logo-rb.png" alt="logo" class="logo">
            <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
                <span class="navbar-toggler-icon"></span>
            </button>
            <div class="collapse navbar-collapse" id="navbarNav">
                <ul class="navbar-nav ms-auto">
                    <li class="nav-item">
                        <nuxt-link to="/" class="nav-link active" aria-current="page">Home</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="/catalogue" class="nav-link">Product</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="/about" class="nav-link">About</nuxt-link>
                    </li>
                    <li class="nav-item">
                        <nuxt-link to="/contact" class="nav-link">Contact</nuxt-link>
                    </li>
                </ul>
            </div>
        </div>
    </nav>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kavoon&family=Miltonian+Tattoo&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Red+Rose:wght@300..700&display=swap');


.nav-item {
    font-size: 1rem;
    margin-right: 2rem;
}

h1 {
    margin-top: 1rem;
    margin-left: 1.5rem;
    font-size: 2rem;

}

.navbar-collapse {
    margin-right: 5rem;
}

i {
    margin-left: 2rem;
}

h1, .nav-item {
    font-family: "Poppins", sans-serif;

}

.logo {
    width: 75px;
    margin-left: 50px;
}

</style>