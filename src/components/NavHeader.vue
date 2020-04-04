<template>

    <div class="nav">

        <div class="nav__grid layout-size">
            <a href="#inicio" class="nav__logo">DanCode</a>
            <a href="#skills" class="nav__item">Skills</a>
            <a href="#proyecto" class="nav__item">Proyectos</a>
            <a href="https://github.com/dancodedev?tab=repositories" target="_blank" class="nav__item">Github</a>
            <a href="https://codepen.io/dancodedev/" target="_blank" class="nav__item">Codepen</a>
            <a href="https://www.linkedin.com/in/dan-jimenez/" target="_blank" class="nav__item">Linkedin</a>
        </div>

    </div>

</template>

<script>

    export default {

        name: 'NavHeader',
        components: {
            
        }

    }

</script>


<style lang="scss" scope>

    @import "../scss/general.scss";
  
    .nav{

        background-color: rgba(17, 17, 17, 0.9);
   
        .nav__grid{
            display: grid;
            grid-template-columns: 3fr repeat(5, auto);
            // grid-template-columns: repeat(auto-fit, minmax(130px,1fr));
            grid-template-rows: 85px;
            grid-column-gap: 30px;
            align-items: center;
            margin: auto;

            @media only screen and (max-width: 723px) {
                grid-template-columns: repeat(auto-fit, minmax(85px,1fr));
                grid-template-rows: 85px 85px;
            }

            @media only screen and (max-width: 375px) {
               grid-template-rows: 42.5px 42.5px 42.5px;
            }
    
            .nav__logo{
                font-size: 23px;
                font-weight: 700;
                user-select: none;
                cursor: pointer;
                color: white;
            }

            .nav__item{
                font-size: 18px;
                font-weight: 600;
                position: relative;
                display: flex;
                justify-content: center;
                align-items: flex-end;
                user-select: none;
                cursor: pointer;
                color: white;

                &:hover::before{
                    content: "";
                    width: 100%;
                    height: 2px;
                    background: #007bff;
                    position: absolute;
                    margin-top: 5px;
                }

                @media only screen and (max-width: 375px) {
                    font-size: 15px;
                }

            }

        }


    }
    


</style>
