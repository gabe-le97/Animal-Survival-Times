# Animal-Survival-Times
Data Science analysis & modeling on the effects of different treatments and poisons on a variation of 
animals using the Jupyter Notebook.
***
Some tools/techniques used were: 
* Data Manipulation
* Data Visualization
* Machine Learning
* Confidence Intervals
* Bootstrap Procedure
* Decision Trees
* k-Nearest Neighbors
* Artificial Neural Networks
* Regression
* Multi-Layer Perceptrons

***

__Intro__:
* I will be analyzing a csv file on animal survival times when given one of 3 poisons and one of 4 forms of treatment. 
I will be attempting to see if there is a correlation between the poisons used and the form of treatment used against it. 
There are 48 total animals (4 randomized types), the poison (levels 1 - 3), the treatment (levels A - D), and the 
survival time (units of 10 hours). I will construct a multitude of graphs and analyze the results thoroughly 
to find a correlation below. I will also be finding the best confidence interval and trying to see which data structure 
performs best on the data set using regression. Ultimately, I will see which treatment performs best on which poison. 
The different treatments will be assigned as the independent variable.

__Body__:
* Modeling and Analysis were done here.

__Conclusion__:
* The artificial neural network and confidence intervals show that this data can be worked without a large error. 
After analyzing and reviewing all the data, it is determined that poison 3 is the most lethal to the animal's 
survival time. It has the most clusters in a spot with the least time (quicker death). Poison 2 and 1 have 
their clusters spread around, but 2 has more in a spot with a lower time. So that means the least lethal 
poison is poison 1. After more analyzing, it looks like each treatment has a different effect on each poison 
regarding survival times. It is evident that treatment B works the best because the animal survival times are 
the highest when this treatment is used, no matter which poison it is. Next would be treatment D because most 
of the spots are less than B and higher than C and A. The next would be treatment C. Treatment C lies around 
the bottom but A clearly lies the lowest. Each treatment approximately does the same against each type of poison. 
So in conclusion, poison 3 is the most lethal and treatment B is the most effective. If there were more details 
in the dataset, we could determine what the name/composition of the poison and treatment that were used against a 
specific animal to do scientific research.

***

__Appendix__:
* [Documentation](https://vincentarelbundock.github.io/Rdatasets/doc/boot/poisons.html)
* [poisons.csv](https://vincentarelbundock.github.io/Rdatasets/csv/boot/poisons.csv)
