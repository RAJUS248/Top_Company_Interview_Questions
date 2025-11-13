# 🧠 Top Company Interview Questions – Evolution and Anatomy of Computers

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

| Generation | Technology Used | Example | Key Advantages |
|-------------|----------------|----------|----------------|
| 1st (1940s–50s) | **Vacuum Tubes**      | ENIAC          | Very large, slow, high power use |
| 2nd (1950s–60s) | **Transistors**       | IBM 1401       | Smaller, faster, more reliable |
| 3rd (1960s–70s) | **Integrated Circuits (ICs)**| IBM 360 | Compact, cheaper, less heat |
| 4th (1970s–80s) | **Microprocessors**   | Intel 4004     | Powerful, personal computers born |
| 5th (Present)   | **AI-based Systems**  | Quantum/AI PCs | Intelligent, parallel processing |

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

| Memory Type | Speed   | Volatility  | Purpose |
|-------------|---------|-------------|----------|
| **Cache**   | Fastest | Volatile    | Stores frequently used data for CPU |
| **RAM**     | Fast    | Volatile    | Temporary storage for running programs |
| **ROM**     | Slow    | Non-volatile| Stores BIOS/Firmware permanently |

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

| Feature | HDD | SSD |
|----------|-----|-----|
| Data Storage | Magnetic disks | Flash memory chips |
| Moving Parts | Yes (spinning disks) | No |
| Speed | Slower | Much faster |
| Noise | Noisy | Silent |

💡 SSDs are faster because they use **electronic circuits** (no mechanical movement).

---

### **8. What happens in the system when you run a software program (from double-click to execution)?**  
**(Microsoft - 2023)**

1. You double-click → OS loads program into RAM.  
2. CPU fetches instructions.  
3. OS allocates memory and resources.  
4. Program executes step by step via CPU.  
5. Output shown on the screen.

---

### **9. Explain the function of a motherboard in a computer. What components are directly mounted or connected to it?**  
**(Wipro - 2023)**

- **Motherboard:** Main circuit board that connects all components.  
- **Connected Components:**  
  - CPU  
  - RAM slots  
  - Storage (HDD/SSD)  
  - GPU (Graphics Card)  
  - Power supply, USB, network ports  

💡 Acts as the **communication backbone** of the computer.

---

### **10. What is the duty of RAM when a program is running? Why does performance drop when RAM usage exceeds capacity?**  
**(Flipkart - 2022)**

- **RAM’s Duty:** Holds data and instructions for running programs.  
- **When RAM is full:** System uses slow disk space (swap file) → performance drops drastically.

---

### **11. What is a graphics card (GPU), and how does it differ from a CPU in architecture and workload type?**  
**(NVIDIA - 2023)**

- **GPU (Graphics Processing Unit):** Designed for **parallel tasks** like rendering images or AI training.  
- **CPU:** Handles general tasks one by one (sequential).  

💡 GPU has **thousands of smaller cores**, CPU has **few powerful cores**.

---

### **12. Why is a good graphics card essential for gaming, AI/ML, or video editing tasks?**  
**(Amazon - 2024)**

Because these tasks need:
- **High-speed parallel processing**
- **Real-time graphics rendering**
- **Handling large data sets**  

💡 Example: AI models train faster using GPUs than CPUs.

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

- OS manages **CPU scheduling**, **memory allocation**, and **I/O devices**.  
- It ensures multiple programs share resources **without conflict**.  
💡 Example: While watching a video, OS handles sound, graphics, and network together smoothly.

---

### **15. How can you view system processes and CPU usage on Windows and Linux? Name equivalent commands/tools.**  
**(Accenture - 2023)**

| Platform | Tool/Command |
|-----------|---------------|
| **Windows** | Task Manager (`Ctrl + Shift + Esc`) |
| **Linux** | `top` or `htop` commands |

---

### **16. What is the role of the BIOS/UEFI during computer startup, and how does it locate the operating system?**  
**(Infosys - 2024)**

- **BIOS/UEFI:** Firmware that starts when you power on the computer.  
**Steps:**  
1. Performs POST (Power-On Self Test).  
2. Checks hardware.  
3. Finds bootable device (HDD/SSD).  
4. Loads OS into memory.

---

### **17. Define firmware. How does it differ from software and hardware? Give an example.**  
**(TCS - 2022)**

- **Firmware:** A small program stored in hardware that controls basic device operations.  
- **Difference:**  
  - Hardware → Physical parts  
  - Firmware → Semi-permanent control code  
  - Software → Easily changeable application code  

**Example:** BIOS in a computer, firmware in a router or washing machine.
