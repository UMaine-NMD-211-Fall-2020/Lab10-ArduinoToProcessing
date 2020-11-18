# Lab 10 - Arduino To Processing
Follow along with tutorials that discuss how to hook an arduino sensor up to processing

## Goals
By the end of this lab, you should understand how to get data from any of the Arduino sensors and use the serial port to transmit it to processing. Specifically, you should be able to 
- Understand how Arduino Serial port works
- Understand how to take physical input and convert it into serial data
- Understand how to transmit serial data to processing
- Understand how to fit the serial data to your processing sketch in a less than clunky manner

## Steps for Lab
0. Share final lanterns / progress if not final
  - Brief verbal overview of what's explained in detail in the videos & what should be learned through the exercises
1. Serial Communications on Arduino 
2. Potentiometers -> Serial Monitor on Arduino
3. Setting up Processing Sketch for  Serial Communications
4. Improving Processing Sketch Communications
5. *Extra* Analog Pong

## Resources useful for each section
1. Learn about the Serial port we've been using
- [NYU ITP's Introduction to Serial Communications](https://vimeo.com/channels/1494527/97518082)
- [NYU ITP's In depth explanation of how to understand what's happening over serial port](https://vimeo.com/channels/1494527/97519477) This video will make everything else make more sense in the long run, but might be a bit confusing at first. No worries if you don't understand it completely. 
2. Add Hardware to the Serial port, this time understanding why everything works
- [NYU ITP's Explanation of creating a Protocol to govern  how a device can understand the stream](https://vimeo.com/channels/1494527/97520383)
- [NYU ITP's explanation of how to control serial data via the potentiometer](https://vimeo.com/channels/1494527/97522438)
- [Overview of Potentiometers](https://www.build-electronic-circuits.com/potentiometer/) This is just one, feel free to use whatever helps you understand a potentiometer. Feel free to look back at the inputs lab for other options, or use your DVD. 
3. Processing & the Serial Port, the basic, clunky version. It works - that's it. It doesn't work well. 
- [NYU ITP's explanation of how to take that potentiometer setup from the last video and use it to control processing](https://vimeo.com/channels/1494527/97523914)
4. How to make better, smoother, control of graphics via arduino's serial port
- [NYU ITP's explanation of how to fit the Arduino input to smoother graphical action](https://vimeo.com/channels/1494527/97524853)

5. *Extra* [Analog Pong Tutorial by Sparfun](https://cdn.sparkfun.com/assets/resources/6/2/Analog_Pong_with_Processing.pdf) Just in case you want extra practice before making your game for Mike, think that this sort of control is useful for your game, or think you need extra lab credit. 

## To Turn in
1. Serial Communications on Arduino 
- In your own words, explain what is happening when Arduino communicates over the serial port. Why is it necessary? Why do we care about the baud rate? What agreements are being made through serial communication, and what are they between? Write a paragraph answering these questions.
2. Potentiometers -> Serial Monitor on Arduino
  - Electrical Diagram (or just explanation w/ sketches of how current flows through setup), Commented Code, Video documetation, and explanation of any problems you ran into/solutions of blink LED via serial monitor
  -  Electrical Diagram (or just explanation w/ sketches of how current flows through setup), Commented Code, Video or screenshot documetation, and explanation of any problems you ran into/solutions of using the potentiometer to change the output of the serial monitor
  - In each of these examples, which direction did information flow? What was the trigger, what was the output? Can you have multiple serial ports open at once? Why did we scale the range of the potentiometer's output?
3. Setting up Processing Sketch for  Serial Communications
- Explanation of how/ why potentiometer motion leads to motion on screen. Not just "because they are connected over serial port". Use more detail
- Commented Code, Explanation of any problems you ran into while trying to set this up, Video Documentation of results. List what do you notice can be improved
4. Improving Processing Sketch Communications
- Explanation of how to make ball fit across screen properly. Explanation of how to reduce latency. Explanation of why it matters which device initiates data transfer. 
- Commented Code, Explanation of any problems you ran into while trying to set this up, Video of your end result
- In your own words, what is the general theory of what you learned with this lab? How would this apply to transferring data from a sensor to your final project for Mike (the game)? Speculate specifically for your controller. Is there anything else you need to know about controlling over serial port to feel confident in your project? Implementation of serial control with your project sensor is not necessary. Make sure to ask whatever relates to these questions. 
5. *Extra* Analog Pong
- Commented Code
- Video of working Example
- List of trials you ran into in process & how you fixed them, notes about what isn't working if it's not working properly 


