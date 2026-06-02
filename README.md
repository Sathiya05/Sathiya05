It looks like you've put together a fantastic and comprehensive GitHub profile! If the images, badges, and stat cards are showing up as broken links or plain text when you paste this into your GitHub `README.md`, it boils down to a few strict rules in how GitHub parses Markdown.

Here is exactly why they aren't working and how to fix them:

### 1. Markdown Inside HTML Tags

GitHub Flavored Markdown (GFM) stops rendering Markdown syntax (like `![Alt](URL)`) if it is placed immediately inside an HTML tag like `<div align="center">` or `<details>`.

* **The Fix:** You either need to leave a completely blank line between the HTML tag and the Markdown, or strictly use HTML `<img>` tags inside your `<div>` containers. Using `<img>` tags is the safest and cleanest way to guarantee perfect center alignment.

### 2. Missing Table Formatting

Your Projects, Achievements, Education, and Certifications sections are currently written as plain text separated by spaces.

* **The Fix:** They need to be wrapped in proper Markdown table syntax (using `|` and `-`) so they render as clean, professional data tables.

### 3. Missing Blank Lines in Dropdowns

In your Work Experience section, the text and badges inside the `<details>` tags will break because there is no blank line immediately following the `<summary>` tag.

---

### The Corrected Code

I have fixed all the formatting conflicts, converted your centered elements to proper HTML tags for perfect alignment, and structured your text into clean tables. Copy and paste the code block below directly into your GitHub `README.md`:

```markdown
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=180&section=header&text=Sathiya%20Priya%20S&fontSize=42&fontColor=fff&animation=twinkling&fontAlignY=32&desc=Frontend%20Developer%20%7C%20UI%2FUX%20Designer%20%7C%20Upcoming%20MERN%20Stack%20Developer&descAlignY=62&descSize=16" width="100%" alt="Header"/>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=26&duration=3000&pause=1000&color=70A5FD&center=true&vCenter=true&width=750&lines=Hi+There%2C+I%27m+Sathiya+Priya+%F0%9F%91%8B;Frontend+Developer+%7C+UI%2FUX+Designer;Upcoming+MERN+Stack+Developer+%F0%9F%9A%80;Turning+Ideas+into+Interactive+Reality+%E2%9C%A8" alt="Typing SVG" />
  <br/>
  <img src="https://komarev.com/ghpvc/?username=Sathiya05&color=70a5fd&style=flat-square&label=Profile+Views" alt="Profile Views" />
  <img src="https://img.shields.io/github/followers/Sathiya05?style=flat-square&color=70a5fd&logo=github&logoColor=white" alt="GitHub followers" />
  <img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
</div>

---

### 👩‍💻 About Me

<img align="right" width="360" src="https://raw.githubusercontent.com/abhisheknaiidu/abhisheknaiidu/master/code.gif" alt="Coding GIF"/>

```javascript
const sathiyaPriya = {
  name        : "Sathiya Priya S",
  location    : "Bargur, Krishnagiri District, Tamil Nadu",
  degree      : "B.E. Computer Science & Engineering (CGPA: 8.81)",
  university  : "Er. Perumal Manimekalai College of Engineering",
  currentRole : "Frontend Developer @ Growwpark Technologies, Hosur",

  stack: [
    "React", "JavaScript", "HTML5",
    "CSS3", "Tailwind CSS", "Python", "SQL"
  ],

  learning: ["MongoDB", "Express.js", "Node.js", "TypeScript"],
  design: ["Figma", "Framer", "Adobe Express", "Canva"],
  analytics: ["Power BI", "Tableau", "MS Excel"],
  
  funFact : "I won 1st place in Paper Presentations — twice!",

  motto() {
    return "Design with empathy. Code with precision. Ship with confidence.";
  }
};

```

---

### 🛠️ Tech Stack & Tools

**💻 Languages** 





**⚛️ Frameworks & Libraries** 





**🎨 UI/UX & Design** 




**📊 Data & Analytics** 



**🌐 Tools & Platforms** 





---

### 📊 GitHub Stats

---

### 🔥 Streak Stats

---

### 📈 Activity Graph

---

### 🏆 Trophy Wall

---

### 💼 Work Experience

> 🚀 Actively contributing to multiple live projects by designing and developing responsive, user-friendly web interfaces
> 🎨 Implementing best UI/UX practices and performance optimization techniques across all products
> 🤝 Collaborating with cross-functional teams including designers, backend developers, and product managers
> 📈 Continuously improving skills in modern frontend technologies and performance optimization

> 📱 Developed and deployed a functional Android application featuring converter and calculator tools
> ⚡ Ensured accuracy and efficiency in computations while optimizing the user interface for a seamless experience
> 🛠️ Gained hands-on experience in mobile app development lifecycle from design to deployment

> 🌐 Acquired foundational knowledge in web design including HTML, CSS, and responsive layouts
> 📐 Developed a strong understanding of structuring and styling web pages for enhanced user experience
> 💡 Explored principles of responsive design and cross-browser compatibility

---

### 🚀 Featured Projects

| 🗂️ Project | 🛠️ Stack | ✨ Highlights |
| --- | --- | --- |
| **MINDSCAPE — AI Mental Health Analysis** | Python · AI · ML · Social Media APIs · Wearable Devices | Final year project · Analyzes mental health via social media & wearable data · End-to-end AI pipeline |
| **ATM Card Fraud Detection** | Python · IBM Cloud · ML · Naan Mudhalvan | Fraud detection model on IBM platform · Real-time transaction analysis · Tamil Nadu Govt. initiative |
| **Coffee Shop Sales & Inventory Analysis** | Power BI · MS Excel · DAX · Data Modeling | Interactive dashboards · Sales trend analysis · Inventory tracking with visual KPIs |
| **Figma UI/UX Designs** | Figma · Framer · UI/UX Design | Food Ordering App · Movie Ticket Booking · Pizza Landing Page · Nike Shoe Page · E-commerce Website |

---

### 🏅 Achievements & Presentations

| 🏆 | Achievement | Details |
| --- | --- | --- |
| 🥇 | **1st Place — Paper Presentation** | InterCollege Symposium EUREKHA 2k21 @ PMC TECH |
| 🥇 | **1st Place — Paper Presentation** | Science Club Event 2k21 @ PMC TECH |
| 🥈 | **2nd Place — Paper Presentation** | InterCollege Symposium @ PSV College |
| 📄 | **Paper Presentation Participant** | InterCollege Symposium @ MGR College |
| 📄 | **Paper Presentation Participant** | InterCollege Symposium @ Podhigai College |
| 🔬 | **National Conference Presenter** | TECHSYNERGY 2025 — Project Paper Presentation @ PMC TECH |
| 🧠 | **Workshop — Data Structures & Data Science** | Oct 2022 · 2 days |
| 🤖 | **Workshop — Neural Networks for Decision-Making** | VEI Technologies · Mar 2024 · 5 days |

---

### 🎓 Education

| 📚 Degree | 🏫 Institution | 📅 Year | 🎯 Score |
| --- | --- | --- | --- |
| **B.E. Computer Science & Engineering** | Er. Perumal Manimekalai College of Engineering, Hosur · Anna University | 2021 – 2025 | CGPA: 8.81 |
| **HSC (Class XII)** | Selva Matric Higher Secondary School, Bargur · State Board | 2020 – 2021 | 93% |
| **SSLC (Class X)** | St. Pauls Matriculation School, Mallapadi · State Board | 2018 – 2019 | 93% |

---

### 📜 Certifications

| 🏅 | Certification | Issuer |
| --- | --- | --- |
| 🐍 | **Python and AI For India 2.0** | GUVI |
| 🤖 | **Basis of Python** | Infosys Springboard |
| 🧠 | **Elements of an Artificial Intelligence Architect** | Infosys Springboard |
| 🎨 | **Introduction to Graphic Design: Basics to UI/UX** | SimpliLearn |
| 📊 | **Introduction to Data Analytics** | SimpliLearn |
| 📈 | **Microsoft Data Analytics Course** | Infosys ICT Academy |

---

### 🌱 Currently Learning

```text
🟢 MongoDB        →  Atlas · Compass · CRUD · Aggregation · Mongoose
🟡 Express.js     →  REST APIs · Middleware · Routing · Authentication
🔵 Node.js        →  Server-side JS · npm · Async/Await · File System
⚛️  React (Adv)   →  Custom Hooks · Context API · React Query · Performance
🔷 TypeScript     →  Types · Interfaces · Generics · TS with React
📊 Power BI Adv   →  DAX Formulas · Dashboard Design · Data Modeling

```

---

### 📬 Connect With Me

---
