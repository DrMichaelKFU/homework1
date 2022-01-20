# homework1
Sampling a 1D Signal
In this homework, you will create a function that performs a series of basic MATLAB tasks. You have taken a MATLAB course before and are expected to know how to create a function to perform basic tasks. In case you are unprepared for this homework, you may reference the MATLAB workshop linked below (and mentioned in the first lecture) to review. All of the MATLAB skills necessary to complete this homework are presented in the MATLAB workshop.

MATLAB WORKSHOP:
 https://youtube.com/playlist?list=PLqT1jKsokNS_AQ7_ZQlNAzmUQI35td6jt

# Summary

For homework 1, you will create one function named HW1_########## (where ########## is replaced by your student ID, e.g., HW1_2018012345). This function will be called with three inputs, HW1_##########(amp1, freq1, amp2, freq2, dec), where amp1 and amp1 are sinusoidal amplitudes, freq1 and freq2 are frequencies given in Hz, and dec is an integer value of 1 or 2. The output of the function is a single variable, fout, and depends on the value of dec.

For all parts of homework 1, consider the continuous function: 

f(t)=(amp1)*sin(2*pi*freq1*t)+(amp2)*cos(2*pi*freq2*t).

# Part 1: Aliasing

If the value of dec is 1, your function will display two plots of f(t) on the same figure and plot. 

In figure(1), first, plot f(t) as a red line using 100 samples from t=0 to t=10 seconds. Second, overlay a plot of f(t) as a blue line using 23 samples from t=0 to t=10 seconds. Include a legend in the top right corner, naming the red line “100 samples” and the blue line “23 samples.” 

Label the x- and y-axes. Ensure the x-axis ranges from 0 to 10 seconds, and the y-axis ranges from -1.5*(amp1+amp2) to 1.5*(amp1+amp2).

Output the 23 values of f(t) for the 23-sample in the variable fout. 

# Part 2: Nyquist Criterion

If the value of dec is 2, your function will calculate the Nyquist criterion for reconstructing the signal from samples. Output the Nyquist criterion frequency value [Hz] in fout.

Additionally, plot in figure(1) the signal f(t) first in red with 10,000 samples from t=0 to t=10 seconds, then overlay a plot of f(t) in blue sampled at the calculate Nyquist criterion frequency.  Include a legend in the top right corner, naming the red line “10,000 samples” and the blue line “Nyquist Criterion.” 

Label the x- and y-axes. Ensure the x-axis ranges from 0 to 10 seconds, and the y-axis ranges from -1.5*(amp1+amp2) to 1.5*(amp1+amp2).

# Some Notes

Do NOT use clear, close all, or clc commands inside your function. This will result in a 0.

You must display the plots in figure(1).

Submitting Your Homework

You must submit your function with the file name HW1_##########.m (where ########## is replaced by your student ID, e.g., HW1_2018012345.m).
