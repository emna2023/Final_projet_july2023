<template>

    <footer class="footer">
        <h2 class="footer__title2">Coordonnées personelles: </h2>
        <div class="footer__container">
            <div class="footer__container__subsection">
                <div class="footer__container__subsection__part">
                <h2> Email: khemakhememna@cedeg.be</h2>
                </div>
                <div class="footer__container__subsection__part">
                <h2> Adresse: chaussée de wavre 17, 5030 Gembloux</h2>
                </div>
                <div class="footer__container__subsection__part">
                <h2> Tel: +32 455 14 77 23</h2>
                </div>
            </div>
        </div>

    </footer>
</template>

<style setup>
  @import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');

.footer{
    /* background-color: rgb(230, 0, 126); */
    background-color:#4d4d4d;
    font-size: 20px;
    padding-top: 20px;
    padding-bottom: 20px;
    padding-left: 5px;
    font-family: 'Martian Mono', monospace;
    font-family: 'Righteous', cursive;
    width:100%;
    color:white;
    font-size: 15px;
    &__title2
    {
        text-align: center;
        padding-bottom: 10px;
    }

    &__container{
    &__subsection
    {
    display:flex;
    justify-content: space-around;
    }

        }
}

@media(max-width:900px)
{
    .footer{
    font-size: 10px;
    }}
@media(max-width:500px)
{
    .footer{
    font-size: 10px;
    &__title2
    {
        text-align: left;
        
    }

    &__container{
            
        &__subsection
        {
        display:block;
        }

        }
    
}}
</style>