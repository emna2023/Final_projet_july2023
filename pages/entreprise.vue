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
                Notre site est dédié aux amateurs de bonnes choses qui souhaitent profiter de repas préparés
                 et surgelés de haute qualité.<br>
                  Nous proposons une large sélection de plats préparés par des chefs 
                 talentueux, utilisant des ingrédients frais et de qualité supérieure. Conçus pour répondre à tous
                  les goûts et à toutes les envies, nos plats sont savoureux, sains et faciles à préparer, 
                  pour vous faire gagner du temps tout en vous offrant une expérience culinaire inoubliable
                   à chaque bouchée. Que vous recherchiez des plats végétariens, sans gluten ou riches en protéines,
                    nous avons tout ce qu'il vous faut pour satisfaire votre appétit. Et avec une livraison rapide
                     et fiable, vous pouvez profiter de nos délicieux plats à tout moment, où que vous soyez.
                      Alors n'hésitez plus, commandez 
                dès maintenant et découvrez la saveur et la qualité de nos plats préparés et surgelés haut de gamme ! 
            </p>
            </Div>
        </div>

        <div class="main__container">
            <img class="main__container__img" alt="logo" src="public/Media/flav1.jpg"/>
            <Div class="main__container__productcontainer">
            <h3 class="main__container__productcontainer__title"> Epices et condiments exotiques </h3>
            <p class="main__container__productcontainer__description">
                Nous sommes fiers de vous proposer une large sélection d'arômes et de saveurs venus des quatre coins du monde.<br>
                Nos produits sont soigneusement sélectionnés pour leur qualité et leur authenticité.
                Nous travaillons en étroite collaboration avec des producteurs locaux pour vous offrir des épices et des condiments de la plus haute qualité.<br> 
                Notre gamme comprend des épices traditionnelles telles que le curcuma, le cumin ou encore le paprika, 
                mais également des mélanges d'épices originaux, issus de recettes traditionnelles. <br>
                Les amateurs de saveurs exotiques trouveront sans aucun doute leur bonheur, 
                avec nos épices et condiments venus d'Asie, d'Afrique, d'Amérique Latine et des Caraïbes.
                 Nous nous efforçons de vous offrir un service de qualité, rapide et fiable.
                  
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
 Les cours débutent à 19h, pour une durée moyenne de 4h.<br>

Il faudra pour chaque cours vous munir d’un essuie, d’un tablier et de deux ou trois récipients pour repartir avec quelques délices chez vous.<br>

Réservations des cours par mail à GourmetFlavors@gmail.com 


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
               Pour réserver un rendez-vous ou vous renseigner sur nos services, contactez-nous par email à l’adresse GourmetFlavors@gmail.com 
            </p>
            </Div>
        </div>
        <h2 class="main__subtitle">
            Newsletter
        </h2>

        <div class="main__container">
        <img class="main__container__img2" alt="logo" src="public/Media/logotraiteur.png"/>

       
        <!-- <form class="main__container__form" action="">
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
        <input class="main__container__form__button" type="button" value="Submit">	
        </form> -->
        <form class="main__container__form" action="submit" @submit.prevent="">
        <label class="main__container__form__label" > Nom:</label>
        <input class="main__container__form__text" name="name" type="text" id="name"  required> 
        <label class="main__container__form__label"> Prénom:</label>
        <input class="main__container__form__text" type="text" id="firstname" required > 
        <label class="main__container__form__label"> Age:</label>
        <input class="main__container__form__text" type="text" id="age" > 
        <label class="main__container__form__label"> Lieu:</label>
        <input class="main__container__form__text" type="text" id="place" >
        <label class="main__container__form__label"> Mail:</label>
        <input class="main__container__form__mail"  type="email" id="email" size="10"  required> 
        <button class="main__container__form__button" type="submit" >Envoyer</button>   
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
        font-size: 1em;
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
            text-align: left;


            }
        }
        &__form
        {
            border:solid;
            border-color: rgb(230, 0, 126);
            padding:20px;
            display:flex;
            flex-direction: column;
            width:600px;

            &__label{
                color: rgb(230, 0, 126);
                font-size: 25px;


            }
            &__text{
                border:solid;
                border-color: rgb(230, 0, 126);

                color: #666666;
                width:300px;

            }
            &__mail{
                border:solid;
                border-color: rgb(230, 0, 126);
                color: #666666;
                width:300px;
                margin-bottom: 30px;
            }
            &__button{
              border:solid;
              width:100px;
              background-color: rgb(230, 0, 126);
              font-size: 25px;
              border-color: rgb(230, 0, 126);
              color: white;
              }
        }
    }
    
}

@media(max-width:900px)
{
    .main
    {
        &__bannercontainer
        {
            &__img{
            height:15em;
            }
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
            font-size: 0.8em;
            
        }
        &__form
        {
            
            width:400px;

            &__label{
                font-size: 20px;


            }
            &__text{
                width:300px;

            }
            &__mail{
                width:300px;
            }
            &__button{
              width:100px;
              font-size: 20px;
              }
        }
    }

}
}
@media(max-width:750px)
{
    .main
    {
    &__bannercontainer
    {
            &__img
            {
            height:10em;
            }
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
    &__form
        {
            
            width:250px;

            &__label{
                font-size: 15px;


            }
            &__text{
                width:200px;

            }
            &__mail{
                width:200px;
            }
            &__button{
              width:80px;
              font-size: 15px;
              }
        }

   

    }

}
}
</style>