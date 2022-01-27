# Lab 2

### Clarify Objective

The objective of the experiment is to measure the spring constant of a spring using the tools provided. Spring constant is the amount of force required to extend a spring by a unit length.

### Explore Tools

| Tools     | Physical Parameters | Resolution | Range         | Usage                                                   | Uncertainty |
| --------- | ------------------- | ---------- | ------------- | ------------------------------------------------------- | ----------- |
| Ruler     | Distance            | 1 cm       | 0 to 100 cm   | Used to measure the extension of the spring             | 0.005 m      |
| Stopwatch | Time                | 0.01 s     | 0 to infinity | Used to measure the period of oscillation of the spring | 0.01 s      |
| Scale     | Mass                | 1 g        | 0 to infinity | Used to measure the mass of the spring and the masses   | 0.00001 kg      |

### Relate Quantities and forming relationship

#### Static method

Relate the force experienced by the spring and the extension of the spring

$${\LARGE F = -k \Delta x}$$
$${\LARGE (m_2 - m_1)g = -k (x_2 - x_1)}$$
$${\LARGE k = - \frac{(m_2 - m_1)\times g}{(x_2 - x_1)}}$$
$${\LARGE k = - \frac{\Delta M \times g}{\Delta x}}$$

#### Uncertainty Calculations

$${\}


$${\LARGE \delta k =  k \times \sqrt{\left(\frac{\sqrt{\delta m_2^2 + \delta m_1^2}}{(m_2 - m_1)}\right)^2 + \left(\frac{\sqrt{\delta x_2^2 + \delta x_1^2}}{(x_2 - x_1)}\right)^2}}$$


### Testing

| Object       | Mass (along with spring) (m in kilograms) | Weight (${F = mg}$) (N) | Length  (x in m) | Extension (${\delta x}$) (m) |
| ------------ | ----------------------------------------- | ----------------------- | ---------------- | ---------------------------- |
| Dot          | 0.042                                     | 0.412                   | 0.46             | 0.00                         |
| Blue Block   | 0.142                                     | 1.390                   | 0.48             | 0.02                         |
| Green Block  | 0.292                                     | 2.860                   | 0.50             | 0.04                         |
| Purple Block | 0.542                                     | 5.320                   | 0.54             | 0.08                         |

### Procedure

1. Measure the mass of the spring before placing any mass on it.
2. Using the ruler to measure the length of the spring.
3. Add the mass on the spring and wait for it to stop oscillating. When the spring stop moving measure the mass of the setup.
4. With the mass on the spring, measure the length of the spring.
5. Use the following equation to measure the value of spring constant,
$${\LARGE k = - \frac{(m_2 - m_1)\times g}{(x_2 - x_1)}}$$
6. And, use the following equation to measure the uncertainty of the value of the spring constant.

$${\LARGE \delta k =  k \times \sqrt{\left(\frac{\sqrt{\delta m_2^2 + \delta m_1^2}}{(m_2 - m_1)}\right)^2 + \left(\frac{\sqrt{\delta x_2^2 + \delta x_1^2}}{(x_2 - x_1)}\right)^2}}$$

7. Repeat the experiment with all 3 different masses and record the values of k. Average these values to eliminate random error.

#### Using the value taken earlier with the procedure

By using the values in the table under the heading of testing, we can determine the value of k and the uncertainty associated with it for the static method.

| Block used | Value of k (N/m) | Value of ${\delta k}$ |
| ---------- | ---------------- | --------------------- |
| Blue       | 479.71           | 169.61                |
| Green      | 600.37           | 106.13                |
| Purple     | 600.37           | 103.32                |

## Revaluation

The produce described above is very inaccurate because the uncertainty of the values of k is around a quarter of the actual value. Therefore, the method stated above is not preferred. Comparatively, a better method would be to measure the period of osciallation of the spring and use the formula,
$${\LARGE T = 2 PI \sqrt{\frac{m}{k}}}$$>)