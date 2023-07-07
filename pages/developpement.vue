<template>

    <main class="main">
        <img alt="maphoto" src="../public/Media/planaction2.webp" class="main__img"/>
        
        <div class="main__container">
            <img alt="maphoto" src="../public/Media/planaction.jpg" class="main__container__img"/>
            <div class="main__container__filesparts">
                <ul class="main__container__filesparts__list">
                    <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href="../public/Pdf/CV.pdf"> 
                            CV</a></li>
                            <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href="../public/Pdf/equivalence.pdf"> 
                            Equivalence des diplômes</a></li>
                            <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href=""> 
                            Lettre de motivation</a></li>
                            <li class="main__container__filesparts__list__element1">
                        <a class="main__container__filesparts__list__element1__link" href=""> 
                            Plan d'action</a></li>
                  
                </ul>
                
            </div>
            
        </div>
        <div class="main__container">
           <h1>Mon CV</h1> 
           <embed class="main__embed" src="../public/CV.pdf" height="800" width="800"> 
        </div>
        <!-- <div class="main__container">
           <h1>Ateliers</h1> 
           <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus viverra nulla eu mollis dignissim. Morbi quis tempus est, nec malesuada elit. Sed dapibus sodales elit nec hendrerit. 
                Vivamus vestibulum aliquam tortor eu vehicula. Cras finibus porta tellus, sit amet faucibus 
            
           </p>
</div> -->
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
        

    &__container{
        margin:60px;
        border:solid;
        border-color: rgb(230, 0, 126);
        border-radius: 20px;
        
        display: grid;
        grid-template-columns: 40% 40%;
        margin-bottom: 20px;
        &__filesparts{
            &__list{
                padding-top: 50px;

            }
        }

    }
}

</style>