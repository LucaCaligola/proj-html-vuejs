<template>
    <div class="container-fluid bg-dark d-flex">
                
        <div class="row">
            
            <div class="col-12 p-0" >
                    <img :src="imageSrc" :alt="title" class="w-100">
                    <h3 class="pt-3 px-2 text-danger fs-5">
                        {{ title }}
                    </h3>  
                    <p class="color-light-blue px-2">
                        {{ text }}
                    </p>     
            </div>
    
        </div>
    </div>
</template>
<script>
export default {

    props: {
        title : String,
        text : String,
        imageSrc : {
            type: [String, Boolean],
            required: true
        },
        
    }
    
}
</script>
<style>
    
</style>