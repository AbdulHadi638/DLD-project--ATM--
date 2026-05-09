# DLD-project-
Designed a simplified ATM system using digital logic design and Finite State Machines (FSMs). Implemented PIN verification, transaction processing, and balance display using logic gates, flip-flops, multiplexers, and 7-segment displays. Simulated core ATM operations with automated state transitions.

The project demonstrates the practical implementation of sequential and combinational logic circuits in a real-world application.

---

## Features
- Power ON initialization state
- 4-bit PIN entry and verification
- Withdrawal/Deposit amount selection
- Balance update and display
- Error indication for incorrect PIN
- Automatic state transitions using FSM logic

---

## Components Used
- Logic Gates (AND, OR, NOT)
- Flip-Flops
- Multiplexers
- Counters (Optional)
- 7-Segment Display
- BCD to 7-Segment Decoder (7447)
- Push Buttons / Switches
- 555 Timer (Clock Pulse Generator)

---

## Working Principle
The ATM system operates using a Finite State Machine (FSM) implemented with flip-flops and digital logic circuits.

1. The system starts in an idle state waiting for user input.
2. The user enters a 4-bit PIN through switches.
3. The PIN is verified using combinational logic gates.
4. If the PIN is correct, the system proceeds to transaction processing.
5. The selected withdrawal/deposit amount is processed using multiplexers.
6. The updated balance is displayed using a 7-segment display and BCD-to-7-segment decoder.
7. A 555 timer generates clock pulses for proper state transitions.
8. After transaction completion, the system resets to the idle state.

---

## Concepts Applied
- Finite State Machines (FSMs)
- Sequential Logic Design
- Combinational Logic Design
- State Transition Control
- Digital Circuit Integration

---

## Applications
- ATM workflow simulation
- Educational DLD projects
- FSM-based system design
- Hardware logic implementation practice

---

## Project Objective
The objective of this project is to design and simulate a functional ATM system using digital logic components while understanding FSM-based control systems and sequential circuit design.


