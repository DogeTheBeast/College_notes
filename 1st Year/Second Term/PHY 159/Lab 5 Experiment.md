# Lab 5 Experiment
Ratiq Narwal (10289395)
Eesha Madaan (19162999)
Date - 2022-03-02

## Objective

We will measure the speed of sound and the pressure amplitude inside an open pipe using the frequency of different waves.
1) Determine the speed of sound inside a tube using the resonance number and the position inside the tube.
2) Measure the pressure amplitude profile, *P(x)*, of the sounds waves inside the tube for the fundamental and the second resonance frequency.




## Relate Quantities and forming relationships

### First objective -  To measure the sound amplitude profile
Firstly, we need to find the fundamental frequency and the 2nd resonance frequency. To find the fundamental frequency, we did a rough calculation and determined the value of the fundamental frequency to be near about 343 Hz. As it is open from both ends, the length of the tube is half the wavelength for the first harmonic.

$${v = f \lambda}$$
$${f = \frac{nv}{\lambda} =  \frac{v}{2L} = \frac{343}{2 \times 0.502} \approx 343 Hz}$$

where,
*f* is the fundamental frequency,
*v* is the speed of sound,
*L* is the length of the tube.

By adjusting the knob for the frequency in the function generator near 343 Hz while keeping the microphone at the half way point of the tube (25 cm), we checked for the highest amplitude. The maximum amplitude of the wave means that the pressure is maximum at the middle of the wave, which only happens when it is at the fundamental frequency. 


Using the formula below, the 2nd resonance frequency can roughly calculated to make it easier to find it by trial and error.
$${f_n = \frac{nv}{2L}}$$
where, 
*n* is the number of resonance (which is 2 in this case) and by plotting the amplitude against the position of the microphone inside the tube.

| Resonance number | Frequency |
| ---------------- | --------- |
| 1                | 318.5 Hz  |
| 2                | 675.6 Hz | 


### Second Objective - Speed of Sound

As it is a tube open from both ends, the following formula can be used to find the wavelength of the wave for different resonance numbers.

$${\lambda_n = \frac{2L}{n}}$$
$${\lambda = \frac{v}{f}}$$
$${v = \frac{2f_n L}{n}}$$
Using the equations above, the relationship between v and the resonance number can be determined which can be used with the slope of the curve to find the speed of sound. Also, the uncertainty in this measurement is,
$${\frac{\delta v}{v} = \sqrt{\left(\frac{\delta f_n}{f_n}\right)^2+\left(\frac{\delta L}{L}\right)^2}}$$




## Procedure (from last lab)

##### Determine the pressure amplitude profile
1) Determine the fundamental frequency of the tube by test and trial of the frequency while keeping the microphone half way inside the tube. 
2) Record the fundamental frequency of the tube.
3) Move the microphone to equidistant intervals and measure the amplitude of the curve.
4) Repeat step 3 for all distances from the speaker. 
5) Plot the pressure amplitude profile with the amplitude at the y axis and the distance from the speaker on the x axis.


##### Speed of Sound

1)  Determine the fundamental frequency of the tube by test and trial of the frequency while keeping the microphone half way inside the tube. 
2)  Slowly adjust the knob on the function generator and increase the frequency of the sound while monitoring the oscilloscope. 
3)  Change the position of the knob to the appropriate distance from the speaker using the equation,

$${distance = \frac{L}{n}}$$
where 
*L* is the length of the tube, and
*n* is the resonance number.

4)  Whenever a spike in the amplitude is observed, slow down even further until the accurate value of the frequency can be measured. 
5)  Record the frequency along with the resonant number and plot it on a graph with the frequency on the y axis and resonant frequency on the x axis.
6)  The slope of the graph can be used to find the speed using the formula,
$${345.1 = \frac{v}{2L}}$$



## Setup

Below is the setup that was used while measuring the pressure profile at the fundamental frequency and the second harmonic and the speed of sound.


![[setup image.PNG]]

![[Setup Lab 5.jpg]]

 By moving the microphone inside the tube to be at a given distance from the speaker, the following data values are determined for each frequency.

### First Harmonic

| Position of microphone (in m) | Pressure (without units) | Pressure uncertainty |
| ----------------------------- | ------------------------ | -------------------- |
| 0.00                          | 21.6                     | 0.1                  |
| 0.05                          | 52.4                     | 0.1                  |
| 0.1                           | 75.6                     | 0.1                  |
| 0.15.                         | 76.8                     | 0.1                  |
| 0.2                           | 78.4                     | 0.1                  |
| 0.25                          | 78.4                     | 0.1                  |
| 0.3                           | 78.4                     | 0.1                  |
| 0.35                          | 75.6                     | 0.1                  |
| 0.4                           | 72.8                     | 0.1                  |
| 0.45                          | 46.7                     | 0.1                  |
| 0.5                           | 12.6                     | 0.1                  | 


Below is the plot of the values obtained after measuring the amplitude of the wave obtained from the microphone against different distances from the speaker configured for the first harmonic.

![[First harmonic lab5.PNG]]

where, the x-axis is the distance between the speaker and the microphone (measured in meters) and on the y-axis it is the amplitude of the wave obtained from the microphone (with no units). The error bars for this graph are not visible because the uncertainty in the y value is very low.


### Second Harmonic

| Position of microphone (in m) | Pressure (without units) | Pressure Uncertainty |
| ----------------------------- | ------------------------ | -------------------- |
| 0.00                          | 38.4                     | 0.1                  |
| 0.05                          | 46.8                     | 0.1                  |
| 0.1                           | 78.4                     | 0.1                  |
| 0.15                          | 68.3                     | 0.1                  |
| 0.2                           | 38.4                     | 0.1                  |
| 0.25                          | 45.8                     | 0.1                  |
| 0.3                           | 50.8                     | 0.1                  |
| 0.35                          | 58.5                     | 0.1                  |
| 0.4                           | 69.6                     | 0.1                  |
| 0.45                          | 42.4                     | 0.1                  |
| 0.5                           | 14.4                     | 0.1                  | 


Below is the plot of the values obtained after measuring the amplitude of the wave obtained from the microphone against different distances from the speaker configured for the first harmonic.

![[Second Harmonic lab 5.PNG]]


where, the x-axis is the distance between the speaker and the microphone (measured in meters) and on the y-axis it is the amplitude of the wave obtained from the microphone (with no units). The error bars for this graph are not visible because the uncertainty in the y value is very low.

### Speed of sound


The resonance frequencies were measured using the oscilloscope by placing the microphone at distances calculated using the equation inside Relating Quantities.

| Distance from the speaker (in m) | Resonance number | Frequency | Uncertainty in Frequency |
| -------------------------------- | ---------------- | --------- | ------------------------ |
| 0.2500                           | 1                | 318.5     | 0.1                      |
| 0.1666                           | 2                | 675.6     | 0.1                      |
| 0.1250                           | 3                | 1015.5    | 0.1                      |
| 0.1000                           | 4                | 1456.2    | 0.1                      |
| 0.0833                           | 5                | 1790.2    | 0.1                      |
| 0.0714                           | 6                | 2104.5    | 0.1                      |
| 0.0625                           | 7                | 2545.7    | 0.1                      | 

![[Speed of sound.PNG]]



where, we have plotted frequency (in hertz) on the y-axis and the resonance number (no unit) on the x-axis. The error bars for this graph are not visible because the uncertainty in the y value is very low.

Using the graph and a linear fit of the graph, the value of the slope was obtained to be 368.4. The slope of the graph is related to the speed of sound using the formula,

$${v = \frac{2f_n L}{n}}$$
$${m = \frac{f_n}{n}}$$

$${v = m \times 2L}$$

By placing the values in the equation above, the value of the speed of sound is obtained to be 368.4 m/s. And from MATLAB, the uncertainty in the slope is determined to be 0.0209.


## Report your results

The following results were obtained for the speed of sound and the uncertainty for it.

| Speed of Sound (m/s) | Uncertainty |
| -------------------- | ----------- |
| 368.4                | 0.0209      |

And the graph for the pressure profile for the first and second harmonic are added above, under experimentation.


## Discuss the results


The value of the speed of sound obtained are close to the actual value and the uncertainty is very small meaning the value obtained is very precise. But, as the uncertainty is too small, that means our method resulted in a value of speed of sound which is not accurate. Th

## Conclusion




---

# Appendix
## Procedure  (from last week)
##### Determine the pressure amplitude profile
1) Determine the fundamental frequency of the tube by test and trial of the frequency while keeping the microphone half way inside the tube. 
2) Record the fundamental frequency of the tube.
3) Move the microphone to equidistant intervals and measure the amplitude of the curve.
4) Repeat step 3 for all distances from the speaker. 
5) Plot the pressure amplitude profile with the amplitude at the y axis and the distance from the speaker on the x axis.


##### Speed of Sound
1)  Determine the fundamental frequency of the tube by test and trial of the frequency while keeping the microphone half way inside the tube. 
2)  Slowly adjust the knob on the function generator and increase the frequency of the sound while monitoring the oscilloscope. 
3)  Change the position of the knob to the appropriate distance from the speaker using the equation,

$${distance = \frac{L}{n}}$$
where 
*L* is the length of the tube, and
*n* is the resonance number.

4)  Whenever a spike in the amplitude is observed, slow down even further until the accurate value of the frequency can be measured. 
5)  Record the frequency along with the resonant number and plot it on a graph with the frequency on the y axis and resonant frequency on the x axis.
6)  The slope of the graph can be used to find the speed using the formula,
$${345.1 = \frac{v}{2L}}$$

