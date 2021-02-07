# Front-end Style Guide

## Layout

The designs were created to the following widths:

- Mobile: 375px
- Desktop: 1440px

## Colors

### Primary

- White: hsl(0, 0%, 100%)
- Black: hsl(0, 0%, 0%)
- Dark Gray: hsl(0, 0%, 55%)
- Very Dark Gray: hsl(0, 0%, 41%)

### Neutral

## Typography

### Body Copy

- Font size: 15px

### Fonts

- Family: [Alata](https://fonts.google.com/specimen/Alata)
- Weight: 400

- Family: [Josefin Sans](https://fonts.google.com/specimen/Alata)
- Weight: 300

## Icons

We provide the required social icons. But, if you prefer, you can use a font icon library. Some suggestions can be found below:

- [Font Awesome](https://fontawesome.com)
- [IcoMoon](https://icomoon.io)
- [Ionicons](https://ionicons.com)




About
  Careers
  Events
  Products
  Support

  Immersive experiences that deliver

  The leader in interactive VR

  Founded in 2011, Loopstudios has been producing world-class virtual reality 
  projects for some of the best companies around the globe. Our award-winning 
  creations have transformed businesses through digital experiences that bind 
  to their brand.

  Our creations

  See all

  Deep earth
  Night arcade
  Soccer team VR
  The grid
  From up above VR
  Pocket borealis
  The curiosity
  Make it fisheye

  About
  Careers
  Events
  Products
  Support

  © 2021 Loopstudios. All rights reserved.



  @import url('https://fonts.googleapis.com/css2?family=Alata&display=swap');

*{
    padding: 0;
    margin: 0;
    box-sizing: border-box;
    font-family: 'Alata', sans-serif;
}


html,body
{
    width: 100%;
    height: 100%;
    margin: 0px;
    padding: 0px;
    overflow-x: hidden; 
}

header{
    width: 100%;
    background-image: url(./images/desktop/image-hero.jpg);
    background-size: cover;
    padding-bottom: 100px;
}

nav{
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-top: 45px;

}


.menu ul{
    display: flex;
}

.menu li{
    margin-left: 30px;
    list-style: none;
}

.menu a{
    color: white;
    text-decoration: none;
}

.background-text{
    margin-left: 10%;
    margin-top: 150px;
    width: 50%;
    height: 300px;
    border: 1px solid white;
}
.background-text h1{
    width: 100%;
    font-size: 60px;
    font-weight: 300;
    color: white;
    padding:30px 0 0 100px;
}

section{
    width: 100%;
    padding-top: 200px;
}

.section1{
    width: 80%;
    margin: auto;
    display: flex;
    align-items: flex-end;
}

.text{
    right: 130px;
    padding: 80px 0 0 50px;
    background-color: white;
    position: relative;
}

.text p,
h1{
    width: 500px ;
}

.text p{
    margin-top: 30px;
}

.text h1{
    font-size: 40px;
}

.section2{
    width: 80%;
    margin: auto;
}

.headline{
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.headline h1{
    font-size: 40px;
}

.headline a{
    border: 1px solid black;
    padding: 10px 50px;
    text-decoration: none;
    color: black;
}

.works{
    margin-top: 100px;
    width: 100%;
}

.work1{
    width: 80%;
    flex: 1;
}

.work2{
    width:  80%;
    flex: 2;
}


footer{
    width: 100%;
    background-color: black;
    padding: 50px 0 50px 0;
    margin-top: 200px;
}

.menuBotton{
    width: 80%;
    margin: auto;
    display: flex;
    justify-content: space-between;
}

.reserved p{
    color: white;
}

.socials a{
    margin-left: 30px;
}

.socials{
    margin-left: 50px;
    margin-bottom: 20px;
}

.menu2 li{
    margin-left: 0;
    margin-right: 20px;
}

.logo2{
    margin-bottom: 20px;
}

@media screen and (max-width:1300px){
    .text{
        right: -40px;
    }
    .photoGlass img{
        width:150%;
    }
    .works h1{
        font-size: 1em;
    }
}
@media screen and (max-width:1241px){
    .background-text h1{
        font-size: 50px;
    }
}

@media screen and (max-width:1155px){
    
}