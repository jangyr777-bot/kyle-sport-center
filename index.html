<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<title>Kyle Hockey V5</title>

<style>
*{box-sizing:border-box;touch-action:none;user-select:none;-webkit-user-select:none}
body{
 margin:0;background:#071421;color:white;
 font-family:-apple-system,BlinkMacSystemFont,Arial;
 text-align:center;overflow:hidden;
}
#header{height:75px;padding-top:4px}
#title{font-size:18px;font-weight:900}
#score{font-size:27px;font-weight:900}
#timer{font-size:14px}

#rink{
 position:relative;width:94vw;height:57vh;margin:auto;
 background:#eafaff;border:5px solid #1976c9;
 border-radius:25px;overflow:hidden;
}

.line{position:absolute;left:0;width:100%;height:4px;opacity:.6}
#redline{top:50%;background:#e84c57}
#blue1{top:27%;background:#287fd1}
#blue2{top:73%;background:#287fd1}
#circle{
 position:absolute;left:50%;top:50%;width:100px;height:100px;
 border:4px solid #e84c57;border-radius:50%;
 transform:translate(-50%,-50%);
}

/* NET */

#goal{
 position:absolute;top:0;left:32%;width:36%;height:52px;
 border-left:7px solid #d82434;
 border-right:7px solid #d82434;
 border-bottom:7px solid #d82434;
 border-radius:0 0 14px 14px;
 background:repeating-linear-gradient(
 45deg,transparent,transparent 7px,#8884 8px,#8884 10px
 );
}

/* GOALIE */

#goalie{
 position:absolute;top:48px;width:48px;height:45px;
 transform:translateX(-50%);z-index:5;
}
.mask{
 position:absolute;left:14px;width:20px;height:20px;
 border-radius:50%;background:white;border:3px solid #222;
}
.gbody{
 position:absolute;top:17px;left:5px;width:38px;height:24px;
 background:#e52f3f;border:2px solid white;border-radius:8px;
}
.pad{
 position:absolute;top:31px;width:12px;height:19px;
 background:white;border:2px solid #555;border-radius:4px;
}
.padL{left:5px}.padR{right:5px}

/* PLAYER */

#player{
 position:absolute;width:48px;height:55px;
 transform:translate(-50%,-50%);z-index:8;
 transition:transform .08s;
}
.head{
 position:absolute;left:13px;width:20px;height:20px;
 background:#16202a;border:3px solid white;border-radius:50%;
}
.body{
 position:absolute;left:7px;top:17px;width:32px;height:28px;
 background:#1676d2;border:2px solid white;border-radius:8px;
}
#stick{
 position:absolute;left:30px;top:36px;width:40px;height:5px;
 background:#9a6230;border-radius:5px;
 transform:rotate(-25deg);transform-origin:left;
}

/* CPU */

#cpu{
 position:absolute;width:46px;height:52px;
 transform:translate(-50%,-50%);z-index:6;
}
.cpuHead{
 position:absolute;left:13px;width:20px;height:20px;
 background:#222;border:3px solid white;border-radius:50%;
}
.cpuBody{
 position:absolute;left:7px;top:17px;width:32px;height:28px;
 background:#ef3e45;border:2px solid white;border-radius:8px;
}
.cpuStick{
 position:absolute;right:29px;top:36px;width:38px;height:5px;
 background:#8b592c;transform:rotate(25deg);
}

/* PUCK */

#puck{
 position:absolute;width:19px;height:11px;background:#111;
 border-radius:50%;transform:translate(-50%,-50%);z-index:10;
}

#message{
 position:absolute;top:41%;width:100%;color:#071421;
 font-size:35px;font-weight:1000;text-shadow:0 2px white;
 z-index:20;pointer-events:none;
}

/* CONTROLS */

#controls{position:relative;height:210px}

#dpad{
 position:absolute;left:10px;top:5px;width:180px;height:125px;
}
.btn{
 position:absolute;width:56px;height:56px;border:0;
 border-radius:17px;background:white;font-size:24px;
 box-shadow:0 3px 8px #0006;
}
.btn:active{transform:scale(.88)}
#up{left:61px;top:0}
#left{left:0;top:58px}
#down{left:61px;top:58px}
#right{left:122px;top:58px}

#shoot{
 position:absolute;right:17px;top:18px;width:103px;height:68px;
 border:0;border-radius:50%;background:#ff3b30;color:white;
 font-size:17px;font-weight:900;
}

#toe{
 position:absolute;right:130px;top:130px;
 width:105px;height:48px;border:0;border-radius:15px;
 background:#21a5e8;color:white;font-weight:900;
}

#turn{
 position:absolute;right:15px;top:130px;
 width:105px;height:48px;border:0;border-radius:15px;
 background:#9146ff;color:white;font-weight:900;
}

.special:disabled{opacity:.35}

</style>
</head>

<body>

<div id="header">
 <div id="title">🏒 KYLE HOCKEY V5</div>
 <div id="score">YOU 0 : 0 CPU</div>
 <div id="timer">⏱️ 60 SECONDS LEFT</div>
</div>

<div id="rink">

 <div id="goal"></div>
 <div class="line" id="blue1"></div>
 <div class="line" id="redline"></div>
 <div class="line" id="blue2"></div>
 <div id="circle"></div>

 <div id="goalie">
  <div class="mask"></div>
  <div class="gbody"></div>
  <div class="pad padL"></div>
  <div class="pad padR"></div>
 </div>

 <div id="cpu">
  <div class="cpuHead"></div>
  <div class="cpuBody"></div>
  <div class="cpuStick"></div>
 </div>

 <div id="player">
  <div class="head"></div>
  <div class="body"></div>
  <div id="stick"></div>
 </div>

 <div id="puck"></div>
 <div id="message"></div>

</div>

<div id="controls">

 <div id="dpad">
  <button class="btn" id="up">▲</button>
  <button class="btn" id="left">◀</button>
  <button class="btn" id="down">▼</button>
  <button class="btn" id="right">▶</button>
 </div>

 <button id="shoot">🔥<br>SHOOT</button>
 <button class="special" id="toe">🏒 TOE DRAG</button>
 <button class="special" id="turn">🌀 TURN</button>

</div>

<script>

const player=document.getElementById("player");
const cpu=document.getElementById("cpu");
const puck=document.getElementById("puck");
const goalie=document.getElementById("goalie");
const stick=document.getElementById("stick");

const message=document.getElementById("message");
const score=document.getElementById("score");
const timer=document.getElementById("timer");

const toeButton=document.getElementById("toe");
const turnButton=document.getElementById("turn");

/* GAME STATE */

let playerX=50;
let playerY=82;

let cpuX=25;
let cpuY=43;

let goalieX=50;

let puckX=57;
let puckY=82;

let puckVX=0;
let puckVY=0;

let moveX=0;
let moveY=0;

let lastX=0;
let lastY=-1;

let possession=true;
let puckFlying=false;

let playerScore=0;
let cpuScore=0;

let seconds=60;

let gameOver=false;
let resetting=false;
let celebrating=false;

let toeReady=true;
let turnReady=true;

let cpuConfused=0;

/* DRAW */

function draw(){

 player.style.left=playerX+"%";
 player.style.top=playerY+"%";

 cpu.style.left=cpuX+"%";
 cpu.style.top=cpuY+"%";

 goalie.style.left=goalieX+"%";

 if(possession){
   puckX=playerX+7;
   puckY=playerY+5;
 }

 puck.style.left=puckX+"%";
 puck.style.top=puckY+"%";
}

/* D-PAD */

function setupButton(id,x,y){

 const b=document.getElementById(id);

 b.addEventListener("touchstart",e=>{
   e.preventDefault();

   if(celebrating)return;

   moveX=x;
   moveY=y;

   lastX=x;
   lastY=y;
 },{passive:false});

 b.addEventListener("touchend",e=>{
   e.preventDefault();
   moveX=0;
   moveY=0;
 },{passive:false});

 b.addEventListener("touchcancel",()=>{
   moveX=0;
   moveY=0;
 });
}

setupButton("up",0,-1);
setupButton("down",0,1);
setupButton("left",-1,0);
setupButton("right",1,0);

/* PLAYER */

function updatePlayer(){

 if(gameOver||resetting||celebrating)return;

 playerX+=moveX*.37;
 playerY+=moveY*.37;

 playerX=Math.max(4,Math.min(96,playerX));
 playerY=Math.max(16,Math.min(91,playerY));
}

/* CPU DEFENDER */

function updateCPU(){

 if(gameOver||resetting||celebrating)return;

 let targetX=possession ? playerX : puckX;
 let targetY=possession ? playerY : puckY;

 let dX=targetX-cpuX;
 let dY=targetY-cpuY;

 let distance=Math.sqrt(dX*dX+dY*dY);

 /*
 Faster CPU.
 Toe drag / turn temporarily fools him.
 */

 let cpuSpeed=.17;

 if(cpuConfused>0){
   cpuSpeed=.035;
   cpuConfused--;
 }

 if(distance>1){
   cpuX+=(dX/distance)*cpuSpeed;
   cpuY+=(dY/distance)*cpuSpeed;
 }

 cpuX=Math.max(5,Math.min(95,cpuX));
 cpuY=Math.max(17,Math.min(86,cpuY));

 if(possession && distance<3.8 && cpuConfused<=0){

   possession=false;

   message.innerHTML="💥 CPU STEAL!";

   setTimeout(resetRound,600);
 }
}

/* GOALIE */

function updateGoalie(){

 if(gameOver||resetting||celebrating)return;

 let target=possession ? playerX : puckX;

 /*
 Faster than V4, slower than original impossible goalie.
 */

 if(target>goalieX+2){
   goalieX+=.105;
 }

 if(target<goalieX-2){
   goalieX-=.105;
 }

 goalieX=Math.max(34,Math.min(66,goalieX));
}

/* SHOOT */

function shoot(){

 if(!possession||puckFlying||gameOver||resetting||celebrating)return;

 possession=false;
 puckFlying=true;

 puckX=playerX+7;
 puckY=playerY;

 /*
 Slight aiming.
 Shoot roughly toward where you're lined up.
 */

 let goalTarget=playerX;

 if(goalTarget<35) goalTarget=38;
 if(goalTarget>65) goalTarget=62;

 puckVX=(goalTarget-puckX)/35;
 puckVY=-1.25;
}

document.getElementById("shoot")
.addEventListener("touchstart",e=>{
 e.preventDefault();
 shoot();
},{passive:false});

/* TOE DRAG */

function toeDrag(){

 if(!toeReady||!possession||gameOver||resetting||celebrating)return;

 toeReady=false;
 toeButton.disabled=true;

 /*
 Pull puck/player sideways depending
 on defender position.
 */

 let direction =
 cpuX<=playerX ? 1 : -1;

 playerX+=direction*8;

 playerX=Math.max(6,Math.min(94,playerX));

 puckX=playerX+(direction*8);

 cpuConfused=32;

 stick.style.transform=
 direction>0
 ? "rotate(25deg)"
 : "rotate(-65deg)";

 message.innerHTML="🏒 TOE DRAG!";

 setTimeout(()=>{
   stick.style.transform="rotate(-25deg)";
   message.innerHTML="";
 },300);

 setTimeout(()=>{
   toeReady=true;
   toeButton.disabled=false;
 },1800);
}

toeButton.addEventListener("touchstart",e=>{
 e.preventDefault();
 toeDrag();
},{passive:false});

/* McDAVID TURN */

function mcdavidTurn(){

 if(!turnReady||!possession||gameOver||resetting||celebrating)return;

 turnReady=false;
 turnButton.disabled=true;

 /*
 Burst away from defender.
 */

 let awayX=playerX-cpuX;
 let awayY=playerY-cpuY;

 let distance=Math.sqrt(
 awayX*awayX+
 awayY*awayY
 )||1;

 playerX+=(awayX/distance)*9;
 playerY+=(awayY/distance)*9;

 playerX=Math.max(6,Math.min(94,playerX));
 playerY=Math.max(18,Math.min(89,playerY));

 cpuConfused=42;

 player.style.transition="transform .35s";
 player.style.transform=
 "translate(-50%,-50%) rotate(360deg)";

 message.innerHTML="🌀 McDAVID TURN!";

 setTimeout(()=>{
   player.style.transition="transform .08s";
   player.style.transform="translate(-50%,-50%)";
   message.innerHTML="";
 },380);

 setTimeout(()=>{
   turnReady=true;
   turnButton.disabled=false;
 },2200);
}

turnButton.addEventListener("touchstart",e=>{
 e.preventDefault();
 mcdavidTurn();
},{passive:false});

/* PUCK */

function updatePuck(){

 if(possession||!puckFlying||gameOver||resetting||celebrating)return;

 puckX+=puckVX;
 puckY+=puckVY;

 /* DEFENDER BLOCK */

 let cdx=puckX-cpuX;
 let cdy=puckY-cpuY;

 let cpuDistance=Math.sqrt(cdx*cdx+cdy*cdy);

 if(cpuDistance<3.3){

   puckFlying=false;
   message.innerHTML="🤖 BLOCKED!";

   setTimeout(resetRound,550);
   return;
 }

 /* GOALIE SAVE */

 if(
 puckY<15 &&
 puckY>6 &&
 Math.abs(puckX-goalieX)<5.3
 ){
   puckFlying=false;

   message.innerHTML="🧤 SAVE!";

   setTimeout(resetRound,650);
   return;
 }

 /* GOAL */

 if(
 puckY<=5 &&
 puckX>32 &&
 puckX<68
 ){
   puckFlying=false;
   playerScore++;

   updateScore();

   celebrateGoal();

   return;
 }

 /* MISS */

 if(puckY<-3){

   puckFlying=false;
   message.innerHTML="💨 WIDE!";

   setTimeout(resetRound,550);
 }
}

/* BOW + ARROW CELEBRATION */

function celebrateGoal(){

 celebrating=true;

 moveX=0;
 moveY=0;

 message.innerHTML="🚨 GOAL!!!";

 /*
 Player skates away from goal first.
 */

 let celebrationMove=setInterval(()=>{

   playerY+=.6;

   if(playerY>68){
     clearInterval(celebrationMove);

     arrowCelebration();
   }

 },16);
}

function arrowCelebration(){

 message.innerHTML="🏹 CELLY!";

 /*
 Turn sideways
 */

 player.style.transition="transform .25s";
 player.style.transform=
 "translate(-50%,-50%) rotate(-25deg) scale(1.15)";

 /*
 Stick becomes the 'bow/arrow' motion.
 */

 stick.style.transition="transform .25s";
 stick.style.transform=
 "rotate(-100deg) translateX(10px)";

 setTimeout(()=>{

   stick.style.transform=
   "rotate(10deg) translateX(25px)";

 },300);

 setTimeout(()=>{

   player.style.transform=
   "translate(-50%,-50%) rotate(20deg) scale(1.15)";

   message.innerHTML="🏹💥";

 },600);

 setTimeout(()=>{

   player.style.transform=
   "translate(-50%,-50%)";

   stick.style.transform=
   "rotate(-25deg)";

   celebrating=false;

   resetRound();

 },1200);
}

/* SCORE */

function updateScore(){
 score.innerHTML=
 "YOU "+playerScore+
 " : "+
 cpuScore+
 " CPU";
}

/* RESET */

function resetRound(){

 if(gameOver)return;

 resetting=true;

 playerX=50;
 playerY=82;

 cpuX=20+Math.random()*60;
 cpuY=36+Math.random()*13;

 goalieX=50;

 puckX=57;
 puckY=82;

 puckVX=0;
 puckVY=0;

 moveX=0;
 moveY=0;

 puckFlying=false;

 setTimeout(()=>{

   possession=true;
   resetting=false;
   message.innerHTML="";

 },250);
}

/* TIMER */

const clock=setInterval(()=>{

 if(gameOver||celebrating)return;

 seconds--;

 if(seconds<0)seconds=0;

 timer.innerHTML=
 "⏱️ "+seconds+" SECONDS LEFT";

 if(seconds<=0){

   gameOver=true;

   clearInterval(clock);

   moveX=0;
   moveY=0;

   if(playerScore>cpuScore){
     message.innerHTML="🏆 YOU WIN!";
   }
   else if(playerScore<cpuScore){
     message.innerHTML="🤖 CPU WINS!";
   }
   else{
     message.innerHTML="🤝 TIE GAME";
   }
 }

},1000);

/* LOOP */

function loop(){

 updatePlayer();
 updateCPU();
 updateGoalie();
 updatePuck();

 draw();

 requestAnimationFrame(loop);
}

draw();
loop();

</script>
</body>
</html>
