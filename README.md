<!-- Copy-and-paste this into README.md -->

<body style="margin:0;padding:0;background:#000;color:#ddd;font-family:'Segoe UI',sans-serif;">
<style>
  /* Background stars */
  .stars, .stars2, .stars3 {
    position:absolute;top:0;left:0;width:100%;height:100%;display:block;
    background-repeat:repeat;
    animation:animStar linear infinite;
  }
  .stars  { background-image:url('https://raw.githubusercontent.com/estariorios/readme-assets/main/stars1.png'); animation-duration:200s; }
  .stars2 { background-image:url('https://raw.githubusercontent.com/estariorios/readme-assets/main/stars2.png'); animation-duration:100s; }
  .stars3 { background-image:url('https://raw.githubusercontent.com/estariorios/readme-assets/main/stars3.png'); animation-duration:300s; }
  @keyframes animStar { from{transform:translateY(0);} to{transform:translateY(-1000px);} }

  /* Falling orbs (“leaves”) */
  .orb {
    position:fixed; background:rgba(255,50,50,0.6);
    border-radius:50%;
    animation:fall linear infinite;
  }
  @keyframes fall {
    0% { transform: translateY(-5vh) translateX(0) scale(0.5); opacity:1; }
    100% { transform: translateY(105vh) translateX(30px) scale(1); opacity:0; }
  }

  /* Glass cards */
  .card {
    backdrop-filter:blur(8px);
    background:rgba(30,0,0,0.5);
    border:1px solid rgba(255,0,0,0.4);
    border-radius:8px;
    padding:16px;
    margin:16px auto;
    max-width:700px;
    box-shadow:0 0 12px rgba(255,0,0,0.6);
    animation:fadeIn 2s ease 1;
  }
  @keyframes fadeIn { from{opacity:0;transform:translateY(20px);} to{opacity:1;} }

  h1, h2 { text-align:center;color:#ff7777; }
  a { color:#ff5555; }
  img { border-radius:4px; }

</style>

<div class="stars"></div><div class="stars2"></div><div class="stars3"></div>

<script>
  for(let i=0;i<12;i++){
    document.write('<div class="orb" style="width:'+ (12+Math.random()*20) +
                   'px;height:'+(12+Math.random()*20) +'px;left:'+ (Math.random()*100)+'vw;animation-duration:'+(8+Math.random()*6)+'s;"></div>');
  }
</script>

<section>
  <h1>👾 Abolfazl Khezri</h1>
  <h2>DevOps • C++ • Linux • Django & DRF</h2>
</section>

<section class="card">
  <h2>📊 GitHub Stats</h2>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=estariorios&theme=dark&hide_border=true&show_icons=true&bg_color=000000&icon_color=ff4444" width="320"/>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=estariorios&theme=dark&hide_border=true&background=000000&fire=ff4444" width="320"/>
  </p>
</section>

<section class="card">
  <h2>🌌 Recent Activity Cube (3D vibe)</h2>
  <p align="center" style="color:#aaa;">[Imagine a slowly spinning 3D activity cube here]</p>
</section>

<section class="card">
  <h2>💼 Featured Projects</h2>
  <p align="center">
    <a href="#"><img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="200" /></a>
    <a href="#"><img src="https://media.giphy.com/media/l0MYGb1LuZ3n7dRnO/giphy.gif" width="200" /></a>
  </p>
</section>

<section class="card">
  <h2>📬 Contact</h2>
  <p align="center">
    <a href="mailto:abolfazl.khezri.business@gmail.com">📧 Email Me</a> • 
    <a href="https://linkedin.com/in/yourprofile">LinkedIn</a> • 
    <a href="https://github.com/estariorios">GitHub</a>
  </p>
</section>

<section align="center" style="margin:40px 0;color:#777;">
  Made with ❤️ in dark space 🌌
</section>
