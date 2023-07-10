<template>

    
        <main class="main">
         <img alt="image_banner" src="public/Media/cedeg1.jpg"  class="main__img"/> 
         <h1 class="main__title">Formation: Développeur(euse) web</h1>
         <h2 class="main__subtitle">
            Lieu: CEDEG (du 15 mars au 14 juillet)</h2>

         
         <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/code3.avif"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Contenus </h3>
            <p class="main__container__productcontainer__description">
                Le langage HTML (Balises, Méthode BEM)<br>
                Les feuilles de styles CSS (SASS, Tailwinds)<br>
                Utilisation du terminal<br>
                Discord (La communication et le télétravail)<br>
                Github <br>
                JavaScript<br>
                Le framework Nuxt.js<br>
                Utilisation de l'API<br>
                MySQL (Création et interrogation de la base de données)<br>


            </p>
            </div>
            </div>
            
            <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/im9.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title">  Formations complémentaires 
            </h3>
            <p class="main__container__productcontainer__description">
                Création de CV <br>
                Création de la lettre de motivation<br>
                Recherche de stage<br>
                Entretien de stage<br>

            </p>
            </Div>
             </Div>
            
           <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/code4.avif"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Réalisations </h3>
            <p class="main__container__productcontainer__description">
                
                
                Une série d'exercices sur HTML et CSS:<br>
                <NuxtLink to="https://github.com/cedeg-formation/HTMLCssLiveCodingGroup">
                    TP 1: Rick & Morty  </NuxtLink> 
                    <NuxtLink to="">
                    /TP 2: First shop (Adidas)</NuxtLink>
                    <NuxtLink to="https://github.com/cedeg-formation/HtmlCssTest-READY">
                    /TP 3: Blog</NuxtLink> <br><br>
                Une série d'exercices JavaScript:<br>
               
                <NuxtLink to="https://github.com/cedeg-formation/JsTest01-PROMO-01">
                    Série 1 Javascript</NuxtLink> 

                <NuxtLink to="https://github.com/cedeg-formation/JsTest01-PROMO-02">
                    /Série 2 Javascript</NuxtLink> <br><br>
                Projets avec Nuxt:<br>

                <NuxtLink to="https://github.com/cedeg-formation/Animal-Crossing-Api-Exo-01">AnimalCrossing</NuxtLink> 

                <NuxtLink to="https://github.com/cedeg-formation/Fake-Store-Api">/FakestoreApi</NuxtLink> 

                <NuxtLink to="https://github.com/emna2023/IntershipProject">/Projet PowerUp</NuxtLink> <br><br>
                Base de données SQL: <br>
                <NuxtLink to="https://github.com/cedeg-formation/LearnSQLWithNaruto">  LearnSQLWithNaruto</NuxtLink> <br>

            </p>
            </Div>
             </Div>
            <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/code1.avif"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Améliorations </h3>
            <p class="main__container__productcontainer__description">
                De fond:<br>
                Un planning clair <br>
                <!-- Organisation pédagogique et répartition des savoirs<br> -->
                Support de cours<br>
                De forme:<br> 
                Petite salle mal aérée<br>
                Les chaises sont inconfortable<br> 
                Le vidéo projecteur est très proche de certains stagiaires (Lumière très forte) <br>
            </p>
            </Div>
            </div>
        
    </main>

</template>
<style scoped>
.main{
    &__title
    {
        font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
        text-align: center;
        font-size: 3em;
        /* color: #666666; */
        color:rgb(230, 0, 126);
        padding-top: 30px;

    }
    &__subtitle
    {
        text-align: center;
        padding: 20px;
        font-size: 3em;
        color: #666666;
        padding-bottom: 50px;

    }

    &__img
        {
        width: 100%;
        height: 20em;
        }
        &__container
    {
        display:grid;
        grid-template-columns: 30% 70%;
        gap:10px;
        font-size: 1em;

        padding: 20px;
        &__img{
            border:solid;
            border-radius: 25% 10%;
            border-color: transparent;
        }
        &__productcontainer
        {
            &__title{
            color: rgb(230, 0, 126);


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
        height:10em;
        }
        &__title
    {
        
        font-size: 2em;
        
    }
    &__subtitle
    {
        font-size: 2em;
 
    }
    &__container
    {
    &__productcontainer
        {
            font-size: 0.9em;
    
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
    &__subtitle
    {
        font-size: 1em;
 
    }
    &__container
    {
    &__productcontainer
        {
            font-size: 0.7em;
    
    }
    
    }
    
    }
}
</style>