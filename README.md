# Cheng-Wei,Shih

---

## 🎓 Education

### National Yang Ming Chiao Tung University
**Master's Degree | Institute of Electrical and Control Engineering**  
Sept. 2024 – Sept. 2026 | In Progress

- **GPA:** 4.13 / 4.30
- **Related Courses:** Embedded Operating Systems, Operating Systems, Computer Architecture, Memory and Storage Systems, Digital Image Processing, Algorithms (In Progress)

### National Sun Yat-sen University
**Bachelor's Degree | Mechanical and Electro-Mechanical Engineering**  
Sept. 2020 – Jun. 2024 | Graduated

- **GPA:** 4.10 / 4.30
- **Department Ranking:** 2 / 115 (for Master's Program Recommendation); 6 / 93 at Graduation
- **Related Courses:** C, C++, MATLAB Programming

---

## 🔬 Research Experience

### Human and Machine Lab | National Yang Ming Chiao Tung University
Sept. 2024 – Sept. 2026

**Master's Thesis**  
*An LLM-Based Task Sequence Generation System with Error Localization and Local Repair*

- **Keywords:** Industrial Robot, LLM, PDDL, Error Localization, Local Repair, Long-Horizon Task Planning

**NSTC Research Project**  
*Development of an Industrial Robot ChatBot for AMR Flexible Manufacturing*

**Advisor:** Prof. Kuu-Young Young

---

## 📄 Publication

### LLM-Based Task Planning for Robot Assembly
**International Conference on Advanced Robotics and Intelligent Systems (ARIS)**  
Taichung, Taiwan | 2025 | LBR

---

## 💼 Experience

### Automatic System Development Engineer
**Hong Lang Technology Co., Ltd.**  
Zhonghe District, New Taipei City  
Jul. 2024 – Jul. 2025

*Footwear Manufacturing Automation Solution*

- Developed automated machinery systems for the footwear industry, focusing on production efficiency and reliability.
- Maintained and extended codebase by implementing new functional modules and improving system stability.

### Industry Collaboration Project
**Techman Robot Inc.**  
Taoyuan, Taiwan  
Sept. 2024 – Present

*Reducer Production-Line Improvement*

- Collaborated with Techman Robot on an industrial reducer-bearing assembly application and improved the existing robotic assembly workflow.
- Developed a rapidly deployable human-machine interface using structured representations and iterative refinement, enabling a 7B local LLM to reliably generate robot task sequences.

---

# 💾 Memory and Storage Systems

## Technical Foundations: NAND Flash, SSD Systems, and Linux I/O Stack

- Familiar with **NAND Flash / SSD architecture and FTL mechanisms**, including:
  - LBA-to-PBA address remapping
  - Out-of-place updates
  - Page-/block-level address translation
  - Garbage Collection (GC)
  - Dynamic / Static Wear Leveling

- Familiar with NAND Flash device operations and reliability, including:
  - Page-level read / program
  - Block-level erase
  - SLC / MLC / TLC / QLC
  - Retention errors
  - Read retry
  - P/E-cycle endurance

- Familiar with the Linux storage I/O stack, including:
  - Block I/O
  - bio
  - VFS
  - I/O scheduling
  - RAID reliability / performance trade-offs

---

## Project: Memory and Program Performance Profiling

- Used **Valgrind Memcheck** to diagnose:
  - Invalid memory accesses
  - Uninitialized values
  - Invalid frees
  - Memory leaks

- Used **Cachegrind** and **Massif** to analyze:
  - Cache locality
  - Memory-access behavior
  - Heap usage

- Used **Callgrind / KCachegrind** and **PyTorch Profiler** to identify:
  - Function-level bottlenecks
  - Call-graph bottlenecks
  - CPU execution bottlenecks
  - Transformer workload bottlenecks

---

## Project: NVMe Storage I/O Benchmarking and Performance Tuning

- Benchmarked **NVMe storage using FIO** across:
  - Sequential / Random read and write
  - Buffered / Direct I/O
  - Different block sizes

- Analyzed storage performance using:
  - IOPS
  - Bandwidth
  - Latency
  - Page Cache effects
  - Different I/O access patterns

- Tuned I/O access patterns and block sizes to improve direct sequential-read performance.

---

# 🐧 Operating Systems and Embedded Operating Systems

## Technical Foundations: Linux Kernel and Embedded Operating Systems

- Familiar with Linux process management and execution:
  - `task_struct`
  - `fork()` / `exec()`
  - Copy-on-Write
  - Context Switching
  - CFS

- Familiar with physical and virtual memory management:
  - Page Tables
  - TLB Translation
  - Page Faults
  - Swapping
  - Buddy Allocator
  - Slab Allocator
  - Huge Pages
  - NUMA

- Familiar with embedded OS hardware interaction and interrupt mechanisms:
  - Memory-Mapped I/O
  - Device-Control Registers
  - Interrupt Latency
  - Deferred Interrupt Handling
  - Priority-Inversion Avoidance

---

## OS Project: RISC-V Linux Kernel Programming and Scheduling

- Implemented custom **system calls** in the RISC-V Linux kernel, including:
  - User–kernel data transfer
  - Mutex-protected kernel linked list

- Developed a multithreaded scheduling-policy demonstration using:
  - `SCHED_FIFO`
  - `SCHED_OTHER`
  - Real-time priorities
  - CPU affinity
  - CPU-bound workloads

- Built a Linux **character-device kernel module**:

```text
/dev/kfetch
