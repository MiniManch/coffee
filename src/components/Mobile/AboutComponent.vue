<template >
    <div class="Container">
        <div class="imageContainer">
            <img src="images/about.jpg" alt="">
        </div>
        <div class="about">
            <h1 class="title">About <span>Pangu</span></h1>
            <p class="info">
                Since 2011, we have been crafting delicious and vibrant dishes. 
                Our mission is to delight your taste buds and bring joy with every bite. <br>
                Indulge in a flavorful meal today!
            </p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
    .Container{
        width:100vw;
        height:100vh;
        padding-top: 5vh;
        background-color: white;

        display: flex;
        flex-direction: column-reverse;
        justify-content: flex-end;
        align-items: center;
        gap:5vh;
    }

    .imageContainer{
        width:100vw;
        overflow-y: hidden;
    }
    .imageContainer > img{
        height:100%;
        width:100%;
        border-radius:50%;
    }
    .about{
        width:100%;
        display:flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap:5vh;
    }
    .about > h1{
        font-family: bubble, sans-serif;
        font-size:4em;
        height:fit-content;
        margin:0;
        font-weight: 200;
        color:black;
    }
    .about > h1 > span{
        color:#FF6347;
        font-size:1.2em;
    }
    .about > p{
        width:80%;
        font-family: "Exo 2", sans-serif;
        margin-top:0;
        margin-bottom: 0;
        font-weight: 300;
        font-size:1.2em; 
        color:black;
        text-align: left;
    }
</style>