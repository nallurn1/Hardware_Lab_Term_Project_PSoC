# Term Project PSoC

### Proposal
Throughout the semester there were countless projects completed utilizing the PSoC Creator IDE and Cypress development kit. Such projects consisted of blinking LEDs, reading different push-button states, printing information to a light crystal display (LCD), and even using a 4x4 matrix keypad to display the respective characters. Utilizing all of the knowledge gained alongside some research our proposed term project is a memory game. Memory games can drastically improve brain function, whether that be improving one's visual recognition, attention to detail, or even concentration. By utilizing six pushbuttons and six LEDs the objective is to create levels of increasing user difficulty. This will be done by increasing the speed or the number of LEDs being used by blinking the LEDs in a random fashion and having the user select the corresponding push button in the correct order. As of now, the goal is to blink the LEDs, then create a delay in which the 7-segment display begins a 10-second countdown timer for the user to begin selecting the pushbuttons in the correct order. Depending on the results, a print statement will be generated on the LCD stating if the correct pattern was inputted or not. If time allows, audio will be implemented within this stage notifying the user of the success or failure of the level. A potential challenge could be asking the user whether or not they want to quit the game or continue to the next level through a microphone and using a natural language neural network to process their response. Otherwise, the user would be asked whether or not they want to quit the game or continue to the next using the pushbuttons and the LCD. It can be seen that there are various components that can be implemented, some being a 32L476GDISCOVERY board, a digital to analog converter, interrupt service routines, and more, but overall by the end of the semester the main focus will be to implement a functional memory game for users.

#### 100 Point System: 
* 70 points: Use of 32L476GDISCOVERY board
* 30 points: Digital to Analog Converter 
* 20 points: At least 10 lines (equivalent) of ‘C’ hand coded in assembly language, Seven-segment display, Three or more push-buttons, Appropriate use of interrupt service routine(s)

### References
[1] Cypress Semiconductor Corporation. “CY8CKIT-050 PSoC® 5 Development Kit Guide.” Cypress. 
[2] “INND-TS56 Series 0.56’ Through Hole Single Digit Display.” Inolux, Inolux Corporation, 12 July 2017. 
[3] Khatri, Pankaj. “Push Button LED Circuit.” Circuit Digest, 26 Jan. 2018, https://circuitdigest.com/electronic-circuits/push-button-led-circuit. 
[4] “Project 2 -Segment LED”, Pearlstein Larry , 4 August 2021. 
[5] “Project 3 – Character LCD & Switch Debouncing”, Pearlstein Larry , 23 September 2021. 

