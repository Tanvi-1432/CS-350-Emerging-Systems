# CS-350: Emerging Systems Architectures and Technologies

This repository contains two projects I completed for CS-350 at Southern New Hampshire University. Throughout this course, I worked with a Raspberry Pi to learn how software interacts with hardware components, including LEDs, buttons, sensors, and LCD displays.

## Project Artifacts

1. Smart Thermostat

For my final project, I developed a smart thermostat prototype using a Raspberry Pi. The system uses an AHT20 temperature sensor to monitor room temperature and allows users to switch between OFF, HEAT, and COOL modes. It also includes buttons to adjust the temperature set point, LEDs to indicate heating or cooling activity, and an LCD to display the current temperature and thermostat settings.

2. Morse Code State Machine

For this project, I created a Morse code system that uses LEDs to display messages through a series of dots and dashes. I implemented a state machine to control the LED sequences and used a button to switch between messages. The LCD also displays the selected message.

## Reflection

### Summarize the project and what problem it was solving.

The main goal of these projects was to develop software that could interact with physical hardware components. For the thermostat project, I needed to create a system that could monitor room temperature and respond based on the selected mode and temperature set point. The Morse code project focused on using a state machine to control LED patterns and handle user input without interrupting the current sequence.

### What did you do particularly well?

I think one thing I did well was troubleshooting problems as they came up. Since I was still getting familiar with the Raspberry Pi and working with physical components, I ran into a few issues with wiring and GPIO connections. Instead of changing everything at once, I tested individual components and worked through the problems until I figured out what was causing them. I also became more comfortable working with Python to control hardware.

### Where could you improve?

One area I could improve is planning out the hardware connections before starting the programming portion. I spent more time than I expected troubleshooting wiring issues that could have been avoided by double-checking the connections earlier. I would also like to improve how I organize and structure my code, especially as projects become more complex.

### What tools and/or resources are you adding to your support network?

This course introduced me to several tools and resources that I can continue using in future projects. I became more comfortable using the Raspberry Pi, GPIOZero, Python libraries for hardware communication, and SSH to access my Raspberry Pi remotely. I also learned how useful hardware documentation, pinout diagrams, and testing scripts can be when troubleshooting issues.

### What skills from this project will be particularly transferable to other projects and/or course work?

One of the biggest skills I gained was learning how to approach problems that involve both hardware and software. I also gained experience working with state machines, handling user input, reading sensor data, and debugging Python programs. These skills can be useful in future software development projects, especially those involving embedded systems, automation, or IoT devices.

### How did you make this project maintainable, readable, and adaptable?

I tried to keep the code organized by separating different functions, such as handling button inputs, controlling LEDs, and updating the LCD. Using a state machine also helped keep the logic organized because each state had a specific purpose. This makes the code easier to understand and allows changes to be made to individual components without having to rewrite the entire program.

## Conclusion

Overall, this course gave me a better understanding of how software and hardware work together. Before taking CS-350, most of my programming experience involved software applications, so working with physical components was a different experience. These projects helped me become more comfortable with embedded systems and gave me practical experience that I can build on in future projects.
