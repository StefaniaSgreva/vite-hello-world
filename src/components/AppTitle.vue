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
    background-color: #e5e1e0;
    padding: 20px;
    box-shadow: 0 0 4px 0 rgba(0, 0, 0, 0.08), 0 2px 4px 0 rgba(0, 0, 0, 0.12);
}
h1 {
    color: #c97a59;
    text-align: center;
    font-size: 38px;
}
</style>