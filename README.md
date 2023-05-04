# STM32 
# Objective 1

1. Simple DSP in Matlab 
   a.Create a vector t representing the time variable with range of one second and sampling period of Ts=0.001 sec 

   b.Create a plot that approximates the continuous time signal x(t)=cos(4πt) for 0≤t≤1, using the plot function 

   c. Label the plot using the xlabel,ylabel and tittle function 

   d. Downsample 

2. Simple Waveform with STM32 
We want to generate a continuous sinusoid signal 
x(t)=u(t)sin(2πfot) by sending the discrete signal 
x[n]=u[n]sin(2π(fo\fs)n) to the DAC where we are given some 
desired frequency as fs=16000hz and fo=1000hz.
Display the output signal on the oscilloscope and verify the 
frequency.(Using lookup table) 

3. Plotting Different Function Using STM32 
Plotting different functions in oscilloscope using ARM 
microcontroller 
# Objective 2

Data Scrambling and Descrambling:

The objective is to use the generated PN sequence to scramble and descramble a binary image.
Use a Linear-feedback shift register for pseudo-noise sequence generation. Store that in an array. 
Create an array containing a sample image say car.png. Show image on screen. Perform the scrambling 
operation and show the scrambled image. Calculate the autocorrelation of the PN sequence of the 
two images and the cross co-relation between the images. Descramble the image and display. Compute 
the autorelation of the descrambled image.

After you have done this part in Matlab and then using STMCube (only the scrambling and 
descrambling part), use the parts that you developed as part of the previous lab to demonstrate this 
on a sin/cos wave and show the scrambled and descrambled waveforms on the oscilloscope
# Objective 3

You will write a program which computes the CRC for a block of data. When you send a sequence 
of bits (message) from one point to another, you want to know that the message arrived correctly. 
You will give it data blocks (say any text data or a sequence of numbers), encode it, introduce errors, 
decode.

Present the results you obtain for each task on the assignment sheet. This section should 
include illustrative oscilloscope screenshots of the algorithms in action. Also include any code 
that you wrote or modified.

This should also have the following:

• Implementation using bit wise operators

• Implementation using byte operations (use integers)

• Improve performance
