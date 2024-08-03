<template>
    <div class="Container">
        <h1>Swing by soon!</h1>
        <div class="textsContainer">
            <div class="contact">
                <h3>The Sunday Bite</h3>
                <p>123 Anywhere St., Any City, State, Country 12345</p>
            </div>
            <div class="contact">
                <h3>Email Address</h3>
                <p>hello@reallygreatsite.com</p>
            </div>
            <div class="contact">
                <h3>Phone Number</h3>
                <p>(123) 456 7890</p>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .Container{
        min-height: 100vh;
        width:100vw;
        background-color: #FF6347; 
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        font-family: 'Exo 2', sans-serif;
    }
    .textContainer{
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    h1{
        font-family: 'Bubble', sans-serif;
        font-size: 4.5em;
        margin: 0;
        font-weight: 200;
        color: black;
        height:fit-content;
    }

    h3{
        font-size: 1.5em;
        margin-bottom: 0;

    }

    p{
    }
</style>