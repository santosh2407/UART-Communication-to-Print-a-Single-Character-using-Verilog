# UART Communication to Print a Single Character using Verilog
- UART, or universal asynchronous receiver-transmitter, is one of the most used device-to-device communication protocols. This article shows how to use UART as a hardware communication protocol by following the standard procedure. When properly configured, UART can work with many different types of serial protocols that involve transmitting and receiving serial data. In serial communication, data is transferred bit by bit using a single line or wire. In two-way communication, we use two wires for successful serial data transfer. Depending on the application and system requirements, serial communications needs less circuitry and wires, which reduces the cost of implementation.

<img width="585" alt="image" src="https://user-images.githubusercontent.com/99958597/230736540-8019dd26-548e-4d59-9f97-1434802e7ed9.png">


- The above figure shows that the two UART modules are directly communicating with eachother. 
- The two signals of each UART device are named:


  - Transmitter (Tx)
   
  - Receiver (Rx)
  
- The main purpose of a transmitter and receiver line for each device is to transmit and receive serial data intended for serial communication.

- In this project, I have used Verilog to construct a UART communication module that allows us to print a single alphabetic character. This project's primary objective is to realize how the UART communication protocol functions and how characters can be printed using UART.



# Tools used: 
- Xilinx Vivado or ModelSIM


# Reference
[Website](https://www.analog.com/en/analog-dialogue/articles/uart-a-hardware-communication-protocol.html#:~:text=By%20definition%2C%20UART%20is%20a,going%20to%20the%20receiving%20end/).
