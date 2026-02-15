<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Tug of War: Mathematics 🧮</title>
<style>
*{box-sizing:border-box}
body{margin:0;font-family:Segoe UI,system-ui;background:#eef2f7}
.header{display:flex;justify-content:space-between;align-items:center;padding:10px 16px;background:#fff;border-bottom:2px solid #ddd}
.header h1{font-size:18px;margin:0}
.timer{font-size:18px;font-weight:700}

.controls{display:flex;gap:10px}
.controls select,.controls input{padding:6px 8px;font-size:14px}

.game{display:grid;grid-template-columns:1fr 1.2fr 1fr;height:calc(100vh - 60px)}
.team{padding:16px;display:flex;flex-direction:column;justify-content:space-between}
.team.blue{background:#e3f2fd}
.team.red{background:#ffebee}
.team-title{font-size:20px;font-weight:700;text-align:center}
.question{font-size:34px;font-weight:800;text-align:center;margin:14px 0}
.answer{font-size:26px;text-align:center;background:#fff;padding:8px;border-radius:10px}
.keypad{display:grid;grid-template-columns:repeat(3,1fr);gap:8px}
.keypad button{font-size:20px;padding:14px;border-radius:12px;border:none;cursor:pointer}
.keypad .ok{grid-column:span 3;background:#4caf50;color:#fff;font-weight:700}

.center{display:flex;flex-direction:column;align-items:center;justify-content:center;background:#fff;position:relative}
.characters{display:flex;gap:20px;font-size:56px;transition:transform .4s}
.characters.pull-left{transform:translateX(-12px)}
.characters.pull-right{transform:translateX(12px)}
.rope-track{width:80%;height:8px;background:#ccc;border-radius:8px;margin-top:10px}
.rope{width:20px;height:26px;background:#ffca28;border-radius:10px;position:relative;left:50%;transform:translateX(-50%);transition:left .3s}
.winner{margin-top:14px;font-size:26px;font-weight:800;animation:pop .6s}
@keyframes pop{from{transform:scale(.7);opacity:0}to{transform:scale(1);opacity:1}}
</style>
</head>
<body>

<div class="header">
  <h1>🧮 Tug of War: Mathematics</h1>
  <div class="controls">
    <select id="level">
      <option value="10">Easy</option>
      <option value="20">Medium</option>
      <option value="50">Hard</option>
    </select>
    <input type="number" id="timeSet" value="30" min="10" />
    <select id="op">
      <option value="+">+</option>
      <option value="-">-</option>
      <option value="*">×</option>
    </select>
  </div>
  <div class="timer" id="timer">⏱️ 30</div>
</div>

<div class="game">
  <div class="team blue">
    <div class="team-title">🔵 Team 1</div>
    <div class="question" id="q1"></div>
    <div class="answer" id="a1">0</div>
    <div class="keypad" id="pad1"></div>
  </div>

  <div class="center">
    <div class="characters" id="chars">
  <!-- Team 1 (Blue) -->
  <svg width="180" height="140" viewBox="0 0 180 140">
    <g id="blueTeam">
      <!-- Kid 1 -->
      <circle cx="40" cy="25" r="10" fill="#1976d2" />
      <rect x="30" y="35" width="20" height="30" rx="5" fill="#1976d2" />
      <line x1="50" y1="45" x2="85" y2="55" stroke="#795548" stroke-width="4" />
      <line x1="35" y1="65" x2="30" y2="95" stroke="#000" stroke-width="3" />
      <line x1="45" y1="65" x2="40" y2="95" stroke="#000" stroke-width="3" />
      <rect x="25" y="95" width="15" height="8" fill="#555" />
      <rect x="35" y="95" width="15" height="8" fill="#555" />

      <!-- Kid 2 -->
      <circle cx="70" cy="25" r="10" fill="#1976d2" />
      <rect x="60" y="35" width="20" height="30" rx="5" fill="#1976d2" />
      <line x1="80" y1="45" x2="85" y2="55" stroke="#795548" stroke-width="4" />
      <line x1="65" y1="65" x2="60" y2="95" stroke="#000" stroke-width="3" />
      <line x1="75" y1="65" x2="70" y2="95" stroke="#000" stroke-width="3" />
      <rect x="55" y="95" width="15" height="8" fill="#555" />
      <rect x="65" y="95" width="15" height="8" fill="#555" />
    </g>
  </svg>

  <!-- Rope -->
  <div style="font-size:26px">🪢</div>

  <!-- Team 2 (Red) -->
  <svg width="180" height="140" viewBox="0 0 180 140">
    <g id="redTeam" transform="translate(40,0)">
      <!-- Kid 1 -->
      <circle cx="40" cy="25" r="10" fill="#d32f2f" />
      <rect x="30" y="35" width="20" height="30" rx="5" fill="#d32f2f" />
      <line x1="30" y1="45" x2="5" y2="55" stroke="#795548" stroke-width="4" />
      <line x1="35" y1="65" x2="30" y2="95" stroke="#000" stroke-width="3" />
      <line x1="45" y1="65" x2="40" y2="95" stroke="#000" stroke-width="3" />
      <rect x="25" y="95" width="15" height="8" fill="#555" />
      <rect x="35" y="95" width="15" height="8" fill="#555" />

      <!-- Kid 2 -->
      <circle cx="70" cy="25" r="10" fill="#d32f2f" />
      <rect x="60" y="35" width="20" height="30" rx="5" fill="#d32f2f" />
      <line x1="60" y1="45" x2="5" y2="55" stroke="#795548" stroke-width="4" />
      <line x1="65" y1="65" x2="60" y2="95" stroke="#000" stroke-width="3" />
      <line x1="75" y1="65" x2="70" y2="95" stroke="#000" stroke-width="3" />
      <rect x="55" y="95" width="15" height="8" fill="#555" />
      <rect x="65" y="95" width="15" height="8" fill="#555" />
    </g>
  </svg>
</div>
    <div class="rope-track"><div class="rope" id="rope"></div></div>
    <div class="winner" id="winner"></div>
  </div>

  <div class="team red">
    <div class="team-title">🔴 Team 2</div>
    <div class="question" id="q2"></div>
    <div class="answer" id="a2">0</div>
    <div class="keypad" id="pad2"></div>
  </div>
</div>

<audio id="correct" src="https://assets.mixkit.co/sfx/preview/mixkit-game-click-1114.mp3"></audio>
<audio id="win" src="https://assets.mixkit.co/sfx/preview/mixkit-animated-small-group-applause-523.mp3"></audio>

<script>
let rope=50,playing=true,time;
let ans1,ans2,in1='',in2='';

function rand(max){return Math.floor(Math.random()*max)+1}
function gen(team){const max=+level.value;const a=rand(max),b=rand(max);const o=op.value;let r=o==='+'?a+b:o==='-'?a-b:a*b;if(team===1){ans1=r;q1.innerText=`${a} ${o} ${b}`;}else{ans2=r;q2.innerText=`${a} ${o} ${b}`;}}

function pad(team){const p=document.getElementById(team===1?'pad1':'pad2');p.innerHTML='';for(let i=1;i<=9;i++)btn(i);btn(0);const ok=document.createElement('button');ok.innerText='✔';ok.className='ok';ok.onclick=()=>check(team);p.appendChild(ok);function btn(n){let b=document.createElement('button');b.innerText=n;b.onclick=()=>add(team,n);p.appendChild(b)}}

function add(t,n){if(!playing)return;t===1?(in1+=n,a1.innerText=in1):(in2+=n,a2.innerText=in2)}

function check(t){if(!playing)return;if(t===1&&+in1===ans1){rope-=5;chars.classList.add('pull-left');correct.play()}
if(t===2&&+in2===ans2){rope+=5;chars.classList.add('pull-right');correct.play()}
setTimeout(()=>chars.classList.remove('pull-left','pull-right'),300);in1=in2='';a1.innerText=a2.innerText='0';update();gen(t)}

function update(){rope=Math.max(0,Math.min(100,rope));ropeEl.style.left=rope+'%';if(rope<=0)end('🏆 Team 1 Wins!');if(rope>=100)end('🏆 Team 2 Wins!')}

function end(t){playing=false;winner.innerText=t;win.play();setTimeout(reset,4000)}

function reset(){rope=50;winner.innerText='';playing=true;time=+timeSet.value;timer.innerText='⏱️ '+time;gen(1);gen(2)}

setInterval(()=>{if(!playing)return;time--;timer.innerText='⏱️ '+time;if(time<=0)end('⏰ Time Up!')},1000)

const q1=document.getElementById('q1'),q2=document.getElementById('q2'),a1=document.getElementById('a1'),a2=document.getElementById('a2');
const ropeEl=document.getElementById('rope'),winner=document.getElementById('winner'),timer=document.getElementById('timer'),level=document.getElementById('level'),op=document.getElementById('op'),timeSet=document.getElementById('timeSet'),chars=document.getElementById('chars');

pad(1);pad(2);reset();
</script>
</body>
</html>
