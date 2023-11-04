# Quadruped Robot
Quadruped spider robots are sophisticated machines that mimic spider movements and
behavior by using four adaptable and flexible legs, enabling them to move and stay stable
even in tight spaces and difficult terrain. 
## INTRODUCTION
At the moment, mobile robots are gaining popularity. They are classified into three types
based on how they move :legged robots, wheeled robots, and tracked robots. The main
advantage of legged robots is that their legs can walk on uneven terrain while remaining
balanced
![image](https://github.com/Tansin9/spider-robot/assets/130788893/30cf3ad2-9b19-4918-a73d-d1bb18b491c9)

Legged robots have several advantages over wheeled robots, especially when traversing
rough or uneven terrain. While wheeled robots can only travel on flat surfaces, legged
robots can traverse complex and irregular terrain such as uneven surfaces or stairs.

## OBJECTIVE
The objective of this project, Quadruped Robot, is to design and develop a highly capable
and adaptable robot capable of mimicking spider movements and behaviour. This project
aims to build a machine that can navigate complex terrain, climb vertical surfaces, allowing it to access areas that humans or wheeled robots cannot.

## SYSTEM DEVELOPMENT
### Block Diagram of Spider Robot

![image](https://github.com/Tansin9/spider-robot/assets/130788893/37c1b3ac-b9f0-4b33-a02b-0f103a933ed2)


The above diagram gives us the perceptible idea of a Quadruped Robot. The block
diagram includes various components, including 18650 lithium-ion
battery, Arduino Uno microcontroller, MG-90 servo motors. The 18650 lithium-ion battery is used to power the robot,
providing a reliable and long-lasting power source. The Arduino Uno is the main
control unit of the robot, responsible for controlling the movement and behavior of
the robot using the MG-90 servo motors. These servo motors are used to actuate the
joints of the robot legs, allowing it to move in a quadrupedal manner. 

### HARDWARE DESIGN


###  POWER SUPPLY
  Because of its high energy density and rechargeable capabilities, the 18650
lithium-ion battery pack has grown in popularity as a power source for a variety of
electronic devices, including robotics. These batteries are small and powerful, making
them an excellent choice for applications that require a portable and efficient power
source. The 18650 batteries are made of lithium-ion cells, which can store a lot of energy
in a small package. This is due to lithium-ion's unique chemistry, which allows it to store
more energy than other types of batteries. In addition to their high energy density, these
batteries have a long cycle life and a low self-discharge rate, making them an effective
and long-lasting power source.
![image](https://github.com/Tansin9/spider-robot/assets/130788893/337f380b-0699-4eb7-9d71-8abbaf4c3eb0)



### Arduino UNO
A microcontroller is a small computer that is used to control the spider robot's
movements. It sends commands to the robot's actuators to produce the desired movements. The Arduino Uno is a popular
microcontroller board used in electronics projects such as robotics. The board is based on
the Atmega328P microcontroller and includes a variety of input/output pins for
connecting to sensors, actuators, and other components. The Arduino Uno's ease of use
and versatility are two of its main advantages. It has a simple programming language that
is simple to learn, making it suitable for both beginners and experienced users. The
Arduino Uno serves as the primary controller in this project, governing the robot's
movement. The servo motors that move the legs are connected to the Arduino board's
input/output pins, which send signals to the motors to move the legs in the desired
pattern.
![image](https://github.com/Tansin9/spider-robot/assets/130788893/4df883c7-9cc8-4205-af13-f41c34bbf553)



### Servo Motors
A servomotor is a rotary actuator or linear actuator that allows for precise control of
angular or linear position, velocity, and acceleration. It consists of a suitable motor
coupled to a sensor for position feedback. MG-90 servo motors are small, high-quality
servo motors that are commonly used in a variety of applications, including robotics, RC
cars, and drones. These motors are popular because of their compact size, high torque
output, and precise control. They are designed to be easy to use, with simple wiring and
plug-and-play compatibility with most microcontrollers. 

![image](https://github.com/Tansin9/spider-robot/assets/130788893/09a3fc11-e0d3-4a65-b217-5056a8af87f8)


### Mechanical Structure
The mechanical structure of a quadruped spider robot is a crucial aspect of its design, as
it determines the robot's movement capabilities and overall stability. The mechanical
structure of a quadruped spider robot consists of four legs, each of which is composed of
several segments connected by joints. These joints are typically actuated by servomotors,
which allow for precise control over the movement of the legs. The legs are attached to a
central body, which houses the control electronics, power source, and other components
of the robot. One of the key design considerations in the mechanical structure of a
quadruped spider robot is the placement of the legs. The legs are positioned in a way that
maximizes stability and maneuverability, while minimizing the risk of tipping over or
losing balance. Additionally, the length and shape of the legs can be adjusted to optimize
the robot's movement capabilities for specific tasks or environments. Acrylic is a type of
thermoplastic material that is lightweight, durable, and easy to work with. Similarly,
Wood is also used to create the framework for the spider robot. These qualities make it an
ideal choice for constructing the body parts of a quadruped spider robot. Additionally,
acrylic is easy to cut and shape using a variety of tools, including laser cutters, saws, and
drills. This makes it easy to create custom body parts that fit the specific needs of the
robot.
![image](https://github.com/Tansin9/spider-robot/assets/130788893/cdd16131-64c0-484e-aac8-1342a2b0cae6)


##  SOFTWARE DESIGN
The software design of the quadruped spider robot is a critical component that facilitates
the control of the robot's movement. The system uses an Arduino
Uno board executes commands that control the servo
motors.The software design involves several stages, including programming the Arduino Uno
board, developing a control algorithm that determines
the movement of the robot.The software design of the quadruped spider robot requires a deep understanding of
programming and control theory. It involves writing code in various programming
languages such as C, C++, or Python, depending on the application requirements. The
software design must also consider the power requirements of the system, as the use of
multiple servo motors can be power-hungry. With careful planning and implementation,
it is possible to create a stable and accurate control system that enables the robot to move
smoothly and efficiently.

### Software Algorithm
- At the start, initialize all the servo motors.

- Move the servo motors of the opposite legs, i.e. Front Left and Rear Right.

- Move the servo motors of the opposite legs i.e. Front Right and Rear Left.

- Send the appropriate signal to each servo motor through its PWM pin.

- Keep repeating steps 2 and 3 until the power is on.

![image](https://github.com/Tansin9/spider-robot/assets/130788893/c2093393-3c51-44b2-a4e2-a95ccb7b6956)


## Result
In conclusion, the project to build a small, agile, and adaptable robot capable of a variety
of applications—the quadruped spider robot—was successfully completed.  18650 Lithium-ion battery pack, Arduino Uno, MG-90 servo motors were just a few of the hardware elements used in the project.
