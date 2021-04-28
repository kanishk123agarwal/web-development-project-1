<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PROJECT 1</title>
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@300&family=Source+Sans+Pro:ital,wght@1,200&display=swap" rel="stylesheet">
    <style>
        
*{
    box-sizing: border-box;
}
body{
    margin: 0px;
    padding: 0px;
    font:poppins;
}
#main{
    width: 100%;
    height: 70vh;
    position: relative;
}
nav{
    display: flex;
    justify-content: space-around;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    background-color: white;
    box-shadow: 5px 10px 30px rgba(0, 0, 0, 0.02);
    z-index:10;
} 
.logo img{
    height: 45px;
}
.menu{
    list-style: none;
    display: flex;
}
.menu li a{
    height: 40px;
    line-height: 50px;
    margin: 3px;
    padding: 0px 22px;
    display: flex;
    font-size: 1em;
    text-transform: uppercase;
    font-weight: 500;
    letter-spacing: 1px;
    color: rgb(221, 14, 14);
}
a{
    text-decoration: none;
}
.hey{
  color: brown;
  font-weight: 400;
  font-size: 20px;
  border-bottom: 2px solid yellow ;
}
/* .image{
    width: 500px;
    height: 500px;
}
.image img{
    width: 100%;
    height: 100%;
    object-fit: contain;
} */
.content{
    display: flex;
    width: 90%;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    left: 50%;
    right: 50%;
    transform: translate(-50%,-50%);
}
.text{
    width: 500px;

}
.text h1{
    font-size: 3em;
    text-decoration: underline;
    color: #1c3548;
    margin: 0px 0px 10px 0px;
    line-height: 60px;
}
.text p{
    color: blue;
    font-family: 'Oswald', sans-serif;
}
.resume-button{
    width: 190px;
    height: 44px;
    display: flex;
    justify-content: center;
    align-items: center;
    color: white;
    background-color: #1db096;
    border-radius: 20px;
    box-shadow:5px 10px 70px lightskyblue;
}
.resume-button:hover{
    background-color: grey;
    transition: all ease 0.2s;
}
.menu li a:hover{
    background-color:greenyellow;
    color: white;
    box-shadow:5px 10px 30px lightblue; 
}
.text h3{
    text-transform: uppercase;
}
.text strong{
    font-style: italic;
    color: black;
}
.text em{
    font-size: 2em;
}
.text .quotes{
    color: red;
    font-size: 25px;
}

    </style>
</head>
<body>
  <section id="main">
      <nav>
        <a href="#" class="logo">
            <img alt="Education Logo Vector Image, Education, Logo, Symbol PNG and Vector with  Transparent Background for Free Download | Education logo, Education logo  design, Logo design" class="n3VNCb" src="https://i.pinimg.com/736x/8e/f8/55/8ef855f46702650f9c4f529d537d7d97.jpg" data-noaft="1" jsname="HiaYvf" jsaction="load:XAeZkd;" style="width: 159px; height: 159px; margin: 0px;">
        </a>
        <span class="menu-space"></span>
        <ul class="menu">
            <li><a href="#">home</a></li>
            <li><a href="#">skills</a></li>
            <li><a href="#">Achivement</a></li>
            <li><a href="#">contact</a></li>
        </ul>
        <a href="#" class="hey">THE GREATEST SCIENTIST IN THE WORLD</a>
      </nav>
  </section>  
  <div class="content">
      <div class="image">

        <img alt="Dr. APJ Abdul Kalam Age, Biography, Wife, Death Cause, Facts &amp; More »  StarsUnfolded" class="n3VNCb" src="http://starsunfolded.com/wp-content/uploads/2017/08/APJ-Abdul-Kalam.jpg" data-noaft="1" jsname="HiaYvf" jsaction="load:XAeZkd;" style="width: 500px; height: 450px; margin: 0px;">
      </div>
      <div class="text">
          <h1>APJ ABDUL KALAM</h1>
          <h3>Introduction</h3>
          <p> <strong>A.P.J. Abdul Kalam, in full Avul Pakir Jainulabdeen Abdul Kalam, (born October 15, 1931, Rameswaram, India—died July 27, 2015, Shillong)</strong>, Indian scientist and politician who played a leading role in the development of India’s missile and nuclear weapons programs. <strong>He was president of India from 2002 to 2007.</strong></p>
          <p> In 1969 he moved to the Indian Space Research Organisation, where he was project director of the SLV-III, the first satellite launch vehicle that was both designed and produced in India. Rejoining DRDO in 1982, Kalam planned the program that produced a number of successful missiles, which helped earn him the nickname <strong>“Missile Man.”</strong></p>
         <p class="quotes">QUOTES</p>
         <em>"Dream, dream, dream. Dreams transform into thoughts and thoughts result in action."</em>
          <a href="#" class="resume-button">ABOUT APJ-Abdul-Kalam</a>
        </div>
  </div>  
</body>
</html>
