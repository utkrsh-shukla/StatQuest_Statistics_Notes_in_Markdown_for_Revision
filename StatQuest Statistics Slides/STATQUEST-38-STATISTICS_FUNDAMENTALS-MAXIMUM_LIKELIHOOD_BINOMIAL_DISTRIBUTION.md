<https://www.youtube.com/watch?v=4KKV9yZCoM4&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=39>

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image1.png)

Today we\'re going to talk about maximum likelihood for the binomial
distribution and it\'s gonna be clearly explained.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image2.png)

Note : this stat quest follows up on the stat quest maximum likelihood
clearly explained

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image3.png)

as well as the stat quest probability versus likelihood

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image4.png)

and lastly this stat quest assumes you are already familiar with the
binomial distribution if not check out the stat quest the binomial
distribution and test clearly explained.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image5.png)

In the stat quest on the binomial distribution and test we use the
binomial distribution

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image6.png)

aka this nasty-looking thing

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image7.png)

to determine if in general people like orange Fanta more than grape
Fanta.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image8.png)

In the context of this problem X is the number of people who preferred
orange Fanta in this case x equals 4.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image9.png)

n is the total number of people we asked about whether they preferred
orange Fanta or grape Fanta in this case in equals 7.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image10.png)

And P is the probability somebody would randomly choose orange Fanta
over grape Fanta in this case P equals 0.5.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image11.png)

Altogether, the left side of the equation reads : the probability of X
(the number of people who say they prefer orange Fanta), given n, the
number of people we asked, and P (the probability of picking orange
Fanta).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image12.png)

Then we just plug the numbers in and chugged away at the math

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image13.png)

and the probability that 4 out of 7 people would randomly prefer orange
Fanta is zero point 2 7 3.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image14.png)

Now, if we want to calculate the likelihood of P equals 0.5, then all we
need to do is rearrange the left side of the equation.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image15.png)

That is to say we change this

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image16.png)

to this !

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image17.png)

Now the left side of the equation reads the likelihood of P (the
probability of picking orange Fanta), given n, the number of people we
asked, and X (the number of people who say they prefer orange Fanta).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image18.png)

The right side of the equation, however, stays the same.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image19.png)

And this is now the likelihood of P equals 0.5 given that four out of
seven people would randomly prefer orange Fanta.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image20.png)

Just a reminder : when we calculate likelihoods for P we can plug in
different values for it

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image21.png)

while the observed data in equals 7 and x equals four, remains fixed.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image22.png)

In other words, we can calculate the likelihoods for different values of
P given that four out of seven people said they preferred orange Fanta.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image23.png)

For example, the likelihood of P equals 0.25 given that four out of
seven people said they prefer two orange Fanta is

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image24.png)

plug and chug

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image25.png)

plug and chug plug and chug 0.058.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image26.png)

The likelihood of P equals 0.25 given that four out of seven people
would randomly prefer orange Fanta is less than 0.2 7/3 the likelihood
when P equals 0.5.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image27.png)

We can also calculate the likelihood of P equals 0.57 given that four
out of seven people said they preferred orange Fanta

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image28.png)

plug and chug

plug and chug

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image29.png)

plug and chug and we get zero point two nine four.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image30.png)

The likelihood of P equals zero point five seven given that four out of
seven people would randomly prefer orange Fanta is greater than zero
point two seven three,the likelihood when P equals zero point five.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image31.png)

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image32.png)

We can plot the likelihood with a bunch of different values for P
between zero and one.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image33.png)

Tada !

This peak is the maximum likelihood.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image34.png)

The slope of the curve at the peak is zero.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image35.png)

That means we can solve for the value for P that results in the maximum
likelihood by finding where the derivative I II the slope is equal to 0.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image36.png)

So let\'s do it !!!!

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image37.png)

Here\'s the original likelihood function with n equals 7 and x equals 4.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image38.png)

The first thing we do is take the log of the likelihood function.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image39.png)

We do this because the original likelihood function and its log will
both reach the maximum using the same value for P and it\'s way easier
to take the derivative of the log of the likelihood function compared to
the original function.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image40.png)

To see this, here is a plot of the likelihood function

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image41.png)

and here is the log of the likelihood function

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image42.png)

both have peaks at the same value for P.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image43.png)

The log function turns the multiplication into addition

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image44.png)

and it turns the exponents into multiplication.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image45.png)

If this log stuff is freaking you out well don\'t freak out.

Just watch the stat quest on logs !

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image46.png)

Now we\'re ready to take the derivative.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image47.png)

But first, because we are running out of room, we\'ll move this to the
top of the screen.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image48.png)

Okay, now we take the derivative with respect to P !

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image49.png)

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image50.png)

This first part doesn\'t contain P at all, so it\'s derivative equals
zero.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image51.png)

The derivative of the second part is just four times one over P.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image52.png)

The derivative of this last part is a little tricky since we need to
apply the chain rule.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image53.png)

So we start with (7 minus 4) times the derivative of the log of (1 minus
P)

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image54.png)

and we multiply that by the derivative of (1 minus P).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image55.png)

Then we simplify

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image56.png)

and plug it in !

BAM !!!!

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image57.png)

Now we set the derivative to zero because we want to find the peak where
the slope of the curve equals zero

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image58.png)

and that will tell us which value for P gives the maximum likelihood.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image59.png)

Now multiply both sides by P times (1 minus P).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image60.png)

Now multiply out 4 times 1 minus P

Now combine negative 4 P and negative 3p .

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image61.png)

Then just solve for P.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image62.png)

The maximum likelihood estimate for P is 4, the number of people who
preferred orange Fanta divided by 7, the total number of people we
asked.

Double bam !!!

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image63.png)

Okay, we just solved for the maximum likelihood estimate for P when we
have data for X and n.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image64.png)

However, we don\'t actually need data to determine a general formula for
the maximum likelihood for P.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image65.png)

This formula will give us the maximum likelihood estimate for P when
there are X successes in n trials.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image66.png)

That\'s how you say it using fancy statistics lingo !!!

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image67.png)

We\'ll start with the original likelihood function however this time all
of the variables, P, X and n are unknown.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image68.png)

Just like before, we take the log of the likelihood function because it
will make solving for the derivative way easier.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image69.png)

And just like before, the log function turns the multiplication into
addition

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image70.png)

and the exponents into multiplication.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image71.png)

Now we\'re ready to take the derivative.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image72.png)

And just like before because we are running out of room, we will move
this to the top of the screen.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image73.png)

Okay, now we take the derivative with respect to P !

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image74.png)

The first part does not contain P, so it\'s derivative is zero.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image75.png)

The derivative of the second part is just x times 1 over P.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image76.png)

And just like before, we have to use

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image77.png)

the chain rule

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image78.png)

to figure out the derivative of this last part.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image79.png)

So we start with (n minus x) times the derivative of the log of (1 minus
P)

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image80.png)

and we multiply that by the derivative of (1 minus P).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image81.png)

Then we simplify

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image82.png)

and plug it in !

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image83.png)

Then, just like before we set the derivative to zero.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image84.png)

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image85.png)

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image86.png)

Note : different values for n and X will result in different curves but
the slope is still zero at the maximum likelihood.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image87.png)

Now multiply both sides by P times (1 minus P).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image88.png)

Now multiply out x times (1 minus P).

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image89.png)

And now negative XP and positive XP cancel each other out

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image90.png)

then just solve for P.

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image91.png)

In this case, the maximum likelihood estimate for P is X, the number of
successes, divided by n, the total number of trials.

BAM !!!

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image92.png)

Some of you may be saying to yourself, duh !! what\'s the big deal ?

The maximum likelihood estimate for P is just the average that\'s
obvious !!!

![](media/STATQUEST-38-STATISTICS_FUNDAMENTALS-MAXIMUM_LIKELIHOOD_BINOMIAL_DISTRIBUTION/image93.png)

Well, I agree, once you know the solution it\'s pretty obvious.

But now we also have a mathematical proof that backs up our intuition,
and to me, that\'s a very comforting thing.
