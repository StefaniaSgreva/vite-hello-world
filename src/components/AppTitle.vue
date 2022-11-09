<template>

    <header>
        <h1>{{titol}}</h1>
    </header>

</template>
  
<script>
    export default {
        name: 'AppTitle',
        data(){
            return{
            titol: 'La mia prima app con Vite!'
            }
        },
    }
</script>

<style lang="css">
header{
    width: 100%;
    height: 90px;
    background-color: bisque;
    padding: 20px;
}
h1 {
    color: green;
    text-align: center;
    font-size: 38px;
}
</style>