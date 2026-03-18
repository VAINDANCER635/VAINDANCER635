<div align="center">

<style>
/* ==================== NEXT-LEVEL NEON HEADER ==================== */
.neon-header {
  background: linear-gradient(135deg, #0D1117 0%, #001F3F 100%);
  padding: 80px 30px 60px;
  border-radius: 24px;
  margin-bottom: 40px;
  border: 3px solid transparent;
  background-clip: padding-box;
  position: relative;
  overflow: hidden;
  box-shadow: 0 0 60px rgba(0, 191, 255, 0.4);
}

/* Animated neon border */
.neon-header::before {
  content: '';
  position: absolute;
  inset: -3px;
  border: 3px solid #00BFFF;
  border-radius: 24px;
  animation: neon-border 3s linear infinite;
  opacity: 0.6;
}

@keyframes neon-border {
  0%   { box-shadow: 0 0 10px #00BFFF; }
  50%  { box-shadow: 0 0 40px #00BFFF, 0 0 70px #00BFFF; }
  100% { box-shadow: 0 0 10px #00BFFF; }
}

/* Lightning bolt */
.bolt {
  font-size: 4.5rem;
  display: block;
  margin-bottom: 10px;
  animation: bolt-pulse 1.8s ease-in-out infinite;
  color: #00BFFF;
  text-shadow: 0 0 20px #00BFFF, 0 0 40px #00BFFF;
}

@keyframes bolt-pulse {
  0%, 100% { transform: scale(1) rotate(-8deg); }
  50%      { transform: scale(1.15) rotate(8deg); }
}

/* Main neon title */
.neon-title {
  font-size: 4.2rem;
  font-weight: 900;
  letter-spacing: -2px;
  color: #FFFFFF;
  margin: 0;
  text-shadow: 
    0 0 10px #00BFFF,
    0 0 20px #00BFFF,
    0 0 40px #00BFFF,
    0 0 70px #00BFFF;
  animation: title-glow 2.5s ease-in-out infinite alternate;
}

@keyframes title-glow {
  from { text-shadow: 0 0 10px #00BFFF, 0 0 20px #00BFFF; }
  to   { text-shadow: 0 0 30px #00BFFF, 0 0 60px #00BFFF, 0 0 90px #00BFFF; }
}

/* Typewriter intro */
.typewriter {
  font-size: 1.45rem;
  font-weight: 600;
  color: #00E6FF;
  overflow: hidden;
  border-right: 4px solid #00BFFF;
  white-space: nowrap;
  margin: 15px 0 0;
  width: 0;
  animation: typing 4s steps(45, end) 0.8s forwards, blink-caret 0.75s step-end infinite;
}

@keyframes typing {
  from { width: 0 }
  to   { width: 100% }
}

@keyframes blink-caret {
  from, to { border-color: transparent; }
  50%      { border-color: #00BFFF; }
}

/* Subtle tagline glow */
.tagline {
  font-size: 1.1rem;
  color: #88EEFF;
  margin-top: 12px;
  text-shadow: 0 0 15px rgba(0, 191, 255, 0.6);
}

/* ==================== REST OF PAGE (ENHANCED) ==================== */
.glow-badge {
  transition: transform 0.3s ease;
}
.glow-badge:hover {
  transform: scale(1.08);
}
</style>

<!-- ==================== NEON HEADER (replaces banner) ==================== -->
<div class="neon-header">
  <span class="bolt">⚡</span>
  <h1 class="neon-title">VAINDANCER635</h1>
  <div class="typewriter">Hey 👋 I'm Samuel (Adam) — Frontend architect turned mobile craftsman</div>
  <p class="tagline">Building buttery-smooth native apps that feel premium and ship fast ⚡</p>
</div>

<!-- Tech Stack -->
<h3>Tech I Ship With ⚡</h3>
<p>
  <img src="https://img.shields.io/badge/React_Native-61DAFB?style=for-the-badge&logo=react&logoColor=black" alt="React Native" class="glow-badge" />
  <img src="https://img.shields.io/badge/Expo-000020?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" class="glow-badge" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" alt="Flutter" class="glow-badge" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin" class="glow-badge" />
  <img src="https://img.shields.io/badge/Swift-FA7343?style=for-the-badge&logo=swift&logoColor=white" alt="Swift" class="glow-badge" />
  <img src="https://img.shields.io/badge/Framework7-EE4D71?style=for-the-badge&logo=framework7&logoColor=white" alt="Framework7" class="glow-badge" />
</p>
<p>
  <strong>Roots in:</strong> React • Gatsby • React Native Web • Bootstrap • CSS sorcery
</p>

<!-- About / Vibe -->
<h3>What I'm About 🔥</h3>
<blockquote style="font-size:1.15rem; border-left: 5px solid #00BFFF; padding-left:20px; color:#BBEEFF;">
  I turn screens into experiences people actually want to touch.<br>
  Deep in next-gen mobile right now: performance-obsessed, intuitive UX, cross-platform mastery.<br>
  From pixel-perfect UIs to production-grade native apps. Let's build something electric.
</blockquote>

<!-- Current Focus / Projects -->
<h3>Currently Building ⚡</h3>
<ul style="font-size:1.1rem;">
  <li>Proprietary next-level mobile applications with React Native + Expo – seamless, locked-down experiences</li>
  <li>High-performance cross-platform tools & utilities for mobile devs</li>
  <li>Exploring Flutter finesse + native Kotlin/Swift bridges</li>
</ul>

<!-- Connect -->
<h3>Let's Connect 🌐</h3>
<p>
  <a href="https://x.com/korrisonadam">
    <img src="https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white" alt="X @korrisonadam" class="glow-badge" />
  </a>
</p>

<p>
  <em>Always shipping, always learning. Drop a ⭐ on my repos if you're into mobile magic.</em>
</p>

<!-- GitHub Stats -->
<img src="https://github-readme-stats.vercel.app/api?username=VAINDANCER635&show_icons=true&theme=radical&hide_border=true&bg_color=0D1117&title_color=00BFFF&text_color=FFFFFF&icon_color=00BFFF" alt="GitHub Stats" width="48%" />
<img src="https://github-readme-streak-stats.herokuapp.com/?user=VAINDANCER635&theme=radical&hide_border=true&background=0D1117&stroke=00BFFF&ring=00BFFF&fire=00BFFF&currStreakNum=FFFFFF&sideNums=FFFFFF" alt="Streak" width="48%" />

</div>
