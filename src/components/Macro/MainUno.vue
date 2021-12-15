<template>
    <main>
        <div class="container">
<Comics />
        </div>
    </main>
</template>



<script>

import Comics from "../Sections/Comics.vue";

export default {
    name: 'MainUno',
    components: {
    Comics    
    }
}
</script>



<style lang='scss' scoped>
@import "../../assets/style/partials/variables.scss";

main {
    background-color: black;
    text-align: center;


}
</style>