<template lang="">
    <div>
        <Header />
        <About />
        <Info />
    </div>
</template>
<script>
import Header from "@/components/Landscape/HeaderComponent.vue";
import About from "@/components/Landscape/AboutComponent.vue"
import Info from "@/components/Landscape/InfoComponent.vue"

export default {
    components:{
        Header,
        About,
        Info
    }
}

</script>
<style scoped>
    
</style>