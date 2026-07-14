<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>SEMINAR</title>
<style>
  body{background:#111;color:#fff;font-family:sans-serif;text-align:center;padding:20px}
  .grid{display:grid;grid-template-columns:repeat(5,70px);gap:15px;justify-content:center;margin-bottom:20px}
  .num{background:#222;border:2px solid #555;border-radius:10px;width:70px;height:70px;
       font-size:24px;color:#fff;cursor:pointer;display:flex;align-items:center;justify-content:center;
       transition:transform .2s, background .2s}
  .num:hover{background:#444}
  .num.pop{animation:pop .35s ease}
  @keyframes pop{
    0%{transform:scale(1)}
    40%{transform:scale(1.3);background:#0a84ff}
    100%{transform:scale(0)}
  }
  .num.used{background:#111;border-color:#333;color:#555;cursor:not-allowed;position:relative}
  .num.used::after{content:"✕";position:absolute;color:red;font-size:28px}
  .grid.hidden{display:none}
  video{display:none;width:90%;max-width:600px;margin-top:10px;background:#000}
  video.show{display:block}
  #back{display:none;margin-top:15px;padding:8px 20px;background:#333;color:#fff;
        border:none;border-radius:6px;cursor:pointer;font-size:16px}
  #back.show{display:inline-block}
  footer{margin-top:30px;color:#888;font-size:13px}
</style>
</head>
<body>

<h2>NUMTRIX 😆</h2>
<div class="grid" id="grid"></div>
<video id="player" controls autoplay></video>
<button id="back">⬅ Back</button>

<footer>Project Organized by S5 BCA Students — Goutham, Yadhu, Justin, Anju, Suryagayathri</footer>

<script>
// video src map. edit path/url per number.
const videos = {
  1:"video1.mp4",
  2:"video2.mp4",
  3:"video3.mp4",
  4:"video4.mp4",
  5:"video5.mp4",
  6:"video6.mp4",
  7:"video7.mp4",
  8:"video8.mp4",
  9:"video9.mp4",
  10:"video10.mp4"
};

const grid = document.getElementById('grid');
const player = document.getElementById('player');
const backBtn = document.getElementById('back');
const used = new Set(); // numbers already picked

for(let i=1;i<=10;i++){
  const btn = document.createElement('div');
  btn.className='num';
  btn.textContent=i;
  btn.onclick=()=>{
    if(used.has(i)) return; // already used, ignore click
    btn.classList.add('pop');
    setTimeout(()=>{
      used.add(i);
      btn.textContent='';
      btn.classList.remove('pop');
      btn.classList.add('used');
      grid.classList.add('hidden');
      player.src = videos[i];
      player.classList.add('show');
      player.play();
      backBtn.classList.add('show');
    },300);
  };
  grid.appendChild(btn);
}

backBtn.onclick=()=>{
  player.pause();
  player.classList.remove('show');
  backBtn.classList.remove('show');
  grid.classList.remove('hidden'); // used numbers stay marked, X persists
};
</script>

</body>
</html>
