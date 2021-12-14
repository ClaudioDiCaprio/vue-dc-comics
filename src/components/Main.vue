<template>
    <main>
        <Hero/>
    </main>
</template>

<script>
import Hero from '../components/Hero.vue'
export default {
    name: 'Main',
    components: {
       Hero,
    }
}
</script>

<style scoped lang="scss">
main {
    background-color: #1c1c1c;
    // height: 120px;
    // color:white;
    // font-size: 15px;
    // position: relative;
    // line-height: 80px;
    // h2{
    //     position: absolute;
    //     left: 250px;
    // }
}
</style>