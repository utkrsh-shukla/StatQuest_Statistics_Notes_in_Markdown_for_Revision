<https://www.youtube.com/watch?v=Dn6b9fCIUpM&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=40>

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image1.png)

Today we\'re going to talk about maximum likelihood for the normal
distribution and it\'s gonna be clearly explained.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image2.png)

Note : this stack quest follows up on the stack quest maximum likelihood
clearly explained

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image3.png)

as well as the stack quest probability versus likelihood

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image4.png)

lastly this stack quest assumes you are already familiar with the normal
distribution.

If not check out the stack quest the normal distribution of clearly
explained.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image5.png)

Let\'s start with this nasty-looking equation

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image6.png)

it\'s the equation for the normal distribution or normal curve.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image7.png)

It has two parameters :

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image8.png)

the first parameter, the Greek character mu, determines the location of
the normal distribution's mean.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image9.png)

A smaller value for MU moves the mean of the distribution to the left

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image10.png)

and a larger value for MU moves the mean of the distribution to the
right.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image11.png)

The second parameter, the Greek character Sigma, is the standard
deviation and determines the normal distributions width.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image12.png)

A larger value for Sigma makes the normal curve shorter and wider

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image13.png)

and a smaller value for Sigma makes the normal curve taller and
narrower.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image14.png)

In this stat quest, we\'re going to use the likelihood of the normal
distribution

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image15.png)

to find the optimal parameters from mu (the mean) and Sigma (the
standard deviation) given some data, x.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image16.png)

Let\'s start with the simplest data set of all a single measurement.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image17.png)

Here we\'ve measured a single Mouse and it weighs 32 grams.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image18.png)

Now, just to see what happens, we can overlay a normal distribution with
mu equals 28 and Sigma equals 2 onto the data.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image19.png)

To determine the likelihood of the data given this curve we can plug the
numbers into the likelihood function

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image20.png)

and then plug the numbers into this equation

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image21.png)

and here\'s the equation with mu equals 28 Sigma equals 2 and x equals
32 plugged in.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image22.png)

Now just do the math

plug and chug plug and chug

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image23.png)

and the likelihood of the curve with mu equals 30 and Sigma equals 2
given the data, is 0.03.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image24.png)

Thus, the y-axis value here is 0.03.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image25.png)

Now we can shift the distribution a little bit to the right by setting
mu equals 30 and then calculate the likelihood.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image26.png)

Again, we just plug the numbers into the likelihood function

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image27.png)

and now we just plug and chug !

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image28.png)

and the likelihood of the new curve with mu equals 30, and Sigma equals
2, given the data, is 0.12.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image29.png)

Thus, the y-axis value here is 0.12.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image30.png)

If we decide to fix Sigma equals 2, so that it is a given, just like the
data

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image31.png)

then we can plug in a whole bunch of values for mu and see which one
gives the maximum likelihood.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image32.png)

For example, if we start with the mean of the distribution over here on
the left at 20 grams

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image33.png)

then we plug mu equals 20 into the equation

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image34.png)

and we get a crazy small likelihood

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image35.png)

and then we can plot the likelihood on a graph.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image36.png)

The y-axis is the likelihood value

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image37.png)

and the x-axis is for the different values that we plug in for MU

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image38.png)

each time we change mu, we calculate the likelihood and plot it.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image39.png)

We can identify the peak in the likelihood graph by determining where
the slope of the curve equals zero.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image40.png)

In this case, the slope equals zero when mu equals 32.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image41.png)

Now we can fix mu equals 32 and treat it like a given, just like the
data

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image42.png)

and we can plug in different values for Sigma to find the one that gets
the maximum likelihood.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image43.png)

Note : you actually need more than one measurement to find the optimal
value for Sigma.

I\'ll leave the reason why as an exercise for the viewer !

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image44.png)

That said if we had more data

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image45.png)

then we could plot the likelihoods for different values of Sigma

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image46.png)

and the maximum likelihood estimate for Sigma would be at the peak with
a slope of the curve equals zero.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image47.png)

The goal of this super simple example is to convey the basic concepts of
how to find the maximum likelihood estimates for MU and Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image48.png)

To solve for the maximum likelihood estimate for MU, we treat Sigma like
it\'s a constant and then find where the slope of its likelihood
function is 0

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image49.png)

and to solve for the maximum likelihood estimate for Sigma we treat me
like it\'s a constant and then find where the slope of its likelihood
function is 0.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image50.png)

The example with one measurement kept the math simple, but now I think
we\'re ready to dive in a little deeper

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image51.png)

so let\'s use a two sample data set to calculate the likelihood of a
normal distribution.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image52.png)

Crazy times !

To keep track of things, let\'s call the mouse that weighs 32 grams X
sub 1.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image53.png)

and the mouse that weighs 34 grams X sub 2.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image54.png)

And again just to see what happens, let\'s overlay a normal distribution
with mu equals 28 and Sigma equals 2 onto the data.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image55.png)

We\'ve already seen how to calculate the likelihood for this curve given
X sub 1, the mouse that weighs 32 grams

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image56.png)

and we can calculate the likelihood for the curve given X sub 2 by
plugging in 34 into this likelihood function

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image57.png)

but what\'s the likelihood of this normal curve given both X sub 1 and X
sub 2 ?

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image58.png)

In other words, what\'s this ?

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image59.png)

Because these measurements are independent (ie weighing X sub 1 did not
have an effect on weighing X sub 2)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image60.png)

the likelihood of a normal distribution with mu equals 28 and Sigma
equals 2

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image61.png)

given the data X sub 1 equals 32 and X sub 2 equals 34

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image62.png)

is just the likelihood of the distribution given X sub 1

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image63.png)

times

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image64.png)

the likelihood of the distribution given X sub 2.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image65.png)

So we just plug in the numbers and do the math

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image66.png)

and that gives us a really small number.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image67.png)

If we had a third data point, then

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image68.png)

we just add it to the given side of the overall likelihood

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image69.png)

and add another individual likelihood term to our multiplication.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image70.png)

With n data points

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image71.png)

we add all n data points to the given side of the overall likelihood
function

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image72.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image73.png)

then multiplied together all in individual likelihood functions.

BAM !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image74.png)

Now that we know how to calculate the likelihood of a normal
distribution and when we have more than one measurement we just multiply
together the individual likelihoods let\'s solve for the maximum
likelihood estimates for MU and Sigma.

Brace yourself for a lot of math but don\'t freak out !

We\'ll go through it one step at a time.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image75.png)

Here\'s the likelihood function without any value specified for MU and
Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image76.png)

It equals the product of the likelihood functions for the N individual
measurements

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image77.png)

and here\'s what the equation looks like.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image78.png)

What we need to do is take two different derivatives of this equation.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image79.png)

One derivative will be with respect to MU, when we treat Sigma like
it\'s a constant

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image80.png)

and we can find the maximum likelihood estimate for MU by finding where
this derivative equals zero.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image81.png)

The other derivative will be with respect to Sigma, when we treat mu
like it\'s a constant

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image82.png)

and we can find the maximum likelihood estimate for Sigma by finding
where this derivative equals zero.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image83.png)

But before we try to take any derivatives let\'s take the log of the
likelihood function.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image84.png)

We do this because it makes taking the derivative way, way easier

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image85.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image86.png)

and the likelihood function and the log of the likelihood function both
peak at the same values for MU and Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image87.png)

I know it\'s hard to tell that the log likelihood function for Sigma
peeks, here but just take my word for it.

I double-checked !

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image88.png)

Here\'s the log of the likelihood.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image89.png)

Now we\'re going to go step by step, through all of the transformations
that the log has on this function.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image90.png)

Just a heads up - the log is going to do a lot of transformations to
this function so hang in there !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image91.png)

First, the log transforms the multiplication

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image92.png)

into addition.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image93.png)

Now we log transform the individual likelihood function.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image94.png)

Let\'s focus on this one first.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image95.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image96.png)

Step 1 : move the log of the first likelihood function to the top
left-hand side of the screen for reference.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image97.png)

Step 2 : convert the multiplication

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image98.png)

into addition.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image99.png)

Step 3 : convert 1 over the square root

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image100.png)

into the exponent negative 1/2

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image101.png)

and convert the exponent

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image102.png)

into multiplication.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image103.png)

Step 4 : convert the negative 1/2 exponent

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image104.png)

into multiplication

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image105.png)

and the log of e equals 1

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image106.png)

so we can remove it.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image107.png)

Step five : the log can convert the multiplication of two times pi times
Sigma squared

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image108.png)

into addition of two times pi and Sigma squared

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image109.png)

and there\'s nothing more to do to this term

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image110.png)

so it doesn\'t change.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image111.png)

Step 6 : convert the exponent in the log of Sigma squared

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image112.png)

into 2 times the log of Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image113.png)

Step 7 : lastly the 2/2 term cancels out.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image114.png)

BAM !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image115.png)

We started with this

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image116.png)

and after the log transformation, ended up with this !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image117.png)

I know all of this log transformation stuff looks bonkers the first time
you see it.

Just remember it will make it easier to take the derivative !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image118.png)

So now we can go back to the original likelihood and turn this

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image119.png)

into this.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image120.png)

And by following the same steps, we can transform the remaining parts of
the sum

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image121.png)into this.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image122.png)

Now let\'s simplify this equation.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image123.png)

Just to be clear about how we simplify keep in mind that since we have n
data points

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image124.png)

that means we have a term for the first data point X sub 1

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image125.png)

and that this represents the terms for the remaining n minus 1 data
points.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image126.png)

So we can combine this from the first term

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image127.png)

with the remaining n minus 1 occurrences

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image128.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image129.png)

1 plus n minus 1 equals n.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image130.png)

Then all n of the negative log of sigma\'s can be combined.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image131.png)

And the last parts of each term stay the same.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image132.png)

This is the log of the likelihood function after simplification, and it
is what we will take the derivative of.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image133.png)

So let\'s move it to the top for reference.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image134.png)

We\'ll start by taking the derivative with respect to MU.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image135.png)

This derivative is the slope function for the log of the likelihood
curve

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image136.png)

and we\'ll use it to find the peak aka where the slope equals zero.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image137.png)

The first term doesn\'t contain mu so it\'s derivative is 0.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image138.png)

The second term doesn\'t contain mu either, so it\'s derivative is also
0.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image139.png)

The third term contains mu, so now we have to work.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image140.png)

Specifically, the numerator contains mu and we have to apply

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image141.png)

the chain.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image142.png)

So we start with the outer derivative of negative 32 minus mu squared

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image143.png)

and then we multiply that by the derivative of (32 minus mu)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image144.png)

and then we simplify.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image145.png)

Because the derivative is with respect to MU, Sigma is a constant and,
thus the denominator doesn\'t change

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image146.png)

so we can combine the two pieces

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image147.png)

an dthe twos cancel out

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image148.png)

and that means the derivative of this

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image149.png)

is this.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image150.png)

Likewise, we apply

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image151.png)

the chain rule

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image152.png)

to the remaining terms and get

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image153.png)

these !

Bam !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image154.png)

Now we can simplify the equation.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image155.png)

These zeros go away

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image156.png)

and we can pull the Sigma squared out

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image157.png)

and add the numerators together

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image158.png)

Tthen we can combine the measurements

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image159.png)

And, lastly, we can combine the mus.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image160.png)

Thus, this is the derivative of the log likelihood function with respect
to mu.

Double bam !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image161.png)

Now let\'s take the derivative of the log likelihood function with
respect to Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image162.png)

This derivative is the slope function for the log of the likelihood
curve

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image163.png)

and we\'ll use it to find the peak, which is hard to see in this graph !

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image164.png)

So, from here on out, because they peak at the same spot, I\'ll show you
the likelihood functions instead of the log likelihood functions.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image165.png)

The first term doesn\'t contain Sigma so it\'s derivative is zero.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image166.png)

The derivative of the second term is just in over Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image167.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image168.png)

The derivative of this term isn\'t tricky, but it\'s easier to figure
out when we rewrite 1 over Sigma squared as Sigma to the negative 2.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image169.png)

Since we\'re taking the derivative with respect to Sigma, this part can
be treated like a big constant

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image170.png)

and the derivative of this

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image171.png)

is this.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image172.png)

The two negatives cancel out

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image173.png)

and then the twos cancel out

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image174.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image175.png)

and lastly we put Sigma back into the denominator by changing the sign
of the exponent.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image176.png)

So the derivative of this

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image177.png)

is this !

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image178.png)

So that\'s what we put into the equation.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image179.png)

Likewise, the derivatives of the remaining terms

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image180.png)

simplify to these.

BAM !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image181.png)

This is the derivative of the log likelihood function with respect to
Sigma.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image182.png)

We can simplify the equation by omitting the zero

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image183.png)

leaving the second term the same

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image184.png)

and we can pull the Sigma cubed out

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image185.png)

and add up the remaining terms.

Double bam !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image186.png)

At long last here are the two derivatives !!!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image187.png)

To find the maximum likelihood estimate for MU we need to solve for
where the derivative with respect to MU equals zero, because the slope
is zero at the peak of the curve.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image188.png)

Likewise, to find the maximum likelihood estimate for Sigma, we need to
solve for where the derivative with respect to Sigma equals zero because
the slope is zero at the peak of the curve.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image189.png)

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image190.png)

We\'ll start by setting the derivative with respect to MU to 0

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image191.png)

and solve for MU.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image192.png)

We start by multiplying both sides by Sigma squared that makes the Sigma
squared go away

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image193.png)

then we add n times mu to both sides

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image194.png)

divide both sides by N and solve.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image195.png)

Thus, the maximum likelihood estimate for MU is the mean of the
measurements.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image196.png)

So that is where the center of our normal curve will go.

Don\'t get too excited, we\'re not done yet !

Dang !!

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image197.png)

Now we need to set the derivative with respect to Sigma to 0.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image198.png)

Now multiply both sides by Sigma

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image199.png)

add n to both sides

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image200.png)

multiply both sides by Sigma squared

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image201.png)

divide both sides by n

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image202.png)

and take the square root of both sides

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image203.png)

and at long last we see that the maximum likelihood estimate for Sigma
is the standard deviation of the measurements.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image204.png)

Thus, we use the formula for the standard deviation to determine the
width of the normal curve that, given the data, has the maximum
likelihood.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image205.png)

In summary :

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image206.png)

the mean of the data is the maximum likelihood estimate for where the
center of the normal distribution should go

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image207.png)

and the standard deviation of the data is the maximum likelihood
estimate of how wide the normal curve should be.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image208.png)

Note : these solutions may be obvious but now we have the math that
proves that our intuition is correct.

![](media/STATQUEST-39-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_NORMAL_DISTRIBUTION/image209.png)

wait for it.

Triple bam !!!
