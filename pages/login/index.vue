<template>
    <div class="container-fluid">

        <div class="text-center">
            <h2>Silahkan login, <b>Admin</b></h2>
        </div>

        <div class="row mt-5 justify-content-center">
            <div class="col-lg-4">
                <div class="card rounded-4 shadow">
                    <div class="card-body p-5">
                        <form>
                            <div class="mb-3">
                                <label for="exampleInputEmail1" class="form-label">Email</label>
                                <input type="email" class="form-control" id="exampleInputEmail1" aria-describedby="emailHelp">
                            </div>
                            <div class="mb-3">
                                <label for="exampleInputPassword1" class="form-label">Password</label>
                                <input type="password" class="form-control" id="exampleInputPassword1">
                            </div>
                            <div class="text-center mt-5">
                                <nuxt-link to="/dashboard">
                                    <button type="submit" class="btn rounded-5 fs-5">Submit</button>
                                </nuxt-link>
                            </div>
                        </form> 
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Kavoon&family=Miltonian+Tattoo&family=Poppins:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&family=Red+Rose:wght@300..700&display=swap');

.container-fluid {
    height: 100vh;
    background-color: #D8C7A6;
}

.text-center, label {
    font-family: "Poppins", sans-serif;
}

.btn {
    width: 125px;
    color: white;
    background-color: #C6AC7B;
}

</style>