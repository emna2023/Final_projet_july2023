<template>

    <main class="main">
        <img alt="image_banner" src="public/Media/im10.jpg"  class="main__img"/>
        <h1 class="main__title">Stagiaire: Emna KHEMAKHEM</h1>
        <h2 class="main__subtitle">
            Formation : Développeur (euse) Web
        </h2>
      

       

<!--  -->
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/cedeg.png"/>
            <Div class="main__container__secondcontainer">
            <h3 class="main__container__secondcontainer__title"> Formation </h3>
            <p class="main__container__secondcontainer__description">
            Grâce à cette formation, j'ai appris  les compétences nécessaires pour concevoir et développer 
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
                Pendant ce stage, j'ai découvert la réalité du monde professionelle
                ainsi que les différents métiers du domaine informatique.<br>
                En travaillant à côté des experts du domaine, j'ai appris des nouvelles compétences techniques et 
                des bonnes pratiques de travail.
                J'ai appris aussi à utiliser le CMS Plone pour la création des sites web et surtout j'ai découvert
                une nouvelle approche de travail à savoir l'industrialisation des sites web.
            </p>
            </Div>
        </div>
        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/objectif.webp"/>
            <Div class="main__container__secondcontainer">
            <h3 class="main__container__secondcontainer__title"> Objectifs professionnels </h3>
            <p class="main__container__secondcontainer__description">
            Mon objectif professionel est de travailler dans une entreprise dynamique et innovante ou je pourrais
            mettre en pratique mes compétences techniques et mes connaissances en matières de développement web.<br>
            Je vise aussi travailler en tant que formatrice dans le domaine de l'informatique étant donné que je maîtrise 
            plusieurs languages de programmation.

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

    }
    &__subtitle
    {
        text-align: center;
        padding: 30px;
        font-size: 3em;
        color: #666666;
        padding-bottom: 50px;

    }
    

    
    &__img{
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
            
        }
        &__secondcontainer
        {
            &__title{
            color:  #666666;
            text-align: left;
            font-size: 20px;
            padding-bottom: 20px;

            }
            &__description{
                font-size: 20px;
            }
        }



    //     &__container{
    //     display:flex;
    //     &__sectionLeft{
    //         width:20%;
    //     }
    //     &__sectionRight{
    //         width:60%
    //     }
    //     &__section3{
    //         width:20%
    //     }

    // }
}
}
</style>
