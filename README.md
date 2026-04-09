# Phantom Power Detector

**Author:** Unnati Kuradkar  
**Affiliation:** MCA Student  
**Date:** April 2026  

## Abstract
The Phantom Power Detector is an intelligent system designed to monitor and detect unnecessary power consumption in electrical devices. Many devices consume “phantom” or standby power even when turned off, leading to wasted electricity and higher energy bills. This project uses sensors and microcontroller-based circuits to identify and alert users about such power usage in real-time, promoting energy efficiency and cost savings.  

## Introduction
Phantom power, also known as standby power, is the electricity consumed by electronic devices while they are switched off or in standby mode. It is a hidden source of energy wastage and increases household or industrial electricity costs. This project aims to develop a simple, real-time detection system to identify phantom power usage, enabling users to minimize unnecessary electricity consumption and improve energy efficiency.  

## Literature Review
Previous methods relied on manual measurement with multimeters or smart plugs to track energy consumption. While effective, these solutions are often expensive or inconvenient for continuous monitoring. Recent research highlights microcontroller-based detection systems with sensors as a cost-effective, accurate, and real-time alternative.  

## Methodology
1. **Power Monitoring:** The system continuously measures voltage and current of connected devices using sensors.  
2. **Detection Algorithm:** It calculates power consumption and identifies abnormal or standby power usage.  
3. **Alert System:** The system notifies users via LEDs, buzzers, or a digital display when phantom power is detected.  

This approach ensures easy identification and reduction of unnecessary energy usage.  

## Implementation
**Programming Languages:** C / Arduino IDE  
**Frameworks/Libraries:** Arduino Libraries for sensors and display  
**Tools:** Microcontroller (Arduino/ESP32), Current Sensor (ACS712), Voltage Sensor, Buzzer/LED for alerts  

## Results and Discussion
- Successfully detected phantom power in connected devices.  
- Alerts notify users instantly to unplug or turn off devices.  
- Can be implemented in households, offices, or factories for energy savings.  
 

## Limitations
- Limited to devices connected to the monitored circuit.  
- Accuracy depends on sensor calibration.  
- Cannot measure power in complex multi-phase systems without additional sensors.  

## Future Scope
- IoT integration for remote monitoring via mobile apps.  
- Data logging for energy usage analytics and cost estimation.  
- Integration with smart home systems for automatic power cut-off.  
- Expand to industrial-level monitoring for multiple circuits.  

## Conclusion
The Phantom Power Detector provides a simple and efficient solution for detecting and reducing standby power consumption. By promoting awareness of phantom energy usage, the system helps users save electricity, reduce costs, and contribute to energy conservation.  

## References
1. J. Doe, "Standby Power Consumption and Reduction Techniques," Energy Journal, 2019.  
2. A. Kumar, "Microcontroller-Based Power Monitoring Systems," IEEE, 2020.  
3. Arduino Documentation: [https://www.arduino.cc](https://www.arduino.cc)  
