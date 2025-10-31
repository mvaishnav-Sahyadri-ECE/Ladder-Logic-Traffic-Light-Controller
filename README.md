# Ladder-Logic-Traffic-Light-Controller


# (OpenPLC)

This project is a basic traffic light controller implemented in Ladder Logic using OpenPLC Editor, targeting an Arduino or similar PLC-compatible device. It simulates a 3-color traffic signal sequence (Red, Yellow, Green) controlled by timers.

## Features

- Sequential cycling of Red, Yellow, and Green lights with adjustable timers.
- Uses TON (On-Delay Timer) and TP (Pulse Timer) instructions for precise timing control.
- Implements mutual exclusivity so that only one light is ON at a time.
- Simple input control to start or stop the sequence.
- Suitable for beginners learning PLC ladder programming and timing concepts.
- Designed for a single LED output per color connected through a resistor.

## Software Used

#### OpenPLC

  
## Ladder Logic Overview

- Four TON/TP timers control the timing of each light phase.
- Logic ensures proper sequencing: Red → Green → Yellow → Red.
- Memory bit `M0` manages one part of the sequencing logic.
- Input bit `INPUT` to enable/disable the traffic light cycle.

## How to Use

1. Open the project in OpenPLC Editor.
2. Map I/O pins to your hardware setup.
3. Modify timer values as needed to adjust light durations.
4. Upload to Arduino or run in OpenPLC Simulator for testing.
5. Monitor LED outputs to observe traffic light sequence.

## Example Timings

| Light  | Duration  |
|--------|-----------|
| Red    | 8 seconds |
| Green  | 5 seconds |
| Yellow | 4 seconds |

#### Diagram Logic

<img width="1205" height="798" alt="Screenshot 2025-09-19 172207" src="https://github.com/user-attachments/assets/28670605-e860-4817-b915-4a8a028728f8" />



## Demo

https://github.com/user-attachments/assets/da2894ac-341b-4f2f-8085-a2e66f098470

## Team Member 

[Pranith-Kumar](https://github.com/Pranith-Kumar-18?tab=repositories)
