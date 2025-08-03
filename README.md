# Autonomous-Chess-Playing-Robotic-Arm
This project features a robotic arm that plays chess autonomously against a human opponent using computer vision and AI.

How It Works
Board Detection: A webcam captures the top view of the chessboard. Using OpenCV, the system identifies the board layout and detects the positions of all pieces.

Move Analysis: After detecting a player's move, the updated board state is passed to Stockfish, a powerful chess engine, which returns the best possible move.

Robotic Execution: The robotic arm picks and places the pieces to perform the AI's move with precision.

Hardware Used
4 DOF 3D-Printed Robotic Arm

MG996R Servo Motors

Stepper Motor (for base rotation)

L298N Motor Driver

Arduino Uno (for motor control)

 Software Stack
Python + OpenCV – for image processing and board tracking

Stockfish – to calculate optimal chess moves

Arduino IDE (C++) – to control the robotic arm via serial commands

 Features
Real-time visual tracking of chess pieces

Autonomous decision-making using AI

Smooth physical execution of moves using servo-based arm

Cost-effective and compact design using 3D printing
