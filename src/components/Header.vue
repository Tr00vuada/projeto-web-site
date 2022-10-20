<template>
    <header>
        <nav class="container">
            <a href="/">
                <img alt="Antifa !" 
                id="logo" src=
                "https://freeblmsigns.org/signs/antifa-three-arrows/antifa-three-arrows.svg">
            </a>

            <img alt="Abrir Menu" 
            id="menu-button" 
            src="https://raw.githubusercontent.com/william-costa/wdev-mock-site-resources/master/assets/images/menu.svg
">
        </nav>
    </header>
</template>

<script>
    export default{
        name: 'Header'
}
</script>

<style scoped>
    header{
        background-color: var(--color-background-nav);
        height: 60px;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: center;
    }
    
    #logo{
        width: 60px;
    }

    #menu-button{
        width: 30px;

    }
    
    nav{
        display: flex;
        justify-content: space-between;
    }

</style>
