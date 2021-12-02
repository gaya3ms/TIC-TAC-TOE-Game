# TIC-TAC-TOE-Game
TIC TAC TOE Game designing on PCB using multiplexing concept with PIC 18 microcontroller

Programming Language: Embedded C, C++ Controller Technology: Mbed LPC 1768, PIC18FK22
• Simple 3x3 gaming Bord where each Place is electrically debounced with two other LEDs.
• Real time user Input from pushbuttons which also gives reset option with user display on computer.
• 30 Seconds time limits for input or automatic placement from controller.
• Secure setup of SPI communication between two Controller.

• Multiplexing allows to control many things with the little control aspects with the
  knowledge of electrical potential difference, this project allows user to play game
  with the real time experience. Each move played by user will make the specific LED
  on and rest will be switched off till second player their turn. +5v output from
  microcontroller with the suitable programming will assist the winning and losing of
  player.
• MBED LPC1768 was used to communicate between the two-controller system.
  MBED was used to gain an industrial experience of communicating between RTOS
  devices. User action was taken on the MBED side, and it will send the sentence and data
  values to the micro-controller, and it will take the particular action and will display the
  user action on the screen.
