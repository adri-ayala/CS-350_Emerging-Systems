# CS-350_Emerging-Systems


## **Project Summary**
This project focused on developing a prototype smart thermostat for SysTec, a company exploring entry into the smart home market. The goal was to design and program a system that could sense temperature, display data, and control heating or cooling indicators using a Raspberry Pi. The thermostat reads temperature through an AHT20 sensor, displays the information on an LCD, and uses LEDs and buttons for user interaction. The prototype also simulates sending data to a cloud server through a serial connection, which represents the next phase of connecting the device to SysTec’s software.

This project solved the problem of creating a working foundation for a smart thermostat that can later be expanded to include Wi-Fi connectivity and cloud integration.

---

## **What I Did Well**
I did well in understanding the code and statemachines. The Python code successfully managed I2C communication with the temperature sensor, handled button inputs, and controlled LED behavior using PWM. I was also proud of the way the state machine controlled the thermostat’s modes and responded to real-time input. The design was consistent with embedded systems best practices and included modular, well-commented code.

---

## **Where I Could Improve**
I could improve on optimizing the code structure to handle timing and concurrency more efficiently. Throughout the course I had issues with the hardware which caused me to fall behind ocasionally. I plan to get better at time management so I can ask for help when I need it.

---

## **Tools and Resources Added to My Support Network**
Throughout this project, I became more confident using hardware-related Python libraries such as GPIOZero, Adafruit CircuitPython, and the adafruit_character_lcd package. I also learned more about using GitHub for version control and documentation. These tools will remain part of my workflow for future embedded projects. The Raspberry Pi development environment and datasheets for sensors and microcontrollers also became valuable resources for hardware integration and testing.

---

## **Transferable Skills**
The skills I developed in this project will apply to many other computer science and engineering projects. I improved my ability to interface software with hardware, analyze architecture performance, and understand the trade-offs between different embedded platforms. I also gained experience with I2C, UART, and GPIO peripherals, which are common across most microcontroller projects. These skills are directly transferable to IoT development, robotics, and real-time embedded control systems.

---

## **Maintainability, Readability, and Adaptability**
I made the project maintainable and readable by using clear variable names, organized classes, and consistent commenting throughout the code. The design is adaptable because each function is modular, allowing new features such as Wi-Fi connectivity or additional sensors to be added without rewriting major sections. The state machine pattern keeps the control logic simple and easy to modify if new thermostat modes or hardware components are introduced later.

Overall, this project not only demonstrated my understanding of embedded systems but also strengthened my ability to write software that bridges hardware and cloud functionality in a structured and scalable way.
