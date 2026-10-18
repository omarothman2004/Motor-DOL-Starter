# 🏭 PLC Ladder Logic & Industrial Automation Portfolio

## 🎯 Overview
Welcome to my industrial automation and PLC programming repository! This workspace is dedicated to building my expertise in ladder logic design, control system architectures, and safety interlocks. 

The projects here are programmed using **Siemens LOGO! Soft Comfort (v9)** and targeted for deployment and simulation on a compact Siemens logic controller.

---

## 🛠️ Hardware & Software 

* **Controller:** [Siemens LOGO! 12/24RCE (Model: 6ED1052-1MD08-0BA2)](https://sieportal.siemens.com/en-gb/products-services/detail/6ED1052-1MD08-0BA2?tree=CatalogTree#documentsAndDownloads)
  * **Power Supply:** 12/24V DC
  * **Inputs:** 8 Digital Inputs (4 configurable as 0–10V Analog Inputs)
  * **Outputs:** 4 Relay Outputs (10A capacity)
  * **Features:** Ethernet port, integrated web server, and microSD card support.
* **Programming Software:** Siemens LOGO! Soft Comfort v9

---

## 🚀 Examples of Projects I am working on

As I build exposure to industrial automation, this repository will document sequential routines focusing heavily on hardware safety interlocks, fault handling, and process timing:

1. **Basic Sensor Simulation (NC/NO Contacts)** 🎛️
   - *Objective:* Understanding physical signal mapping using Normally Open (NO) and Normally Closed (NC) field contacts.
   - *Focus:* Digital input states, signal inversion, and basic combinational logic gates.

2. **Motor Direct-On-Line (DOL) Starter Program** ⚡
   - *Objective:* Implementing standard motor starter logic with seal-in (latching) contacts.
   - *Focus:* Incorporating safety interlocks such as emergency stop buttons (NC) and thermal overload trip monitoring to prevent unsafe machine restarts.

3. **Conveyor Belt System Control** 📦
   - *Objective:* Sequencing a multi-stage material handling process.
   - *Focus:* Timers, counters, sensor handshaking, product sorting logic, and safety light-curtain/emergency stop integration.

4. **Iterative Control Exercises** ⚙️
   - *Objective:* Developing custom minor routines, state machines, and warning indicator sequences to explore advanced block functionalities within LOGO! Soft Comfort.

---

## 📂 Repository Structure
- `/programs`: LSC project files for Siemens LOGO! Soft Comfort.
- `/docs`: Wiring diagrams, I/O assignment lists, and functional descriptions.
