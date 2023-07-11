<template>

    <main class="main">
        <img alt="image_banner" src="public/Media/im10.jpg"  class="main__img"/>
        <h1 class="main__title">Emna KHEMAKHEM</h1>
        
      

       

<!--  -->
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/profil3.jpg"/>
            <Div class="main__container__secondcontainer">
            <h3 class="main__container__secondcontainer__title"> Présentation </h3>
            <p class="main__container__secondcontainer__description">
             Titulaire d'un master en systèmes d'information et nouvelles technologies et ayant une solide
             expérience pédagogique dans le domaine de  l'enseignement secondaire consolidé par la participation
             à plusieurs projets Erasmus+, je souhaite orienter ma carriére vers le développement web
            <br>
            
            <a class="main__container__secondcontainer__description__link"
            href="https://sway.office.com/f2JfIBZCkUaQ5zFd?ref=Link&loc=play"> (Cliquer ici pour voir mes activités pédagogiques)</a><br>
        <br>

        
        </p>
            </Div>
        </div>
            <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/cedeg.png"/>
            <Div class="main__container__secondcontainer">
            <h3 class="main__container__secondcontainer__title"> Formation </h3>
            <p class="main__container__secondcontainer__description">
            J'ai suivi un programme de formation de développemnt web à la CEDEG dans lequel j'ai acquis  les compétences nécessaires pour concevoir et développer 
            des sites web de qualité professionnelle en utilisant le langage de balisage HTML, les feuilles de styles CSS et le langage de programmation JavaScript.
            </p>
            </Div>
        </div>
        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imioback2.jpg"/>
            <Div class="main__container__secondcontainer">
            <h3 class="main__container__secondcontainer__title"> Stage </h3>
            <p class="main__container__secondcontainer__description">
                J'ai réalisé un stage dans l'intercommunale Imio qui offre des produits et des services 
                informatiques pour les pouvoirs locaux de la Wallonie.<br>
                Pendant ce stage, j'ai découvert le monde de l'entreprise
                ainsi que les différents métiers du domaine informatique.<br>
                En travaillant à côté des experts du domaine, j'ai appris des nouvelles compétences techniques et 
                des bonnes pratiques de travail.
                Ce stage m'a permis aussi d'utiliser le CMS Plone pour la création des sites web et de découvrir
                un nouveau concept de travail à savoir l'industrialisation des sites web.
            </p>
            </Div>
        </div>
        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/objectif.webp"/>
            <Div class="main__container__secondcontainer">
            <h3 class="main__container__secondcontainer__title"> Objectifs professionnels </h3>
            <p class="main__container__secondcontainer__description">
            Mon objectif professionel est de consolider cette expérience acquise en travaillant
            dans une entreprise dynamique et innovante où je pourrais
            mettre en pratique mes compétences techniques et mes connaissances en matières de développement web.<br>
            Par la suite, Je viserai d'entamer une carriére en tant que formatrice dans le domaine informatique.

            </p>
            </Div>
        </div>



        <!-- /* -->
        

    </main>

</template>

<script setup>
</script>

<style lang="scss" >
@import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');

.main{
    // font-family: Georgia, 'Times New Roman', Times, serif;
    // font-weight: 700;
    font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
    &__title
    {
        font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
        text-align: center;
        font-size: 3em;
        color: rgb(230, 0, 126);
        padding-bottom: 50px;
        padding-top:30px;


    }
    &__img
    {
        height:20em;
        width:100%;
    }

    &__container
    {
        display:grid;
        grid-template-columns: 30% 70%;
        gap:10px;
        padding: 20px;
        &__img{
            border:solid;
            border-radius: 25% 10%;
            border-color: transparent;
            width:auto;
            
        }
        &__secondcontainer
        {
            font-size: 20px;

            &__title{
            color:  #666666;
            text-align: left;
            padding-bottom: 20px;

            }
            &__description{
                &__link{
                    font-size: 15px;
                    color: #666666;
                }
            }
        }

}
}

@media(max-width:900px)
{
    .main
    {
        &__img
    {
        height:15em;
    }
        &__title
    {
        
        font-size: 2em;
        
    }
    &__container
    {
       &__secondcontainer
        {
            font-size: 15px;
        }
      }
    }
}
@media(max-width:750px)
{
    .main
    {
        &__img
        {
        height:10em;
        }
        &__title
        {
        font-size: 1.5em;
        }
        &__container
         {
          &__secondcontainer
          {
            font-size: 12px;
          }
          }
    }
    
}
</style>
