<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/rfs-hybrid/42-Common-Core/main/assets/logos/42_Logo_White.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/rfs-hybrid/42-Common-Core/main/assets/logos/42_Logo_Black.svg">
    <img alt="42 Logo" src="https://upload.wikimedia.org/wikipedia/commons/8/8d/42_Logo.svg" width="150" />
  </picture>
  
  <h1>🌌 42 Common Core</h1>
  <p><i>A showcase of low-level systems programming, algorithmic optimization, and robust UNIX architecture.</i></p>
  
  [![maaugust's 42 stats](https://badge.mediaplus.ma/binary/maaugust?1337Badge=off&UM6P=off)](https://github.com/oakoudad/badge42)
  <br />
</div>

---

## 🛠️ Core Competencies
* **Languages:** C, Bash, Shell Scripting
* **Systems & Architecture:** UNIX/Linux Process Management, POSIX Threads, Inter-Process Communication (Pipes, Semaphores, Mutexes), Abstract Syntax Trees (AST)
* **Networking & Infrastructure:** Virtualization, Subnetting & Network Routing (TCP/IP), LVM, UFW
* **QA & Optimization:** Memory Leak Profiling (Valgrind), Thread Sanitization (Helgrind), Algorithmic Time/Space Complexity ($Big\ O$)

---

## 🚀 The "125% Standard" (Engineering Philosophy)

The 42 curriculum is heavily project-based and peer-evaluated. While completing the core requirements is enough to pass, **I treat every project in this portfolio as production-grade software.** Every completed project in this repository has been engineered to achieve the maximum possible bonus score (**125%**). This isn't just about grades; it's a deliberate engineering choice to tackle the most complex architectural challenges available:
* **Defensive Programming:** Every memory allocation is protected. Every file descriptor is tracked. Every executable is proven 100% leak-free via rigorous `Valgrind` testing.
* **Advanced Architectures:** Going beyond the basics (e.g., building a full AST for `minishell` parsing, or implementing multi-process semaphore locking for `philosophers`).
* **Strict Compliance:** All C code adheres to the draconian *42 Norm* (strict formatting, maximum of 4 parameters per function, maximum 25 lines per function), forcing highly modular, decoupled, and readable codebases.

This repository uses a **Git Submodule architecture**. Each project below links to its dedicated repository, complete with exhaustive documentation, technical breakdowns, and testing strategies.

*(To clone with all source code: `git clone --recurse-submodules https://github.com/rfs-hybrid/42-Common-Core.git`)*

---

## 🏆 Curriculum Progress & Skills Matrix

*Currently starting Milestone 4.*

### 🧱 Milestone 0 & 1: The Foundations
*Mastering C programming, memory management, and system administration.*

| Project | Status | Technologies & Concepts | Description |
| :---: | :---: | :--- | :--- |
| [**Libft**](https://github.com/rfs-hybrid-42-common-core/libft)<br>![libft](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/libftm.png) | 🟢 Done<br>*(125%)* | **C, Makefile**<br>Memory Management, Linked Lists, Pointers | Recoding standard C library functions (`libc`) from scratch to build a foundational personal library used throughout the curriculum. |
| [**ft_printf**](https://github.com/rfs-hybrid-42-common-core/ft_printf)<br>![ft_printf](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/ft_printfm.png) | 🟢 Done<br>*(125%)* | **C, Makefile**<br>Variadic Functions, String Formatting | Rebuilding the standard `printf` function, handling dynamic argument lists (`va_list`) and complex formatting flags. |
| [**get_next_line**](https://github.com/rfs-hybrid-42-common-core/get_next_line)<br>![get_next_line](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/get_next_linem.png) | 🟢 Done<br>*(125%)* | **C, IO Operations**<br>Static Variables, File Descriptors, Buffers | Writing a highly optimized function to read a file line-by-line without memory leaks, regardless of the buffer size. |
| [**Born2beroot**](https://github.com/rfs-hybrid-42-common-core/Born2beroot)<br>![Born2beroot](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/born2berootm.png) | 🟢 Done<br>*(125%)* | **Debian, Rocky, VirtualBox**<br>Sysadmin, LVM, Bash Scripting, UFW, Firewalld, SSH | Setting up, configuring, and securing a strict virtual machine environment according to specific corporate-level IT guidelines. |

### ⚙️ Milestone 2: Algorithms & UNIX Pipes
*Exploring algorithmic complexity, data structures, and inter-process communication.*

| Project | Status | Technologies & Concepts | Description |
| :---: | :---: | :--- | :--- |
| [**push_swap**](https://github.com/rfs-hybrid-42-common-core/push_swap)<br>![push_swap](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/push_swapm.png) | 🟢 Done<br>*(125%)* | **C, Makefile**<br>Sorting Algorithms, Big O, Data Structures | Sorting a random stack of integers using a strictly limited set of operations to achieve the lowest possible algorithmic time complexity. |
| [**pipex**](https://github.com/rfs-hybrid-42-common-core/pipex)<br>![pipex](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/pipexm.png) | 🔵 Unevaluated<br>*(125% Built)* | **C, Makefile**<br>UNIX Processes, Pipes, File Descriptors | Recreating the behavior of UNIX shell pipes and redirections, rigorously managing concurrent execution and in-memory `here_doc` routing. |
| [**minitalk**](https://github.com/rfs-hybrid-42-common-core/minitalk)<br>![minitalk](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/minitalkm.png) | 🟢 Done<br>*(125%)* | **C, Makefile**<br>UNIX Signals, IPC, Bitwise Operations | Building a client-server data exchange program that transmits strings across processes exclusively using OS-level signals (`SIGUSR1/2`). |
| [**fract-ol**](https://github.com/rfs-hybrid-42-common-core/fract-ol)<br>![fract-ol](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/fract-olm.png) | 🟢 Done<br>*(125%)* | **C, MiniLibX, Math**<br>Graphics, Complex Numbers, Optimization | Programming a high-performance graphical renderer to explore and infinitely zoom into mathematical fractals (Mandelbrot, Julia, Phoenix). |

### 🧠 Milestone 3: Concurrency & Shell Architecture
*Mastering process synchronization, threading, and shell logic.*

| Project | Status | Technologies & Concepts | Description |
| :---: | :---: | :--- | :--- |
| [**Philosophers**](https://github.com/rfs-hybrid-42-common-core/philosophers)<br>![philosophers](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/philosophersm.png) | 🟢 Done<br>*(125%)* | **C, POSIX Threads**<br>Mutexes, Semaphores, Deadlocks, Data Races | Solving the Dining Philosophers problem by carefully managing concurrent threads/processes and protecting shared resources. |
| [**minishell**](https://github.com/rfs-hybrid-42-common-core/minishell)<br>![minishell](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/minishellm.png) | 🟢 Done<br>*(125%)* | **C, Makefile**<br>AST, Lexer/Parser, Redirections, Pipes | Developing a fully functional UNIX shell from scratch, complete with an expansion engine, logical short-circuiting, and built-ins. |

### 🌐 Milestone 4: Networking, 3D & OOP
*Stepping into network engineering, raytracing, and Object-Oriented C++.*

| Project | Status | Technologies & Concepts | Description |
| :---: | :---: | :--- | :--- |
| [**NetPractice**](https://github.com/rfs-hybrid-42-common-core/netpractice)<br>![NetPractice](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/netpracticem.png) | 🟡 Up Next | **Networking**<br>TCP/IP, Subnetting, Routing, Masks | Configuring small-scale virtual networks to solve addressing and routing problems. |
| [**miniRT**](https://github.com/rfs-hybrid-42-common-core/miniRT)<br>![miniRT](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/minirtm.png) | 🟡 In Progress | **C, MiniLibX, Math**<br>Raytracing, Vectors, Lighting, 3D Rendering | Creating a 3D rendering engine capable of displaying mathematically generated spheres, planes, and cylinders with lighting computation. |
| [**CPP 00-04**](https://github.com/rfs-hybrid-42-common-core/cpp_modules)<br>![CPP](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/cppm.png) | ⚪ Not Started | **C++98, Makefile**<br>OOP, Classes, Polymorphism, Inheritance | A deep dive into the fundamentals of Object-Oriented Programming using C++. |

### 🏗️ Milestone 5: Infrastructure & Advanced OOP
*Deploying containerized infrastructure and building non-blocking servers.*

| Project | Status | Technologies & Concepts | Description |
| :---: | :---: | :--- | :--- |
| [**Inception**](https://github.com/rfs-hybrid-42-common-core/inception)<br>![Inception](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/inceptionm.png) | ⚪ Not Started | **Docker, Alpine**<br>Containerization, DevOps, Nginx, MariaDB | Deploying a multi-container infrastructure using `docker-compose`, strictly building customized images from Alpine Linux. |
| [**webserv**](https://github.com/rfs-hybrid-42-common-core/webserv)<br>![webserv](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/webservm.png) | ⚪ Not Started | **C++98, Network I/O**<br>HTTP/1.1, Sockets, Multiplexing (`epoll`) | Writing a fully compliant, non-blocking HTTP web server from scratch capable of handling multiple client requests concurrently. |
| [**CPP 05-09**](https://github.com/rfs-hybrid-42-common-core/cpp_modules)<br>![CPP](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/cppm.png) | ⚪ Not Started | **C++98, Makefile**<br>Templates, Exceptions, STL, Casts | Mastering advanced C++ concepts and the Standard Template Library (STL). |

### 🚀 Milestone 6: The Final Project
*The culmination of the 42 Common Core.*

| Project | Status | Technologies & Concepts | Description |
| :---: | :---: | :--- | :--- |
| [**ft_transcendence**](https://github.com/rfs-hybrid-42-common-core/ft_transcendence)<br>![ft_transcendence](https://github.com/rfs-hybrid/42-common-core/raw/main/assets/badges/ft_transcendencem.png) | ⚪ Not Started | **TypeScript, NestJS**<br>WebSockets, SPA, React/Vue, PostgreSQL | Building a full-stack, real-time multiplayer Pong website with chat rooms, user authentication, and matchmaking. |

---

## 📬 Connect & Collaborate
I am always open to discussing system architecture, C programming, and low-level optimization.

* **GitHub:** [@rfs-hybrid](https://github.com/rfs-hybrid)
* **LinkedIn:** [Márcio Almeida](https://www.linkedin.com/in/marcioaugustoalmeida/)

<p align="center">
  <sub>⭐ If you found the documentation or code in these submodules helpful, consider starring the repo! ⭐</sub>
</p>
