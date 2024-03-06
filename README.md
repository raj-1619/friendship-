<!DOCTYPE html>
<html lang="en">
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>love Card</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Special+Elite&display=swap" rel="stylesheet">
    
    <!-- Google Font-->
    <link
      href="https://fonts.googleapis.com/css2?family=Poppins&display=swap"
      rel="stylesheet"
    />
    <!-- Stylesheet -->
    <link rel="stylesheet" href="march.css" />
  </head>
  <body>
   
    <div class="card">
      <div class="outside">
        <div class="front">
          <p>Happy Friendship Anniversary </p>
          <div class="Heart">
            
            <div class=""></div>
            <div class=""></div>
            
            <div>
            <img src="images/heart.png.png" alt="" class="type1">
            <img src="images/boy.png.png" alt="" class="type3">
           
            <img src="images/boy2.png.png" alt="" class="type5">
            <img src="images/girl.png.png" alt="" class="type8">
            <img src="images/girl2.png.png" alt="" class="type9">
            <img src="images/rebin.png.png" alt="" class="type10">
            <img src="images/by.png.png" alt="" class="type11"
            >
          </div>

            <div class=""></div>
            <div class=""></div>
          </div>
        </div>
        <div class="back"></div>
      </div>
      <div class="inside">
        <p><h5>Thank you for coming into my life 3 years ago today,you are very Special for me,
          you are most trustable person in my life,Thank you for understanding me 💝💖💌👩🏻‍🤝‍🧑🏻</h5></p>
        <div>
          <img src="images/butterfly.png.png" alt="" class="type13">
          <img src="images/flower.png.png" alt="" class="type14">
          <img src="images/cloud.png.png" alt="" class="type15">
          <img src="images/krinu.png.png" alt="" class="type12">
          <img src="images/rose.png.png" alt="" class="type2"
          
          >
        </div>
      </div>
    </div>
  </body>
  * {
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: "Special Elite", system-ui;
  body {
    background-color: #e61414;
  }
  
  
  .card {
    width: 640px;
    height: 400px;
    position: absolute;
    margin: auto;
    left: 0;
    right: 0;
    top: 0;
    bottom: 0;
    -webkit-perspective: 1200px;
    perspective: 1200px;
    transition: 1s;
  }
  .card:hover {
    transform: rotate(-5deg);
  }
  .card:hover .outside {
    transform: rotateY(-130deg);
  }
  .outside,
  .inside {
    height: 100%;
    width: 50%;
    position: absolute;
    left: 50.1%;
  }
  .inside {
    background: linear-gradient(to right, #e7e7e7, #ffffff 30%);
    line-height: 3;
    padding: 0 20px;
    text-align: center;
    display: flex;
    flex-direction: column;
    justify-content: space-around;
    align-items: center;
    left: 50%;
  }
  .outside {
    -webkit-transform-style: preserve-3d;
    transform-style: preserve-3d;
    z-index: 1;
    transform-origin: left;
    transition: 2s;
    cursor: pointer;
  }
  .front,
  .back {
    height: 100%;
    width: 100%;
    position: absolute;
    -webkit-backface-visibility: hidden;
    backface-visibility: hidden;
    transform: rotateX(0deg);
  }
  .front {
    background-color: #ffffff;
  }
  .back {
    transform: rotateY(180deg);
    background: linear-gradient(to left, #e7e7e7, #ffffff 30%);
  }
  .cake {
    width: 100%;
    position: absolute;
    bottom: 30px;
  }
  .special-elite-regular {
    font-family: "Special Elite", system-ui;
    font-weight: 400;
    font-style: normal;
  }
  .top-layer,
  .middle-layer,
  .bottom-layer {
    height: 80px;
    width: 240px;
    background-repeat: repeat;
    background-size: 60px 100px;
    background-position: 28px 0;
    background-image: linear-gradient(
        transparent 50px,
        #fedbab 50px,
        #fedbab 60px,
        transparent 60px
      ),
      radial-gradient(circle at 30px 5px, #994c10 30px, #fcbf29 31px);
    border-radius: 10px 10px 0 0;
    position: relative;
    margin: auto;
  }
  .middle-layer {
    transform: scale(0.85);
    top: 6px;
  }
  .top-layer {
    transform: scale(0.7);
    top: 26px;
  }
  .candle {
    height: 45px;
    width: 15px;
    background: repeating-linear-gradient(
      45deg,
      #fd3018 0,
      #fd3018 5px,
      #ffa89e 5px,
      #ffa89e 10px
    );
    position: absolute;
    margin: auto;
    left: 0;
    right: 0;
    bottom: 202px;
  }
  .candle:before {
    content: "";
    position: absolute;
    height: 16px;
    width: 16px;
    background-color: #ffa500;
    border-radius: 0 50% 50% 50%;
    bottom: 48px;
    transform: rotate(45deg);
    left: -1px;
  }
  .outside p {
    font-size: 23px;
    text-transform: uppercase;
    margin-top: 30px;
    text-align: center;
    letter-spacing: 6px;
    color: #000046;
  }
  .inside h1 {
    font-size: 120px;
    line-height: 120px;
  }
  .type1 {
    width: 40%;
    position: absolute;
    top: 55%;
    left: 49%;
    transform: translate(-50%,-50%);
  }
  .type2 {
    width: 40%;
    position: absolute;
    top: 80%;
    left: 49%;
    transform: translate(-50%,-50%);

  }
  .type3 {
    width: 20%;
    position: absolute;
    top: 37%;
    left: 57%;
    transform: translate(-50%,-50%);
  }
  .type10 {
    width: 100%;
    position: absolute;
    top: 84%;
    left: 50%;
    transform: translate(-50%,-50%);
  }
  
  .type5 {
    width: 20%;
    position: absolute;
    top: 42%;
    left: 87%;
    transform: translate(-50%,-50%);
  }
  
  .type8 {
    width: 20%;
    position: absolute;
    top: 35%;
    left: 40%;
    transform: translate(-50%,-50%);
  }
  .type9 {
    width: 20%;
    position: absolute;
    top: 42%;
    left: 15%;
    transform: translate(-50%,-50%);
  }
  .type11 {
    width: 20%;
    position: absolute;
    top: 75%;
    left: 14%;
    transform: translate(-50%,-50%);
  }
  .type12 {
    width: 50%;
    position: absolute;
    top: 73%;
    left: 87%;
    transform: translate(-50%,-50%);
  }
  .type13 {
    width: 30%;
    position: absolute;
    top: 13%;
    left: 85%;
    transform: translate(-50%,-50%);
  }
  .type14 {
    width: 30%;
    position: absolute;
    top: 69%;
    left: 17%;
    transform: translate(-50%,-50%);
  }
  .type15 {
    width: 35%;
    position: absolute;
    top: 13%;
    left: 50%;
    transform: translate(-50%,-50%);
  }
}
</html>
