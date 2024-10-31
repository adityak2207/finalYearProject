# BrailloComm: A Braille Integrated Communication Software

**Authors**:  
Aditya K, Mohammed Yunus, Basit Reshi, Aakash V, Dr. Chaitra H V  
**Institution**: Nitte Meenakshi Institute of Technology, Bengaluru, India  

## Overview

BrailloComm is a cost-effective, refreshable braille display model designed to enhance accessibility for visually impaired individuals. Using a combination of Arduino-UNO and micro servo motors, the device translates text to braille patterns, making it a portable and user-friendly option for visually impaired users to read and navigate text. 

## Motivation

The visually impaired population is often underserved by modern technological advancements. While braille technology has evolved, current solutions are often costly and less portable. Our project aims to address this gap by developing an affordable, efficient braille display using compact and lightweight materials.

## Key Features

- **Low-Cost Design**: By using micro servos, the device reduces the cost of braille displays by nearly 30%.
- **Portability**: Designed to be lightweight and small, it can easily fit into a bag or be carried.
- **Ease of Use**: Minimalistic hardware design allows for easy operation and maintenance.
- **Voice-to-Braille Conversion**: Uses Google Speech to Text API to convert spoken input into braille patterns.

## Hardware Components

- **Arduino UNO**: Main processing unit
- **Raspberry Pi**: Used for speech-to-text conversion
- **SG90 Micro Servos**: Serves as braille pattern actuators
- **LiPo Battery**: Portable power source

## Software Implementation

The device uses Python for the speech-to-text conversion and Arduino to control the servos. Text characters are translated into corresponding braille patterns and displayed on the braille cell via the micro servos.

## Results and Analysis

BrailloComm’s performance was validated through:
- **Readability Tests**: Demonstrated high accuracy in character recognition.
- **Cost Analysis**: Showed a significant reduction in cost compared to traditional braille displays.
- **Portability Assessment**: Lightweight design proved convenient for everyday use.

## Future Work

Potential improvements include integrating ultrasonic or touch-sensitive sensors to enhance interactivity and functionality.


Thank you for your interest in BrailloComm! We hope this project contributes meaningfully to braille technology accessibility.
