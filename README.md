4-digit password lock, fully hardware.

Built this for a Digital Systems lab with 2 classmates. No Arduino, no code, just ICs on 3 breadboards.

How it works:
Code is 1 - 3 - 5 - 7 in order. Press 1, a flip-flop saves it and the 7-seg shows 1. Same for 3, then 5, then 7. Each step only works if the one before it is already set.
There are 10 buttons. The other 6 numbers are traps, press any of them and everything clears and you start over, red LED stays on.
Get all 4 right and red turns off, green turns on.

Parts: 74HC74 flip-flops, 7-seg decoders and displays, 74HC32 and 74HC04 for the reset logic, buttons, red/green LEDs.

Demo video is demo.mp4. Lab report is also here.
