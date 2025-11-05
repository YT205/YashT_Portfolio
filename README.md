# 🚀 Project Portfolio – **Yash Thakker**  

Welcome to my project portfolio! Below is a showcase of engineering and software projects I’ve built, ranging from **operating systems** and **embedded systems** to **robotics** and **mobile applications**.  

---

## 🧩 **Custom RISC-V Operating System (In Progress)**
**Description:**
Designing and implementing a Unix-like operating system from scratch for the RISC-V architecture, focusing on kernel-level systems programming, process management, and hardware-software interfacing.

**Key Features:**
 - Developed a preemptive multitasking kernel with round-robin scheduling and context switching between user and kernel modes.
 - Implemented a virtual memory subsystem using paging with demand allocation and address translation through the RISC-V Sv32 MMU.
 - Created a system call interface for user programs supporting I/O, memory allocation, and inter-process communication.
 - Wrote device drivers for UART serial I/O, real-time clock (RTC), and VirtIO block/network devices using PLIC interrupt handling and memory-mapped I/O.
 - Designed and integrated a basic file system layer to support persistent storage and hierarchical directory structures.
 - Debugged and validated kernel execution using GBD Debugger and custom RISC-V assembly test programs.

🛠 **Tech Stack:** RISC-V Assembly, C, QEMU, VirtIO, PLIC, OS Development

---

## 🧠 **Parallel Programming for CNN Acceleration (In Progress)**
**Description:**
Developing GPU-accelerated implementations of convolutional neural network (CNN) inference pipelines to explore how low-level CUDA optimization techniques can improve performance in embedded and high-performance computing systems.

**Key Features:**
 - Implemented parallelized matrix multiplication and 2D convolution kernels using CUDA threads and shared memory for data reuse, minimizing global memory bandwidth bottlenecks.
 - Explored memory coalescing and bank conflict mitigation techniques to optimize thread-level data access patterns and improve occupancy.
 - Built a forward-pass implementation of the LeNet-5 CNN architecture, integrating convolution, pooling, and fully connected layers optimized for GPU execution.
 - Compared GPU vs. CPU latency and throughput across multiple batch sizes, observing >10× speedup for convolutional layers.
 - Designed a modular pipeline structure to facilitate future integration with embedded AI accelerators or FPGA-based compute platforms.
 - Profiling and optimization performed using Nsight Systems and CUDA Visual Profiler to identify kernel bottlenecks and fine-tune grid/block configurations.

🛠 **Tech Stack:** C/C++, CUDA, NVIDIA Nsight, Parallel Computing, GPU Optimization

---

## 🎮 **FPGA Platformer Game**  
**Description:**  
A **2D platformer game** implemented entirely in hardware on the **Xilinx Urbana board**. Designed custom game logic, rendering, and input handling directly in Verilog.  

**Key Features:**  
- Built **multiple levels** with progression system.  
- Implemented game mechanics: **jumping, collisions, hazards, and victory detection**.  
- **Lava blocks** reset the player’s position; reaching the **green flag** advances to the next level.  
- Designed **HDMI/VGA output module** for real-time graphics rendering.  
- Integrated **user input** for responsive controls.  

🛠 **Tech Stack:** `Verilog`, `Xilinx Urbana FPGA`, `HDMI/VGA Output`  

---

## 🎾 **Tennis Connect App**  
**Description:**  
A **social networking app** for tennis players to connect, find courts, and schedule matches. Coded in our high school independent study CS class.

**Key Features:**  
- **Court Finder:** Integrated **Google Maps API** to filter and display local courts.  
- **Player Matching:** Find players by **skill level** and **location**.  
- **Forum:** Dedicated hub for **tennis advice and discussion**.  
- **Deployment:** Published to the **Google Play Store**.  
- **Recognition:** Won **3rd place in the Congressional App Challenge**.  

🛠 **Tech Stack:** `Java`, `Android Studio`, `Firebase`, `Google Maps API`  

Check out the [demo](https://youtu.be/bq_ouTgR8yc).

---

## 🤖 **Self-Balancing Robot**  
**Description:**  
A **two-wheeled self-balancing robot** that uses **sensor fusion** and **PID control** to stay upright. Built in our college dorm! 

**Key Features:**  
- Implemented a **PID control algorithm** for real-time balance.  
- Used an **MPU-9250 IMU** (gyro + accelerometer + magnetometer) for orientation tracking.  
- Wrote **custom Arduino drivers** for gyroscope data handling.  
- Controlled DC motors with an **H-Bridge motor driver**.  
- Powered by an **Arduino Uno**, achieving smooth recovery from disturbances.
- Designed a custom light-weight frame to house the electrics using **Autodesk Inventor**

🛠 **Tech Stack:** `Arduino Uno`, `MPU-9250 IMU`, `H-Bridge`, `DC Motors`, `PID Control`  

Link to a short [demo](https://youtu.be/Un7fE2883EU).

---

## 🏠 **IoT Smart Blinds**  
**Description:**  
A **wireless smart home device** for controlling window blinds with **Alexa integration**. 

**Key Features:**  
- **ESP32 microcontroller** controls a stepper motor via **A4988 driver**.  
- Connected to **Sinric Pro platform** via Wi-Fi for cloud control.  
- **Alexa voice assistant integration** for hands-free operation.  
- Wrote drivers for a **DHT22 temperature sensor** to monitor and transmit room climate data over I²C.  

🛠 **Tech Stack:** `ESP32`, `A4988 Driver`, `DHT22`, `Arduino IDE`, `Sinric Pro`, `Alexa Integration`  

Click to watch a [demo](https://youtu.be/SyJ3WhEeh3o)

---

## 🔋 **Robotics Telemetry System**  
**Description:**  
A **real-time telemetry system** for monitoring battery voltage on a robotics competition robot. 

**Key Features:**  
- Measured voltage down to **0.01V precision** with a **16-bit ADC**.  
- Data acquisition & processing handled by **Arduino Nano**.  
- Wireless transmission to smartphone using **HC-05 Bluetooth module**.  
- Designed and fabricated a **custom PCB in EagleCAD** for compact performance.  
- Improved **robot safety & reliability** during competitions.  

🛠 **Tech Stack:** `Arduino Nano`, `HC-05 Bluetooth`, `EagleCAD`, `16-bit ADC`, `PCB Design`  


---

## ⚡ **Fighting Robot – Vertical Spinner**  
**Description:**  
Captain of a robotics team that built an **85 lb vertical spinner combat robot**.  

**Key Features:**  
- Designed and assembled the **electronics system**: motors, ESCs, battery management, and receiver module.  
- Collaborated with mechanical subteam to integrate drivetrain & weapon systems.  
- Competed against **30+ teams** and secured 🥇 **1st place at district competition**.  

🛠 **Tech Stack:** `High-Power DC Motors`, `ESCs`, `LiPo Batteries`, `Receiver Modules`  




---
