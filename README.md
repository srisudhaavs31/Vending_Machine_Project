# Vending_Machine_Project– Verilog Project
Verilog-based FSM vending machine that accepts ₹5/₹10 coins and dispenses products priced at ₹5, ₹10, and ₹20 with support for cancellation and change return.

This project implements a Finite State Machine (FSM)-based vending machine in Verilog. The system accepts coin inputs of ₹5 and ₹10 denominations and dispenses products priced at ₹5, ₹10, and ₹20. It supports product selection via input signals and includes functionality for cancellation with change return.

The FSM is modeled using five states (S0, S5, S10, S15, and S20) representing the accumulated balance. Transitions between these states are determined by the inserted coin values and user actions (selection or cancellation). The machine dispenses one of three products (PrA, PrB, PrC) based on the selected option and the current state. Unused balance is returned as change when appropriate or when the cancel input is triggered.

This project demonstrates practical application of Mealy-type FSM design and state-based control in digital systems using Verilog.

