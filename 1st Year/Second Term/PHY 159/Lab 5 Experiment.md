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

![[Setup Lab 5.jpg]]

 By moving the microphone inside the tube to be at a given distance from the speaker, the following data values are determined for each frequency.

### First Harmonic

| Position of microphone (in m) | Pressure (without units) |
| ----------------------------- | ------------------------ |
| 0.00                          | 21.6                     |
| 0.05                          | 52.4                     |
| 0.1                           | 75.6                     |
| 0.15.                         | 76.8                     |
| 0.2                           | 78.4                     |
| 0.25                          | 78.4                     |
| 0.3                           | 78.4                     |
| 0.35                          | 75.6                     |
| 0.4                           | 72.8                     |
| 0.45                          | 46.7                     |
| 0.5                           | 12.6                     | 


Below is the plot of the values obtained after measuring the amplitude of the wave obtained from the microphone against different distances from the speaker configured for the first harmonic.

![[First harmonic lab5.PNG]]

where, the x-axis is the distance between the speaker and the microphone (measured in meters) and on the y-axis it is the amplitude of the wave obtained from the microphone (with no units).


### Second Harmonic

| Position of microphone (in m) | Pressure (without units) |
| ----------------------------- | ------------------------ |
| 0.00                          | 38.4                     |
| 0.05                          | 46.8                     |
| 0.1                           | 78.4                     |
| 0.15                          | 68.3                     | 
| 0.2                           | 38.4                     |
| 0.25                          | 45.8                     |
| 0.3                           | 50.8                     |
| 0.35                          | 58.5                     |
| 0.4                           | 69.6                     |
| 0.45                          | 42.4                     |
| 0.5                           | 14.4                     |


Below is the plot of the values obtained after measuring the amplitude of the wave obtained from the microphone against different distances from the speaker configured for the first harmonic.

![[Second Harmonic lab 5.PNG]]


where, the x-axis is the distance between the speaker and the microphone (measured in meters) and on the y-axis it is the amplitude of the wave obtained from the microphone (with no units).

### Speed of sound


The resonance frequencies were measured using the oscilloscope by placing the 

| Distance from the speaker (in m)    | Resonance number | Frequency |
| --- | ---------------- | --------- |
| 0.25    | 1                | 318.5     |
| 0.125    | 2                | 675.6     |
| 0.0625    | 3                | 1015.5    |
| 0.0312    | 4                | 1456.2    |
| 0.0151    | 5                | 1790.2    |
| 0.0052    | 6                | 2104.5    |
| 0.00    | 7                | 2545.7    |

![[Speed of sound.PNG]]



## Testing

### Pressure amplitude profile
 
 By moving the microphone inside the tube to be at a given distance from the speaker, the following data values are determined for each frequency.
 
#### Fundamental Frequency (309.8 Hz)

| Reading | Distance from the speaker (cm) | Amplitude |
| ------- | ------------------------------ | --------- |
| 1       | 0                              | 21.6      |
| 2       | 10                             | 75.6      |
| 3       | 20                             | 78.4      |
| 4       | 30                             | 78.4      |
| 5       | 40                             | 72.8      |
| 6       | 50                             | 12.6      |

![[first fundamental.PNG]]

#### 2nd Resonance Frequency (619.1 Hz)

| Reading | Distance from the speaker (cm) | Amplitude |
| ------- | ------------------------------ | --------- |
| 1       | 0                              | 38.4      |
| 2       | 10                             | 78.4      |
| 3       | 20                             | 38.4      |
| 4       | 30                             | 50.8      |
| 5       | 40                             | 69.6      |
| 6       | 50                             | 14.4      |
![[second fundamental.PNG]]

## Second Objective - Speed of sound


By used the method used to measure the fundamental frequency and the second resonance frequency, we found the third and the fourth resonance frequency which is stated below.

| Resonance number | Frequency (Hz) |
| ---------------- | -------------- |
| 1                | 309.8          |
| 2                | 619.1          |
| 3                | 1260           |
| 4                | 1580           |


![[Frequency against n.PNG]]

Using the curve above, the slope of the curve is determined to be 345.1. Using the equations stated in the previous part (Relate Quantities). Using 345.1, the value of the speed of sound can be determined. 
$${345.1 = \frac{v}{2L}}$$
$${v = 345.1 \times 2 \times 0.502}$$
$${v = 345.1 m/s}$$
#### Uncertainty
$${\frac{\delta v}{v} = \sqrt{\left(\frac{1}{309.8}\right)^2+\left(\frac{0.0005}{0.5}\right)^2}}$$
$${\delta v = 3 \times 10^{-3}}$$
This is the uncertainty in the measured speed of sound rounded to 1 significant figure.





## Report your results

## Discuss the results

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

