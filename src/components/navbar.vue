<template>
    <div class="navigation-container mt-2">
        <nav class="navbar d-flex justify-content-between navbar-expand-lg">
           <div class="col-6 col-md-2 text-left m-0 p-0">
                <img src="../assets/logo.png" alt="" style="max-height: 50px;">
           </div>
                <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
                   <i class="fa fa-bars" aria-hidden="true"></i>
                </button>
            <div class="collapse col-md-10 pull-right navbar-collapse" id="navbarSupportedContent">
                <ul class="navbar-nav ml-auto">
                <li class="nav-item active">
                    <a class="nav-link px-3" href="#">Home <span class="sr-only">(current)</span></a>
                </li>
                <li class="nav-item">
                    <a class="nav-link px-3" href="#">Features</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link px-3" href="#">How it works?</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link px-3" href="#">Our Mission.</a>
                </li>
                <li class="nav-item">
                    <a class="nav-link px-3" href="#">Why us?</a>
                </li>
                 <li class="nav-item">
                    <a class="nav-link px-3" href="#">Meet our team.</a>
                </li>
                <!-- <li class="nav-item dropdown">
                    <a class="nav-link px-3 dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
                    Dropdown
                    </a>
                    <div class="dropdown-menu" aria-labelledby="navbarDropdown">
                    <a class="dropdown-item" href="#">Action</a>
                    <a class="dropdown-item" href="#">Another action</a>
                    <div class="dropdown-divider"></div>
                    <a class="dropdown-item" href="#">Something else here</a>
                    </div>
                </li> -->
                <li class="nav-item">
                    <button class="btn med-button">Contact</button>
                </li>
                </ul>
                <!-- <form class="form-inline my-2 my-lg-0">
                <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
                <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
                </form> -->
            </div>
        </nav>
    </div>
</template>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Raleway:wght@600;700;900&display=swap');

.nav-item{
    font-family: 'Raleway', sans-serif;
    font-weight: 600;
   
}
.nav-item a{
     color: #343434 !important;
}
.med-button{
    background-color: white;
    color:rgb(66,180,231)
}
</style>