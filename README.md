# Microprocessor simulator
My task was to make a visual microprocessor simulator with four registers (AX, BX, CX, DX). There are two addressing modes - register and immediate, 3 commands (ADD, SUB, MOV) and 10 interrupts. User is typing DEC numbers and program is automatically converting it to BIN. When user select one of the 10 interrupts it will block commands for 6 seconds and writing data to the registers temporary (eg. if user select Read screen resolution it will write number of X pixels to the AX and number of Y pixels to the BX). After 6 seconds everything returns to normal. User can run the command by F2 key too.
Moreover, at the left there is a command line - here it is automatically writing every command user do (with time). User can save his work to the file and load it.
![program window](https://raw.githubusercontent.com/Rayroth/Microprocessor-simulator/master/program.jpg)
