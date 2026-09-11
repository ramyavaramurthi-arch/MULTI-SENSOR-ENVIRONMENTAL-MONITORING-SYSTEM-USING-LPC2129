# MULTI-SENSOR-ENVIRONMENTAL-MONITORING-SYSTEM-USING-LPC2129

Overview

This project is a multi-sensor environmental monitoring system developed using the LPC2129 ARM7 microcontroller and Embedded C as a mini project.

The system monitors temperature, light intensity, soil moisture, and water detection. The LPC2129 processes the sensor inputs and determines the current environmental condition.

Microcontroller
* Microcontroller: LPC2129
* Architecture: ARM7
* Programming Language: Embedded C

Sensors Used
* LM35 – Temperature monitoring
* LDR – Light intensity monitoring
* Soil Moisture Sensor – Soil moisture monitoring
*Water Sensor – Water detection

Peripherals Used
* GPIO
* ADC
* UART
* 16×2 LCD
* LEDs

Working

The LPC2129 reads the sensor inputs and processes them to determine the current environmental condition.

Temperature

The LM35 provides an analog output which is read using the LPC2129 ADC. The ADC value is converted into the corresponding temperature.

LDR Sensor

The LDR is used to monitor the intensity of surrounding light. Its output is read through the LPC2129 ADC to determine the light level.

Soil Moisture Sensor

The soil moisture sensor is used to determine the moisture level of the soil. The LPC2129 reads the sensor value through the ADC and determines whether the soil is sufficiently moist or dry.

Water Sensor

The water sensor provides a digital signal to detect the presence of water. The LPC2129 processes this signal to determine the water detection status.

The project documentation specifies the LM35, LDR, and soil moisture sensor as analog inputs and the water sensor as a digital input.
