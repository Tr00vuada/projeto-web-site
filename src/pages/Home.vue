<template>
   <main>
     <div class="text-top">
        <b>Clique no olho pra dar uma espiada !</b>
     </div>
     <a href="https://github.com/Tr00vuada/Punk-Frog" target="blank">
        <img alt="Confira o repositório do game !" id="punk-frog" :src="require('file:///C:/Users/gabri/Downloads/medical-medicine-health-15-svgrepo-com.svg')">  
     </a>  
   </main>
</template>

<script>
    export default{
        name: 'Home',
    }
</script>

<style scoped>
    main{
        background-color: var(--color-background-home);
        justify-content: center;
        align-items: center;   
    }

    .text-top{
        color: var(--color-text-light);
        font-size: 22px;
        margin-bottom: -70px;
    }

    #punk-frog{
        width: 340px;
    }
    
    @media(min-width: 700px){
        #punk-frog{
            width: 380px;
        }
    }

</style>