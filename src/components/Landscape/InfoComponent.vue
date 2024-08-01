<template >
    <div class="Container">
        <div class="textLeft">
            <h1>
                A Matter of  <br> <span>Taste</span>
            </h1>
            <p>
                There's a reason our regulars have been coming back for more. <br> Word of mouth has been our only advertisement - but happy mouths are the best ambassadors!
            </p>
        </div>
        <div class="textRight">
            <div class="para">
                <div class="num">1</div>
                <div class="content">
                    <h1>Fresh, Seasonal Ingredients</h1>
                    <p>Our menu follows the seasons, featuring the best local produce available</p>
                </div>
            </div>
            <div class="para">
                <div class="num">2</div>
                <div class="content">
                    <h1>Comfort Food, Elevated</h1>
                    <p>We have simple crowd-favorites on the menu - but we do them well. <br> Our flavors stand out, guaranteed.</p>
                </div>
            </div>
            <div class="para">
                <div class="num">3</div>
                <div class="content">
                    <h1>Better Beverages </h1>
                    <p>We're your cafe and barista in one, serving your favorite cuppa by sun-up, and your cocktail-of-choice by sundown.</p>
                </div>
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
        width:100vw;
        height:100vh;

        display: flex;
        justify-content: center;
        align-items: center;

        font-family: 'Exo 2', sans-serif;
    }
    .textLeft {
        width:30vw;
        display: flex;
        flex-direction: column;
    }
    .textLeft > h1{
        font-size:4em;
        color: black;
        font-weight: 400;
        text-align: left;
        width:fit-content;
        margin-bottom: 0;
    }
    .textLeft > h1 > span {
        color: #FF6347; 
    }
    .textLeft > * {
        overflow: hidden;
    }
    .textLeft > p {
        width:70%;
        font-size: 1.5em;
        text-align: left;
    }
    .textRight {
        background-color: #FF6347;
        border-radius: 25px;
        width:40vw;
        padding:3vh;
        padding-left: 5vh;
    }
    .para{
        display: flex;
        justify-content: center;
        align-items: center;
        gap:3vw;
    }
    .para > .num{
        font-size: 2em;
        font-weight: 400;
        color:white;

        background-color: black;
        border-radius: 60%;
        width:3vw;
        padding: 1vw;
    }
    .content{
        width:100%;
        text-align: left;
    }
</style>