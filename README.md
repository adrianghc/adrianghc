## Hi there, I'm Adrian! 👋

### Python | C/C++ | Qt

From C/C++ to Python and in between, I work in the low-level (embedded programming), high-level (Python) and where they intersect (e.g., Python bindings and debugging inside the CPython VM). I've presented at a conference (PyConES 2023) and am eager to expand my speaking skills and do more talks. Avid follower of tech news and always in the loop. Eternally fascinated by the intersection of technology, society, politics and culture.

---

- 🛠️ **Tech Stack:**  
  - Languages: **Python**, **C/C++**
  - Frameworks & Tools: **Qt**, Python bindings, embedded systems
- 🎤 **Speaker:** Presented at **PyConES 2023**, looking forward to more opportunities!
- 📖 **Interests:** Technology, society, politics, culture, and anywhere they intersect
- 👤 **Pronouns:** He/him
- 📌 **Location:** Berlin, Germany
- 🌐 **LinkedIn:** [Adrian Georg Herrmann](https://www.linkedin.com/in/adrian-georg-herrmann-7a8b42165/)

---

### 📌 Pinned Repositories

#### [ChaOS](https://github.com/adrianghc/chaos) - A small microkernel operating system

A small microkernel operating system developed from scratch for the ARM-based taskit Portux MiniPC SoC with an AT91RM9200 CPU, 16 MiB Flash memory and 64 MiB RAM. This project was developed during Barry Linnert's operating systems course at Freie Universität Berlin over the course of fourteen weeks in 2018-2019.

Supported features include:

- Serial interface (DBGU) driver (supports read/write, interrupts)
- Processor modes, stacks, dynamic kernel memory management
- Interrupt handlers (SWI, ABT, FIQ, IRQ, UND)
- System timer and scheduling
- Processes/threads, context switches, simple round-robin-based scheduling (preemptive multitasking)
- Memory protection with MMU, logical address spaces
- User/kernel interface (syscalls, utility library)

There are also two example applications that demonstrate several capabilities of the kernel:
1. An application to demonstrate address space separation, context switching, system calls and process/thread creation.
2. An application to demonstrate protection against various forbidden actions.

Limitations:

- No filesystem - everything happens in RAM.
- Therefore, also no dynamic loading of code - everything is statically linked into the kernel binary.

---

#### [HEMS](https://github.com/adrianghc/HEMS) - Home Energy Management System for a residential PV installation

A partial implementation of a Home Energy Management System for a residential PV installation. A custom machine learning model that was trained on historical energy production and weather data would predict future energy production via weather forecasts. These predictions would then be used to recommend a load distribution of house appliances with the goal of increasing energy self-consumption. Predictions could achieve R² scores of over 0.9 when using global radiation data, or up to 0.8 when global radiation data is not available. The allocation of tasks could reach perfect efficacy if sufficient energy for all appliances was expected to be available, and an efficacy of up to about 63% allocated energy if total task energy consumption was expected to be as high as 150% of the total available energy budget.

The prototype implementation consisted of a C++ program for Linux and a set of accompanying Python tools.

---

#### [pyside/pyside-setup](https://github.com/pyside/pyside-setup) - Qt for Python

Qt for Python is a project that enables using the popular cross-platform, GUI-focused Qt library in Python. Qt is a native C++ library that requires bindings in order to be used in Python. Qt for Python consists of two components:

1. **PySide**, which contains said bindings for the library, plus a number of Qt tools and pure Python modules.
2. **Shiboken**, a binding generator that can be used to create bindings for custom classes (even if they don't use Qt).

The project is available under the LGPLv3/GPLv3 and the Qt commercial license.

<!--
**adrianghc/adrianghc** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.
-->
