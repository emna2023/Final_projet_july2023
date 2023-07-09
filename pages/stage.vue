<template>

<main class="main">
         <img alt="image_banner" src="public/Media/imio1.jpg"  class="main__img"/> 
         <h1 class="main__title">Stage d'entreprise: Imio</h1>
         <h2 class="main__subtitle">Intercommunale de Mutualisation Informatique et Organisationnelle
        </h2>
<h2 class="main__subtitle">Du 01 juin au 30 juin 2023</h2>
<!-- <embed class="main__embed" src="../public/" height="400" width="300"> -->
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imioback2.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Missions et services </h3>
            <p class="main__container__productcontainer__description">
                L'intercommunale a pour but de promouvoir et coordonner la mutualisation 
                de solutions organisationnelles, <br>de produits et services informatiques pour
                 les pouvoirs locaux de la Wallonie.
             </p>
            </div>
</div>

<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imio3.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> iA.SmartWeb </h3>
            <p class="main__container__productcontainer__description">
                iMio offre pour les autorités locales un modèle de site web 
                prêt à l’emploi afin de créer leurs sites web publique. <br> <br>
                Technologie utilisé: CMS Plone (un système de gestion de contenu Web libre)<br>
                IMIO a personnalisé Plone en ajoutant un système de sections <br> <br>
                
                Elle a réalisé plus de 230 sites web avec Plone <br>
                Des sites responsive et répondre au mieux aux attentes d'accessibilité.
             </p>
            </div>
            </div>

            <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imio6.png"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Processus de travail </h3>
            <p class="main__container__productcontainer__description">
                Création et configuration de l'instance<br>
                Formations pour les agents <br>
                Création de contenus par les agents<br>
                Création de la maquette <br>
                Validation de la maquette <br>
                Intégartion du site <br>
                Mise en ligne
                 
             </p>
            </div>
</div>
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/appris2.webp"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> J'ai appris </h3>
            <p class="main__container__productcontainer__description">
                Création de la maquette avec Figma <br>
                Intégration des sites avec Plone 6 en maintenant une squelette HTML standard<br>
                Paramétres d'accessibilité <br>
                Vérification des contrastes de couleurs  <br>
                Utilisation des images libres<br>
                Programmation avec React et Python<br>
                Des bonnes pratiques professionnelles pour le nommage des variables et les fonctions<br>
                 
             </p>
            </div>
</div>
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/emna3.png"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Réalisations </h3>
            <p class="main__container__productcontainer__description">
                Intégration des sections dans des sites<br>
                Réalisation des pages d'erreurs Imio<br>
                Inspection des sites et proposition des améliorations<br>
             </p>
</div>

</div>
</main>

</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');
.main{
    background-image: url("../public/Media/Calque1.jpg");

    &__title
    {
        font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
        text-align: center;
        font-size: 3em;
        padding-bottom: 10px;
        color: rgb(230, 0, 126);

    }
        &__subtitle
    {
        text-align: center;
        padding: 20px;
        font-size: 1.5em;
        color: #666666;
    }
    &__container
    {
        display:grid;
        grid-template-columns: 30% 70%;
        gap:10px;
        padding: 20px;
        padding-top: 50px;
        &__img{
            border:solid;
            border-radius: 25% 10%;
            border-color: transparent;
            height: 250px;
        }
        &__productcontainer
        {
            &__title{
            color: rgb(230, 0, 126);


            }
        }
    }
}




</style>