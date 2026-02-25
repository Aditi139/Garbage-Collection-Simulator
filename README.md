🧠 Garbage Collection Simulator

An interactive Garbage Collection & Memory Management Simulator built using PHP + Tailwind CSS + Chart.js.

This project visually demonstrates:

Generational Garbage Collection

Mark and Sweep Algorithm

Memory Allocation & Deallocation

Fragmentation & Compaction

Root References

GC Performance Metrics

📌 Project Overview

The simulator mimics how modern programming languages manage memory internally using:

🟥 Young Generation

🟨 Middle Generation

🟩 Old Generation

Objects move between generations based on survival after garbage collection cycles.

It also provides real-time visualization of:

Memory blocks

Object references

Root references

Fragmentation percentage

GC performance statistics

🛠️ Tech Stack
Backend

PHP (OOP Based)

Session Handling

Frontend

Tailwind CSS

Chart.js

JavaScript

🧩 Core Concepts Implemented
1️⃣ Memory Pool Simulation

Fixed-size block memory

Contiguous allocation

Free block detection

2️⃣ Generational GC

Young Collection

Middle Collection

Old Collection

Full GC

3️⃣ Mark & Sweep Algorithm

Mark reachable objects from root references

Sweep unreachable objects

Promote surviving objects

4️⃣ Memory Compaction

Rearranges objects

Reduces fragmentation

5️⃣ Object References

Objects can reference other objects

Reference tracking

Root reference control

🎮 Available Actions

Allocate Small / Medium / Large Object

Collect Young Generation

Collect Middle Generation

Collect Old Generation

Full Garbage Collection

Compact Memory

Make Object Root

Remove Root

Manually Free Object

📊 Real-Time Statistics

The simulator tracks:

Total Blocks

Allocated Blocks

Free Blocks

Fragmentation %

Young / Middle / Old Object Count

Total GC Runs

Objects Collected

Total GC Time

Average Objects Collected per GC

📂 Project Structure
Garbage-Collection-Simulator/
│
├── index.php   # Main simulator file
└── README.md

This project helps understand:

How memory is allocated internally

Why garbage collection is needed

How fragmentation occurs

Difference between generational GC and full GC

Real-world GC behavior simulation

📈 Learning Outcomes

After using this simulator, you will clearly understand:

Heap memory behavior

Object lifecycle

Reachability analysis

Reference-based memory management

Compaction techniques

🚀 Future Improvements

Circular reference visualization

Stop-the-world simulation delay

GC tuning parameters

Heap resizing

Detailed object inspection modal

Export GC statistics

👨‍💻 Built For

Computer Science students learning:

Operating Systems

Memory Management

Data Structures

Runtime Systems

Garbage Collection Algorithms
