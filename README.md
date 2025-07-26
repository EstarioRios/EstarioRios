<!-- Profile Header -->
<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=800000&height=200&section=header&text=Abolfazl%20Khezri%20%7C%20EstarioRios&fontSize=40&fontColor=ffffff"/>

<div align="center">

### 🧠 Backend Developer | Pythonista | Linux Enthusiast

💻 Specialized in building secure, scalable backends

🔒 JWT • 🐍 Python • 🦄 Django & DRF • 🐳 Docker • 🐧 Linux • ⚡ NodeJS • 🔃 Redis • 🐘 PostgreSQL • 💾 SQLite • 💠 C++

</div>

---

### 🔥 Stats & Contributions

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=EstarioRios&theme=dark&fire=DD2727&ring=DD2727&currStreakLabel=ffffff&background=000000" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=EstarioRios&show_icons=true&hide_border=true&title_color=DD2727&icon_color=DD2727&text_color=ffffff&bg_color=000000" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=EstarioRios&layout=compact&title_color=DD2727&text_color=ffffff&bg_color=000000" />
</p>

---

### 🛠️ Skills Snapshot

> JWT · NodeJS · Python · Django · Django REST Framework · Docker · Linux · JavaScript · Redis · PostgreSQL · SQLite · C++

---

### 📈 GitHub Metrics Setup (for you to keep using):

<details>
<summary>Click to expand workflow setup</summary>

```yml
name: Metrics
on:
  schedule: [{ cron: "0 0 * * 0" }]
  workflow_dispatch:
jobs:
  github-metrics:
    runs-on: ubuntu-latest
    steps:
      - uses: lowlighter/metrics@latest
        with:
          filename: metrics.plugin.isocalendar.fullyear.svg
          token: ${{ secrets.METRICS_TOKEN }}
          base: ""
          plugin_isocalendar: yes
          plugin_isocalendar_duration: full-year

      - uses: lowlighter/metrics@latest
        with:
          filename: metrics.plugin.languages.details.svg
          token: ${{ secrets.METRICS_TOKEN }}
          base: ""
          plugin_languages: yes
          plugin_languages_ignored: html, css
          plugin_languages_details: bytes-size, percentage

      - uses: lowlighter/metrics@latest
        with:
          filename: metrics.plugin.topics.icons.svg
          token: ${{ secrets.METRICS_TOKEN }}
          base: ""
          plugin_topics: yes
          plugin_topics_mode: icons
          plugin_topics_sort: stars
