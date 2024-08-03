<template lang="">
    <div>
        <Header />
        <About />
        <Info />
        <Menu />
        <Customers />
        <Contact />
    </div>
</template>
<script>
import Header from "@/components/Landscape/HeaderComponent.vue";
import About from "@/components/Landscape/AboutComponent.vue"
import Info from "@/components/Landscape/InfoComponent.vue"
import Menu from "@/components/Landscape/MenuComponent.vue"
import Customers from "@/components/Landscape/CustomersComponent.vue"
import Contact from "@/components/Landscape/ContactComponent.vue"



export default {
    components:{
        Header,
        About,
        Info,
        Menu,
        Customers,
        Contact
    }
}

</script>
<style scoped>
    
</style>