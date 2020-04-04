<template>

    <div class="portada">

        <div class="portada__box">

            <div class="portada__text">Hola! me llamo</div>
            <div class="portada__text portada__text--title">Dan Jimenez</div>
            <div class="portada__text portada__text--subTitle">Javascript, Node.js, Scrap</div>

        </div>
      
    </div>

</template>

<script>

    export default {

        name: 'portada',
        components: {
            
        }

    }

</script>


<style lang="scss" scope>

    @import "../scss/general.scss";
  
    .portada{

        .portada__box{
            margin: 127.5px 0;
            text-align: center;

            .portada__text{
                font-size: 23px;
                font-weight: 300;
                margin: 20px;


                &.portada__text--title{
                    font-size:70px;
                    font-weight: 800;
                    
                    @media only screen and (max-width: 425px) {
                        font-size: 63px;
                    }
                    
                }

                &.portada__text--subTitle{
                    font-size:23px;
                    font-weight: 600;
                }

            }

        }


    }
    


</style>
