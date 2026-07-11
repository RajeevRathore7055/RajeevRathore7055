<svg width="1200" height="320" viewBox="0 0 1200 320" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <linearGradient id="bg" x1="0%" y1="0%" x2="100%" y2="100%">
      <stop offset="0%" stop-color="#050308"/>
      <stop offset="50%" stop-color="#0b0713"/>
      <stop offset="100%" stop-color="#0a0510"/>
    </linearGradient>
    <radialGradient id="glowPurple" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#9d4edd" stop-opacity="0.55"/>
      <stop offset="100%" stop-color="#9d4edd" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowOrange" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff8c42" stop-opacity="0.45"/>
      <stop offset="100%" stop-color="#ff8c42" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="glowRed" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#ff3864" stop-opacity="0.35"/>
      <stop offset="100%" stop-color="#ff3864" stop-opacity="0"/>
    </radialGradient>
    <linearGradient id="textGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#c77dff"/>
      <stop offset="45%" stop-color="#ff8c42"/>
      <stop offset="100%" stop-color="#ff3864"/>
    </linearGradient>
    <linearGradient id="lineGrad" x1="0%" y1="0%" x2="100%" y2="0%">
      <stop offset="0%" stop-color="#9d4edd" stop-opacity="0.9"/>
      <stop offset="100%" stop-color="#ff3864" stop-opacity="0.15"/>
    </linearGradient>
    <filter id="softBlur" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="6"/>
    </filter>
  </defs>

  <rect width="1200" height="320" fill="url(#bg)"/>
  <circle cx="140" cy="80" r="180" fill="url(#glowPurple)"/>
  <circle cx="1060" cy="260" r="200" fill="url(#glowOrange)"/>
  <circle cx="900" cy="60" r="150" fill="url(#glowRed)"/>

  <!-- neural network mesh -->
  <g stroke="url(#lineGrad)" stroke-width="1" opacity="0.55">
    <line x1="60" y1="60" x2="230" y2="120"><animate attributeName="opacity" values="0.2;0.8;0.2" dur="4s" repeatCount="indefinite"/></line>
    <line x1="60" y1="150" x2="230" y2="120"><animate attributeName="opacity" values="0.7;0.15;0.7" dur="3.2s" repeatCount="indefinite"/></line>
    <line x1="60" y1="240" x2="230" y2="180"><animate attributeName="opacity" values="0.3;0.9;0.3" dur="5s" repeatCount="indefinite"/></line>
    <line x1="230" y1="120" x2="400" y2="70"><animate attributeName="opacity" values="0.8;0.2;0.8" dur="3.6s" repeatCount="indefinite"/></line>
    <line x1="230" y1="120" x2="400" y2="160"><animate attributeName="opacity" values="0.2;0.7;0.2" dur="4.4s" repeatCount="indefinite"/></line>
    <line x1="230" y1="180" x2="400" y2="160"><animate attributeName="opacity" values="0.6;0.15;0.6" dur="2.8s" repeatCount="indefinite"/></line>
    <line x1="230" y1="180" x2="400" y2="230"><animate attributeName="opacity" values="0.25;0.85;0.25" dur="3.9s" repeatCount="indefinite"/></line>
    <line x1="400" y1="70" x2="560" y2="120"><animate attributeName="opacity" values="0.7;0.2;0.7" dur="4.1s" repeatCount="indefinite"/></line>
    <line x1="400" y1="160" x2="560" y2="120"><animate attributeName="opacity" values="0.3;0.8;0.3" dur="3.3s" repeatCount="indefinite"/></line>
    <line x1="400" y1="230" x2="560" y2="180"><animate attributeName="opacity" values="0.8;0.25;0.8" dur="4.7s" repeatCount="indefinite"/></line>
  </g>

  <g fill="#c77dff">
    <circle cx="60" cy="60" r="3.5"/>
    <circle cx="60" cy="150" r="3.5"/>
    <circle cx="60" cy="240" r="3.5"/>
    <circle cx="230" cy="120" r="4.5"/>
    <circle cx="230" cy="180" r="4.5"/>
  </g>
  <g fill="#ff8c42">
    <circle cx="400" cy="70" r="4"/>
    <circle cx="400" cy="160" r="4"/>
    <circle cx="400" cy="230" r="4"/>
  </g>
  <g fill="#ff3864">
    <circle cx="560" cy="120" r="4.5"/>
    <circle cx="560" cy="180" r="4.5"/>
  </g>

  <!-- right side floating math / code glyphs -->
  <g font-family="Menlo, Consolas, monospace" fill="#9d4edd" opacity="0.35" font-size="15">
    <text x="720" y="55">∑ P(θ|X)</text>
    <text x="850" y="95">f(x) = Wx + b</text>
    <text x="980" y="45">def forward():</text>
    <text x="760" y="140">∇L</text>
    <text x="900" y="180">async fastapi</text>
    <text x="1020" y="130">λ e⁻ˣ</text>
    <text x="740" y="230">agent.invoke()</text>
    <text x="880" y="265">O(n log n)</text>
    <text x="1010" y="230">AWS · Docker</text>
  </g>

  <!-- headline -->
  <text x="60" y="185" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="46" font-weight="700" fill="url(#textGrad)">
    RAJEEV RATHORE
  </text>
  <text x="61" y="185" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="46" font-weight="700" fill="url(#textGrad)" opacity="0.3" filter="url(#softBlur)">
    RAJEEV RATHORE
  </text>
  <text x="60" y="220" font-family="'Segoe UI', Helvetica, Arial, sans-serif" font-size="16.5" letter-spacing="2.5" fill="#e6d9ff" opacity="0.9">
    AI RESEARCH ENGINEER  ·  MACHINE LEARNING  ·  MATHEMATICS  ·  AGENTIC SYSTEMS
  </text>

  <rect x="60" y="240" width="440" height="1.4" fill="url(#textGrad)" opacity="0.7"/>
</svg>

<div align="center">

<img src="./assets/banner.svg" alt="Rajeev Rathore — AI Research Engineer" width="100%"/>

<br/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=3200&pause=900&color=C77DFF&center=true&vCenter=true&width=650&lines=Agentic+AI+Intern+%40+Innomatics+Research+Labs;Building+AI+Agents+with+LangChain+%2B+LangGraph;Machine+Learning+%7C+Mathematics+%7C+FastAPI;Turning+Equations+into+Working+Systems" alt="Typing SVG" />
</a>

<br/>

[![LinkedIn](https://img.shields.io/badge/LinkedIn-rajeev--rathore01-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/rajeev-rathore01)
[![Email](https://img.shields.io/badge/Email-cs23rajeev%40rbmi.in-FF3864?style=flat-square&logo=gmail&logoColor=white)](mailto:cs23rajeev@rbmi.in)
[![Profile Views](https://komarev.com/ghpvc/?username=RajeevRathore7055&style=flat-square&color=9d4edd&label=Profile+Views)](https://github.com/RajeevRathore7055)

</div>

<br/>

## Introduction

I'm an Agentic AI Intern at **Innomatics Research Labs**, currently building agent-based
AI systems with LangChain and LangGraph, backed by FastAPI services and AWS infrastructure.
My work sits at the intersection of **mathematics and machine learning** — I like problems
that reduce cleanly to an objective function, and systems that reduce cleanly to an API
contract. Final-year B.Tech CSE student at RBMI Group of Institutions (AKTU), building
toward a career designing and shipping real AI agent architectures.

<br/>

## Short Bio

- 🎓 Final-year B.Tech CSE student (2023–2027) at RBMI Group of Institutions, AKTU Lucknow
- 🤖 Agentic AI Intern at Innomatics Research Labs — LangChain, LangGraph, FastAPI, AWS
- 📐 Strong foundation in Linear Algebra, Calculus, and core ML algorithms
- 🛠️ Shipped ML platforms, deployed AI agents, and led a 50+ student robotics workshop
- ♟️ Approaches problems the way I approach chess — a few moves ahead

<br/>

## Current Focus

```
Currently Learning     → Advanced LangGraph orchestration, RAG pipelines, Transformer internals
Currently Building     → AI Interview Agent (voice), Coding Notes RAG Agent, LinkedIn Post Agent
Research Interests     → Agentic architectures, applied ML, mathematical foundations of learning
Current Tech Stack     → Python · FastAPI · LangChain · LangGraph · Hugging Face · AWS · Docker
```

<br/>

## About Me

I specialize in programming and software development with a particular pull toward
**data analytics and machine learning**. My foundation in mathematics — linear algebra
and calculus — isn't academic box-ticking; it's the lens I use to actually understand
*why* a model works, not just how to call `.fit()`.

Day to day, that shows up as: building AI agents at Innomatics Research Labs, deploying
ML models behind REST APIs, and picking apart algorithms (logistic regression, SVMs,
decision trees, CNNs) until the math behind them is boring and obvious. I've run a
Robotics & Automation workshop for 50+ students, worked across the MERN stack, and
I'm most productive when a problem has both a clean mathematical structure and a real
system to ship it in.

Outside of code: chess, basketball, cricket, and competitive e-sports — different boards,
same instinct for reading a few moves ahead.

<br/>

## Tech Stack

<details open>
<summary><b>Programming Languages</b></summary><br/>

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Python](https://img.shields.io/badge/Python-9D4EDD?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-FF8C42?style=for-the-badge&logo=openjdk&logoColor=white)

</details>

<details open>
<summary><b>Frontend & Backend</b></summary><br/>

![HTML5](https://img.shields.io/badge/HTML5-FF3864?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-9D4EDD?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-FF8C42?style=for-the-badge&logo=javascript&logoColor=black)
![FastAPI](https://img.shields.io/badge/FastAPI-05998b?style=for-the-badge&logo=fastapi&logoColor=white)
![React](https://img.shields.io/badge/React-15161a?style=for-the-badge&logo=react&logoColor=61DAFB)

</details>

<details open>
<summary><b>Machine Learning & AI</b></summary><br/>

![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-9D4EDD?style=for-the-badge&logo=scikitlearn&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF3864?style=for-the-badge&logo=tensorflow&logoColor=white)
![Hugging Face](https://img.shields.io/badge/Hugging%20Face-FF8C42?style=for-the-badge&logo=huggingface&logoColor=black)
![LangChain](https://img.shields.io/badge/LangChain-1a1a2e?style=for-the-badge&logo=langchain&logoColor=C77DFF)
![OpenCV](https://img.shields.io/badge/OpenCV-9D4EDD?style=for-the-badge&logo=opencv&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-FF3864?style=for-the-badge&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-FF8C42?style=for-the-badge&logo=pandas&logoColor=black)

`LangGraph` · `RAG` · `Transformers` · `Linear/Logistic Regression` · `SVM` · `Decision Tree` · `KNN` · `CNN`

</details>

<details open>
<summary><b>Mathematics</b></summary><br/>

`Linear Algebra` · `Calculus` · `Statistical Learning` · `Probability Foundations for ML`

</details>

<details open>
<summary><b>Database, Cloud & Tools</b></summary><br/>

![MySQL](https://img.shields.io/badge/MySQL-9D4EDD?style=for-the-badge&logo=mysql&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF8C42?style=for-the-badge&logo=amazonaws&logoColor=black)
![Docker](https://img.shields.io/badge/Docker-FF3864?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-9D4EDD?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-15161a?style=for-the-badge&logo=github&logoColor=white)
![VSCode](https://img.shields.io/badge/VS%20Code-FF8C42?style=for-the-badge&logo=visualstudiocode&logoColor=black)

`Selenium` · `Matplotlib` · `Codeium`

</details>

<details open>
<summary><b>Soft Skills</b></summary><br/>

`Communication` · `Leadership` · `Teamwork` · `Problem Solving` · `Critical Thinking` · `Time Management`

</details>

<br/>

## Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 🧠 Dementia-Risk Assessment Platform
ML-powered health risk classification system.
- **Stack:** React · Python · Logistic Regression
- **Achievement:** ~87% classification accuracy
- **Impact:** Role-based access (Admin / Doctor / Patient) for real clinical-style workflows

</td>
<td width="50%" valign="top">

### 🔐 SecurePass — Password Analyzer
ML-driven password strength & breach detection tool.
- **Stack:** FastAPI · React · MySQL · Scikit-learn · HIBP API · JWT
- **Achievement:** Logistic Regression strength model + live breach lookup
- **Impact:** Super Admin panel with breach IP tracking

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 📄 Resume Matcher AI
AI-powered resume-to-job matching platform.
- **Stack:** Hugging Face models · Prompt Engineering · FastAPI · MySQL · React
- **Impact:** Automated, model-driven candidate–role fit scoring

</td>
<td width="50%" valign="top">

### 🩺 Medical AI Agent
Conversational AI agent for medical receptionist workflows.
- **Stack:** LangChain · LangGraph · Hugging Face · FastAPI · Streamlit
- **Impact:** Agent-driven intake flow, no paid API keys required

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🌦️ Weather AI Agent
Containerized AI agent for weather queries.
- **Stack:** LangChain/LangGraph · Docker
- **Impact:** Fully containerized deployment for portability

</td>
<td width="50%" valign="top">

### ✉️ AI Email Generator
LLM-powered contextual email drafting tool.
- **Stack:** AI / LLM prompting
- **Impact:** Automated professional email generation

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💼 LinkedIn Post Generator Agent
Deployed AI agent for LinkedIn content generation.
- **Stack:** Groq (Llama 3.3 70B) · FastAPI · Docker · Render
- **Impact:** Live-deployed, production agent from workshop to production

</td>
<td width="50%" valign="top">

### ⚙️ FastAPI ML Model Deployment
REST API serving a machine learning model.
- **Stack:** FastAPI
- **Impact:** Real-time prediction endpoint, deployment-ready serving pattern

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚆 Railway Ticket Booking System
Ticket reservation simulation.
- **Stack:** HTML · CSS · JavaScript · LocalStorage
- **Impact:** Full booking flow without a backend, pure client-side state

</td>
<td width="50%" valign="top">

### 📊 Machine Learning Mini Projects
Focused implementations of core ML algorithms.
- **Stack:** Linear/Logistic Regression · Decision Tree · KNN · CNN · Perceptron · Neural Networks
- **Impact:** Hands-on mastery of algorithm fundamentals from first principles

</td>
</tr>
</table>

<br/>

## GitHub Analytics

<div align="center">

<img height="165" src="https://github-readme-stats.vercel.app/api?username=RajeevRathore7055&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D0D0D&title_color=C77DFF&icon_color=FF8C42&text_color=e6d9ff" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=RajeevRathore7055&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D0D0D&title_color=C77DFF&text_color=e6d9ff" />

<br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=RajeevRathore7055&theme=tokyonight&hide_border=true&background=0D0D0D&ring=C77DFF&fire=FF3864&currStreakLabel=FF8C42" />

<br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=RajeevRathore7055&theme=react-dark&hide_border=true&bg_color=0D0D0D&color=C77DFF&line=FF8C42&point=FF3864" width="100%"/>

<br/><br/>

<img src="https://github-profile-trophy.vercel.app/?username=RajeevRathore7055&theme=darkhub&no-frame=true&margin-w=8&row=1" />

</div>

<br/>

<div align="center">

### Contribution Snake

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/RajeevRathore7055/RajeevRathore7055/output/assets/snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/RajeevRathore7055/RajeevRathore7055/output/assets/snake.svg" />
  <img alt="contribution snake animation" src="https://raw.githubusercontent.com/RajeevRathore7055/RajeevRathore7055/output/assets/snake.svg" width="100%"/>
</picture>

</div>

<br/>

## Achievements

- Workshop Instructor — 5-Day Bootcamp, RBMI Group of Institutions
- Conducted Arduino & IoT sessions for 50+ students, introducing programming and Python basics
- Volunteered in technical and cultural events, coordinating smooth execution and participation

<br/>

## Experience

**Agentic AI Intern** · Innomatics Research Labs *(Feb 2026 – Present · Remote)*
Building and deploying agent-based AI applications with Python, FastAPI, LangChain, and
LangGraph; applying AWS for cloud-based AI solutions.

**Co-Organizer & Technical Facilitator — Robotics & Automation Workshop** · RBMI Group of
Institutions *(May 2025)*
Facilitated a hands-on Robotics & Automation workshop for 50+ students (Classes 9–12) with
a 6-member team, covering electronics, sensors, and automation tools.

**MERN Stack Intern**
Full-stack web development using MongoDB/MySQL, Express.js, React.js, and Node.js.

<br/>

## Certifications

| Certification | Provider |
|---|---|
| Machine Learning Foundations: Linear Algebra | Wolfram Research / LinkedIn Learning |
| Machine Learning Foundations: Calculus | LinkedIn Learning |
| Learning Everyday Math | LinkedIn Learning |
| Foundational Math for Machine Learning | LinkedIn Learning |
| Complete Machine Learning & Data Science Skill Up | GeeksforGeeks |
| Statistical Learning | LinkedIn Learning |
| MySQL Data Analysis | LinkedIn Learning |
| Selenium Fundamentals | LinkedIn Learning |

<br/>

## A Thought

> *"Every model is just a hypothesis wearing a gradient — the math doesn't lie,*
> *it just waits for you to ask the right question."*

<br/>

## Contact

<div align="center">

Open to conversations on agentic AI, machine learning, and anything that starts
with a well-posed problem.

[![LinkedIn](https://img.shields.io/badge/Connect-LinkedIn-9D4EDD?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/rajeev-rathore01)
[![Email](https://img.shields.io/badge/Reach%20Out-Email-FF3864?style=for-the-badge&logo=gmail&logoColor=white)](mailto:cs23rajeev@rbmi.in)
[![GitHub](https://img.shields.io/badge/Follow-GitHub-FF8C42?style=for-the-badge&logo=github&logoColor=black)](https://github.com/RajeevRathore7055)

</div>

<br/>

<div align="center">
<sub>Built with Python, mathematics, and a lot of tab-switching between docs.</sub>
</div>


