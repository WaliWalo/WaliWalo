<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Train+One&display=swap" rel="stylesheet">
<link rel="preconnect" href="https://fonts.gstatic.com">
<link href="https://fonts.googleapis.com/css2?family=Teko&family=Train+One&display=swap" rel="stylesheet">
<style>
h1{
    font-family: 'Train One', cursive;
}
p{
    font-family: 'Teko', sans-serif;
    font-size: 20px;
    text-align: justify;
}
#logoContainer{
    /* position:relative; */
    /* width: 100vw; */
    /* height: 12em;     */
}
.logos{    
    position:absolute;
    animation-duration: 4s; 
    animation-iteration-count: infinite;
    animation-direction: alternate;
    z-index:-1;
    opacity: 0.5;
}
#logo0{
    width: 50px;
    left:40%;
    top:10%;
    animation-name: position0;
}
#logo1{
    width: 70px;
    left: 60%;
    top: 35%;
    animation-name: position1;
}
#logo2{
    width: 40px;
    left: 60%;
    top: 70%;
    animation-name: position2;
}
#logo3{
    width: 35px;
    top: 70%;
    left:30%;
    animation-name: position3;
}
#logo4{
    width: 45px;
    top: 35%;
    left: 15%;
    animation-name: position4;
}
@keyframes position0 {
  0%   {
            left:40%;
            top:10%;
        }
  20%  {
             left: 60%;
             top: 35%;
        }
  40%  {
           left: 60%;
            top: 70%;
        }
  60%  {
           top: 70%;
            left:30%;    
        }
  80% {
            top: 35%;
              left: 15%;
        }
}
@keyframes position1 {
  80%   {
            left:40%;
            top:10%;
        }
  0%  {
             left: 60%;
             top: 35%;
        }
  20%  {
           left: 60%;
            top: 70%;
        }
  40%  {
           top: 70%;
            left:30%;    
        }
  60% {
            top: 35%;
              left: 15%;
        }
}
@keyframes position2 {
  60%   {
            left:40%;
            top:10%;
        }
  80%  {
             left: 60%;
             top: 35%;
        }
  0%  {
           left: 60%;
            top: 70%;
        }
  20%  {
           top: 70%;
            left:30%;    
        }
  40% {
            top: 35%;
              left: 15%;
        }
}
@keyframes position3 {
  40%   {
            left:40%;
            top:10%;
        }
  60%  {
             left: 60%;
             top: 35%;
        }
  80%  {
           left: 60%;
            top: 70%;
        }
  0%  {
           top: 70%;
            left:30%;    
        }
  20% {
            top: 35%;
              left: 15%;
        }
}
@keyframes position4 {
  20%   {
            left:40%;
            top:10%;
        }
  40%  {
             left: 60%;
             top: 35%;
        }
  60%  {
           left: 60%;
            top: 70%;
        }
  80%  {
           top: 70%;
            left:30%;    
        }
  0% {
            top: 35%;
              left: 15%;
        }
}
.icons{
    width: 5em;
    height: 5em;
    border-radius:100%;
    background-color: white;
    margin: 1em
}
.iconsContainer{
    display: flex;
    justify-content: center;
    margin-bottom:2em;
    margin-top: 1em;
}
.icons >img{
    width: 100%;
    height: 100%;
    object-fit: cover;
    border-radius: 100%;
}
.icons >img:hover{
    cursor: pointer
}
.email{
    margin-bottom: 1em;
    font-family: 'Teko', sans-serif;
    font-size: 2em;
}
</style>

![Hung Jin Chong Header](/images/header.jfif)

<h1 align="center">Hello there! My name is Jin <img src="https://res.cloudinary.com/waliwalo/image/upload/v1618306281/portfolio/handWave_oow7h1.gif" width="20px"></h1>

<p>
I'm from Malaysia. I completed my Diploma in Software Engineering in Malaysia, then continued my studies in Dublin where I acquired my Bachelor Degree in Computer Science.

After all that I decided to improve my skills in web development, so I enrolled in Strive master camp for Full-Stack Developer. Now I am proud to say I'm a Full-Stack Developer looking for an opportunity where I can start my adventure in web development.

<div align="center">
    <div id="logoContainer">
                    <img
                    alt="mongoLogo"
                    id="logo0"
                    class="logos"
                    src="https://res.cloudinary.com/waliwalo/image/upload/v1617711149/portfolio/mongodb_apsqb7.png"
                    />
                    <img
                    alt="reactLogo"
                    id="logo1"
                    class="logos"
                    src="https://res.cloudinary.com/waliwalo/image/upload/v1617711044/portfolio/react-removebg-preview_1_d2wuyc.png"
                    />
                    <img
                    alt="nodeLogo"
                    id="logo2"
                    class="logos"              src="https://res.cloudinary.com/waliwalo/image/upload/v1617711153/portfolio/nodeJs_tgl1sx.png"
                    />
                    <img
                    alt="typescriptLogo"
                    id="logo3"
                    class="logos"
                    src="https://res.cloudinary.com/waliwalo/image/upload/v1617711874/portfolio/ts_db0zho.png"
                    />
                    <img
                    alt="reduxLogo"
                    id="logo4"
                    class="logos"
                    src="https://res.cloudinary.com/waliwalo/image/upload/v1617712054/portfolio/redux-removebg-preview_jepndp.png"
                    />
                </div>
</div>
</p>

<div class="iconsContainer">
    <div class="icons" href="https://www.linkedin.com/in/hungjinchong/">
        <img src="https://res.cloudinary.com/waliwalo/image/upload/v1617786130/portfolio/linkedin-icon-2_cv4ywd.svg">
    </div>
    <div class="icons" href="https://jin-portfolio.vercel.app/">
        <img src="https://res.cloudinary.com/waliwalo/image/upload/v1617807197/portfolio/AvatarMaker_2_kp8v5q.png">
    </div>    
    <!-- <div class="icons">
        <img src="https://res.cloudinary.com/waliwalo/image/upload/v1618319554/portfolio/cv-logo-template-icon-isolated-on-black-background-130135732_jbbu8l.jpg">
    </div>     -->
</div>

<div align="center" class="email">hungjinchong@outlook.com</div>

[![Anurag's GitHub stats](https://github-readme-stats.vercel.app/api?username=WaliWalo&hide=stars&include_all_commits=true&show_icons=true&theme=dark)](https://github.com/anuraghazra/github-readme-stats)

<!--
**WaliWalo/WaliWalo** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
  -->
