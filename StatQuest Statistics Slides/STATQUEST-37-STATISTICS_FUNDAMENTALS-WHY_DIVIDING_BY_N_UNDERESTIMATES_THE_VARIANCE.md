<https://www.youtube.com/watch?v=sHRBg6BhKjI&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=38>

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image1.png)

Today we\'re going to talk about why dividing by n underestimates the
variance.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image2.png)

This stack quest assumes you already understand why we want to estimate
population parameters.

If not check out the quest.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image3.png)

Also this stack quest picks up from where we left off when we gave an
overview of how to estimate the mean variance and standard deviation.

If you haven\'t seen that one you might want to check it out getting up
from where we left off

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image4.png)

In the stat quest on the mean variance and standard deviation we
measured gene X in five different liver cells

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image5.png)

and then we collected data from more liver cells

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image6.png)

until we had the entire population of liver cells

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image7.png)

and we used all of that data to draw a histogram

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image8.png)

and then we fit a normal curve to the histogram.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image9.png)

That meant we calculated the population mean mu.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image10.png)

The population mean mu equals the sum of the measurements divided by the
number of measurements which equals the average measurement mu.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image11.png)

And we calculated the population variance in standard deviation the
population variance is the average of the squared distances between the
data and the population mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image12.png)

and the population standard deviation is just the square root of the
variance.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image13.png)

Since the standard deviation is in the same units as the original data
we can draw it on the graph.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image14.png)

However since we rarely if ever have enough time and money to measure
every single thing in a population

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image15.png)

we almost always estimate the population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image16.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image17.png)

The estimated population mean x-bar equals the sum of the measurements
divided by the number of measurements and that equals the average
measurement x-bar

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image18.png)

and we estimate the variation and standard deviation.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image19.png)

The estimated population variance is the sum of the squared differences
divided by n minus 1.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image20.png)

And the standard deviation is just the square root of the variance

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image21.png)

and since the standard deviation is in the same units as the original
data we can draw it on the graph.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image22.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image23.png)

We also mentioned that dividing by IDI minus one compensates for the
fact that we are calculating differences from the sample mean instead of
the population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image24.png)

Otherwise we would consistently underestimate the variance around the
population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image25.png)

Then I said I\'d give more details about why dividing by n
underestimates the population variance in a future stat quest !

The future is now.

BAM !!!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image26.png)

To understand why dividing by n underestimates the population variance
we\'ll start with a few simple examples and then we\'ll dive into the
math and prove it once and for all.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image27.png)

In this first example I want to replace the sample mean x-bar with zero
and see what happens.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image28.png)

Now we square the differences between the measurements and zero

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image29.png)

calculate the average

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image30.png)

and that gives us 391.

BAM !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image31.png)

Now let\'s plot that value on a graph.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image32.png)

The y-axis on this graph corresponds to the value we just calculated.

Tt is the variance around a specific point.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image33.png)

And the x-axis corresponds to that point.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image34.png)

Now let\'s move the purple line over to five

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image35.png)

and square the differences between the measurements and five

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image36.png)

and then calculate the average

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image37.png)

and that gives us 240.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image38.png)

And we can plot that point on the graph.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image39.png)

Here\'s another point

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image40.png)

and another.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image41.png)

And this is the variance around the sample mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image42.png)

Remember right now we are dividing by n not n minus 1.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image43.png)

This is the variance around the population mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image44.png)

and here are a few more points.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image45.png)

Note : the point with the smallest variance

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image46.png)

corresponds to the sample mean x-bar

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image47.png)

and this point with a slightly larger variance

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image48.png)

corresponds to the population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image49.png)

So in this case when we plug in the population mean and divide by n we
get a larger variance

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image50.png)

then when we plug in the sample mean and divide by n.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image51.png)

In other words when we use the sample mean we underestimated the
variance we got with the population mean.

BAM !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image52.png)

Now let\'s get 5 new measurements from the same population and see if
the same thing happens .

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image53.png)

When we divide by n with a smallest variance be around the sample mean ?

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image54.png)

So just like before let\'s replace the sample mean x-bar with zero and
see what happens.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image55.png)

Now square the differences between the measurements and zero

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image56.png)

calculate the average

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image57.png)

that gives us 616.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image58.png)

And just like before we can plot variances on the graph.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image59.png)

Here\'s another point and another and another.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image60.png)

This is the variance around the population mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image61.png)

and this is the variance around the sample mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image62.png)

And here are a few more points.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image63.png)

Just like before we see that the minimum variance is at the sample mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image64.png)

So just like before when we plug in the population mean and divide by n
we get a larger variance

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image65.png)

then when we plug in the sample mean and divide by n.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image66.png)

So again when we use the sample mean and divided by n we underestimated
the variance calculated around the population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image67.png)

BAM !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image68.png)

So far we have seen two simple examples where using the sample mean and
dividing by n underestimated the variance as we got with the population
mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image69.png)

Now let\'s prove that this will always happen.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image70.png)

First let\'s go back to the original data

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image71.png)

and the graph that we drew with it.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image72.png)

The first thing we do is realize that even though we only calculated
variance around a handful of points

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image73.png)

we can replace X bar with an unknown value V

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image74.png)

and use this formula to graph all possible values for V.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image75.png)

Note : to emphasize the fact that we are plugging in different values
for V I\'ve modified the X axis label.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image76.png)

No we can take the derivative of this formula with respect to the
unknown value V

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image77.png)

and use it to determine the slope of the curve at different values for V

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image78.png)

and the slope equals zero then we found the value for V that gives us
the smallest variance.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image79.png)

So let\'s move this to the upper left hand corner and solve for the
derivative !!!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image80.png)

The first thing we do is use

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image81.png)

the chain rule what the chain rule

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image82.png)

to solve for the derivative of X minus V squared.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image83.png)

So we bring the square down to the front

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image84.png)

and then we multiply everything by the derivative of X minus V which is
negative one

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image85.png)

because the derivative of X with respect to V is zero and the derivative
of negative V is negative one

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image86.png)

and that gives us the derivative with respect to v.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image87.png)

Now we simplify by multiplying 2 and negative 1.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image88.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image89.png)

Lastly we can simplify things just a little more by moving the negative
2 and 1 divided by n outside of the summation.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image90.png)

This is the derivative with respect to the unknown value, v.

BAM !

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image91.png)

Just to remind you the derivative corresponds to the slope of the Purple
Line

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image92.png)

and we want to find the value for V such that the slope of the Purple
Line equals zero because that is where we will find the minimum
variance.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image93.png)

To make this as clear as possible we will find where the derivative is
zero and the variance is minimized three different ways.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image94.png)

First we\'ll find where the variance is minimized using the observed
data

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image95.png)

then we\'ll find where the variance is minimized for any five
measurements

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image96.png)

and then we\'ll show how to find the minimum variance for any sample
regardless of size.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image97.png)

So let\'s start by plugging the data into the derivative.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image98.png)

The first thing we do is plug in 5 for n since we have 5 measurements

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image99.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image100.png)

then we plug in the measurements.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image101.png)

Since we want to find the value for V where the slope equals zero

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image102.png)

and the derivative is the slope

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image103.png)

we set the derivative equal to zero

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image104.png)

and solve for v.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image105.png)

Note : this negative 2/5 is the only thing making it hard to solve for
V, so

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image106.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image107.png)

we multiply both sides by 5 divided by negative 2 to cancel out the
negative 2/5.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image108.png)

Now solving for V is super easy.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image109.png)

boo boo boo boo boo boo boo boo boo.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image110.png)

V is the average of the five measurements

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image111.png)

which is the sample mean x-bar

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image112.png)

and thus V equals x-bar which equals seventeen point six.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image113.png)

Thus the derivative is zero when V equals x-bar which equals seventeen
point six

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image114.png)

and the variance is minimized when V equals x-bar which equals seventeen
point six.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image115.png)

This is why given this data the value around the sample mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image116.png)

is less than the value around the population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image117.png)

In other words the differences between the data and the sample mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image118.png)

tend to be smaller than the differences between the data and the
population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image119.png)

Thus the differences around the population mean will result in a larger
average

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image120.png)

and the larger average is what we are trying to estimate.

BAM !!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image121.png)

Now let\'s go back to plugging data into the derivative

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image122.png)

and replace the data with five unknown values.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image123.png)

These unknown values represent future measurements.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image124.png)

We\'ll call this unknown value X sub one.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image125.png)

Note : even though X sub one, is on the left side of the graph, just
know that it could be any possible value.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image126.png)

And let\'s call this unknown value X sub 2

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image127.png)

X sub 3 of four

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image128.png)

and X sub 5.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image129.png)

Now let\'s plug the unknown data into the derivative.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image130.png)

Just like before we plug in five four in since we have five measurements

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image131.png)

then we plug in the measurements.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image132.png)

Since we want to find the value for V where the slope equals zero we set
the derivative equal to zero

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image133.png)

and solve for V.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image134.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image135.png)

And just like before we multiply both sides by 5 divided by negative 2
to cancel out the negative 2/5.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image136.png)

Now solving for V is super easy.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image137.png)

boo-boo-boo-boo-boo-boo-boop boom boom

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image138.png)

V is the average of the five measurements which is the sample mean x-bar

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image139.png)

so no matter what five measurements we start with the value that gives
us the minimum variance is x-bar.

BAM !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image140.png)

Now let\'s see what happens when we have any size sample ie a sample
with in measurements.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image141.png)

So let\'s plug the unknown data into the derivative.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image142.png)

Now instead of replacing n with a number, we just leave it, since we
have n measurements.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image143.png)

Now we plug in all in measurements

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image144.png)

and set the derivative equal to zero

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image145.png)

and solve for V.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image146.png)

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image147.png)

First we multiply both sides by n divided by negative 2 to cancel out
the negative 2 divided by N.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image148.png)

Now solving for V is super easy .

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image149.png)

V is the average of the end measurements

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image150.png)

which is the sample mean x-bar.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image151.png)

So no matter how many measurements we start with the value that gives us
the minimum variance is X bar.

Double BAM !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image152.png)

Thus when we divide by n, the value around the sample mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image153.png)

is always less than the value around the population mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image154.png)

unless the sample mean is the exact same as the population mean and that
pretty much never happens.

Triple bam !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image155.png)

PS : Before we go let\'s talk about why we square the differences
instead of using the absolute value.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image156.png)

Remember when we use the derivative to find the minimal value ?

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image157.png)

Doing the calculus and understanding that this formula underestimated
the variance around the population mean was relatively easy.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image158.png)

In contrast if we use the absolute value instead we\'d get a graph that
looked like this

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image159.png)

and since we have this sharp angle at the minimum value

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image160.png)

and derivatives do not exist at sharp angles like this

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image161.png)

then finding the minimum value is much harder with the absolute value
than with the square.

BAM !!!

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image162.png)

In summary :

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image163.png)

When we only divide by n

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image164.png)

we underestimate the variation in the data around the population main.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image165.png)

This is because the differences between the data and the sample mean

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image166.png)

tend to be smaller than the differences between the data and the
population mean.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image167.png)

Thus the differences around the population mean will result in a larger
average

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image168.png)

and the larger average is what we are trying to estimate.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image169.png)

So, if you are estimating the population variance, divided by n minus
one.

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image170.png)

PS : if you\'re wondering why we divide by n minus 1 and not n minus 0.5
or n minus 2

![](media/STATQUEST-37-STATISTICS_FUNDAMENTALS-WHY_DIVIDING_BY_N_UNDERESTIMATES_THE_VARIANCE/image171.png)

then you\'ll just have to wait for the stat quest on expected values.
