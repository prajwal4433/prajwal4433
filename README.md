## 👋 Hello! Welcome to my Portfolio 

![PRAJWAL SHINDE](https://raw.githubusercontent.com/prajwal4433/prajwal4433/refs/heads/main/Screenshot%202025-07-14%20114110.png)


## 📌About Me

I am , an Embedded Systems trainee with strong programming skills in C, C++, Embedded C, and Data Structures. Currently training at Vector India, Hyderabad, I’m working extensively with microcontrollers like ARM7 (LPC2129/LPC2148), 8051 and gaining in-depth knowledge of embedded hardware and software integration.

My focus areas include real-time operating systems (RTOS), Linux-based development, and communication protocols such as CAN, SPI, I2C, and UART. I enjoy problem-solving and continuously seek to improve system efficiency and reliability. My dedication to learning and building practical solutions is driven by a passion for coding, electronics, and system interfacing.

I’m looking forward to contributing to innovative embedded technology projects and growing in a challenging, fast-paced environment that values creativity and technical depth.

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
## 💻 Tools & Technologies:

 - __Programming Languages:__ C, C++, Data Structures & Algorithms (DSA), Embedded C
 - __Microcontrollers:__ ARM (LPC2129 & LPC2148) and 8051(89S51 & 89C52)
 - __Operating Systems:__ Linux, Real-Time Operating System (RTOS)
 - __Developer Tools:__ Keil µVision, Proteus, Arduino IDE
 - __Communication Protocols:__ CAN, SPI, I2C, USB, UART
 - __Networking Protocols:__ TCP/IP

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
![Blue and White Modern Professional General Linkedin Banner (1)](https://github.com/user-attachments/assets/f2d83747-9329-4c00-ac32-117608b218d9)

## MAJOR PROJECTS 

__Module C, DSA, Embedded C, Linux, ARM7(LPC2148) & Protocols : ATM System Design with Database Integration__

__Objective:__ The main aim of this project is to develop a secure ATM system using RFID authentication and a PIN-based interface, with backend banking database integration implemented in C using data structures 

__Project Overview:__\
The system consists of two main components: \
__1. Front-End [Microcontroller (LPC2148) side]:__\
Acts like a real ATM interface:
 - RFID card reader to identify user
 - Keypad for PIN entry and transaction inputs
 - LCD display for menu and status messages
 - Communicates with backend PC via UART
 - Handles the ATM interface (LCD, keypad, RFID reader) 

__2. Back-End [PC (Linux) side Application in C]:__\
Simulates a banking system:
 - Stores user and transaction data using struct and file I/O
 - Receives commands via UART from MCU
 - Sends results and balance info back to MCU
 - Simulates a banking database using data structures and file handling 

__Learning Keys:__
 - RFID Integration with LPC2148: Learned to interface RFID module with ARM7 using UART and validate unique card IDs.
 - PIN Verification Logic: Developed logic for secure PIN entry, attempt limits, and error handling in embedded C.
 - 4x4 Keypad & LCD Interfacing: Implemented a user-friendly interface for menu navigation using keypad and 16x2 LCD.
 - Buzzer Alerts: Used buzzer feedback for invalid actions and transaction notifications.
 - UART Communication: Configured serial communication between LPC2148 and Linux PC using MAX232 IC.
 - Protocol Design: Designed a command-response protocol for reliable data exchange between ATM front-end and PC.
 - File Handling in C: Used text/binary file operations to store user data, transactions, and mini-statements persistently.
 - Dynamic Data Structures: Applied linked lists and structures to manage banking operations like mini-statements and transaction logs.
 - Menu-Driven Console Interface: Created user menus for testing and debugging PC-side operations via terminal.
 - Keil uVision & Flash Magic: Practiced embedded development cycle: code > compile > flash > test using LPC2148.
 - GCC & Linux Terminal Usage: Compiled and debugged C programs on Linux, improving command-line confidence.
 - Embedded-Desktop System Integration:  Understood complete flow of embedded system communicating with a software database.
 - Modular Code Architecture: Separated logic into reusable modules (RFID, keypad, LCD, UART, banking logic).
 - Debugging & Troubleshooting: Gained skills in tracing serial data issues, peripheral mismatches, and logical errors.
 - Real-Time Application Thinking: Developed understanding of real-world system behavior, user access security, and fault-tolerance.

__📁 View Project LPC2148: 🔗[Link](https://github.com/gopaldhanokar22/ATM_System_Design_with_Database_Integration_LPC2148/tree/main)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

## MINI PROJECTS 

__Module C & DSA : Student Database__

__Objective:__ Your app should be used for all elementary work of a database application such as Input Records, deletion of records, Display records, sort records, save , search record etc..

__Learning Keys:__
 - Applied modular programming by separating each functionality (add, delete, edit, search, etc.) into different .c files.
 - Used structures and structure pointers to manage complex student records efficiently.
 - Implemented singly linked list (SLL) for dynamic student record storage and manipulation.
 - Practiced Dynamic Memory Allocation (DMA) to manage memory at runtime for growing/shrinking records.
 - Designed a menu-driven interface for interactive and user-friendly operations.
 - Enforced unique Student ID validation to avoid duplicate entries in the database.
 - Implemented file handling in C to persist student data across sessions (save(), syncfile() etc.).
 - Developed sub-menu logic for editing, allowing modification of individual record fields.
 - Built and compiled the project using a Makefile, improving efficiency and maintainability.
 - Structured the project with clear code organization and proper header file usage (typedef, enum).
 - Strengthened understanding of real-time database concepts and logic building using system-level C programming.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Student_Database)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module C & DSA : Bank managment system__

__Objective:__ Developed a Banking Management System in C using structures, file handling, and linked lists to manage account creation, transactions, and data persistence through a menu-driven interface. Focused on modular programming and real-time data storage.

__Learning Keys:__
 - Designing structure-based applications.
 - Using structure within a structure for transaction tracking.
 - Implementing SLL (Singly Linked List) with structure pointers.
 - Applying Dynamic Memory Allocation (DMA)
 - Developing a file-based storage system (save/load features)
 - Creating modular code architecture.
 - Managing the project using Makefile and CLI tools.
 - Enhancing code quality with typedef, enum.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Bank_managment_system)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module C & DSA : Library Management System__

__Objective:__ Designed and implemented a Library Management System in C using structures, pointers, and singly linked lists. Supported book addition, listing, searching, sorting, and counting functionalities. Integrated file handling to retain data across sessions. Used modular programming with separate source files and a Makefile for compilation.

__Learning Keys:__
 - Applied modular programming by dividing functionality into separate .c files.
 - Used structures and structure pointers to manage book data efficiently.
 - Implemented singly linked list (SLL) for dynamic book record storage.
 - Practiced file handling in C to retain data between program executions.
 - Designed a menu-driven interface for user interaction.
 - Used Dynamic Memory Allocation (DMA) to manage data at runtime.
 - Built and managed the project using a Makefile for simplified compilation.
 - Gained understanding of code organization, debugging, and testing in a real-world project structure.
 - Enhanced logic-building and problem-solving through C-based system-level programming.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Library_Management_System/tree/main)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module C & DSA : Phone Book Application__

__Objective:__ Your project is to implement PHONE BOOK APP with options to save multiple numbers, address, gmail, and many more options as per requirement in single contact. And this app should be allow us to edit, remove, find the contacts from the phone book.

__Learning Keys:__
 - Applied modular programming by dividing functionalities into multiple .c and .h files.
 - Used structures and structure pointers to store and manage contact details like name, numbers, email, and address.
 - Implemented a singly linked list (SLL) for dynamic, runtime contact management.
 - Practiced file handling in C to enable persistent data storage across multiple app runs.
 - Developed a menu-driven user interface to interactively perform contact operations.
 - Used Dynamic Memory Allocation (DMA) (malloc, free) to handle variable-length contact records.
 - Automated the build process with a Makefile, improving code maintenance and compilation speed.
 - Strengthened knowledge of code structure, debugging, and modular testing in a real-world application.
 - Improved logic-building, problem-solving, and system-level programming in the C language.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Phone_Book_Application)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module C++ : Student Database using C++ Programming__

__Objective:__ Develop a menu-driven application to manage student records with functionalities like add, delete, display, edit, search, save, and reverse records.

__Learning Keys:__
 - Applied modular programming by separating functionality into multiple .cpp and .h files.
 - Used structure pointers and singly linked list (SLL) for dynamic student record management.
 - Implemented file handling using fstream to ensure data persistence across sessions.
 - Designed a menu-driven interface for user-friendly interaction with options like add, delete, search, edit, and save.
 - Enforced unique Student ID validation to maintain database integrity.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Student_Data_base_cpp)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module C++ : Bank Managment System Using C++__

__Objective:__ Develop a menu-driven banking application to manage accounts with functionalities like account creation, deposits, withdrawals, transfers, balance inquiries, and transaction history tracking.

__Learning Keys:__
 - Implemented binary file handling for persistent storage using fstream, enabling automatic data load/save with RAII (constructor/destructor).
 - Used structure and class-based design for accounts and transactions, integrating vector for dynamic lists.
 - Applied enum class (TransactionType) to clearly categorize transaction types like DEPOSIT, WITHDRAW, and TRANSFER.
 - Designed a modular C++ project with well-organized source files (main.cpp, accounts.cpp, file_operations.cpp, banking.h).
 - Developed a menu-driven interface for user-friendly interaction supporting core banking operations and transaction tracking.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Bank_managment_system_using_cpp/tree/main)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module LINUX : Implementation of a Basic ls -l Command in C__

__Objective:__ The objective of this project is to develop a simplified version of the Unix ls -l command using C programming. The program aims to list the contents of a directory in a long-format style, displaying detailed information about each file, such as:
- File permissions (read/write/execute)
- Number of hard links
- File owner and group names
- File size in bytes
- Last modification time
- Filename

__Learning Keys:__
 - Directory Traversal: Learned how to use opendir() and readdir() to access and iterate through directory contents.
 - File Metadata Access: Used lstat() to retrieve file information like size, permissions, and timestamps.
 - Bitwise Permission Parsing: Understood how to extract file permission bits using bitwise operations on st_mode.
 - Owner and Group Resolution: Applied getpwuid() and getgrgid() to convert UID and GID to readable names.
 - Formatted Output: Practiced structuring output similar to ls -l using strftime() and formatted printing.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/my_ls_command/blob/main/README.md)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module LINUX : Chatting Application Using FIFO (Named Pipes) and IPC in C.__

__Objective:__ To design and implement a two-way communication system between two users using FIFO (Named Pipes), enabling them to chat in real-time through inter-process communication in a Linux environment.

__Learning Keys:__
- Inter-Process Communication (IPC): Understanding how named pipes (FIFOs) facilitate communication between unrelated processes.
- Process Management: Usage of fork() to create a child process for concurrent send-receive operations.
- File Operations in Linux: System calls: open(), read(), write(), close() with FIFO files.
- Signal Handling: Capturing and handling signals like SIGINT using signal() to clean up resources properly.
- Error Handling and Resource Cleanup: Avoiding resource leaks (e.g., dangling FIFOs, zombie processes) through proper cleanup and process management.
- Full-Duplex Communication Concept: Implementing bi-directional communication using two FIFOs (one for each direction).
- User Input/Output Handling: Using fgets() for safe input and fflush(stdout) for clean output display.
- Concurrency Basics: Understanding concurrent execution of send/receive through parent-child process splitting.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Mini_Project_Linux/tree/main)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__Module ARM :⏱️ The Time-Driven Access Control System.__

__Objective:__ To design a time-driven embedded access control system that displays real-time clock information, allows user-defined scheduling and editing via keypad, and grants access based on correct password entry within a predefined time window.

__Learning Keys:__
 - Real-Time Clock (RTC) Integration: Learn how to interface and manage real-time clocks (RTC) with microcontrollers, ensuring accurate time and date display on an LCD.
 - Keypad Interface: Understand how to interface a 4x4 matrix keypad to capture user input (password entry, RTC, and time editing) and handle debouncing for reliable signal detection.
 - Password-Based Access Control: Implement security features, such as checking user passwords and granting access based on time schedules and password correctness.
 - Interrupts and Event Handling: Use interrupts to trigger the editing mode for RTC and schedule times, which is a common technique in embedded systems to manage real-time inputs effectively.
 - LCD and User Interface: Learn to display real-time information (like date, time, and access status) on a 16x2 or 20x4 LCD and provide a user-friendly interface for password entry and settings modification.
 - System Integration: Integrate all components (LPC2148 microcontroller, RTC, LCD, Keypad, and Buzzer/LED) to build a complete access control system that works under scheduled conditions.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Time_Driven_Access_Control_System)__

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__👨‍💻 ARM7 LPC2148__

01. Title: Led Light blinking System Using LPC2148
02. Title: Traffic Light System Using LPC2148
03. Title: LED Binary Counter (1 to 255) Using LPC2148
04. Title: Electronic Dice Using LPC2148
05. Title: Switch-Controlled LED Using LPC2148
06. Title: Dual Switch-Controlled LED Using LPC2148
07. Title: 4 Switches Controlling 4 LEDs Using LPC2148
08. Title: 7-Segment Display Digit Test Using LPC2148
09. Title: Dual-Digit 7-Segment Multiplexed Display Test Using LPC2148
10. Title: Electronic Dice Simulation on 7-Segment Display Using LPC2148
11. Title: 60-Second Stopwatch Using LPC2148 and 7-Segment Display
12. Title: 60-Second Timer with Increment, Decrement, and Reset Using LPC2148
13. Title: LCD Functionality Test Using LPC2148
14. Title: Displaying Capital Alphabets with ASCII Values on 16x2 LCD
15. Title: Electronic Dice Simulation Using LCD Display
16. Title: Scrolling and Oscillating Message Display on LCD Using LPC2148
17. Title: Fastest Finger First Timer using LCD and LPC2148 Microcontroller
18. Title: Fastest Finger First System Using LPC2148 with 7-Segment Display
19. Title: 4x4 Matrix Keypad Interface and Display Test Using LPC2148 and LCD
20. Title: SMS-Style Text Entry Using 4x4 Keypad and LCD with LPC2148
21. Title: ADC Value Display on LCD using LPC2148
22. Title: Temperature Monitoring using LM35 Sensor and LPC2148 with LCD Display
23. Title: Distance Measurement using GP2D12 Sensor with LPC2148 and LCD Display
24. Title: DHT11 Interfacing with LPC2148 for Temperature and Humidity Monitoring
25. Title: 20x4 LCD Interface with LPC2148 for Multi-Format Data Display

__Learning Keys:__
 - GPIO Programming: Control digital inputs and outputs using microcontroller ports.
 - Bit Manipulation: Use bitwise operations to set, clear, and toggle specific bits.
 - Delay Control: Create precise timing delays for LED patterns and display effects.
 - Decision Logic: Apply if, else, and switch-case statements for input handling.
 - 7-Segment Interfacing: Drive numeric displays by mapping segment patterns.
 - Multiplexing Display: Control multi-digit displays efficiently with digit scanning.
 - LCD Interfacing: Initialize and operate 16x2 or 20x4 LCDs in 4-bit/8-bit modes.
 - Dynamic LCD Display: Show scrolling, blinking, and formatted text on screen.
 - Keypad Interfacing: Detect keypresses via row-column scanning and debounce logic.
 - ADC Interfacing: Read analog sensor data using internal ADC and display values.
 - Sensor Integration: Convert analog signals (e.g., LM35) into real-world units.
 - RTC Communication: Interface real-time clock modules using I2C for timekeeping.
 - Interrupt Handling: Use external interrupts for events like keypad edit or alerts.
 - Modular Design: Split large code into reusable functions and separate files.
 - Real-Time Embedded Systems: Build integrated projects simulating real-world systems.
   
__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/ARM7_LPC2148)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__👨‍💻 ARM7 LPC2129__
01. Title: Led Light blinking System Using LPC2129
02. Title: Traffic Light System Using LPC2129
03. Title: LED Binary Counter (1 to 255) Using LPC2129
04. Title: Electronic Dice Using LPC2129
05. Title: Switch-Controlled LED Using LPC2129
06. Title: Dual Switch-Controlled LED Using LPC2129
07. Title: 4 Switches Controlling 4 LEDs Using LPC2129
08. Title: 7-Segment Display Digit Test Using LPC2129
09. Title: Dual-Digit 7-Segment Multiplexed Display Test Using LPC2129
10. Title: Electronic Dice Simulation on 7-Segment Display Using LPC2129
11. Title: 60-Second Stopwatch Using LPC2129 and 7-Segment Display
12. Title: 60-Second Timer with Increment, Decrement, and Reset Using LPC2129
13. Title: LCD Functionality Test Using LPC2129
14. Title: Displaying Capital Alphabets with ASCII Values on 16x2 LCD
15. Title: Electronic Dice Simulation Using LCD Display
16. Title: Scrolling and Oscillating Message Display on LCD Using LPC2129
17. Title: Fastest Finger First Timer using LCD and LPC2129 Microcontroller
18. Title: Fastest Finger First System Using LPC2129 with 7-Segment Display
19. Title: 4x4 Matrix Keypad Interface and Display Test Using LPC2129 and LCD
20. Title: SMS-Style Text Entry Using 4x4 Keypad and LCD with LPC2129
21. Title: ADC Value Display on LCD using LPC2129
22. Title: Temperature Monitoring using LM35 Sensor and LPC2129 with LCD Display
23. Title: Distance Measurement using GP2D12 Sensor with LPC2129 and LCD Display
24. Title: DHT11 Interfacing with LPC2129 for Temperature and Humidity Monitoring
25. Title: 20x4 LCD Interface with LPC2129 for Multi-Format Data Display

__Learning Keys:__
 - GPIO Programming: Control digital inputs and outputs using microcontroller ports.
 - Bit Manipulation: Use bitwise operations to set, clear, and toggle specific bits.
 - Delay Control: Create precise timing delays for LED patterns and display effects.
 - Decision Logic: Apply if, else, and switch-case statements for input handling.
 - 7-Segment Interfacing: Drive numeric displays by mapping segment patterns.
 - Multiplexing Display: Control multi-digit displays efficiently with digit scanning.
 - LCD Interfacing: Initialize and operate 16x2 or 20x4 LCDs in 4-bit/8-bit modes.
 - Dynamic LCD Display: Show scrolling, blinking, and formatted text on screen.
 - Keypad Interfacing: Detect keypresses via row-column scanning and debounce logic.
 - ADC Interfacing: Read analog sensor data using internal ADC and display values.
 - Sensor Integration: Convert analog signals (e.g., LM35) into real-world units.
 - RTC Communication: Interface real-time clock modules using I2C for timekeeping.
 - Interrupt Handling: Use external interrupts for events like keypad edit or alerts.
 - Modular Design: Split large code into reusable functions and separate files.
 - Real-Time Embedded Systems: Build integrated projects simulating real-world systems.
   
__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/ARM7_LPC2129)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__👨‍💻 Microcontroller AT89S52(8051)__
1. Title: LED Blinking using AT89C51 Microcontroller
2. Title: Traffic Light Signal Simulation using AT89S52 Microcontroller
3. Title: Running LED Pattern Display using AT89S52 Microcontroller
4. Title: Random Dice Value Display on LEDs using AT89S52 Microcontroller
5. Title: Switch-Controlled LED Using AT89S52 Microcontroller
6. Title: Dual Switch-Controlled LED Using AT89S52 Microcontroller
7. Title: 4 Switches Controlling 4 LEDs Using AT89S52 Microcontroller
8. Title: Single Digit Up Counter using Common Anode 7-Segment Display with AT89S52
9. Title: Digital Clock Simulation on 7-Segment Display Using AT89S52
10. Title: Static 4-Digit Number Display Using AT89S52 and 7-Segment Display
11. Title: Floating Point Number Display on 4-Digit 7-Segment Using AT89S52
12. Title: Scrolling Message Display on 4-Digit 7-Segment Using AT89S52
13. Title: LCD 16*2 Data Display with CGRAM and Multiple Formats Using AT89S52
14. Title: Alphabet Display with ASCII Values on LCD Using AT89S52
15. Title: Electronic Dice Simulation on LCD Using AT89S52
16. Title: Oscillating Message Display on 16x2 LCD Using AT89S52
17. Title: Fastest Finger First Timer Display on LCD Using AT89S52
18. Title: 4x3 Matrix Keypad Interface with 16x2 LCD on AT89S52
19. Title: Name Entry System Using 4x4 Keypad and 16x2 LCD on AT89C51
20. Title: LCD 20*4 Data Display with CGRAM and Multiple Formats Using AT89S52
    
__Learning Keys:__
 - Understand GPIO pin configuration for input and output operations.
 - Learn how to implement software-based delay using loops.
 - Practice LED control through logical HIGH/LOW pin toggling.
 - Implement switch-based user input handling using polling.
 - Develop multiplexing techniques for 7-segment display interfacing.
 - Display numbers, characters, and messages using 16x2 and 20x4 LCDs.
 - Generate and display random values using logic and timer-based techniques.
 - Interface matrix keypad with microcontroller to detect keypresses.
 - Control cursor, create custom symbols, and format strings on LCD.
 - Design real-time logic flows like counters, clocks, and simulators.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/AT89S52_Microcontroller/tree/main)__
________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________


![2](https://github.com/user-attachments/assets/5d46e877-801a-4f53-9e75-7f5d3f50db25)


__🤖 1. ALL IN ONE ROBOT__

__Objective:__ The project focuses on developing a multifunctional robotic system designed for military applications. It integrates advanced features such as line following, obstacle avoidance, IR remote control, voice control, and mobile application-based control for versatile operation. Additionally, the robot incorporates specialized systems like landmine detection, RADAR technology, unwanted activities detection, fire detection, GPS navigation, and a solar panel power supply. The goal is to create a unified platform that enhances military operations by providing surveillance, reconnaissance, and tactical support while ensuring safety and sustainability.

__Learning Keys:__
 - Gained hands-on experience in embedded systems and sensor integration (IR, ultrasonic, GPS, fire, metal detection).
 - Implemented multi-control modes: voice, IR remote, mobile app, and autonomous navigation.
 - Developed military-grade features like landmine detection, RADAR, intruder alert, and fire detection.
 - Integrated GPS for real-time navigation and tracking.
 - Utilized solar panel for sustainable power management.
 - Strengthened skills in team collaboration, embedded C programming, and real-time system design.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/All_in_One_Robot)__

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__🗳️ 2. SMART ELECTRONIC VOTING MACHINE__

__Objective:__ Designed and implemented an electronic voting machine to replace traditional manual systems, ensuring secure, transparent, and efficient voting. The system uses an Arduino UNO as the central controller, allowing voters to select candidates via push buttons, with votes counted and displayed in real-time on a 16x2 LCD. A dedicated "result" button provides instant tally results, eliminating fraud and enhancing user experience.

__Learning Keys:__
 - Understood real-time embedded system design using Arduino UNO as the core controller.
 - Gained experience in push button interfacing and vote logic implementation.
 - Learned how to display dynamic data using a 16x2 LCD for live vote count and result display.
 - Implemented a fraud-proof voting mechanism with secure input handling and instant result generation.
 - Strengthened skills in Embedded C programming, hardware debugging, and user-centric design.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Smart_Electronic_Voting_Machine_Using_Arduino_Uno_R3)__

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__👨‍💻3. Ardiuno Nano__

01. Title: Traffic Light System Using Arduino nano
02. Title: Counter Control System Using Arduino nano
03. Title: Seven Segment Display - Counting 0 to 9 Using Arduino nano
04. Title: LCD Interfacing with Arduino nano
05. Title: Basic Calculator Using Arduino nano and Keypad with LCD Display
06. Title: DC Motor Control System Using Arduino nano
07. Title: Servo Motor Control Using Arduino nano
08. Title: Temperature Sensor (LM35) Interfacing with Arduino nano
09. Title: DHT11 Temperature and Humidity Sensor Interfacing with Arduino nano
10. Title: Fire Sensor Interfacing with Arduino nano
11. Title: LED Blinking with Arduino nano
12. Title: Sharp Distance Sensor Interfacing with Arduino nano
13. Title: Ultrasonic Sensor (HC-SR04) Interfacing with Arduino nano
14. Title: Vibration Sensor-Based LED Indicator Using SW-420 and Arduino nano
15. Title: Bi-Directional Counter Using IR Sensors and LCD

__Learning Keys:__
 - Developed strong hands-on experience in Arduino Nano programming and embedded C logic design.
 - Gained practical knowledge in sensor interfacing, including temperature (LM35, DHT11), fire, ultrasonic, vibration, and IR sensors.
 - Learned to control output devices like LEDs, LCDs, DC motors, servo motors, and 7-segment displays.
 - Implemented real-time applications like traffic control, counters, calculators, and fire alert systems.
 - Strengthened understanding of data display techniques using LCDs and 7-segment displays.
 - Mastered input handling using keypads, buttons, and IR-based triggers for interactive embedded systems.
 - Improved circuit designing, debugging, and logical thinking for real-world hardware integration.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Arduino_nano_v3)__

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__👨‍💻4. Ardiuno Uno__

01. Title: Traffic Light System Using Arduino uno 
02. Title: Counter Control System Using Arduino uno
03. Title: Seven Segment Display - Counting 0 to 9 Using Arduino uno
04. Title: LCD Interfacing with Arduino uno
05. Title: Basic Calculator Using Arduino uno and Keypad with LCD Display
06. Title: DC Motor Control System Using Arduino uno
07. Title: Servo Motor Control Using Arduino uno
08. Title: Temperature Sensor (LM35) Interfacing with Arduino uno
09. Title: DHT11 Temperature and Humidity Sensor Interfacing with Arduino uno
10. Title: Fire Sensor Interfacing with Arduino uno
11. Title: LED Blinking with Arduino uno
12. Title: Sharp Distance Sensor Interfacing with Arduino uno
13. Title: Ultrasonic Sensor (HC-SR04) Interfacing with Arduino uno
14. Title: Vibration Sensor-Based LED Indicator Using SW-420 and Arduino uno
15. Title: Bi-Directional Counter Using IR Sensors and LCD

__Learning Keys:__
 - Developed strong hands-on experience in Arduino Uno programming and embedded C logic design.
 - Gained practical knowledge in sensor interfacing, including temperature (LM35, DHT11), fire, ultrasonic, vibration, and IR sensors.
 - Learned to control output devices like LEDs, LCDs, DC motors, servo motors, and 7-segment displays.
 - Implemented real-time applications like traffic control, counters, calculators, and fire alert systems.
 - Strengthened understanding of data display techniques using LCDs and 7-segment displays.
 - Mastered input handling using keypads, buttons, and IR-based triggers for interactive embedded systems.
 - Improved circuit designing, debugging, and logical thinking for real-world hardware integration.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Arduino_Uno_R3)__

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

__👨‍💻5. Microcontroller 8051__

01. Title: Traffic Light System Using Microcontroller 8051 
02. Title: Counter Control System Using Microcontroller 8051
03. Title: Seven Segment Display - Counting 0 to 9 Using Microcontroller 8051
04. Title: LCD Interfacing with Microcontroller 8051
05. Title: Basic Calculator Using Microcontroller 8051 and Keypad with LCD Display
06. Title: DC Motor Control System Using Microcontroller 8051
07. Title: Servo Motor Control Using Microcontroller 8051
08. Title: Temperature Sensor (LM35) Interfacing with Microcontroller 8051
09. Title: DHT11 Temperature and Humidity Sensor Interfacing with Microcontroller 8051
10. Title: Fire Sensor Interfacing with Microcontroller 8051
11. Title: LED Blinking with Microcontroller 8051
12. Title: Sharp Distance Sensor Interfacing with Microcontroller 8051
13. Title: Ultrasonic Sensor (HC-SR04) Interfacing with Microcontroller 8051
14. Title: Vibration Sensor-Based LED Indicator Using SW-420 and Microcontroller 8051
15. Title: Bi-Directional Counter Using IR Sensors and LCD

__Learning Keys:__
 - Gained hands-on experience with 8051 architecture, pin configuration, and register-level programming in Embedded C.
 - Mastered interfacing techniques for input and output peripherals including LCDs, 7-segment displays, keypads, and LEDs.
 - Developed real-time applications like traffic light systems, counters, calculators, and fire alert mechanisms.
 - Interfaced and processed data from sensors like LM35, DHT11, ultrasonic, vibration (SW-420), IR, and sharp distance sensors.
 - Built motor control systems for both DC and Servo motors, learning about PWM and port manipulation.
 - Understood the fundamentals of interrupt handling, delay generation, and bitwise operations for embedded control.
 - Improved circuit design, debugging skills, and low-level hardware interaction using Keil uVision and proteus simulations.

__📁 View Project: 🔗[Link](https://github.com/gopaldhanokar22/Microcontroller_8051)__

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

## 🌐 Let’s Connect!
📍 Location: Hyderabad \
📧 Email: gopaldhanokar22@gmail.com \
🔗 LinkedIn: https://www.linkedin.com/in/gopal-dhanokar-60b196216/ \
📦 GitHub: https://github.com/gopaldhanokar22 

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

## ✨ Final Words
Thank you for exploring my portfolio!

________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________________
