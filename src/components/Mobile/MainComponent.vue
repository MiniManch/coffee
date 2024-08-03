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
import Header from "@/components/Mobile/HeaderComponent.vue";
import About from "@/components/Mobile/AboutComponent.vue"
import Info from "@/components/Mobile/InfoComponent.vue"
import Menu from "@/components/Mobile/MenuComponent.vue"
import Customers from "@/components/Mobile/CustomersComponent.vue"
import Contact from "@/components/Mobile/ContactComponent.vue"

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