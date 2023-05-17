<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Anish Sukhramani</title>
    <link rel="stylesheet" href="my_style.css" />
    <style>
      body {
        margin: 0;
        padding: 0;
        height: 100vh;
        background-position: center;
        background-size: cover;
      }
    </style>
    <!-- heading -->
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Lora&family=Orbitron:wght@700;900&display=swap");
    </style>
    <!-- nav bar -->
    <style>
      @import url("https://fonts.googleapis.com/css2?family=Lora&family=Orbitron:wght@600;700;900&display=swap");
    </style>
  </head>
  <body>
    <script src="slideshow.js"></script>
        <div class="my_name" id="my_name">
            <div class="first_flex">
              <nav class="navbar" style="display: flex; justify-content: center; align-items: center;">
                <a class="cvbtn" href="https://www.linkedin.com/in/anish-sukhramani-b0148121b" target="_blank" style="margin-right: 100px;">
                  <button>Refer Me</button>
                </a>
                <div style="display: flex; align-items: center;">
                  <a href="index.html" style="display: inline-block; margin-right: 35px; margin-left: 35px;">Home</a>
                  <a href="#AboutMe" style="display: inline-block; margin-right: 35px">About Me</a>
                  <a href="Blog.html" style="display: inline-block; margin-right: 35px">Blog</a>
                  <a href="#projects" style="display: inline-block; margin-right: 35px">Projects</a>
                  <a href="#contact_me" style="display: inline-block; margin-right: 35px">Contact Me</a>
                </div>
                <a class="cvbtn" href="example.pdf" download style="margin-left: 100px;">
                  <button>Download CV</button>
                </a>
              </nav>
              
              
              <div class="wrapper">
                <div class="static-txt"></div>
                <ul class="dynamic-txts">
                  <!-- <li><span>Hello! I am</span></li>
                  <li><span>नमस्ते! मैं हूँ</span></li>
                  <li><span>こんにちは！私は</span></li>
                  <li><span>안녕하세요! 그래요</span></li>
                  <li><span>你好！我是</span></li>
                  <li><span>হ্যালো! আমি</span></li>
                  <li><span>નમસ્તે! હું છું</span></li>
                  <li><span>Olá! Eu sou</span></li>
                  <li><span>Hola! yo soy</span></li>
                  <li><span>Hallo! Ich bin</span></li> -->
                </ul>
              </div>
              <h1 class="Anish">Anish</h1>
              <h1 class="Sukhramani">Sukhramani</h1>
              <a href="https://www.linkedin.com/in/anish-sukhramani-b0148121b/" target="_blank" style=" /* display: inline-block; */ margin-right: 35px; margin-left: 35px; margin-top: 90px;"><img src="WhiteIN.png" alt=""  height="30px"/></a>
              <a
                href="https://github.com/AnishSukhramani"
                target="_blank"
                style="display: inline-block; margin-right: 35px"
                ><img src="WhiteGit.png" alt="" height="28px"
              /></a>
              <a
                href="https://www.instagram.com/anishsukhramani/"
                target="_blank"
                style="display: inline-block; margin-right: 35px"
                ><img src="WhiteIG.png" alt="" height="28px"
              /></a>
              <a href="https://twitter.com/AnishSukhramani"target="_blank"style="display: inline-block;margin-right: 35px;margin-bottom: 10px;"><img src="WhiteTW.png" alt="" height="28px";"></a>
              <a href="#my_name" id="myBtn"><img src="Arrow.png" alt="" height="30px"/></a>
            </div>
        </div>
      <div id="AboutMe" class="new">
        <div class="new1" style="background-image: url('Hover.png');">
          <img src="Anish Sukhramani.png" alt="" class="myimg" style="width: auto; height: 350px; margin: 0%; padding: 0;border-radius: 10px;">
          <img src="Sig.png" alt="" width="300px" style="margin-top: 35%;">
        </div>
        <div class="new2" >
          <h1 style="background-image: url('Hover.png'); margin-left: 4%; font-family: 'Gtek Technology', sans-serif; ">About Me</h1>
          <p style="background-image: url('Hover.png'); margin-top: 3%; margin-left: 4%; width: 80%; text-align: justify; font-family: 'Rthin'; ">I am a 5-Star Coder in both C++ and Python and ardently explore and work on Web Development and Data Science. <br> <br> I have a keen interest and competence in Mathematics including its branches such as Calculus and Laplace Transforms, Discrete Mathematics and Graph Theory, Applied Linear Algebra, and Applied Numerical Methods. <br> <br> I am an active core member of SEDS Nebula due to my childhood fascination with Space Technology, in this organization, I have worked both in the Technical as well as management domains.</p>
          <button class="edubtn" onclick="toggleDiv()" style="border-radius: 10px; border: none; margin-top: 7%; height: 50px; width: 150px; margin-right: 6.9%">Education</button>
          <button class="edubtn" onclick="toggleDiv1()" style="border-radius: 10px; border: none; margin-top: 7%; height: 50px; width: 150px;margin-right: 6.9%"">Skills</button>
          <button class="edubtn" onclick="toggleDiv2()" style="border-radius: 10px; border: none; margin-top: 7%; height: 50px; width: 150px;margin-right: 6.9%"">Extra-Curricular</button>
          <a href="hobies.html" style="background-image: url('Hover.png');"><button class="edubtn" style="border-radius: 10px; border: none; margin-top: 7%; height: 50px; width: 150px;margin-right: 6.9%"">Hobbies</button></a>
          <div class="infobox" style="display: flex; background-image: url('Hover.png');">
            <div id="hidden-div" style="display: none; background-image: url('Hover.png');"><img src="Edu Details.png" alt="" style="width: 300px; border-radius: 10px; margin-top: 3%; margin-right: 0%;"></div>
            <div id="hidden-div1" style="display: none; background-image: url('Hover.png'); margin-left: 3%"><img src="Skills.png" alt="" style="height: 255.4px; border-radius: 10px; margin-top: 3.5%; margin-left: 3%;"></div>
            <div id="hidden-div2" style="display: none; background-image: url('Hover.png'); margin-left: 5%"><img src="ExtraC.png" alt="" style="height: 255.4px; border-radius: 10px; margin-top: 3.5%; "></div></div>
        </div>
      </div>
      <div id="projects" class="scar" style="width: 100px; border-radius: 10px; margin-top: 8%; margin-left: 5%; height:0px; display: flex;">
        <a href="https://github.com/AnishSukhramani/Scar"><img src="SCAR New.png" alt="" width="300px" style="border-radius: 10px;"></a>
        <a href="https://github.com/CrossbowPlasma/Brain-Cancer-Detection" style=" margin-left: 30%;margin-right: 30%;"><img src="BTC1.png" alt="" width="300px" style="border-radius: 10px; "></a>
        <a href="https://github.com/AnishSukhramani/Scar" style="margin-left: 30%; margin-right: 30%;"><img src="More2.png" alt="" width="300px" style="border-radius: 10px; "></a>
      </div>
    <div style="margin-top: 40%" style="background-image: url('ConBG.png');">
      <img src="ConBG.png" alt="" width="100%">
    </div>
  </body>
</html>
