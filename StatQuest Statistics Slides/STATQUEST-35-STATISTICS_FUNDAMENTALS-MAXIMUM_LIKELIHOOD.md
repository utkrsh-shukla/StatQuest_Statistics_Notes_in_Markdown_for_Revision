<https://www.youtube.com/watch?v=XepXtl9YKwc&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=36>

Today we\'re going to be talking about maximum likelihood.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image1.png)

Let\'s say we weighed a bunch of mice.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image2.png)

The goal of maximum likelihood is to find the optimal way to fit a
distribution to the data.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image3.png)

There are lots of different types of distributions for different types
of data.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image4.png)

Here\'s a normal distribution.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image5.png)

Here\'s what an exponential distribution looks like.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image6.png)

And here\'s what a gamma distribution looks like and there are many
more.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image7.png)

The reason you want to fit a distribution to your data is it can be
easier to work with and it is also more general it applies to every
experiment of the same type.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image8.png)

In this case we think the weights might be normally distributed.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image9.png)

That means we think it came from this type of distribution :

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image10.png)

normally distributed means a number of things :

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image11.png)

1\. first we expect most of the measurements.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image12.png)

For example Mouse weights to be close to the mean or average and we see
low and behold in our data set.

Most of the mice weigh close to the average.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image13.png)

We also expect the measurements to be relatively symmetrical around the
mean.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image14.png)

Although the measurements are not perfectly symmetrical around the mean
they are not crazy skewed to one side either.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image15.png)

This is pretty good normal distributions come in all kinds of shapes and
sizes.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image16.png)

They can be skinny, medium or large boned.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image17.png)

Once we settle on the shape we have to figure out where to Center the
thing.

Is one location better the another ?

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image18.png)

Before we get too technical let\'s just pick any old normal distribution
and see how well it fits the data.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image19.png)

This distribution says most of the values you measure should be near my
average !

The distributions average is the black dotted line in this case that\'s
different from the average of the actual measurements !

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image20.png)

Unfortunately most of the values we measured are far from the
distributions average.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image21.png)

According to a normal distribution with a mean value over here

the probability or likelihood of observing all these weights is low.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image22.png)

What if we shifted the normal distribution over so that its mean was the
same as the average weight ?

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image23.png)

According to a normal distribution with a mean value here

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image24.png)

the probability or likelihood of observing these weights is relatively
high.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image25.png)

If we kept shifting the normal distribution over

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image26.png)

then the probability or likelihood of observing these measurements would
go down again.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image27.png)

We can plot the likelihood of observing the data over the location of
the center of the distribution.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image28.png)

We start on the left side

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image29.png)

and we calculate the likelihood of observing the data and then we shift
the distribution to the right and recalculate.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image30.png)

We just do this all the way down the data once we\'ve tried all the
possible locations we could Center the normal distribution on.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image31.png)

We want the location that maximizes the likelihood of observing the
weights we measured .

This location for the mean maximizes the likelihood of observing the
weights we measured.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image32.png)

Thus it is the maximum likelihood estimate for the mean.

In this case we\'re specifically talking about the mean of the
distribution not the mean of the data however with a normal distribution
those two things are the same great

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image33.png)

Now we have figured out the maximum likelihood estimate for the me.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image34.png)

Now we have to figure out the maximum likelihood estimate for the
standard deviation.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image35.png)

Again we can plot the likelihood of observing the data over different
values for the standard deviation.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image36.png)

Now we found the standard deviation that maximizes the likelihood of
observing the weights we measured.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image37.png)

This is the normal distribution that has been fit to the data by using
the maximum likelihood estimations for the mean and the standard
deviation.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image38.png)

Now when someone says that they have the maximum likelihood estimates
for the mean or the standard deviation or for something else

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image39.png)

you know that they found the value for the mean or the standard
deviation or for whatever that maximizes the likelihood that you
observed.

The things that you observed.

![](media/STATQUEST-35-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD/image40.png)

Terminology alert !

In everyday conversation probability and likelihood mean the same thing.

However in stats land likelihood specifically refers to this situation
we\'ve covered here where you are trying to find the optimal value for
the mean or standard deviation for a distribution given a bunch of
observed measurements. This is how we fit a distribution to data.
