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
    - Program the board with a simple set of software which     blinks a LED
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
