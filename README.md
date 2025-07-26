<!-- Profile Header -->

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=800000&height=200&section=header&text=Abolfazl%20Khezri%20%7C%20EstarioRios&fontSize=40&fontColor=ffffff"/>

<div align="center">

### 🧠 Backend Developer | Pythonista | Linux Enthusiast

💻 Specialized in building secure, scalable backends

🔒 JWT • 🐍 Python • 🦄 Django & DRF • 🐳 Docker • 🐧 Linux • ⚡ NodeJS • 🔃 Redis • 🐘 PostgreSQL • 💾 SQLite

</div>

---

### 🔥 Stats & Contributions

<!-- GitHub Metrics: Isocalendar -->

<p align="center">
  <img src="https://raw.githubusercontent.com/EstarioRios/EstarioRios/master/metrics.plugin.isocalendar.fullyear.svg" width="85%">
</p>

<!-- GitHub Metrics: Languages -->

<p align="center">
  <img src="https://raw.githubusercontent.com/EstarioRios/EstarioRios/master/metrics.plugin.languages.details.svg" width="85%">
</p>

<!-- GitHub Metrics: Topics (with icons) -->

<p align="center">
  <img src="https://raw.githubusercontent.com/EstarioRios/EstarioRios/master/metrics.plugin.topics.icons.svg" width="85%">
</p>

---

### 🛠️ Skills Snapshot

> JWT · NodeJS · Python · Django · Django REST Framework · Docker · Linux · JavaScript · Redis · PostgreSQL · SQLite

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
```

</details>

---

### 🧩 About Me

I’m **Abolfazl Khezri**, a backend developer who enjoys writing clean, efficient, and scalable backend code.

* 🔭 I’m currently working on full-stack systems with DRF and PostgreSQL
* 🌱 Learning more about system architecture and performance optimization
* ⚡ Fun fact: I love building command-line tools and automating Linux workflows

---

<div align="center">

*"Think deeply. Code cleanly. Deploy wisely."*

⭐️ If you like what you see, consider following or contributing to my repositories!

</div>
