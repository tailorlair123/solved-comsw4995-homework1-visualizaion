Download Link: https://assignmentchef.com/product/solved-comsw4995-homework1-visualizaion
<br>
<h1>Task 1: Density Plots</h1>

1.1 Plot the longitude vs latitude several ways within a single figure (each in its own axes):

<ul>

 <li>Using the matplotlib defaults.</li>

 <li>Adjusting alpha and marker size to compensate for overplotting.</li>

 <li>Using a hexbin plot.</li>

 <li>Subsampling the dataset.</li>

</ul>

For each but the first one, ensure that all the plotting area is used in a reasonable way and that as much information as possible is conveyed; this is somewhat subjective and there is no one right answer. [45 pts]

1.2 In what areas are most of the anomalies (measurements) located? [5pts]

<h1>Task 2: Visualizing class membership</h1>

Visualize the distribution of Brightness temperature I-4 as a histogram (with appropriate settings). Let’s assume we are certain of a fire if the value of temperature I-4 is saturated as visible from the histogram.

2.1 Do a small multiples plot of whether the brightness is saturated, i.e. do one plot of lat vs long for those points with brightness saturated and a separate for those who are not (within the same figure on separate axes). You can pick any of the methods from 1.1 that you find most suitable. Can you spot differences in the distributions? [20 pts]

2.2 Plot both groups in the same axes with different colors. Try changing the order of plotting the two classes (i.e. draw the saturated first then the non-saturated or the other way around).

Make sure to include a legend. How does that impact the result? [20 pts]

2.3 Can you find a better way to compare the two distributions? [10pts]

<h1>Bonus</h1>

(no points and only semi-related to the rest of the class)

Find a dataset for classification or regression on <u>​</u><a href="https://kaggle.com/">Kaggle</a>​. Install dabl (‘pip install dabl’) and use <a href="https://amueller.github.io/dabl/dev/generated/dabl.plot.html#dabl.plot">dabl.plot</a><u>​</u> to visualize the dataset. Briefly discuss the insights from this output. See how you can improve over these visualizations and what new insights you can get. As mentioned in class, dabl will not be allowed for any of the graded assignments. If you get an error, file an issue at <a href="https://github.com/amueller/dabl">https://github.com/amueller/dabl</a>​ .