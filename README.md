# Universal Display Driver for Arduino (LED, LCD, OLED)

##  Overview
This project implements a universal display driver using Arduino UNO that supports multiple display types including 7-segment LED, 16x2 LCD, and SSD1306 OLED using a single firmware system.

##  Key Features
- Supports multiple display types with one codebase
- Automatic display detection (OLED → LCD → LED)
- Modular and layered architecture
- Reduces code redundancy
- Easy to extend for future displays

##  Technologies Used
- Arduino UNO
- Embedded C / Arduino IDE
- I2C Communication
- GPIO Control

##  Hardware Components
- Arduino UNO
- 7-Segment Display
- 16x2 LCD (I2C)
- OLED (SSD1306)
- Breadboard & Jumper Wires

##  Working Principle
The system detects available display modules and automatically selects the appropriate display. A unified function allows displaying data without changing application logic.

##  Output
<img width="622" height="355" alt="image" src="https://github.com/user-attachments/assets/23d76ff6-0f9a-43d7-b10b-16686ac1b72e" />
<img width="641" height="358" alt="image" src="https://github.com/user-attachments/assets/c730267a-6a7f-497f-ab59-f9364e43921f" />
<img width="298" height="408" alt="image" src="https://github.com/user-attachments/assets/35f05575-3ced-47ee-addd-e379fa31d3b2" />

##  Author
Priyanshu Gupta
