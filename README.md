# Hands-free-Tetris
## Introduction

Due to their versatile nature, using FPGAs for computer gaming applications is increasing day
by day. The use of strict logic, simple operation and appropriate programming difficulty, not only
lets us apply Digital System Design and coding concepts, but also proves to be a strong source
of entertainment.

Apart from coding for the FPGA to facilitate hosting a video game on an OLED like display, we
also plan to make our system more advanced by using Hand Gesture recognition for changing
your gaming moves instead of going for remote controls or other wired devices.
Hence, we are using a camera for video processing the gestures to literally give the user all the
control in their hands.

## Method:

### Hardware:

We will be using an FPGA board to contain the neural network model
responsible for gesture classification, the camera for capturing the video feed, and an
OLED screen to display the game. The game will be made using a Hardware Description
Language like Verilog, and the FPGA will bring the 3 modules of the project together.
### Software: 

We will build a small Tensorflow model to identify different poses of a
binarized image of a hand. The game will have around 5 controls, so the required variety
can easily be obtained from a binary image. The model will be made and trained on
Tensorflow, and the weights will be deployed onto the FPGA board.

## Expected Results:
The final apparatus will be able to identify different hand poses as different controls, and as a
result, we will be able to play the game AFK.
