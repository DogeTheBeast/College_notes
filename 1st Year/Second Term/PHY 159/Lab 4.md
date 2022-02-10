# Lab 4
#### Ratiq Narwal (10289395)
Date - 2022-02-09
Lab members - Tim Ke, Bruno Eliseo, Ratiq Narwal

## Clarify Objective
To measure the ${V_{out}/V_{in}}$ for a voltage divider.
Voltage is the difference in charge between 2 points on a circuit.


## Explore tools
| Tools              | Physical Parameters   | Resolution    | Range                                                           | Usage                                                                                                         | Uncertainty |
| ------------------ | --------------------- | ------------- | --------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------- | ----------- |
| Digital Multimeter | Voltage and Current   | 0.001 V and A | Negative infinity to infinity                                   | Connect the two ends of the multimeter to the circuit to measure the voltage or the current of the component. | 0.001       |
| Oscilloscope       | Voltage and Current   |               |                                                                 |                                                                                                               |             |
| Resistor 1         | Resistance            | 10 ${k\ohm}$  |                                                                 | Provides a source of resistance                                                                               | 0.01        |
| Resistor 2         | Resistance            | 15 ${k\ohm}$  |                                                                 | Provides a source of resistance                                                                               | 0.01        |
| Function Generator | Voltage and Frequency |               | For voltage: 0 to 15 Volts and for Frequency: 0 to 3 Mega hertz | Provides a source of voltage along with a frequency                                                           |             |


## Relate Quantities and forming relationships

#### Method 1
The ratio of the voltage out and voltage in is,
$${\LARGE r = \frac{V_{out}}{V_{in}}}$$

The uncertainty for this method can be calculated by doing the following,

$${\LARGE \frac{\delta r}{r_0} = \frac{\delta V_{out}}{V_{out}} + \frac{\delta V_{in}}{V_{in}} }$$

#### Method 2

Using the Kirchoff's Loop Law to derive the equation for the procedure,
${ V_{in} - IR_1 - IR_2 = 0}$

${ V_{in} = I(R_1 + R_2)}$

${ V_{out} = IR_2}$

${ \frac{V_{out}}{V_{in}} = \frac{IR_2}{I(R_1 + R_2)}}$

Therefore, it can be simplified into,

$${\LARGE r = \frac{R_2}{R_1 + R_2}}$$

The uncertainty can be calculated by doing the following,
${\delta R_{total} = \delta R_1 + \delta R_2}$
${\frac{\delta r}{r_0} = \frac{\delta R_2}{R_2} + \frac{\delta R_{total}}{R_{total}}}$
$${\LARGE \frac{\delta r}{r_0} = \frac{\delta R_2}{R_2} + \frac{\delta R_1 + \delta R_2}{R_1 + R_2}}$$




## Testing
|                                | DMM              | Oscilloscope |
| ------------------------------ | ---------------- | ------------ |
| DC supply, V                   | 5.079 *V*        | 5.16 *V*     |
| Resistor 1, R                  | 9.88 ${k \ohm}$  |              |
| Function Generator, ${V_{pp}}$ |                  | 3.04 *V*     |
| Function Generator, f          |                  | 928.3 *Hz*   |
| Resistor 2, R                  | 14.96 ${k \ohm}$ |              |


DC Supply using multimeter
We connected the DC supply to the breadboard with the negative and the positive terminals connected to the power rails. Using the multimeter, we measured the voltage supplied by connecting the terminals of the multimeter with the power rail.

DC Supply using Oscilloscope
We connected the oscilloscope through channel 2 to the circuit and measured with the graph of the voltage.

Resistor using multimeter
We measured the resistance of the resistor using the multimeter and changing the settings to resistance from voltage. We connected the alligator clips from the multimeter to the 2 ends of the resistor and measured the resistance of the resistor.

Function Generator using the oscilloscope

We measured the voltage produced by the Function Generator using the oscilloscope. We set the function generator to produce a wave of 1 kilohertz and the output level to be 2 and we measured the voltage to be 3.04 Volts and 928.4 hertz.

#### Using method 1

By using the method 1, we determined the value of voltage out to be between 5.079 Volts using the multimeter  and by using the multimeter, the value of the voltage out for resistor 2 is determined to be 3.045. And by using the formula stated in relating quantities, the value of the ratio is determined.


| ${V_{in}}$      | ${V_{out}}$    | *r*               |
| --------------- | -------------- | ----------------- |
| 5.079 ± 0.001 V | 3.045 ± 0.001V | 0.59956 ± 0.00031 |


#### Using method 2
By using the method 2, we determined the value of the resistance of each of the resistors using the multimeter and by using the formulas listed in relating quantities, the ratio can be determined.

| ${R_1}$              | ${R_2}$               | ${R_{total}}$        | *r* |
| -------------------- | --------------------- | -------------------- | --- |
| 9.88 ± 0.01 ${ k\ohm}$ | 14.96 ± 0.01 ${k\ohm}$ | 24.84 ± 0.02 ${\ohm}$ | 0.60297 ± 0.00088   |

Method 1 yields a better result compared to method 2 as the uncertainty is less.

## Procedure

1. Connect the DC power supply to the breadboard through the power rails.
2. Use the multimeter and connect the positive terminal to the positive power rail and the negative terminal to the negative power rail.
3. Set the multimeter to read voltage and measure the voltage of the voltage in.
4. Disconnect the multimeter and complete the circuit as shown in the diagram. 
5. Connect the multimeter to the resistor as shown in the image below.

![[voltage divider.webp]]
7. Measure the voltage out.
8. Use the following formula to measure the value of *r* along with the uncertainty.

$${\LARGE r = \frac{V_{out}}{V_{in}}}$$

The uncertainty, 

$${\LARGE \frac{\delta r}{r_0} = \frac{\delta V_{out}}{V_{out}} + \frac{\delta V_{in}}{V_{in}} }$$


## Evaluation
After comparing both the methods, it was determined that the first method is better as it leads to a more accurate value with a lesser uncertainty as compared to the second method. The theoretical value is 0.6 and from the testing of both the methods, the values calculated are very accurate compared to the theoretical value. But the method 2 is much easier because it doesn't require the user to complete a circuit and makes it very complicated.