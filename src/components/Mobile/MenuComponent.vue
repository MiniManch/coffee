<template lang="">
    <div class="Container">
        <div class="text">
            <h1>Our Menu</h1>
        </div>
        <div class="imagesContainer">
            <div class="imageCard">
                <div class='image image_3'></div>
                <div class="imageText">
                    <h3>Gourmet Burgers</h3>
                    <p>
                        Juicy and savory, we offer endless toppings like cheese, bacon and way too many sauces.
                    </p>
                </div>
            </div>
            <div class="imageCard">
                <div class='image image_2'></div>
                <div class="imageText">
                    <h3>Açaí</h3>
                    <p>
                        Our bowls are a delicious way to enjoy a blend of açaí berries, granola, and assorted fresh fruits.
                    </p>
                </div>
            </div>
            <div class="imageCard">
                <div class='image image_1 '></div>
                <div class="imageText">
                    <h3> Thirst Quenchers</h3>
                    <p>
                        Fluffy and golden, a breakfast favorite that can be topped with everything.
                    </p>
                </div>
            </div>
        </div>
        <button>VIEW FULL MENU</button>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .Container{
        min-height:100vh;
        max-height: fit-content;
        width:100vw;
        margin-top: 10vh;
        padding-bottom: 10vh;
        padding-top: 5vh;
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
        background-color: #FF6347;
        font-family: 'Exo 2', sans-serif;
    }

    .text{
        width:100vw;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    .imageText{
        display: flex;
        justify-content: center;
        align-items: center;
        flex-direction: column;
    }
    h1{
        font-family: 'Bubble', sans-serif;
        font-size: 5em;
        margin: 0;
        margin-bottom: 5vh;
        font-weight: 200;
        color: black;
    }
    p{
        width:80%;
        margin-top: 0;
    }
    h3{
        font-size:1.5em;
        margin-bottom: 1vh;
        margin-top: 1vh;
    }
    button {
        width:70vw; 
        height: 10vh; 
        margin-top: 5vh;
        background-color: #fff; 
        color: #FF6347; 
        border: none;
        border-radius: 25px; 
        font-size: 2em;
        font-family: 'Exo 2', sans-serif;
        cursor: pointer;
        z-index: 1; 
        transition: background-color 0.3s, color 0.3s;
        padding:0 3vh;
    }

    button:focus {
        background-color: black;
    }
    .imagesContainer{
        width:80vw;
        display: flex;
        flex-direction: column;
        gap: 10vw;
    }
    .imageCard{
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        width:100%;
        border-radius: 25px;
    }
    .image{
        height:40vh;
        width:100%;
        background-repeat: no-repeat;
        background-position: center;
        

    }
    .imageText{
        background-color: white;
        width:100%;
        height:20vh;

        display: flex;
        flex-direction: column;
        justify-content: flex-start;
    }
    .image_1{
        background-image: url('../../../public/Images/menu/menu_1s.jpg');
    }
    .image_2{
        background-image: url('../../../public/Images/menu/menu_2s.jpg');
    }
    .image_3{
        background-image: url('../../../public/Images/menu/menu_3s.jpg');
    }
    
</style>