# Lab 9
#### Ratiq Narwal (10289395)
#### Yutaka Kobashi (11315314)
Date - 2022-03-23



### Clarify Objective

Measure the molar density and atmosphere pressure in the atmosphere. Atmospheric pressure is the amount of pressure that is felt on an object by the weight of the air on top of the object. Pressure is calculated by measuring the force over unit area and molar density is amount of moles occupying a unit volume. 


### Explore tools
| Tools                   | Physical Parameters | Resolution   | Range            | Usage                                                   | Uncertainty   |
| ----------------------- | ------------------- | ------------ | ---------------- | ------------------------------------------------------- | ------------- |
| Ruler                   | Length              | 0.05 cm      | 0 to 100 cm      | Measure the length of an object                         | 0.1 cm        |
| Masses                  | Mass                | 0.5 g        | 0 to 1000 g      | Masses used for measurement                             | 0.5 g         |
| Syringe                 | Volume              | 0.1 ${cm^3}$ | 0 to 10 ${cm^3}$ | Used to measure volume                                  | 0.05 ${cm^3}$ |
| Digital Weighting scale | Mass                | 0.0001 kg    | 0 to 10 kg       | Used to measure the mass of an object                   | 0.0001 kg     |
| Table Clamp             | -                   | -            | -                | -                                                       | -             |
| Metal bar with holes    | -                   | -            | -                | -                                                       | -             |
| Vernier Calipers        | Length              | 0.05 mm      | 0 to 150 mm      | Used to measure the length of smaller objects precisely | 0.025 mm      |

### Relate Quantities and forming relationships

Below is the free body diagram of the end of the syringe,

![[Syringe.PNG]]

![[Radius for syringe.PNG]]



#### Objective 1 - Measuring the molar density

The standard formula that relates pressure and volume with temperature for ideal gases is,

$${\LARGE PV = nRT}$$
From the diagram, the following equation can be derived,

$${\LARGE F_{atm} = mg + F_{gas}}$$
$${\LARGE \frac{F_{atm}}{A} = \frac{mg}{A} + \frac{F_{gas}}{A}}$$
$${\LARGE P_{atm} = \frac{mg}{A} + P_{gas}}$$
$${\LARGE \frac{nRT}{V_0} = \frac{mg}{A} + \frac{nRT}{V_{gas}}}$$

$${\LARGE \frac{1}{V_0} - \frac{1}{V_{gas}} = \frac{mg}{AnRT}}$$

where,
*m* is the weight added on the syringe,
*g* is acceleration due to gravity,
*A* is the area of the seal,
*n* is the number of moles,
*R* is the gas constant (${8.314 J \times mol^{-1} \times K^{-1}}$), and
*T* is the temperature of the gas (standard temperature (273.15 K)).

The equation above can be plotted to find the slope which will be equal to ${\frac{1}{AnRT}}$ and from this, the number of moles can be calculated. Using the number of moles, the molar density of the gas can be calculated using the equation,

$${\LARGE molar\space density = \frac{n}{V_0}}$$


#### Objective 2 - Measuring the atmospheric pressure

$${\LARGE F_{atm} = mg + F_{gas}}$$
$${\LARGE P_{atm} = \frac{F_{app}}{A} + P_{gas}}$$
$${\LARGE P_{atm}\times A = F_{app} + P_{gas}\times A}$$
$${\LARGE  \frac{nRT}{V} =  P_{atm} - \frac{mg}{A}}$$

where,
*m* is the weight added on the syringe,
*g* is acceleration due to gravity,
*A* is the area of the seal,
*n* is the number of moles,
*R* is the gas constant (${8.314 J \times mol^{-1} \times K^{-1}}$), and
*T* is the temperature of the gas (standard temperature (273.15 K)).



### Testing


#### Objective 1 - Measuring the molar density
The values below were collected,

| Weight (kg) | x value for graph (${kg/m^2}$) | Initial Volume (${m^3}$) | Final Volume (${cm^3}$) | Difference in volume (${cm^3}$) | ${\LARGE \frac{1}{V_0} - \frac{1}{V_{gas}}}$ |
| ----------- | ------------------------------ | ------------------------ | ----------------------- | ------------------------------- | -------------------------------------------- |
| 0           | 0                              | ${5.0 \times 10^{-6}}$   | ${5.0 \times 10^{-6}}$  | 0.0                             | 0.000                                        |
| 0.4         | 24094                          | ${5.0 \times 10^{-6}}$   | ${5.9 \times 10^{-6}}$  | ${9.0 \times 10^{-7}}$          | 30508                                        |
| 0.7         | 42165                          | ${5.0 \times 10^{-6}}$   | ${6.9 \times 10^{-6}}$  | ${1.9 \times 10^{-6}}$          | 55072                                        |
| 1.0         | 60235                          | ${5.0 \times 10^{-6}}$   | ${9.0 \times 10^{-6}}$  | ${3.0 \times 10^{-6}}$          | 88889                                        |

and the following graph was obtained from the values above.



![[syringe graph.PNG]]

On the x axis, we have ${\frac{mg}{A}}$ and on the y axis, we have ${\frac{1}{V_0} - \frac{1}{V_{gas}}}$


![[Slope for syringe.PNG]]


Using the value of the slope, the value of n can be calculated,
$${\LARGE n = \frac{1}{1.3747 \times 294.55 \times 8.314}}$$
$${\LARGE n = 2.9704 \times 10^{-4}}$$

and using the value of n, the value of the molar density can be calculated,

$${\LARGE molar \space density = \frac{n}{V_0} = \frac{2.9704 \times 10^{-4}}{5\times 10^{-6}}}$$
$${\LARGE molar \space density = 59.41}$$

The uncertainty in the value of the molar density and the related calculations is shown below,

![[uncertainty in syringe.PNG]]

#### Objective 2 - Measuring the atmospheric pressure

The following values were obtained and modified to be plotted,

| Weight (kg) | x value for graph (${kg/m^2}$) | Initial Volume (${m^3}$) | Final Volume (${cm^3}$) | Difference in volume (${cm^3}$) | ${\LARGE \frac{nRT}{V_0}}$ |
| ----------- | ------------------------------ | ------------------------ | ----------------------- | ------------------------------- | -------------------------- |
| 0           | 0                              | ${5.0 \times 10^{-6}}$   | ${5.0 \times 10^{-6}}$  | 0.0                             | 145439                     |
| 0.4         | -24094                         | ${5.0 \times 10^{-6}}$   | ${5.9 \times 10^{-6}}$  | ${9.0 \times 10^{-7}}$          | 123253                     |
| 0.7         | -42165                         | ${5.0 \times 10^{-6}}$   | ${6.9 \times 10^{-6}}$  | ${1.9 \times 10^{-6}}$          | 105390                     |
| 1.0         | -60235                         | ${5.0 \times 10^{-6}}$   | ${9.0 \times 10^{-6}}$  | ${3.0 \times 10^{-6}}$          | 80799                      | 

and the following graph was obtained for the values above,

![[atmospheric pressure graph.PNG]]

On the x-axis, we have ${\frac{mg}{A}}$ and on the y-axis, we have 
![[y-intercept.PNG]]



### Procedure

#### Objective 1 - Measuring the molar density

1. Setup the apparatus as shown below with the syringe suspended from the bracket.
![[syringe setup.PNG]]
3. Setup the syringe and fill it with air to a measuring and controlled amount. Use a stopper and close the syringe.
4. Suspend weights of different masses from the syringe and measure the extension new volume of the air in the syringe.
5. Use the formula below to plot a graph of the behavior of the gas in the syringe.
$${\LARGE \frac{1}{V_0} - \frac{1}{V_{gas}} = \frac{mg}{AnRT}}$$
where,
${\frac{1}{V_0} - \frac{1}{V_{gas}}}$ is the y value,
${\frac{1}{nRT}}$ is the slope, and
${\frac{mg}{A}}$ is the x value.
6. Use the slope of the graph and use the formula below to calculate the number of moles of the gas present. 
$${\LARGE n = \frac{1}{slope\times R \times T}}$$
8. Use the number of moles and divide it be the initial volume of the gas in the syringe to find the molar density.

$${\LARGE molar\space density = \frac{n}{V_0}}$$

#### Objective 2 - Measuring the atmospheric pressure

## Evaluation
The method used to measure the molar density was determined to be very accurate 


## Reflection
