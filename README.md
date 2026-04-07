<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Mahedere Gezahegn's Dev Profile</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');
  
  :root {
    --primary: #00dc82;
    --secondary: #61dafb;
    --accent: #2496ed;
    --dark: #0d1117;
    --light: #f8f9fa;
    --gray: #8b949e;
    --bg: #0d1117;
  }
  
  body {
    font-family: 'Inter', sans-serif;
    max-width: 900px;
    margin: 0 auto;
    padding: 0 20px;
    color: #e0e0e0;
    background-color: var(--bg);
    line-height: 1.6;
  }
  
  h1, h2, h3 {
    color: #ffffff;
    font-weight: 600;
  }
  
  h1 {
    text-align: center;
    padding: 1.5em 0;
    border-bottom: 2px solid var(--dark);
  }
  
  .badge {
    border-radius: 20px;
    padding: 0.5em 1.5em;
    font-weight: 600;
    color: var(--light);
  }
  
  .hero {
    background: linear-gradient(135deg, var(--dark), #1a1a1a);
    border-radius: 20px;
    padding: 30px;
    text-align: center;
    margin: 20px 0;
    box-shadow: 0 4px 15px rgba(0,0,0,0.5);
  }
  
  .hero-img {
    width: 100%;
    max-width: 600px;
    border-radius: 15px;
    margin: 15px 0;
    box-shadow: 0 6px 20px rgba(0,0,0,0.4);
  }
  
  .stats {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    gap: 20px;
    margin: 25px 0;
  }
  
  .stats a {
    text-decoration: none;
    color: #00dc82;
    background: rgba(0, 0, 0, 0.3);
    padding: 10px 20px;
    border-radius: 20px;
    font-weight: 500;
    transition: all 0.3s;
  }
  
  .stats a:hover {
    background: rgba(0, 220, 130, 0.2);
    transform: translateY(-2px);
  }
  
  .section {
    margin: 35px 0;
    border-radius: 15px;
    padding: 25px;
    background: rgba(10, 17, 23, 0.7);
  }
  
  .section h2 {
    color: var(--secondary);
    margin-bottom: 15px;
  }
  
  .divider {
    height: 2px;
    background: rgba(255, 255, 255, 0.1);
    margin: 20px 0;
  }
  
  .tech-stack {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
    gap: 15px;
  }
  
  .tech-card {
    background: rgba(0, 220, 130, 0.15);
    border-radius: 10px;
    padding: 15px;
    text-align: center;
    transition: transform 0.3s;
  }
  
  .tech-card:hover {
    transform: translateY(-5px);
  }
  
  .tech-card img {
    width: 40px;
    height: 40px;
  }
  
  .project {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 20px;
    margin: 25px 0;
  }
  
  .project img {
    border-radius: 15px;
    width: 100%;
    height: 250px;
    object-fit: cover;
    box-shadow: 0 6px 20px rgba(0,0,0,0.4);
  }
  
  .project-details {
    background: rgba(10, 17, 23, 0.7);
    border-radius: 15px;
    padding: 20px;
  }
    .project-details h3 {
    color: var(--secondary);
    margin-top: 0;
  }
  
  .badge-accent {
    background: var(--accent);
    color: #0d1117;
  }
  
  .snake-container {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin: 30px 0;
  }
  
  .snake {
    width: 350px;
    height: 150px;
  }
    .trophy-container {
    display: flex;
    justify-content: center;
    gap: 15px;
    margin: 25px 0;
  }
  
  .trophy {
    width: 120px;
    height: 120px;
  }
  
  @media (max-width: 768px) {
    .project {
      grid-template-columns: 1fr;
    }
    
    .tech-stack {
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
    }
    
    .stats {
      flex-direction: column;
    }
  }
</style>
</head>
<body>
  <div class="hero">
    <h1>Mahedere Gezahegn</h1>
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Full%20Stack%20Developer%20%E2%80%94%20Ethiopia%20%F0%9F%87%AA%F0%9F%87%B9&fontSize=48&fontColor=fff&animation=twinkling" alt="Hero Banner">
    <p style="color: #aaa;">Building real-world solutions for communities • Full Stack Developer • Geo-Discovery Specialist</p>
  </div>
  
  <div class="stats">
    <a href="https://github.com/mahederegezahegn"><span class="badge">GitHub</span></a>
    <a href="https://linkedin.com/in/mahederegezahegn"><span class="badge">LinkedIn</span></a>
    <a href="mailto:mahederegezaheng@gmail.com"><span class="badge" style="background: #D14836;">Email</span></a>
  </div>

  <div class="section">
    <h2>👨‍💻 About Me</h2>
    <p>I'm a Full Stack Developer from Addis Ababa, Ethiopia 🇪🇹 with 6+ years of experience building web and mobile applications — from solo client projects to collaborative enterprise systems.</p>
    
    <p>I care about <strong>clean architecture</strong>, <strong>great UX</strong>, and <strong>shipping products that actually work</strong>. My focus is on creating technology that serves real human needs.</p>
    
    <p><strong>What I'm focused on right now:</strong></p>
    <ul style="padding-left: 20px; color: #aaa;">
      <li>🏗️ Building <strong>LocalLens</strong> — a geo-discovery platform for real communities</li>
      <li>📱 Deepening Flutter animation & state management skills</li>
      <li>🌍 Exploring geospatial tech: PostGIS, Leaflet, MapLibre</li>
    </ul>
    
    <p>I'm comfortable with the full lifecycle: <code>requirements → design → build → deploy → maintain</code></p>
    
    <p><strong>Fun fact:</strong> I've delivered 6+ client projects end-to-end, across healthcare, HR, CRM and mobile — all while building side projects in my own time.</p>
  </div>

  <div class="section">
    <h2>🛠 Tech Stack</h2>
    <div class="tech-stack">
      <div class="tech-card">
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat&logo=php" alt="PHP">
        <div>Backend</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/Dart-0175C2?style=flat&logo=dart" alt="Dart">
        <div>Mobile</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/Laravel-FF2D20?style=flat&logo=laravel" alt="Laravel">
        <div>Framework</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/React-20232A?style=flat&logo=react" alt="React">
        <div>Frontend</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat&logo=tailwindcss" alt="Tailwind">
        <div>UI</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/PostGIS-4169E1?style=flat&logo=postgresql" alt="PostGIS">
        <div>Database</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker" alt="Docker">
        <div>DevOps</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma" alt="Figma">
        <div>Design</div>
      </div>
      <div class="tech-card">
        <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=flat&logo=visualstudiocode" alt="VS Code">
        <div>Tools</div>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>🚀 Featured Work</h2>
    
    <div class="project">
      <div>
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=mahederegezahegn&repo=local-lens&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00dc82&icon_color=00b8ff&text_color=8b949e" alt="LocalLens">
      </div>
      <div class="project-details">
        <h3>LocalLens <span class="badge">Active</span></h3>
        <p>A community-powered geo-discovery platform that connects real people with meaningful local spots. No algorithms, just authentic connections.</p>
        
        <div class="stats">
          <div>🗺️ 500+ spots</div>
          <div>📊 15K+ views</div>
          <div>👥 200+ users</div>
        </div>
        
        <p><strong>Stack:</strong> Laravel · React · Inertia.js · Tailwind · MySQL · PostGIS · Leaflet Maps</p>
        <a href="https://github.com/mahederegezahegn/local-lens" style="display: inline-block; margin-top: 10px; color: white; background: var(--primary); padding: 8px 15px; border-radius: 20px; text-decoration: none;">View Project</a>
      </div>
    </div>

    <div class="project">
      <div>
        <img src="https://github-readme-stats.vercel.app/api/pin/?username=mahederegezahegn&repo=flutter-book-app&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00dc82&icon_color=00b8ff&text_color=8b949e" alt="Flutter Book App">
      </div>
      <div class="project-details">
        <h3>Flutter Book App</h3>
        <p>Offline-first reading tracker with real-time sync via Firebase and Google OAuth authentication.</p>
        
        <div class="stats">
          <div>⚡ Offline-first architecture</div>
          <div>🔐 Google Auth</div>
          <div>📱 100+ downloads</div>
        </div>
        
        <p><strong>Stack:</strong> Flutter · Firebase · Google Auth</p>
        <a href="https://github.com/mahederegezahegn/flutter-book-app" style="display: inline-block; margin-top: 10px; color: white; background: var(--primary); padding: 8px 15px; border-radius: 20px; text-decoration: none;">View Project</a>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>📂 Public Repositories</h2>
    <p>Explore my work in the [GitHub repositories page](https://github.com/mahederegezahegn?tab=repositories&sort=updated).</p>
    
    <p><strong>🔥 Pin your top repos here</strong> (replace "repo-name" with actual repo names):</p>
    <div class="trophy-container">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=mahederegezahegn&repo=repo1&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00dc82&icon_color=00b8ff&text_color=8b949e" alt="Repo 1" class="trophy">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=mahederegezahegn&repo=repo2&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00dc82&icon_color=00b8ff&text_color=8b949e" alt="Repo 2" class="trophy">
      <img src="https://github-readme-stats.vercel.app/api/pin/?username=mahederegezahegn&repo=repo3&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=00dc82&icon_color=00b8ff&text_color=8b949e" alt="Repo 3" class="trophy">
    </div>
  </div>

  <div class="section">
    <h2>🐍 GitHub Snake Animation</h2>
    <p>Check out my dynamic GitHub contribution graph:</p>
    
    <div class="snake-container">
      <img src="https://github.com/mahederegezahegn/mahederegezahegn/raw/output/github-contribution-grid-snake.svg" alt="Light Mode Snake" class="snake">
      <img src="https://github.com/mahederegezahegn/mahederegezahegn/raw/output/github-contribution-grid-snake-dark.svg" alt="Dark Mode Snake" class="snake">
    </div>
    <p style="color: #aaa; font-size: 0.9em;">The snake updates every 12 hours automatically. [Workflow](https://github.com/mahederegezahegn/.github/actions/snake)</p>
  </div>

  <div class="section">
    <h2>📊 GitHub Journey</h2>
    <div class="stats">
      <div>⚡ 1800+ commits</div>
      <div>📈 3.5 avg streak</div>
      <div>💪 100% contribution streak</div>
    </div>
    
    <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
      <img src="https://github-readme-stats.vercel.app/api?username=mahederegezahegn&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=00dc82&icon_color=00b8ff&text_color=8b949e&rank_icon=percentile" alt="GitHub Stats">
      <img src="https://github-readme-streak-stats.herokuapp.com/?user=mahederegezahegn&theme=tokyonight&hide_border=true&background=0d1117&ring=00dc82&fire=00b8ff&currStreakLabel=00dc82&sideLabels=8b949e&dates=8b949e" alt="Streak">
    </div>
    
    <div class="trophy-container">
      <img src="https://github-profile-trophy.vercel.app/?username=mahederegezahegn&theme=tokyonight&no-frame=true&no-bg=true&margin-w=8&column=7" alt="Trophies" class="trophy">
      <img src="https://github-readme-activity-graph.vercel.app/graph?username=mahederegezahegn&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=00dc82&line=00b8ff&point=7c3aed&area=true&area_color=00dc8215" alt="Activity Graph" class="trophy">
    </div>
  </div>

  <div class="section">
    <h2>💡 Skill Levels</h2>
    <p>My expertise levels across different technologies:</p>
    
    <div style="display: flex; flex-wrap: wrap; gap: 20px; justify-content: center;">
      <div style="flex: 1 1 250px; background: rgba(0, 220, 130, 0.15); border-radius: 10px; padding: 15px; text-align: center;">
        <div style="font-size: 1.2em; color: var(--primary); margin-bottom: 5px;">90%</div>
        Laravel / PHP
      </div>
      <div style="flex: 1 1 250px; background: rgba(97, 218, 251, 0.15); border-radius: 10px; padding: 15px; text-align: center;">
        <div style="font-size: 1.2em; color: var(--secondary); margin-bottom: 5px;">87%</div>
        React / Inertia.js
      </div>
      <div style="flex: 1 1 250px; background: rgba(2, 86, 155, 0.15); border-radius: 10px; padding: 15px; text-align: center;">
        <div style="font-size: 1.2em; color: #02569B; margin-bottom: 5px;">84%</div>
        Flutter / Dart      </div>
    </div>
  </div>

  <div class="section" style="text-align: center; padding: 30px 0;">
    <p>I'm always open to interesting projects, freelance work, or just a good tech conversation.</p>
    
    <a href="mailto:mahederegezaheng@gmail.com" style="display: inline-block; margin: 10px; color: white; background: var(--primary); padding: 10px 20px; border-radius: 20px; text-decoration: none; font-weight: 600;">Email Me</a>
    
    <div style="margin-top: 20px; display: flex; gap: 15px; justify-content: center;">
      <a href="https://github.com/mahederegezahegn" style="display: flex; align-items: center; gap: 8px; color: white; text-decoration: none;">
        <img src="https://simpleicons.org/icons/github.svg" width="20" alt="GitHub">
        GitHub
      </a>
      <a href="https://linkedin.com/in/mahederegezahegn" style="display: flex; align-items: center; gap: 8px; color: white; text-decoration: none;">
        <img src="https://simpleicons.org/icons/linkedin.svg" width="20" alt="LinkedIn">
        LinkedIn
      </a>
    </div>
  </div>

  <div class="hero">
    <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer&animation=twinkling" width="100%">
  </div>
</body>
</html>
