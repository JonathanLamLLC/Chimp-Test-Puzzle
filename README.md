# Chimp-Test-Puzzle
Chimp-Test Puzzle created by Jerry Hu and I for ECE198 project. The code can be found in main.c under src folder.

# Operational Concept Description:
Our Chimp-Test Puzzle displays a randomized sequence of 12 numbers on a single-digit 7-segment LED display at a challenging pace for each number. The player must then input the same sequence of numbers on a 4x4 digital keypad to solve the puzzle. If the player’s inputs exactly match the order of numbers that was previously shown within a given time, multi-color LEDs will blink green to indicate the player has successfully completed the puzzle. If the player fails to input the correct sequence of numbers or runs out of time, all multi-color LEDs will display red to indicate the player has failed the puzzle.

# Project Elements:
1 Nucleo STM32 board, 1 breadboard, 1 7-segment LED display, 1 digital keypad, 1 multi-color LED, connecting wires, and an aluminum sheet to be cut and shaped into a bomb-defuser-like box. 

# Hardware:
  4 x 4 Digital Keypad: connect 8 consecutive wires from R1 to C4 with male connectors number 19-33 in CN 10 column.
  Specifically, R1 - CN10 num 19(Port C Pin 7), R2 - CN10 num 21(Port A Pin 9), R3 - CN10 num 23(Port A Pin 8), R4 - CN10 num 25(Port B Pin 10),  C1 - CN10 num 27(Port B Pin 4), C2 - CN10 num 29(Port B Pin 5), C3 - CN10 num 31(Port B Pin 3), C4 - CN10 num 33(Port A Pin 10). 
  Multicolor LEDs: Connect LED with the bread boards; Connect a current limiting resistor with each of the 3 non-common cathode pins; Use jump wires to connect the LED with the main board. Namely, non-common cathode of the red LED to D11, non-common cathode of the green LED to D12 and non-common cathode of the blue LED to D13, common cathode to GND.
  7-segment LED: Connect LED with the bread board, make sure every pin is in a separate line different from each others; Put a current limiting resistor at the ground pin and connect it to one of the rails, use a jumper wire to connect that rail to the ground pin of the main board;Use jump wires to connect other pins to the main board.

# Target Audience:
Our target audience also includes people who like to challenge themselves. The chimp-test puzzle is a great challenge to people’s working memory, suitable for those who have a competitive and self-challenging spirit.
