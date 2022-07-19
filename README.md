# Neuroscience Research in Collaboration with Fortin Lab

### Purpose

The goal of this research is to determine if we can predict what odor the rat is 
thinking of by decoding hippocampal neurons. 

### Tools and Installation


We have use multiple R packages to make models and plots, including tidyverse, runner, R.matlab, janitor, readr, dplyr, gridExtra, caret, InformationValue, ISLR, nnet, broom, ggplot2, ggstance, devtools, ggbiplot, summarytools, neuralnet, pls, leaps.



### Methods

__Peri-stimulus time histograms__ (PSTHs) were used to visual individual neurons 
firing count over the average time of all trials. A trial represents each time 
the rat held its nose in the odor port and averaged around 1000-1500 ms. Five 
PSTHs were created for each neuron separated by odor. The visuals were then used 
to find firing patterns in each neuron. 

__Principal Component Analysis__ is a dimensionality-reduction method that was
implemented to build our __multinomial logistic regression__ model. The first 15
principal components are our predictors with odors A-E as our response. 



### Conclusion

### Credits

Team member: Giles Carlos, Yi Ling Chiu, Alyssandrei Parinas, Cadee Pinkerton, James Owens
Special thanks to: Keiland Cooper, Mine Dogucu, Norbert Fortin, Jessica Jaynes, Mansi Saraf, Roberto Pelayo, Babak Shahbaba





