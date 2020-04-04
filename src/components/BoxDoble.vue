<template>

    <div class="box-doble">

        <div class="box-doble_content layout-size">

            <slot name="cat"></slot>

            <div class="box-doble__left">

                <slot name="left"></slot>
   
            </div>

            <div class="box-doble__right">

                <slot name="right"></slot>

            </div>

        </div>
      
    </div>

</template>

<script>

    export default {

        name: 'portada',
        props:['img'],
        components: {
            
        }

    }

</script>


<style lang="scss" scope>

    @import "../scss/general.scss";
  
    .box-doble{

        margin: 40px 0;

        .box-doble_content{
            background: #111111;
            margin: auto;
            display: grid;
            grid-template-columns: 1fr 1fr;
            position: relative;

            @media only screen and (max-width: 1024px) {
                grid-template-columns: 1fr;
            }

        }

        .box-doble__cat {
            background: #007bff;
            position: absolute;
            padding: 10px 20px;
            right: -10px;
            top: -10px;
            font-size: 12px;

            @media only screen and (max-width: 768px) {
                display: none;
            }

        }

        .box-doble__left{
            padding: 40px;

            @media only screen and (max-width: 425px) {
                padding: 15px;
            }
        }

        .box-doble__right{
            padding: 40px;

            @media only screen and (max-width: 425px) {
                padding: 15px;
            }

        }

        .box-doble__image{
            border-radius: 50%;
            overflow: hidden;
            width: 250px;
            height: 250px;
            margin: auto;
            position: relative;
            
            img{
                width: 100%;
                -o-object-fit: cover;
                object-fit: cover;
            }

        }

        .box-doble__title{
            font-size: 25px;
            font-weight: 500;
            text-shadow: 0 0 15px #000;
            line-height: 1.5;
        }

        .box-doble__parrafo{
            font-size: 16px;
            font-weight: 400;
            line-height: 22px;
            margin: 5px 0;
            display: block;
            
            img{
                width: 100%;
            }

            iframe{
                width: 100%;
            }

        }


    }
    


</style>
