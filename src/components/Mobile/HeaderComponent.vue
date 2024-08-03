<template>
    <div class="ContainerOfAll">
        <div class="text">
            <h1 class="title">Pangu Coffee mobile</h1>
            <p class="under-title">Enjoy Food, Enjoy Life</p>
        </div>
        <div class="imageContainer">
            <img src="Images/header.jpg" alt="header">
            <button>BOOK A TABLE</button>
        </div>
    </div>
</template>

<script>
export default {
}
</script>

<style scoped>
    .ContainerOfAll {
        height: 100vh;
        width: 100vw;
        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        background-color: #FF6347;
    }

    .text {
        width: 100%;
        text-align: center;
        margin-top: 20px; /* Add some space from the top */
        overflow-y: hidden;
    }

    .imageContainer {
        width: 100%;
        height: 65%;
        position: relative; /* Positioning context for the button */
        overflow: hidden;
    }

    .text > h1 {
        font-family: 'Bubble', sans-serif;
        font-size: 5em;
        margin: 0;
        font-weight: 200;
        color: black;
    }

    .text > p {
        font-family: 'Exo 2', sans-serif;
        font-size: 2em;
        margin-top: 0;
        font-weight: 200;
        color: black;
    }

    .imageContainer > img {
        width: 100%;
        height: 100%;
        object-fit: cover; 
    }

    button {
        position: absolute; 
        bottom: 20px; 
        left: 50%; 
        transform: translateX(-50%); 
        width:70vw; 
        height: 10vh; 
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
        background-color: #FF6347;
        color: #fff;
    }
</style>
