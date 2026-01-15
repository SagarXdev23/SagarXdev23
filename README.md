## 🐍 Contribution Activity

<p align="center">
  <img src="https://raw.githubusercontent.com/SagarXdev23/SagarXdev23/main/assets/snake.svg" alt="Snake animation" />
</p>


# 🌌 Programming World of Sagar

Hi, I’m **Sagar Mishra** — a computer science student and passionate programmer exploring the vast space of software development.  
I work primarily with **Java**, **Python**, and **C**, and I enjoy transforming ideas into clean, functional code while solving real-world problems through logic and discipline.

---

## 🧬 About Me
- 🔭 **Currently Learning:** JavaScript & Full-Stack Development  
- 💾 **Databases:** MySQL  
- 🐧 **Experience:** Comfortable with Linux commands & environments  
- 🎯 **2025 Goal:** Build meaningful projects and contribute to open-source  
- ⚡ **Fun Fact:** Debugging feels like solving a puzzle — patience wins  

---

## 🧠 Skills & Tools

### 🖥️ Programming Languages
- Java  
- Python  
- C  
- JavaScript *(learning)*  

### 🌐 Web Development
- HTML  
- CSS  

### 🗃️ Databases
- MySQL  

### ⚙️ Tools & IDEs
- VS Code  
- IntelliJ IDEA  
- Git & GitHub  

### 🐧 Operating Systems
- Linux  
- Windows  

---
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

jobs:
  snake:
    runs-on: ubuntu-latest
    steps:
      - uses: Platane/snk@v3
        with:
          github_user_name: SagarXdev23
          outputs: |
            assets/snake.svg

      - name: Commit snake to main
        uses: EndBug/add-and-commit@v9
        with:
          add: "assets/snake.svg"
          message: "chore: update snake animation"


> *Quiet progress. Strong fundamentals. Long-term growth.*
