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

<!-- Speaker Notes: -->
<!-- Kick off with a smile. -->
<!-- “Hi everyone, I’m Sriram — a backend engineer who somehow ended up touching Tailwind and JSX. This is the story of how that happened — not intentionally — but by stumbling, learning, and laughing along the way.” -->

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

# <!--fit--> Not for **me**
<!-- Speaker Notes: -->
<!-- “You know the meme: new JS framework every week. As a backender, this felt exhausting and mysterious. Why does everyone care about pixels? I just wanted to ship something that worked. I once memorized how to center a div just for interviews… not because I understood it!” -->

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

<!-- Speaker Notes: -->
<!-- “This was my actual first frontend project — editing Blogger templates, adding music, carousels, making it all very… chaotic. But it was fun. And unknowingly, this was my first exposure to web UI.” -->

---

<!-- Slide 4 -->
<!-- _class: lead _ -->

# <!--fit--> 👉 frontend by ✍️ tests.

<!-- Speaker Notes: -->
<!-- “Fast forward a few years, I’m working with Behat, testing interfaces with CSS selectors. Technically touching the frontend... with a very long stick. I wasn’t designing, just verifying if stuff didn’t explode.” -->

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

<div class="split-screen">
  <div class="left">Servers <br> YAML</div>
  <div class="middle">&gt;</div>
  <div class="right">✨Styling✨<br> ✨CSS✨</div>
</div>

<!-- Speaker Notes: -->
<!-- “I thrived in infra land. Give me a terminal, logs, or Ansible — I’m happy. Styling though? Absolute chaos. Font-weight: 500? 600? Bold? Help. YAML made more sense than CSS to me.” -->

---

<!-- Slide 6 -->

![Timeline](assets/timeline.png)

<!-- Speaker Notes: -->
<!-- “At Versent, I started in a platform team — Jenkins, pipelines, cloud infra. Then APIs at Transurban. Then events at Shell Energy. This slow but steady shift brought me closer to apps — and frontend wasn’t optional anymore.” -->

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

<!-- Speaker Notes: -->
<!-- “In a burst of chaotic motivation, my friends and I built an altcoin site using Vue. In one weekend we made $19K. We were stunned. Vue was overkill for landing pages, but the project was alive and real!” -->

---

<!-- Slide 8 -->

# Crafty Live Demo

> "I didn't do much of the frontend here, but I helped build out certain features."

<a href="https://prod.crafty.versent.io"><img src="assets/crafty-bear.png" width="400" alt="Crafty Avatar"></a>

<!-- Speaker Notes: -->
<!-- “Crafty was a project I helped on — not as the main frontend dev, but I contributed components and learned how modern React setups worked. A real team effort. And I started appreciating things like design systems.” -->

---

<!-- Slide 9 -->
<!-- _class: lead _ -->
<!--fit-->

# **AI Helped A Lot**

![bg left:40%](assets/duck-ai.png)

_Copilot._ _ChatGPT_. _Claude_. _My 24/7 pair buddy._

<!-- Speaker Notes: -->
<!-- “Let’s be honest — frontend is hard. Hooks? State? Tailwind? Having Copilot and ChatGPT was like having a 24/7 teammate. I didn’t always understand everything I pasted, but I could ask why — and that’s powerful.” -->

---

<!-- Slide 10 -->
<!-- _class: lead _ -->
<!--fit-->

# <!--fit--> Still not **frontend-y**…

## _but I get it now (**kinda**). And I’m not afraid._

<!-- Speaker Notes: -->
<!-- “I’m still not a pixel-perfect frontend dev. But I’m not afraid to try anymore. And that shift in mindset is everything. I don’t need to master it all — just stay curious and build.” -->

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

<!-- Speaker Notes: -->
<!-- “This talk, this whole journey, happened because I said yes to DevJam. It’s a safe space to try new tech, take risks, and just make something weird and cool. Seriously, get involved.” -->

---

<!-- Slide 12 -->
<!-- _class: lead _ -->
<!--fit-->

<style>
  .rainbow-text {
    background: linear-gradient(to right, red, orange, yellow, green, blue, indigo, violet);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
    font-weight: bold;
  }
</style>

## <!--fit--> Curiosity + **Caffeine** + <span class="rainbow-text">Copilot</span> = 🚀

<!-- Speaker Notes: -->
<!-- “Frontend still scares me a bit. But with curiosity, caffeine, and Copilot — you can build real things. Even accidentally. Like an altcoin site. Or a live demo. Or this talk.” -->
