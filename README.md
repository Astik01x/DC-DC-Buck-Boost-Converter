# 🏗 DC-DC Buck-Boost Converter Project

## Overview

This project involved designing and implementing an efficient model of a Buck-Boost Converter to provide a variable voltage supply in the range of 15-20 volts. The work was completed as part of a 4-member team from March 2024 to April 2024.

## Objectives

- Design a Buck-Boost Converter capable of handling a variable voltage supply range of 15-20 volts.
- Implement a Pulse Width Modulator (PWM) to control the output voltage with a variable duty cycle and switching frequency.
- Simulate the model using Simulink to analyze performance across different frequency ranges.
- Verify simulation results through practical hardware implementation.

## Implementation Details

### 1. **Buck-Boost Converter**

The Buck-Boost Converter is a type of DC-DC converter that can step up or step down the input voltage. This project focused on creating an efficient model of the Buck-Boost Converter with the following features:

- **Variable Voltage Supply**: Designed to operate within a range of 15-20 volts.
- **Pulse Width Modulation (PWM)**: Used to regulate the output voltage.

### 2. **Pulse Width Modulator (PWM)**

- **IC TL-494**: Used for generating PWM signals with variable duty cycles and switching frequencies.

### 3. **Simulation**

- **Software**: Simulink
- **Objective**: Simulate the converter's performance across specific frequency ranges to determine the discontinuous conduction mode frequency.
- **Verification**: Comparison of simulated results with actual hardware performance.

## IC TL-494

The **TL-494** is a popular integrated circuit used in pulse width modulation and power supply applications. Below are some details about the IC TL-494:

### 1. **Overview**

The TL-494 is a versatile PWM control IC designed for various applications, including DC-DC converters, motor control, and power supplies. It provides precise control over switching frequencies and duty cycles.

### 2. **Key Features**

- **Variable Duty Cycle**: Allows adjustment of the pulse width for precise control.
- **Switching Frequency**: Adjustable frequency range to suit different applications.
- **Integrated Circuits**: Combines multiple functions such as oscillators, comparators, and error amplifiers in a single package.

### 3. **Applications**

- **DC-DC Converters**: Used to generate stable and adjustable output voltages.
- **Motor Control**: Provides precise control over motor speed and direction.
- **Power Supplies**: Regulates output voltage and current in power supply circuits.

### 4. **Datasheet**

For more detailed specifications and application information, refer to the [TL-494 Datasheet](https://www.ti.com/product/TL494).

---

