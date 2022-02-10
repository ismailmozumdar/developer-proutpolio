<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>ismamil-proutpolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <style>
        body{
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
}
.main{
	width: 100%;
	background: linear-gradient(to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%), url(1.jpg);
	background-attachment: center;
	background-size: cover;
	height: 100vh;
}
.nabver{
	width: 1200px;
	height: 75px;
	margin: auto;
}
.ion{
	width: 305px;
	float: left;
	height: 70px;
}
.logo{
	color: salmon;
	font-size: 35px;
	font-family: Arial;
	padding-left: 10px;
	float: left;
	padding-top: 10px;
}
.Menu{
	width: 475px;
	float: left;
	height: 70px;
}
ul{
	float: left;
	display: flex;
	justify-content: center;
}
ul li{
	list-style: none;
	margin-top: 27px;
	font-size: 18px;
	transition: 1s;
}
ul li a{
	text-decoration:none ;
	color: seashell;
	font-family: Arial;
	font-weight: bold;
	transition: 1s;
}
ul li a:hover{
	color: salmon;
	border-bottom: 2px solid #00ffe7;
}
.search{
	width: 300px;
	float: right;
    margin-top: 20px;
}
.srch{
	font-family: 'Times New Roman';
	width: 200px;
	height: 40px;
	background: transparent;
	border: 1px solid salmon;
	margin-top: 20px;
	color: #ffffff;
	border-right: none;
	font-size: 16px;
	float: left;
	padding: 10px;
	border-bottom-left-radius: 5px;
	border-top-left-radius: 5px;
}
.btn{
	width: 100px;
	height: 40px;
	background: salmon;
	border: 2px solid salmon;
	margin-top: 20px;
	color: #fff;
	font-size: 15px;
	border-bottom-right-radius: 5px;
	border-top-right-radius: 5px;
}
.btn a{
	text-decoration: none;
	color: #fff;
}
.btn:focus{
	outline: none;
}
.srch:focus{
	outline: none;
}
.contant{
	width: 1200px;
	height: auto;
	margin: auto;
	color: #fff;
	position: relative;
}
.contant .per{
	height:120px;
	width: 500px;
	padding-left: 20px;
	padding-bottom: 10px;
	font-family: Arial;
	letter-spacing: 1.5px;
	line-height:20px;
	text-align: justify;
}
.contant h1{
	font-family: 'Times New Roman';
	font-size: 50px;
	padding-left: 20px;
	margin-top: 80px;
	letter-spacing: 2px;
}
.contant .join{
	width: 160px;
	height: 40px;
	background: salmon;
	border: none;
	margin-bottom: 10px;
	margin-left: 20px;
	font-size: 18px;
	border-radius: 10px;
	cursor:pointer;
	transition: 0.5s;
}
.contant .join a{
	text-decoration: none;
	color: #fff;
	transition: 0.5s;
}
.contant .join:hover a{
	color: salmon;
}
.contant .join:hover{
	background: #00ffe7;
}
.contant .one{
	color: #00ffe7;
}
.contant .two{
	color: salmon;
}
.frome{
	width: 250px;
	height: 280px;
	background: linear-gradient(to top, rgba(0,0,0,0.5)50%,rgba(0,0,0,0.5)50%);
	position: absolute;
	top: -20px;
	margin-top:60px;
	left: 700px;
	border-radius: 10px;
	padding: 25px;
}
.frome h1{
	font-family: sans-serif;
	text-align: center;
	color: salmon;
	font-size: 22px;
	margin: 2px;
	padding: 10px;
}
.frome input{
	width: 240px;
	height: 35px;
	color: salmon;
	margin-top: 15px;
	border-bottom: 1px solid salmon;
	border-top: 1px solid #00ffe7;
	border-left: none;
	border-right: none;
	font-family: sans-serif;
	background: transparent;
}

.frome input:focus{
	outline: none;
}
::placeholder{
	color: #00ffe7;
}
.frome .btn1{
	border-radius: 10px;
	width: 200px;
	height: 35px;
	margin-top: 10px;
	margin-left: 30px;
	border: none;
	transition: 1s;
	background:#00ffe7;
}
.btn1:hover{
	background: salmon;
}
.frome .btn1 a{
	text-decoration: none;
	color: #fff;
	font-size: 18px;
}
.frome p{
	margin-top: 10px; 
	text-align: center;
}
.frome .sin{
	text-decoration: none;
	color: salmon;
	font-size: 18px;
	margin-left: 80px;
	margin-top: 10px;
	margin-bottom: 10px;
}
h1{
    font-size: 50px;
}
span{
    color: salmon;
}
.flexebol-containt{
    display: flex;
    margin-bottom: 150px;
}
.haf-width{
    width: 50%;
    padding-left: 5%;
}
.haf-width img{
    width: 80%;
}
.link-button{
    text-decoration: none;
    color: white;
    font-weight: 700;
    background-image: linear-gradient(salmon, rgb(255, 39, 39));
    padding: 10px 40px;
    border-radius: 5px;
}
.banner{
    background-image: url(images/top-banner.png);
    background-repeat: no-repeat;
}
.Dream-Big{
    background-image: url(images/dream-bg.png);
    background-repeat: no-repeat;
    background-position:right ;
}.color{
    color: #ffb824;
}
.boxsudo{
    width: 40%;
    margin-left: 5%;
    margin-right: 5%;
    padding: 20px;
    box-shadow: 10px 10px 40px gray;
}
h2{
    font-size: 40px;
}
.experiences-area{
    background-image: url(images/exp-bg.png);
    background-repeat: no-repeat;
    background-position: left;
}
#one{
    border-left: 7px solid;
    border-image: linear-gradient(salmon, rgb(255, 50, 84) );
    border-image-slice: 1;
}
#two{
    border-left: 7px solid;
    border-image: linear-gradient(blue, rgb(0, 255, 55) );
    border-image-slice: 1;
}
footer p{
    text-align: center;
}
    </style>
</head>
<body>
    
	<div class="main">
		<div class="nabver">
			<div class="ion">
				<h1 class="logo">Ismail Mozumdar</h1>
			</div>
			<div class="Menu">
				<ul><li><a href="https://ismailmozumdar.github.io/finel-site/">Home</a></li></ul>
				<ul><li><a href="https://ismailmozumdar.github.io/developer-proutpolio/">About</a></li></ul>
				<ul><li><a href="#">Servich</a></li></ul>
				<ul><li><a href="#">Contact</a></li></ul>
				<ul><li><a href="#">Blog</a></li></ul>
			</div>
			<div class="search">
				<input class="srch" type="search" name=""placeholder="Type to text">
				<button class="btn"><a href="#">search</a></button>
			</div>
		</div>
		<div class="contant">
			<h1> <span class="one">Web Design &</span> <br><span class="two"> Development </span> <br>Courch</h1>
			<p class="per">Lorem Ipsum is simply dummy text of the printing and typesetting
				 industry. Lorem Ipsum has been the industry's standard dummy text ever since the
				  1500s, when an unknown printer took a galley of type and scrambled it to make a
				   type specimen book. It has survived not only five centuries, but also the leap
					   versions of Lorem Ipsum.</p>
					   <button class="join"><a href="#">Join us</a></button>
					   <div class="frome">
						   <h1>Log in</h1>
						   <input type="email" name="email" placeholder="Enter Your Email">
						   <input type="password" name="password" placeholder="Enter Your Password">
						   <button class="btn1"><a href="#">Log in</a></button>

						   <p class="link">Don't have an account</p><a class="sin" href="#">Sing up here</a><p class="liw"> Log in with</p>
					   </div>
		</div>
	</div>
   <section class="banner flexebol-containt">
    <div class="haf-width">
        <h1>Wellcome to</h1>
    <h1><span>Ismail Mozumdar</span> World!</h1>
    <h3 class="color">Build Climber and Train Stopper</h3>
    <p>Hi, I am Ismail Mozumdar. I am A professional web & graphics designer and a web developer.I do some offline website. And a <a href="https://ismailmozumdar.github.io/finel-site/">online website</a>. But now I want to work Online I crate html, css and wordpress website. I am a professional graphics , logo and business curd Designer. I hope you like my work. </p>
    <a class="link-button" target="_blank" href="https://www.linkedin.com/in/ismail-mozumdar-13000b224/">HEIR ME</a>
    </div>
    <div class="haf-width">
        <img src="images/my-bg3.png" alt="">
    </div>
   </section>
   <section class="Dream-Big flexebol-containt">
        <div class="haf-width">
        <img src="images/my-bg1.png" alt="">
       </div>
       <div class="haf-width">
        <h1>Dream Big</h1>
        <h2>Become a web developer</h2>
        <p>I already learned the basic HTML and CSS. I can build any simple website. I can even teach my grandma how to make simple website. My goal is to build 3 websites and learn advanced topics.</p>
        <a class="link-button" target="_blanck" href="">DOWNLOAD RESUME</a>
       </div>
   </section>
   <section class="experiences-area">
    <h1>Experiences</h1>
   <div class="flexebol-containt">
    <div id="one" class="boxsudo">
        <h2>Full Stack Developer</h2>
        <h3 class="color">2022-Present | Pro Level Developer</h3>
        <p>I am the master of HTML, CSS and Javascript. I know everything needed to make a website function, efficient. I didn't stop with the web. I went beyond with most popular Javascript framework called Vue JS. I even know the deployment, server and security. I will give you 100% web solution.</p>
    </div>
    <div id="two" class="boxsudo">
        <h2>Baby Web Developer</h2>
        <h3 class="color">2022-2022 | Programming Hero Learner</h3>
        <p>They didn't offer me a job. But I made myself as a remove web developer. I made their website and showed it to them. They liked it. And uploaded the content. It was fun working at Programming Hero.</p>

    </div>
   </div>
   </section>
   <footer>
       <p>© Peter Parker 2021, a Programmer Ismail initiative.</p>
   </footer>
</body>
</html>
