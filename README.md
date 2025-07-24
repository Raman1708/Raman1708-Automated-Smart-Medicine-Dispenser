# Automated Smart Medicine Dispenser
## Overview
The Automated Smart Medicine Dispenser is an Arduino-based device designed to simplify and ensure accurate medication management, especially for elderly users or those memory challenges. It features individually controlled compartments, visual and audible reminders, programmable schedules, and environmental monitoring to maintain optimal storage conditions.

## Motivation

Managing multiple medications on strict schedules poses challenges and stress—especially for seniors. Missed or incorrect doses can lead to health complications. This project automates dispensing, reduces human error, and promotes adherence, offering peace of mind to users and caregivers alike.

## Features

- Programmable Dispense Schedule

- Individual Compartments with servo-controlled lids

- Real-Time Clock (RTC) for precise timing

- Visual (LED) and Audible (Buzzer) reminders

- Temperature Monitoring to ensure proper storage

- Rechargeable Battery Power for portability

- Modular Design—adjustable number of compartments

## Hardware Specifications

- Microcontroller: ATmega328 @ 16 MHz, 5 V logic

- RTC Accuracy: ±2 ppm (DS3231)

- Servo Torque: ~1.8 kg·cm

- Buzzer Voltage: 12 V DC

- Battery Pack: 37 V nominal (10×3.7 V), capacity as per runtime requirement

- Operating Temperature Range: 0 °C – 50 °C

## Mechanical Assembly

### 1.Enclosure Preparation
  - Divide the box into compartments sized for daily doses.

  - Install servo motors beneath each lid section.

### 2.Mounting Components

  - Fix Arduino, RTC, and LCD onto the rear panel.

  - Secure battery pack and rocker switch inside.

### 3.Wiring Harness

  - Route servo signal wires and power lines neatly.

  - Connect temperature sensor to an analog input.

### 4.Cover Layer

  -Affix thin cardboard or acrylic lids onto servo output horns via gears.
