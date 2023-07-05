<template>

    <main class="main">
        <div class="main__bannercontainer">
            <img class="main__bannercontainer__img" alt="logo" src="public/Media/flav2.jpg"/>
        </Div>
        <h1 class="main__title">Bienvenue chez Gourmet Flavors</h1>
        <h2 class="main__subtitle">
            Nos Produits et services
        </h2>
        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/fav7.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Plats préparés et surgelés de haute qualité </h3>
            <p class="main__container__productcontainer__description">
                Nos plats préparés surgelés combleront toutes vos envie en matière d'alimentation variée. La qualité et le goût des produits surgelés ne sont en aucun cas inférieurs aux repas préparés frais. Tous nos plats préparés surgelés
                sont préparés en un rien de temps au four, au micro-onde ou à la poêle et préservent toutes la saveur du poisson, de la viande, des légumes, des pâtes et du riz. 
            </p>
            </Div>
        </div>

        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/flav1.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Epices et condiments exotiques </h3>
            <p class="main__container__productcontainer__description">
                Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus viverra nulla eu mollis dignissim. Morbi quis tempus est, nec malesuada elit. Sed dapibus sodales elit nec hendrerit. 
                Vivamus vestibulum aliquam tortor eu vehicula. Cras finibus porta tellus, sit amet faucibus 
            </p>
            </Div>
        </div>

        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/flav3.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Cours de cuisine et ateliers gastronomiques </h3>
            <p class="main__container__productcontainer__description">
                Les cours de cuisine sont avant tout un moment de partage, parce que la cuisine ça se partage, ce sont des moments en famille, des repas assis à table, ce sont des moments de plaisir, de retrouvailles et de joie.

C’est avant tout sur le partage que le chef veut axer ces cours, c’est pourquoi lors des cours de cuisine vous aurez l’occasion de réaliser l’entièreté des recettes des cours, il n’est donc pas question
 de faire une recette sur les quatre, mais bien de voir la totalité du cours. <br>
 Les cours débutent à 19h, pour une durée moyenne de 3h30 à 4h.<br>

Il faudra pour chaque cours vous munir d’un essuie, d’un tablier et de deux ou trois récipients pour repartir avec quelques délices chez vous.<br>

Réservations des cours par mail à info@laurentmoutoy.com ou au 081 / 61.46.60 .<br>

Seul le paiement de la totalité du cours de cuisine confirme votre inscription, celui-ci est à verser sur le compte BE15.0019.2535.6030.
Les cours ne sont ni échangeables, ni remboursables, dans les sept jours précédents celui-ci, sauf décès et cas de force majeure.
            </p>
            </Div>
        </div>
        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/fav5.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Service de traiteur pour évènements spéciaux </h3>
            <p class="main__container__productcontainer__description">
                Pour réaliser vos souhaits, Aromate, votre traiteur, organise vos réceptions, banquets, fêtes privées
                et vos événements d’entreprise avec passion ainsi qu’une attention particulière aux moindres détails.<br>
                notre chef, vous accompagne et vous conseille pour définir le menu idéal en fonction de vos goûts et des préférences de vos convives.<br>
                Notre équipe multiculturelle crée des menus et des plats adaptés à toutes occasions, mariages, fêtes d’anniversaire, babyshower, cocktails dinatoires, vernissages, ou pendaison de crémaillère.

Du repas assis en passant par le walking dinner, nous proposons également une multitude d’échoppes qui fera voyager vos invités.
Aromate a pour mission de vous faire vivre une véritable expérience gustative et conviviale.<br>
Pour réserver un rendez-vous ou vous renseigner sur nos services, contactez-nous par email à l’adresse info@aromate.be
            </p>
            </Div>
        </div>
        <h2 class="main__subtitle">
            Newsletter
        </h2>
        <div class="main__container">
        <img class="main__container__img2" alt="logo" src="public/Media/logotraiteur.png"/>
        <form class="main__container__form" action="">
        <label class="main__container__form__label"> Nom:</label>
        <input class="main__container__form__text" type="text" id="nom"> 
        <label class="main__container__form__label"> Prénom:</label>
        <input class="main__container__form__text" type="text" id="prénom"> 
        <label class="main__container__form__label"> Age:</label>
        <input class="main__container__form__text" type="text" id="age"> 
        <label class="main__container__form__label"> Lieu:</label>
        <input class="main__container__form__text" type="text" id="Lieu">
        <label class="main__container__form__label"> Mail:</label>
        <input class="main__container__form__mail"  type="email" id="email" size="10" required> 
        <input type="button" value="Submit">	

        </form>
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
        font-size: 3em;
        color: #666666;
    }
    &__bannercontainer
    {
        &__img
        {
        width: 100%;
        height: 20em;
        }
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
        &__productcontainer
        {
            &__title{
            padding-top: 10px;
            color: rgb(230, 0, 126);
            padding-bottom: 10px;


            }
        }
        &__form
        {
            border:solid;
            border-color: rgb(230, 0, 126);
            padding:20px;
            display:flex;
            flex-direction: column;
        }
    }
    
}
</style>