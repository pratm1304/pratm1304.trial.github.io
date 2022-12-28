# Travel-

<!DOCTYPE html>
<html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta http-equiv="X-UA-Compatible" content="IE=edge">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <script src="https://kit.fontawesome.com/5011490c37.js" crossorigin="anonymous"></script>
        
    <title>Document</title>
    
    <style type="text/css">
       
        *{
            margin: 0;
            padding: 0;
            font-family: sans-serif;
            background-image: linear-gradient(45deg,#FFA5C6,rgb(62, 197, 255));
            
            
        }
        .container {
            
            position: relative;
            width: 1200px;
            height: 300px;
            margin: 50px auto;
            margin-left: 150px;
            background-image: linear-gradient(45deg,#FFA5C6,rgb(62, 197, 255));
        }

        .box {

            position: relative;
            width: calc(380px - 30px);
            height: calc(300px - 30px);
            background-image:linear-gradient(45deg,rgb(62, 197, 255),white);
            float: left;
            margin: 15px;
            box-sizing: border-box;
            overflow: hidden;
            border-radius: 10px;

        }

        .icon {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: white;
            background: #FFA5C6;
            
            transition: 1s;
            z-index: 1;

    
        }

        :hover.icon {
            
            top: 90px;
            left: calc(50% - 50px);
            width: 100px;
            height: 100px;
            border-radius: 100%;
            background-image: linear-gradient(45deg,#FFA5C6,rgb(62, 197, 255));
        }

        .icon.fa {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 200px;
            transition: 1s;
            
            

        }

        :hover.icon.fa {
            font-size: 1000px;
        }

        .content {
            position: absolute;
            top: ;
            left: 6%;
            height: calc(100% - 100px);
            text-align: center;
            padding: 100px;
            background-image: linear-gradient(45deg,white,rgb(62, 197, 255));
            color: white;
            box-sizing: border-box;
            opacity: 0;
            

        }

        :hover.content.h1 {
            top: 100px;
            opacity: 1;
        }

        .content.h1 {
            margin: 0;
            padding: 0;
            font-size: 50px;
            font-style:italic ;
            
        }








        .box2 {

            position: relative;
            width: calc(380px - 30px);
            height: calc(300px - 30px);
            background: linear-gradient(45deg,#FFA5C6,white);
            float: left;
            margin: 15px;
            box-sizing: border-box;
            overflow: hidden;
            border-radius: 10px;
        }


        .icon2 {
            
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            color: white;
            background: #79C9FA;
            transition: 1s;
            z-index: 1;

    
        }

        :hover.icon2 {
            
            top: 80px;
            left: calc(50% - 50px);
            width: 100px;
            height: 100px;
            border-radius: 100%;
            background-image: linear-gradient(45deg,#FFA5C6,rgb(62, 197, 255));
        }

        .icon2.fa {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 200px;
            transition: 1s;
            color:#FFA5C6;

        }

        :hover.icon2.fa {
            font-size: 1000px;
        }

        .content2 {
            position: absolute;
            top: 100px;
            left: 12%;
            height: calc(100% - 100px);
            text-align: center;
            padding: 100px;
            background-image: linear-gradient(45deg,white,#FFA5C6);
            color: white;
            box-sizing: border-box;
            

        }

        .content2.h1 {
            margin: 0;
            padding: 0;
            font-size: 50px;
            font-style:italic ;
        }







        .box3 {

            position: relative;
            width: calc(380px - 30px);
            height: calc(300px - 30px);
            background:  #79C9FA;
            float: left;
            margin: 15px;
            box-sizing: border-box;
            overflow: hidden;
            border-radius: 10px;
            }


        .icon3 {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: #FFA5C6;
            transition: 1s;
            z-index: 1;


            }

        :hover.icon3 {

            top: 80px;
            left: calc(50% - 50px);
            width: 100px;
            height: 100px;
            border-radius: 100%;
            
            }

        .icon3.fa {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            font-size: 200px;
            transition: 1s;
           

            }

        :hover.icon3.fa {
            font-size: 1000px;
            }

        .content3 {
            position: absolute;
            top: 100px;
            left: 8%;
            height: calc(100% - 100px);
            text-align: center;
            padding: 100px;
            box-sizing: border-box;


            }

        .content3.h1 {
            margin: 0;
            padding: 0;
            color: black;
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
            color: #FFA5C6;
            text-align: center;
            padding: 100px;
            
        }

        .box4 {

            position: relative;
            width: 370px;
            height: 370px;
            background:  white;
            float: left;
            box-sizing: border-box;
            overflow: hidden;
            border-radius: 10px;
            margin-left: 150px;
        
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
        


    </style>
              
</head>

  
<div class="container">
    
    <div class ="box">
        <div class="icon">
            <br />
            &nbsp;&nbsp;&nbsp;<i class="fa-solid fa-plane-up fa-4x" area-hidden="true"></i>
           
        </div>
        <div class="content">
            <h1>flight</h1>

        </div>
        
    </div>





    <div class ="box2">
        <div class="icon2">
            <br />
            &nbsp;&nbsp;&nbsp;&nbsp;<i class="fa-solid fa-bus fa-4x"></i>
        </div>
        <div class="content2">
            <h1>BUS</h1>


        </div>
        
    </div>

    <div class ="box3">
        <div class="icon3">
            <br />
            &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<i class="fa-solid fa-train fa-4x"></i>
        </div>
        <div class="content3">
            <h1>TRAIN</h1>
        </div>
    </div>

    <div class="bg-gradient">

    </div>
</div>

<div class="container2">

    <div class ="box4"> 
        <img src="new.png" class="img">  
    </div>

    
    <div class="rect">

        <h2>rectangle</h2>
    </div>
    
    

</div>

</body>
</html>
