<!-- HEADER -->
<h1 align="center">Hey there 👋, I'm <span style="color:#f75c7e;">Harshvinder Singh</span></h1>
<h3 align="center">🚀 Tech Explorer | 💡 Lifelong Learner | 🧠 AI Enthusiast</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=24&pause=1000&center=true&vCenter=true&multiline=true&width=700&height=80&lines=⚡+Engineer+in+the+Making;🌐+Full-stack+Developer;🤖+AI+%2B+ML+Explorer;🎯+Focused+on+Growth+%26+Impact" alt="Typing SVG" />
</p>

---

## 👨‍💻 About Me

🎓 Pursuing **M.Tech** at **Lovely Professional University**  
🌱 Passionate about:
- 🤖 Artificial Intelligence & Machine Learning  
- 📊 Data Science, Analytics & Visualizations  
- 🌐 Web Development & Automation Tools  

🔥 Currently building exciting projects & sharpening my skills  
🎯 Long-term Vision: **Becoming a versatile engineer & a creative problem-solver**

💬 Ask me about:
- 📌 AI, ML, Deep Learning
- 🛠️ Python, Web Dev, GitHub tricks
- 📚 Productivity hacks & smart learning

---

## 🎮 Flappy Bird Game

<p align="center">
  <iframe 
    src="https://giphy.com/embed/du3J3cXyzhj75IOgvA" 
    width="300" 
    height="200" 
    frameBorder="0" 
    allowFullScreen 
    style="border-radius: 12px;">
  </iframe>
  <br><br>
  <a href="https://flappybird.io/" target="_blank" align="center">
    <img src="https://img.shields.io/badge/Play%20Flappy%20Bird-Click%20Here-ff69b4?style=for-the-badge&logo=game-controller&logoColor=white">
  </a>
</p>

---

## 🌟 Motivational Quote Generator

<p align="center">
  <div style="background-color: #212121; color: white; border-radius: 12px; padding: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.5); width: 80%; text-align: center;">
    <h3>Get Your Daily Motivation</h3>
    <p id="quote" style="font-size: 18px; font-weight: bold; color: white;"></p>
    <button id="new-quote-btn" onclick="generateQuote()" style="padding: 10px 20px; background-color: #ff69b4; color: white; border-radius: 12px; cursor: pointer;">Get New Quote</button>
  </div>
</p>

<!-- Motivational Quote Script -->
<script>
  async function generateQuote() {
    const response = await fetch('https://api.quotable.io/random');
    const data = await response.json();
    const quoteText = data.content || "Oops! No quotes available right now.";
    document.getElementById('quote').textContent = `"${quoteText}"`;
  }

  // Initial quote load
  generateQuote();
</script>

---

## 🎭 Fun Facts

<p align="center">
  <ul style="list-style-type: none; color: #f75c7e; font-size: 18px; font-weight: bold;">
    <li>🧠 I love diving into new tech and exploring unknown horizons.</li>
    <li>🎧 Music fuels my productivity, especially lo-fi beats while coding.</li>
    <li>☕ Coffee is my coding companion, and bugs are my nemesis.</li>
    <li>🛸 I'm passionate about building tech that simplifies life.</li>
  </ul>
</p>

---

## 🎭 Dev Humor (18+ 🤫)

<div id="joke-container" style="text-align: center; padding: 10px; background-color: #212121; border-radius: 12px;">
  <h3 style="font-family: 'Fira Code', monospace; color: #f75c7e;">🤖 Here's a Dev Joke (18+ 😜)</h3>
  <p id="joke-text" style="font-size: 18px; font-weight: bold; color: white;"></p>
  <button id="new-joke-btn" onclick="getJoke()" style="padding: 10px 20px; background-color: #ff69b4; color: white; border-radius: 12px; cursor: pointer;">Get New Joke</button>
</div>

<!-- Joke Script -->
<script>
  async function getJoke() {
    const response = await fetch('https://v2.jokeapi.dev/joke/Programming?lang=en&type=single');
    const data = await response.json();
    const jokeText = data.joke || "Oops! No jokes available right now.";
    document.getElementById('joke-text').textContent = jokeText;
  }

  // Initial joke load
  getJoke();
</script>

---

## 🎮 Interactive Code Snippet

<p align="center">
  <div style="background-color: #212121; color: white; border-radius: 12px; padding: 20px; box-shadow: 0 4px 12px rgba(0,0,0,0.5); width: 80%; text-align: center;">
    <h3>Try this Python Code Snippet!</h3>
    <p>Click to view a Python code snippet:</p>
    <button onclick="alert('print(\"Hello, World!\")')" style="padding: 10px 20px; background-color: #ff69b4; color: white; border-radius: 12px; cursor: pointer;">View Code</button>
  </div>
</p>

---

## 📫 Let's Connect

<p align="center">
  <a href="https://www.linkedin.com/in/harshvindersingh15122000/" target="_blank">
    <img src="https://img.shields.io/badge/-LinkedIn-%230077B5?style=for-the-badge&logo=linkedin&logoColor=white"/>
  </a>
  <a href="mailto:singh.harshvinder2000@gmail.com">
    <img src="https://img.shields.io/badge/-Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white"/>
  </a>
</p>

---

<p align="center">
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="300" style="border-radius: 12px;" />
</p>

<h3 align="center">⚡ Building the future, one line of code at a time ⚡</h3>
