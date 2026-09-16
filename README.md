<div align="center">

  <!-- Enhanced ECE Neural Circuit Banner -->
  <svg width="100%" height="300" viewBox="0 0 800 300" xmlns="http://www.w3.org/2000/svg" style="background: linear-gradient(135deg, #0f3460 0%, #16213e 100%); border-radius: 10px;">
    <defs>
      <linearGradient id="grad1" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#00d4ff;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#0099ff;stop-opacity:1" />
      </linearGradient>
      <linearGradient id="grad2" x1="0%" y1="0%" x2="100%" y2="100%">
        <stop offset="0%" style="stop-color:#00ff88;stop-opacity:1" />
        <stop offset="100%" style="stop-color:#00cc66;stop-opacity:1" />
      </linearGradient>
      <style>
        @keyframes pulse {
          0%, 100% { opacity: 0.3; }
          50% { opacity: 1; }
        }
        @keyframes glow {
          0%, 100% { filter: drop-shadow(0 0 4px rgba(0, 255, 136, 0.4)); }
          50% { filter: drop-shadow(0 0 12px rgba(0, 255, 136, 0.8)); }
        }
        .pulse-node { animation: pulse 2s infinite; }
        .glow-text { animation: glow 2.5s infinite; }
        .text-main { font-size: 52px; font-weight: bold; font-family: 'Courier New', monospace; letter-spacing: 2px; }
        .text-sub { font-size: 16px; font-family: 'Courier New', monospace; }
        .circuit-line { stroke-dasharray: 5,5; }
      </style>
    </defs>
    
    <!-- Grid Background (Subtle) -->
    <g opacity="0.08" stroke="#00d4ff" stroke-width="0.5">
      <line x1="50" y1="0" x2="50" y2="300" />
      <line x1="100" y1="0" x2="100" y2="300" />
      <line x1="150" y1="0" x2="150" y2="300" />
      <line x1="200" y1="0" x2="200" y2="300" />
      <line x1="250" y1="0" x2="250" y2="300" />
      <line x1="300" y1="0" x2="300" y2="300" />
      <line x1="350" y1="0" x2="350" y2="300" />
      <line x1="400" y1="0" x2="400" y2="300" />
      <line x1="450" y1="0" x2="450" y2="300" />
      <line x1="500" y1="0" x2="500" y2="300" />
      <line x1="550" y1="0" x2="550" y2="300" />
      <line x1="600" y1="0" x2="600" y2="300" />
      <line x1="650" y1="0" x2="650" y2="300" />
      <line x1="700" y1="0" x2="700" y2="300" />
      <line x1="750" y1="0" x2="750" y2="300" />
      
      <line x1="0" y1="50" x2="800" y2="50" />
      <line x1="0" y1="100" x2="800" y2="100" />
      <line x1="0" y1="150" x2="800" y2="150" />
      <line x1="0" y1="200" x2="800" y2="200" />
      <line x1="0" y1="250" x2="800" y2="250" />
    </g>
    
    <!-- Left Neural Network Input Layer -->
    <circle cx="80" cy="70" r="5" fill="url(#grad1)" class="pulse-node" />
    <circle cx="80" cy="140" r="5" fill="url(#grad1)" class="pulse-node" />
    <circle cx="80" cy="210" r="5" fill="url(#grad1)" class="pulse-node" />
    
    <!-- Hidden Layers -->
    <circle cx="200" cy="60" r="5" fill="url(#grad2)" class="pulse-node" />
    <circle cx="200" cy="120" r="5" fill="url(#grad2)" class="pulse-node" />
    <circle cx="200" cy="180" r="5" fill="url(#grad2)" class="pulse-node" />
    <circle cx="200" cy="240" r="5" fill="url(#grad2)" class="pulse-node" />
    
    <!-- Processing Layer -->
    <circle cx="350" cy="90" r="5" fill="url(#grad1)" class="pulse-node" />
    <circle cx="350" cy="180" r="5" fill="url(#grad1)" class="pulse-node" />
    <circle cx="350" cy="240" r="5" fill="url(#grad1)" class="pulse-node" />
    
    <!-- Output Layer (Right) -->
    <circle cx="500" cy="100" r="5" fill="url(#grad2)" class="pulse-node" />
    <circle cx="500" cy="200" r="5" fill="url(#grad2)" class="pulse-node" />
    
    <!-- Connecting Lines with Signal Flow -->
    <g stroke-width="1.5" opacity="0.4">
      <line x1="80" y1="70" x2="200" y2="60" stroke="url(#grad1)" class="circuit-line" />
      <line x1="80" y1="70" x2="200" y2="120" stroke="url(#grad1)" class="circuit-line" />
      <line x1="80" y1="140" x2="200" y2="180" stroke="url(#grad1)" class="circuit-line" />
      <line x1="80" y1="210" x2="200" y2="240" stroke="url(#grad1)" class="circuit-line" />
      
      <line x1="200" y1="60" x2="350" y2="90" stroke="url(#grad2)" />
      <line x1="200" y1="120" x2="350" y2="90" stroke="url(#grad2)" />
      <line x1="200" y1="180" x2="350" y2="180" stroke="url(#grad2)" />
      <line x1="200" y1="240" x2="350" y2="240" stroke="url(#grad2)" />
      
      <line x1="350" y1="90" x2="500" y2="100" stroke="url(#grad1)" />
      <line x1="350" y1="180" x2="500" y2="100" stroke="url(#grad1)" />
      <line x1="350" y1="240" x2="500" y2="200" stroke="url(#grad1)" />
    </g>
    
    <!-- Main Title -->
    <text x="630" y="130" text-anchor="start" class="text-main glow-text" fill="url(#grad1)">
      Rudranil
    </text>
    <text x="630" y="180" text-anchor="start" class="text-main glow-text" fill="url(#grad2)">
      Mukherjee
    </text>
    
    <!-- Subtitle -->
    <text x="630" y="220" text-anchor="start" class="text-sub" fill="#00d4ff">
      ⚡ ECE | VLSI | Embedded | AI
    </text>
    <text x="630" y="245" text-anchor="start" class="text-sub" fill="#00ff88">
      &gt;_ Hardware • Software • Innovation
    </text>
  </svg>

  <br />

  <!-- Badges Section -->
  <div>
    <img src="https://img.shields.io/badge/ECE%20Undergrad-IEM%20Kolkata-0A66C2?style=for-the-badge&logo=graduation-cap&logoColor=white" />
    <img src="https://img.shields.io/badge/VLSI%20Design-Learning-8A2BE2?style=for-the-badge" />
    <img src="https://img.shields.io/badge/Embedded%20Systems-Enthusiast-FF6B6B?style=for-the-badge" />
    <img src="https://img.shields.io/badge/AI%2FML-Explorer-00D4FF?style=for-the-badge" />
  </div>

  <br />

  <!-- Social Links -->
  <p>
    <a href="https://www.linkedin.com/in/rudranilmukherjee/">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" />
    </a>
    <a href="mailto:rudranilmukherjeeclassviiid@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" />
    </a>
    <a href="https://github.com/rudranilmukherjee1">
      <img src="https://img.shields.io/badge/GitHub-Profile-181717?style=for-the-badge&logo=github&logoColor=white" />
    </a>
  </p>

</div>

---

## 👨‍💻 About Me

🎓 **B.Tech Electronics & Communication Engineering** at IEM Kolkata

🔬 Passionate about **VLSI Design**, **Semiconductor Technology**, and **Digital Design**

⚡ Exploring **Embedded Systems**, **IoT**, and **Hardware-Software Integration**

🤖 Diving deep into **AI/ML for Edge Devices** and **TinyML applications**

💻 Building expertise in **C++, Python, Verilog, and FPGA Design**

🚀 Converting engineering concepts into **practical, working solutions**

🎯 Vision: Becoming a proficient **ECE engineer** with **industry-ready skills** in both hardware and software domains

---

## 🛠️ Skills & Technologies

### 💻 Programming Languages

<p align="left">
  <img src="https://skillicons.dev/icons?i=c,cpp,python,java,html,css,js" />
</p>

| Language | Proficiency | Use Case |
|----------|------------|----------|
| **C/C++** | 🟢 Intermediate | System Programming, Competitive Coding |
| **Python** | 🟢 Intermediate | Data Science, Automation, AI/ML |
| **Java** | 🟡 Learning | OOP Concepts |
| **JavaScript** | 🟡 Learning | Web Development |
| **HTML5/CSS3** | 🟡 Learning | Frontend Development |

### 🔬 VLSI & Digital Design

<p align="left">
  <img src="https://img.shields.io/badge/Verilog-HDL%20-000000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/RTL-Design-8B0000?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Digital%20Design-Logic%20Circuits-6A5ACD?style=for-the-badge" />
</p>

**Core Areas:**
- ✅ Digital Logic Design & Boolean Algebra
- ✅ Verilog HDL & RTL Coding
- ✅ Sequential & Combinational Circuits
- ✅ Computer Architecture Basics
- ✅ FPGA Concepts & Implementation
- ✅ Semiconductor Technology
- ✅ VLSI Design Flow & EDA Tools

### ⚡ Embedded Systems & IoT

<p align="left">
  <img src="https://skillicons.dev/icons?i=arduino,raspberrypi" />
</p>

**Technologies & Tools:**
- 🔧 **Microcontrollers**: ESP32, Arduino, STM32
- 📡 **Protocols**: UART, SPI, I2C, CAN
- 🌐 **IoT Platforms**: Arduino IoT Cloud, Blynk
- 📊 **Sensors**: Temperature, Humidity, Motion, Ultrasonic
- 🛠️ **Tools**: Arduino IDE, PlatformIO, Proteus Simulation

### 🤖 AI & Machine Learning

<p align="left">
  <img src="https://skillicons.dev/icons?i=python,pytorch,tensorflow,opencv,matlab" />
</p>

**Focus Areas:**
- 🧠 **TinyML** & Edge AI
- 🎯 **Machine Learning**: Supervised & Unsupervised Learning
- 👁️ **Computer Vision**: Image Processing with OpenCV
- 📊 **Data Analysis**: NumPy, Pandas, Matplotlib
- 🔍 **Libraries**: TensorFlow, PyTorch, Scikit-learn
- 🤖 **Hardware-Aware AI**: Neural Network Optimization for Embedded Devices

### 🧪 Hardware & Simulation

<p align="left">
  <img src="https://skillicons.dev/icons?i=matlab" />
</p>

**Tools & Platforms:**
- 🔧 **MATLAB/Simulink**: Signal Processing, System Modeling
- 🎯 **Proteus**: Circuit Simulation & PCB Design
- 📐 **LTspice**: Analog Circuit Analysis
- 🖥️ **FPGA Tools**: Xilinx ISE, Vivado
- 🔌 **Hardware Debugging**: Logic Analyzers, Oscilloscopes

### 🗄️ Databases & Backend

<p align="left">
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

`MySQL` • `SQL` • `DBMS` • `RDBMS Concepts` • `Database Optimization`

### 🧰 Development Tools & Platforms

<p align="left">
  <img src="https://skillicons.dev/icons?i=git,github,vscode,linux,docker" />
</p>

| Tool | Purpose |
|------|---------|
| **Git/GitHub** | Version Control & Collaboration |
| **VS Code** | Code Editor & Debugging |
| **Linux** | OS & Command Line |
| **Docker** | Containerization (Learning) |

---

## 📚 Learning Roadmap

```
┌─────────────────────────────────────────────────────────┐
│  ECE Engineering Excellence Journey                      │
├─────────────────────────────────────────────────────────┤
│                                                          │
│  ✅ Digital Logic Design              [PROGRESSING]     │
│  ✅ C/C++ Programming                 [INTERMEDIATE]    │
│  ✅ Embedded Systems Basics           [INTERMEDIATE]    │
│  🔄 VLSI Design & Verilog            [IN PROGRESS]     │
│  🔄 FPGA Implementation              [IN PROGRESS]     │
│  🔄 Advanced Embedded Systems        [UPCOMING]        │
│  🔄 Semiconductor Technology         [UPCOMING]        │
│  🔄 Hardware-Aware AI/ML             [UPCOMING]        │
│  ⏳ Real-time Systems Design         [PLANNED]         │
│  ⏳ Tape-Out & IC Design            [FUTURE GOAL]      │
│                                                          │
└─────────────────────────────────────────────────────────┘
```

---

## 🚀 Featured Projects

### 🔌 [Smart IoT Home Automation System]
**Tech**: ESP32 | Arduino | Python | MQTT  
A complete IoT solution for home automation with sensor integration and real-time data monitoring.

### 🎛️ [FPGA-based Digital Signal Processor]
**Tech**: Verilog | FPGA | Vivado  
Implemented DSP algorithms on FPGA for real-time signal processing.

### 🤖 [TinyML Image Classification on ESP32]
**Tech**: TensorFlow Lite | Python | C++  
Deployed optimized ML models on edge microcontrollers for real-world inference.

### 📊 [RTL Design of ALU & CPU Core]
**Tech**: Verilog | Logic Synthesis | Testing  
Designed and simulated a complete arithmetic logic unit with pipelined architecture.

---

## 📊 GitHub Stats & Contributions

<div align="center">
  <img src="https://github-readme-stats.oxro.onrender.com/api?username=rudranilmukherjee1&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&text_color=00d4ff" height="165" alt="GitHub Stats" />
  <img src="https://github-readme-stats.oxro.onrender.com/api/top-langs/?username=rudranilmukherjee1&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&text_color=00d4ff" height="165" alt="Top Languages" />
</div>

<br />

<div align="center">
  <img src="https://streak-stats.demolab.com?user=rudranilmukherjee1&theme=tokyonight&hide_border=true&background=0d1117&ring=00d4ff&fire=ff6b6b" alt="Contribution Streak" width="48%" />
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rudranilmukherjee1&theme=github-dark-dimmed&hide_border=true&area=true&hide_title=false" alt="Contribution Graph" width="48%" />
</div>

---

## 🎓 Certifications & Achievements

- 🏆 **Data Structures & Algorithms** - In Progress
- 🏆 **Digital Electronics & Logic Design** - In Progress  
- 🏆 **Embedded Systems with Arduino** - Completed
- 🏆 **Python for Data Science** - In Progress
- 🏆 **Competitive Programming** - Active on CodeChef & HackerRank

---

## 💡 What I'm Currently Working On

- 🔧 **VLSI Design Projects**: Gate-level optimization & timing analysis
- 🤖 **TinyML Implementation**: Deploying neural networks on microcontrollers
- 📡 **IoT Applications**: Multi-sensor data acquisition and cloud integration
- 🧠 **Advanced DSP**: Real-time signal processing on embedded platforms
- 📚 **System Design**: Learning CAD tools and schematic capture

---

## 🤝 Let's Collaborate!

I'm always excited to:
- 💬 Discuss **ECE concepts**, **embedded systems**, and **VLSI design**
- 🔧 Collaborate on **hardware-software integration projects**
- 🚀 Explore **AI/ML applications in embedded systems**
- 📖 Learn from **experienced engineers and mentors**
- 🌟 Contribute to **open-source hardware projects**

**Feel free to reach out on [LinkedIn](https://www.linkedin.com/in/rudranilmukherjee/) or via [Email](mailto:rudranilmukherjeeclassviiid@gmail.com)!**

---

## 📈 Activity & Contributions

<div align="center">
  
![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=rudranilmukherjee1.rudranilmukherjee1&left_text=Profile%20Views&right_color=00d4ff)

</div>

---

<div align="center">
  
### ✨ "Code is poetry, and hardware is the canvas" ✨

**🌟 If you find my work interesting, don't forget to star the repos! 🌟**

</div>

---

## 📜 Footer

<div align="center">

Built with ❤️ by Rudranil Mukherjee | Last Updated: 2026

*"The future belongs to those who code it"* — Let's build amazing things together! 🚀⚡

</div>
