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
            <div class="bg-green">
                <p class="pt-5 text-white fs-3">Why work with me</p>
                <p class="text-white my-fs-10">WEB • BRANDING • UX/UI</p>
                <hr class="text-white pb-5 hr-small">
            </div>
            <div class="bg-red container-fluid">
                <div class="row p-0">
                    <div class="col-6 p-0 position">
                        <div class="img-container">
                            <img src="../../src/assets/img/portfolio1_featured_item-1200x960.jpg" alt="foto dei lavori recenti 1" class="img-hover w-100">
                            <p class="nome-brand">Brand Name</p>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <div class="img-container">
                            <img src="../../src/assets/img/portfolio5_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 2" class="img-hover w-100">
                            <p class="nome-brand">Brand Name</p>
                        </div>
                    </div>
                </div>

                <div class="row">
                    <div class="col-6 p-0">
                        <div class="img-container">
                            <img src="../../src/assets/img/portfolio4_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 3" class="img-hover w-100">
                            <p class="nome-brand">Brand Name</p>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <div class="img-container">
                            <img src="../../src/assets/img/portfolio3_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 4" class="img-hover w-100">
                            <p class="nome-brand">Brand Name</p>
                        </div>
                    </div>
                </div>
                <div class="row">
                    <div class="col-6 p-0">
                        <div class="img-container">
                            <img src="../../src/assets/img/portfolio2_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 5" class="img-hover w-100">
                            <p class="nome-brand">Brand Name</p>
                        </div>
                    </div>
                    <div class="col-6 p-0">
                        <div class="img-container">
                            <img src="../../src/assets/img/portfolio6_featured_item-1200x960.jpg" alt="foto dei lavoti recenti 6" class="img-hover w-100">
                            <p class="nome-brand">Brand Name</p>
                        </div>
                    </div>
                </div>
            </div>

            <div class="text-center bg-red py-4 text-hover">VIEW ALL MY WORK</div>

        </div>

        <div class="quotes">
        
            <div class="container">
                <div class="row text-center d-flex justify-content-center">
                    <div class="col-12">
                        <div v-for="(quote, index) in quotes" :key="index" :class="{ active: index === currentIndex }" class="carousel-item">
                            <div class="row text-center d-flex justify-content-center">
                                <div class="col-9">
                                    <p class="text-center pt-5 my-fs-big">"</p>
                                    <p class="text-white fst-italic">{{ quote.text }}</p>
                                    <p class="text-white my-fs-10">{{ quote.author }}</p>
                                </div>
                            </div>    
                        </div>
                    </div>
                </div>

                <div class="row text-center d-flex justify-content-center py-5">
                    <div class="col-8">
                        <p class="text-white">TRUSTED BY GLOBAL BRANDS</p>
                        <div class="logos d-flex justify-content-between py-3">
                            <img src="../../src/assets/img/logo_demo_1.png" alt="Logo lorem">
                            <img src="../../src/assets/img/logo_demo4.png" alt="Logo American">
                            <img src="../../src/assets/img/Vector_Smart_Object-1.png" alt="Logo lorem">
                            <img src="../../src/assets/img/Vector_Smart_Object-2.png" alt="Logo lorem">
                            <img src="../../src/assets/img/Vector_Smart_Object-3.png" alt="Logo lorem">
                        </div>
                    </div>
                </div>

               
            </div>
        </div>

        <div class="expert-design">

            <div class="text-center py-5">
                <p class="pt-5 text-white fs-3">Expert Design Advice</p>
                <p class="text-white my-fs-10">TRENDING DESIGN NEWS</p>
                <hr class="text-white pb-5 hr-small">
            </div>  

            <!-- INSERIRE UN NUOVO COMPONENT DA QUI -->
            <section class="news">

            
                <DynamicAppNews v-for="news in newsList" 
                :imageSrc="news.src"
                :title="news.titolo"
                :text="news.text"
                />
            </section>   
            <!-- A QUI -->
        </div>

        <div class="work-together text-center container">
            <div class="row d-flex justify-content-center">
                <div class="col-6">

                    <p class="pt-5 fs-3">Let's Work Together</p>
                    <p class="my-fs-10 color-light">TELL ME MORE ABOUT YOUR PROJECT</p>
                    <hr class="pb-5 hr-medium">   

                    <p class="my-fs-10 color-light">Lorem ipsum dolor sit amet consectetur adipisicing elit. Esse ratione a, aut voluptates nulla magnam fuga nobis? Dolore, eos cum. Deleniti voluptates esse odit doloremque praesentium, velit nemo aliquam voluptate.</p>


                    <form class="pb-5">
                        <fieldset disabled>
                            
                            <div class="m-3">
                                <input type="text" id="name" class="form-control" placeholder="NAME*" style="border-radius: 0;">
                            </div>

                            <div class="m-3">
                                <input type="text" id="email" class="form-control" placeholder="EMAIL*" style="border-radius: 0;">
                            </div>

                            <div class="m-3">
                                <input type="text" id="phone" class="form-control" placeholder="PHONE*" style="border-radius: 0;">
                            </div>
                           
                            <button type="submit" class=" btn-primary bottone text-white">LET'S TALK</button>
                        </fieldset>
                    </form>
                </div>
            </div>
        </div>
    </main>
</template>
<script>

import DynamicAppNews from './DynamicAppNews.vue';

export default {
    components: {
        DynamicAppNews
    },
    data() {
        return {
            currentIndex: 0,
            newsList: [
                    {
                        src: "../../src/assets/img/blog3-featured.jpg",
                        titolo: "Live The Design Process",
                        text: "What's to come next? Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud", 
                        
                    },
                    {
                        src: "../../src/assets/img/blog2-featured.jpg",
                        titolo: "What's Next Of The App Store",
                        text: "What's to come next? Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud",
    
                    },
                    {
                        src: "../../src/assets/img/blog1-featured.jpg",
                        titolo: "The Humble Wood Desk",
                        text: "What's to come next? Lorem ipsum dolor sit amet, consectetur adipiscing elit sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud",
                       
                    },
                    
                ],

        
            quotes: [
                    { 
                        text: "That's been one of my mantras - focus and simplicity. Since can be harder than complex; you have to work hard to get your thinking clean to make it simple.", 
                        author: "STEVE JOBS - APPLE" 
                    },

                    { 
                        text: "When something is important enough, you do it even if the odds are not in your favor.", 
                        author: "ELON MUSK - TESLA X" 
                    },
                    { 
                        text: "The biggest risk is not taking any risk.", 
                        author: "MARK ZUCKERBERG - FACEBOOK, INSTAGRAM" 
                    },

                    { 
                        text: "The Web as I envisaged it, we have not seen it yet. The future is still so much bigger than the past.", 
                        author: "TIM BERNERS-LEE" 
                    }

                     ],
                
        }
    },

    mounted() {
        this.startCarousel();
            },

     methods: {
        startCarousel() {
        setInterval(() => {
        this.currentIndex = (this.currentIndex + 1) % this.quotes.length;
      }, 5000);
    },
  },

    
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
        margin: auto;
        font-weight: bolder;
        border-top: 2px solid white;
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
    .bg-green {
        background-color: #96C577;
    }
    .recent-work img {
    width: 50%;
    }

    .bg-red {
        background-color: #F9225B;
    }

    .quotes{
        background-image: url(../../src/assets/img/testimonial_bkgd.jpg);
        height: 550px;
        background-position: center; 
        background-size: cover;
        position: relative;
    }

    .quotes .my-fs-big {
        font-size: 112px;
        color: #F9225B ;
    }

    .quotes p {
        font-size: 12px;
    }
    .expert-design {
        background-color:#49629B ;
    }

    .hr-medium {
        width: 90px;
        margin: auto;
        font-weight: bolder;
        border-top: 2px solid #737E8B;
    }

    .bottone {
        padding: 10px 12px;
        background-color: #F9225B;
        border: none;
    }
    input .no-rounded {
        border-radius: 0; /* Imposta il bordo arrotondato a 0 per rimuoverlo */
    }

    .news {

        display: flex;
        justify-content: center;
        flex-wrap: nowrap; 
    }
/* 
    .img-hover:hover {
        background-color: #F8225A;
        opacity: 0.2;
        
        
    }

    .nome-brand {
        display: none;
        position: absolute;
        top: 50%;
        right: 50%;
        
    }

    .nome-brand:hover {
        display: inline-block;
    }

    .position {
        position: relative;
    } */



    .img-container {
    position: relative;
    overflow: hidden;
}

.img-hover {
    transition: opacity 0.3s;
}

.img-container:hover .img-hover {
    opacity: 0.3;
}

.nome-brand {
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
    font-size: 20px;
    opacity: 0;
    transition: opacity 0.3s;
}

.img-container:hover .nome-brand {
    opacity: 1;
}

.text-hover{
    color: white;
}

.text-hover:hover {
background-color: white;
transition: 0.3s;
color:#F8225A;
}
</style>