<h1 align="center">Hi 👋, I'm Charvee Masand</h1>

<p align="center">
  <b>B.Tech CSE (AI & ML) Student</b> • Full-Stack • APIs • Open Source
</p>

<p align="center">
  I love building clean, functional products and learning by shipping real projects.
</p>
### 🚀 What I’m working on

- Building frontend projects using **HTML, CSS, JavaScript, React**
- Exploring **APIs and backend basics** with Node.js
- Learning **AI & ML fundamentals** as part of my CSE specialization
- Contributing to projects to improve real-world development skills
### 🛠 Tech Stack

**Languages**
<br/>
<img src="https://skillicons.dev/icons?i=c,cpp,java,python,js,ts" />

**Frontend**
<br/>
<img src="https://skillicons.dev/icons?i=html,css,react,tailwind,nextjs" />

**Backend & Tools**
<br/>
<img src="https://skillicons.dev/icons?i=nodejs,express,git,github,vercel" />
### 📌 Featured Projects

- 🍽 **Recipe Finder App**  
  A JavaScript app using a public API to search and display recipes.  
  🔗 https://recipe-app-three-psi.vercel.app  

- 💰 **Budget Tracker App**  
  Flutter + Firebase app to manage expenses with authentication.

- 🧠 **AI Mini Projects**  
  Small experiments while learning AI & ML fundamentals.
### 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=charveemasand108&show_icons=true&theme=tokyonight" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com?user=charveemasand108&theme=tokyonight" />
</p>
### 🖥️ Systems

![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![Arch Linux](https://img.shields.io/badge/Arch_Linux-1793D1?style=for-the-badge&logo=arch-linux&logoColor=white)
![FreeBSD](https://img.shields.io/badge/FreeBSD-AB2B28?style=for-the-badge&logo=freebsd&logoColor=white)

### 🔧 Hardware

![Google Coral](https://img.shields.io/badge/Google_Coral-4285F4?style=for-the-badge&logo=google&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberry-pi&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
name: Generate Pacman Contribution Graph

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: charveemasand108
          outputs: |
            dist/pacman-contribution-graph.svg
      - uses: crazy-max/ghaction-github-pages@v3
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
### 🟩 Contribution Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/charveemasand108/charveemasand108/output/pacman-contribution-graph.svg" />
</p>
### 👨‍💻 About Me

- 🤖 Interested in the intersection of **AI, systems, and user-centric design**
- 🧠 Exploring **Prompt Engineering** and real-world LLM integration
- 🖥️ Enjoy building **full-stack apps** and custom Linux setups (Arch / BSD / Hyprland)
- 📚 Strong believer in mastering **CS fundamentals** — DSA, OS, and systems
### ⚡ Fun Fact

> Programming is **40% writing code** and **60% debugging**… and the rest is Googling 😄
---

> “Code for a cause, build for the future.” 🚀
