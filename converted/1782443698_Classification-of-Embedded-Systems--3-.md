<!-- Slide number: 1 -->

Classification of Embedded Systems
Presented by:
Fazal – 3BR25CA022
R Mallikarjuna swamy – 3BR25CA080
Manikanta N – 3BR25CA048
Mohammad Aadil Pasha – 3BR25CA056
Guided by:- Prof. Harshitha K R

### Notes:

<!-- Slide number: 2 -->
Embedded Systems: Classification Framework
Embedded systems: An Embedded System is a dedicated computer system built into a device to perform a specific task, combining hardware and software to control and automate functions without human interaction.
The classification of Embedded systems is as follows:
Based on generations.
Complexity and performance required.
Based on deterministic behaviour.
Based on triggering.

### Notes:

<!-- Slide number: 3 -->

GENERATION
1st & 2nd Generation Embedded Systems
Embedded systems evolved from 1st generation simple 8/4-bit microprocessor-based systems handling basic tasks, to 2nd generation more powerful 16-bit processor-based systems with complex instruction sets handling advanced industrial applications.
1st Generation — 8-bit Era
Built around 8-bit microprocessors and 4-bit microcontrollers — minimal hardware, simple firmware, single-function tasks.
Digital telephone keypads
Stepper motor control units
2nd Generation — 16-bit Era
Upgraded to 16-bit processors and 8/16-bit microcontrollers — richer instruction sets enabling industrial data processing and remote monitoring.
Data Acquisition Systems
SCADA (Supervisory Control & Data Acquisition)

### Notes:

<!-- Slide number: 4 -->

GENERATION
3rd Generation — The Domain-Specific Era
The 3rd generation introduced domain-specific chips — systems could now be optimized for specific tasks, delivering higher speed and power efficiency.
32-bit Processors
DSPs
Greater processing power and addressable memory for complex applications.
Digital Signal Processors optimized for real-time signal math — audio, video, communications.
ASICs
Applications
Application-Specific Integrated Circuits — custom hardware for a single dedicated function.
Robotics, industrial process control, and embedded networking.

### Notes:

<!-- Slide number: 5 -->

![preencoded.png](Image0.jpg)

GENERATION
4th Generation — System on Chip
The 4th generation unified processor, memory, and peripherals onto a single chip — slashing size, cost, and power consumption while boosting performance.
Connectivity became a core feature — built-in Wi-Fi, Bluetooth, and cellular support made 4th gen systems the foundation of IoT Power efficient. improved drastically — advanced fabrication allowed higher performance with significantly lower power consumption, enabling longer battery life in smart devices.
SoC (System on Chip)
Multicore & Reconfigurable
Examples
Smartphones, Mobile Internet Devices (MIDs).
Full system integration on one die.
Parallel processing and adaptive architectures.

### Notes:

<!-- Slide number: 6 -->

CLASSIFICATION 2
Complexity & Performance Classification
Beyond historical generations, embedded systems are classified by scale of complexity into three practical tiers. Unlike generation-based classification, this framework directly guides design and cost decisions in real projects — helping engineers select the right hardware for the right application.
Performance needs define the choice — a simple sensor node doesn't need a 64-bit processor; matching complexity to requirement is what makes embedded design efficient.
Cost scales with complexity — small scale systems are cheapest, while large scale systems involve significantly higher design and manufacturing costs
Large Scale,
Medium Scale
High performance, critical systems,

### Notes:

<!-- Slide number: 7 -->

COMPLEXITY
Small Scale Embedded Systems
A Small Scale Embedded System is a simple, low-cost embedded system built around 8-bit or 16-bit microprocessors/microcontrollers, designed to perform a single specific task with minimal hardware and firmware, and may or may not require an operating system to function.
No OS required in most cases — these systems run on bare-metal firmware, meaning the code directly controls the hardware without any operating system layer
The most widely produced embedded systems in the world — found in everyday household devices. Built for simplicity, low cost, and single-function operation.

Hardware
Software
Example
Low-performance 8-bit or 16-bit microprocessors/microcontrollers
May or may not require an OS — often bare-metal firmware.
Electronic toys, remote controls, basic sensors.

### Notes:

<!-- Slide number: 8 -->

COMPLEXITY
Medium Scale Embedded Systems
Used where moderate processing power and real-time capability are needed — balancing performance with cost. These systems typically run a lightweight OS or RTOS.

Processors
RTOS
16/32-bit microprocessors, microcontrollers, or DSPs with medium performance at low cost.
A Real-Time Operating System manages tasks efficiently without the overhead of a full OS.

DSPs & ASICs
Applications
Digital Signal Processors and ASICs fall into this category — optimized for specific workloads.
Industrial controllers, smart meters, automotive subsystems, and consumer electronics.

### Notes:

<!-- Slide number: 9 -->

COMPLEXITY
Large Scale Embedded Systems
A Large Scale Embedded System is a highly complex system built around 32/64-bit processors and SoC, designed to handle intensive real-time tasks like media decoding and cryptographic functions.
The backbone of modern infrastructure — from medical imaging to aerospace control. Failure is not an option.

Hardware
Software
Examples
32/64-bit processors, RISC, SoC, and scalable configurable processors.
Powerful OS required — handles intensive, real-time workloads.
Media encoding/decoding, cryptographic implementations, medical imaging, aerospace systems.

### Notes:

<!-- Slide number: 10 -->
THANK YOU!

### Notes: