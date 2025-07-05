#  👋 Hi, I’m Erick Silva

I’m a passionate **Junior Front-End Developer** focused on building intuitive and functional user interfaces. I’m actively looking for opportunities to grow and contribute to challenging projects.

I have hands-on experience with **JavaScript**, **Vue.js**, **HTML**, **CSS**, and I’m always learning new technologies to deliver clean, efficient, and maintainable 
<!--header-->
<table>
  <tr><td colspan="2"><a href="/README.md#-plugins">← Back to plugins index</a></td></tr>
  <tr><th colspan="2"><h3>📅 Isometric commit calendar</h3></th></tr>
  <tr><td colspan="2" align="center"><p>This plugin displays an isometric view of a user commit calendar along with a few additional statistics like current streak and average number of commit per day.</p>
</td></tr>
  <tr><th>⚠️ Disclaimer</th><td><p>This plugin is not affiliated, associated, authorized, endorsed by, or in any way officially connected with <a href="https://github.com">GitHub</a>.
All product and company names are trademarks™ or registered® trademarks of their respective holders.</p>
</td></tr>
  <tr>
    <th rowspan="3">Supported features<br><sub><a href="metadata.yml">→ Full specification</a></sub></th>
    <td><a href="/source/templates/classic/README.md"><code>📗 Classic template</code></a> <a href="/source/templates/terminal/README.md"><code>📙 Terminal template</code></a></td>
  </tr>
  <tr>
    <td><code>👤 Users</code></td>
  </tr>
  <tr>
    <td><code>🔑 (scopeless)</code> <code>read:org (optional)</code> <code>read:user (optional)</code> <code>read:packages (optional)</code> <code>repo (optional)</code></td>
  </tr>
  <tr>
    <td colspan="2" align="center">
      <details open><summary>Full year calendar</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.fullyear.svg" alt=""></img></details>
      <details><summary>Half year calendar</summary><img src="https://github.com/lowlighter/metrics/blob/examples/metrics.plugin.isocalendar.svg" alt=""></img></details>
      <img width="900" height="1" alt="">
    </td>
  </tr>
</table>
<!--/header-->

## ➡️ Available options

<!--options-->
<table>
  <tr>
    <td align="center" nowrap="nowrap">Option</i></td><td align="center" nowrap="nowrap">Description</td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_isocalendar</code></h4></td>
    <td rowspan="2"><p>Enable isocalendar plugin</p>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>boolean</code>
<br>
<b>default:</b> no<br></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><h4><code>plugin_isocalendar_duration</code></h4></td>
    <td rowspan="2"><p>Time range</p>
<ul>
<li><code>half-year</code>: 180 days</li>
<li><code>full-year</code>: 1 year</li>
</ul>
<img width="900" height="1" alt=""></td>
  </tr>
  <tr>
    <td nowrap="nowrap"><b>type:</b> <code>string</code>
<br>
<b>default:</b> half-year<br>
<b>allowed values:</b><ul><li>half-year</li><li>full-year</li></ul></td>
  </tr>
</table>
<!--/options-->

## ℹ️ Examples workflows

<!--examples-->
```yaml
name: Half-year calendar
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.isocalendar.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_isocalendar: yes

```
```yaml
name: Full-year calendar
uses: lowlighter/metrics@latest
with:
  filename: metrics.plugin.isocalendar.fullyear.svg
  token: ${{ secrets.METRICS_TOKEN }}
  base: ""
  plugin_isocalendar: yes
  plugin_isocalendar_duration: full-year

```
<!--/examples-->
# 💻 Tech Stack:
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E) ![Java](https://img.shields.io/badge/java-%23ED8B00.svg?style=for-the-badge&logo=openjdk&logoColor=white) ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white) ![Rust](https://img.shields.io/badge/rust-%23000000.svg?style=for-the-badge&logo=rust&logoColor=white) ![PHP](https://img.shields.io/badge/php-%23777BB4.svg?style=for-the-badge&logo=php&logoColor=white) ![Angular](https://img.shields.io/badge/angular-%23DD0031.svg?style=for-the-badge&logo=angular&logoColor=white) ![Flask](https://img.shields.io/badge/flask-%23000.svg?style=for-the-badge&logo=flask&logoColor=white) ![FastAPI](https://img.shields.io/badge/FastAPI-005571?style=for-the-badge&logo=fastapi) ![Vue.js](https://img.shields.io/badge/vue.js-%2335495e.svg?style=for-the-badge&logo=vuedotjs&logoColor=%234FC08D) ![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white) ![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white) ![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white) ![MySQL](https://img.shields.io/badge/mysql-4479A1.svg?style=for-the-badge&logo=mysql&logoColor=white) ![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white) ![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white) ![Power Bi](https://img.shields.io/badge/power_bi-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
# 📊 GitHub Stats:
![](https://github-readme-stats.vercel.app/api?username=steve-erick&theme=dark&hide_border=false&include_all_commits=true&count_private=false)<br/>
![](https://nirzak-streak-stats.vercel.app/?user=steve-erick&theme=dark&hide_border=false)<br/>
![](https://github-readme-stats.vercel.app/api/top-langs/?username=steve-erick&theme=dark&hide_border=false&include_all_commits=true&count_private=false&layout=compact)

🏆 GitHub Trophies ![](https://github-profile-trophy.vercel.app/?username=steve-erick&theme=radical&no-frame=true&no-bg=false&margin-w=4)

### ✍️ Random Dev Quote
![](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight)

### 🔝 Top Contributed Repo
![](https://github-contributor-stats.vercel.app/api?username=steve-erick&limit=5&theme=dark&combine_all_yearly_contributions=true)

---
[![](https://visitcount.itsvg.in/api?id=steve-erick&icon=2&color=0)](https://visitcount.itsvg.in)

<!-- Proudly created with GPRM ( https://gprm.itsvg.in ) -->
