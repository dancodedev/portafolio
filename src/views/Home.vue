<template>

    <div class="web">

        <div class="particles">
            <div class="particle-1"></div>
            <div class="particle-2"></div>
            <div class="particle-3"></div>
        </div>

        <nav-header></nav-header>

        <portada></portada>

        <box-doble id="inicio">

            <template slot="left">
                <div class="box-doble__image">
                    <img src="@/assets/yo.png" alt="">
                </div>
            </template>

            <template slot="right">

                <h1 class="box-doble__title">¿Quien soy?</h1> 

                <span class="box-doble__parrafo">
                    Tengo 28 años y llevo en el mundo del desarrollo más de 7 años, se podría decir que he pasado por java, C# y php, pero el lenguaje que más domino sin duda es javascript.
                </span>

                <h1 class="box-doble__title">¿Que Hago?</h1> 

                <span class="box-doble__parrafo">
                    Actualmente trabajo como freelance desarrollando scrapings para servicios de IA 
                </span>

            </template>
            
        </box-doble>

        <box-doble id="skills">

            <template slot="cat">
                <div class="box-doble__cat">Skills</div>
            </template>

            <template slot="left">

                <h1 class="box-doble__title">¿Que se hacer?</h1> 

                <span class="box-doble__parrafo">
                    <ul>
                        <li>Node.js y javascript tanto cliente como servidor</li>
                        <li>Desarrollo de bots, scrap, automatización</li>
                        <li>Bases de datos Postgress y Msql y No-SQL</li>
                        <li>Framework Vue y React</li>
                        <li>Desarrollo de app android</li>
                        <li>Extensiones de Chrome</li>
                        <li>Wordpress, plugins y plantillas</li>
                        <li>HTML y CSS Avanzado</li>
                    </ul>
                </span>

            </template>

            <template slot="right">

                <h1 class="box-doble__title">¿En que soy experto?</h1> 

                <span class="box-doble__parrafo">
                    Estas son las tecnologías que más se y utilizo a diario.
                </span>

                 <span class="box-doble__parrafo">
                    <ul>
                        <li>Javascript tanto frontend como backend</li>
                        <li>Framework Vue</li>
                        <li>CSS (SASS)</li>
                    </ul>
                </span>
               
            </template>
            
        </box-doble>

         <box-doble id="proyecto">

            <template slot="cat">
                <div class="box-doble__cat">Freelance</div>
            </template>

            <template slot="left">

                <h1 class="box-doble__title">Freelance y proyectos</h1> 

                <span class="box-doble__parrafo">
                    <ul>
                        <li><a href="http://compare-instagram.dancode.es/" target="_blank">Comparador de perfiles instagram</a></li>
                        <li><a href="https://yourwayco.com/es/" target="_blank">Tienda online de gafas</a></li>
                        <li><a href="https://play.google.com/store/apps/details?id=fs.animals.puzzle.kids" target="_blank">Juego android de puzzles para niños</a></li>
                        <li><a href="https://www.youtube.com/channel/UCY43EU9Ne-GxfHiYw2VcwLg/videos" target="_blank">Canal de nombres generado automáticamente</a></li>
                    </ul>
                </span>

            </template>

        </box-doble>

        <box-doble>

            <template slot="cat">
                <div class="box-doble__cat">Proyecto</div>
            </template>

            <template slot="left">

                <h1 class="box-doble__title">Escuchando en castellano videos de youtube en inglés</h1> 

                <span class="box-doble__parrafo">
                    Como de costumbre navegaba por youtube en busca de algún vídeo interesante que ver. No me resultó extraño encontrar decenas de vídeos en inglés sobre justamente la temática que quería. Mi rutina normal fue la de siempre, activar los subtítulos y empezar a leer, pero ese día seguramente por exceso de pereza me vino una sencilla pregunta.
                </span>

                <span class="box-doble__parrafo">
                   ¿Y si pudiera reproducir con un sintetizador de voz TTS los subtítulos ya existentes?
                </span>


            </template>

            <template slot="right">

                <iframe width="100%" height="315" src="https://www.youtube.com/embed/m-VppFIKoGk" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

            </template>
            
        </box-doble>

        <box-doble >

            <template slot="cat">
                <div class="box-doble__cat">Proyecto</div>
            </template>

            <template slot="left">

                <h1 class="box-doble__title">Ganar dinero creando juegos para android no es tan fácil</h1> 

                <span class="box-doble__parrafo">
                    <p>Desde que empecé en la programación siempre quise hacer un juego y por fin parecía que iba a llegar ese momento. Mis requisitos son "sencillos"</p>
                    <ul>
                        <li>Juego multijugador masivo en línea</li>
                        <li>60fps y latencia mínima</li>
                        <li>Gráficos 3d con resolución 4k</li>
                        <li>Música de estudio</li>
                    </ul>
                    <p>Vamos yo quería hacer esto...</p>
                    <p><img src="https://i.giphy.com/media/SNf41wfVbB8vS/giphy.webp" alt="&quot;creando" width="400" /></p>
                    <p>Y termine haciendo esto....</p>
                    <p><img src="https://media.giphy.com/media/tHyv5R8goWqpxLL1Er/giphy.gif" alt="puzzle de animales para niños" width="400" /></p>
                    <p>Lo mejor de todo fue juntarme con mi amigo y socio <a target="_blank"  href="https://www.linkedin.com/in/izhar-sanz-fuentes-416299175/">Izhar</a> para montar lo que sería nuestro primer juego para android. En ese momento pensamos que el contenido para niños era una buena idea, ya que al investigar la store de google play nos pareció un nicho lo suficientemente demandado y con no demasiada competencia, nuestro primer y gran error.</p>
                    <p>La idea principal del juego fue hacer un puzzle muy sencillo, con piezas grandes. Usando google store buscamos la principal competencia y nos dimos cuenta del gran potencial de demanda.</p>
                    <ul>
                        <li><strong><a target="_blank" href="https://play.google.com/store/apps/details?id=com.iabuzz.puzzle4kidsAnimals">Puzzles animales para niños</a>:</strong> 10.000.000+</li>
                        <li><a target="_blank" href="https://play.google.com/store/apps/details?id=com.littleApple.PuzzleAnimals"><strong>Juegos para peques de 2 años</strong></a>: A: 1.000.000+</li>
                        <li><strong><a target="_blank" href="https://play.google.com/store/apps/details?id=com.appilo.puppiespuzzle">Cachorros - Rompecabezas</a>:</strong> 5.000.000+</li>
                    </ul>
                                        
                </span>

            </template>

            <template slot="right">

                <span class="box-doble__parrafo">
                    <p>Claro, al ver tantas descargas en este tipo de aplicaciones nos emocionamos rápidamente y pensamos que nosotros también podríamos mantener nuestro juego en las primeras posiciones bajo nuestra palabra clave <a target="_blank" href="https://play.google.com/store/apps/details?id=fs.animals.puzzle.kids">Puzzle de Animales para Niños.</a></p>
                    <p>En ese momento no teníamos ni diseñador ni presupuesto para invertir, pero como nos encanta investigar y probar, nos lanzamos de lleno. Las herramientas de las que disponíamos fueron.</p>
                    <ul>
                        <li><a target="_blank" href="https://unity3d.com/es">Unity</a>: Para la creación del videojuego</li>
                        <li><a target="_blank" href="https://www.freepik.es/">Freepik</a>: Imagenes de Stock para usarlas en el juego</li>
                        <li><a target="_blank" href="https://www.adobe.com/es/products/illustrator.html">Adobe Ilustrator</a>: Editor de imágenes vectoriales</li>
                    </ul>
                    <p>Desconocíamos cómo funcionaba unity y debido a eso tardamos más de la cuenta en crear el videojuego, lo que iba a ser un mes, terminó siendo varios, sobretodo queríamos lanzar algo de buena calidad, nos centramos mucho en el rendimiento para que funcionase en casi cualquier móvil y que todo se viese con buena resolución.</p>
                    <p>
                        <iframe src="https://www.youtube.com/embed/HXh9fE4bSjQ" width="100%" height="315" frameborder="0" allowfullscreen="allowfullscreen"></iframe>
                    </p>
                    <p> </p>
                    <p>Esta es la triste realidad actual de la app, como se puede ver, esta totalmente abandonada y apenas mantiene entre 20 y 40 usuarios activos de los 240.</p>

                    <p>La app arrancó como esperamos con cero visitas, pero google ads nos regaló una promoción de 100€ y quisimos invertir, en ese momento sí que se noto las instalaciones y lo mejor de todo fue que posicionó durante ese tiempo en las primeras posiciones bajo su palabra clave, el problema fue que al quitar los anuncios, bajaron las instalaciones y la app se perdido entre todas las demás apps.</p>

                    <p><strong>Conclusión</strong></p>
                    <p>Aparte de hacer un buen producto, es necesario tener una estrategia para llegar a tu audiencia, la gran cantidad de apps que se publican cada día en la tienda de google play dificulta mucho aparecer delante de los usuarios, por nuestras pruebas es necesaria una base de usuarios activa que mueves hacia la app o captar nuevos usuarios con ads. No dudo que volveremos a intentarlo con nuevas estrategias, un saludo.</p>
                </span>


            </template>
            
        </box-doble>


        <!-- <codepen-view :ids="['eqRdaR', 'mNwrMz', 'gVRMdv']"></codepen-view> -->

    </div>

</template>

<script>

    import NavHeader from '@/components/NavHeader'
    import Portada from '@/components/Portada'
    import BoxDoble from '@/components/BoxDoble'
    import codepenView from '@/components/codepenView'

    export default {
        name: 'web',
        components: { NavHeader, Portada, BoxDoble, codepenView},
        data(){
            return {
   
            }
        }

    }

</script>



<style lang="scss" scope>

    @import "../scss/colors.scss";
    @import "../scss/_particles.scss";

    body{
        color: #fff;
        font-family: 'Montserrat', sans-serif;
        background-color: #030303;
    }

</style>
