# How to Create a Minimalistic AR Glasses

## 1. Design the Hardware

### 1.1 Choose a Microdisplay

- The microdisplay is the component that will output the information to the user.
- OLED microdisplays are often used due to their high contrast and response time.
- Example: Sony ECX339A OLED Microdisplay.
- Note: The chosen microdisplay should be compatible with the chosen microcontroller.

### 1.2 Choose a Microcontroller

- Microcontrollers are mini computers on a chip consisting of a processor, memory, and input/output peripherals.
- Microcontrollers are used to control the operation of the microdisplay.
- Example: Teensy 4.0, known for its high performance and ease of use.
- Requires knowledge of C programming.
- Initial learning project often involves programming the microcontroller to blink an LED.
- Steps involved:
    - Set up the development environment.
    - Set up the microcontroller evaluation board.
    - Program the board with a simple set of software which blinks a LED&#8203;``oaicite:{"number":1,"metadata":{"title":"\n\tMicrocontroller Programming 101 - NXP Community\n","url":"https://community.nxp.com/t5/University-Programs-Knowledge/Microcontroller-Programming-101/ta-p/1105406","text":"Microcontroller Programming 101 \n\n# Getting Started with the Freescale Cup\n\n##  \n\n## How to achieve the goal of creating an autonomous vehicle that quickly navigates around a track?\n\nBefore continuing with this tutorial, students should take the time to choose which Freescale Microcontroller your team is going to use. The Introduction to Freescale Cup Training article has some details about how to choose your microcontroller. Although the concepts and end results are similar no matter which microcontroller you decide to utilize, much of the software implementation details will differ.\n\n##  \n\n## What is a Microcontroller?\n\nFor information on what a microcontroller is head to the microcontrollers article.\n\n##  \n\n## Getting Started - Learn to Program a microcontroller \n\nFirst off, you are going to need to know C programming. For a crash-course head to c-programming-for-embedded-systems.\n\nThe classic first application to learn how to program a microcontroller is to get through the process of Blinking an LED. This wiki contains a tutorial for each of the Cup microprocessors which simplifies the process of setting up the evaluation board, installing the Integrated Development Environment, and programming the board with a simple set of software which blinks a LED. The Blink a LED tutorial is the first of 4 tutorials designed to familiarize students with the process of designing a cup car.\n\nThese four tutorials will introduce students to many of the fundamentals of robotics, the software used to control the locomotion and sensors on an autonomous line following vehicle, and provide example code which help simplify the process of creating a competitive entry in the Freescale Cup.\n\n###  \n\n### Here is an outline of the Basic Microcontroller Programming Tutorial:\n\n  1. Read the microcontroller article \n  2. Choose a microcontroller \n  3. Set up the development environment \n  4. Set up the microcontroller evaluation board \n  5. Program A LED \n  6. move to the next tutorial","pub_date":null}}``&#8203;.
- Note: A specific guide for driving a microdisplay with a microcontroller is not readily available and would likely depend on the specific microdisplay and microcontroller being used.

### 1.3 Create a Mounting System

- The mounting system holds the microdisplay in place in front of the user's eyes.
- Can be attached to a pair of glasses or a headband.
- 3D printing can be used to create a custom mounting system.

## 2. Write the Software

### 2.1 Develop a User Interface

- The user interface should be simple and easy to read.
- As per your request, the UI could resemble a green terminal font.
- Note: The specifics of how to develop the user interface would depend on the chosen microcontroller and microdisplay.

### 2.2 Implement Text Input

- Text input can be accomplished via voice recognition, a connected keyboard, or a gesture-based system.
- Note: The specifics of how to implement text input would depend on the chosen input method.

## 3. Assemble and Test the Glasses

- Once the hardware is designed and the software is written, assemble the glasses.
- Test the glasses to ensure they are working as expected.
- Modify the hardware design or software as needed based on testing results.

## 4. Iterate and Improve

- Once the basic system is working, you can iterate and improve on the design.
- You might add additional features, improve the user interface, or refine the text input method.
