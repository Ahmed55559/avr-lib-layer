

# AVR Lib Layer

A small collection of common C definitions and utilities used across my AVR embedded software projects.

## Contents

- `STD_TYPES.h` — Common fixed-width and project-level type definitions.
- `BIT_MATH.h` — Bit manipulation macros used for register-level programming.

## Purpose

This layer provides the basic building blocks shared by the AVR software stack.

It is intentionally lightweight and independent of any specific peripheral.

## Usage

Include the required header from the library layer in the driver or application that needs it.

```c
#include "STD_TYPES.h"
#include "BIT_MATH.h"
````

## Target

* AVR 8-bit microcontrollers
* C

## Project Stack

```text
Applications
     │
     ▼
HAL Drivers
     │
     ▼
MCAL Drivers
     │
     ▼
AVR Lib Layer
     │
     ▼
AVR Hardware
```

## Status

Complete.

This library layer was developed as part of my AVR embedded-systems development work.
