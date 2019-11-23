![img](plot.png)

Correlation matrices are a powerful visual tool. Your matrix shows the correlation by color and with the number. While normally using 2 features for the same variable is not advisable, in this case it allows the user to get a synoptic understanding of the patterns, while being able to look at the details as they wish. 

It is not clear which numbers are printed in red and which in white. If the color is changed it should be changed in some meaningful way, since this will attract the reader's attention. It seems like your threshold is 0.5/-0.5, which makes it the quartile range, but it is not clear enough that this is the pattern to make it not distracting. 

Your plot uses a red-green scheme which is not color-blind compliant. The amount of information is large, and the correlation matrix looses power because of the large number of cells. If you want to show a correlation matrix with such large number of cells you should order the cells by some meaningful pattern. The abbreviationsa re not parsable. since the matrix repeats identical information on the upper-triangular and lower-triangular part a better use of space would be to only plot the lower-triangular and to put the legend in the now empty half og the plot.


