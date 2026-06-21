# FPGA-Music-Tone-Generator
Overview

This project implements a digital music tone generator on the Basys3 FPGA development board using Verilog HDL. Musical notes are generated through frequency synthesis techniques and played through a piezo buzzer. User inputs are provided through onboard push buttons, and the system incorporates debounce logic to ensure reliable operation.

Features

- Digital music generation using Verilog HDL
- Clock division for frequency generation
- Push-button controlled note selection
- Debounce logic for stable input detection
- Piezo buzzer output for audio generation
- Hardware implementation on Basys3 FPGA

Hardware Used

- Basys3 FPGA Development Board
- Piezo Buzzer
- Push Buttons (on-board)

Software Used

- Xilinx Vivado
- Verilog HDL

Working Principle

The FPGA's system clock is divided to generate frequencies corresponding to musical notes. Push-button inputs are processed through debounce circuits to eliminate switch noise. Based on the selected input, the corresponding frequency signal is generated and applied to a piezo buzzer, producing audible musical tones.

Project Outcomes

- Successfully implemented a hardware-based music generation system.
- Demonstrated clock management and frequency synthesis techniques.
- Verified functionality on the Basys3 FPGA board.

Repository Contents

- Project Abstract
- Hardware Demonstration Images
- Project Documentation
