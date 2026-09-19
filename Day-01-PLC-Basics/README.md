# Day 01 - PLC Basics

## What I learned

- What is a PLC?
- Basic PLC components
- Inputs and outputs
- PLC scan cycle

## Practical

Created my first PLC project in CODESYS.

## Goal

Understand the basic working of a PLC.

## Practical Task 1 - Switch and Lamp

### Objective
Turn ON the lamp when the switch is ON.

### Ladder Logic
Switch (NO) → Lamp

### Variables
- switch: BOOL
- lamp: BOOL

### Expected Output

| Switch | Lamp |
|---|---|
| FALSE | FALSE |
| TRUE | TRUE |

### Result
Successfully tested the program in CODESYS.
The lamp turns ON when the switch is TRUE.

### Learning
Learned how a normally-open contact controls an output coil in Ladder Logic.
