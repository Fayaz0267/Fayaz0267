<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=220&section=header&text=Shaik%20Mahammad%20Fayaz&fontSize=44&fontColor=ffffff&animation=twinkling&fontAlignY=38&desc=I%20build%20AI%20that%20people%20can%20actually%20use&descSize=18&descAlignY=60" width="100%" alt="Shaik Mahammad Fayaz" />
</p>

<p align="center">
  <a href="https://git.io/typing-svg">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=2800&pause=900&color=38BDF8&center=true&vCenter=true&width=560&height=45&lines=Aspiring+AI%2FML+Engineer+%F0%9F%A7%A0;Full-Stack+Developer+(MERN)+%F0%9F%8C%90;Computer+Vision+%C2%B7+LLMs+%C2%B7+Web+Apps+%F0%9F%91%81%EF%B8%8F;Currently+building+an+AI+proctoring+system+%F0%9F%8E%A5" alt="Typing animation" />
  </a>
</p>

<p align="center">
  <a href="https://fayaz-portfolio-gamma.vercel.app/"><img src="https://img.shields.io/badge/%F0%9F%9A%80%20Live%20Portfolio-111827?style=for-the-badge" alt="Live Portfolio" /></a>
  <a href="https://www.linkedin.com/in/shaik-mahammad-fayaz-1009bb338"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:Shaikfayaz0267@gmail.com?subject=Hey%20Fayaz%20%F0%9F%91%8B"><img src="https://img.shields.io/badge/Say%20Hello-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20to-Internships-22C55E?style=flat-square" alt="Open to internships" />
  <img src="https://img.shields.io/badge/3rd%20Year-B.Tech%20CSE-38BDF8?style=flat-square" alt="3rd year B.Tech CSE" />
  <img src="https://img.shields.io/badge/Hyderabad-India-F97316?style=flat-square" alt="Hyderabad, India" />
  <img src="https://komarev.com/ghpvc/?username=Fayaz0267&label=Profile%20Views&color=0e75b6&style=flat-square" alt="Profile views" />
</p>

---

## 👋 Hey, I'm Fayaz

> *"I want to ship products that are both intelligent and usable, not just models that live in notebooks."*

Third-year **Computer Science** student at **St. Peter's Engineering College, Hyderabad**, working where **AI/ML** meets **full-stack development**.

| | |
|---|---|
| 🎯 **Focus** | AI/ML engineering · LLMs · Computer vision · Data-driven web apps |
| 🔭 **Building now** | An AI video proctoring system for college exams |
| 🏆 **Hackathon** | NASSCOM FutureSkills Prime GenAI Forge (2026) |
| 💼 **Experience** | Software Engineering Intern, Embrizon Technologies |
| 📬 **Looking for** | AI/ML and software development internships |

---

## 🧭 Pick Your Path

> [!TIP]
> Short on time? Click what describes you and I'll point you to the best stuff.

<details>
<summary><b>🧑‍💼 I'm a recruiter or hiring manager</b></summary>

<br/>

1. **[Live portfolio](https://fayaz-portfolio-gamma.vercel.app/)**: a quick overview of everything
2. **[AI Video Invigilation](#-currently-building)**: my most technical project (computer vision + a real-world workflow)
3. **[DataMind](https://github.com/Fayaz0267/DataMind)**: full-stack + AI in one product
4. **[LinkedIn](https://www.linkedin.com/in/shaik-mahammad-fayaz-1009bb338)** or **[email me](mailto:Shaikfayaz0267@gmail.com?subject=Internship%20opportunity)** to talk

</details>

<details>
<summary><b>🛠️ I want to collaborate or build something</b></summary>

<br/>

I'm open to **hackathon teams, open source and research collaborations**. If your idea involves AI, computer vision or a web product people will really use, [send me a message](mailto:Shaikfayaz0267@gmail.com?subject=Let%27s%20build%20something). I reply fast.

</details>

<details>
<summary><b>🏆 I'm a hackathon organizer or judge</b></summary>

<br/>

I took part in the **NASSCOM FutureSkills Prime GenAI Forge (2026)**. I like building end-to-end: model, backend, UI and deployment. Start with **[CampusEats](https://github.com/Fayaz0267/campuseats-frontend)** and **[PayAI](https://github.com/Fayaz0267/PayAI)** to see how I ship.

</details>

---

## 🚧 Currently Building

### 🎥 AI Video Invigilation

![Status](https://img.shields.io/badge/status-prototype-F59E0B?style=flat-square)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white)

A standalone AI proctoring module designed to plug into an existing college online-exam system.

```mermaid
flowchart TD
    A[📷 Webcam feed] --> B[🧠 MediaPipe<br/>face landmarks + gaze]
    B --> C[⚠️ Event detection<br/>gaze, secondary device]
    C --> D[📊 Risk score<br/>LOW to CRITICAL]
    D --> E[🧑‍🏫 Faculty dashboard<br/>events + evidence]
    E --> F[✅ Faculty makes the final call]

    style A fill:#0f2027,stroke:#38bdf8,color:#ffffff
    style B fill:#203a43,stroke:#38bdf8,color:#ffffff
    style C fill:#203a43,stroke:#f59e0b,color:#ffffff
    style D fill:#203a43,stroke:#f59e0b,color:#ffffff
    style E fill:#2c5364,stroke:#22c55e,color:#ffffff
    style F fill:#14532d,stroke:#22c55e,color:#ffffff
```

> **Design principle:** the AI reports *events, confidence and evidence*; **faculty makes the final call**. No single detection is ever labeled "cheating", which keeps false positives low.

<!-- Add the repo link once public: [View repo →](https://github.com/Fayaz0267/YOUR_REPO_NAME) -->

---

## 🚀 Featured Projects

<p align="center"><i>Click any card to open the repo</i></p>

<p align="center">
  <a href="https://github.com/Fayaz0267/campuseats-frontend"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Fayaz0267&repo=campuseats-frontend&theme=tokyonight&hide_border=true&border_radius=10" width="48%" alt="CampusEats" /></a>
  <a href="https://github.com/Fayaz0267/DataMind"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Fayaz0267&repo=DataMind&theme=tokyonight&hide_border=true&border_radius=10" width="48%" alt="DataMind" /></a>
</p>
<p align="center">
  <a href="https://github.com/Fayaz0267/PayAI"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Fayaz0267&repo=PayAI&theme=tokyonight&hide_border=true&border_radius=10" width="48%" alt="PayAI" /></a>
  <a href="https://github.com/Fayaz0267/Incredible_India"><img src="https://github-readme-stats.vercel.app/api/pin/?username=Fayaz0267&repo=Incredible_India&theme=tokyonight&hide_border=true&border_radius=10" width="48%" alt="Incredible India" /></a>
</p>

| Project | What it does | Stack |
|---|---|---|
| 🍽️ **CampusEats** | Food ordering for college campuses with **real-time order tracking** and **role-based access** for students, vendors and admins | MERN |
| 📊 **DataMind** | AI-powered analytics platform with interactive dashboards and **natural-language queries** over your data | MERN + AI |
| 💳 **PayAI** | Financial transaction and payment utility with smart payment workflows and contextual AI insights | TypeScript |
| 🗺️ **Incredible India** | Tourism and itinerary planning with smart trip planning and location-based recommendations | Interactive web UI |
| 🌐 **[Personal Portfolio](https://fayaz-portfolio-gamma.vercel.app/)** | Responsive portfolio with dark/light theme and Framer Motion animations, built for recruiters and judges | React · Vite · Framer Motion · Vercel |

<details>
<summary><b>➕ More projects</b></summary>

<br/>

- 🕵️ **AI-Based Fake Job Detection System**: ML mini project that flags fake job postings (Flask, TF-IDF, Logistic Regression)
- 🏢 **Community360**: apartment management app with a maintenance module (Flutter, Firebase)

</details>

---

## 🛠️ Tech Stack

<p align="center"><b>🤖 AI / ML</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=py,tensorflow,sklearn,flask&theme=dark" alt="Python, TensorFlow, scikit-learn, Flask" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white" alt="Pandas" />
  <img src="https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white" alt="NumPy" />
  <img src="https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square&logo=google&logoColor=white" alt="MediaPipe" />
</p>

<p align="center"><b>🌐 Full-Stack</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,react,vite,nodejs,express,mongodb&theme=dark&perline=7" alt="TypeScript, JavaScript, React, Vite, Node.js, Express, MongoDB" />
</p>

<p align="center"><b>📱 Mobile</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=flutter,dart,firebase&theme=dark" alt="Flutter, Dart, Firebase" />
</p>

<p align="center"><b>⚙️ Tools & Deployment</b></p>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,vercel,vscode&theme=dark" alt="Git, GitHub, Vercel, VS Code" />
</p>

---

## 💼 Experience

**🏢 Software Engineering Intern** · Embrizon Technologies

<!-- Add the duration and 1-2 bullets on what you built or shipped, e.g. "Built X using Y, which did Z". -->

---

## 🏅 Certifications & Achievements

<p>
  <img src="https://img.shields.io/badge/NASSCOM-GenAI%20Forge%20Hackathon-0A66C2?style=flat-square" alt="NASSCOM GenAI Forge Hackathon" />
  <img src="https://img.shields.io/badge/NPTEL-Cloud%20Computing%20(Elite)-F97316?style=flat-square" alt="NPTEL Cloud Computing Elite" />
  <img src="https://img.shields.io/badge/EY%20x%20Microsoft-AI%20Skills%20Passport-FFE600?style=flat-square&labelColor=2E2E38" alt="EY x Microsoft AI Skills Passport" />
</p>

<details>
<summary><b>More certifications and credential IDs</b></summary>

<br/>

**Credential IDs**
- GenAI Forge Hackathon (NASSCOM FutureSkills Prime): `FSP/2026/2702/272`
- Cloud Computing, Elite (NPTEL): `NPTEL26CS55S956200743`
- Software Engineering Intern (Embrizon Technologies): `ET2025IC1814`

**Other courses and workshops**
- HP LIFE: Strategic Planning in the AI Age
- Masters' Union: Build Your First AI App
- be10X: AI Tools & ChatGPT Workshop

</details>

---

## 📊 GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Fayaz0267&show_icons=true&theme=tokyonight&hide_border=true&include_all_commits=true&count_private=true&border_radius=10" width="48%" alt="GitHub stats" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Fayaz0267&layout=compact&theme=tokyonight&hide_border=true&border_radius=10" width="38%" alt="Top languages" />
</p>


---

## 🤝 Let's Build Something

> [!IMPORTANT]
> I'm actively looking for **AI/ML and software development internships**. If you're working on something interesting, I'd love to hear about it.

<p align="center"><b>Open to:</b> Internships · Open Source · Hackathon Teams · Research Collaborations</p>

<p align="center">
  <a href="mailto:Shaikfayaz0267@gmail.com?subject=Let%27s%20talk%20%F0%9F%91%8B"><img src="https://img.shields.io/badge/%F0%9F%93%A9%20Email%20me-EA4335?style=for-the-badge" alt="Email me" /></a>
  <a href="https://www.linkedin.com/in/shaik-mahammad-fayaz-1009bb338"><img src="https://img.shields.io/badge/Connect%20on-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="Connect on LinkedIn" /></a>
  <a href="https://fayaz-portfolio-gamma.vercel.app/"><img src="https://img.shields.io/badge/See%20my-Portfolio-111827?style=for-the-badge" alt="See my portfolio" /></a>
</p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:2c5364,50:203a43,100:0f2027&height=100&section=footer&text=Thanks%20for%20stopping%20by%20%E2%9C%A8&fontSize=16&fontColor=ffffff&fontAlignY=65" width="100%" alt="Footer" />
</p>
