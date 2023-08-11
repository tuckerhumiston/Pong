# Pong Game on FPGA using SystemVerilog

![zoomed_out_pong_rtl](https://github.com/tuckerhumiston/Pong/assets/128828000/9a1da67b-d9bc-4e87-b507-0a0e94c3b541)


## Introduction

This project is an implementation of the classic Pong game using SystemVerilog and targeted for the Intel Aterra DE0 FPGA board. It was developed as part of our Sequential Logic Systems class at The University of Maine.

## Features

- Two-player Pong game with a simple graphical interface.
- Real-time ball and paddle movement simulation.
- VGA output for display on an external monitor/TV.
- Responsive controls using FPGA board switches/buttons.
- Scorekeeping on the HEX LED display.

## Getting Started

1. **Clone the repository:**

  ```bash
   git clone https://github.com/yourusername/pong-fpga.git
   cd pong-fpga
  ```
2. **Compile and Synthesize Code**
3. **Upload code onto the FPGA board**

## How to Play

After getting started, each player will pick a side of the board. Players have control over two switches which control the up and down movement of the respective paddles. If the ball makes contact with the player's side of the screen, the other player will score a point.


## Contributors

- Tucker Humiston
- Roy Koneff
- Branson Waldrop

