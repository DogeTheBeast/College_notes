# Lab 2

## Clarify Objective

The objective of the experiment is to measure the spring constant of a spring using the tools provided. Spring constant is the amount of force required to extend a spring by a unit length.

## Explore Tools

| Tools     | Physical Parameters | Resolution | Range         | Usage                                                   | Uncertainty |
| --------- | ------------------- | ---------- | ------------- | ------------------------------------------------------- | ----------- |
| Ruler     | Distance            | 1 cm       | 0 to 100 cm   | Used to measure the extension of the spring             | 0.005 m      |
| Stopwatch | Time                | 0.01 s     | 0 to infinity | Used to measure the period of oscillation of the spring | 0.01 s      |
| Scale     | Mass                | 1 g        | 0 to infinity | Used to measure the mass of the spring and the masses   | 0.00001 kg      |

## Relate Quantities and forming relationship

#### Static method

Relate the force experienced by the spring and the extension of the spring

$${\LARGE F = -k \Delta x}$$
$${\LARGE (m_2 - m_1)g = -k (x_2 - x_1)}$$
$${\LARGE k = - \frac{(m_2 - m_1)\times g}{(x_2 - x_1)}}$$
$${\LARGE k = - \frac{M \times g}{X}}$$

where, *M* is the difference in mass, and
*X* is the difference in extension.

#### Uncertainty Calculations

$${\Large \delta M = \sqrt{\delta m_2^2 + \delta m_1^2}}$$
$${\LARGE \delta X = \sqrt{\delta x_2^2 + \delta x_1^2}}$$
$${\Large \frac{\delta k}{k} = \sqrt{\left(\frac{\delta M}{M}\right)^2 + \left(\frac{\delta X}{X}\right)^2}}$$


$${\LARGE \delta k =  k \times \sqrt{\left(\frac{\sqrt{\delta m_2^2 + \delta m_1^2}}{(m_2 - m_1)}\right)^2 + \left(\frac{\sqrt{\delta x_2^2 + \delta x_1^2}}{(x_2 - x_1)}\right)^2}}$$



#### Graphing Method

From the equation,
$${\LARGE F = -k \Delta x}$$
it is evident that ${\Delta x}$ and F are proportional and the slope of the straight line is negative k. Therefore, by plotting the values of the F against x, we can use the slope to find the value of k.


## Testing

### Raw Data

#### For dot object

| Trial   | Mass (in g) | Length (in cm) |
| ------- | ----------- | -------------- |
| 1       | 41.88       | 46             |
| 2       | 42.08       | 47             |
| 3       | 42.19       | 46             |
| Average | 42.05       | 46.3           |

#### For Blue block

| Trial   | Mass (in g) | Length (in cm) |
| ------- | ----------- | -------------- |
| 1       | 142.26      | 47             |
| 2       | 142.17      | 48             |
| 3       | 142.44      | 47             |
| Average | 142.29      | 47.3           |


#### For Green block

| Trial   | Mass (in g) | Length (in cm) |
| ------- | ----------- | -------------- |
| 1       | 293.07      | 49             |
| 2       | 291.95      | 49             |
| 3       | 292.69      | 50             |
| Average | 292.57      | 49.3           |

#### For Purple block

| Trial   | Mass (in g) | Length (in cm) |
| ------- | ----------- | -------------- |
| 1       | 543.34      | 52             |
| 2       | 542.93      | 51             |
| 3       | 541.14      | 52             |
| Average | 542.47      | 51.7           |


### Processed Data

| Object       | Average Mass (along with spring) (m in gram) | Mass (without spring) (m in kilograms) | Weight (${F = mg}$) (N) | Average Length (in cm) | Length  (x in m) | Extension (${\delta x}$) (m) |
| ------------ | -------------------------------------------- | -------------------------------------- | ----------------------- | ---------------------- | ---------------- | ---------------------------- |
| Dot          | 42.05                                        | 0.000                                  | 0.000                   | 46.3                   | 0.463            | 0.000                        |
| Blue Block   | 142.29                                       | 0.100                                  | 0.980                   | 47.3                   | 0.473            | 0.010                        |
| Green Block  | 292.57                                       | 0.150                                  | 1.470                   | 49.3                   | 0.493            | 0.030                        |
| Purple Block | 542.47                                       | 0.500                                  | 4.900                   | 51.7                   | 0.517            | 0.054                        |

### Procedure

#### Static Method

1. Measure the mass of the spring before placing any mass on it.
2. Using the ruler to measure the length of the spring.
3. Add the mass on the spring and wait for it to stop oscillating. When the spring stops moving, measure the mass of the setup. Subtract the mass of the spring from the mass measured.
4. With the mass on the spring, measure the length of the spring.
5. Repeat the steps above as many times as the different weights are available.
6. Use the following equation to measure the value of spring constant (using 2 of the values measured),
$${\LARGE k = - \frac{(m_2 - m_1)\times g}{(x_2 - x_1)}}$$

6. And, use the following equation to measure the uncertainty of the value of the spring constant.

$${\LARGE \delta k =  k \times \sqrt{\left(\frac{\sqrt{\delta m_2^2 + \delta m_1^2}}{(m_2 - m_1)}\right)^2 + \left(\frac{\sqrt{\delta x_2^2 + \delta x_1^2}}{(x_2 - x_1)}\right)^2}}$$

7. Repeat the calculations with all 3 different masses and record the values of *k*. Average out the values to find the most accurate value.

#### Using the value taken earlier with the static procedure

By using the values in the table under the heading of testing, we can determine the value of k and the uncertainty associated with it for the static method.

| Block used | Value of k (N/m) | Value of ${\delta k}$ |
| ---------- | ---------------- | --------------------- |
| Blue       | 479.71           | 169.61                |
| Green      | 600.37           | 106.13                |
| Purple     | 600.37           | 103.32                |


#### Graphing Method

1. Measure the mass of the spring before placing any mass on it.
2. Using the ruler to measure the length of the spring.
3. Add the mass on the spring and wait for it to stop oscillating. When the spring stops moving, measure the mass of the setup.
4. With the mass on the spring, measure the length of the spring.
5. Repeat the steps above as many times as the different weights are available.
6. Multiply the value of the mass with *g* to find the weight of the blocks.
7. Plot the graph of the weight of the blocks against the extension that was observed.
8. Plot the error bars for the weight for each point and use MatLab of any other graphing software to plot the best fit line along with the uncertainty in the slope of the line.
9. The value of the slope is the negative value of *k* and the uncertainty in the value of the slope is the uncertainty in the value of *k*.


#### Using the value taken earlier with the graphing procedure






## Revaluation

The produce described above is very inaccurate because the uncertainty of the values of k is around a quarter of the actual value. Therefore, the method stated above is not preferred. Comparatively, a better method would be to measure the period of osciallation of the spring and use the formula,
$${\LARGE T = 2 PI \sqrt{\frac{m}{k}}}$$