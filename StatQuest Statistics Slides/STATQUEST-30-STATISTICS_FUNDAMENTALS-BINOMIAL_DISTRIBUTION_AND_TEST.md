<https://www.youtube.com/watch?v=J8jNoF-K8E8&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=31>

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image1.png)

Today we\'re going to talk about the binomial distribution and the
binomial test and they\'re going to be clearly explained.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image2.png)

Usually when people talk about the binomial distribution they talk about
flipping a coin.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image3.png)

A coin usually has heads

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image4.png)

and at least one tail.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image5.png)

For example you can use the binomial distribution to find out the
probability of getting six heads in six tosses.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image6.png)

But who really cares about flipping coins ?

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image7.png)

What folks really want to know is whether or not people like orange
Fanta more than grape Fanta.

Which flavor reigned supreme or are they both equally loved ?

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image8.png)

To answer this question we can ask a bunch of people which flavor they
prefer.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image9.png)

If everybody but one person said they liked orange Fanta more than grape
Fanta then it would be pretty obvious what people liked most

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image10.png)

but what if four people say they like orange Fanta and three people say
they\'d like grape Fanta ?

Is that enough to be confident than most people like orange Fanta ?

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image11.png)

Or could it be that people in general don\'t have a preference and these
results are just due to random chance and a small sample size.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image12.png)

Maybe if we surveyed another seven people we might only get three people
who like orange Fanta and for people who like grape Fanta ?

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image13.png)

To get to the bottom of this mystery we need to get a sense of what to
expect if there is no preference.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image14.png)

Then we determine if our survey results fit those expectations if not we
can reject the idea that both Fantas are loved equally.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image15.png)

The binomial distribution will tell us what to expect if there is no
preference.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image16.png)

To say the same thing using statistics lingo.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image17.png)

We will use the binomial distribution

aka this nasty looking thing

to model what to expect when there is no preference

then we\'ll see how well this model fits the data if the model is a poor
fit we will reject the idea that both flavors are loved equally.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image18.png)

So let\'s start with a super simple example and assume that I asked
three people if they liked orange Fanta more than grape Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image19.png)

The first person we asked said they preferred orange Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image20.png)

The second person we asked also said they preferred orange Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image21.png)

And the third person we asked said they preferred grape Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image22.png)

If people really didn\'t prefer one flavor over the other then we will
assume that there is a 50% chance they will pick orange and a 50% chance
they will pick grape.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image23.png)

We can then calculate the probability of the first two people randomly
choosing orange in the third person randomly choosing grape.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image24.png)

Assuming that there is no real preference the probability of the first
person preferring orange Fanta is 0.5.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image25.png)

And the probability of the first two people preferring orange Fanta is
0.5 times 0.5 which equals 0.25.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image26.png)

And the probability of the first two people preferring orange Fanta and
the third person performing grape is 0.5 times 0.5 times 0.5 which
equals 0.125.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image27.png)

Note 0.125 is the probability of the first two people saying they prefer
orange and the third person saying they prefer grape.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image28.png)

It is not the probability that any two out of three people would prefer
orange.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image29.png)

Let me explain.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image30.png)

It could have just as easily been that the first person said they
preferred grape.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image31.png)

In this case the probability would still be 0.125 but we\'d multiply the
numbers together in a different order.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image32.png)

Likewise if the second person said they preferred grape we just multiply
the numbers together in a different order.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image33.png)

So all three of these combinations are equally likely.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image34.png)

And this means that the probability that any two out of three people
prefer orange Fanta is the sum of the three possible orders.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image35.png)

So we just add the three probabilities together

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image36.png)

and the probability that any two out of three people would randomly say
they prefer orange Fanta is 0.375.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image37.png)

Alternatively we could have done the math using this nasty-looking
formula.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image38.png)

X is the number of people who preferred orange Fanta in this case X
equals 2

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image39.png)

n is the total number of people we asked in this case n equals 3.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image40.png)

Note : n minus X the total number of people we asked minus the number of
people who preferred orange Fanta equals the number of people who said
they prefer grape Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image41.png)

P is the probability that someone will pick orange Fanta in this case P
equals 0.5.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image42.png)

Note : the probability that someone might prefer grape Fanta is 1 minus
P.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image43.png)

Together this says the probability of X the number of people who say to
prefer orange Fanta given in the number of people we asked and P the
probability of picking orange Fanta

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image44.png)

equals this nasty looking thing.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image45.png)

Ooh it\'s got factorials don\'t freak out it looks fancy but it just
boils down to the number of different ways two of three people could say
they prefer orange Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image46.png)

When we did everything by hand we saw that there were three ways for two
of three people to say they prefer orange Fanta

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image47.png)

and if we plug in N equals 3 and x equals 2

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image48.png)

and then just do the math

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image49.png)

we get

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image50.png)

three three ways that two out of three people could prefer orange Fanta
just like when we did it by hand.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image51.png)

So this fancy thing is really no big deal !!!

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image52.png)

The next part of the formula P to the X corresponds to the probability
that orange Fanta was chosen two of the three times.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image53.png)

In other words P to the X just consolidates 0.5 times 0.5 into 0.5
squared.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image54.png)

The last part of the equation corresponds to the probability that
someone preferred grape Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image55.png)

Remember that one minus P is the probability that someone prefers grape
fanta

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image56.png)

and n minus X is the number of people that said they preferred grape
Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image57.png)

If we plug in N equals three x equals two and P equals zero point five

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image58.png)

and then do the math we get zero point five.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image59.png)

So this term corresponds to the one person who liked grape Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image60.png)

Thus these two parts of the equation correspond to zero point five times
zero point five times zero point five.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image61.png)

And the nasty part just multiplies it by three.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image62.png)

Now we can put all the parts together

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image63.png)

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image64.png)

and plug in x equals to the number of people that preferred orange Fanta
in equals three the number of people we asked and P equals 0.5 the
probability someone would randomly pick orange Fanta

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image65.png)

and we get the same probability that two out of three people would
randomly prefer orange Fanta that we got when we did everything by hand
0.375.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image66.png)

In other words the binomial distribution tells us that the probability
that two of three people will prefer orange Fanta due to random chance
is 0.375.

BAM !!!

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image67.png)

Calculating the probability of three of three people saying they prefer
orange Fanta by hand is pretty easy since there is only one combination.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image68.png)

But we can just as easily use the fancy formula by plugging in x equals
three

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image69.png)

and then we just do the math this term equals one since we are dividing
three factorial by three factorial

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image70.png)

and this term is also equal one because anything raised to the zero
power equals one

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image71.png)

and then we just keep doing the math

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image72.png)

and this means that the probability of three of three people randomly
preferring orange Fanta is 0.125

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image73.png)

which is exactly what we got when we did the calculations by hand.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image74.png)

Now that we\'ve seen that we can calculate probabilities with the
binomial distribution let\'s go back to our original question if four
people say they\'d like orange Fanta and three people say they\'d like
grape Fanta can we conclude that people in general prefer orange Fanta ?

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image75.png)

Now we plug in x equals for the number of people that preferred orange
Fanta n equals 7 the number of people we asked and P equals 0.5 the
probability someone would randomly pick orange Fanta

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image76.png)

and then just do the math

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image77.png)

and we get zero point two seven three the probability that four of seven
people would randomly prefer orange Fanta.

Double bam !!!

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image78.png)

When you use a binomial distribution to calculate a p-value it\'s called
a binomial test.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image79.png)

So what\'s the p-value for four out of seven people preferring orange
Fanta ?

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image80.png)

The p-value is the probability of the observed data four of seven people
prefer orange Fanta plus the probabilities of all other possibilities
that are equally likely or rarer.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image81.png)

This means we need to calculate these probabilities.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image82.png)

These are the observed results of our poll.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image83.png)

And these are rarer possibilities

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image84.png)

and we also need to calculate the probabilities of these combinations.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image85.png)

These two possibilities for verses three and three versus four are
equally rare.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image86.png)

If you don\'t believe me plug in the numbers and see.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image87.png)

The remaining possibilities are rarer.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image88.png)

In other words by including possibilities when grape Fanta is preferred
equally or more often we are calculating a two-sided p-value.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image89.png)

If this is blowing your mind don\'t freak out just watch the stat quests
on p-values clearly explained and one and two sided p-values (the links
are in the description below).

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image90.png)

We\'ve already calculated the probability that four out of seven people
prefer orange Fanta it\'s zero point two seven three.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image91.png)

For this we just set X to five and plug and chug

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image92.png)

and we get zero point one six four

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image93.png)

then we get zero point zero five five

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image94.png)

and then we get zero point zero zero eight.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image95.png)

Adding the probabilities together gives us 0.5 the probability that
orange Fanta is preferred.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image96.png)

Now we just plug and chug the numbers for when grape Fanta is preferred.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image97.png)

Adding the probabilities together gives us 0.5 the probability that
orange Fanta is not preferred.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image98.png)

The sum of the probabilities of all combinations of events that have an
equal probability or a rarer equals 0.5 plus 0.5 which equals 1.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image99.png)

Which means the p-value for 4 out of 7 people saying that prefer orange
Fanta is 1.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image100.png)

Which means that the model the binomial distribution with P equals 0.5
ie orange Fanta and grape Fanta are both equally loved is a good fit for
the observed data.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image101.png)

Thus we conclude that given the sample size seven we cannot rule out the
possibility that both orange Fanta and grape Fanta are equally loved !!!

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image102.png)

Think about that the next time you watch the World Series of baseball.

Triple bam !!!!

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image103.png)

One last thing before we\'re done.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image104.png)

The binomial distribution only works when the probability that someone
likes orange Fanta does not change if someone else already said they
liked orange Fanta.

![](media/STATQUEST-30-STATISTICS_FUNDAMENTALS-BINOMIAL_DISTRIBUTION_AND_TEST/image105.png)

In other words if we asked a bunch of people if they liked orange Fanta
and they all say yes then that should not affect the probability that
the next person also likes orange Fanta.
