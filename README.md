# Math-functions-as-regression
In image/signal processing topics there is artifact that is
popular for aliasing as you see its sample[wiki]. It often
occurs when sampling rate is too low.
A mathematical function in inverse Fourier transform of an
image with the main lobe and some side lobes affects the
image and an aliasing artifact appears (you will learn a lot
about it in DIP course). You are given a dataset that consists
of some samples by mentioned function; consider it and
follow below parts:
a) Load and plot the dataset using a scatter plot.
b) Is dataset sorted? How do you check it and what is its time complexity? Do we always need
shuffling the dataset in regression methods? If no, give an example. Explain your answers.
c) Split the dataset to train/test parts with the ratio of 8:2 and plot them together in one figure
with different colors to indicate that splitting is done by balanced.
d) According to SSE loss function, implement below function based on gradient descent:
RegressionTrainerGD (x, y, learning_rate, iteration, degree) : weights of regression model
Implement your function such that a plot will be reported which indicates changes
of MSE during the iterations.
You are not allowed to use built-in functions or other tools like packages and etc. to
aim train regression.
Also, It is recommended to reduce learning rate during the iterations. (why?)
e) Using above function, train 15 regressions with combination of 100, 1000, 5000 iterations
and degrees of 1,2,3,5,10. In one 3x5 plot, report obtained regression lines and in another
3x5 plot, report MSE for each train. Discuss about results and explain which one is optima.
f) Implement your strategy (1-b) and find mentioned parameter as well as reports of
regression lines and MSE chart. Also, compare it with best result of previous part.
g) Now, implement normal equation method to train regression model (based on given
formula in slides) and plot regression line then compare with results of previous parts and
discuss about it.
h) Using the 5-fold cross validation with five different values for regularization term, try to
train an optima regression model based on gradient descent with 2500 iterations and
degree of 4. Report result and discuss about obtained value.
Note: mention all details in title of each chart.
