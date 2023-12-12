I have developed a Moore FSM (finite state machine) using Verilog, designed to act as a combination lock and implemented on an FPGA DE1-SoC board.

Functions:

The lock mechanism permits users to enter a password via four designated switches.
The lock remains secure until the precise password is entered.
Upon receiving the correct input sequence, coupled with the activation of the enter key, the doors will unlock.
Provided the current password is correctly entered, users have the option to establish a new password by pressing the change key, followed by their new chosen password.
Should the enter key be pressed twice in succession without the correct password, an alarm system will be triggered.
