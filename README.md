# 🚀 Dr.exnon: Journey Through Embedded Systems & Beyond 🚀

---

## 👨‍💻 About Me
<p align="center">
  <img src="assets/my_logo.png" alt="Dr.exnon Logo" width="200"/>
</p>
Hello there! I'm **Dr.exnon**, an **Embedded Developer** with a passion for diving deep into the intricacies of hardware and software. My expertise lies in crafting robust and efficient solutions for embedded systems, ranging from low-level microcontroller programming to building complex monitoring tools and exploring system internals.

This GitHub repository is a showcase of my personal projects, experiments, and contributions, reflecting my journey and continuous learning in the vast world of technology. Here, you'll find a blend of embedded development, system analysis, web tools, mobile applications, and more!

---

## 🛠️ My Skillset & Proficiency

As an Embedded Developer, my core strengths revolve around bringing digital ideas to life on physical hardware. However, my curiosity extends beyond, leading me to explore various facets of software development, including mobile application development.

Below is an overview of my primary skills and their approximate proficiency levels, based on my project experience:

| Skill Category        | Key Technologies/Tools                                | Proficiency |
| :-------------------- | :---------------------------------------------------- | :---------- |
| **Embedded C/C++** | Microcontrollers (ESP32, STM32), FreeRTOS, Peripherals, Drivers | `█████████░` 90% |
| **Mobile Development** | **Flutter, Dart, Java, Kotlin (Android)** | `████████░░` 80% |
| **Windows Internals** | Win32 API, Process/Thread/Module Analysis, Low-level System Interaction | `████████░░` 80% |
| **Python Development**| Flask, SQLAlchemy, Data Processing, Scripting         | `███████░░░` 70% |
| **Web Technologies** | HTML5, CSS3, JavaScript (ES6+), Chart.js, UI/UX Concepts | `███████░░░` 70% |
| **Version Control** | Git, GitHub Workflows                                   | `████████░░` 80% |
| **Networking (IoT)** | Wi-Fi, HTTP, WebSockets, RESTful APIs                 | `███████░░░` 70% |
| **Database** | SQLite, Basic SQL                                     | `██████░░░░` 60% |
| **Debugging & Tools** | Logic Analyzers, Debuggers (GDB), Serial Monitors, VS Code | `████████░░` 80% |

---

## 📂 Featured Projects

Here are some of the key projects residing in this repository that demonstrate my capabilities:

### 1. **[Distributed Embedded Health Monitor (DEHM)](https://github.com/F0G3J3/Distributed-Embedded-Health-Monitor)**
**(C++, Python, HTML, CSS, JavaScript, SQLite)**

A sophisticated, real-time monitoring system for **ESP32** devices. This project showcases a full-stack approach:
* **ESP32 Firmware:** Collects detailed metrics like **CPU usage**, **Heap memory**, **Task status (FreeRTOS)**, and **Stack High Water Mark**. It securely sends this data via **HTTP POST** requests.
* **Python Backend (Flask + SQLAlchemy):** Receives data from multiple ESP32 devices, stores it persistently in a **SQLite database**, and provides a RESTful API for the frontend.
* **Web Frontend (HTML/CSS/JS with Chart.js):** A modern, responsive dashboard that fetches live and historical data from the backend, displaying it through dynamic charts and detailed tables.
* **Key Features:** Real-time data visualization, historical data logging, multi-device support readiness, and **OTA (Over-The-Air) firmware updates** for the ESP32.

### 2. **[WinProcessView: Windows Internals Analyzer](https://github.com/F0G3J3/WinProcessView)**
**(C Language, Win32 API)**

A powerful command-line utility for deeply inspecting **Windows operating system internals**. This project highlights my proficiency in low-level system programming:
* **Functionality:** Lists all running processes, retrieves their detailed information (PID, executable path), enumerates loaded modules (DLLs), and displays active threads for any selected process.
* **Techniques:** Leverages core **Win32 API** calls (`CreateToolhelp32Snapshot`, `Process32First`, `Module32First`, `Thread32First`, `GetModuleFileNameEx`) for direct interaction with the Windows kernel.
* **Utility:** An invaluable tool for system diagnostics, security research, and understanding the execution flow within Windows.

### 3. **[DorkCraft: Advanced Dork Builder](https://github.com/F0G3J3/DorkCraft)**
**(HTML, CSS, JavaScript)**

A sleek and intuitive client-side web tool designed to simplify the creation of advanced search engine dorks.
* **Purpose:** Helps users (especially security researchers and OSINT enthusiasts) craft precise search queries for Google, Bing, DuckDuckGo, and Yandex.
* **User Experience:** Features a modern, responsive UI/UX with dynamic input fields for various search operators (`site:`, `inurl:`, `filetype:`, `intitle:`, `intext:`, etc.).
* **Live Preview:** Provides instant, real-time feedback of the generated dork, with one-click copy and direct search functionalities.

---

## 🤝 Let's Connect!

I'm always open to discussing new ideas, collaborating on interesting projects, or sharing insights into embedded systems and software development.

* Drop me an email: **FOG3J3@GMAIL.COM**
* Connect on Telegram: **@FOG3J3**

---

## 📜 License

All projects within this repository are open source and typically licensed under the **MIT License**, unless otherwise specified within their respective project directories. Please refer to each project's `LICENSE` file for full details.

---

Made with ❤️ by **Dr.exnon**
