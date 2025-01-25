<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Animation Home Work</title>
    <link rel="stylesheet" href="AnimationHW1(2)/AnimationHW1(2).css">
    <style> *{
        margin:0px;
        padding:0px;
    }
    .main{
        height:350px;
        width:1500px;
        border:8px solid black;
        position:relative;
        margin-top:20px;
        margin-left:2px;
    }
    
    
    .one{
        background: black;
        height:100px;
        width:100px;
        border-radius: 60%;
        position:absolute;
        top:5px;
        left:5px;
        animation-name: bouncing;
        animation-duration: 8s;
        animation-delay: 1s;
        animation-iteration-count: infinite;
    }
    @keyframes bouncing{
        0% {
            top:0px;
            left:0px;
            background-color: black;
            transform:scale(1);
        }
        10%{
         top:270px;
         left:150px;  
         background-color: blue; 
         transform:scale(0.75);
        }
        20%{
            top:-30px;
            left:300px;
            background-color: brown;
            transform: scale(0.5);
        }
        30%{
            top:290px;
            left:450px;
            background-color: green;
            transform: scale(0.25);
        }
        40%{
            top:-30px;
            left:600px;
            background-color: yellow;
            transform: scale(0.5);
        }
        50%{
            top:266px;
            left:750px;
            background-color: chocolate;
            transform: scale(0.75);
        }
        60%{
            top:-4px;
            left:900px;
            background-color: hotpink;
            transform: scale(1);
        }
        70%{
            top:265px;
            left:1050px;
            background-color: peru;
            transform: scale(0.75);
        }
        80%{
            top:-30px;
            left:1200px;
            background-color: brown;
            transform: scale(0.5);
        }
        90%{
            top:285px;
            left:1350px;
            background-color: gold;
            transform: scale(0.25);
        }
        100%{
            top:0px;
            left:1420px;
            background-color: navy;
            transform: scale(0.75);
        }
        
    }
    </style>
</head>
<body>
    <div class="main">
        <div class="one"></div>
    </div>
</body>
</html>
