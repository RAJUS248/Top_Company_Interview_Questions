# 🧠 Top Company Interview Questions – Basics of Operating System

---

### **1. What is the main role of an Operating System in a computer system?**  
**(TCS - 2023)**  
**Answer:**  
The Operating System manages hardware and software resources. It acts as a bridge between the user and hardware, handling process management, memory allocation, file handling, and device communication.

---

### **2. How does a Desktop Operating System differ from a Mobile Operating System?**  
**(Wipro - 2022)**  

| Desktop OS | Mobile OS |
|------------|------------|
| Runs on PCs/laptops | Runs on smartphones/tablets |
| Supports heavy apps | Optimized for light apps |
| Keyboard + mouse | Touch interface |
| More RAM, multitasking | Limited RAM, strict memory control |

---

### **3. What happens if a program fails to free heap memory?**  
**(Amazon - 2023)**  
**Answer:**  
This causes a **memory leak**, leading to:  
- Increasing RAM usage  
- Slow performance  
- App/OS crash

---

### **4. What is the purpose of Device Manager, and how does it interact with drivers?**  
**(Infosys - 2023)**  
**Answer:**  
Device Manager shows all hardware devices. It interacts with **device drivers**, which help the OS communicate with hardware like printers, keyboards, and network cards.

---

### **5. How does the OS check memory availability before running an application?**  
**(TCS - 2024)**  
**Answer:**  
OS checks free RAM and compares it with the program’s requirement. If not enough, it may use **virtual memory**, delay launch, or show an error.

---

### **6. What are the main layers of an Operating System?**  
**(Amazon - 2023)**  

1. Hardware  
2. Kernel  
3. System Calls / APIs  
4. System Software  
5. Applications  

---

### **7. What are device drivers, and why are they necessary?**  
**(Wipro - 2022)**  
**Answer:**  
Drivers are small programs that allow the OS to talk to hardware. Without drivers, devices like printers, Wi-Fi, or USB devices cannot function.

---

### **8. Give two examples of input/output drivers and explain interaction.**  
**(Infosys - 2024)**  
**Answer:**  
- **Keyboard driver:** Sends keypress signals to OS.  
- **Printer driver:** Converts print commands into hardware instructions.  

Drivers translate OS requests into device-level operations.

---

### **9. What are shared resources in an OS, and how is fair access ensured?**  
**(TCS - 2021)**  
**Answer:**  
Shared resources: CPU, memory, disk, printers.  
OS ensures fairness using:  
- Scheduling algorithms  
- Locks and semaphores  
- Priority handling  

---

### **10. What are the building blocks of an OS and their role during startup?**  
**(Microsoft - 2023)**  
**Answer:**  

- **Hardware:** CPU, RAM, Disk  
- **BIOS/UEFI:** Performs hardware tests  
- **RAM:** Loads the OS for execution  

Startup sequence → Power ON → BIOS → Bootloader → OS in RAM

---

### **11. What is a bootloader and what happens in the boot sequence?**  
**(Accenture - 2023)**  
**Answer:**  
A bootloader loads the OS into RAM.  
Sequence:  
1. BIOS runs tests  
2. BIOS finds bootloader  
3. Bootloader loads OS kernel  
4. OS starts services  
5. Login screen shows

---

### **12. Where is the OS installed, and how is it loaded on power ON?**  
**(Infosys - 2022)**  
**Answer:**  
OS is installed in HDD/SSD. On power ON → BIOS runs → Bootloader loads OS → OS copied to RAM → CPU runs it.

---

### **13. What is the function of Task Manager (Windows) or Activity Monitor (macOS)?**  
**(Capgemini - 2022)**  
**Answer:**  
They show CPU, memory, disk usage, processes, and allow force-stopping apps.

---

### **14. Explain the difference between Stack and Heap memory.**  
**(Google - 2024)**  

| Stack | Heap |
|--------|--------|
| Fast memory | Slower |
| Stores local variables | Stores dynamic allocations |
| Managed automatically | Managed manually |
| Limited size | Larger area |

Example:  
`int x = 10;` → Stack  
`int* p = new int;` → Heap  

---
"""
