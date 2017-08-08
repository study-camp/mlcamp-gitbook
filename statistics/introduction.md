# Introduction To Statistics

These are notes captured from the [Udacity Intro to Statistics Course.](https://www.udacity.com/course/intro-to-statistics--st101)

## Looking At Data

### Scatter Plots

Scatter plots are way to visualize the relationship between two variables. If the two variables are related then there is "linearity" in the graph and we can predict the value of one variable given the value of the other variable. If the graph consists of random points scattered all over the graph then the variables are not related. We cannot predict one variable's value based on the other variable.

### Bar Charts

A bar chart can be used to show comparisons among categories. A bar chart is a common way to view \*\*categorical data\*\*. A common type of bar chart is a \*\*histogram\*\*. A histogram shows the \*frequency\* at which categories appear in a data set. For example, if we ask a group of people what their salaries are we will get a range of answers. If we sort the salaries from lowest to highest and put them into groups \($50,000 - $60,000; $61,000 - $70,000 and so on\) a histogram would show the frequency at which each grouping occurrs - e.g., 5 people in the first group, 10 people in the second and so on.

### Pie Charts

Pie charts are used to view relative data. A pie chart shows the relative proportion of quantities. For example, there is an election with two political parties. One party gets 60% and the other gets 40%. This pie chart would have on slice that takes 60% of the pie and another slice that takes up 40%.

### Programming Charts

This is an optional module but, since this is a study group whose purpose is technology and programming, it is probably a good idea to do it. It uses a python library called "plotting". This is not a standard graphing library so don't bother googling it. It is a Udacity specific library that is actually a wrapper for matplotlib - which \*is\* a standard graphing library. Details and instructions are [here](https://www.udacity.com/wiki/plotting-graphs-with-python#!#overview). One side effect of going through the exercise of using this library as opposed to just using matplotlib is that, if your python skills need work, you get to see the source code and you can get practice working in the python environment.

## Statistics Can Be Misleading

### Simpson's Paradox

There are two baseball players, Player1 and Player2. In each of three seasons Player2 has a higher batting average than Player1. \(Batting Average is a percentage and is calculated by dividing "Hits" by "At Bats".\) However, when the three seasons are aggregated Player1 actually has the higher overall batting average!


Player | Season1 | Season2 | Season3 | Combined
-------|---------|---------|---------|---------
P1 | 12/48 (.250) | 183/582 (.314) | 190/654	(.291) | **385/1284 (.300)**
P2 | **104/411 (.253)** | **45/140 (.321)** | **163/495 (.329)** | 312/1046 (.298)	

The key takeaway is that statistics can be misleading and one can draw the wrong conclusions from them if they are not done correctly. One should be skeptical of statistics and one must really understand the problem in order to turn raw data into statistics.

A nice visual explanation of Simpson's Paradox is here: http://flowingdata.com/2013/09/19/a-visual-explanation-of-simpsons-paradox/

## Probability ##
Probability is the opposite of statistics. In statistics we are given data and try to infer possible causes related to the data whereas in probability we are given the description of the causes and we need to predict the data. That is, probability is the method of describing the anticipated outcome of something - a coin flip, say - and the reason for studying probablity is because it gives us the means for describing the relationship between the data and the underlying causes.

The notation for probability is **P** and the probability of event "x" occurring is P(x). If something occurs 100% of the time it has a probability of 1. P(x) = 1.

### Probability of a single event ###

A single event is something like a coin toss or the roll of a single die. In the case of a single coin toss there are two equally possible outcomes, heads or tails, so the probability of either event occurring is 50%. P(H) = 0.5 and P(T) = 0.5. The probabilities of each single event always add up to 1. If P(H) is one event then P(T) is the *opposite event*. The opposite event is calculated as:
P(opposite event) = 1 - P(original event). So, in our case P(T) = 1 - P(H).

### Probability of independent events ###

To get the probability of two successive events you multiply them together. For example, P(H) = 0.5. For two successive coin flips that result in heads, denoted P(H,H), to occur we multiply their respective probabilities together. In this case, 0.5 and 0.5. 0.5 * 0.5 = 0.25. So, P(H,H) = 0.25. The outcome of one coin flip does not affect the outcome of the other. Thus, they are independent events. Independent events are also called *composite events*. 

### Probability of dependent events ###

In this case we want to know the probability of something given that something else happened. For example, we might want to know the probability of "x" given that "y" occurs. This is notated as P(x | y). This is known as a *conditional probability*.



