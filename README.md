<h1><img src="https://emojis.slackmojis.com/emojis/images/1531849430/4246/blob-sunglasses.gif?1531849430" width="30"/> <span> Hey, glad you came! </span> </h1>

I'm Lorenzo Han 😉, data guy based in New York🗽. 

I tell stories with data and I use Python, R, and SQL to write stories. 🦹‍♀️

<img src="https://readme-typing-svg.herokuapp.com?vCenter=true&width=500&lines=I+love+crunching+numbers" height="40"/>

<div>
<a href="mailto: xuefan.han@columbia.edu">
<img src="https://img.shields.io/badge/-xuefan.han@columbia.edu-7B83EB?&style=for-the-badge&logo=Microsoft-outlook&logoColor=white" ></a>  <a  href="https://www.instagram.com/lorenzo_han/">   <img src="https://img.shields.io/badge/@lorenzo_han_-%23E4405F.svg?&style=for-the-badge&logo=instagram&logoColor=white"></a>  <a href="https://www.linkedin.com/in/xuefan-han-391084217/"><img src="https://img.shields.io/badge/xuefan han-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" ></a> 
  
</div>

### Current Status Quo : 📡

- 🧑‍🎓 I’m a master's student in Applied Analytics at <strong>Columbia University in the City of New York</strong>.
- 🔭 I focus on <strong>Data Analytics</strong> and <strong>Machine Learning</strong>.
- 👨‍🎤 I’m currently working on a <strong>YouTube Video Recommender System</strong>.



<!--header-->
<table>
  <tr><th colspan="2"><h3>📅 Isometric commit calendar</h3></th></tr>
  <tr><td colspan="2" align="center"><p>This plugin displays an isometric view of your commit calendar along with a few additional statistics like current streak and average number of commit per day.</p>
</td></tr>
  <tr>
    <th rowspan="3">Supported features<br><sub><a href="metadata.yml">→ Full specification</a></sub></th>
    <td><a href="/source/templates/classic/README.md"><code>📗 Classic template</code></a> <a href="/source/templates/terminal/README.md"><code>📙 Terminal template</code></a></td>
  </tr>
  <tr>
    <td><code>👤 Users</code></td>
  </tr>
  <tr>
    <td><code>🔑 (scopeless)</code> <code>read:org (optional)</code> <code>read:user (optional)</code> <code>repo (optional)</code></td>
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
    <td align="center" nowrap="nowrap">Type</i></td><td align="center" nowrap="nowrap">Description</td>
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
