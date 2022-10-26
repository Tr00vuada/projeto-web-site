<template>
    <footer>

    </footer>
</template>

<script>
    import api from '@/services/api.js'


    export default{
        name: 'Footer',
        data(){
            return{
                socialLinks: []
            }
        },
        mounted(){
            api.get('/social-links.json').then(response => {
                this.socialLinks = response.data;
            })
        }
    }
</script>

<style scoped>
    footer{
        height: 60px;
        width: 100%;
        background-color: var(--color-background-nav);
        display: flex;
        justify-content: center;
        align-items: center;
    }




</style>