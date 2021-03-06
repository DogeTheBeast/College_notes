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
| R4 (${\frac{1}{\frac{1}{R1}\frac{1}{R2}}}$) (Parallel) | 7.46 k${\ohm}$  | 0.01 k${\ohm}$ |



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


The initial voltage of the circuit was measured by removing the capacitor and recording the value of the voltage obtained on the oscilloscope. The following values were obtained from the testing the circuit and recording the values from the oscilloscope,


| Time    | Voltage | ln(voltage) |
| ------- | ------- | ----------- |
| 0       | 4.46 V  | 1.495       |
| 480 us  | 3.4 V   | 1.223       |
| 840 us  | 2.8V    | 1.029       |
| 1770 us | 1.5V    | 0.405       |

![[graph 1.PNG]]

On the x-axis is the time (in micro seconds) and on the y-axis is the voltage (in Volts).

The slope is calculated to be -0.00006176

Using the equations in relating quantities, the value of C can be calculated and it is 0.0000000217 F with the uncertainty as 1.0113 x 10^-7 F.

#### Method 2 - Measuring the Time Constant


By changing the resistor, the value of the time constant can be calculated,

| Time   | Initial Voltage | Voltage at time = Tau | Resistance |
| ------ | --------------- | --------------------- | ---------- |
| 280 us | 1.86            | 0.684                 | 7.461      |
| 350 us | 3.88            | 1.427                 | 9.96       |
| 610 us | 4.28            | 1.574                 | 29.92      | 


![[graph 3.PNG]]

From the graph, the value of the slope is calculated to be 0.000014014 F with an uncertainty of 1.0419 x 10^-7 F.



### Procedure
Procedure:

  

1.  Set up the bread board as shown in the diagram below with the resistor and capacitor attached in series to the battery. 
    
2.  Change the function generator to square wave form.
    
3.  Look for the discharging part of the graph shown on the oscilloscope. 
    
4.  Once the graph has appeared properly on the oscillograph, To determine the initial voltage look for the maximum point on the graph and record the Y-value associated with that value.
    
5.  Record the time and voltage of 6 different data points with roughly the same time intervals in between. The data points should be located on the graph.
    
6.  Plot the data in a graphing software such as Matlab.
    
7.  Using Matlab the slope of the graph will be equal to (-t/RC) where t is the independent variable and R and C are constants. 
    
8.  To calculate C we use the relation C = (-1/R)*(1/slope).
    
9.  The uncertainty in C can be calculated from the uncertainty in the slope of the graph, which will be calculated by Matlab automatically.
    

![[RC circuit.png]]
  
  

## Reflection and justification of Procedure:

Our Final procedure involved plotting the data points of a Voltage vs time graph. The capacitance was then found using the slope of this graph. This method was the preferred method because the plot allows us to use as many data points as necessary. Utilizing more or less data points allows us to measure the capacitance to a greater degree of certainty. This method also requires only one resistor, therefore it is easier to set up. The capacitance calculated yielded a value that was accurate and of low uncertainty.

  

As for the possible sources of error in the lab there were uncertainties and fluctuations in the oscilloscope as well as the DMM. Sources of error also include human error when measuring the resistances and adjusting the oscilloscope.
