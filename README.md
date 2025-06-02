<!--
Eduardo Paim — Full Stack Developer (in training)
README clean, elegante, com SVGs animados para destacar Tech Stack e estatísticas.
Snake animation configurada para contribuições, visual moderno e clean.
-->

<h1 align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=32&duration=2000&pause=900&color=00ADB5&center=true&vCenter=true&width=550&lines=Eduardo+Paim;Full+Stack+Developer;Senac+RS+%7C+19+y%2Fo" alt="Typing SVG" />
</h1>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00adb5&height=80&section=header&animation=twinkling" alt="header" />
</p>

<p align="center">
  <b style="font-size:1.16em;color:#222831;">
    Desenvolvedor focado em soluções reais, tecnologia de ponta e design limpo.
  </b>
</p>

---

<h2 align="center" style="color:#00adb5;margin-bottom:0;">Tech Stack</h2>

<table align="center" width="100%" style="border:none;">
  <tr>
    <td align="center" valign="top" width="34%">
      <b style="color:#00adb5;">Linguagens</b><br>
      <img src="https://skillicons.dev/icons?i=python,js,ts,php,java,cpp,html,css,postgres&theme=light" alt="Languages" />
    </td>
    <td align="center" valign="top" width="33%">
      <b style="color:#00adb5;">Frameworks</b><br>
      <img src="https://skillicons.dev/icons?i=django,react,nodejs&theme=light" alt="Frameworks" />
    </td>
    <td align="center" valign="top" width="33%">
      <b style="color:#00adb5;">Ferramentas</b><br>
      <img src="https://skillicons.dev/icons?i=git,github,gitlab,vscode,postman&theme=light" alt="Ferramentas" />
    </td>
  </tr>
</table>

---

<table align="center" width="100%" style="border:none;">
  <tr>
    <td valign="top" width="50%">
      <b style="color:#00adb5;">O que faço</b>
      <ul>
        <li>APIs REST robustas com Django & DRF</li>
        <li>Interfaces modernas com React.js</li>
        <li>Versionamento contínuo e CI/CD</li>
      </ul>
    </td>
    <td valign="top" width="50%">
      <b style="color:#00adb5;">Objetivos</b>
      <ul>
        <li>Graduar em <b>ADS</b> com projetos de impacto</li>
        <li>Desenvolver apps full stack escaláveis</li>
        <li>Atuar em iniciativas open source</li>
      </ul>
    </td>
  </tr>
</table>

---

<h2 align="center" style="color:#00adb5">GitHub Overview</h2>
<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Edu-2de&show_icons=true&theme=react&hide_border=true&hide_title=true&include_all_commits=true&count_private=true" height="145"/>
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Edu-2de&layout=compact&theme=react&hide_border=true&hide_title=true" height="145"/>
</p>
<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Edu-2de&theme=react&hide_border=true&background=FFFFFF00&fire=00adb5&currStreakLabel=00adb5" alt="GitHub Streak" height="125"/>
</p>
<!-- SNAKE ANIMATION: Este bloco só funciona se a GitHub Action snk estiver ativa e o SVG existir -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Edu-2de/Edu-2de/output/github-contribution-grid-snake.svg" alt="snake animation" width="80%" style="min-width:300px;max-width:640px;">
</p>

---

<h2 align="center" style="color:#00adb5">Contato</h2>
<p align="center">
  <a href="mailto:edupaim1712@gmail.com" target="_blank">
    <img src="https://img.shields.io/badge/Email-00adb5?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://www.instagram.com/edu.2de/" target="_blank">
    <img src="https://img.shields.io/badge/Instagram-00adb5?style=for-the-badge&logo=instagram&logoColor=white" />
  </a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00adb5&height=60&section=footer" alt="footer" />
</p>
<p align="center" style="color:#bdbdbd;font-size:0.95rem;">
  <sub>&lt;/&gt; Obrigado por visitar!</sub>
</p>

<!--
⚡ Snake animation:
- O SVG só aparece se você ativar a action Platane/snk.
- Crie o arquivo .github/workflows/snake.yml no seu repositório com o conteúdo abaixo:

name: Generate Snake Animation

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  generate:
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v4
      - uses: Platane/snk@v3
        with:
          github_user_name: ${{ github.repository_owner }}
          outputs: |
            output/github-contribution-grid-snake.svg
      - name: Push generated snake svg
        uses: EndBug/add-and-commit@v9
        with:
          add: "output/github-contribution-grid-snake.svg"
          message: "generate contribution snake"

- Após o primeiro run, o arquivo será criado e a snake aparece no seu README!
-->
