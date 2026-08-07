<h1 align="center">Hi there, I'm Md Raghib Rahi 👋</h1>

<h3 align="center">🎓 MCA Graduate | 💻 Full-Stack Web Developer | 📊 Aspiring Data Scientist</h3>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=2E9EF7&center=true&vCenter=true&width=600&lines=Full-Stack+Web+Developer;MERN+Stack+Enthusiast;DSA+%2B+Problem+Solver;Learning+Data+Science+%26+AI;Code.+Learn.+Build.+Improve.+Repeat." alt="Typing SVG" />
</p>

<p align="center">
  <a href="#"><img src="https://img.shields.io/badge/Status-Open%20to%20Work-brightgreen?style=for-the-badge" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Focus-Full--Stack%20Dev-blue?style=for-the-badge" /></a>
  <a href="#"><img src="https://img.shields.io/badge/Learning-Data%20Science-orange?style=for-the-badge" /></a>
</p>

---

### 🚀 About Me

- 🎓 Graduated with a **Master of Computer Applications (MCA)**
- 💻 Skilled in **Python, JavaScript, C, HTML, CSS, React, Node.js, Express.js, and MongoDB**
- 📊 Currently expanding my knowledge in **Data Science, Machine Learning, and Artificial Intelligence**
- 🧩 Passionate about **Data Structures & Algorithms (DSA)** and problem-solving
- 🌱 Always learning new technologies and improving my development skills
- 🎯 Focused on building clean, efficient, and user-friendly applications

---

### 🛠️ Tech Stack

**Languages**
<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white" />
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" />
</p>

**Frontend**
<p>
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" />
  <img src="https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white" />
</p>

**Backend**
<p>
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white" />
</p>

**Database**
<p>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" />
</p>

**Tools**
<p>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />
  <img src="https://img.shields.io/badge/VS_Code-007ACC?style=flat-square&logo=visualstudiocode&logoColor=white" />
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
  <img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />
</p>

---

### 📌 Current Focus

- 🏗️ Building Full-Stack Web Applications
- 🧠 Strengthening Data Structures & Algorithms
- 📈 Learning Data Science & Machine Learning
- ☁️ Exploring Cloud Technologies
- 🌍 Contributing to Open Source

---

### 📂 Featured Projects

| Project | Description | Status |
|---|---|---|
| 📱 **MERN Stack Applications** | Full-stack apps built with MongoDB, Express, React, and Node.js | 🚧 In Progress |
| 🐍 **Python Beginner Projects** | A collection of foundational Python projects | ✅ Complete |
| 📐 **Area Calculator** | A simple utility to calculate area for various shapes | ✅ Complete |
| 🍔 **Fast Food Billing System** | A billing system project for a fast-food scenario | ✅ Complete |
| 🔢 **DSA Solutions** | Data Structures & Algorithms solutions in C & Python | 🚧 In Progress |
| 🚀 **E-Commerce Platform** | Full-featured online store with payment integration | 🔜 Coming Soon |

---

### 📊 GitHub Stats

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=git-Raghib&show_icons=true&theme=tokyonight&hide_border=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=git-Raghib&layout=compact&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=git-Raghib&theme=tokyonight&hide_border=true" />
</p>

<p align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=git-Raghib&theme=tokyonight&row=2&column=3" />
</p>

---

### 💡 Code Snapshot

```python
# Example: Two Sum Problem - O(n) solution
def two_sum(nums, target):
    seen = {}
    for i, num in enumerate(nums):
        complement = target - num
        if complement in seen:
            return [seen[complement], i]
        seen[num] = i
    return []

# Example: Binary Search - O(log n) solution
def binary_search(arr, target):
    left, right = 0, len(arr) - 1
    while left <= right:
        mid = (left + right) // 2
        if arr[mid] == target:
            return mid
        elif arr[mid] < target:
            left = mid + 1
        else:
            right = mid - 1
    return -1
