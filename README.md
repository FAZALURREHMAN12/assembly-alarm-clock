# Assembly Language Alarm Clock

An x86 Assembly alarm clock project developed and tested in **emu8086**. The program demonstrates low-level programming concepts such as BIOS/DOS interrupts, register-level operations, time input handling, and real-mode execution inside an emulator environment.

## Preview

![Assembly Alarm Clock running in emu8086](screenshots/alarm-clock-emulator.png)

## Overview

This project simulates an alarm clock using x86 Assembly language. The program accepts alarm time input from the user, stores the values in memory, and checks time-related values through low-level control flow.

The project was built to practice how Assembly programs manage data, registers, memory variables, procedure calls, interrupts, and emulator-based execution.

## Features

- Alarm time input for hour, minute, and second values
- Time display and prompt handling inside the emulator console
- Use of Assembly variables for storing current time and alarm time
- Register-based data movement and comparison logic
- Procedure-based structure for cleaner Assembly code organization
- Runs inside the emu8086 emulator environment

## Tech Stack

| Area | Technology |
|---|---|
| Language | x86 Assembly |
| Emulator | emu8086 |
| Architecture | 16-bit real mode |
| Concepts | Registers, memory variables, interrupts, procedures |

## What this project demonstrates

- Working with low-level Assembly syntax
- Understanding CPU registers and memory handling
- Using interrupts for input/output behavior
- Writing structured Assembly code with procedures
- Debugging and stepping through code in emu8086
- Understanding how simple programs work closer to hardware level

## How to run

1. Install and open **emu8086**.
2. Clone or download this repository.
3. Open the `.asm` file in emu8086.
4. Click **Compile**.
5. Click **Emulate**.
6. Enter the required alarm time values when prompted.

## Project Structure

```text
assembly-alarm-clock/
├── alarm.asm
├── README.md
└──  alarm-clock-emulator.png
```

> Note: The Assembly source filename may differ depending on the version uploaded to the repository.

## Future Improvements

- Improve input validation for invalid time values
- Add clearer alarm trigger messages
- Add sound/beep behavior where supported by the emulator
- Improve code comments for easier understanding
- Add multiple alarm presets

## Author

**Fazal Ur Rehman**  
GitHub: [FAZALURREHMAN12](https://github.com/FAZALURREHMAN12)
