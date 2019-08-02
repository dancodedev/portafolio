<template>

    <div class="codepen-view">

        <div class="codepen-box layout-size layout-size--center">

            <p 
                v-for="id in ids" :key="id"
                class="codepen" data-height="565" data-theme-id="dark" data-default-tab="css,result" data-user="dancodedev" :data-slug-hash="id"
            ></p>

        </div>

    </div>

</template>

<script>

    export default {
        name: 'codepenView',
        props:['ids'],
        components: {
            
        }

    }

</script>


<style lang="scss" scope>

    @import "../scss/general.scss";
  

    .cp_embed_wrapper{
        margin: 20px 0;
    }
    .codepen{
        height: 565px; 
        box-sizing: border-box; 
        display: flex; 
        align-items: center; 
        justify-content: center; 
        margin: 1em 0; 
        padding: 1em;
    }



</style>
