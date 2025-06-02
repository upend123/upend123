<div align="center">

  # 👋 Hey there, I'm Upendra Yadav

- 🎓 I'm currently pursuing **B.Tech in Electronics & Communication Engineering**
- 💼 I love building modern Android apps using **Kotlin, Jetpack Compose, MVVM, Room, and Retrofit**
- 🤖 I also build smart projects integrating **IoT (Arduino/ESP32)** with Android
- 🛠️ Always learning about **clean architecture, coroutines, data store, APIs** and more
- 🌟 I believe in consistency, clean code, and continuous improvement

  ![Profile Views](https://komarev.com/ghpvc/?username=upendrayadav&color=blue&style=flat-square)

</div>

---

## 🛠️ My Tech Stack

### 🧑‍💻 Core Languages
![Java](https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=java&logoColor=white)
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=for-the-badge&logo=kotlin&logoColor=white)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![XML](https://img.shields.io/badge/XML-E44D26?style=for-the-badge&logo=xml&logoColor=white)
<!--![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
-->

---

### 📱 Android Development
![Android Studio](https://img.shields.io/badge/Android%20Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack%20Compose-4285F4?style=for-the-badge&logo=jetpackcompose&logoColor=white)
![Room](https://img.shields.io/badge/Room-007396?style=for-the-badge&logo=android&logoColor=white)
![Retrofit](https://img.shields.io/badge/Retrofit-4CAF50?style=for-the-badge&logo=retrofit&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
![DataStore](https://img.shields.io/badge/DataStore-FF6F00?style=for-the-badge&logo=android&logoColor=white)

---

### ☁️ Backend & Cloud
![REST API](https://img.shields.io/badge/REST%20API-0052CC?style=for-the-badge&logo=postman&logoColor=white)
![Firebase Firestore](https://img.shields.io/badge/Firebase%20Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)
<!-- ![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white)
![Cloudinary](https://img.shields.io/badge/Cloudinary-3448C5?style=for-the-badge&logo=cloudinary&logoColor=white)
-->
---

### 🔌 IoT & Embedded Systems
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-000000?style=for-the-badge&logo=espressif&logoColor=white)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![RFID](https://img.shields.io/badge/RFID-1E88E5?style=for-the-badge&logo=rss&logoColor=white)

---

### 👨‍💻 Competitive Coding
![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)
![HackerRank](https://img.shields.io/badge/HackerRank-2EC866?style=for-the-badge&logo=hackerrank&logoColor=white)

---

### 🧰 Tools & Workflow
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![VS Code](https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)

---

## 🚀 Projects

### [🔐 Smart IoT Door Lock](https://github.com/upendrayadav/smart-lock)  
> A complete smart security solution combining hardware and software for seamless access control:  
> - **✨ Key Features:**  
>   - **🔐 Real-time Lock/Unlock:** Use RFID tags to authenticate and control a solenoid lock.  
>   - **🌐 Remote Monitoring:** ESP32 serves a JSON API polled by the Android app every 3–5 seconds.  
>   - **🔔 Notifications:** Firebase Cloud Messaging alerts you instantly when the state changes.  
>   - **🗄️ Access Logs:** Stored locally in Room DB, viewable via the app.  
> - **🛠️ Hardware:**  
>   - **ESP32:** Wi-Fi connectivity and web server hosting.  
>   - **RFID Reader (13.56 MHz):** Scans tags/cards.  
>   - **Solenoid Lock + Power Supply:** Controlled via ESP32 GPIO.  
>   - **LCD Display:** Shows “Locked” or “Unlocked” status.  
> - **💻 Software:**  
>   - **ESP32 Web API:** Lightweight HTTP endpoint returns JSON status.  
>   - **Android App (Jetpack Compose):**  
>     - **🔄 Polling Service:** Kotlin Coroutines & Flow fetch updates.  
>     - **📊 UI Screens:** Display current status, history, and manual override.  

---

### [📊 Upendra’s Quiz App](https://github.com/upendrayadav/quiz-app)  
> An interactive quiz platform built for Android, focusing on smooth UX and robust data handling:  
> - **🏗️ Architecture:** MVVM + Repository Pattern ensures separation of concerns.  
> - **📦 Data Persistence:**  
>   - **Proto DataStore:** Saves user profile (name, email) and preferences.  
>   - **Room Database:** Stores quizzes, questions, and leaderboard scores.  
> - **🔗 API Integration:**  
>   - **Retrofit + Coroutines/Flow:** Fetch question sets from a REST endpoint asynchronously.  
> - **🎨 UI/UX (Jetpack Compose):**  
>   - **⚡ Shimmer Loading:** Placeholder effect while data loads.  
>   - **❓ Quiz Screen:** Timed multiple-choice questions with animated progress.  
>   - **🏆 Score Screen:** Shows final score; “Save” button enabled once per attempt.  
>   - **🥇 Leaderboard Screen:** Displays top scores sorted by score and date.  
>   - **🎉 Lottie Animations:** Celebrate correct answers and high scores.  
>   - **📋 List Interactions:**  
>     - **Tap:** Show question details in a dialog.  
>     - **Long-press:** Prompt deletion of that quiz attempt.  

---

### [📇 Contact Manager App](https://github.com/upendrayadav/contact-app)  
> A polished contact management application using modern Android components and best practices:  
> - **🏛️ Architecture:** MVVM + Clean Architecture for maintainable code.  
> - **🗄️ Data Layer:**  
>   - **Room Database:** Stores contacts (name, phone, email, profile photo).  
>   - **Kotlin Flow:** Streams live updates to the UI for immediate feedback.  
> - **🚀 Features:**  
>   - **🖼️ Image Picker:** Select or capture profile photos with runtime permissions.  
>   - **➕➖ CRUD Operations:** Add, edit, delete, and list contacts seamlessly.  
>   - **🔍 Search & Sort:**  
>     - **🔎 Real-time Search:** Filter contacts by name as you type.  
>     - **⬆️ Sort:** Arrange contacts alphabetically or by date added.  
>   - **📞 Direct Calling:** One-tap dial via Intent.  
>   - **🎨 Material Design UI:** Responsive Compose layout supporting dark/light themes.  

> 🚧 More exciting Android + IoT projects are on the way…

---

## 🏆 Achievements & Recognition

- 🏅 Selected for **SRIJAN RGPV Project Expo 2025** – Smart IoT Door Lock  
- 🥈 Top Projects at JUGAD Creation @ JIT Borawan  
- 🎖️ **GDSC Contributor** – Led Jetpack Compose & IoT Workshops  

---

## 📚 Currently Learning

- ✅ Jetpack Compose Advanced: Navigation, State Management, Animations  
- ✅ Kotlin Coroutines & Flow for smooth async operations  
- ✅ Clean Architecture (MVVM + Repository Pattern)  
- ✅ Synchronizing REST APIs with Room Database  
- ✅ IoT + Embedded Integration: MQTT, AWS IoT, Edge Computing  
- ✅ Data Structures & Algorithms (Interview Prep)  

---
<!--
##📊 Contribution Graph
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=upend123&bg_color=0D1117&color=00E7FF&line=00B2FF&point=ffffff&area=true&hide_border=true" width="100%" alt="Upendra's Contribution Graph" />
</p> 
--> 
## 📊 GitHub Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=upend123&theme=github-compact" alt="GitHub Contribution Graph"/>
</p>
---
## 🔗 Let's Connect!

- 📧 Email: [upendrayadav10@gmail.com](mailto:upendrayadavofficial10@gmail.com)  
- 💼 LinkedIn: [linkedin.com/in/upendra-yadav](https://www.linkedin.com/in/upendra-yadav-a560322a4?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app)  
- 🐙 GitHub: [github.com/upend123](https://github.com/upend123)

---

## 💡 Fun Quote

<p align="center">
  <img src="https://quotes-github-readme.vercel.app/api?type=horizontal&theme=tokyonight" alt="Motivational Quote"/>
</p>

---

<p align="center"><b>✨ "Build it like it matters, because one day, it just might."</b></p>
