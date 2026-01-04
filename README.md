# Hi, I’m Linus Kundur-Zourntos

I’m a systems-focused engineering student with a strong interest in **systems security**, **binary exploitation**, and **low-level software design**.  
My work centers on understanding how software fails at the lowest levels and how to design systems that are harder to break.

Most of what I build and analyze is in **C, C++, and assembly**, with an emphasis on:
- memory safety and allocator internals
- binary exploitation primitives (stack/heap overflows, UAF, control-data corruption)
- OS and hardware–software security mechanisms
- exploit mitigation design (canaries, quarantines, W^X, resource limits.
- practical exploit techniques and mitigations
- CPU microarchitecture (5-stage pipelined processor design, hazards, control/data paths)

---

## 🔧 Current Focus
- Binary exploitation fundamentals, with an emphasis on heap and stack misuse
- Designing and analyzing memory allocators for security and robustness
- Building low-level systems software in C/C++ (shells, runtimes, execution models)
- Understanding calling conventions, ABIs, and program behavior at the assembly level
- Exploring exploit mitigations across software and hardware (canaries, W^X, sandboxing)
- Studying CPU microarchitecture and its interaction with software security

---

## 📁 Selected Projects
- **AURION-5** — A softcore 5-stage pipelined processor implementing the classic IF/ID/EX/MEM/WB pipeline, with hazard detection and control/data path design explored through simulation and testing.

- **shsh** — A command-line shell implemented in C supporting built-in and external commands, input/output redirection, and Unix process execution via fork/exec.

- **Custom Heap Allocator** — A basic dynamic memory allocator implementing `malloc` and `free`, with explicit free lists and coalescing to manage heap memory.

- **Pong (Computer Opponent)** — A Pong game where the player competes against an computer-controlled paddle that tracks and intercepts the ball, demonstrating real-time game logic and control flow.

---

## 🧠 What I Care About
- Learning systems deeply by building and breaking them
- Developing a strong mental model of vulnerabilities and why they occur
- Understanding exploitation at the level of memory layout, control flow, and ABI behavior
- Building systems software (allocators, shells, processors) as a way to study how real systems work

---

## 📫 Contact
If you’re interested in systems security, low-level engineering, or research-oriented projects, feel free to reach out.

