
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<style>
* {
  margin: 0 auto;
  padding: 0px;
  text-align: center;
}

.cont_corazon {
  position: relative;
  margin-top: 100px;
}

.cont_corazon > h1 {
  font-family: "Roboto";
  font-weight: 300;
}
.cont_corazon > hr {
  width: 300px;
}

#rect3810,
#rect3802,
#rect3826,
#rect3806,
#rect3820,
#rect3818,
#rect3822,
#rect3824 {
  z-index: -5;
  position: relative;
  animation-name: mov_1;
  animation-duration: 200ms;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in-out;
}

#rect3808,
#rect3828,
#rect3812,
#rect3814 {
  position: relative;
  animation-name: mov_1;
  animation-duration: 2s;
  animation-iteration-count: infinite;
  animation-timing-function: ease-in;
}

#rect3804 {
  z-index: -5;
  position: relative;
  /*   animation-name: mov_2;
    animation-duration: 2s;
      animation-iteration-count: infinite;
animation-timing-function: ease-in; */
}

@-webkit-keyframes mov_1 {
  from {
    opacity: 1;
    -webkit-transform: translate(4px, -1px);
    transform: translate(4px, -1px);
  }
  to {
    -webkit-transform: translate(-5px, -1px);
    transform: translate(-5px, -1px);
    opacity: 0;
  }
}
@-o-keyframes mov_1 {
  from {
    opacity: 1;
    -webkit-transform: translate(4px, -1px);
    transform: translate(4px, -1px);
  }
  to {
    -webkit-transform: translate(-5px, -1px);
    transform: translate(-5px, -1px);
    opacity: 0;
  }
}
@-moz-keyframes mov_1 {
  from {
    opacity: 1;
    -webkit-transform: translate(4px, -1px);
    transform: translate(4px, -1px);
  }
  to {
    -webkit-transform: translate(-5px, -1px);
    transform: translate(-5px, -1px);
    opacity: 0;
  }
}
@keyframes mov_1 {
  from {
    opacity: 1;
    -webkit-transform: translate(4px, -1px);
    transform: translate(4px, -1px);
  }
  to {
    -webkit-transform: translate(-5px, -1px);
    transform: translate(-5px, -1px);
    opacity: 0;
  }
}

@-webkit-keyframes mov_2 {
  from {
    opacity: 1;
    -webkit-transform: translate(-4px, -1px);
    transform: translate(-4px, -1px);
  }
  to {
    -webkit-transform: translate(-8px, -1px);
    transform: translate(-8px, -1px);
  }
}
@-o-keyframes mov_2 {
  from {
    opacity: 1;
    -webkit-transform: translate(-4px, -1px);
    transform: translate(-4px, -1px);
  }
  to {
    -webkit-transform: translate(-8px, -1px);
    transform: translate(-8px, -1px);
  }
}
@-moz-keyframes mov_2 {
  from {
    opacity: 1;
    -webkit-transform: translate(-4px, -1px);
    transform: translate(-4px, -1px);
  }
  to {
    -webkit-transform: translate(-8px, -1px);
    transform: translate(-8px, -1px);
  }
}
@keyframes mov_2 {
  from {
    opacity: 1;
    -webkit-transform: translate(-4px, -1px);
    transform: translate(-4px, -1px);
  }
  to {
    -webkit-transform: translate(-8px, -1px);
    transform: translate(-8px, -1px);
  }
}

svg {
  position: relative;
  animation-name: mov_heart;
  animation-duration: 1s;
  animation-iteration-count: infinite;
  -webkit-animation-timing-function: linear;
}

@-webkit-keyframes mov_heart {
  0% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
  50% {
    -webkit-transform: translate(0px, 0px);
    transform: translate(0px, 0px);
  }

  100% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
}
@-o-keyframes mov_heart {
  0% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
  50% {
    -webkit-transform: translate(0px, 0px);
    transform: translate(0px, 0px);
  }

  100% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
}
@-moz-keyframes mov_heart {
  0% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
  50% {
    -webkit-transform: translate(0px, 0px);
    transform: translate(0px, 0px);
  }

  100% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
}
@keyframes mov_heart {
  0% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
  50% {
    -webkit-transform: translate(0px, 0px);
    transform: translate(0px, 0px);
  }

  100% {
    -webkit-transform: translate(0px, 10px);
    transform: translate(0px, 10px);
  }
}

.carousel-product {
  width: 100%;
  height: 500px;
  position: relative;
  margin-top: 50px;
  margin-bottom: 50px;
}

.swiper-container {
  width: 300px;
  height: 500px;
  padding-top: 50px;
  padding-bottom: 50px;
}

.swiper-slide {
  background-position: center;
  background-size: cover;
  width: auto;
  height: auto;
}

.swiper-slide img {
  display: block;
  width: 100%;
}
canvas {
  position: fixed;
  left: 0;
  bottom: 0;
  display: block;
  width: 100%;
  height: 100%;
}



@import url('https://fonts.googleapis.com/css2?family=Alfa+Slab+One&family=Concert+One&family=Kanit:wght@300&family=Oswald:wght@300&family=Patrick+Hand+SC&family=Satisfy&display=swap');

 
body {
 
  font-family: 'Concert One', cursive;
  min-height: 100vh;
  
  align-items: center;
  justify-content: center;
 
}

 
.flip_letters {
  position: relative;
}

.flip_letters span {
  font-size: 10rem;
  position: relative;
  display: inline-block;
  color: #c71111;
  animation: flip 2s infinite;
  animation-delay: calc(.2s * var(--flip));
}

@keyframes flip {
  0%, 80% {
    transform: rotateY(360deg); 
  }
}
 
</style>
<body>

  <video src="file:///C:/Users/pc/Downloads/Couple%20-%2062666.mp4" style="min-height: 100%;min-width: 100%;position: fixed;right: 0; bottom: 0;" autoplay="true" muted="true" loop="true" poster="https://carontestudio.com/img/contacto.jpg"></video>
    <canvas></canvas>
 
    <link
      rel="stylesheet"
      href="https://unpkg.com/swiper/swiper-bundle.min.css"
    />

<div class="cont_corazon">


<svg
   xmlns:dc="http://purl.org/dc/elements/1.1/"
   xmlns:cc="http://creativecommons.org/ns#"
   xmlns:rdf="http://www.w3.org/1999/02/22-rdf-syntax-ns#"
   xmlns:svg="http://www.w3.org/2000/svg"
   xmlns="http://www.w3.org/2000/svg"
   xmlns:xlink="http://www.w3.org/1999/xlink"
   xmlns:sodipodi="http://sodipodi.sourceforge.net/DTD/sodipodi-0.dtd"
   xmlns:inkscape="http://www.inkscape.org/namespaces/inkscape"
   width="285"
   height="200"
   id="svg2"
   version="1.1"
   inkscape:version="0.48.4 r9939"
   sodipodi:docname="corazon1.svg">
  <defs
     id="defs4">
    <inkscape:perspective
       sodipodi:type="inkscape:persp3d"
       inkscape:vp_x="331.11267 : 470.55503 : 1"
       inkscape:vp_y="-114.03555 : 993.47667 : 0"
       inkscape:vp_z="351.78171 : -213.14729 : 0"
       inkscape:persp3d-origin="673.2305 : 245.09276 : 1"
       id="perspective3832" />
  </defs>
  <sodipodi:namedview
     id="base"
     pagecolor="#ffffff"
     bordercolor="#666666"
     borderopacity="1.0"
     inkscape:pageopacity="0.0"
     inkscape:pageshadow="2"
     inkscape:zoom="1"
     inkscape:cx="113.13962"
     inkscape:cy="121.70077"
     inkscape:document-units="px"
     inkscape:current-layer="g3014"
     showgrid="false"
     inkscape:window-width="1286"
     inkscape:window-height="622"
     inkscape:window-x="0"
     inkscape:window-y="376"
     inkscape:window-maximized="0" />
  <metadata
     id="metadata7">
    <rdf:RDF>
      <cc:Work
         rdf:about="">
        <dc:format>image/svg+xml</dc:format>
        <dc:type
           rdf:resource="http://purl.org/dc/dcmitype/StillImage" />
        <dc:title></dc:title>
      </cc:Work>
    </rdf:RDF>
  </metadata>
  <g
     inkscape:label="Capa 1"
     inkscape:groupmode="layer"
     id="layer1"
     transform="translate(0,-852.36217)">
    <g
       style="display:block"
       id="g3014"
       transform="matrix(9.2997748,0,0,9.2997748,281.65476,176.12942)">
      <g
         id="favorite"
         style="fill:#ff2a2a"
         transform="matrix(0.86377488,0.50387791,-0.50387791,0.86377488,-15.607114,69.366951)">
        <path
           id="path3006"
           d="M 12,21.4 10.6,20 C 5.4,15.4 2,12.3 2,8.5 2,5.4 4.4,3 7.5,3 9.2,3 10.9,3.8 12,5.1 13.1,3.8 14.8,3 16.5,3 19.6,3 22,5.4 22,8.5 22,12.3 18.6,15.4 13.4,20 L 12,21.4 z"
           inkscape:connector-curvature="0"
           style="fill:#ff2a2a" />
      </g>
     
      <rect
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3802"
         width="5.5461264"
         height="1.2834011"
         x="-18.125158"
         y="78.652931"
         ry="0.64170057"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         ry="0.64170057"
         y="79.936333"
         x="-17.865423"
         height="1.2834011"
         width="5.5461264"
         id="rect3804"
         style="fill:#ffffff;fill-opacity:1;fill-rule:nonzero;stroke:none"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         ry="0.64170057"
         y="81.189178"
         x="-16.70425"
         height="1.2834011"
         width="5.5461264"
         id="rect3806"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3808"
         width="2.2618349"
         height="1.2834011"
         x="-20.631451"
         y="78.622375"
         ry="0.64170057"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         ry="0.64170057"
         y="78.589966"
         x="-25.879452"
         height="1.2834011"
         width="5.0358133"
         id="rect3810"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3812"
         width="5.5461264"
         height="1.2834011"
         x="-17.09318"
         y="87.844193"
         ry="0.64170057"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         ry="0.64170057"
         y="90.350624"
         x="-15.148534"
         height="1.2834011"
         width="5.5461264"
         id="rect3814"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         style="fill:#ffffff;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3816"
         width="5.5461264"
         height="1.2834011"
         x="-17.043888"
         y="89.140625"
         ry="0.64170057"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)"
         ry="0.64170057"
         y="87.581421"
         x="-24.723297"
         height="1.2834011"
         width="2.2618349"
         id="rect3818"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none" />
      <rect
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3820"
         width="5.0358133"
         height="1.2834011"
         x="-22.31197"
         y="87.651573"
         ry="0.64170057" />
      <rect
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3822"
         width="2.2618349"
         height="1.2834011"
         x="-18.035168"
         y="90.323357"
         ry="0.64170057"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         ry="0.64170057"
         y="90.290947"
         x="-23.283165"
         height="1.2834011"
         width="5.0358133"
         id="rect3824"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)" />
      <rect
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)"
         ry="0.64170057"
         y="81.188286"
         x="-24.60672"
         height="1.2834011"
         width="2.2618349"
         id="rect3826"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none" />
      <rect
         transform="matrix(0.99842403,0.05612006,-0.05612006,0.99842403,0,0)"
         style="fill:#ff2a2a;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="rect3828"
         width="5.0358133"
         height="1.2834011"
         x="-22.072313"
         y="81.176163"
         ry="0.64170057" />
       <path
         sodipodi:type="arc"
         style="fill:#800000;fill-opacity:1;fill-rule:nonzero;stroke:none"
         id="path3018"
         sodipodi:cx="347.22763"
         sodipodi:cy="248.59453"
         sodipodi:rx="8.841444"
         sodipodi:ry="8.841444"
         d="m 356.06907,248.59453 a 8.841444,8.841444 0 1 1 -17.68288,0 8.841444,8.841444 0 1 1 17.68288,0 z"
         transform="matrix(0.09288127,0.05418173,-0.05418173,0.09288127,-30.934836,39.825796)" />
      <path
         transform="matrix(0.09288127,0.05418173,-0.05418173,0.09288127,-26.363112,42.480176)"
         d="m 356.06907,248.59453 a 8.841444,8.841444 0 1 1 -17.68288,0 8.841444,8.841444 0 1 1 17.68288,0 z"
         sodipodi:ry="8.841444"
         sodipodi:rx="8.841444"
         sodipodi:cy="248.59453"
         sodipodi:cx="347.22763"
         id="path3790"
         style="fill:#800000;fill-opacity:1;fill-rule:nonzero;stroke:none"
         sodipodi:type="arc" />
      <path
         transform="matrix(0.25331256,0.14776837,-0.14776837,0.25331256,-62.780156,-28.67167)"
         d="m 356.06907,248.59453 a 8.841444,8.841444 0 1 1 -17.68145,-0.15928"
         sodipodi:ry="8.841444"
         sodipodi:rx="8.841444"
         sodipodi:cy="248.59453"
         sodipodi:cx="347.22763"
         id="path3792"
         style="fill:#800000;fill-opacity:1;fill-rule:nonzero;stroke:none"
         sodipodi:type="arc"
         sodipodi:start="0"
         sodipodi:end="3.1596087"
         sodipodi:open="true" />
 
      <g
         id="g3943"
         transform="matrix(0.99690695,0.07859092,-0.07859092,0.99690695,-22.848116,72.882677)">
        <path
           sodipodi:nodetypes="ccccc"
           inkscape:connector-curvature="0"
           id="rect3924"
           d="m 15.487498,-0.92172966 c 2.959093,0.121571 5.441627,1.095173 7.47666,2.86885266 l -0.425097,0.556348 c -2.4782,-1.79746166 -4.531372,-2.48840266 -7.037575,-2.60571666 z"
           style="fill:#ffd42a;fill-opacity:1;stroke:none" />
        <path
           style="fill:#ffd42a;fill-opacity:1;stroke:none"
           d="M 22.502735,3.531372 C 19.543642,3.409801 17.124113,2.619965 15.089081,0.84628534 l 0.329933,-0.770753 C 17.897214,1.8729943 19.938778,2.597611 22.44498,2.714925 z"
           id="path3928"
           inkscape:connector-curvature="0"
           sodipodi:nodetypes="ccccc" />
        <path
           sodipodi:nodetypes="ccccc"
           inkscape:connector-curvature="0"
           id="rect3935"
           d="m 15.491279,-0.9218567 0.100733,0.82387004 c -0.188049,-0.003 -0.25282,0.07502 -0.156165,0.188037 -0.06678,0.07156 -0.280724,0.61439149 -0.34558,0.75841549 -1.182149,-1.08441001 -0.915368,-1.69656794 0.401012,-1.77032253 z"
           style="fill:#ffd42a;fill-opacity:1;fill-rule:nonzero;stroke:none" />
        <path
           sodipodi:nodetypes="ccccc"
           inkscape:connector-curvature="0"
           id="rect3938"
           d="m 22.964159,1.955525 c 0.678057,0.667502 0.448336,1.5161474 -0.472544,1.572514 l -0.04725,-0.811196 c 0.127279,-0.01981 0.167677,-0.09879 0.08179,-0.229522 z"
           style="fill:#ffd42a;fill-opacity:1;fill-rule:nonzero;stroke:none" />
      </g>
    </g>
  </g>

  </svg>
  <br />
 


  <div class="flip_letters">
    <span style="--flip:1">F</span>
    <span style="--flip:2">E</span>
    <span style="--flip:3">L</span>
    <span style="--flip:4">I</span>
    <span style="--flip:5">Z</span>
    <span style="--flip:6">&#x2665;</span>
    <span style="--flip:7">D</span>
    <span style="--flip:8">I</span>
    <span style="--flip:9">A</span>
    <span style="--flip:10">&#x2665;</span>
    <span style="--flip:11">M</span>
    <span style="--flip:12">A</span>
    <span style="--flip:13">M</span>
    <span style="--flip:14">Á</span>
   </div>

</div>



<div class="carousel-product">
 
    <div class="swiper-container mySwiper">
      <div class="swiper-wrapper">
        <div class="swiper-slide">
          <img src="file:///D:/PRUEBAS%20HTML/IMG/mama.jpg" />
        </div>
        <div class="swiper-slide">
          <img src="file:///D:/PRUEBAS%20HTML/IMG/mama1.jpg" />
        </div>
        
        <div class="swiper-slide">
          <img src="file:///D:/PRUEBAS%20HTML/IMG/mama2.jpg" />
        </div>
        
      </div>
      <div class="swiper-pagination"></div>
    </div>
</div>

 


    <script src="https://unpkg.com/swiper/swiper-bundle.min.js"></script>
  <!-- <audio controls autoplay id="music">
  <source src="https://drive.google.com/uc?id=1-d1ysEfUVj0nCT117PIxf6m6pTNDc8Tg&export=download" type="audio/mp3">
</audio>   -->
    <script>
        var swiper = new Swiper(".mySwiper", {
        effect: "coverflow",
        grabCursor: true,
        centeredSlides: true,
        slidesPerView: "auto",
        autoplay:true,
        loop:true,
        coverflowEffect: {
          rotate: 50,
          stretch: 0,
          depth: 100,
          modifier: 1,
          slideShadows: true,
        },
        pagination: {
          el: ".swiper-pagination",
        },
      });


var canvas = document.querySelector("canvas"),
  ctx = canvas.getContext("2d");

var ww,wh;

function onResize(){
  ww = canvas.width = window.innerWidth;
  wh = canvas.height = window.innerHeight;
}

ctx.strokeStyle = "red";
ctx.shadowBlur = 25;
ctx.shadowColor = "hsla(0, 100%, 60%,0.5)";

var precision = 100;
var hearts = [];
var mouseMoved = false;
function onMove(e){
  mouseMoved = true;
  if(e.type === "touchmove"){
    hearts.push(new Heart(e.touches[0].clientX, e.touches[0].clientY));
    hearts.push(new Heart(e.touches[0].clientX, e.touches[0].clientY));
  }
  else{
    hearts.push(new Heart(e.clientX, e.clientY));
    hearts.push(new Heart(e.clientX, e.clientY));
  }
}

var Heart = function(x,y){
  this.x = x || Math.random()*ww;
  this.y = y || Math.random()*wh;
  this.size = Math.random()*2 + 1;
  this.shadowBlur = Math.random() * 10;
  this.speedX = (Math.random()+0.2-0.6) * 8;
  this.speedY = (Math.random()+0.2-0.6) * 8;
  this.speedSize = Math.random()*0.05 + 0.01;
  this.opacity = 1;
  this.vertices = [];
  for (var i = 0; i < precision; i++) {
    var step = (i / precision - 0.5) * (Math.PI * 2);
    var vector = {
      x : (15 * Math.pow(Math.sin(step), 3)),
      y : -(13 * Math.cos(step) - 5 * Math.cos(2 * step) - 2 * Math.cos(3 * step) - Math.cos(4 * step)) 
    }
    this.vertices.push(vector);
  }
}

Heart.prototype.draw = function(){
  this.size -= this.speedSize;
  this.x += this.speedX;
  this.y += this.speedY;
  ctx.save();
  ctx.translate(-1000,this.y);
  ctx.scale(this.size, this.size);
  ctx.beginPath();
  for (var i = 0; i < precision; i++) {
    var vector = this.vertices[i];
    ctx.lineTo(vector.x, vector.y);
  }
  ctx.globalAlpha = this.size;
  ctx.shadowBlur = Math.round((3 - this.size) * 10);
  ctx.shadowColor = "hsla(0, 100%, 60%,0.5)";
  ctx.shadowOffsetX = this.x + 1000;
  ctx.globalCompositeOperation = "screen"
  ctx.closePath();
  ctx.fill()
  ctx.restore();
};


function render(a){
  requestAnimationFrame(render);
  
  hearts.push(new Heart())
  ctx.clearRect(0,0,ww,wh);
  for (var i = 0; i < hearts.length; i++) {
    hearts[i].draw();
    if(hearts[i].size <= 0){
      hearts.splice(i,1);
      i--;
    }
  }
}



onResize();
window.addEventListener("mousemove", onMove);
window.addEventListener("touchmove", onMove);
window.addEventListener("resize", onResize);
requestAnimationFrame(render);

var play = document.getElementById('music')
play.autoplay
    </script>
</body>
</html>
