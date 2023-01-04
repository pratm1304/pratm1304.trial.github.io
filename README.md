<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <script
      src="https://kit.fontawesome.com/5011490c37.js"
      crossorigin="anonymous"
    ></script>

    <title>Document</title>

    <style type="text/css">
      * {
        margin: 0;
        padding: 0;
        font-family: sans-serif;
      }

      .body-container {
        background-image: linear-gradient(45deg, #ffa5c6, rgb(62, 197, 255));
      }

      .container {
        position: relative;
        width: 1200px;
        height: 300px;
        margin: 50px auto;
        margin-left: 150px;
        background-image: linear-gradient(45deg, #ffa5c6, rgb(62, 197, 255));
      }

      .box {
        position: relative;
        width: calc(380px - 30px);
        height: calc(300px - 30px);
        background-image: linear-gradient(45deg, rgb(62, 197, 255), white);
        float: left;
        margin: 15px;
        box-sizing: border-box;
        overflow: hidden;
        border-radius: 10px;
        transition: 1s;
      }

      :hover.box {
        transform: scale(1.2);
        z-index: 1;
      }

      .icon {
        position: absolute;
        width: 100%;
        height: 100%;
        color: white;
        background-image: linear-gradient(45deg, #ffa5c6, white);
        transition: 1s;
        z-index: 1;
      }

      .content {
        text-align: center;
        padding: 10px;
        font-size: 20px;
        color: white;
      }

      .content.h1 {
        margin: 0;
        padding: 0;
        font-size: 50px;
        font-style: italic;
      }

      .box2 {
        position: relative;
        width: calc(380px - 30px);
        height: calc(300px - 30px);
        background: linear-gradient(45deg, #ffa5c6, white);
        float: left;
        margin: 15px;
        box-sizing: border-box;
        overflow: hidden;
        border-radius: 10px;
        transition: 1s;
      }

      :hover.box2 {
        transform: scale(1.2);
        z-index: 1;
      }

      .icon2 {
        position: absolute;
        width: 100%;
        height: 100%;
        color: white;
        background-image: linear-gradient(45deg, rgb(62, 197, 255), white);
        transition: 1s;
        z-index: 1;
      }

      .content2 {
        text-align: center;
        padding: 10px;
        color: white;
        font-size: 20px;
      }

      .content2.h1 {
        margin: 0;
        padding: 0;
        font-size: 50px;
        font-style: italic;
      }

      .box3 {
        position: relative;
        width: calc(380px - 30px);
        height: calc(300px - 30px);
        background: #79c9fa;
        float: left;
        margin: 15px;
        box-sizing: border-box;
        overflow: hidden;
        border-radius: 10px;
        transition: 1s;
      }

      :hover.box3 {
        transform: scale(1.2);
        z-index: 1;
      }

      .icon3 {
        position: absolute;
        width: 100%;
        height: 100%;
        background-image: linear-gradient(45deg, #ffa5c6, white);
        transition: 1s;
        z-index: 1;
        color: white;
      }

      .content3 {
        text-align: center;
        font-size: 20px;
        padding: 10px;
        color: white;
      }

      .content3.h1 {
        margin: 0;
        padding: 0;
        font-size: 50px;
        font-style: italic;
      }

      .rect {
        position: relative;
        height: 170px;
        width: 520px;
        margin: 50px;
        margin-left: 550px;
        background: #ffffff;
        background-image: linear-gradient(white, pink);
        text-align: center;
        padding: 100px;
      }

      .box4 {
        position: relative;
        width: 370px;
        height: 370px;
        background: white;
        float: left;
        box-sizing: border-box;
        overflow: hidden;
        border-radius: 10px;
        margin-left: 160px;
      }

      .img {
        background-position: center;
        display: block;
        width: 370px;
        height: 370px;
        background-size: cover;
        transition: 1s;
      }

      .img:hover {
        transform: scale(1.2);
      }

      .main {
        width: 100%;
        min-height: 50px auto 100px;
        text-align: center;
        position: relative;
        cursor: pointer;
        margin-bottom: 20%;
      }

      .service {
        background: white;
        padding: 30px;
        border-radius: 10px;
        position: absolute;
        bottom: 0;
        box-shadow: 0 0 20px -15px black;
        z-index: 1;
        margin-left: 20%;
        transition: 1s;
      }

      .service:hover {
        transform: scale(1.2);
      }

      .service-logo {
        width: 130px;
        height: 130px;
        background: white;
        border-radius: 50%;
        border: 10px solid pink;
        margin: -90px auto 0;
      }

      .service.h2 {
      }
    </style>
  </head>

  <body class="body-container" link="white" vlink="white" alink="white">
    <div class="container">
      <div class="box">
        <div class="icon">
          <br />
          <br />
          <center>
            <i class="fa-solid fa-plane-up fa-10x" area-hidden="true"></i>
          </center>
          <div class="content">
            <a href="youtube.com" style="text-decoration: none"
              ><h1>FLIGHT</h1></a
            >
          </div>
        </div>
      </div>

      <div class="box2">
        <div class="icon2">
          <br />
          <br />
          <center><i class="fa-solid fa-bus fa-10x"></i></center>
          <div class="content2">
            <a href="youtube.com" style="text-decoration: none"><h1>BUS</h1></a>
          </div>
        </div>
      </div>

      <div class="box3">
        <div class="icon3">
          <br />
          <br />
          <center><i class="fa-solid fa-train fa-10x"></i></center>
          <div class="content3">
            <a href="youtube.com" style="text-decoration: none"
              ><h1>TRAIN</h1></a
            >
          </div>
        </div>
      </div>
    </div>

    <div class="container2">
      <div class="box4">
        <img src="new.png" class="img" />
      </div>

      <div class="rect">
        <h2>rectangle</h2>
      </div>
    </div>

    <div class="container3">
      <div class="row">
        <div class="colm">
          <div class="main">
            <div class="service">
              <div class="service-logo">
                <i class="fa-solid fa-phone fa-6x"></i>
              </div>
              <h2>CALL US</h2>
              <p>
                +12 78745893733 <br />
                +12 746987846438 <br />
                +12 768834262984
              </p>
            </div>

            <div class="shadow-1"></div>
            <div class="shadow-2"></div>
          </div>
        </div>
        <div class="colm"></div>
        <div class="colm"></div>
      </div>
    </div>
  </body>
</html>
