<https://www.youtube.com/watch?v=VX_M3tIyiYk&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=14>

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image1.png)

Today we\'re going to talk about power analysis and it\'s going to be
clearly explained.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image2.png)

Note : this stat quest assumes that you are already familiar with what
power means.

If not check out the quest.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image3.png)

It would also be helpful if you understood the difference between
population parameters and estimated population parameters.

If not check out the quest.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image4.png)

Lastly because we do a power analysis to avoid p hacking, you should be
familiar with that topic as well.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image5.png)

Imagine there was a virus

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image6.png)

and we had two drugs that we could use to treat it.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image7.png)

So we see how long it takes for three people using drug a to recover
from the virus

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image8.png)

and we see how long it takes three people using drug b to recover.

Just looking at the data makes us think that drug a might be better
since those people tended to recover from the virus more quickly.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image9.png)

So we calculate the means for both drugs

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image10.png)

and do a statistical test to compare the means and get a p-value equal
to 0.06.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image11.png)

Because the p-value is greater than 0.05 the threshold that we are using
to define a statistically significant difference

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image12.png)

we can\'t say that drug a is better than drug b.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image13.png)

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image14.png)

In other words even though we suspect that the measurements for drug a
represent this distribution

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image15.png)

and the measurements for drug b represent this other separate
distribution

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image16.png)

because the p-value 0.06 is greater than 0.05 we cannot reject the idea
that maybe all of the measurements represent the same distribution in
the middle.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image17.png)

Because we suspect that the measurements represent two different
distributions and the p-value 0.06 is just a little bit bigger than
0.05.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image18.png)

it is tempting to give one more person drug A and give another person
drug b

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image19.png)

and recalculate the means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image20.png)

and then redo the statistical test.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image21.png)

However we must resist this temptation because that would be p hacking
and we don\'t want to do that.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image22.png)

Instead of p hacking we\'re going to do the right thing.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image23.png)

We\'re going to do a power analysis to determine the sample size for the
next time we do this experiment.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image24.png)

A power analysis determines what sample size will ensure a high
probability that we will correctly reject the null hypothesis that there
is no difference between the two groups.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image25.png)

In other words if we use the sample size recommended by the power
analysis we will know that regardless of the p-value we used enough data
to make a good decision.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image26.png)

Power is affected by several things however there are two main factors :

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image27.png)

one how much overlap there is between the two distributions we want to
identify with our study

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image28.png)

two the sample size the number of measurements we collect from each
group.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image29.png)

For example if i want to have power equal to 0.8 meaning i want to have
at least an 80 chance of correctly rejecting the null hypothesis

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image30.png)

then if there is very little overlap a small sample size will give me
power equal to 0.8.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image31.png)

However the more overlap there is between the two distributions

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image32.png)

the larger the sample size needs to be in order to have power equal to
0.8.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image33.png)

To understand the relationship between overlap and sample size

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image34.png)

the first thing we need to realize is that when we do a statistical test
we usually don\'t compare the individual measurements.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image35.png)

Instead we compare summaries of the data for example we often compare
the means.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image36.png)

So let\'s see what happens when we calculate means with different sample
sizes.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image37.png)

First let\'s focus on the distribution for drug A.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image38.png)

The population mean for drug A is represented by this green arrow.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image39.png)

Typically when we do an experiment we don\'t know the population mean
and instead have to estimate it.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image40.png)

So if we collected one measurement and use that one measurement

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image41.png)

to estimate the population mean for drug A

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image42.png)

then the estimated mean represented by this green bar would be the same
as the measurement we collected.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image43.png)

Now let\'s get rid of the measurement but keep the estimated mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image44.png)

and collect a new measurement

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image45.png)

and use it to estimate the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image46.png)

Now let\'s collect more measurements and use each one to estimate the
population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image47.png)

Note : we occasionally get a wonky point that is really far from the
population mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image48.png)

and when that happens the estimated mean is also pretty wonky and really
far from the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image49.png)

Now compared to the population mean for the distribution

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image50.png)

we see that the estimated means are all over the place.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image51.png)

In other words there\'s a lot of variation in the estimated means.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image52.png)

And all this variation makes it hard to be confident that any single
estimated mean is a good estimate of the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image53.png)

Sure some of the estimated means are close to the population mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image54.png)

but others are pretty far away.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image55.png)

And since 25 of the area under the curve is relatively far from the mean
and off to the left

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image56.png)

25 of the measurements should be far from the mean and off to the left

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image57.png)

and since in this case a single measurement is the same as the estimated
mean 25 percent of the estimated means should be pretty far off to the
left.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image58.png)

Likewise another 25 percent of the estimated means should be pretty far
off to the right.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image59.png)

In summary when we only use one measurement to estimate the population
mean the probability that we\'ll get something far from it is too high
for us to be confident that we have a good estimate.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image60.png)

Now let\'s do the same thing for drug B

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image61.png)

collect one measurement and use that to estimate the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image62.png)

Now let\'s do that a bunch of times

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image63.png)

just like before compared to the population mean for the distribution

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image64.png)

the estimated means are all over the place.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image65.png)

And just like before fifty percent of the estimated mean should be
pretty far to the left or right of the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image66.png)

And when we only use one measurement to estimate the population mean the
probability that we\'ll get something far from it is too high for us to
be confident in our estimate.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image67.png)

And because we don\'t have a lot of confidence in the estimated means
we\'ll end up with a relatively large p-value.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image68.png)

And that means we will not correctly reject the null hypothesis.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image69.png)

In other words if this distribution said all data comes from me

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image70.png)

then due to all of the variation in the estimated means we\'d say in a
small meek voice

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image71.png)

dang i can\'t reject the null hypothesis.

Bam !

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image72.png)

Now let\'s collect two measurements at one time

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image73.png)

and use the average to estimate the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image74.png)

Now let\'s repeat that process a bunch of times collect two measurements
and use the average to estimate the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image75.png)

Note : just like before we occasionally get a wonky point that is really
far from the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image76.png)

However the other point we measured compensates for the wonky point and
prevents the estimated mean from being too far from the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image77.png)

In other words even though there is a 25 probability that we will get a
measurement way out on the left side

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image78.png)

there is a 75 probability that the next measurement will be in this
range and pull the estimated mean back to the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image79.png)

In summary when we use more than one measurement to estimate the
population mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image80.png)

extreme measurements have less effect on how far the estimated mean is
from the population mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image81.png)

and as a result the estimated means are closer to the population mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image82.png)

compared to the means we estimated with a single observation.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image83.png)

This suggests that we should have more confidence that averages
estimated with two observations will be closer to the population mean
than averages estimated with one observation.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image84.png)

Now let\'s collect two measurements each time for drug b and use their
average to estimate the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image85.png)

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image86.png)

Again when we use two measurements we can have more confidence that the
estimated means are closer to the population mean

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image87.png)

compared to the means we estimated with a single observation.

Bam !!!

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image88.png)

Now imagine we did the same thing only this time we collected 10
measurements

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image89.png)

and used them to estimate the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image90.png)

Then we repeated that process collected 10 measurements and then
estimated the population mean a bunch of times

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image91.png)

then we did the same thing for drug b.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image92.png)

Now we see that the more measurements we use for each estimate the
closer they are to the population main

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image93.png)

and the more confidence we can have that an individual estimated mean
will be close to the population mean.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image94.png)

In this example the estimated means are so close to the population means
that they no longer overlap.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image95.png)

And that suggests there is a high probability that we will correctly
reject the null hypothesis that both samples were taken from the same
distribution.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image96.png)

In other words even when the distributions overlap if the sample size is
large we can have high power.

Bam !!

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image97.png)

Note : although we used normal distributions in this example

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image98.png)

the central limit theorem tells us that these results apply to any
underlying distribution.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image99.png)

Shameless self-promotion.

For more details about the central limit theorem check out the quest.

The link is in the description below.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image100.png)

Now at long last let\'s talk about how to actually do a power analysis.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image101.png)

First remember that a power analysis will tell us what sample size we
need to have power.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image102.png)

So the first thing we need to decide is how much power we want.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image103.png)

Although we can pick any value between 0 and 1 for power a common value
is 0.8 so let\'s use that.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image104.png)

That means we want an 80 probability that we will correctly reject the
null hypothesis.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image105.png)

The second thing we need to do is determine the threshold for
significance often called alpha.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image106.png)

We can use any value between 0 and 1 but a very common threshold is 0.05
so we\'ll use that.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image107.png)

Lastly we need to estimate the overlap between the two distributions.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image108.png)

Overlap is affected by both the distance between the population means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image109.png)

and the standard deviations.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image110.png)

A common way to combine the distance between the means and the standard
deviations into a single metric

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image111.png)

is to calculate an effect size which is also called d.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image112.png)

In the numerator we have the estimated difference in the means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image113.png)

and in the denominator we have the pooled estimated standard deviations.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image114.png)

One of the simplest ways to pool the estimated standard deviations

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image115.png)

is the square root of the sum of the squared standard deviations divided
by 2

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image116.png)

where the green s represents the estimated standard deviation for the
green distribution

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image117.png)

and the purple s represents the estimated standard deviation for the
purple distribution.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image118.png)

Note : there are tons of other ways to calculate effect sizes and this
is just one of them

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image119.png)

so when you do a power analysis you may have to do a little research
about how to estimate the overlap.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image120.png)

However in general the mean and standard deviations can be estimated
with prior data a literature search or in a worst case scenario an
educated guess.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image121.png)

In this case the original data suggests that the difference between the
two means is ten

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image122.png)

and the estimated standard deviations are seven and six

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image123.png)

so we plug those into the formula for the pooled standard deviation

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image124.png)

and we get six point five

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image125.png)

so the effect size is 1.5.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image126.png)

Once we know the effect size and the amount of power we want and the
threshold for significance

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image127.png)

we google statistics power calculator pretty much every statistics
department in the world has one online.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image128.png)

Then we plug in the numbers.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image129.png)

I got sample size equals nine this means that if i get nine measurements
per group i will have an eighty percent chance that i will correctly
reject the null hypothesis.

Double bam !!!

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image130.png)

In summary

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image131.png)

when two distributions overlap we need a relatively large sample size to
have a lot of power.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image132.png)

When the sample size is small

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image133.png)

we have low confidence that the estimated means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image134.png)

are close to the population means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image135.png)

and that lack of confidence is reflected in a low probability that we
will correctly reject the null hypothesis.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image136.png)

In contrast when we increase the sample size

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image137.png)

we have more confidence that the estimated means are close to the
population means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image138.png)

because extreme observations have less effect on the location of the
estimated means

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image139.png)

and the closer the estimated means are to the population means the less
the means from the different distributions will overlap

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image140.png)

and that increases the probability that we will correctly reject the
null hypothesis.

![](media/STATQUEST-14-STATISTICS_FUNDAMENTALS-POWER_ANALYSIS/image141.png)

And when you have a high probability that we will correctly reject the
null hypothesis you have high power.

Triple bam !!!
