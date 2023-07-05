<template>

    <footer class="footer">
        <div class="footer__container">
            <img class="footer__container__img" alt="myphoto" src="public\Media\cedeg.png"/>
            <div class="footer__container__subsection">
                <h2>Coordonnées personelles: </h2>
                <h2> Adresse: chaussée de wavre 17, 5030 Gembloux</h2>
                <h2> Email: khemakhememna@cedeg.be</h2>
                <h2> Tel: +32 455 14 77 23</h2>

                 
            </div>
            <div class="footer__container__subsection">Liens utiles</div>
        </div>

    </footer>
</template>

<style setup>
  @import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');


.footer{
    /* background-color: rgb(230, 0, 126); */
    background-color:#4d4d4d;



        color:white;
        
        font-size: 15px;
        &__container{
            display:flex;
            justify-content: space-around;
            &__img{
                height:20%;
                width:80px;
            }
           &__subsection
           {
            
           }

        }
}
</style>