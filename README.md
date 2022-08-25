
# DESAFIO CARD - FLEX

Neste projeto tivemos que desenvolver um desafio feio pelo o Professor: Fábio, onde tivemos 
que criar um card, utilizando HTML e CSS.

## TECNOLOGIAS

HTML E CSS

## CARD
![image](https://user-images.githubusercontent.com/101206689/186695662-77c92be1-72bc-4550-99a4-1304954387a2.png)

## Autores

- [@Edivaldo2004](https://github.com/Edivaldo2004)



## Código HTML

```javascript
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/style.css"/>
    <link rel="stylesheet" href="css/media.css"/>
    <title>NFT Card</title>
</head>
<body>
    <center>
    <div class="container">
          <img src="img/image-equilibrium.jpg">
          <p class="text">Equilibrium #3429</p>
          <p class="first-text">Our Equilibrium collection promotes balance</p>
          <p class="second-text"> and calm.</p>
          <div class="img-text">
          <img src="img/icon-ethereum.svg" class="second-img"><h1 class="scar">0.041 ETH</h1>
          <img src="img/icon-clock.svg" class="third-img"><h1 class="m60">3 days left</h1>
          </div>
          <hr class="hr">
          <div class="creation">
          <img src="img/image-avatar.png" class="first-img"><h1 class="jules">Creation of<span>Jules Wyvern</span></h1>
        </div>
        </div>
    </div>
</center>
</body>
</html>
```
## Código Css

```javascript
body{
    background-color:  hsl(217, 54%, 11%);
}
.container{
    background-color: hsl(215, 32%, 27%);
    width: 350px;
    height: 600px;
    border-radius: 10px;
    margin-top:80px;
    box-shadow: 0 6px 16px rgba(28, 78, 216, 0.6);
}
.container:hover{
    transform: scale(1.1);
    transition-duration: 1s;
     font-family: "FontAwesome";
     font-style: normal;
     font-variant-caps: normal;
     font-variant-ligatures: normal;
     text-rendering: auto;
     box-shadow: 0 6px 16px rgba(216, 28, 131, 0.6);
}
img{
    width: 300px;
    height: 300px;
    margin-top: 25px;
    border-radius: 10px;
}
.text{
    color: white;
    font-size: 22px;
    margin-right: 122px;
    margin-top: 14px;
    font-weight: bold;
}
.text:hover{
    color: hsl(178, 100%, 50%);
}
.first-text{
    margin-right: 12px;
    margin-top: -8px;
    color: #a8cfdb;
}
.nop{
    margin-right: 18px;
}
.second-text{
    margin-right: 240px;
    margin-top: -12px;
    color: #a8cfdb;
}
.first-img{
    width: 40px;
    height: 40px;
    margin-right: 260px;
}
.second-img{
    width: 15px;
    height: 15px;
    margin-left: 23px;
    margin-top: 12px;
}
.img-text{
    display: flex;
}
.scar{
    font-size: 15px;
    margin-top: 12px;
    margin-left: 8px;
    color: hsl(178, 100%, 50%);
}
.m60{
    font-size: 15px;
    margin-top: 11px;
    margin-left: 5px;
    color: #a8cfdb;
}
.third-img{
    width: 15px;
    height: 15px;
    margin-left: 120px; 
    margin-top: 12px;
}
.hr{
    width: 298px;
    color: #a8cfdb;
}
.jules{
    color: #a8cfdb;
    font-size: 15px;
    margin-top: -32px;
    margin-left: 5px;
}
span{
    color: white;
    margin-left: 5px;
}
span:hover{
    color: hsl(178, 100%, 50%);
}
```