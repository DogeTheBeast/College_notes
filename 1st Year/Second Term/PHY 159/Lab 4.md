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

The uncertainty can be calculated 




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

## Procedure




## Evaluation