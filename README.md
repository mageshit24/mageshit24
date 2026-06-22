<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&duration=3000&pause=1000&color=6366F1&center=true&vCenter=true&width=600&lines=Hey%2C+I'm+Magesh+Hariram+K+%F0%9F%91%8B;Full-Stack+Developer;ML+%26+IoT+Engineer;Building+things+that+work." alt="Typing SVG" />

<br/>

<p>
  System Engineer Intern · <strong>EdgeVerve Finacle</strong>, Bengaluru<br/>
  B.Tech Information Technology · <strong>Hindusthan Institute of Technology</strong>, Coimbatore
</p>

<p>
  <a href="https://mageshhariramk.netlify.app" target="_blank">
    <img src="https://img.shields.io/badge/Portfolio-%23000000.svg?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio"/>
  </a>
  <a href="https://linkedin.com/in/magesh-hariram-k-6011132a4" target="_blank">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/>
  </a>
  <a href="mailto:mageshhariramk@gmail.com">
    <img src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/>
  </a>
</p>

<img src="https://komarev.com/ghpvc/?username=mageshit24&style=flat-square&color=6366f1&label=profile+views" alt="Profile views" />

</div>

---

## 🧑‍💻 About me

```ts
const magesh = {
  role      : "Full-Stack Developer & ML Engineer",
  internship: "System Engineer @ EdgeVerve Finacle (Bengaluru)",
  education : "B.Tech IT — Hindusthan Institute of Technology",
  building  : ["full-stack web apps", "ML & IoT systems", "disaster early-warning tools"],
  stack     : ["Angular", "Spring Boot", "Node.js", "Python", "MySQL"],
  openTo    : ["full-time software engineering roles"],
};
```

---

## 🛠️ Tech stack

<div align="center">

**Frontend**

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

**Backend**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=for-the-badge&logo=flask&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

**Database**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Sequelize](https://img.shields.io/badge/Sequelize-52B0E7?style=for-the-badge&logo=sequelize&logoColor=white)

**AI / ML & IoT**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-27338e?style=for-the-badge&logo=OpenCV&logoColor=white)
![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)

**Tools & Deployment**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-0078D4?style=for-the-badge&logo=visual%20studio%20code&logoColor=white)

</div>

---

## 🎓 Major project

<table>
<tr>
<td valign="top">

### 🌩️ A Decentralized IoT & ML Framework for Hyperlocal Cloudburst Prediction
> Final Year Major Project — Disaster Early-Warning System

Traditional weather forecasting misses hyperlocal cloudburst triggers. This system deploys **ESP32 sensor nodes** in the field to monitor soil moisture, rainfall intensity, temperature, and humidity — transmitting over **two independent channels** simultaneously:

- **LoRa 433MHz** → local RX node for offline field alerts (LCD · buzzer · GSM SMS) — works without internet
- **WiFi/UDP** → Flask server running a **Random Forest classifier** → MySQL logging → live auto-refreshing dashboard

The dual-channel design ensures the system keeps alerting locally even when the network is down — critical for disaster-prone, connectivity-poor regions.

`ESP32` `LoRa SX1278` `C++` `Python` `Flask` `Random Forest` `MySQL` `Blynk` `GSM` `scikit-learn`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/mageshit24/A-Decentralized-IoT-and-Machine-Learning-Framework-for-Hyperlocal-Cloudburst-Prediction)

</td>
</tr>
</table>

---

## 🔬 Mini project

<table>
<tr>
<td valign="top">

### 💤 Insomnia Prediction (IoT)
> Third Year Mini Project — Smart Pillow with ML-based Sleep Analysis

Engineered a sensor-embedded smart pillow using ESP32 to continuously monitor pulse, respiration, body temperature, pressure, and sleep posture. Sensor data streams in real time to a Node.js REST API, persisted in MongoDB, and classified by a Random Forest model to predict insomnia risk.

`ESP32` `C++` `Node.js` `MongoDB` `Python` `Random Forest` `REST API`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/mageshit24/Insomnia-Prediction-Using-IoT-Integrated-Smart-Pillow)

</td>
</tr>
</table>

---

## 🚀 Featured projects

<table>
<tr>
<td width="50%" valign="top">

### 🍽️ The Cozy Table
> Full-Stack Restaurant Management System

Architected and deployed a production-grade restaurant platform featuring real-time order state management, reservation flows, menu filtering, JWT-secured role-based access, and Winston structured logging.

Resolved **40+ production-level bugs** across the full stack — including in-memory auth caching to eliminate per-request DB queries, RxJS `catchError` fix to prevent polling stream termination, and `ChangeDetectorRef.detectChanges()` injected across 10+ components to fix Angular rendering failures.

`Angular 21` `Node.js` `Express` `MySQL` `Sequelize` `JWT` `RxJS` `TypeScript`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/mageshit24/the-cozy-table)

</td>
<td width="50%" valign="top">

### 👥 Employee Management System
> Enterprise-Grade HR Platform

Built a layered Java backend (controller → service → repository) exposing a JWT-secured REST API, consumed by a React frontend. Implements department hierarchies, employee CRUD, and role-based access control — mirroring patterns used in production enterprise HR systems.

Demonstrates core **Spring Boot** competencies directly applicable to backend engineering roles: bean lifecycle, JPA/Hibernate ORM, DTO mapping, exception handling, and stateless JWT auth.

`Spring Boot` `Java` `React` `MySQL` `JPA/Hibernate` `JWT` `REST API`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/mageshit24/Employee-Management-System)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🚗 Driver Drowsiness Alert
> Real-Time Computer Vision Safety System

Implemented a real-time eye-aspect-ratio (EAR) algorithm on a live webcam feed using OpenCV to detect sustained eye closure. On drowsiness detection, the system triggers an audio alarm via Pygame and dispatches an email alert with the driver's GPS coordinates using smtplib and GeoPy — sub-second end-to-end response.

`Python` `OpenCV` `smtplib` `Pygame` `GeoPy`

[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/mageshit24/Driver-Drowsiness-Alert)

</td>
<td width="50%" valign="top">

### ✅ ToDoList — MERN Stack
> Deployed Full-Stack Web Application

Built and shipped a full MERN stack to-do application with deadline tracking, overdue detection, and persistent task state. Frontend deployed on **Netlify**, backend on **Render** — live and publicly accessible.

Demonstrates end-to-end ownership: React SPA, Express REST API, MongoDB data layer, CORS configuration, environment-based config, and cloud deployment.

`React` `Node.js` `Express` `MongoDB` `Netlify` `Render`

[![Live Demo](https://img.shields.io/badge/Live_Demo-00C7B7?style=flat&logo=netlify&logoColor=white)](https://github.com/mageshit24/ToDoList)
[![Repo](https://img.shields.io/badge/View_Repo-181717?style=flat&logo=github&logoColor=white)](https://github.com/mageshit24/ToDoList)

</td>
</tr>
</table>

---

## 📊 GitHub stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=mageshit24&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366F1&icon_color=6366F1&text_color=C9D1D9&rank_icon=github" height="165" alt="GitHub stats"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=mageshit24&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=6366F1&text_color=C9D1D9&langs_count=6" height="165" alt="Top Languages"/>

<br/><br/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=mageshit24&theme=tokyonight&hide_border=true&background=0D1117&ring=6366F1&fire=6366F1&currStreakLabel=6366F1" alt="GitHub Streak"/>

</div>

---

## 🔍 Other projects

| Project | Description | Stack |
|---|---|---|
| [Student Attendance Tracker](https://github.com/mageshit24/Student-Attendance-Tracker-with-Alcohol-Detection) | Face-recognition-based attendance system with alcohol detection via sensor integration | Python · OpenCV · ESP32 · MongoDB |
| [Angular ToDoList](https://angulartodolistminiproject.netlify.app/) | Standalone Angular 21 to-do app — live Netlify deploy, no external dependencies | Angular · TypeScript |
| [FlappyBird](https://github.com/mageshit24/FlappyBird) | Fully playable Flappy Bird built in Java Swing — physics, collision detection, live scoring, runs as a standalone `.jar` | Java · Swing/AWT |

---

<div align="center">
  <img src="https://raw.githubusercontent.com/Platane/snk/output/github-contribution-grid-snake-dark.svg" alt="Contribution snake animation"/>
</div>
