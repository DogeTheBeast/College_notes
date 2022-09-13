# Digital Abstraction

### Analog Approach
Use voltage to directly encode information. The problem with this approach is the existence of noise and not being able to remove noise.

![[Analogue Approach.PNG]]

### Digital binary
Only 2 states exist (High and Low). Less possible states but also removes noise from the system.

![[Digital Binary.PNG]]

### Buffer
Takes an input and turns it into a digital binary signal. Able to remove noise from the signal.

![[Buffer.png]]

### Noise accumulation

The more analog circuits we combine the more noise accumulation impacts the output of the circuit. 

![[Noise Accumulation.PNG]]

To fix this, we can add buffers after every time noise is added to the circuit. Hence, digital binary systems are easily scalable.

![[Fixed Noise Accumulation.PNG]]

### Noise Tolerance

We wish to design a buffer so that the tolerance for noise is lower. The input voltage from the x axis is projected onto the y values from the graph. the slope needs to be less than 1 if we wish to make it 



---
Read also - 