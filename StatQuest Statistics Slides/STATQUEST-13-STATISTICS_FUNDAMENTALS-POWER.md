<https://www.youtube.com/watch?v=Rsc5znwR5FA&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=13>

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image1.png)

Today we\'re gonna talk about statistical power and it\'s gonna be
clearly explained.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image2.png)

Note this stat quest assumes that you are already familiar with p-values
if not check out the quests.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image3.png)

This stat quest also assumes that you are already familiar with the
normal distribution.

If not check out the quest.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image4.png)

Let\'s start with two distributions.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image5.png)

The one on the Left represents the weights of mice on a special diet

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image6.png)

and the one on the right represents the weights of mice eating normal
Mouse food.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image7.png)

Since there\'s only a little bit of overlap

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image8.png)

it\'s pretty easy to see the difference between these two diets.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image9.png)

Most of the mice on the special diet weigh less than the mice on the
normal diet.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image10.png)

And if we collect a small set of measurements from the special diet

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image11.png)

and another small set of measurements from the normal diet

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image12.png)

and plot these points on a graph and compare their means

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image13.png)

then in this case we\'ll get a p-value equal to zero point zero zero
zero four.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image14.png)

And this small p-value less than 0.05 would cause us to correctly reject
the null hypothesis that both sets of data came from the same
distribution.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image15.png)

In other words if this distribution which is somewhere between the
special and normal diets said all data a tums from me then.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image16.png)

Then the small p-value would say in a loud and confident voice

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image17.png)

I reject your hypothesis !!!

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image18.png)

If we repeated this experiment a bunch of times there\'s a high
probability that each statistical test will correctly give us a small
p-value.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image19.png)

In other words there is a high probability that the null hypothesis that
all of the data came from the same distribution

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image20.png)

will be correctly rejected.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image21.png)

But every once in a while we will get something like this where the data
overlap

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image22.png)

and when this happens we will get a large p-value greater than 0.05

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image23.png)

and that means that even though we know the data came from two different
distributions

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image24.png)

we cannot correctly reject the null hypothesis that all of the data
comes from the same distribution.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image25.png)

So the large p-value says in a very small and meek voice.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image26.png)

Dang I can\'t reject the null hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image27.png)

That said because these distributions are so far apart

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image28.png)

and there is so little overlap

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image29.png)

the probability of correctly rejecting the null hypothesis is high.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image30.png)

Power is the probability that we will correctly reject the null
hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image31.png)

Alternatively you could say that power is the probability that we will
correctly get a small p-value (\<0.05).

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image32.png)

In this example because we have a high probability of correctly getting
a small p-value and rejecting the null hypothesis

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image33.png)

we have a large amount of power.

BAM !!!

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image34.png)

Note : if there was no difference between the special diet and the
normal diet and they both shared the same distribution

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image35.png)

and we collected one set of measurements for mice on the special diet

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image36.png)

and one set of measurements for mice on the normal diet then the null
hypothesis that both datasets came from the same distribution would be
true in this case there is no such thing as correctly rejecting the null
hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image37.png)

So the concept of power the probability that we will correctly reject
the null hypothesis doesn\'t apply in this situation.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image38.png)

In contrast if this special diet wasn\'t very good at helping mice lose
weight but it still made a difference

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image39.png)

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image40.png)

then even though there is a lot of overlap

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image41.png)

we have two distinct distributions

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image42.png)

and that means power the probability that we correctly reject the null
hypothesis, applies.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image43.png)

If we were to weigh three mice on the special diet

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image44.png)

and three mice on the normal diet

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image45.png)

and plot these points on a graph and compare their averages

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image46.png)

then in this case we will get a p-value equal to 0.34

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image47.png)

that means we will fail to reject the null hypothesis that both groups
come from the same distribution.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image48.png)

This is a bummer because in this case we know the data comes from two
different distributions.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image49.png)

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image50.png)

And when we repeat this many times most of the time we will get a large
p-value and fail to reject the null hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image51.png)

However every once in a while we will get something like this where the
data do not overlap

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image52.png)

and we will correctly get a small p-value (\<0.05)

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image53.png)

when this happens even though the null hypothesis says all day today
comes from me.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image54.png)

The small p-value will say in a loud and confident voice

I reject the null hypothesis !!!

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image55.png)

So out of all these tests this was the only one that gave us a p-value
small enough that we correctly rejected the null hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image56.png)

And that means when there is a lot of overlap between the two
distributions and we have a small sample size we have a relatively low
power.

Medium BAM.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image57.png)

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image58.png)

The good news is that we can always increase power by increasing the
number of measurements we collect

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image59.png)

and a power analysis will tell us how many measurements we need to
collect to have a good amount of power.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image60.png)

Shameless self-promotion.

We\'ll talk more about how and why we can increase power in the stat
quest on power analyses.

BAM !!!

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image61.png)

In summary

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image62.png)

power is the probability that we will correctly reject the null
hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image63.png)

When we have two distributions that have very little overlap

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image64.png)

we will have a lot of power because there is a high probability that we
will correctly reject the null hypothesis.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image65.png)

However when the two distributions overlap a lot

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image66.png)

and if we have a small sample size we will have a small amount of power.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image67.png)

However if we want more power we can increase the sample size.

![](media/STATQUEST-13-STATISTICS_FUNDAMENTALS-POWER/image68.png)

Lastly a power analysis will tell us how many measurements to collect to
have a good amount of power.

Double BAM !!!
