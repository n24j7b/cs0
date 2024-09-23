java cASSIGNMENT 1 – CONTROLLER FOR AN ELECTRIC WATER HEATER
A controller is to be designed for an Electric Water Heater using a 20MHz C167 microcontroller and this is to be developed using the Keil IDE.
Operation
The temperature setpoint is set by the user via a temperature control potentiometer. This potentiometer is connected across the power supply rails providing a voltage between 0V (minimum temperature) and 5V (maximum temperature). To maximise the resolution, the full range of the potentiometer should be used.
The temperature setpoint range should be between 45°C (to ensure legionella bacteria is destroyed) and 60°C (to limit the risk of scalding).
Signal conditioning has been provided that offsets, scales and linearises the thermistor temperature sensor output to occupy the full voltage range of the analogue to digital converter (ADC) for the temperature range required.
2 temperature sensors introduce redundancy in
case of temperature sensor failure. If the readings from the temperature sensors代 写program、 java/Python
代做程序编程语言 deviate from each other by more than 5°C then a warning buzzer should sound. The buzzer is activated by a high output from the microcontroller.
The heating elements are in parallel, i.e. one digital output drives one power transistor that switches one relay that powers both heating elements.
2°C of hysteresis should be implemented to prevent any chattering of the relay.
To be submitted:
Project files (zipped) with fully commented source code should be uploaded to MyUni. Use your student ID as the filename and in the header of the main program (as comment). Maintain a modular file structure, i.e. keep all ADC related functions in source file adc.c with prototypes exported through adc.h, etc.
Include a word document or pdf showing your flowcharts, state diagram or pseudo code to document the algorithmic details of your program. Also include Keil Simulator screenshots showing the correct operation of your controller.
State any necessary assumptions.
    

         
加QQ：99515681  WX：codinghelp
