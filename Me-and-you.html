<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<title>ME & YOU</title>
<style>
  *{box-sizing:border-box;-webkit-tap-highlight-color:transparent}
  html,body{margin:0;width:100%;height:100%;overflow:hidden;background:#07090d;color:#f4f4f1;font-family:Arial,"Noto Sans Thai",sans-serif}
  body{touch-action:pan-y}
  #stars{position:fixed;inset:0;overflow:hidden;pointer-events:none}
  .star{position:absolute;width:2px;height:2px;background:#fff;border-radius:50%;opacity:.45;animation:twinkle 3s infinite ease-in-out}
  @keyframes twinkle{50%{opacity:.1;transform:scale(.7)}}
  .shooting{position:absolute;width:90px;height:1px;background:linear-gradient(90deg,transparent,#fff,transparent);opacity:0;transform:rotate(-28deg);animation:shoot 1.8s ease-out forwards}
  @keyframes shoot{0%{opacity:0;transform:translate(0,0) rotate(-28deg)}15%{opacity:.9}100%{opacity:0;transform:translate(-260px,150px) rotate(-28deg)}}

  #app{height:100%;position:relative}
  .slide{
    position:absolute;inset:0;padding:28px 22px calc(34px + env(safe-area-inset-bottom));
    display:flex;flex-direction:column;justify-content:center;align-items:center;
    text-align:center;opacity:0;transform:translateX(100%) scale(.985);
    transition:transform .65s cubic-bezier(.22,.7,.2,1),opacity .5s ease;
    pointer-events:none;
  }
  .slide.active{opacity:1;transform:translateX(0) scale(1);pointer-events:auto}
  .slide.prev{opacity:0;transform:translateX(-100%) scale(.985)}
  .cover h1{font-size:clamp(46px,14vw,82px);letter-spacing:.12em;font-weight:500;margin:0 0 18px}
  .eyebrow{font-size:11px;letter-spacing:.28em;text-transform:uppercase;opacity:.5}
  .hint{font-size:12px;opacity:.48;margin-top:35px}
  .line{width:34px;height:1px;background:#777;margin:20px auto;opacity:.7}
  .date{font-size:11px;letter-spacing:.2em;opacity:.48;margin-bottom:18px}
  .text{max-width:520px;line-height:1.95;font-size:15px;color:#e8e8e4}
  .text strong{font-size:20px;font-weight:500;display:inline-block;margin-top:7px}
  .small{font-size:12px;opacity:.48;letter-spacing:.08em}
  .polaroid{
    width:min(78vw,330px);background:#eeeae1;padding:10px 10px 30px;
    box-shadow:0 16px 45px rgba(0,0,0,.4);transform:rotate(-1.5deg);margin-bottom:24px;
  }
  .polaroid img{display:block;width:100%;aspect-ratio:4/5;object-fit:cover;background:#d8d5ce}
  .polaroid .caption{color:#252525;font-size:10px;letter-spacing:.12em;margin-top:12px}
  .film-grid{
    width:min(88vw,420px);display:grid;grid-template-columns:1fr 1fr;gap:8px;
    padding:10px;background:#e9e5dc;box-shadow:0 18px 45px rgba(0,0,0,.38);margin-bottom:20px;
  }
  .film-grid img{width:100%;aspect-ratio:1/1;object-fit:cover;background:#d3d0c9}
  .nav{position:fixed;bottom:15px;left:50%;transform:translateX(-50%);z-index:20;display:flex;gap:10px;align-items:center}
  .dot{width:4px;height:4px;border-radius:50%;background:#777;transition:.3s}
  .dot.active{width:18px;border-radius:3px;background:#eee}
  #music{
    position:fixed;right:16px;top:calc(15px + env(safe-area-inset-top));z-index:30;
    width:38px;height:38px;border:1px solid #555;border-radius:50%;background:#0b0d12;color:#fff;
    font-size:14px;display:none
  }
  .choice{
    border:1px solid #777;background:transparent;color:#fff;padding:13px 22px;border-radius:999px;
    font-size:13px;letter-spacing:.05em;margin-top:24px;cursor:pointer
  }
  .choice:active{transform:scale(.96)}
  .final .question{font-size:clamp(27px,8vw,44px);font-weight:400;line-height:1.35;margin:10px 0}
  .final .choice{border-color:#aaa}
  .final-message{display:none;margin-top:30px;font-size:18px;line-height:1.8}
  .final-message.show{display:block;animation:fadeUp 1.4s ease both}
  @keyframes fadeUp{from{opacity:0;transform:translateY(20px)}to{opacity:1;transform:none}}
  .footer-note{position:absolute;bottom:35px;font-size:10px;opacity:.3;letter-spacing:.12em}
</style>
</head>
<body>
<div id="stars"></div>

<audio id="musicAudio" src="halley.mp3" loop preload="auto"></audio>
<button id="music" aria-label="เปิดปิดเพลง">♫</button>

<main id="app">

<section class="slide cover active">
  <div class="eyebrow">a little something</div>
  <h1>TO YOU</h1>
  <div class="line"></div>
  <div class="hint">แตะเพื่อเปิด</div>
</section>

<section class="slide">
  <div class="eyebrow">before we get there</div>
  <div class="text" style="margin-top:22px">
    <strong>ก่อนที่เราจะไปถึงตรงนั้น</strong><br>
    ลองย้อนกลับไปดูตรงนี้ด้วยกันก่อนนะ
  </div>
</section>

<section class="slide">
  <div class="date">25.07.69</div>
  <div class="polaroid">
    <img src="photo1.jpg" alt="ความทรงจำ 25.07.69">
    <div class="caption">OUR FIRST TRIP</div>
  </div>
  <div class="text">ไปเที่ยวด้วยกันครั้งแรก<br>ตื่นเต้นมาก แอบทำตัวไม่ถูก<br>มีแอบทำให้เคืองนิด ๆ</div>
</section>

<section class="slide">
  <div class="date">26.07.69</div>
  <div class="polaroid" style="transform:rotate(1.4deg)">
    <img src="photo2.jpg" alt="ความทรงจำ 26.07.69">
    <div class="caption">THE NEXT DAY</div>
  </div>
  <div class="text">
    วันต่อมาอีเวนต์หลักเลยนะ<br>
    ได้พาเธอไปในที่ที่เธออยากไป<br>
    ได้สนุกด้วยกัน<br><br>
    เธอชอบถามว่าเราจะเบื่อรึเปล่า<br>
    กลัวเราเบื่อก็น่ารักดี<br>
    แต่เราไม่เบื่อเลย<br><br>
    <strong>รู้รึเปล่าว่าเธอได้เป็นความสุขของเราเลยนะ</strong>
  </div>
</section>

<section class="slide">
  <div class="date">29.07.69</div>
  <div class="polaroid" style="transform:rotate(-2deg)">
    <img src="photo3.jpg" alt="ความทรงจำ 29.07.69">
    <div class="caption">HOLIDAY TOGETHER</div>
  </div>
  <div class="text">เราตัวติดกันตลอดช่วงวันหยุดเลย<br>รู้สึกจั๊กจี้มาก<br><strong>ชอบมองหน้าเธอจัง</strong></div>
</section>

<section class="slide">
  <div class="date">06.08.69</div>
  <div class="polaroid" style="transform:rotate(1.7deg)">
    <img src="photo4.jpg" alt="ความทรงจำ 06.08.69">
    <div class="caption">I KNEW IT</div>
  </div>
  <div class="text">
    ชอบมากกกกกกกกกก<br><br>
    เราว่าวันนี้เรารู้สึกมั่นใจมาก ๆ แล้วว่าเราชอบเธอ<br>
    <strong>ชอบจนตอนนี้ถอยออกมาไม่ได้ละ</strong>
  </div>
</section>

<section class="slide">
  <div class="eyebrow">little moments</div>
  <div class="polaroid" style="transform:rotate(-1deg);margin-top:18px">
    <img src="photo5.jpg" alt="ความทรงจำ">
    <div class="caption">ชอบจัง ได้ใช้วันหยุดร่วมกัน</div>
  </div>
</section>

<section class="slide">
  <div class="eyebrow">little moments</div>
  <div class="polaroid" style="transform:rotate(1.5deg);margin-top:18px">
    <img src="photo6.jpg" alt="ความทรงจำ">
    <div class="caption">กินข้าวด้วยกันอร่อยจัง</div>
  </div>
</section>

<section class="slide">
  <div class="eyebrow">little moments</div>
  <div class="polaroid" style="transform:rotate(-1.8deg);margin-top:18px">
    <img src="photo7.jpg" alt="ความทรงจำ">
    <div class="caption">แบะๆๆๆ</div>
  </div>
</section>

<section class="slide">
  <div class="eyebrow">little moments</div>
  <div class="polaroid" style="transform:rotate(1deg);margin-top:18px">
    <img src="photo8.jpg" alt="ความทรงจำ">
    <div class="caption">เห้อออออ — ชอบจัง</div>
  </div>
</section>

<section class="slide">
  <div class="eyebrow">some of my favorite moments</div>
  <div class="film-grid">
    <img src="photo1.jpg" alt="">
    <img src="photo2.jpg" alt="">
    <img src="photo3.jpg" alt="">
    <img src="photo4.jpg" alt="">
  </div>
  <div class="small">memories I want to keep</div>
</section>

<section class="slide">
  <div class="text">
    ที่ผ่านมาเราก็รู้สึกดีมาก ๆ แล้วนะ<br><br>
    แล้วเราก็คิดว่า...
    <br><br>
    <strong>ถ้าเราไปต่อจากตรงนี้ด้วยกัน<br>มันก็คงดีเหมือนกัน</strong>
  </div>
</section>

<section class="slide final">
  <div class="eyebrow">one last thing</div>
  <div class="question">เราไปต่อกันไหม?</div>
  <button class="choice" id="yes">ไปต่อกันนะ ✦</button>
  <div class="final-message" id="finalMessage">
    งั้นจากตรงนี้ไป<br>
    เราไปด้วยกันนะ
    <div class="small" style="margin-top:16px">✦ me & you ✦</div>
  </div>
</section>

</main>

<div class="nav" id="nav"></div>

<script>
const slides=[...document.querySelectorAll('.slide')];
const nav=document.getElementById('nav');
const audio=document.getElementById('musicAudio');
const musicBtn=document.getElementById('music');
let index=0, started=false, startX=0, startY=0;

slides.forEach((_,i)=>{
  const d=document.createElement('div');
  d.className='dot'+(i===0?' active':'');
  nav.appendChild(d);
});
const dots=[...document.querySelectorAll('.dot')];

function show(n, direction=1){
  n=Math.max(0,Math.min(slides.length-1,n));
  if(n===index && slides[index].classList.contains('active')) return;
  const old=index;
  index=n;
  slides.forEach((s,i)=>{
    s.classList.remove('active','prev');
    if(i===index) s.classList.add('active');
    else if(i===old && index>old) s.classList.add('prev');
  });
  dots.forEach((d,i)=>d.classList.toggle('active',i===index));
}

async function start(){
  if(!started){
    started=true;
    musicBtn.style.display='block';
    try{await audio.play()}catch(e){}
  }
}
slides[0].addEventListener('click',()=>{start();show(1)});
document.getElementById('yes').addEventListener('click',()=>{
  start();
  document.getElementById('finalMessage').classList.add('show');
  for(let i=0;i<35;i++) setTimeout(shootStar,i*55);
});

musicBtn.addEventListener('click',()=>{
  if(audio.paused) audio.play(); else audio.pause();
  musicBtn.textContent=audio.paused?'♫':'Ⅱ';
});

function shootStar(){
  const s=document.createElement('div');
  s.className='shooting';
  s.style.left=(55+Math.random()*45)+'%';
  s.style.top=(Math.random()*70)+'%';
  document.getElementById('stars').appendChild(s);
  setTimeout(()=>s.remove(),1900);
}

for(let i=0;i<90;i++){
  const s=document.createElement('div');
  s.className='star';
  s.style.left=Math.random()*100+'%';
  s.style.top=Math.random()*100+'%';
  s.style.animationDelay=(Math.random()*4)+'s';
  s.style.opacity=(.15+Math.random()*.55);
  document.getElementById('stars').appendChild(s);
}

document.addEventListener('touchstart',e=>{
  startX=e.changedTouches[0].clientX;
  startY=e.changedTouches[0].clientY;
},{passive:true});

document.addEventListener('touchend',e=>{
  const dx=e.changedTouches[0].clientX-startX;
  const dy=e.changedTouches[0].clientY-startY;
  if(Math.abs(dx)>55 && Math.abs(dx)>Math.abs(dy)*1.15){
    start();
    if(dx<0 && index<slides.length-1) show(index+1,1);
    if(dx>0 && index>0) show(index-1,-1);
  }
},{passive:true});

document.addEventListener('keydown',e=>{
  if(e.key==='ArrowRight') show(index+1,1);
  if(e.key==='ArrowLeft') show(index-1,-1);
});
</script>
</body>
</html>
'''

path = Path("/mnt/data/me-and-you.html")
path.write_text(html, encoding="utf-8")
print(f"สร้างไฟล์แล้ว: {path}")
