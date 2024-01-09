<template>
    <main>
        <div class="about-me text-center">
            <div class="container pb-5">

                <p class="pt-5 text-white fs-3">About Me</p>
                <p class="color-light-blue"> UI & UX EXPERT</p>
                <hr class="text-white pb-5 hr-small">

            
                <div class="row color-light-blue d-flex justify-content-center pb-5">
                    <p class="col-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea, odio assumenda, unde ex quasi laudantium earum similique explicabo quam porro laborum aspernatur! 
                        Alias, ipsam officia similique atque distinctio fuga sequi!
                        Ut magni pariatur velit fugiat error voluptatum amet qui minus cum magnam, dolorem minima eos hic? Similique eligendi dicta, maiores exercitationem odio vitae recusandae! Assumenda soluta at quaerat impedit in!
                        Doloribus eveniet non, libero iure quasi quos, blanditiis tenetur architecto nostrum aperiam veritatis ullam totam perferendis at exercitationem molestiae enim mollitia ab veniam debitis eum vero velit ut hic! Nobis!
                    </p>
                    <p class="col-5">Lorem ipsum dolor sit amet consectetur adipisicing elit. Ea, odio assumenda, unde ex quasi laudantium earum similique explicabo quam porro laborum aspernatur! Alias, ipsam officia similique atque distinctio fuga sequi!
                    Ut magni pariatur velit fugiat error voluptatum amet qui minus cum magnam, dolorem minima eos hic? Similique eligendi dicta, maiores exercitationem odio vitae recusandae! Assumenda soluta at quaerat impedit in!
                    Doloribus eveniet non, libero iure quasi quos, blanditiis tenetur architecto nostrum aperiam veritatis ullam totam perferendis at exercitationem molestiae enim mollitia ab veniam debitis eum vero velit ut hic! Nobis!
                    </p>
                </div>
            </div>
        </div>

        <div class="work-with-me text-center">
            <div class="container py-5">
                <p class="pt-5 text-white fs-3">Why work with me</p>
                <p class="color-light-blue">WEB • BRANDING • UX/UI</p>
                <hr class="text-white pb-5 hr-small">

                <div class="row color-light-blue d-flex justify-content-center pb-5">
                    <p class="col-5">Lorem ipsum, dolor sit amet consectetur adipisicing elit. Necessitatibus esse numquam quam commodi officiis illo culpa expedita id repellendus dolores? Eius tenetur dolores sed commodi illo quos culpa minus vitae!

                    </p>
                    
                </div>

                <div class="row d-flex justify-content-center">
                    <div class="col-3">
                        <i class="fa-solid fa-pen-nib circle-1"></i>
                        <p class="text-white pt-3">WEB DESIGN</p>
                    </div>

                    <div class="col-3">
                        <i class="fa-solid fa-shield-halved circle-2"></i>
                        <p class="text-white pt-3">BRANDING</p>
                    </div>

                    <div class="col-3">
                        <i class="fa-regular fa-gem circle-3"></i>
                        <p class="text-white pt-3">UX / UI</p>
                    </div>
                </div>
            </div>
        </div>

        <div class="recent-work text-center">

            <p class="pt-5 text-white fs-3">Why work with me</p>
            <p class="text-white my-fs-10">WEB • BRANDING • UX/UI</p>
            <hr class="text-white pb-5 hr-small">

            <img src="../../src/assets/img/portfolio1_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 1">
            <img src="../../src/assets/img/portfolio5_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 2">
            <img src="../../src/assets/img/portfolio4_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 3">
            <img src="../../src/assets/img/portfolio3_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 4">
            <img src="../../src/assets/img/portfolio2_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 5">
            <img src="../../src/assets/img/portfolio6_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 6">


        </div>






    </main>
</template>
<script>
export default {
    
}
</script>
<style>
    .about-me {
        height: 100%;
        background-color: #1F232C;
        /* clip-path: polygon(0 0, 100% 0, 100% 100%, 0 80%); */
        
    }
    .hr-small {
        width: 60px;
        height: 10px;
        margin: auto;
        font-weight: bolder;
        border-top: 3px solid white;
    }

    .work-with-me {
        background-color: #191C22;
        /* clip-path: polygon(100% 80%, 100% 100%, 100% 100%, 0 100%); */
        /* clip-path: polygon(0 0, 100% 0, 100% 96%, 0 100%); */
        margin-bottom: rem;
    }

    .col-3 i {
        font-size: 3rem;
        color: #626E8A;
        padding: 1.8rem;
        /* border: 6px solid #F8225A; */
        border-radius: 50%;
    }
    .circle-1 {
        background: 
        radial-gradient(closest-side, #191C22 85%, transparent 100% 100%),
        conic-gradient(#F8225A 90%, transparent 0);
    }
    .circle-2 {
        background: 
        radial-gradient(closest-side, #191C22 85%, transparent 100% 100%),
        conic-gradient(#F8225A 80%, transparent 0);
    }
    .circle-3 {
        background: 
        radial-gradient(closest-side, #191C22 85%, transparent 100% 100%),
        conic-gradient(#F8225A 97%, transparent 0);
    }
    .col-3 p {
        font-size: 10px;
    }
    .recent-work {
        background-color: #96C577;
    }

</style>