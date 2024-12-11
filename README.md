# 🖥️ Rethinking Memory Management in Modern Operating Systems

Welcome to the **Memory Management Exploration Project**!  
This project delves into advanced memory management techniques inspired by the research paper *"Rethinking Memory Management in Modern Operating Systems: Horizontal, Vertical, or Random?"* The study addresses the challenges of managing memory in modern multicore systems, proposing the innovative HVR (Horizontal, Vertical, Random) framework to optimize performance.

---

## 📖 Project Overview

This project is part of the **IE2032 – Secure Operating Systems** module in the **B.Sc. (Hons) in Information Technology specializing in Cyber Security** at **SLIIT**.

### 💡 Key Highlights:
- Investigates modern memory management challenges and solutions.
- Implements advanced strategies such as horizontal and vertical partitioning, random allocation, and dynamic workload classification.
- Demonstrates the HVR framework's integration into the Linux kernel.
- Shows up to **20% performance improvement** in managing complex workloads.

---

## 🛠️ Features and Implementations

### 1️⃣ **Key Problems Addressed**
- Inefficient memory access patterns.
- Limited flexibility in memory management.
- Overhead associated with managing multiple applications and dynamic workloads.

### 2️⃣ **Proposed Solutions**
- **Vertical Partitioning:** Divides memory across levels like DRAM and LLC to reduce contention and improve efficiency.
- **Horizontal Partitioning:** Allocates resources within memory levels to minimize interference.
- **Sys-Mon Tool:** Monitors application activities dynamically for real-time optimization.
- **Partitioning & Coalescing:** Optimizes memory usage by dividing and combining memory units.
- **Multi-Policy Framework:** Applies multiple memory management policies simultaneously.

### 3️⃣ **Implementation**
- Developed HVR in the Linux kernel with features like:
  - X-Buddy for physical page indexing.
  - Dynamic partitioning rules to optimize memory for various workloads.
  - Lazy page migration to reduce overhead.

---

## 🔬 Results

- **Performance Gains:** Up to **21% improvement** in memory-intensive workloads.
- **Reduced Overhead:** 
  - Page table sampling overhead minimized.
  - Lazy migration reduces page movement costs.
- **Real-World Applications:** Enhanced memory management for cloud computing and data centers.

---
## 🖋️ About the Team
### Group 16 Members:

- IT23368248 - S.M. Dissanyaka
- IT23406094 - S.D. Jayasinghe
- IT23381322 - Rajapaksha R.P
- IT23265592 - Rajapaksha R.M.P.U

---
## 📚 References
- L. Liu, Y. Li, C. Ding, H. Yang, and C. Wu, "Rethinking Memory Management in Modern Operating System: Horizontal, Vertical or Random?" IEEE Transactions on Computers, vol. 65, no. 6, pp. 1921–1935, Jun. 2016.
- https://doi.org/10.1109/TC.2015.2462813

---

## 📜 How to Use

### 🛠️ Clone this Repository:

