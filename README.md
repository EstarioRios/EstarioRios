<!-- 🚨 Add this at the very top for global dark background -->
<body style="background:#0f0f0f;color:#e0e0e0;font-family:Verdana,sans-serif;">

<style>
  /* ------- Global styling ------- */
  body { margin:0; padding:0; }
  a { color:#ff5555; text-decoration:none; }
  h1, h2, h3 { color:#ff4444; }
  section { padding:20px; margin:0 auto; max-width:800px; }

  /* --------- Animated leaves --------- */
  .leaf {
    position: fixed; top:-10%;
    width: 30px; height:30px;
    background: rgba(255,0,0,0.7);
    border-radius:50%;
    animation: fall 8s linear infinite, sway 4s ease-in-out infinite;
  }
  @keyframes fall { 100% { transform: translateY(120vh) rotate(720deg); opacity:0; } }
  @keyframes sway { 0%,100% { transform: translateX(0); } 50% { transform: translateX(100px); } }

  /* ------ 3D Activity cube ------ */
  .cube-container {
    perspective: 800px; width:300px; height:300px;
    margin: 40px auto;
  }
  .cube {
    position: relative; width:100%; height:100%; transform-style: preserve-3d;
    animation: spin 12s infinite linear;
  }
  .cube-face {
    position: absolute; width:300px; height:300px;
    background: rgba(255,85,85,0.2); line-height:300px;
    text-align:center; font-size:24px;
    border:2px solid #ff5555;
  }
  .face-front  { transform: translateZ(150px); }
  .face-back   { transform: rotateY(180deg) translateZ(150px); }
  .face-right  { transform: rotateY(90deg) translateZ(150px); }
  .face-left   { transform: rotateY(-90deg) translateZ(150px); }
  .face-top    { transform: rotateX(90deg) translateZ(150px); }
  .face-bottom { transform: rotateX(-90deg) translateZ(150px); }

  @keyframes spin { from { transform: rotateX(0deg) rotateY(0deg); } to { transform: rotateX(360deg) rotateY(360deg); } }
</style>

<!-- Falling leaves animation -->
<div id="leaves"></div>
<script>
  for(let i=0;i<15;i++){
    const l=document.createElement('div');
    l.className='leaf'; l.style.left = Math.random()*100+'%';
    l.style.animationDelay = (Math.random()*5)+'s';
    l.style.width = l.style.height = (20+Math.random()*20)+'px';
    document.body.appendChild(l);
  }
</script>

<section align="center">
  <h1>I'm Abolfazl Khezri</h1>
  <h2>✨ DevOps • C++ • Linux • Django & DRF Expert</h2>
  <p>Contact: <a href="mailto:abolfazl.khezri.business@gmail.com">Email Me</a></p>
</section>

<section>
  <h2>🛰️ 3D Recent Activity Cube</h2>
  <div class="cube-container">
    <div class="cube">
      <div class="cube-face face-front">Latest Commit</div>
      <div class="cube-face face-back">PR Merged</div>
      <div class="cube-face face-right">Issue Opened</div>
      <div class="cube-face face-left">Code Review</div>
      <div class="cube-face face-top">Deployed 🚀</div>
      <div class="cube-face face-bottom">CI Pass</div>
    </div>
  </div>
  <p style="text-align:center;color:#aaa">The cube slowly spins, showcasing your most recent actions in 3D space.</p>
</section>

<section align="center">
  <h2>📊 GitHub Stats</h2>
  <img src="https://github-readme-stats.vercel.app/api?username=estariorios&theme=dark&hide_border=true&show_icons=true&bg_color=000000&icon_color=ff4444" alt="GitHub Stats" width="300"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=estariorios&theme=dark&hide_border=true&background=000000&fire=ff4444" alt="Streak Stats" width="300"/>
</section>

<section align="center">
  <h2>🏆 Achievements & Quote</h2>
  <img src="https://github-profile-trophy.vercel.app/?username=estariorios&theme=darkhub&no-bg=true&margin-w=15" alt="Trophies" width="300"/>
  <p><em>"<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark" alt="Random Dev Quote"/>"</em></p>
</section>

<section align="center">
  <h2>💼 Featured Projects</h2>
  <a href="#"><img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="200" alt="Project A"/></a>
  <a href="#"><img src="https://media.giphy.com/media/l0MYGb1LuZ3n7dRnO/giphy.gif" width="200" alt="Project B"/></a>
</section>

<section align="center">
  <p>Built in 🔥 dark mode with ⚡ red accents</p>
</section>

</body>
