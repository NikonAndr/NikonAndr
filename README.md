## 👋 Hi, I'm Andrii
🎓 2nd year student at Wrocław University of Science and Technology
💻 Major: Computer Systems in Automation
🚀 Currently looking for a summer internship (C++ / Embedded / Systems)

## About me
I'm a second-year engineering student focused on low-level programming, embedded systems, and performance-oriented developement.

Recently, I've been transitioning from hardware description languages (SystemVerilog) toward C++ and system-level programming.

I enjoy building things that are close to the hardware and understanding how systems work under the hood.

## ⚒️ My Projects
### UART + Register Model Verification
Developed a full **SystemVerilog UVM testbench**, including:  
* **UART Agent** with driver and monitor for sending and recieving data.
* **Test sequences**: random transaction generation, including error injection.
* **Register Model (RAL)**: two master/slave register blocks, reg2bus/bus2reg adapter integrated with UART agents.
* **Scoreboard and verification**: comparing transmitted/recieved data with register model, layered architecture (layering) support, verifying correct read/write operations.

**Outcome**: A complete testbench verification of UART communication and register model correctness under realistic conditions, with error handling and layered agent architecture.

### C++ CLI Downloader
* Implemented a command-line tool for downloading files over HTTP/HTTPS using libcurl
* Designed a modular architecture separating HTTP communication, download logic, and file handling
* Implemented streaming data processing to avoid full file buffering in memory
* Added basic progress tracking and handled binary file writing
Currently extending the project with additional features (e.g. improved error handling and
performance)

⭐ Thanks for visiting my profile!
