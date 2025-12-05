# Coursework Project

Part 1: Random walk Metropolis

In this part, you are asked to work with the Markov Chain Monte Carlo algorithm, in
particular the Metropolis-Hastings algorithm. The aim is to simulate random numbers
for the distribution with probability density function given below
f (x) = 1
2 exp (−|x|),
where x takes values in the real line and |x|denotes the absolute value of x. More
specifically, you are asked to generate x0, x1, . . . , xN values and store them using the
following version of the Metropolis-Hastings algorithm.

Apply the random walk Metropolis algorithm using N = 10000 and s = 1. Use the
generated samples (x1, . . . xN ) to construct a histogram and a kernel density plot in
the same figure. Note that these provide estimates of f (x).Overlay a graph of f (x) on
this figure to visualise the quality of these estimates. Also, report the sample mean
and standard deviation of the generated samples (Note: these are also known as the
Monte Carlo estimates of the mean and standard deviation respectively).


Part 2: Data analysis on flight data

The 2009 ASA Statistical Computing and Graphics Data Expo consisted of flight arrival
and departure details for all commercial flights on major carriers within the USA from Oc-
tober 1987 to April 2008. This is a large dataset; there are nearly 120 million records in
total, and it takes up 1.6 gigabytes of space when compressed and 12 gigabytes when un-
compressed. The complete dataset, along with supplementary information and variable
descriptions, can be downloaded from the Harvard Dataverse at
https://doi.org/10.7910/DVN/HG7NV7
Choose any subset of ten consecutive years and any of the supplementary information
provided by the Harvard Dataverse to answer the following questions using the principles
and tools you have learned in this course:
(a) What are the best times and days of the week to minimise delays each year?
(b) Evaluate whether older planes suffer more delays on a year-to-year basis.
(c) For each year, fit a logistic regression model for the probability of diverted US flights
using as many features as possible from attributes of the departure date, the sched-
uled departure and arrival times, the coordinates and distance between departure
and planned arrival airports, and the carrier. Visualize the coefficients across years.

