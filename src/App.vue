<template>
    <Calculadora/>
</template>

<script>
import Calculadora from './main/CalcVue.vue'
export default {
  components:{Calculadora}
}
</script>

<style>
@font-face {
    font-family: 'RobotoMono';
    src: url("./fonts/RobotoMono.ttf");
}

*{
    font-family: 'RobotoMono', 'monospace';
}

body{
    margin: 0;
}

#app{
    display: flex;
    flex-direction: column;
    height: 100vh;
    justify-content: center;
    align-items: center;
    text-align: center;

    color: white;
    background: linear-gradient(to right, rgb(83,105,118), rgb(41,46,73));
}

</style>