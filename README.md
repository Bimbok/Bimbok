<div align="center">

<!-- Animated Header -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=200&section=header&text=Bratik%20Mukherjee&fontSize=80&fontAlignY=35&animation=twinkling&fontColor=fff" width="100%"/>

<!-- Typing Animation -->
<a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=00D9FF&center=true&vCenter=true&multiline=true&repeat=true&random=false&width=800&height=150&lines=Full+Stack+Developer+%F0%9F%9A%80;B.Tech+IT+Student+%F0%9F%8E%93;Building+Impactful+Solutions+%F0%9F%92%A1;Open+Source+Enthusiast+%E2%9C%A8" alt="Typing SVG" /></a>
<p align="center">
  <em>Transforming Ideas into Elegant Digital Experiences</em>
</p>

<!-- Animated Social Badges -->
<p align="center">
  <a href="https://www.linkedin.com/in/bratik-mukherjee/" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white&animation=pulse" alt="LinkedIn"/>
  </a>
  <a href="https://github.com/Bimbok" target="_blank">
    <img src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/>
  </a>
  <a href="mailto:bimbokmkj@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
  <a href="https://bimbok-portfolio.vercel.app/" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" alt="Portfolio"/>
  </a>
</p>

<!-- Profile Views & Followers -->
<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Bimbok&label=Profile%20Views&color=blueviolet&style=for-the-badge" alt="Profile views" />
  <img src="https://img.shields.io/github/followers/Bimbok?label=Followers&style=for-the-badge&color=blue" alt="followers" />
  <img src="https://img.shields.io/github/stars/Bimbok?label=Stars&style=for-the-badge&color=yellow" alt="stars" />
</p>

</div>

---

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 🎯 About Me

</div>

<img align="right" alt="Coding" width="400" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif"/>

```typescript
const Bratik = {
    location: "Kolkata, India 🇮🇳",
    education: "B.Tech IT @ TMSL",
    currentYear: "3rd Year",
    
    code: ["JavaScript", "TypeScript", "Python", "C++", "Bash"],
    
    technologies: {
        frontEnd: {
            js: ["React", "Next.js"],
            css: ["Tailwind", "Bootstrap", "Material-UI"]
        },
        backEnd: {
            js: ["Node.js", "Express"],
            python: ["Django", "Flask"]
        },
        databases: ["MongoDB", "PostgreSQL", "MySQL", "Firebase"],
        devOps: ["Docker", "Kubernetes", "CI/CD", "Nginx", "Vercel"],
        linux: {
            distros: ["Arch Linux (Daily Driver)", "Ubuntu"],
            expertise: ["CLI Automation", "System Hardening", "Shell Scripting"]
        },
        tools: ["Git", "Neovim", "Tmux", "Postman", "Figma"]
    },
    
    currentFocus: "Mastering Cloud Native Ecosystem & Linux Internals",
    learning: ["Rust", "Advanced Kubernetes", "System Design"],
    
    philosophy: "Automation is the ultimate form of laziness (the good kind) 🐧"
};
```

<br clear="right"/>

### 🚀 What I'm Up To

- 🔭 Building a **MERN stack application** with real-time features
- 🌱 Daily driving **Arch Linux** and optimizing my **Linux CLI workflow**
- 🛠️ Automating everything with **Bash scripts** and **DevOps pipelines**
- 👯 Looking to collaborate on **Open Source** & **Infrastructure projects**
- 💼 Open for **internships** and **full-time opportunities**
- 💬 Ask me about **Linux, Docker, Kubernetes**, or **Full-Stack Development**
- ⚡ Fun fact: I use Arch btw (but I started with Ubuntu) 🐧

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 🏆 Featured Projects

</div>

<div align="center">

### 🌊 [AlgoScope](https://algo-scope-virid.vercel.app/) — Interactive Algorithm Visualizer

<a href="https://algo-scope-virid.vercel.app">
  <img src="Sample/2026-05-10-102609_hyprshot.png" alt="AlgoScope" width="600px" style="border-radius: 10px;"/>
</a>

**A modern, interactive algorithm visualizer that demystifies complex logic through real-time, high-fidelity animations.**

[![React](https://img.shields.io/badge/React-19-61DAFB?style=flat&logo=react&logoColor=white)](https://react.dev/)
[![Vite](https://img.shields.io/badge/Vite-7.x-646CFF?style=flat&logo=vite&logoColor=white)](https://vitejs.dev/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind--CSS-4.x-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![Docker Hub](https://img.shields.io/badge/Docker-Hub-2496ED?style=flat&logo=docker&logoColor=white)](https://hub.docker.com/r/bimbok/algoscope-app)

<details>
<summary><b>🔍 Explore AlgoScope Deep Dive</b></summary>

#### 💡 Project Purpose
**AlgoScope** bridges the gap between static pseudocode and dynamic execution. By transforming abstract logic into fluid animations, it helps users build a mental model of how algorithms actually work.

#### ✨ Key Features
- **Real-time Visualization:** Smooth, step-by-step animations using Framer Motion and Anime.js.
- **Algorithm Coverage:** Comprehensive support for Sorting, Searching, and Graph Algorithms.
- **Code Insights:** Multi-language implementation (C++, Java, Python, JS) alongside the visualization.

#### 🏗️ Architecture & Data Flow
```mermaid
flowchart TD
    user[User] -- Parameters --> logic[Algorithm Engine]
    logic -- State Updates --> state[State Manager]
    state -- Data --> vis[Visualizer Renderer]
    vis -- Animation --> user
```

</details>

---

### 🌸 [Sizuka Language](https://github.com/Bimbok/Sizuka) — Interpreted JVM Language

**A clean, interpreted programming language built from scratch in Java.**

Sizuka runs on the JVM and features a custom recursive descent parser and a tree-walk interpreter, designed to explore core compiler design concepts.

[![Java](https://img.shields.io/badge/Java-17+-ED8B00?style=flat&logo=java&logoColor=white)](https://www.oracle.com/java/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat)](LICENSE)

<details>
<summary><b>📝 View Syntax & Features</b></summary>

#### ⚡ Features
- **Variables & Arithmetic:** Dynamic typing with `say` keyword and full operator precedence.
- **Packs (Arrays):** Built-in support for dynamic, zero-indexed collections.
- **Control Flow:** `if`/`else` branching, `from` loops, and `while` loops.
- **Interactive REPL:** Instant code execution shell.

#### 📝 Syntax Preview
```text
say x = 10
from 1 to 5 as i {
    out "Sizuka iteration: " + (x * i)
}
```

</details>

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 🛠️ Tech Stack & Tools

</div>

### 💻 Languages

<p align="center">
  <img src="https://skillicons.dev/icons?i=js,ts,python,cpp,java,html,css,bash" />
</p>

### 🎨 Frontend Development

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,bootstrap,materialui,redux,vite" />
</p>

### ⚙️ Backend Development

<p align="center">
  <img src="https://skillicons.dev/icons?i=nodejs,express,django,flask,fastapi,graphql" />
</p>

### 🗄️ Databases & Cloud

<p align="center">
  <img src="https://skillicons.dev/icons?i=mongodb,postgres,mysql,redis,firebase,supabase" />
</p>

### 🚀 DevOps & Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,git,github,nginx,vercel,aws,gcp,arch,ubuntu" />
</p>

### 🎨 Design & Other Tools

<p align="center">
  <img src="https://skillicons.dev/icons?i=figma,postman,vscode,linux,vim,neovim,tmux" />
</p>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 📊 GitHub Analytics

</div>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api?username=Bimbok&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" />
  <img width="49%" src="https://github-readme-streak-stats.herokuapp.com/?user=Bimbok&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img width="49%" src="https://github-readme-stats.vercel.app/api/top-langs/?username=Bimbok&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
  <img width="49%" src="https://github-readme-activity-graph.vercel.app/graph?username=Bimbok&theme=tokyo-night&hide_border=true&area=true" />
</p>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=Bimbok&theme=tokyonight&no-frame=true&no-bg=false&margin-w=4&row=1&column=7" width="100%" />
</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 📝 Latest Blog Posts & Articles

</div>

<div align="center">

[![Blog](https://img.shields.io/badge/Read-How%20to%20Config%20Neovim%20with%20LazyVim-00D9FF?style=for-the-badge&logo=vim)](https://github.com/Bimbok/nvim)

[![Blog](https://img.shields.io/badge/Read-Understanding%20Shell%20Internals-00D9FF?style=for-the-badge&logo=gnu-bash)](https://github.com/Bimbok/myshell)

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 💭 Random Dev Quote

<img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" />

</div>

<img src="https://user-images.githubusercontent.com/73097560/115834477-dbab4500-a447-11eb-908a-139a6edaec5c.gif">

<div align="center">

## 🤝 Let's Connect & Collaborate!

<p align="center">
  <a href="https://www.linkedin.com/in/bratik-mukherjee/">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="mailto:bimbokmkj@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-Email%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white" />
  </a>
  <a href="https://bimbok-portfolio.vercel.app/">
    <img src="https://img.shields.io/badge/Portfolio-Visit-FF5722?style=for-the-badge&logo=google-chrome&logoColor=white" />
  </a>
  <a href="https://github.com/Bimbok">
    <img src="https://img.shields.io/badge/GitHub-Follow-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
</p>

### 💼 Open for Opportunities

I'm actively seeking **internships** and **full-time roles** in Full-Stack Development, Cloud Engineering, or DevOps. Let's build something amazing together!

<p align="center">
  <em>"Code is like humor. When you have to explain it, it's bad." – Cory House</em>
</p>

</div>

<!-- Animated Footer -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=100&section=footer" width="100%"/>

---

<div align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Snake animation" />
</div>

<div align="center">
  
### Show some ❤️ by starring some repositories!

</div>
