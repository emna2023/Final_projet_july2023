<template>

    <main class="main">
        <div class="main__container">
            <img alt="maphoto" src="../public/Media/im2.jpg" class="main__container__img"/>
            <div class="main__container__filesparts">
                <ul class="main__container__filesparts__list">
                    <li class="main__container__filesparts__list__element1">
                        <NuxtLink class="main__container__filesparts__list__element1__link" to=""> 
                            CV</NuxtLink></li>
                            <li class="main__container__filesparts__list__element1">
                        <NuxtLink class="main__container__filesparts__list__element1__link" to=""> 
                            Lettre de motivation</NuxtLink></li>
                            <li class="main__container__filesparts__list__element1">
                        <NuxtLink class="main__container__filesparts__list__element1__link" to=""> 
                            Plan d'action</NuxtLink></li>
                  
                </ul>
                
            </div>
            
        </div>
        <div class="main__container">
           <h1>Ateliers</h1> 
           <p>
            Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus viverra nulla eu mollis dignissim. Morbi quis tempus est, nec malesuada elit. Sed dapibus sodales elit nec hendrerit. 
                Vivamus vestibulum aliquam tortor eu vehicula. Cras finibus porta tellus, sit amet faucibus 
            
           </p>
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