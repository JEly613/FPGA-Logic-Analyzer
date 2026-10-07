### Idea

Logic analyzer & oscilloscope with 4 digital channels and 2 analog channels processed with the Cmod A7 35-T FPGA board. The board uses a UART-USB bridge so the streaming rate is highly limited. 

The solution is to write incoming data to SRAM then slowly read it all off, giving a snapshot of input signal. Goal is to do this at 100MHz for digital input.

Currently designing analog front end for digital and analog channels. See sims and. calculations for more details.