<template>
    <div id="jumbo">
        <div class="jumbo-inner-wrap">
            <h2>Lorem, ipsum.</h2>
            <div>Lorem, ipsum dolor sit amet consectetur adipisicing elit. Eum obcaecati at blanditiis, ad nemo odio incidunt et dicta fugiat in?</div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'Jumbotrone',
        data(){
            return{
                
            }
        }
    }
</script>

<style lang="css" scoped>
#jumbo{
    height: 500px;
    position: relative;
    background-image: url('https://artstore.house/wp-content/uploads//2019/10/huge-paintings.jpg');
    background-size: cover;
}

.jumbo-inner-wrap{
    position: absolute;
    width: 100%;
    left: 0;
    bottom: 0;
    padding: 30px;
    background-color: rgba(0, 0, 0, 0.5);
}
</style>