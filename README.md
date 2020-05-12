# Spectral-Forecast
An implementation after Paul A. Gagniuc et al. Spectral Forecast: A general purpose prediction model as an alternative to classical neural networks. Chaos 30, 033119 (2020); doi: 10.1063/1.5120818 https://aip.scitation.org/doi/pdf/10.1063/1.5120818  

This project uses 3 arrays as the inputs in the main file, healthyArray and illArray as samples from a healthy and a non-healthy patients, while predictionArray is as sample from a patient that wants to find out his health state, and gives the user an output as a similarity index between the array sample from a patient and the other samples. The output is represented by the values that are calculated and displayed in the editText and in a line graph. 
The article above containts the equations that were used to find out the result in this program.

New things that can be added: a slider can be implemented to change the data in the prediction array and a button that can recalculate the similarity index when pressed. Also, the algorithm for finding the maximum matrices can be improved, going from the usual way by comparing a value in the matrix with the next value until we find the highest value, using a single line of code using the functions already built in java for finding out the maximum. The code can also be modified to use any kind of matrix, of any size set by the user.

![Example](https://github.com/DominicBlack/Spectral-Forecast/blob/master/Screenshot_20200512-105408_Spectral-Forecast.jpg)
