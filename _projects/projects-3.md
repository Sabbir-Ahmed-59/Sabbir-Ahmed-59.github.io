---
title: "Designing a Calculator Using 8051 Microcontroller"
excerpt: "Designed a calculator using the 8051 microcontroller to perform real-time arithmetic operations with inputs via a keypad and output displayed on an LCD.<br/><img src='/images/Micro_CKT.jpeg'>"
collection: projects
---

This project demonstrates the implementation of a basic calculator using an 8051 microcontroller. The calculator performs arithmetic operations—addition, subtraction, multiplication, and division. The inputs are provided through a 4x4 keypad, and results are displayed on an LCD screen.  

---
## Features

- **Arithmetic Operations:** Performs addition, subtraction, multiplication, and division of two numbers.  
- **Keypad Input:** User-friendly interface using a 4x4 keypad for input.  
- **LCD Display:** Results are displayed in real-time on a standard 16x2 LCD.  
- **Memory Utilization:** Stores inputs and results in dedicated memory locations within the microcontroller.  
- **Simulation and Coding:** Circuit designed in Proteus, and the code developed using MIDE-51 IDE.  

---
## Implementation Details  

### **8051 Microcontroller:**  
- Controls the keypad, processes inputs, executes arithmetic operations, and displays the output.  

### **Keypad Scanning:**  
- Continuously scans the 4x4 keypad matrix to detect pressed keys and identify inputs.  

### **LCD Integration:**  
- Displays inputs, operations, and results in ASCII format on a 16x2 LCD module.  

### **Proteus Simulation:**  
- Circuit simulated in Proteus software, ensuring proper functionality before hardware implementation.  

### **Code Compilation:**  
- Program written in Assembly language using MIDE-51 IDE, converted into a `.hex` file, and uploaded to the microcontroller.  

---
## Challenges Faced  

- Limited memory and 8-bit register size, restricting operations to values ≤ 255.  
- Difficulties in handling division outputs for numbers exceeding the 8-bit range.  
- Converting large hexadecimal outputs to decimal format.  

---
## Future Prospects  

- Expanding functionality to handle floating-point operations.  
- Optimizing the algorithm to support larger numbers and advanced operations.  
- Transitioning to a more advanced microcontroller for enhanced capabilities.  

---
## Project Report  

[Download the full project report (PDF)](/files/Microcontroller_Project.pdf)  

---  
