<https://www.youtube.com/watch?v=IFKQLDmRK0Y&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=32>

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image1.png)

Today we\'re going to be talking about quantiles and percentiles and
they\'re gonna be clearly explained.

I thought putting this stat quest together was going to be super easy
but doing a little research sent me down a crazy rabbit hole pretty
much.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image2.png)

Every webpage I looked at had a slightly different explanation.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image3.png)

Part of the problem is that there\'s a difference between how the word
quantile is defined and how quantiles are used in practice.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image4.png)

The other problem is that there\'s a ton of different ways to calculate
quantiles.

The quantile function in R alone has nine different methods.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image5.png)

Let\'s start by talking about the strict definition of quantile.

And then we\'ll move on and talk about how the word is used in practice.

If you can recognize the definition you can skip it and move on to
something more useful !

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image6.png)

We\'ll start by measuring expression for a gene.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image7.png)

Then we measure expression for another gene.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image8.png)

We measured expression from 15 genes total.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image9.png)

This is the median value, 50% of the genes have higher expression and
50% of the genes have lower expression.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image10.png)

Technically speaking, the median is a quantile because it splits the
data into groups that contain the same number of data points.

In this example there are seven data points below the line and seven
data points above the line.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image11.png)

Sometimes this quantile the medium is labeled 0.5 since it splits the
data in half and sometimes it\'s labeled 50% since 50% of the data is
above it and 50% is below it .

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image12.png)

The median value is 4.5.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image13.png)

Thus the 50 percent or 0.5 quantile value is 4.5.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image14.png)

To summarize this first point.

The median is a quantile because it splits the data into equal sized
groups.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image15.png)

This is called the 0.5 quantile or the 50% quantile.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image16.png)

Regardless of which notation is correct you\'re likely to see both of
them in the wild.

So let\'s just roll with it and not get to been out of shape over the
nomenclature.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image17.png)

Now we\'ve added two more lines.

Together with the first line they divide the data into four equally
sized groups.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image18.png)

These new lines are quantiles because they divide the data into equally
sized groups.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image19.png)

This one is called the 0.25 or 25 percent quantile because 1/4 or 25% of
the points are less than it.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image20.png)

The 25% or 0.25 quantile is 2.5.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image21.png)

This one is called the 0.75 or 75 percent quantile because
three-quarters or 75% of the points are less than it.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image22.png)

The 75 percent or 0.75 quantile is 7.3.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image23.png)

In general quantiles are just the lines that divide data into equally
sized groups.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image24.png)

At least that\'s the technical definition.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image25.png)

And technically speaking percentiles are just quantiles that divide the
data into 100 equally sized groups.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image26.png)

However in practice the terminology is much more flexible.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image27.png)

Even though this data set isn\'t large enough to be divided into 100
groups we still call the median or the fiftieth quantile the fiftieth
percentile.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image28.png)

And this is called the 75th percentile.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image29.png)

And this is called the twenty-fifth percentile.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image30.png)

Often the terms quantile and percentile are used when we divide each
data point into its own group.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image31.png)

Since no values are less than this one at the bottom it\'s called the
zero percent quantile or the zeroth percentile.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image32.png)

This data point is the one divided by fifteen equals seven percent
quantile or the seventh percentile.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image33.png)

I use one divided by fifteen because there\'s one data point of the
fifteen that are less than it.

This data point is the three divided by fifteen or twenty percent
quantile or the twentieth percentile etc etc etc. Calculating quantiles
and percentiles is just a matter of finding out how many values are less
than the value you\'re interested in.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image34.png)

one last thing before we move on.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image35.png)

So far I\'ve shown you one way to calculate the quantiles and
percentiles however there are many more.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image36.png)

R\'s quantile function provides nine different ways to calculate
quantiles each one resulting in slightly different results.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image37.png)

What this means is that if your data set is small don\'t put too much
stock in the quantiles since they can change a lot from method to method
and sample to sample.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image38.png)

However when your data set is large then all of the methods give fairly
similar results.

![](media/STATQUEST-31-STATISTICS_FUNDAMENTALS-QUANTILE_PERCENTILE/image39.png)

Now that we know what quantiles and percentiles are we can talk about
quantile quantile plots and quantile normalization which I\'ll cover in
separate stat quests.
