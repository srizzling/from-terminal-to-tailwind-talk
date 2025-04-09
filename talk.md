---
marp: true
theme: rose-pine
paginate: true
---

<!-- Slide 1 -->
<!-- _class: lead _ -->
<!--fit-->

# From **Terminal** to **Tailwind**

**Sriram Venkatesh**

---

<!-- Slide 1.5 - Introduction -->
<!-- _class: lead _ -->
<style>
.intro-container {
  display: flex;
  align-items: center;
  justify-content: space-around;
  margin-top: 20px;
}

.intro-text {
  flex: 1;
  text-align: left;
  padding: 0 20px;
}

.intro-image {
  flex: 1;
  text-align: center;
}

.emoji-container {
  font-size: 10em;
  margin-top: 20px;
  display: flex;
  justify-content: center;
  gap: 20px;
}
</style>

<div class="intro-container">
  <div class="intro-text">
    <div class="emoji-container">
        <div>🇱🇰</div>
        <div>🍜</div>
    </div>
    <p>Lead Engineer exploring the frontend wilderness</p>
    <p>AWS ☁️ Enthusiast</p>
  </div>
  <div class="intro-image">
    <!-- Replace 'your-avatar.png' with your actual avatar image -->
    <img src="assets/avatar.jpeg" width="300" alt="Sriram's Avatar">
  </div>
</div>

---

<!-- Slide 2 -->
<!-- _class: lead _ -->
<style>
.pixelated {
  font-family: "Courier New", Courier, monospace;
  font-size: 1em; /* Increased font size */
  text-shadow: 0 0 5px #000, 0 0 4px #000, 0 0 9px #000; /* Enhanced shadow for stronger pixel effect */
  letter-spacing: 3px; /* Increased letter spacing */
}

</style>

## Soooooo many **frameworks**

# <i> Too **fast** </i>

<span class="pixelated">Requires pixel perfection</span>

# <!--fit--> Not for **me**.

![bg full](assets/js-framework-explosion.jpg)

---

<!-- Slide 3 -->
<!-- _class: lead _ -->
<style>
@keyframes carousel-move {
  0% {
    transform: translateX(-100%);
  }
  100% {
    transform: translateX(100%);
  }
}

.carousel {
  display: inline-block;
  font-size: 1.5em;
  color: #ff4500; /* Highlighted color */
  animation: carousel-move 5s linear infinite; /* Left-to-right animation */
  white-space: nowrap; /* Prevent text wrapping */
  position: absolute; /* Allow positioning across the full page */
  top: 50%; /* Center vertically */
  left: 0; /* Start from the left edge */
  transform: translateY(-50%); /* Adjust for vertical centering */
  width: 100%; /* Ensure it spans the full width */
  text-align: center; /* Center the text horizontally */
}
</style>

  <h1>Blogger</h1>
  <span class="carousel">Carousels</span>.
  <h1>Autoplay music</h1>

---

<!-- Slide 4 -->
<!-- _class: lead _ -->

# <!--fit--> 👉 frontend by ✍️ tests.

---

<!-- Slide 5 -->
<style>
@import url('https://fonts.googleapis.com/css2?family=Pacifico&display=swap');

.split-screen {
  display: flex;
  height: 100vh; /* Full slide height */
  margin: 0;
  position: relative;
}

.left {
  flex: 1;
  background: black;
  color: green;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: monospace;
  font-size: 2em;
}

.right {
  flex: 1;
  background: linear-gradient(45deg, #ff7eb3, #ff758c);
  color: white;
  display: flex;
  justify-content: center;
  align-items: center;
  font-family: 'Pacifico', cursive; /* Added a pretty font */
  font-size: 2em;
  position: relative;
}

.middle {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  font-size: 3em;
  font-weight: bold;
  color: white;
  z-index: 10;
}
</style>

<!-- Slide 5 -->
<div class="split-screen">
  <div class="left">Servers <br> YAML</div>
  <div class="middle">&gt;</div>
  <div class="right">✨Styling✨<br> ✨CSS✨</div>
</div>

---

<!-- Slide 6 -->

![Timeline](assets/timeline.png)

---

<!-- Slide 7 -->
<style>
.earnings {
  font-size: 4em;
  font-weight: bold;
  color: #ffd700; /* Gold color for emphasis */
  text-shadow: 0 0 10px #ffd700, 0 0 20px #ffd700;
  margin-bottom: 20px;
}

vue-logo {
  width: 100px;
  margin-bottom: 20px;
}

 .demo-button {
  font-size: 1.5em;
  color: white;
  background: #42b883; /* Vue.js green */
  padding: 10px 20px;
  border-radius: 5px;
  text-decoration: none;
  box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
  transition: background 0.3s;
}

.demo-button:hover {
  background: #2a9d6f;
}


</style>

# <!--fit--> Altcoin Weekend 💸

<div class="altcoin-slide">
  <div class="earnings">$19K</div> <a href="https://astrokitty.pages.dev" class="demo-button" target="_blank">Live Demo</a>
</div>

---

<!-- Slide 8 -->

# Crafty Live Demo

> "I didn't do much of the frontend here, but I helped build out certain features."

<a href="https://prod.crafty.versent.io"><img src="assets/crafty-bear.png" width="400" alt="Crafty Avatar"></a>

---

<!-- Slide 9 -->
<!-- _class: lead _ -->
<!--fit-->

# **AI Helped A Lot**

![bg left:40%](assets/duck-ai.png)

_Copilot._ _ChatGPT_. _Claude_. _My 24/7 pair buddy._

---

<!-- Slide 10 -->
<!-- _class: lead _ -->
<!--fit-->

# <!--fit--> Still not **frontend-y**…

## _but I get it now (**kinda**). And I’m not afraid._

---

<!-- Slide 11 -->
<style>
.devjam-slide {
  background: linear-gradient(135deg, #4776E6, #8E54E9); /* Vibrant gradient background */
  color: white;
  padding: 20px;
  border-radius: 10px;
  text-align: center;
}

.devjam-title {
  font-size: 2.5em;
  font-weight: bold;
  margin-bottom: 10px;
  text-shadow: 0 2px 4px rgba(0,0,0,0.2);
}

.devjam-subtitle {
  font-style: italic;
  font-size: 1.5em;
  margin-bottom: 20px;
}

.highlight {
  background: rgba(255,255,255,0.2);
  padding: 2px 8px;
  border-radius: 4px;
}

.call-to-action {
  font-size: 1.8em;
  margin-top: 20px;
  font-weight: bold;
  animation: pulse 2s infinite;
}

@keyframes pulse {
  0% { transform: scale(1); }
  50% { transform: scale(1.05); }
  100% { transform: scale(1); }
}
</style>

<div class="devjam-slide">
  <div class="devjam-title">DevJam = <span class="highlight">low stakes</span>, <span class="highlight">high growth</span></div>
  <div class="devjam-subtitle">Theme: <span class="highlight">Agentic AI</span></div>
  <p>Try anything. AI has your back.</p>
</div>

---

<!-- Slide 12 -->
<!-- _class: lead _ -->
<!--fit-->

## <!--fit--> Curiosity + **Caffeine** + **Copilot** = 🚀
