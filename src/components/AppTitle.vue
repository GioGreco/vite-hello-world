<template>
    <header>
        <h1>{{title}}</h1>
    </header>
</template>

<script>
    export default {
        name: 'AppTitle',
        data(){
            return{
                title: 'La mia prima App con Vite'
            }
        }
    }
</script>

<style lang="css" scoped>

header{
    display: flex;
    flex-direction: row;
    justify-content: center;
    align-items: center;
    padding: 20px;
    border-bottom: 1px solid white;
}

</style>