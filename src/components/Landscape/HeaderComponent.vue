<template >
    <div class="ContainerOfAll">
        <div class="text">
            <h1 class="title">Pangu Island Coffee</h1>
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
    .ContainerOfAll{
        height: 100vh;
        width: 100vw;

        display: flex;
        flex-direction: column;
        justify-content: space-between;
        align-items: center;
        gap:0;

        background-color: #FF6347;
    }

    .text{
        width:60%;
        height:30%;
        overflow-y: hidden;
    }
    .imageContainer{
        width:85%;
        height:65%;
        overflow: hidden;
    }
    .text > h1{
        font-family: bubble, sans-serif;
        font-size:8em;
        height:fit-content;
        margin:0;
        font-weight: 200;
        color:black;
    }
    .text > p{
        font-family: "Exo 2", sans-serif;
        font-size:2em;
        margin-top:0;
        font-weight: 200;
        color:black;
    }

    .imageContainer > img {
        width:100%;
        height:100%;
    }
    button{
        position: relative;
        top:0;
        z-index: 2;
    }

</style>