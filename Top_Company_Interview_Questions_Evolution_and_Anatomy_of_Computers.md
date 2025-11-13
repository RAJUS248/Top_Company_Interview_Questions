# Recreate the markdown file with corrected tables and improved formatting
md_content = """# 🧠 Top Company Interview Questions – Evolution and Anatomy of Computers

---

### **1. Explain the difference between general-purpose and specific-purpose computers with examples.**  
**(TCS - 2023)**

- **General-purpose computers:**  
  Designed to perform multiple tasks.  
  👉 *Examples:* Desktop PCs, Laptops.  
  - Can run Word, Excel, games, browsers, etc.

- **Specific-purpose computers:**  
  Designed to perform one specific task.  
  👉 *Examples:* ATM machines, washing machine controllers, flight control systems.

---

### **2. How did computers evolve from vacuum tubes to microprocessors? Mention key advantages at each stage.**  
**(Infosys - 2022)**

| Generation       | Time Period     | Technology Used                  | Example    | Key Advantages                             |
|------------------|-----------------|----------------------------------|------------|--------------------------------------------|
| 1st              | 1940s–50s       | Vacuum Tubes                     | ENIAC      | Very large, slow, high power consumption    |
| 2nd              | 1950s–60s       | Transistors                      | IBM 1401   | Smaller, faster, more reliable              |
| 3rd              | 1960s–70s       | Integrated Circuits (ICs)        | IBM 360    | More compact, cheaper, less heat            |
| 4th              | 1970s–80s       | Microprocessors                  | Intel 4004 | Personal computers become possible          |
| 5th (present)    | 1990s–present   | AI systems / Parallel computers  | Modern AI/Quantum prototypes | Intelligent computing, parallel processing |

---

### **3. Define the main components of a computer system and explain how they interact to execute a program.**  
**(Capgemini - 2022)**

**Main Components:**
1. **Input Unit:** Accepts data (keyboard, mouse).  
2. **CPU:** Processes data (ALU + CU + Registers).  
3. **Memory Unit:** Stores data (RAM, ROM).  
4. **Output Unit:** Displays results (monitor, printer).  

**Interaction:**  
Input → CPU processes using Memory → Output.  
Example: You type a sum → CPU calculates → Monitor shows result.

---

### **4. What is the role of the CPU, and how do its components (ALU, CU, Registers) coordinate during instruction execution?**  
**(Amazon - 2023)**

- **CPU (Central Processing Unit):** The brain of the computer.  
- **ALU (Arithmetic Logic Unit):** Performs calculations and logic.  
- **CU (Control Unit):** Directs the flow of data and instructions.  
- **Registers:** Small, fast memory inside CPU for quick data storage.

**Process:**  
CU fetches instruction → ALU executes → Result stored in Registers → Sent to memory/output.

---

### **5. How does RAM differ from Cache memory and ROM in terms of access speed, volatility, and purpose?**  
**(Infosys - 2021)**

| Memory Type | Typical Access Speed | Volatility   | Main Purpose                                 |
|-------------|----------------------|--------------|-----------------------------------------------|
| Cache       | Fastest (few cycles) | Volatile     | Holds frequently used data/instructions close to the CPU for speed |
| RAM         | Fast (tens of cycles)| Volatile     | Holds running programs and active data        |
| ROM         | Slower (compared to RAM) | Non-volatile | Stores firmware/boot code that must persist across power cycles |

---

### **6. Why does a system need both primary memory (RAM) and secondary memory (HDD/SSD)?**  
**(TCS - 2024)**

- **RAM (Primary):** Fast, temporary memory for currently running programs.  
- **HDD/SSD (Secondary):** Permanent storage for files and OS.  

💡 Example:  
When you open a program → it loads from HDD to RAM → CPU runs it fast.

---

### **7. How does an SSD store data differently from an HDD, and why is it faster?**  
**(Accenture - 2022)**

| Feature         | Hard Disk Drive (HDD)         | Solid State Drive (SSD)           |
|-----------------|-------------------------------|-----------------------------------|
| Data Storage    | Magnetic platters              | NAND flash memory (electronic)    |
| Moving Parts    | Yes — spinning disks + head    | No — no moving parts              |
| Typical Speed   | Slower (mechanical seek time)  | Much faster (near-instant access) |
| Noise           | Produces audible noise         | Silent                            |
| Durability      | More sensitive to shock        | More shock-resistant              |

**Why faster:** SSDs have near-instant random access because they use electronic flash memory rather than waiting for mechanical parts to move.

---

### **8. What happens in the system when you run a software program (from double-click to execution)?**  
**(Microsoft - 2023)**

1. You double-click → OS loads program binary from disk into RAM.  
2. The OS loader links required libraries and allocates memory regions.  
3. CPU instruction fetch / decode / execute cycle begins for the program's threads.  
4. The OS handles scheduling, I/O, and system calls while the program runs.  
5. Output is produced (render to screen, write to disk, send network packets).

---

### **9. Explain the function of a motherboard in a computer. What components are directly mounted or connected to it?**  
**(Wipro - 2023)**

- **Motherboard:** Main circuit board that connects all components and provides power/data buses.  
- **Connected Components:**  
  - CPU (socket)  
  - RAM (DIMM slots)  
  - Storage (SATA / NVMe connectors)  
  - GPU (PCIe slot)  
  - Power connectors, USB headers, network ports, audio headers, chipset, CMOS battery

💡 Acts as the **communication backbone** of the computer.

---

### **10. What is the duty of RAM when a program is running? Why does performance drop when RAM usage exceeds capacity?**  
**(Flipkart - 2022)**

- **RAM’s Duty:** Holds data and instructions for running programs and active OS structures.  
- **When RAM is full:** The OS uses slower secondary storage as "swap" or "page file", causing large slowdowns (disk I/O is much slower than RAM).

---

### **11. What is a graphics card (GPU), and how does it differ from a CPU in architecture and workload type?**  
**(NVIDIA - 2023)**

- **GPU (Graphics Processing Unit):** Designed for **parallel computations** (many simple cores). Ideal for graphics and matrix-heavy workloads (AI/ML).  
- **CPU:** Designed for low-latency sequential tasks with a few complex cores.

💡 GPU: thousands of smaller cores → great for parallelism.  
CPU: few powerful cores → great for single-threaded performance.

---

### **12. Why is a good graphics card essential for gaming, AI/ML, or video editing tasks?**  
**(Amazon - 2024)**

Because these tasks need:
- **High-speed parallel processing** (render frames, train models)
- **Large memory bandwidth** (textures, tensors)
- **Specialized hardware** (e.g., tensor cores for ML)

💡 Example: AI models train much faster on GPUs than on CPUs.

---

### **13. What are input devices and output devices? Explain their roles in the input-process-output cycle.**  
**(TCS - 2021)**

- **Input Devices:** Give data to computer (Keyboard, Mouse, Scanner).  
- **Output Devices:** Show results (Monitor, Printer).  

**Cycle:**  
Input → Process (CPU) → Output.

---

### **14. How does the operating system use hardware resources to execute software efficiently?**  
**(Google - 2024)**

- OS manages **CPU scheduling**, **memory allocation**, **I/O operations**, and **security**.  
- It ensures multiple programs run concurrently and resources are fairly allocated.

---

### **15. How can you view system processes and CPU usage on Windows and Linux? Name equivalent commands/tools.**  
**(Accenture - 2023)**

| Platform | Tool / Command | How to open / run |
|----------|----------------|--------------------|
| Windows  | **Task Manager** | Press `Ctrl + Shift + Esc` or right-click taskbar → Task Manager |
| Linux    | **top** / **htop** | Run `top` or `htop` in terminal (install `htop` if not present) |

*Example commands:*


