# Lab 6
Ratiq Narwal (10289395)
Tim Ke (42973255)

Date - 2022-03-09

### Clarify Objective

To measure the capacitance of a capacitor. The capacitance is the ratio of the charge to the electric potential across the capacitor. 

### Explore tools
| Tools              | Physical Parameters            | Resolution | Range      | Usage                                                                      | Uncertainty         |
| ------------------ | ------------------------------ | ---------- | ---------- | -------------------------------------------------------------------------- | ------------------- |
| Oscilloscope       | Voltage and Current            | 0.001 mV   |            | Used to measure the current and voltage                                    |                     |
| Function Generator | Frequency                      | 0.05 Hz    | 0 to 3M Hz | Used to generate a current of either DC or AC current                      | 0.025 Hz            |
| Multimeter         | Voltage Current and Resistance | 0.1 mV     |            | Used to measure the current, voltage and resistance of specific components | 0.1 mV/mA/m${\ohm}$ |
| Capacitor          | Capacitance                    |            |            | Capacitance that will be measured                                          |                     |
| Resistor           | Resistance                     |            |            | Provides resistance in the circuit that can be used in calculation         |                     |
| Breadboard         |                                |            |            | Used to construct circuits                                                 |                     |
| Connecting cable   |                                |            |            | Used to connect components of a circuit together                           |                     |

We combined the 2 resistors provided to us to obtain a net resistance of a different value. We will connect the resistors in both series and parallel and record the resistance below. The resistance of the Resistors measured using the digital multimeter

| Resistor Number                                        | Resistance      | Uncertainty    |
| ------------------------------------------------------ | --------------- | -------------- |
| R1                                                     | 9.96 k${\ohm}$  | 0.01 k${\ohm}$ |
| R2                                                     | 29.92 k${\ohm}$ | 0.01 k${\ohm}$ |
| R3 (R1 + R2) (Series)                                  | 39.83 k${\ohm}$ | 0.01 k${\ohm}$ |
| R4 (${\frac{1}{\frac{1}{R1}\frac{1}{R2}}}$) (Parallel) | 74.61 k${\ohm}$  | 0.01 k${\ohm}$ | 



### Relate Quantities



#### Method 1 - Measuring voltage
Constructing an RC Circuit as shown below,

![[RC circuit.png]]

and using the equations that define a RC circuit,

![[Lab 6 method 1.PNG]]

The voltage, while the capacitor is discharging, can be measured and can be used with the formula above to form a plot. Using the plot, the slope can be measured and using the equation highlighted in yellow, the value of C can be calculated.

#### Method 2 - Measuring the Time Constant

The time constant defines the value at which the initial voltage is at the value ${\frac{V_0}{e}}$. Using this concept, the following can be used to form a plot,

![[Lab6 method 2.PNG]]

Multiple data points can be recorded for the value of the time constant for different resistors and they can be plotted against the resistance and use the slope (from the yellow highlighted part) to calculate the value of capacitance.


### Testing

#### Method 1 - Measuring Voltage

We measured the voltage across the capacitor using the resistor R3 and set it up as shown in the image below.


The initial voltage of the circuit was measured by removing the capacitor and recording the value of the voltage obtained on the oscilloscope. The value was recorded to be 8.8 V. The following values were obtained from the testing the circuit and recording the values from the oscilloscope,


| Time    | Voltage |
| ------- | ------- |
| 0       | 8.8 V   |
| 288 us  | 6.04V   |
| 648us   | 3.8V    |
| 1.02 ms | 2.32 V  |
| 1.44 ms | 1.28V   |
| 1.91 ms | 0.720 V  |

#### Method 2 - Measuring the Time Constant

8.8/e = 3.2373390823



### Procedure

## Evaluation