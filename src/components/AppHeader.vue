<template>
    <header>
        
        <div class="sfondo">

            <div class="nav-bar d-flex justify-content-between">
                <div>
                    <img src="../../src/assets/img/avada-freelance-logo.png" alt="Logo av Freelance">
                </div>

                <div class="header-right-side text-white">
                    <i class="fa-solid fa-plus mx-4"></i>
                    <i class="fa-solid fa-bars"></i>
                </div>
            </div>

            <div class="d-flex flex-column align-items-center testo">
                <span class="text-white">AVADA FREELANCE</span>
                <span class="text-big">Art Director</span>
                <span class="color-light-blue">IF IT DOESN'T CHALLENGE YOU, IT DOESN'T CHANGE YOU</span>
            </div>
                
            <div class="demos">
                <span class="folder"><i class="fa-solid fa-folder-closed"></i></span>
                <span>Demos</span>
            </div>
            <div class="onsale">
                <span class="dollaro">$</span>
                <span class="prezzo">39</span>
                <p>On Sale</p>
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
    height: 550px;
    background-position: center; 
    background-size: cover;
    position: relative;
}

#background-header {
  width: 100%;
  height: 100%;
}

.nav-bar {
   padding: 20px 50px;
}

.nav-bar img {
    height: 25px;
    width: 110px;
}

.text-big {
    font-size: 5rem;
    color: #F8225B;
   
}

.testo {
    margin-top: 120px;
}

.demos {
    position: absolute;
    top: 100px;
    right: 15px;
    font-size: 10px;
    background-color: white;
    height: 50px;
    width: 50px;
    border-radius: 5px;
    text-align: center;
    color: #33475B;
}

.folder {
    font-size: 20px;
}

.prezzo {
    font-size: 20px;
    color: #65BC7B;
    text-align: center;
    font-weight: bold;
    text-align: center;
}

.dollaro {
    position: absolute;
    top: 0px;
    left: 3px;
    color: #65BC7B;
    font-size: 15px;
    font-weight: bold;

}

.onsale {
    position: absolute;
    top: 160px;
    right: 15px;
    font-size: 10px;
    background-color: white;
    height: 50px;
    width: 50px;
    border-radius: 5px;
    text-align: center;
    
}
</style>