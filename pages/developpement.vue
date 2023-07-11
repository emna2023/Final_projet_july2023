<template>

    <main class="main">
        <img alt="maphoto" src="../public/Media/planaction2.webp" class="main__img"/>
        
        
        <div class="main__container">
            <img alt="maphoto" src="../public/Media/planaction.jpg" class="main__container__img"/>
            <div class="main__container__filesparts">
                <ul class="main__container__filesparts__list">
                    <li class="main__container__filesparts__list__element1">
                    <a class="main__container__filesparts__list__element1__link" href="../public/plan.pdf"> 
                            Plan d'action</a>
                    </li>
                        <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href=""> 
                            Lettre de motivation</a>
                        </li>
                        <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href="../public/Pdf/equivalence.pdf"> 
                            Equivalence des diplômes</a>
                        </li>
                        
                            <li><a class="main__container__filesparts__list__element1__link" href="../public/lettrederecommandation.pdf"> 
                            Lettre de recommandation</a></li>
                            <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href="../public/CV.pdf"> 
                            CV</a></li>
                  
                </ul>
                
            </div>
            
        </div>

        <div class="main__firstcontainer">
           <embed class="main__container__embed" height="1200px" width="1100px" src="../public/CV.pdf" > 
        </div>
        
    </main>

</template>
<style scoped>
  @import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');

.main{
    font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
        font-size: 25px;
        color: #666666;
         &__img{
               
        width: 100%;
        height: 12em;
        }
        &__firstcontainer{
        /* margin:60px; */
        padding-left: 100px;
        padding-top: 30px;
        padding-bottom: 30px;

        border:solid;
        border-color: rgb(230, 0, 126);
        border-radius: 20px;
        margin:60px;
        position:relative;
        overflow: hidden;
        &__embed
        {
            position: absolute;
            width:100%;
            height:100%;

            /* padding-left: 500px; */
            
        }
        }

        
        

    &__container{
        margin:60px;
        border:solid;
        border-color: rgb(230, 0, 126);
        border-radius: 20px;
        
        display: grid;
        grid-template-columns: 40% 40%;
        &__filesparts{
            &__list{
                padding-top: 50px;

            }
        }

    }
}

@media(max-width:900px)
{
    .main
    {
        font-size:20px;
        &__img{
               
               height: 10em;
               }
        
    
        &__firstcontainer
        {
        
        &__embed
        {
            height:200px;
            width:200px;
        }
        }
}
}
@media(max-width:750px)
{
    .main
    {
        &__img{
               
               height: 8em;
               }
    font-size: 10px;
   
}
}

</style>

