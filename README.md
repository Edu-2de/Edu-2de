<!--
Eduardo Paim — Full Stack Developer (in training)
No emojis. Unique, professional, and visually creative README with a "front-end" flavor.
If JavaScript is allowed (as with profile README on GitHub, note that only static HTML/CSS/images will render), but you can provide interactive touches for personal/portfolio sites.
Use creative CSS for dark mode, badge styling, and dynamic content feel.
-->

<style>
:root {
  --accent: #00adb5;
  --bg: #222831;
  --card: #393e46;
  --txt: #eeeeee;
  --muted: #bdbdbd;
  --badge-bg: #23272f;
  --badge-txt: #f8f8f8;
  --border: #00adb588;
}
body, .readme-main { background: var(--bg); color: var(--txt); font-family: 'Fira Mono', 'Consolas', monospace; }
.readme-main { max-width: 850px; margin: 0 auto; padding: 32px 24px; border-radius: 14px; background: var(--card); box-shadow: 0 4px 32px #0004;}
.readme-title { font-size: 2.5rem; letter-spacing: -1px; color: var(--accent);}
.readme-sub { font-size: 1.35rem; color: var(--muted);}
.tech-badges { display: flex; flex-wrap: wrap; gap: 7px; margin-top: 6px;}
.tech-badge { background: var(--badge-bg); color: var(--badge-txt); border-radius: 8px; padding: 5px 15px; font-size: 0.97rem; border: 1.5px solid var(--border); transition: transform .15s;}
.tech-badge:hover { transform: scale(1.05);}
.section { margin-top: 34px;}
.section-title { font-size: 1.4rem; color: var(--accent); border-left: 4px solid var(--accent); padding-left: 10px; margin-bottom: 10px;}
.focus-list, .goals-list { list-style: none; padding: 0;}
.focus-list li:before, .goals-list li:before { content: '▸ '; color: var(--accent);}
.card-grid { display: flex; gap: 24px; flex-wrap: wrap;}
.card { flex: 1 1 220px; background: var(--bg); border-radius: 12px; padding: 16px 20px; box-shadow: 0 2px 10px #0003; margin-bottom: 18px;}
.contact-links { display: flex; gap: 16px; margin-top: 8px;}
.contact-link { color: var(--accent); text-decoration: none; font-weight: 600;}
.contact-link:hover { text-decoration: underline;}
.stats-grid { display: flex; gap: 20px; flex-wrap: wrap; justify-content: center; margin-top: 12px;}
.stats-img { border-radius: 12px; box-shadow: 0 2px 14px #0003;}
@media (max-width: 700px) { .card-grid, .stats-grid { flex-direction: column; gap: 0; }}
</style>

<div class="readme-main">

<div class="readme-title">Eduardo Paim</div>
<div class="readme-sub">Full Stack Developer (in training) &nbsp;|&nbsp; 19 y/o<br>
Student @ Senac RS — Focused on real-world backend & web app development
</div>

<div class="section">
  <div class="section-title">Tech Stack</div>
  <div class="card-grid">
    <div class="card">
      <b>Languages</b>
      <div class="tech-badges">
        <span class="tech-badge">Python</span>
        <span class="tech-badge">JavaScript</span>
        <span class="tech-badge">TypeScript</span>
        <span class="tech-badge">PHP</span>
        <span class="tech-badge">SQL</span>
        <span class="tech-badge">HTML5</span>
        <span class="tech-badge">CSS3</span>
        <span class="tech-badge">C++</span>
        <span class="tech-badge">Java</span>
      </div>
    </div>
    <div class="card">
      <b>Frameworks</b>
      <div class="tech-badges">
        <span class="tech-badge">Django</span>
        <span class="tech-badge">React</span>
        <span class="tech-badge">Node.js</span>
      </div>
    </div>
    <div class="card">
      <b>Tools</b>
      <div class="tech-badges">
        <span class="tech-badge">Git</span>
        <span class="tech-badge">GitHub</span>
        <span class="tech-badge">GitLab</span>
        <span class="tech-badge">VSCode</span>
        <span class="tech-badge">REST API</span>
      </div>
    </div>
  </div>
</div>

<div class="section">
  <div class="section-title">Focus Areas</div>
  <ul class="focus-list">
    <li>REST APIs with Django & DRF</li>
    <li>UI building with React.js</li>
    <li>Version control with Git & CI/CD workflows</li>
  </ul>
</div>

<div class="section">
  <div class="section-title">GitHub Overview</div>
  <div class="stats-grid">
    <img class="stats-img" height="160" src="https://github-readme-stats.vercel.app/api?username=Edu-2de&show_icons=true&theme=default&include_all_commits=true&count_private=true" alt="Edu-2de Stats"/>
    <img class="stats-img" height="160" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Edu-2de&layout=compact&theme=default" alt="Edu-2de Top Langs"/>
  </div>
</div>

<div class="section">
  <div class="section-title">Goals</div>
  <ul class="goals-list">
    <li>Graduate in <b>ADS</b> with a solid project portfolio</li>
    <li>Build scalable full stack apps</li>
    <li>Join open source initiatives</li>
  </ul>
</div>

<div class="section">
  <div class="section-title">Contact</div>
  <div class="contact-links">
    <a class="contact-link" href="mailto:edupaim1712@gmail.com" target="_blank">Email</a>
    <a class="contact-link" href="https://www.instagram.com/edu.2de/" target="_blank">Instagram</a>
  </div>
</div>

<div style="margin-top:36px;color:var(--muted);font-size:0.95rem;">
  <span>&lt;/&gt; Thanks for stopping by!</span>
</div>

</div>

<!--
Tip: For an even more "front-end" feel, serve this as your portfolio landing page with actual CSS/JS.
But on GitHub profile README, only HTML and inline CSS are rendered, no JS or embedded <style> tags.
-->
