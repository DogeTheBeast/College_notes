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


#### Objective 1 - Measuring the atmospheric pressure

$${\LARGE F_{atm} = mg + F_{gas}}$$
$${\LARGE P_{atm} = \frac{F_{app}}{A} + P_{gas}}$$
$${\LARGE P_{atm}\times A = F_{app} + P_{gas}\times A}$$
$${\LARGE P_{atm}\times A = F_{app} + \frac{nRT}{V}A}$$

where,
*m* is the weight added on the syringe,
*g* is acceleration due to gravity,
*A* is the area of the seal,
*n* is the number of moles,
*R* is the gas constant (${8.314 J \times mol^{-1} \times K^{-1}}$), and
*T* is the temperature of the gas (standard temperature (273.15 K)).


#### Objective 2 - Measuring the molar density

The standard formula that relates pressure and volume with temperature for ideal gases is,

$${\LARGE PV = nRT}$$
From the diagram, the following equation can be derived,

$${\LARGE F_{atm} = mg + F_{gas}}$$
$${\LARGE \frac{F_{atm}}{A} = \frac{mg}{A} + \frac{F_{gas}}{A}}$$
$${\LARGE P_{gas} = \frac{mg}{A} + P_{gas}}$$
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

### Testing

| Weight (kg) | x value for graph | Initial Volume (${cm^3}$) | Final Volume (${cm^3}$) | Difference in volume (${cm^3}$) | ${\LARGE \frac{1}{V_0} - \frac{1}{V_{gas}}}$ |
| ----------- | ----------------- | ------------------------- | ----------------------- | ------------------------------- | -------------------------------------------- |
| 0           | 0                 | 5.0                       | 5.0                     | 0.0                             | 0.000                                        |
| 0.4         |                   | 5.0                       | 5.9                     | 0.9                             | 0.031                                        |
| 0.7         |                   | 5.0                       | 6.9                     | 1.9                             | 0.055                                        |
| 1.0         |                   | 5.0                       | 9.0                     | 3.0                             | 0.089                                        |

![[graph for syringe.PNG]]

![[slope for syringe.PNG]]

#### Objective 2 - Measuring the molar density






### Procedure

## Evaluation