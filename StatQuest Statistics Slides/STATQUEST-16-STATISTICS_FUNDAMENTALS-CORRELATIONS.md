<https://www.youtube.com/watch?v=xZ_z8KWkhXE&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=16>

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image1.png)

Today is part two in our series on covariance and correlation.

This time we\'re going to talk about correlation.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image2.png)

However before we dive deep into correlation, I want to talk about
relationships.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image3.png)

Not the fun and/or confusing kind we sometimes find ourselves in will
you hold my hand um you don\'t have a hand you\'re just a stick figure
dang.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image4.png)

Instead I want to talk about the relationships between data on the
x-axis

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image5.png)

and data on the y-axis.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image6.png)

In this example we\'re looking at mRNA transcripts from gene X in five
different cells on the x-axis

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image7.png)

and from gene Y, in the same five different cells, on the y-axis.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image8.png)

However if mRNA transcripts doesn\'t mean anything to you imagine we
went into five different grocery stores and put the number of green
apples on the x-axis in the number of red apples on the y-axis

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image9.png)

Each pair of measurements were taken from a single cell or grocery store
and can be represented by a blue dot.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image10.png)

We can see that in general relatively low values for gene X are paired
with relatively low values for gene Y

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image11.png)

and relatively high values for gene X are paired with relatively high
values for gene y.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image12.png)

We can use a straight line with a positive slope to represent this
trend.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image13.png)

And if someone told us that they collected a new measurement for gene X,
20

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image14.png)

then we can use the line to predict that when gene X equals 20

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image15.png)

then the value for gene Y should be somewhere around 27.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image16.png)

Alternatively if someone gave us a value for gene Y

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image17.png)

we could use the trend to predict a range of values for gene X.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image18.png)

In both cases we made guesses based on the trend we observed in the
data.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image19.png)

If the data were closer to the trend line

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image20.png)

then given a gene X value we might guess that the value for gene Y falls
in a smaller range.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image21.png)

In this case the closer the data are to the line the more gene X can
tell us about gene y.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image22.png)

Alternatively we could say that the relationship between gene X and gene
Y is relatively strong.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image23.png)

The data were further from the trend line

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image24.png)

then we might guess that the value for gene Y falls in a larger range.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image25.png)

In this case we could say that the values for gene X tell us less about
the values for gene y.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image26.png)

Alternatively we could say that the relationship between gene X and gene
Y is relatively weak.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image27.png)

Note : just to be clear all we are saying is that we observed that low
values for gene X

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image28.png)

tend to be paired with low values for gene Y

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image29.png)

and that high values for gene X tend to be paired with relatively high
values for gene Y

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image30.png)

and that this observation suggests a trend

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image31.png)

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image32.png)

that we can use to make predictions and inferences aka educated guesses.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image33.png)

We are not saying that a low value for gene X

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image34.png)

causes gene Y to have a low value

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image35.png)

or that a high value for gene Y

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image36.png)

causes gene X to have a high value.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image37.png)

In other words we are not ruling out the possibility that something else
causes the trend that we observe.

Small bam.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image38.png)

so far we have looked at a relatively weak relationship

and a relatively strong relationship.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image39.png)

We can quantify the strength of a relationship with correlation.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image40.png)

In other words these data with a relatively weak relationship have a
small correlation value

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image41.png)

these data with a moderate relationship have a moderate correlation
value

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image42.png)

and these data with a strong relationship have a relatively large
correlation value.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image43.png)

The maximum value for correlation is 1.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image44.png)

Correlation equals one when a straight line with a positive slope can go
through the center of every data point.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image45.png)

This means that if someone gave us a value for gene X

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image46.png)

then we could guess that gene y had a value in a very very narrow range.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image47.png)

Note : correlation does not depend on the scale of the data.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image48.png)

In fact I intentionally omitted putting numbers on the axes because they
do not affect correlation at all.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image49.png)

In other words regardless of the scale of the data correlation equals
one when a straight line with a positive slope can go through all of the
data.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image50.png)

That means that correlation can equal one when the slope is large

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image51.png)

and when the slope is small.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image52.png)

Note : when a straight line with a positive slope goes through the data
correlation equals one regardless of how much data we have.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image53.png)

For example if we only had two data points

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image54.png)

then we can draw a straight line with a positive slope by just
connecting the two dots

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image55.png)

and then correlation equals one and that makes the relationship appear
strong

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image56.png)

but we should not have any confidence in predictions made with this line

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image57.png)

because we have so little data.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image58.png)

To understand why we should have low confidence in correlations made
with small datasets.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image59.png)

let\'s start with an empty graph

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image60.png)

and draw two random points on it

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image61.png)

then just like before we could draw a straight line that goes through
the center of each point just by connecting the dots

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image62.png)

and that means correlation equals one for these two randomly drawn dots.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image63.png)

In fact we can always draw a straight line between any two random dots.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image64.png)

Now let\'s go back to the original data and imagine that instead of two
pairs of measurements

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image65.png)

we had three pairs of measurements.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image66.png)

Now just like before since we can draw a straight line through all three
points correlation equals one.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image67.png)

however now we can have more confidence in the predictions we make with
this line.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image68.png)

This is because if we started with an empty graph and drew three random
points on it

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image69.png)

then even though it\'s easy to draw a straight line to connect any two
points

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image70.png)

there is a very small chance that we will be able to draw a straight
line through all three points.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image71.png)

Ultimately the probability that we can connect three randomly drawn
points with a straight line is very small

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image72.png)

and thus we can have more confidence that the observed correlation
isn\'t just the result of random chance.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image73.png)

In general the more data we have

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image74.png)

the more confidence we have in the predictions we make with the line

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image75.png)

because the probability that we can draw a straight line through the
same number of randomly placed points gets smaller and smaller with each
additional point.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image76.png)

Note : we could draw a squiggly line that connects all of the dots

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image77.png)

but when we\'re talking about correlation were only talking about using
straight lines.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image78.png)

Oh no it\'s the dreaded terminology alert !!!

For correlation a p-value tells us the probability that randomly drawn
dots will result in a similarly strong relationship or stronger.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image79.png)

Thus the smaller the p-value the more confidence we have in the
predictions we make with the line.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image80.png)

In this case the p-value is crazy small 2.2 times 10 to the negative 16

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image81.png)

which means that the probability of random data creating a similarly
strong or stronger relationship is crazy small.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image82.png)

To summarize what we\'ve talked about so far.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image83.png)

The maximum value for correlation, 1, occurs whenever you can draw a
straight line with a positive slope that goes through all of the data

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image84.png)

and our confidence in how useful the relationship is depends on how much
data we have.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image85.png)

Of these three examples we should have the least confidence in this
relationship since it is supported by the least amount of data

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image86.png)

and we should have the most confidence in this relationship since it is
supported by the most data and has the smallest p-value.

BAM !!!

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image87.png)

When a straight line with a negative slope can go through the center of
every data point then the correlation equals negative one.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image88.png)

Since a straight line can go through all of the data points correlation
equals negative one implies that there is a strong relationship in the
data

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image89.png)

and if someone gives us a value for gene X

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image90.png)

then we can guess a value for gene Y within a very narrow range.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image91.png)

Just like before our confidence in that guess which we quantify with a
p-value depends on how much data we have.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image92.png)

If we had a lot of data we could have a lot of confidence in the guess
because the p-value would be super small

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image93.png)

and the less data we have the less confidence we have in the guess
because the p-value gets larger.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image94.png)

Just like before as long as a straight line goes through all of the data
and the slope of the line is negative correlation equals negative one
when the slope is large

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image95.png)

and when the slope is small.

BAM !!!

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image96.png)

So far we\'ve seen that when the slope of the line is negative the
strongest relationship has correlation equal to negative one

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image97.png)

and when the slope of the line is positive the strongest relationship
has correlation equal to one.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image98.png)

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image99.png)

In both cases if a straight line cannot go through all of the data then
we will get correlation values closer to zero

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image100.png)

and the worse the fit the closer the correlation gets to zero

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image101.png)

and when there is no relationship that we can represent with a straight
line correlation equals zero.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image102.png)

When correlation equals zero a value on the x-axis

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image103.png)

doesn\'t tell us anything about what to expect on the y-axis

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image104.png)

because there is no reason to choose one value over another.

BAM !!!

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image105.png)

As long as the correlation value is not zero

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image106.png)

we can still use the line to make inferences

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image107.png)

but our guesses become more refined the closer the correlation values
get to negative one or one

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image108.png)

and just like before our confidence in our inferences depends on the
amount of data we have collected and the p-value.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image109.png)

In the left graph we have very little confidence in the trim because we
have very little data and the p value equals 0.8.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image110.png)

In the middle we have moderate confidence in the trend because we have
more data and the p value equals 0.08.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image111.png)

On the right we have a lot of confidence in the trend because we have
even more data in the p value equals zero point zero zero eight.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image112.png)

Note : the correlation equals zero point three in all three examples.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image113.png)

In this case increasing the sample size did not increase correlation and
that means adding data did not refine our guests.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image114.png)

All it did was increase our confidence in the guess.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image115.png)

Thus our guesses will probably be pretty bad in all three cases.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image116.png)

However we\'ll have the most confidence in the bad guest that came from
this data.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image117.png)

In other words just because you have a lot of data and you have a lot of
confidence in your guess

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image118.png)

if the correlation value is small your guests will still be bad.

Double bam !!!

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image119.png)

If you know how to calculate variance and covariance calculating
correlation is a snap.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image120.png)

Note : if you\'re not already familiar with the concepts of variance and
covariance check out the quests the links are in the description below.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image121.png)

If this were the data

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image122.png)

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image123.png)

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image124.png)

then the correlation equals the covariance of gene X and gene Y divided
by the square root of the variance for gene X times the square root of
the variance for gene y.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image125.png)

As we saw in the stat quest on covariance the numerator can be any value
between positive and negative infinity depending on

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image126.png)

whether the slope of the line that represents the relationship is
positive or negative.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image127.png)

How far the data are spread out around the means

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image128.png)

and the scale of the data.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image129.png)

Thus when we calculate correlation the denominator squeezes the
covariance to be a number from negative 1 to 1.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image130.png)

In other words the denominator ensures that the scale of the data does
not affect the correlation value and this makes correlations much easier
to interpret.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image131.png)

When the data all fall on a straight line with a positive or negative
slope

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image132.png)

then the covariance and the product of the square root of the variance
terms are the same and division gives us 1 or negative 1 depending on
the slope.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image133.png)

When the data do not fall on a straight line with a positive or negative
slope.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image134.png)

Then the covariance accounts for less of the variance in the data and
the correlation is closer to zero.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image135.png)

As we saw in the stat quest on covariance the covariance value for this
data is 116

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image136.png)

so the denominator will squeeze 116 down to a value from negative 1 to
1.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image137.png)

The variance in the gene X data is 100 1.8

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image138.png)

and the variants in the gene Y data is 160 point 3

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image139.png)

and when we do the math we get 0.9.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image140.png)

Like I mentioned earlier we can quantify our confidence in this
relationship with a p-value.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image141.png)

The smaller the p-value the more confidence we can have in the guesses
we make.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image142.png)

In this case the p-value is 0.03.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image143.png)

That means that there is a 3% chance that random data could produce a
similarly strong relationship or stronger.

Triple bam !!!!

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image144.png)

Before we go there\'s one last important thing I want to mention about
correlation.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image145.png)

Even though correlation values are way easier to interpret then
covariance values they are still not super easy to interpret.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image146.png)

For example it\'s not super obvious that this relationship where
correlation equals zero point nine is twice as good as making
predictions as

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image147.png)

this relationship where correlation equals zero point six four.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image148.png)

The good news is that R squared which is related to correlation solves
this problem.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image149.png)

The better news is that if you want to learn more about r-squared, you
can check out these quests.

The links are in the description below.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image150.png)

PS : another awesome thing about R squared is that it can quantify
relationships that are more complicated than simple straight lines.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image151.png)

In summary

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image152.png)

correlation quantifies the strengths of relationships if you have a weak
relationship then you will have a small correlation value.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image153.png)

if you have a moderate relationship then you\'ll have a moderate
correlation value

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image154.png)

and if you have a strong relationship then you will have a large
correlation value.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image155.png)

Correlation values go from negative one which is the strongest linear
relationship with a negative slope

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image156.png)

to one which is the strongest linear relationship with a positive slope.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image157.png)

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image158.png)

In both cases if a straight line cannot go through all of the data then
we will get correlation values closer to zero

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image159.png)

and the worse the fit the closer the correlation values get to zero

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image160.png)

and when there is no relationship that we can represent with a straight
line correlation equals zero.

![](media/STATQUEST-16-STATISTICS_FUNDAMENTALS-CORRELATIONS/image161.png)

Lastly our confidence in the inferences depends on the amount of data we
have collected and the p-value the more data we have the smaller the
p-value.

And the more confidence we have in our inferences.

BAM !!!!
