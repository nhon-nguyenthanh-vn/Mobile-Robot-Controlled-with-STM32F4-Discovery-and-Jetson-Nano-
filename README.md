# Mobile-Robot-Controlled-with-STM32F4-Discovery-and-Jetson-Nano-
My code get data from Jetson through Image Processing and controlled a mobile robot which approach a fixed target by STM32F4 Discovery
Using Embedded Computer + camera + image processing, u can get the distance and angel deflection from your robot to the sample target. 
Send it to STM32F4, my communication protocol using this frame: 
"12.12 (5 byte distance) 0(1 sign byte) 06.07 (5 byte angel)"
sign byte 0 correspond to + angel and 1 to - angel.
