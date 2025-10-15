<https://www.youtube.com/watch?v=HDCOUXE3HMM&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=12>

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image1.png)

Today we\'re gonna talk about P hacking what it is and how to avoid it.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image2.png)

Note : this stack quest assumes that you are already familiar with
p-values if not check out the quests.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image3.png)

Imagine there was a virus and we wanted to develop a drug to reduce the
time it took to recover from it.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image4.png)

So he created a bunch of candidate drugs

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image5.png)

and we tested each one to find out if any of them worked.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image6.png)

So we measured how long it took for three people to recover from the
virus without any drugs

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image7.png)

and then we gave three people drug a and measured how long it took them
to recover.

Just by looking at the graph it appears that drug a did not shorten
recovery very much if at all.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image8.png)

So we measure how long it takes three more people to recover without any
medicine

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image9.png)

and then we give three people drug B and measure how long it takes them
to recover.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image10.png)

Again just by looking at the graph it doesn\'t look like drug B helped
people recover any faster than people without any medicine.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image11.png)

So we just keep testing drugs until we get one that really looks like it
does a good job.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image12.png)

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image13.png)

And at long last it looks like drugs Z does a great job reducing the
amount of time it takes to recover from the virus.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image14.png)

So we calculate the means of the two groups

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image15.png)

and do a statistical test to compare the means and we get a p-value
equal to 0.02.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image16.png)

And since 0.02 is less than 0.05 we reject the null hypothesis which is
that there is no difference between not taking a drug and taking drugs
Z.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image17.png)

BAM ?

No. No BAM.

We just pee hacked !!!!

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image18.png)

p-hacking refers to the misuse and abuse of analysis techniques and
results in being fooled by false positives.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image19.png)

However instead of feeling great shame let\'s learn about pee hacking so
we don\'t do it again.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image20.png)

Imagine we measured recovery times for a whole lot of people who did not
take any drugs to fight the virus.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image21.png)

And then we fit a normal distribution to all of the recovery times.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image22.png)

The red area under the curve indicates the percentage of people that
recovered from the illness within a range of possible values.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image23.png)

For example 2.5 percent of the area under the curve is for durations
less than 5 days indicating a 2.5 percent of the people recovered in
less than 5 days.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image24.png)

In contrast 95 percent of the area under the curve is between 5 and 15
days indicating that 95 percent of the people were covered between 5 to
15 days.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image25.png)

Now if we only asked three people represented by light blue circles how
long it took them to recover from the illness there\'s a good chance all
three would say something between five and fifteen days.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image26.png)

And if we asked a different set of three people represented by dark blue
circles there\'s a good chance all three would also say something
between five and 15 days.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image27.png)

Just like before we can plot these two groups of people on a graph

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image28.png)

and we can calculate the mean values for the two groups

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image29.png)

and compare those two means and get a p-value equal to zero point eight
six.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image30.png)

And because zero point eight six is greater than 0.05 we would fail to
see a significant difference between the two groups of observations.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image31.png)

In other words the p-value did not convince us that the observations
came from two different distributions

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image32.png)

and that makes sense because both groups of people came from the exact
same distribution.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image33.png)

Now imagine we asked another group of three people how long it took them
to recover

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image34.png)

And we plotted their recovery times and mean value on a graph.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image35.png)

Then we asked another group of three people how long it took them to
recover

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image36.png)

and we plotted their recovery times and mean value on the graph.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image37.png)

Again we do a test to compare the two means and we get a p-value equal
to zero point six three.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image38.png)

And since 0.63 is greater than 0.05 we would fail to see a significant
difference between the two groups of observations.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image39.png)

And again this is good because both sets of observations came from the
exact same distribution.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image40.png)

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image41.png)

Now imagine we just keep taking two groups of three from the same
distribution and testing to see if they are different

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image42.png)

note these two groups almost look like they could be different but the p
value equals 0.06 which is greater than the standard threshold for
significance 0.05.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image43.png)

So we just keep going

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image44.png)

and sooner or later we will get something like this.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image45.png)

When we compare the two means the p-value equals zero point zero two.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image46.png)

And that tells us that there is a statistically significant difference
between the two groups

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image47.png)

suggesting that the data came from two different distributions which is
incorrect.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image48.png)

Since we know that both samples came from the same distribution the
small p-value is a false positive.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image49.png)

Note : you may remember from the stat quest on interpreting p-values
that setting the threshold for significance to 0.05

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image50.png)

means that approximately 5% of the statistical tests we do on data
gathered from the same distribution will result in false positives.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image51.png)

That means if we did 100 tests we would expect about 5 false positives
or 5 percent.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image52.png)

And if we did 10,000 tests we would expect about 500 false positives.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image53.png)

In other words the more tests we do the more false positives we have to
deal with.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image54.png)

Oh no it\'s the dreaded terminology alert doing a lot of tests and
ending up with false positives is called the multiple testing problem.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image55.png)

The good news is that there are many ways to compensate for the multiple
testing problem and reduce the number of false positives.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image56.png)

One popular method is called the false discovery rate.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image57.png)

Shameless self-promotion.

I have a whole stack quest on the false discovery rate the link is in
the description below.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image58.png)

The main idea is that you input the p-values for every single comparison

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image59.png)

d ppppp boop boop

and then the false discovery rate does some surprisingly simple
mathematics

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image60.png)

and outcome adjusted p-values that are usually larger than the original
p-values.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image61.png)

And ultimately some of the tests that were false positives before end up
with adjusted p-values greater than 0.05.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image62.png)

Like I said I have a whole stack quest on this method if you want to
know more details.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image63.png)

The important thing to know now however is that in order for false
discovery rates or any other method that compensates for multiple
testing to work properly

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image64.png)

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image65.png)

you have to include all of the p-values for all of the tests not just
the one that looks like it will give you a small p-value.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image66.png)

In other words don\'t cherry-pick your data and only do tests that look
good.

BAM !!!

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image67.png)

Now let\'s talk about a slightly less obvious form of p-hacking.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image68.png)

Remember these two groups ?

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image69.png)

The p-value was 0.06.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image70.png)

Now we know that both groups came from the same distribution

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image71.png)

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image72.png)

but typically when we are doing experiments we don\'t know if they both
came from the same distribution or different ones.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image73.png)

And let\'s be honest we usually hope that the observations come from two
different distributions.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image74.png)

In this example we are looking for a new drug to help people so we want
to see an improvement.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image75.png)

So when we get data like this where the p-value is close to 0.05 but not
less than it is very tempting to think hmm I wonder if the p-value will
get smaller if I add more data

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image76.png)

So we add one more measurement to each group

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image77.png)

and now when we calculate the p-value we get zero point zero two which
is less than 0.05 so we can report a statistically significant
difference.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image78.png)

Hooray.

We got what we wanted right ?

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image79.png)

No we P hacked again !

Wah wah.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image80.png)

When a p-value is close to 0.05 like what we had with the original data

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image81.png)

there\'s a surprisingly high probability that just adding one new
measurement to both groups

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image82.png)

will result in a false positive.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image83.png)

In other words even though using a threshold of 0.05 should only result
in 5% of the bogus test giving us false positives

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image84.png)

the theory assumes that we only calculate a single p-value to make a
decision.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image85.png)

In this case we calculated two p-values to make our decision.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image86.png)

The one at the start which was 0.06

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image87.png)

then because the first p-value is close to 0.05

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image88.png)

we added more data and calculated a second p-value.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image89.png)

In this case we know all of the measurements came from the exact same
distribution so we know this is a false positive.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image90.png)

So how do we keep from making this mistake ?

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image91.png)

In order to avoid making this mistake we need to determine the proper
sample size before doing the experiment

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image92.png)

and that means we need to do a power analysis.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image93.png)

A power analysis is performed before doing an experiment and tells us
how many replicates we need in order to have a relatively high
probability of correctly rejecting the null hypothesis.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image94.png)

Cool !!!

Where can I learn more about doing a power analysis ??

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image95.png)

In the next stack quests we\'ll talk about power and power analyses to
determine the appropriate sample size.

BAM !!!

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image96.png)

In summary

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image97.png)

if you have a bunch of things you want to test out like a bunch of
different drugs that might help people recover from a virus

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image98.png)

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image99.png)

don\'t just collect all the data but only calculate a p-value for the
one time things look different.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image100.png)

Instead calculate a p-value for each test and adjust all of the p-values
with something like the false discovery rate.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image101.png)

This will help reduce the probability of reporting a false positive.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image102.png)

And when you do a test and get a p-value close to 0.05 but not quite
less than 0.05

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image103.png)

don\'t just add more observations to the data you already have.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image104.png)

Instead use the data you have for a power analysis to determine the
correct sample size.

![](media/STATQUEST-12-STATISTICS_FUNDAMENTALS-P-HACKING/image105.png)

This will help prevent you from being fooled by a false positive.

Double BAM !!!
