<https://www.youtube.com/watch?v=JQc3yx0-Q9E&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=11>

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image1.png)

Today we\'re gonna talk about how to calculate p-values.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image2.png)

Note : this stat quest assumes that you are already familiar with what
p-values are and how to interpret them if not check out the quest.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image3.png)

Also note : before we get started I want to mention that there are two
types of P values

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image4.png)

one sided and two sided.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image5.png)

Two-sided p-values are the most common and this quest focuses on
calculating them.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image6.png)

In contrast one-sided p-values are rarely used and to be honest
potentially dangerous I won\'t mention them again until the very end
when I give an example of why they should be avoided.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image7.png)

With that said let\'s imagine I had a coin

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image8.png)

and I flipped it once and got heads.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image9.png)

Then I flipped it again and got heads a second time.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image10.png)

Now at this point I might be tempted to think wow !

My coin is super special because it landed on heads twice in a row !!

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image11.png)

This is a hypothesis.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image12.png)

However in statistics lingo the hypothesis is : even though I got two
heads in a row, my coin is no different from a normal coin.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image13.png)

Note : although we want to know if our coin is special

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image14.png)

the statistics lingo version says the opposite, that our coin is the
same as a normal coin.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image15.png)

Statisticians call this the null hypothesis and a small p-value will
tell us to reject it.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image16.png)

And if we reject this null hypothesis we will know that our coin is
special.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image17.png)

So let\'s test this hypothesis by calculating a p-value.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image18.png)

p-values are determined by adding up probabilities so let\'s start by
figuring out the probability of getting two heads in a row.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image19.png)

When we flip a normal everyday coin there\'s a 50% chance we\'ll get
heads

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image20.png)

and a 50% chance we\'ll get tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image21.png)

Now if we got heads on the first flip

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image22.png)

and flip the coin a second time

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image23.png)

then just like before there\'s a 50% chance we\'ll get heads and a 50%
chance we\'ll get tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image24.png)

Likewise if we got tails on the first flip

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image25.png)

and flip the coin again

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image26.png)

then just like before there\'s a 50% chance we\'ll get heads and a 50%
chance we\'ll get tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image27.png)

Ultimately these are the four possible outcomes after flipping a coin
two times.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image28.png)

Because each outcome is equally probable we can calculate the
probability of getting two heads with the following formula :

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image29.png)

the number of times we got two heads divided by the total number of
outcomes.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image30.png)

In this case we only got two heads one time so we put a 1 in the
numerator.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image31.png)

And since there were four possible outcomes we put a four in the
denominator.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image32.png)

Thus the probability of getting two heads is 0.25.

L![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image33.png)Likewise the probability of getting two
tails is

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image34.png)

0.25.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image35.png)

Finally the probability of getting one heads and one tails regardless of
the order is 0.5.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image36.png)

Now you may be wondering why we don\'t care about the order of the heads
and tails and treat these outcomes as the same.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image37.png)

In this case the order doesn\'t matter because getting a heads on the
first flip

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image38.png)

doesn\'t change the probabilities of getting heads or tails on the
second flip.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image39.png)

Likewise getting tails on the first flip

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image40.png)

doesn\'t change the probabilities of getting heads or tails on the
second flip.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image41.png)

Because order does not affect the probabilities of getting heads and
tails we treat these outcomes as the same.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image42.png)

Now let\'s move the outcomes over to the left unless the probability of
each outcome

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image43.png)

and calculate the p-value for getting two heads.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image44.png)

A p-value is composed of three parts.

The first part is the probability random chance would result in the
observation.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image45.png)

In this case the first part is just the probability that a normal coin
would give us two heads which is 0.25.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image46.png)

The second part is the probability of observing something else that is
equally rare.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image47.png)

In this case getting two tails is as rare as two heads so we add 0.25.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image48.png)

The third part is the probability of observing something rare or more
extreme.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image49.png)

In this case the third part is zero because no other outcomes are rarer
than two heads or two tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image50.png)

Now we just add everything together

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image51.png)

and the p-value for getting two heads equals 0.5.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image52.png)

Now remember the reason we calculated the p-value was to test this
hypothesis : even though I got two heads in a row my coin is no
different from a normal coin.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image53.png)

Typically we only reject a hypothesis if the p-value is less than 0.05

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image54.png)

and since 0.5 is greater than 0.05 we fail to reject the hypothesis.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image55.png)

In other words the data getting two heads in a row, failed to convince
us that our coin is special.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image56.png)

Note : the probability of getting two heads 0.25 is different from the
p-value for getting two heads 0.5.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image57.png)

This is because the p-value is the sum of three parts

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image58.png)

the first part is the probability random chance would result in the
observation

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image59.png)

the second part is the probability of observing something else that is
equally rare.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image60.png)

And the third part is the probability of observing something rare or
more extreme.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image61.png)

Now the question is why do we care about things that are equally rare or
more extreme ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image62.png)

In other words why do we add parts two and three to the p value ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image63.png)

We add part to the probability of something else that is equally rare
because although getting two heads might seem special it doesn\'t seem
as special when we know that other things are just as rare.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image64.png)

For example imagine giving a loved one a flower and saying this is the
rarest flower of this species none are equally as rare.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image65.png)

Chances are your loved one would think that the flower was super
special.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image66.png)

You might even get a kiss on the cheek.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image67.png)

Now imagine saying to your loved one this flower is equally as rare as
all of these other flowers.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image68.png)

In this case your loved one might not think the flower is very special.

Wha-wha.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image69.png)

Note : even though these flowers are different colors just knowing that
they\'re equally rare would be a bummer.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image70.png)

Because a lot of equally rare things would make something less special
we add part two to the p-value.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image71.png)

And we add rare things to the p-value for a similar reason.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image72.png)

Going back to our flower example imagine telling your loved one this is
the rarest flower of this species none are rarer.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image73.png)

Again there\'s a good chance your loved one would think that the flower
was super special.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image74.png)

Now imagine saying there are a lot of flowers that are rarer than this
one.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image75.png)

In this case your loved one might not think the flower is very special.

Wah-wah.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image76.png)

And like before even though these flowers are all different colors just
knowing they are rare would be a bummer.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image77.png)

Thus because rarer things make something less special we add part three
to the p-value.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image78.png)

Okay now that we know that getting two heads in a row is not very
special or statistically significant

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image79.png)

what about getting four heads and one tails ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image80.png)

Would that suggest that our coin is special ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image81.png)

In other words we can calculate a p-value to test this hypothesis :

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image82.png)

even though I got four heads and one tails, my coin is no different from
a normal coin.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image83.png)

Again although we want to know if the coin is special the null
hypothesis focuses on a normal coin

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image84.png)

but if we get a small p-value and reject the null hypothesis we will
know that our coin is special.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image85.png)

So let\'s calculate the p-value for getting four heads and one tail.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image86.png)

First we know that it is possible to flip a coin five times and get
heads each time

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image87.png)

so let\'s keep track of that with five blue H\'s.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image88.png)

We can also flip a coin five times and get four heads and one tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image89.png)

Note : there are five different ways to get four heads and one tails but
we treat them all the same because the order of heads and tails doesn\'t
matter.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image90.png)

Likewise there are ten ways that we can flip a coin and get three heads
and two tails

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image91.png)

and ten ways to get two heads and three tails

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image92.png)

and five ways to get one heads and four tails

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image93.png)

and lastly one way to flip a coin five times and get five tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image94.png)

All in all when we flip a coin five times there are 32 possible
outcomes.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image95.png)

The p-value for getting four heads and one tails is

1\. the probability we randomly get four heads and one tails this is
5/32.

Since five of the 32 outcomes had four heads and one tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image96.png)

2\. the probability we randomly get something else that is equally
rare : this is 5 divided by 32 since 5 of the 32 outcomes had one head
and four tails

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image97.png)

3\. the probability we randomly get something rarer or more extreme this
is 2 divided by 32

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image98.png)

Because both 5 heads and 5 tails only occurred once each they are rarer
than four heads and one tails.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image99.png)

Thus the p-value for getting four heads and one tails is 0.375.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image100.png)

Again we typically only reject the null hypothesis if the p-value is
less than 0.05

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image101.png)

so in this case we will fail to reject the null hypothesis.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image102.png)

In other words the data getting four heads and one tails did not
convince us that our coin was special.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image103.png)

With coin tosses it\'s pretty easy to calculate probabilities and
p-values because it\'s pretty easy to list all of the possible outcomes.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image104.png)

But what if we wanted to calculate probabilities and p-values for how
tall or short people are ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image105.png)

In theory we could try to list every single possible value for height.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image106.png)

However in practice when we calculate probabilities and p-values for
something continuous like height we usually use something called a
statistical distribution.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image107.png)

Here we have a distribution of height measurements from Brazilian women
between 15 and 49 years old taken in 1996.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image108.png)

The red area under the curve indicates the probability that a person\'s
height will be within a range of possible values.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image109.png)

For example 95 percent of the area under the curve is between 142 and
169

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image110.png)

and that means that 95 percent of the Brazilian women were between 142
and 169 centimeters tall.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image111.png)

In other words there is a 95 percent probability that each time we
measure a Brazilian woman their height will be between 142 and 169
centimeters.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image112.png)

2.5 percent of the total area under the curve is greater than 169.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image113.png)

And that means there is a 2.5 percent probability that each time we
measure a Brazilian woman their height will be greater than 169
centimeters.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image114.png)

Likewise 2.5 percent of the total area under the curve is less than 142.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image115.png)

Thus there is a 2.5 percent probability that each time we measure a
Brazilian woman their height will be less than 142 centimeters.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image116.png)

To calculate p-values with a distribution you add up the percentages of
area under the curve.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image117.png)

For example imagine we measured someone who is 142 centimeters tall.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image118.png)

If we measured someone who is 142 centimeters tall we might wonder if it
came from this distribution of heights which has an average value of
155.7

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image119.png)

or if it came from another distribution of heights for example this
green distribution has an average value of 142.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image120.png)

So the question is is this measurement 142 centimeters so far away from
the mean of the blue distribution that we can reject the idea that it
came from it ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image121.png)

If so then that would suggest that another distribution like this green
one might do a better job explaining the data.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image122.png)

The p-value for the hypothesis this measurement comes from the blue
distribution

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image123.png)

starts with the 2.5 percent of the area for people less than or equal to
142 centimeters.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image124.png)

Note : when we are working with a distribution we are interested in
adding more extreme values to the p value rather than rarer values.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image125.png)

In this case all heights further than 142 centimeters from the mean are
considered more extreme than what we observed.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image126.png)

We also add the 2.5% of the area for people 169 centimeters or taller.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image127.png)

Note : just like on the other side of the distribution these values are
considered equal to or more extreme because there is far from the mean
or further.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image128.png)

Now we just do the math and get 0.05.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image129.png)

So the p-value for the hypothesis someone 142 centimeters tall could
come from the blue distribution is 0.05.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image130.png)

And since the cutoff for significance is usually 0.05 we would say

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image131.png)

Hmm.

Maybe it could come from this distribution maybe not.

It\'s hard to tell since the p-value is right on the borderline.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image132.png)

So maybe they come from this distribution

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image133.png)

or maybe they come from this distribution.

The data are inconclusive.

Wah wah.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image134.png)

Note : if we had measured someone who is 141 centimeters tall so just a
little bit shorter than 142 centimeters

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image135.png)

then the p value would be 0.01 6

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image136.png)

plus 0.01 6

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image137.png)

which equals zero point zero three

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image138.png)

and since 0.03 is less than 0.05 the standard threshold we can reject
the hypothesis that given the blue distribution it is normal to measure
someone 141 centimeters tall.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image139.png)

Thus we will conclude that it\'s pretty special to measure someone that
short.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image140.png)

And that suggests that a different distribution of Heights makes more
sense.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image141.png)

Now what if we measured someone who is between 155 point four in 156
centimeters tall ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image142.png)

Note : the peak of the curve is right at the average height so we were
asking

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image143.png)

is a measurement between 155 point four and 156 so far away from the
mean of the blue distribution that we can reject the idea that it came
from it ?

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image144.png)

If the p-value is small then that suggests that some other distribution
would do a better job explaining the data.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image145.png)

Note : the probability of someone being between 155 point four and 156
centimeters is only 0.04 the red area is pretty small barely a line !

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image146.png)

So 0.04 is the first part of calculating the p-value since given this
distribution of heights that is the probability that we would randomly
measure someone in this range of values.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image147.png)

Now we need to figure out the more extreme parts.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image148.png)

On the left side all of the heights less than 150 5.4 are further from
the mean thus they are more extreme.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image149.png)

And because 48% of the area under the curve is for Heights less than 150
5.4 we add 0.48 to the p-value.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image150.png)

On the right side all of the heights greater than 156 are further from
the mean thus they are all more extreme.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image151.png)

And because 48% of the area under the curve is for Heights greater than
156 we add 0.48 to the p-value.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image152.png)

Ultimately we end up adding all of the area under the curve so the
p-value equals one.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image153.png)

So this means that given this distribution of heights we would not find
it unusual to measure someone whose height was close to the average even
though the probability is small (0.04).

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image154.png)

In other words, the data does not suggest that another distribution
would do a better job explaining the data.

BAM.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image155.png)

So far we\'ve only talked about two-sided p-values.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image156.png)

Now I\'ll give you an example of a one-sided p-value and tell you why it
has the potential to be dangerous.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image157.png)

Imagine we measured how long it took a bunch of people to recover from
an illness.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image158.png)

Now imagine we created a new drug super drug and wanted to see if it
helped people recover in fewer days.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image159.png)

If we gave super drug to a bunch of people and the average recovery was
4.5 days

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image160.png)

then a two-sided p-value like the ones we\'ve been computing all along
would be

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image161.png)

the sum of this area under the curve 0.016

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image162.png)

plus this area under the curve 0.016

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image163.png)

and the total is 0.03.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image164.png)

And since 0.03 is less than 0.05 the two-sided p-value tells us that
given this distribution of recovery times super drug did something
unusual.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image165.png)

and that suggests that some other distribution does a better job
explaining the data.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image166.png)

For a one-sided p-value the first thing we do is decide which direction
we want to see change in.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image167.png)

In this case we\'d like super drug to shorten the time it takes to
recover from the illness

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image168.png)

so that means we want to see if recovery times are shorter.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image169.png)

Because we want to see change in this direction the only more extreme
values are less than 4.5 days.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image170.png)

All of the values greater than 4.5 days are considered less extreme.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image171.png)

So when we calculate a one-sided p-value we only use the area that is in
the direction we want to see change 0.016.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image172.png)

Again since 0.01 6 is less than 0.05 the one-sided p-value would tell us
that given this distribution super drug did something unusual

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image173.png)

and that some other distribution makes more sense.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image174.png)

Now imagine that super drug wasn\'t so super and on average it took
fifteen point five days to recover.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image175.png)

Just like before the two-sided p-value would be

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image176.png)

the sum of this area under the curve zero point zero one six

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image177.png)

plus this area under the curve zero point zero one six

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image178.png)

and the total is zero point zero three.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image179.png)

In other words regardless of whether super drug is super and makes
things better or if it is not so super and makes things worse a
two-sided p-value will detect something unusual happened.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image180.png)

For a one-sided p-value the first thing we do is decide which direction
we want to see change in.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image181.png)

And just like before that means we want to see if recovery times are
shorter.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image182.png)

So the one-sided p-value is this huge area 0.98 because it is more
extreme in the direction we want to see change.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image183.png)

And since 0.98 is greater than 0.05 the one-sided p-value would not
detect that Superdrug was doing anything unusual.

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image184.png)

In other words the one-sided p-value is only looking to see if a
distribution to the left of the original mean makes more sense

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image185.png)

and since the observation is on the right side of the mean we fail to
reject the hypothesis that the original distribution makes sense

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image186.png)

and since failing to detect that Superdrug is making things worse would
be bad one-sided p-values are tricky and should be avoided or only used
by experts who really know what they\'re doing.

BAM !!

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image187.png)

In summary a p-value is composed of three parts :

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image188.png)

the first part is the probability random chance would result in the
observation

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image189.png)

the second part is the probability of observing something else that is
equally rare

![](media/STATQUEST-11-STATISTICS_FUNDAMENTALS-CALCULATE_P_VALUE/image190.png)

and the third part is the probability of observing something rarer or
more extreme.

BAM !!!
