
****************************************************************************************************************************************************************

 PLEASE AVOID THIS PATCH IF YOU SUFFER FROM EPILEPSY 

****************************************************************************************************************************************************************

Kadenze Assignment 5 

for more info: https://www.kadenze.com/courses/machine-learning-for-musicians-and-artists-v

This project uses filtered sines’s audio parameters to modify a video matrix.
By modifying some audio parameters (frequencies and filter values) user will  be able to modify several settings of two video matrixes (number of planes, lines and rows).

This project is meant to be used with Wekinator (http://www.wekinator.org) as a Machine Learning  middleware between a MaxMSP audio signal input and a MaxMSP video signal output (within the same patch). So basically MaxMSP sends data to wikinator through OSC communication, and once the data is “cooked” by wekniator, it receives some values back from the incoming OSC port and modifies the video matrix.

Wekinator is set to regression mode, and is to receive 7 input and to output 6 values. Algorithm is Neural Network.
Patch is very simple, sound and video might be annoying by some (most ;-). 


How to use it: 

1) Turn ON the DAC (if it does not turn ON automatically, as it should)
2) Play with the seven number input, or alternatively press the space bar to create random sounds
3) press the button to send the data to train wekinator (in wekinator you might want to play with the output to associate the input to your desired video signal)