<template>
    <div class="Container">
        <h1>From Our <span>Community</span></h1>
        <div class="customersContainer">
            <div class="customerCard">
                <div class="flower-img image_1"></div>
                <div class="cardText">
                    <h3>Brock, new in town</h3>
                    <p>I stumbled upon <span>Pangu</span> when I was exploring my new neighborhood. Everyone was so friendly, and the food was delish! Will be back.</p>
                </div>
            </div>
            <div class="customerCard">
                <div class="flower-img image_2"></div>
                <div class="cardText">
                    <h3>Steffi, lives around the corner</h3>
                    <p><span>Pangu</span> is a huge part of my life. The staff feels like family, and they know just how I like my coffee - and my gourmet burger fix!</p>
                </div>
            </div>
            <div class="customerCard">
                <div class="flower-img image_3"></div>
                <div class="cardText">
                    <h3>Mara, regular since 2015</h3>
                    <p><span>Pangu</span> is my neighborhood cafe, hangout spot, and bar all in one and nearby! Comfort food in a comforting atmosphere - need I say more?</p>
                </div>
            </div>
        </div>
    </div>
  </template>
  
  <script>
  export default {
    name: 'FlowerImage',
  }
  </script>
  
  <style lang="scss" scoped>
  @import '/src/assets/MobileCustomers.scss';
  .Container{
    min-height:100vh;
    width: 100vw;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
    font-family: 'Exo 2', sans-serif;
    padding-bottom: 5vh;
    padding-top: 5vh;
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
    margin-top: 0;
    margin-bottom:1vh;
    font-size:1.5em;
  }
  p{
    margin-top: 0;
    font-size: 1.2em;
  }
  p>span,h3>span{
    font-family: 'Bubble', sans-serif;
    font-weight: 100;
    font-size: 1.5em;
  }
  span{
    color: #FF6347; 
  }

  .customersContainer{
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    gap:9vw;
  }
  .customerCard{
    width:80vw;
  }
  .cardText{
    width:100%;
    height:25vh;
    display: flex;
    flex-direction: column;
    justify-content: flex-start;
  }
  .flower-img {
    height: auto;
    width:100%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
  }
  .image_1{
    background-image: url('../../../public/Images/customers/customer_1.jpg');
  }
  .image_2{
    background-image: url('../../../public/Images/customers/customer_3.jpg');
  }
  .image_3{
    background-image: url('../../../public/Images/customers/customer_2.jpg');
  }
  </style>
  