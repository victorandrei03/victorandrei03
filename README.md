# 🚀 Hi, I'm Victor-Andrei Preda
### Software Engineer

Welcome to my GitHub profile! Here you can find a showcase of my technical projects, ranging from low-level operating systems, networking protocols, and embedded hardware to graph algorithms, numerical analysis, and game development.

---

## 🎮 Game Development & Embedded Systems

* **[SurvivorsOfTheHollow](https://github.com/victorandrei03/Survivors-of-the-Hollow)** – A survival action game developed in C++ and Unreal Engine 5. Features dynamic enemy wave spawning, custom player abilities, combat mechanics, AI behavior trees, and UI systems.
  * **Tech:** C++, Unreal Engine 5, Blueprints, Game AI, UI Systems.
 
* **[Drone Racing Game](https://github.com/victorandrei03/Drone-Racing)** – An interactive 3D Drone Racing Game built with Modern OpenGL, featuring procedural terrain heightmaps, custom GLSL vertex/fragment noise shaders, 3D AABB & Ellipsoid collision detection, dynamic minimap rendering, and a time-attack checkpoint navigation system.
  * **Tech:** C++, Modern OpenGL, GLSL Shaders, Procedural Noise, 3D Collision Detection, `gfx-framework`.

* **[Tank-Wars](https://github.com/victorandrei03/Tank-Wars)** – A 2D real-time interactive artillery game featuring procedurally generated deformable terrain (sine-wave synthesis), dynamic impact craters, landslide slope smoothing, ballistic projectile trajectory preview, and 2D matrix shear transformations.
  * **Tech:** C++, OpenGL, Ballistic Physics, Procedural Deformable Terrain, 2D Shear Transformations.

* **[Pico-checkers](https://embedded-rust-101.wyliodrin.com/docs/acs_cc/project/2025/victor_andrei.preda)** – A hardware-based online multiplayer Checkers game built on two Raspberry Pi Pico 2W microcontrollers communicating via Wi-Fi[cite: 1]. Developed in Rust (`no_std`) using the `Embassy` async runtime, featuring real-time SPI LCD rendering and custom Flash memory storage[cite: 1].
  * **Tech:** Rust, Embassy Async, CYW43 Wi-Fi, SPI LCD (ILI9341), Embedded Graphics, Flash Memory[cite: 1].

---

## 🖥️ Operating Systems & Low-Level C Programming

* **[POSIX Mini-Shell](https://github.com/victorandrei03/Mini-Shell)** – A Bash-like command-line interpreter supporting process execution, environment variable handling, built-in commands (`cd`, `pwd`), and complex execution operators including sequential (`;`), parallel (`&`), conditional (`&&`, `||`), pipes (`|`), and file I/O redirection[cite: 5].
  * **Tech:** C, POSIX API, `fork()`, `execvp()`, `dup2()`, Anonymous Pipes, Process Management[cite: 5].

* **[Custom Memory Allocator](https://github.com/victorandrei03/Memory-allocator)** – A minimalistic dynamic memory management library implementing `malloc`, `calloc`, `realloc`, and `free`[cite: 7]. Interacts directly with Linux kernel syscalls (`brk`, `mmap`, `munmap`) with 8-byte alignment, heap pre-allocation, block splitting, and best-fit block coalescing[cite: 7].
  * **Tech:** C, Linux Syscalls (`brk`/`mmap`), Virtual Memory, Dynamic Memory Management[cite: 7].

* **[Mini-LibC](https://github.com/victorandrei03/Mini-LibC)** – A lightweight, zero-dependency C standard library replacement (`mini-libc`) built directly on top of `x86_64` Linux system calls[cite: 8]. Implemented core functionality for string manipulation, memory operations (`memcpy`, `memset`), POSIX file I/O, and memory mapping[cite: 8].
  * **Tech:** C, x86_64 Assembly, Linux Syscalls, POSIX I/O, Memory Management[cite: 8].

---

## ☁️ Cloud-Native, Microservices & Web Development

* **[Cloud-Native Collaborative Shopping List System](https://github.com/shopping-list-cloud-native)** – A distributed, cloud-native collaborative platform built on a microservices architecture deployed on Docker Swarm. Features JWT authentication, shared shopping list management, automated budget/expense threshold calculation, real-time modification notifications, and data-layer isolation using custom Docker network segmentation.
  * **Tech:** Microservices, Docker Swarm, Kong API Gateway, PostgreSQL, Portainer, Prometheus & Grafana, REST APIs.

* **[RoRoute - Smart Travel & Itinerary Planner](https://github.com/victorandrei03/RoRoute)** – An interactive web application for planning and optimizing vacation itineraries across Romania. Features an interactive attractions map with rich pop-ups, custom user preference surveying, backend route optimization logic, attraction rating/review workflows, and real-time database synchronization.
  * **Tech:** Angular, Flask (Python), Firebase Realtime Database, ArcGIS JavaScript API, ArcGIS Online, `bcrypt`.

---

## ⚡ Parallel Computing & Multithreading

* **[BitTorrent-MPI](https://github.com/victorandrei03/BitTorrent-MPI)** – A custom C++ implementation of the BitTorrent file-sharing protocol using MPI (Message Passing Interface) for parallel execution[cite: 3]. Simulates peer-to-peer segment exchanges with ACK/NACK signaling, dynamic seed/peer role transitioning, and centralized tracker state synchronization[cite: 3].
  * **Tech:** C++, MPI, P2P Architecture, Parallel Computing, STL[cite: 3].

* **[Pthreads Map-Reduce Framework](https://github.com/victorandrei03/Map-Reduce)** – A multithreaded Map-Reduce processing engine built in C using POSIX Threads[cite: 4]. Features thread-safe task distribution via mutex-guarded work queues, custom barrier synchronization between Mapper and Reducer phases, and parallel result aggregation[cite: 4].
  * **Tech:** C, Pthreads, Concurrency, Mutexes, Barriers, Parallel Algorithms[cite: 4].

* **[Parallel Graph Traversal with Thread Pool](https://github.com/victorandrei03/Parallel-Graph)** – A high-performance parallel BFS graph traversal system using a custom C thread pool architecture[cite: 6]. Utilizes dynamic task queues and fine-grained mutex synchronization to safely compute global graph metrics concurrently without data races[cite: 6].
  * **Tech:** C, Multithreading, Thread Pools, Synchronization, Graph Algorithms[cite: 6].

---

## 🌐 Networking, Protocols & Web Applications

* **[Router Dataplane Implementation (IPv4, ARP, ICMP)](https://github.com/victorandrei03/Router)** – A custom software router dataplane implementing core network layer protocols[cite: 12]. Features IPv4 packet routing with longest prefix matching (LPM) and checksum validation, ARP cache handling with dynamic request/reply queuing, and ICMP error signaling[cite: 12].
  * **Tech:** C, Networking, IPv4, ARP, ICMP, Dynamic Routing, Packet Processing[cite: 12].

* **[TCP/UDP Network Communication & Protocol](https://github.com/victorandrei03/Client--Server-Application)** – A multiplexed I/O server-client system built with `poll()` handling concurrent TCP clients and UDP packet forwarding[cite: 11]. Implemented custom binary protocol serialization, state tracking for client connections/subscriptions, and wildcard pattern matching (`+`, `*`) for topic routing[cite: 11].
  * **Tech:** C++, TCP/IP, UDP Sockets, I/O Multiplexing (`poll`), Protocol Design[cite: 11].

* **[HTTP REST Client & Library System](https://github.com/victorandrei03/WEB-app)** – A command-line client interacting with a RESTful server over custom TCP sockets[cite: 10]. Features user authentication with session cookies, JWT bearer authorization for restricted routes, and strict request payload validation with JSON parsing[cite: 10].
  * **Tech:** C++, REST API, JWT, Sockets, HTTP Protocol, `nlohmann/json`[cite: 10].

---

## 🧮 Algorithms, Numerical Methods & Data Structures

* **[Markov Chain Maze Solver & Linear Regression Engine](https://github.com/victorandrei03/Markov)** – Implementation of numerical algorithms in MATLAB[cite: 16, 17]. Features a Markov Chain probabilistic maze solver using iterative Jacobi solvers and greedy heuristics, alongside a Multiple Linear Regression engine with L1/L2 regularization (Lasso/Ridge) and Gradient Descent optimization[cite: 16, 17].
  * **Tech:** MATLAB, Sparse Matrices, Markov Chains, Jacobi Iterative Solver, Linear Regression[cite: 16, 17].

* **[Quadtree Image Compression Tool](https://github.com/victorandrei03/quad-tree)** – An image processing application in C utilizing quaternary tree data structures for PPM image lossy compression and decompression[cite: 18]. Evaluates pixel matrix similarity metrics using arithmetic means to recursively subdivide image quadrants[cite: 18].
  * **Tech:** C, Binary File I/O, Quadtrees, Image Processing (PPM format), Recursive Subdivision[cite: 18].

* **[Halite Map-Expansion Bot](https://github.com/victorandrei03/Halite-Bot)** – A strategic game bot designed for territorial expansion over a grid map[cite: 13]. Implements a custom scoring heuristic evaluating tile production, strength ratios, distance decay factors, and map expansion coefficients to calculate optimal tactical moves[cite: 13].
  * **Tech:** C++, Search Heuristics, Spatial Scoring, Strategic AI[cite: 13].

* **[Graph Optimization Suite (DP & Shortest Paths)](https://github.com/victorandrei03/Graph-theory-in-real-life-problems)** – Algorithmic solutions for complex graph problems including common graph construction with Dynamic Programming path counting, recursive topological sorting for longest-path determination, and mandatory path selection using multi-source Dijkstra[cite: 14].
  * **Tech:** C++, Graph Theory, Dynamic Programming, Topological Sort, Dijkstra's Algorithm[cite: 14].

* **[Algorithmic Problem-Solving Suite](https://github.com/victorandrei03/Dynamic-programming-Greedy-algorithms)** – A collection of efficient C++ solutions covering binary search over continuous bounds, dynamic programming state transitions, 0/1 Knapsack optimization, and list compression algorithms[cite: 15].
  * **Tech:** C++, Binary Search, Dynamic Programming, Knapsack Problem, Greedy Algorithms[cite: 15].

* **[Text-Highlighting, Autocomplete & Ciphers Suite](https://github.com/victorandrei03/Autocomplete--TextHighlight)** – Low-level C utilities featuring dynamic text-highlighting parser, dictionary-based autocomplete engine with priority tracking, Columnar Transposition Cipher implementation, and cycle-detection algorithms for the Prisoners & Boxes problem[cite: 19, 20].
  * **Tech:** C, Dynamic Memory Allocation, String Parsing, Cryptography, Permutation Cycles[cite: 19, 20].

---

## 💻 Software Engineering & OOP Applications

* **[IMDB-Style Entertainment System](https://github.com/victorandrei03/IMDB-SWING)** – A desktop movie and actor database management system built using clean OOP principles and Design Patterns (Observer, Strategy)[cite: 9]. Supports dual operational interfaces (CLI and Java Swing GUI), role-based access control (Admin, Contributor, Regular), real-time notifications, user reviews, and personalized favorite lists[cite: 9].
  * **Tech:** Java, Java Swing (GUI), OOP, Observer & Strategy Design Patterns[cite: 9].

---

📬 **How to reach me:**
- **LinkedIn:** [linkedin.com/victor-preda](https://www.linkedin.com/in/victor-preda-83ab4b280/)
- **Email:** victorandrei05@gmail.com
