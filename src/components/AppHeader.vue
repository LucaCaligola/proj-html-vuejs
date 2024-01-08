<template>
    <header>
        <div class="sfondo">
            <!-- <img src="../../src/assets/img/banner_images.jpg" alt="backgound image" id="background-header"> -->

            <div class="nav-bar d-flex justify-content-between">
                <div>
                    <img src="../../src/assets/img/avada-freelance-logo.png" alt="Logo av Freelance">
                </div>

                <div class="header-right-side">
                    <i class="fa-solid fa-plus mx-4"></i>
                    <i class="fa-solid fa-bars"></i>
                </div>
            </div>
        </div>
    </header>
</template>
<script>
export default {
    
}
</script>

<style>

.sfondo {
    background-image: url(../../src/assets/img/banner_images.jpg);
    height: 600px;
    background-position: center; 
    background-size: cover;
}

#background-header {
  width: 100%;
  height: 100%;
}

.nav-bar {
   padding: 20px 40px;
}

.nav-bar img {
    height: 25px;
    width: 110px;
}
    
.header-right-side {
    color: white;
}    
</style>