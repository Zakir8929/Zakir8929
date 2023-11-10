- 👋 Hi, I’m @Zakir8929
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Zakir8929/Zakir8929 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <link rel="icon" href="images/213432536.jpg">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="smith portfolio">
    <link rel="stylesheet" href="http://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.14.0/css/all.min.css">
    <link href="https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css" rel="stylesheet">
    <title>Portfolio</title>

    <style>

*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: sans-serif;
    list-style: none;
    text-decoration: none;
    scroll-behavior: smooth;
}
body{
    background: rgb(32, 33, 33);
    color: white;
}

/* --- header-----*/
header{
    position: fixed;
    top: 0;
    right: 0;
    width: 100%;
    z-index: 1000;
    display: flex;
    align-items: center;
    justify-content: space-between;
    padding: 20px 14%;
    background: transparent;
    transition: all .50s;
}
header.sticky{
    background: #09c5eb;
    box-shadow: 0 .1rem 1rem rgb(red, green, blue);
    padding: 16px 16%;
}
.logo{
    color: white;
    font-size: 25px;
    font-weight: 600;
    text-decoration: none;
}
 span{
    color: rgb(28, 239, 247);
}
.navlist{
    display: flex;
}
.navlist a{
    color: whitesmoke;
    font-size: 20px;
    font-weight: 500;
    margin-left: 40px;
    transition: all .50s;
    position: relative;
    transition: .2s;
}
.navlist a::before{
    content: '';
    width: 0;
    height: 3px;
    position: absolute;
    background: rgb(8, 233, 249);
    left: 0;
    bottom: -7px;
    transition: .2s;
}
.navlist a:hover::before{
    width: 100%;
}
.navlist a:hover{
    color: rgb(1, 227, 235);
    text-shadow: 3px 3px 20px chartreuse , -2px 1px 30px crimson;
}
#menu-icon{
    color: white;
    font-size: 30px;
    z-index: 10001;
    cursor: pointer;
    display: none;
}
.h-btn{
    display: inline-block;
    padding: 6px 26px;
    background: black;
    color: antiquewhite;
    border: 2px solid aqua;
    border-radius: 5px;
    font-weight: 600;
    transition: all .50s;
  
}

.h-btn:hover{
    color: aliceblue;
    background: aqua;
    box-shadow: 0 0 20px aqua;
    transform: scale(1.1);
}


/*----hero---dddddddddddddddddddddddddddddddddddddddddddddddddddddddddddd-*/

section{
    padding: 110px 14% 90px;
}
.hero{
width: 100%;
height: 100vh;
background: url(imhsa.jpg);
background-position: top right;
background-size: cover;
display: flex;
align-items: center;
justify-content: flex-start;
}
.content h4{
    font-size: 1.5rem;
}
.content h1{
    font-size: 36px;
    font-weight: 900;
    margin: 10px 0 10px;
    line-height: 1.2;
}
.content p{
font-size: 18px;
font-weight: 500;
width: 600px;
max-width: 100%;
color: aliceblue;
line-height: 20px;
}
 .icon{
    display: flex;
    margin-bottom: 40px;
    margin-top: 10px;
 }
.icon a{
    height: 40px;
    width: 40px;
   
    margin: 0 8px;
    font-size: 20px;
    border-radius: 50%;
    text-align: center;
    line-height: 40px;
   color: #fff;
    text-decoration: none;
    transition: .2s;
    
}
.icon a:nth-child(1){
    background: #8178e7;
}
.icon a:nth-child(1):hover{
    color: #49a9ed;
    background: #fff;
    box-shadow: 0 0 20px aqua;
    transform: scale(1.1);
}
.icon a:nth-child(2){
    background: #f45956;
}
.icon a:nth-child(2):hover{
    color: #ff3f04;
    background: #fff;
    box-shadow: 0 0 20px aqua;
    transform: scale(1.1);
}
.icon a:nth-child(3){
    background: #045efb;
}
.icon a:nth-child(3):hover{
    color: #49a9ed;
    background: #fff;
    box-shadow: 0 0 20px aqua;
    transform: scale(1.1);
}
.icon a:nth-child(4){
    background: #71c3d7;
}
.icon a:nth-child(4):hover{
    color: #0393f9;
    background: #fff;
    box-shadow: 0 0 20px aqua;
    transform: scale(1.1);
}
.icon a:nth-child(5){
    background: #eb2009;
}
.icon a:nth-child(5):hover{
    color: #f81109;
    background: #f2f1f1;
    box-shadow: 0 0 20px aqua;
    transform: scale(1.1);
}
.btn{
    display: inline-block;
    background: rgb(5, 225, 241);
    color: white;
    padding: 11px 26px;
    font-size: 15px;
    font-weight: 600;
    transition: all .50s ease;
    border-radius: 8px;
    border: 2px solid aqua;
}
.btn:hover{
    color: #f3eeed;
    background:transparent;
    transform:scale(1.1) ;
    box-shadow: 0 0 20px aqua;
}
.btn2{
    background: transparent;
    margin-left: 15px;
}
.btn2:hover{
    background: aqua;
}


/*--------- about---------------------mmmmmmmmmmmmm*/
 .about{
    width: 100%;
height: 100vh;
    background: #4a4949;
    background-size: cover ;
    display: grid;
    grid-template-columns: repeat(2,1fr);
   align-items: center;
    gap: 1rem;
 }
 /*
 .img{
    border: 10px solid rgb(23, 122, 135);
    border-radius: 50%;
    width: 100%;
    height: 350px;
    max-width: 350px;
    box-shadow: 0 0 20px rgb(246, 35, 2);
 }*/
.img img{
    width: 100%;
    height: 230px;
    max-width: 230px;
    border-radius: 50%;
    object-fit: cover;
    border: 7px solid rgb(7, 181, 250);
    box-shadow: 0 0 20px aqua;
   transition: 2s;
   cursor: pointer;
}
.img img:hover{
    transform: scale(1.1);
}

.about-text h2{
    font-size: 28px;
    line-height: 1.6rem;
    margin-bottom: 20px;
}
.exp-area{
    margin-bottom: 50px;
}
.exp-area p{
    font-size: 19px;
    font-weight: 600;
    color: rgb(241, 246, 246);
    line-height: 30px;
}
.exp-area p span{
    color: #07e9f1;
    margin-left: 8px;
    font-size: 17px;
    font-weight: 400;
}


/*----------services-----------*/

.center-text{
    text-align: center;
}
.center-text h2{
    font-size: 30px;
    font-weight: 700;
}
.content2{
display: grid;
grid-template-columns: repeat(auto-fit, minmax(300px ,auto) );
align-items: center;
gap: 1.3rem;
margin-top: 4.2rem;
}
.box{
    padding: 80px 40px 66px;
    background: #8178e7;
    border-radius: 20px;
    border: 2px solid transparent;
    box-shadow: 0 0 50px rgb(0, 170, 255);
    transition: all .50s ease;
}
.box img{
    margin-bottom: 10px;
}
.box h3{
    font-size: 30px;
font-weight: 700;
margin-bottom: 10px;

}
.box p{
    font-size: 15px;
    font-weight: 400;
    color: whitesmoke;
    line-height: 20px;
    margin-bottom: 10px;
}
.box a{
    display: inline-block;
  line-height: 1.273rem;
  font-weight: 700;
  padding: 7px 0;
    font-size: 22px;
    color: rgb(119, 248, 245);
    border-bottom: 2px solid rgb(166, 169, 168);
    transition: all .50s ease;
}
.box i{
    vertical-align: middle;
    font-size: 25px;
    color: #06fcfc;
    margin-left: 5px;
}
.box a:hover{
    border-bottom: 2px solid rgb(8, 221, 249);
}
.box:hover{
    border: 1px solid aqua;
    transform: translateY(-5px) scale(1.0);
}





/*  -------- portfolio----------------------*/

.portfolio{
    background: #4a4949;
}
.portfolio-content{
    display: grid;
grid-template-columns: repeat(auto-fit, minmax(300px ,auto) );
align-items: center;
gap: 1.3rem;
margin-top: 4.2rem;
}
.row img{
    width: 100%;
    height: 250px;
    border-radius: 28px;
    margin-bottom: 1.5rem;
   
}
.row{
    background: rgb(80, 83, 83);
    border-radius: 8px;
    border: 2px solid aqua;
    box-shadow: 0 0 7px transparent;
    padding: 20px;
    transition: all .50s ease;
}
#main-row{
    display: inline-block;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 0.5rem;
}
.row:hover{
    border: 2px solid aqua;
    transform: translateY(-5px) scale(1.0);
}



/*---------contact-------------*/

.contact-form{
    display: flex;
    align-items: center;
    justify-content: center;
    margin-top: 4.2rem;
}
.contact-form form{
    position: relative;
    width: 600px;
    
}
form input,
form textarea{
    width: 100%;
    padding: 15px;
    border: none;
    outline: none;
    box-shadow: 0 0 5px rgb(28, 247, 244);
    background: #313131;
    color: #06e5fa;
    margin-bottom: 15px;
    border-radius: 8px;
}
form .btn{
display: inline-block;
width: 30%;
}






.footer{
    padding: 22px 16%;
    background: rgb(67, 68, 68);
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 2rem;
}



@media (max-width:1700px){
    header{
        padding: 20px 8%;

    }
    header .sticky{
padding: 14px 8%;
    }
    section{
        padding: 90px 8% 80px;
    }
    .footer{
        padding: 14px 8%;

    }
    .logo{
        font-size: 20px;
    }
}
@media (max-width:1328px){
    header{
        padding: 20px 8%;

    }
    header .sticky{
padding: 14px 8%;
    }
    section{
        padding: 90px 8% 80px;
    }
    .footer{
        padding: 14px 8%;

    }
   
    .hero{
height: 90vh;
background-position: center;
    }
}


@media (max-width:1290px){
.box{
    padding: 40px 40px 40px;
}
.box img{
    width: 100%;
    height: 60px;
    max-width: 60px;
}

}
@media (max-width:1240px){
.about{
    
    grid-template-columns: 1fr ;
    gap: 2rem;
    text-align: center;
}
}

@media (max-width:960px){
.social{
    margin-bottom: 20px ;
}
#menu-icon{
    display: block;
}
.navlist{
    position: absolute;
    top: 100%;
    right: -100%;
    width: 225px;
    min-height: 100vh;
display: flex;
flex-direction: column;
background: #2c3030;
transition: all .50s ease;
}
.navlist a{
    display: block;
    padding: 17px;
    font-size: 20px;
}
.navlist .active{
    right: 0;
}
}
@media (max-width:680px){
.content p{
    width: 100%;
}
}



    </style>
</head>
<body>

   <!-------------header --------------->
<header>
<a href="#" class="logo">FronTend <span>X.</span></a>
<div class="bx bx-menu" id="menu-icon"></div>
<ul class="navlist">
    <li><a href="#home">Home</a>  </li>
    <li><a href="#about ">About </a>  </li>
    <li><a href="#services">Services</a>  </li>
    <li><a href="#portfolio"> Portfolio</a>  </li>
    <li><a href="#contact">Contact</a> </li>
</ul>
<div class="top-btn">
<a href="#" class="h-btn">Contact me</a>
</div>

</header>


<!--------------hero---------------->
<section class="hero" id="home">
    <div class="content">
<h4> Hi , There!</h4>
<h1> I'm <span>Zakir Alibaliyev</span></h1>
<p> I am a junior developer building websites for small and medium businesses

    HTML, CSS, Bootstrap, Javascript
    Complete project management from start to finish.</p>
<div class="icon">
    <a href="#"><i class="fab fa-facebook"></i>  </a>
    <a href="#"><i class="fab fa-instagram"></i> </a>
    <a href="#"><i class="fab fa-linkedin-in"></i> </a>
    <a href="#"><i class="fab fa-twitter"></i> </a>
    <a href="#"><i class="fab fa-youtube"></i> </a>
</div>

<div class="main-btn">
    <a href="#" class="btn"> Hire me..</a>
    <a href="#" class=" btn btn2"> Download CV..</a>
</div>
    </div>
</section>



<!--------------about ----------------->
<section class="about" id="about">
    <div class="img">
        <img src="">
    </div>
    <div class="about-text">
        <h2> I am Product <span> FronTend</span><br/> & Web Developer 
        </h2>
        <div class="exp-area">
            <p class="exp">
                Experince:
                <span> 1 Years</span>
            </p>
            <p class="exp">
                Specialty:
                <span> FronTend Developer</span>
            </p>
            <p class="exp">
                Address:
                <span> Azerbaycan , Zaqatala</span>
            </p>
            <p class="exp">
                Email:
                <span> alibaliyev232gmail.com</span>
            </p>
            <p class="exp">
                Phone:
                <span> (+994) 050 783 41 21</span>
            </p>
            <p class="exp">
                Freelancer:
                <span> Zakir Alibaliyev</span>
            </p>
        </div>
        <a href="#" class="btn"> View All Projets</a>
    </div>
</section>



<!-------------services-------->
<section class="serices" id="services">
    <div class="center-text">
<h2>My <span>Services</span></h2>
    </div>

    <div class="content2">
        <div class="box">
            <img src="">
            <h3>Frontend</h3>
            <p>
                The field of user experience design is a conceptual design discipline and has its roots 
                in human factors and ergonomics, a field that, since the late 1940s
                 interaction between human users.
                 
            </p>
            <a href="#">
                Download now     
                <i class='bx bx-right-arrow-alt'></i>     
            </a>
        </div>


        <div class="box">
            <img src="">
            <h3> Bckend  </h3>
            <p>
                Front-end web development is the development of the graphical user interface of a website, 
                through the use of HTML, CSS, and JavaScript, so that users can view and interact with that website.
            </p>
            <a href="#">
                Download now     
                <i class='bx bx-right-arrow-alt'></i>    
            </a>
        </div>


        <div class="box">
            <img src="">
            <h3>Fullstarcks </h3>
            <p>
                Graphic design uses typography, photography and illustration in order to convey any 
                information to a certain target audience, and designs such as logos, posters, billboards, 
                banners, 
               
            </p>
            <a href="#">
                Download now     
                <i class='bx bx-right-arrow-alt'></i>       
            </a>
        </div>

    </div>
</section>


<!----------portfolio------------>

<section class="portfolio" id="portfolio">
<div class="center-text">
    <h2>My <span>Portfolio</span></h2>
</div>

<div class="portfolio-content">
    <div class="row">
<img src="https://web-images.pixpa.com/w5vvJthJwGbV4GN09jKYN1aFDr2THdHKlUC-fTzFPyA/rs:fit:1200:0/q:80/czM6Ly9waXhwYS5jb20vL2NvbS9hcnRpY2xlcy8xNjA3MzI0NjMzLTg0NzcxNi1tYXR0aGV3anBnLmpwZw==">

<div id="main-row">
    <div class="row-text">
        <h5>Website Design</h5>
    </div>


    <div >
        <h4> Website Development For Dark X </h4>
    </div>
</div>
    </div>


    
    <div class="row">
<img src="https://web-images.pixpa.com/h2ta1mnofDYKM0xWn1g6PfXTUdgZBU4dcq_dQx60TpA/rs:fit:640:0/q:80/czM6Ly9waXhwYS5jb20vY29tL2V4YW1wbGVzLzE2MzMzNDAwNDMtZ2FlbGxlLW1vbmluLnBuZw==">

<div id="main-row">
    <div class="row-text">
        <h5>Website Design</h5>
    </div>
    
    <div >
        <h4> Website Development For Dark X </h4>
    </div>
</div>
    </div>


    <div class="row">
<img src="https://web-images.pixpa.com/h2ta1mnofDYKM0xWn1g6PfXTUdgZBU4dcq_dQx60TpA/rs:fit:640:0/q:80/czM6Ly9waXhwYS5jb20vY29tL2V4YW1wbGVzLzE2MzMzNDAwNDMtZ2FlbGxlLW1vbmluLnBuZw==">

<div id="main-row">
    <div class="row-text">
        <h5>Website Design</h5>
    </div>
    
    <div >
        <h4> Website Development For Dark X </h4>
    </div>
</div>

   


    </div>
    <div class="row">
        <img src="https://web-images.pixpa.com/w5vvJthJwGbV4GN09jKYN1aFDr2THdHKlUC-fTzFPyA/rs:fit:1200:0/q:80/czM6Ly9waXhwYS5jb20vL2NvbS9hcnRpY2xlcy8xNjA3MzI0NjMzLTg0NzcxNi1tYXR0aGV3anBnLmpwZw==">
        
        <div id="main-row">
            <div class="row-text">
                <h5>Website Design</h5>
            </div>
            
            <div >
                <h4> Website Development For Dark X </h4>
            </div>
        </div>
            </div>
        
        
            
            <div class="row">
        <img src="https://web-images.pixpa.com/h2ta1mnofDYKM0xWn1g6PfXTUdgZBU4dcq_dQx60TpA/rs:fit:640:0/q:80/czM6Ly9waXhwYS5jb20vY29tL2V4YW1wbGVzLzE2MzMzNDAwNDMtZ2FlbGxlLW1vbmluLnBuZw==">
        
        <div id="main-row">
            <div class="row-text">
                <h5>Website Design</h5>
            </div>
           
            <div >
                <h4> Website Development For Dark X </h4>
            </div>
        </div>
            </div>
        
        
            <div class="row">
        <img src="https://web-images.pixpa.com/h2ta1mnofDYKM0xWn1g6PfXTUdgZBU4dcq_dQx60TpA/rs:fit:640:0/q:80/czM6Ly9waXhwYS5jb20vY29tL2V4YW1wbGVzLzE2MzMzNDAwNDMtZ2FlbGxlLW1vbmluLnBuZw==">
        
        <div id="main-row">
            <div class="row-text">
                <h5>Website Design</h5>
            </div>
            
            <div >
                <h4> Website Development For Dark X </h4>
            </div>
        </div>
</div>
</section>


<!----------contact=====------>

<section class="contact" id="contact">

    <div class="center-text">
        <h2> Contact <span>Me</span></h2>
    </div>
    <div class="contact-form">
        <form action="">
            <input type="text" name="text" placeholder="UserName" required>
            <input type="email" name="" placeholder="Your Email" required>
            <textarea name="" id="" cols="30" rows="10" placeholder="Write Message here......" required></textarea>
            <input type="submit" value="Send Message" class="btn">
        </form>
    </div>
</section>



<div class="footer">
    <div class="copyright">
        <p>2023 Zakir Alibaliyev | All Rights Reserved.</p>
    </div>

</div>
<script>
    const header = document.querySelector("header");

window.addEventListener("scroll" , function(){
    header.classList.toggle("sticky" , window.scrollY>120)
});


let menu = document.querySelector('#menu-icon');
let navlist = document.querySelector('.navlist');

menu.onclick = () =>{
   menu.classList.toggle('bx-x')
   navlist.classList.toggle('active')
} 
window.onscroll = ()=>{
    menu.classList.remove('bx-x')
   navlist.classList.remove('active')
}
</script>
</body>
</html>
