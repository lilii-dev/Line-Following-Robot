Line Following Robot

A Raspberry Pi-based line-following robot built using the YB PCB Car and IR tracking sensors.

About the Project

I built this project using a YB PCB Car controlled by a Raspberry Pi. The robot uses IR sensors to detect and follow a line, while an additional sensor allows the robot to stop when a specific condition is detected.

The project focuses on sensor-based movement, motor control, and autonomous robot behavior.

Hardware

- Raspberry Pi
- YB PCB Car
- 3 IR sensors
- DC motors

Software

- Python
- Raspberry Pi GPIO
- YB_Pcb_Car library

Features

- Line following using two IR sensors
- Automatic movement and steering
- Additional stop sensor
- Left and right spinning
- Forward movement
- Real-time sensor value output

How It Works

The robot continuously reads the values from its IR sensors.

- When both tracking sensors detect the line, the robot moves forward.
- When only one sensor detects the line, the robot adjusts its direction.
- When the additional left sensor detects the stop condition, the robot stops.

The program also includes functions for moving forward and spinning left or right.

What I Learned

Through this project, I learned more about reading sensors with Raspberry Pi GPIO, controlling motors, implementing line-following logic, and creating autonomous robot behaviors using Python.

Future Improvements

- Add more advanced line-following algorithms
- Improve turning accuracy
- Add obstacle detection
- Implement maze-solving algorithms
- Optimize movement speed and sensor response
