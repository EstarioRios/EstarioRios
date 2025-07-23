<!-- Dark-space themed GitHub profile README -->
<body style="margin:0;padding:0;background:#000;color:#eee;font-family:'Segoe UI',sans-serif;">

<style>
  /* Background starfield */
  @keyframes stars { from { transform: translateY(0);} to { transform: translateY(-1000px);} }
  .stars {
    position: fixed; top:0; left:0; width:100%; height:100%;
    background: url('https://raw.githubusercontent.com/estariorios/readme-assets/main/stars1.png') repeat;
    animation: stars 200s linear infinite;
    opacity:0.6;
    z-index:-2;
  }

  /* Subtle red flicker text */
  .flicker {
    color: #ff5555;
    animation: flicker 1.5s infinite alternate;
  }
  @keyframes flicker {
    from { opacity:.8; text-shadow: 0 0 8px #ff4444; }
    to   { opacity:1; text-shadow: 0 0 16px #ff2222; }
  }

  /* Glassy info cards */
  .card {
    background: rgba(30,0,0,0.5);
    backdrop-filter: blur(8px);
    border: 1px solid rgba(255,0,0,0.3);
    border-radius:8px;
    padding:20px;
    margin:20px auto;
    max-width:800px;
    box-shadow: 0 0 12px rgba(255,0,0,0.6);
    animation: fade 1.2s ease-out;
  }
  @keyframes fade {
    from { opacity:0; transform: translateY(20px); }
    to   { opacity:1; transform: translateY(0); }
  }

  h1, h2, h3 { color: #ff6666; text-align:center; }
  p, li { line-height:1.6; }
  a { color:#ff7777; }
  img { border-radius:4px; }
</style>

<div class="stars"></div>

<section>
  <h1 class="flicker">👨‍🚀 Abolfazl Khezri</h1>
  <h2>Back‑End Developer | Redis • Django • DRF • JS • Docker • Python • PostgreSQL • SQLite</h2>
</section>

<section class="card">
  <h3>📊 GitHub Stats</h3>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=estariorios&theme=dark&hide_border=true&show_icons=true&bg_color=000000&icon_color=ff4444" width="300" alt="GitHub Stats"/>
    <img src="https://github-readme-streak-stats.herokuapp.com/?user=estariorios&theme=dark&hide_border=true&background=000000&fire=ff4444" width="300" alt="Streak Stats"/>
  </p>
</section>

<section class="card">
  <h3>💼 Featured Projects</h3>
  <p align="center">
    <a href="#"><img src="https://media.giphy.com/media/3oEjI6SIIHBdRxXI40/giphy.gif" width="200" alt="Project ✨"/></a>
    <a href="#"><img src="https://media.giphy.com/media/l0MYGb1LuZ3n7dRnO/giphy.gif" width="200" alt="Project 🚀"/></a>
  </p>
</section>

<section class="card">
  <h3>🌌 Activity Showcase</h3>
  <p align="center" style="color:#ccc;">
    📌 Latest Commits • ⭐ PRs • 🐛 Issues • 🛠 Code Reviews • 🚚 Deploys
  </p>
  <p align="center"><em>Visualize your activity via GitHub Actions or external SVG here.</em></p>
</section>

<section class="card">
  <h3>📬 Contact & Connect</h3>
  <p align="center">
    📧 <a href="mailto:abolfazl.khezri.business@gmail.com">Email Me</a> ·
    💼 LinkedIn ·
    ⚙️ DockerHub ·
    💻 GitHub
  </p>
</section>

<p align="center" style="margin:40px 0;color:#555;">
  Built in 🖤 dark mode with blazing 💥 red accents • crafted by Abolfazl
</p>

</body>
