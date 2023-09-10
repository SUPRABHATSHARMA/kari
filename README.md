<!DOCTYPE html>
<html lang="en">
<head>
    <style>
body{

    margin: 0;
height: 100vh;
display: flex;
justify-content: center;
background-color: black;
overflow: hidden;


}
.container {
font-size: 10px;
width: 40em;
height: 40em;
position: relative;

}

.sun {
position: absolute;
top: 20em;
left: 40em;
width: 10em;
height: 10em;
background-color: yellow;
border-radius: 50%;
box-shadow: 0 0 3em white;
}

.earth{

position: absolute;
border-style: solid;
border-color: white transparent
transparent
transparent;
border-width: 0.1em 0.1em 0 0;
border-radius: 50%;

}
.earth {

top:10em;
left: 30em;
width: 30em;
height: 30em;
animation: orbit 36.5s Linear infinite;
}



.earth::before {

content: '';
position: absolute;
border-radius: 50%;
}


.earth:before {

top: 2.8em;
right: 2.8em;
width: 3em;
height: 3em;
background-color: aqua;








}
@keyframes orbit {
to {transform: rotate(360deg);

    
}



}








    </style>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <div class ="container"> </div>
    <div class ="sun"></div>
    <div class ="earth"></div>
    
</body>
</html>
