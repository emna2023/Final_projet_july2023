<template>
    <header class="header"> 
    <Div class="header__wrapper wrapper">
    <h2 class="header__title">Travail de Fin de Formation</h2>
    <!-- <form>
    <label for="site-search">Search the site:</label>
     <input type="search" id="site-search" name="q">
    <button>Search</button>
    </form> -->
    <nav class="header__nav">
        <ul class="header__nav__list">
            <li class="header__nav__list__onelist">
                 <NuxtLink class="header__nav__list__onelist__link" to="/"> Accueil</NuxtLink></li>
            <li class="header__nav__list__onelist"> 
                <NuxtLink class="header__nav__list__onelist__link" to="/entreprise"> Gourmet Flavors</NuxtLink></li>
            <li class="header__nav__list__onelist">
                <NuxtLink class="header__nav__list__onelist__link" to="/formation"> Formation</NuxtLink></li>
            <li class="header__nav__list__onelist">
                <NuxtLink class="header__nav__list__onelist__link" to="/stage"> Stage</NuxtLink></li>
            <li class="header__nav__list__onelist">
                <NuxtLink class="header__nav__list__onelist__link" to="/developpement"> Développement professionnel</NuxtLink></li>
        </ul>
    </nav>
</Div>
    <!-- <div class="header__img" > </div> -->
    <!-- <img alt="image_banner" src="public/Media/im10.jpg"  class="header__img"/> -->
    
    </header>
    </template> 
    <style scoped>
        @import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');

  .header{
        background-color: rgb(230, 0, 126);;
        padding-top: 20px;
        padding-bottom: 10px;
        color:white; 
        font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
        &__title{
        text-align: center;
        padding:10px;
        font-size: 2em;
        
        }
        
        &__img{
            background-size: cover; 
            width:100%;
            text-align: center;
            height: 120px;

        }
        &__nav
        {
            padding:10px;
            &__list{
                display:flex;
                justify-content: space-around;
                font-size: 20px;
                &__onelist:hover
                {
                    border:solid;
                    border-color: transparent;
                    background-color:white;
                    border-radius: 30px;
                    width:200px;
                    max-height: 80px;
                    float:left;
                    color: rgb(230, 0, 126);
                    text-align: center;
                }


            }
        }
    }
   
    @media(max-width:750px)
{
    .header
    {
        &__title{
        
        font-size: 1.2em;
        
        }
        &__nav
        {
            &__list
            {
                display:block;
                font-size: 15px;
            }
        }
}
}
@media(max-width:900px)
{
    .header
    {
        &__title{
        
        font-size: 1.2em;
        
        }
        &__nav
        {
            &__list
            {
                font-size: 13px;
            }
        }
}
}
    </style> 
    
