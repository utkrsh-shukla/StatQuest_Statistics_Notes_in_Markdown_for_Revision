<https://www.youtube.com/watch?v=p3T-_LMrvBc&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=37>

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image1.png)

Today we\'re going to be talking about the exponential distribution and
its maximum likelihood estimate.

W e\'ll start with a brief introduction of the distribution and what
it\'s used for.

And then we\'ll dive into the math and nitty-gritty of how maximum
likelihood is applied to it.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image2.png)

So what is the exponential distribution.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image3.png)

It\'s a statistical distribution that models the time between events.
For example how long will you wait before you get another text message
or how much time will pass before the next person views this video.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image4.png)

Here\'s what an exponential distribution looks like the x-axis is the
amount of time between events.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image5.png)

The y-axis is scaled so that the total area under the curve equals 1.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image6.png)

If we were interested in the probability of an event like someone
viewing this video happening within 0 to 5 seconds we solved for the
area under the curve from x equals 0 to x equals 5 seconds.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image7.png)

Here\'s the equation for an exponential distribution.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image8.png)

You plug in some value for X

and out comes a value for y .

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image9.png)

Lambda is called the rate parameter and it is proportional to how
quickly things happen.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image10.png)

In this graph lambda equals 1 and this models an event happening like
someone watching this video on average every second.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image11.png)

Here lambda equals two and this models someone watching the video on
average twice every second.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image12.png)

Here lambda equals 0.5 and this models someone watching this video on
average once every two seconds.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image13.png)

The goal of maximum likelihood is given a set of measurements to find an
optimal value for lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image14.png)

So assume I collected a lot of data about how much time passed between
views of this video.

X sub 1 equals the amount of time that passed between the first and
second views.

X sub 2 equals the amount of time that passed between the second and
third views.

X sub 3 equals the amount of time that passed between the third and
fourth views.

Etc etc etc

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image15.png)

Here are the n measurements.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image16.png)

For now let\'s assume we already have a good value for lambda.

What\'s the likelihood of lambda given our first measurement X sub 1.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image17.png)

Here\'s the likelihood function we have the likelihood of lambda

given that we have this measurement X sub 1

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image18.png)

and the likelihood equals this equation this equation is just the
equation for the curve with X sub 1 plugged into it.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image19.png)

If X sub 1 was here

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image20.png)

the likelihood of lambda would be this value on the y-axis.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image21.png)

Similarly the likelihood of lambda given the second measurement X sub 2
is just the equation for the curve with X sub 2 plugged into it.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image22.png)

If X sub 2 was here

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image23.png)

the likelihood of lambda would be this value on the y-axis.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image24.png)

What is the likelihood of lambda given both X sub 1 and X sub 2.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image25.png)

Well here are the individual likelihood functions

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image26.png)

and here\'s the combined likelihood function.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image27.png)

Because we are interested in X sub 1 and X sub 2 we multiply the 2
likelihood functions together.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image28.png)

Here I\'ve just plugged in the 2 likelihood equations

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image29.png)

and now I\'ve pulled the two lambdas out

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image30.png)

and lastly I can add the exponents together.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image31.png)

Thus this equation is the likelihood of lambda given X sub 1 and X sub 2
.

Bam !!!

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image32.png)

What is the likelihood of lambda ?

Given all of the data X sub 1 X sub 2 all the way to X sub n.

Here\'s the likelihood function that includes all of the data we have
collected it is equal to the product of all the individual likelihoods.

Here I\'ve just plugged in all the individual likelihood equations and
now I\'ve just pulled out all of the lambdas and lastly I\'ve added all
of the exponents together.

Thus this equation is the likelihood of lambda given all of the data X
sub 1 X sub 2 all the way to X sub M.

BAM !!!

What if we don\'t have a good value for lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image33.png)

Well we try different values for lambda to find a good one

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image34.png)

to find the maximum likelihood we

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image35.png)

one take the derivative of this

and to solve for lambda when the derivative is set to be equal to zero.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image36.png)

Here\'s a graph of the likelihood using different values for lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image37.png)

At the maximum likelihood the slope and thus the derivative will be
equal to zero to.

Find the maximum likelihood estimate for lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image38.png)

Step 1 we take the derivative of the likelihood function.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image39.png)

Any time you have a function with an exponential in it it\'s almost
always easier to take the derivative of the log of that function.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image40.png)

So that\'s what we\'re going to do.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image41.png)

We can do this because the derivative of a function and the derivative
of the log of a function equals zero at the same place so for the
purposes of finding where the derivative equals zero the original
function and its log are interchangeable.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image42.png)

Since we are now working with the log of the function we can split up
the multiplication into addition.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image43.png)

Next we move lambdas exponent in to be in front of the log

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image44.png)

and the log of the exponential function reduces to just its exponent.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image45.png)

If any of this fancy log stuff is confusing you check out the stat quest
on logs.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image46.png)

Finally we take the derivative of both parts of the equation with
respect to lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image47.png)

Now we move on to step two set the derivative to be zero and solve for
lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image48.png)

Here I added X sub 1 plus X sub 2 plus all the way to X sub n to both
sides causing the term to cancel out on the right side of the equal
sign.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image49.png)

Then I just multiplied both sides by lambda

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image50.png)

and lastly I divided both sides by X sub 1 plus X sub 2 plus all the way
to X sub n

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image51.png)

This is the maximum likelihood estimate for lambda.

Double BAM !!!

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image52.png)

Now whenever we collect a lot of data about how much time takes place
between events we just plug those values into this equation and we\'ll
get the maximum likelihood estimate for lambda and then we can fit an
exponential distribution to our data.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image53.png)

For example if two seconds pass between the first and second times this
video was watched

then X sub 1 would equal 2

and of 2.5 seconds passed between the second and third times this video
was watched

then X sub 2 would equal 2.5

and 1.5 seconds passed between the third and fourth times this video was
watched

then X sub 3 would equal 1.5.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image54.png)

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image55.png)

If that\'s all our data then we just plug in to 2.5 and 1.5 into the
formula for the maximum likelihood estimate for lambda and solve for
lambda.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image56.png)

Thus given the data the maximum likelihood estimate for lambda is 0.5.

![](media/STATQUEST-36-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_EXPONENTIAL_DISTRIBUTION/image57.png)

And this is what an exponential distribution looks like when lambda
equals 0.5.
