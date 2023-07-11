<template>

    <!-- <div class="container">
        <p>Le code de l'erreur est: {{ error.statusCode }}</p>
        <p>Oups</p>
        <p>{{ error.message }}</p>
    </div>
    <img alt="img" src="/Media/error.jpg"/> -->
    
<img alt="image_banner" src="public/Media/error2.webp"  class="img"/> 
<h1 class="title">Ou<span class="title__colorletter">p</span>s!
</h1>
<h3 class="subtitle">Une erreur s'est produite</h3>
<h4 class="subtitle2">Le code de l'erreur est: {{ error.statusCode }}</h4>
<p class="msg">{{ error.message }}</p>
<NuxtLink class="link" alt="link" to="/">
Retour à la page d'accueil</NuxtLink>
</template>

    <script setup>
    defineProps(['error'])
    </script>



    <!-- <style lang="scss">
    img{
        width:100%;
    }
    .container{
        width: 400;
        height:400;
        background-color: aqua;
        font-family: 'Courier New', Courier, monospace;
        font-weight: bolder;
        text-align: center;
    }
    </style> -->

    
    
        
    <style lang="scss">
      @import url('https://fonts.googleapis.com/css2?family=Martian+Mono:wght@300&family=Righteous&display=swap');

       
      .img
        {
        width: 100%;
        height: 20em;
        padding-bottom: 20px;
        }
        *
        {
                  
        } 
    
        .msg
        {
            font-weight: 700;
            padding-bottom: 40px;
            padding-top: 20px;
            font-family: 'Martian Mono', monospace;
            font-family: 'Righteous', cursive;
            color: #666666;   
            text-align: center;
        } 
        .title
        {
            font-size: 80px;
            margin-top: 0;
            font-family: 'Martian Mono', monospace;
            font-family: 'Righteous', cursive;
            color: #666666;   
            text-align: center;
        &__colorletter
        {
            color: #DE047B;
          }
        } 
        .subtitle
        {
            font-weight: 400;
            font-size: 35px;
            font-family: 'Martian Mono', monospace;
            font-family: 'Righteous', cursive;
            color: #666666;   
            text-align: center;
    
        } 
        .subtitle2
        {
            font-weight: 700;
            font-size: 20px;
            padding-top: 20px;
            font-family: 'Martian Mono', monospace;
            font-family: 'Righteous', cursive;
            color: #666666;   
            text-align: center;

    
        } 
        .link
        {
        text-decoration: none;
        text-align: center;
        font-weight: 600;
        background-color:#4A4AF2;
        font-size: 18px;
        border-radius: 10px;
        color: white;
        padding: 10px 25px;
        border:solid;
        font-family: 'Martian Mono', monospace;
        font-family: 'Righteous', cursive;
        margin-left: auto;
        display:block;
        margin-right: auto;
        width: 400px;
    
        }
    
        
        .link:hover
        {
    
         font-weight: bold;
         color:#4A4AF2;
         background-color: white;
        }
    
        
        @media (max-width: 620px) 
        {
         .subtitle{
         font-size: 20px;
            
         }
         .title
        {
            
            font-size: 50px;
            
        } 
        
        .link
        {
           
        font-size: 15px;
        
        
        }
    
         }
        
    
    
    </style>
    
    
    
        

