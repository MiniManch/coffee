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
        background-color: white;

        display: flex;
        flex-direction: row;
        justify-content: center;
        align-items: center;
        gap:10vw;
        margin:0 5vw;
    }

    .imageContainer{
        width:30vw;
        overflow-y: hidden;
    }
    .imageContainer > img{
        height:100%;
        width:100%;
        border-radius:50%;
    }
    .about{
        width:40vw;
        display:flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
    }
    .about > h1{
        font-family: bubble, sans-serif;
        font-size:8em;
        height:fit-content;
        margin:0;
        font-weight: 200;
        color:black;
    }
    .about > h1 > span{
        color:#FF6347;
    }
    .about > p{
        width:60%;
        font-family: "Exo 2", sans-serif;
        margin-top:0;
        font-weight: 300;
        font-size:1.2em; 
        color:black;
        text-align: left;
    }
</style>