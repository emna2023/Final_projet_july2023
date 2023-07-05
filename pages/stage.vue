<template>

<main class="main">
         <img alt="image_banner" src="public/Media/imio1.jpg"  class="main__img"/> 
         <h1 class="main__title">Stage d'entreprise: Imio</h1>
         <h2 class="main__subtitle">Intercommunale de Mutualisation Informatique et Organisationnelle
</h2>
<h2 class="main__subtitle">Du 01 juin au 30 juin 2023</h2>

<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imio3.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Missions et services </h3>
            <p class="main__container__productcontainer__description">
                L'intercommunale a pour but de promouvoir et coordonner la mutualisation 
                de solutions organisationnelles, de produits et services informatiques pour
                 les pouvoirs locaux de la Wallonie.
             </p>
            </div>
</div>

<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imio5.png"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> iA.SmartWeb </h3>
            <p class="main__container__productcontainer__description">
                iMio offre pour les autorités locales un modèle de site web 
                prêt à l’emploi afin de créer leurs sites web publique. <br>
                Elle a réalisé plus de 230 sites web avec Plone <br>
                Technologie utilisé: CMS Plone  <br>
                Plone est un système de gestion de contenu Web libre<br>
                IMIO a ajouté des personnalisations pour répondre aux besoins des pouvoirs publics 
             </p>
            </div>
</div>
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imio6.png"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Processus de travail </h3>
            <p class="main__container__productcontainer__description">
                iMio offre pour les autorités locales un modèle de site web 
                prêt à l’emploi afin de créer leurs sites web publique. <br>
                Elle a réalisé plus de 230 sites web avec Plone <br>
                Technologie utilisé: CMS Plone  <br>
                Plone est un système de gestion de contenu Web libre<br>
                IMIO a ajouté des personnalisations pour répondre aux besoins des pouvoirs publics 
             </p>
            </div>
</div>
<div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/imio7.png"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> J'ai appris </h3>
            <p class="main__container__productcontainer__description">
                Création de la maquette avec Figma <br>
                Prend en considération les paramétres d'accessibilité: <br>
                vérifier les contrastes de couleurs  <br>
                Utiliser des images libres<br>
                Maintenir une squelette HTML standard pour tous les sites et modifier le reste par le css<br>
                Fait des pages et des sections en HTML/CSS (Pages d'erreurs Imio, sections du site Tubize)<br>
                Inspecter des sites et proposer des Améliorations<br>
                Initiation à React et Python<br>
                Pratiques professionnelles pour le nommage des variables et les fonctions<br>
                Assister à des formations
             </p>
            </div>
</div>



         </main>

</template>

<style scoped>

@import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');
.main{
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
        font-size: 1.5em;
        color: #666666;
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