<https://www.youtube.com/watch?v=okjYjClSjOg&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=33>

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image1.png)

Today we\'re gonna be talking about quantile, quantile plots.

These are called QQ plots sometimes and they\'re gonna be clearly
explained.

This stat quest assumes you already know what a quantile is if you
don\'t.

Nno big deal !

Just check out the stat quest on quantiles and percentiles and then you
can watch this one in or make a lot more sense.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image2.png)

We\'ll start with this data set where we measured expression in 15
genes, total.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image3.png)

One question we might have is is this data normally distributed ?

A QQ plot will help answer that question.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image4.png)

Step 1 give each point its own quantile.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image5.png)

Step 2 get yourself a normal curve any normal curve will do.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image6.png)

Step 3 add the same number of quantiles to the curve as you created for
the data .

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image7.png)

That is to say there are 15 lines dividing the data into equal sized
groups

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image8.png)

and there are 15 lines dividing the normal curve into equal sized
groups.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image9.png)

For the normal curve equal sized groups means that there is an equal
probability of observing a value within each group.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image10.png)

This means that groups on the edge must be wider to account for the
lower probability of observing a value out there

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image11.png)

and groups in the middle are narrower since there is a higher
probability of observing a value in that region.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image12.png)

Step 4 now plot your QQ graph !!!

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image13.png)

A QQ graph has two axes

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image14.png)

one for the quantiles that we generated from our data set and one for
the quantiles we generated from the normal distribution.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image15.png)

We\'ll start with the smallest quantile in our data set this quantile is
at 0.6 and our data set.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image16.png)

And so we\'ll draw a dotted line on the QQ plot to indicate that
location then we draw a vertical line representing the position of the
smallest quantile in the normal distribution.

This quantile is at negative 1.5.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image17.png)

So that\'s where our vertical dotted line goes now all we do is put a
dot where those two lines intersect.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image18.png)

Now we move on to the second quantile in the data set that we collected.

This one is at one point one.

So we have a horizontal dotted line at one point one in our quantile
quantile graph.

Then we draw a vertical line at the location of the second quantile in
the normal distribution.

This quantile is at negative 1.2.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image19.png)

So we draw a vertical line at negative 1.2 then we draw a dot where the
two lines intersect

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image20.png)

The third quantile in the data set that we collected is at 1.9.

So we draw a horizontal line at 1.9.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image21.png)

And the 3rd quantile in our normal distribution is at negative zero
point 8 9.

So we draw a vertical line at that position and then we draw a dot where
the two lines intersect.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image22.png)

And then we just do the same thing over and over.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image23.png)

Again for each quantile until we have all the quantiles represented in
our quantile quantile graph.

Hooray !!!

Now we\'ve got dots showing where the quantiles from our data set
intersected with the quantiles from the normal distribution on our
graph.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image24.png)

Now we see how well the dots fit a straight line

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image25.png)

if the data were normally distributed most of the points would be on the
line.

This would mean that both the data set and the normal distribution have
comparable quantiles.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image26.png)

In this case the fit is not awesome

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image27.png)

so we should compare the data that we collected to another distribution.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image28.png)

What if we compare our data to a uniform distribution ?

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image29.png)

The process is the same :

Step 1 give each point its own quantile.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image30.png)

Step 2 get yourself a uniform distribution.

Any old uniform distribution will do.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image31.png)

Step 3 add the same number of quantiles to the distribution as you
created for your data.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image32.png)

Step 4 now plot your QQ graph !!!

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image33.png)

Just like before we\'ve got the data quantiles on the y axis and the
distribution quantiles on the x axis.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image34.png)

Now we draw a straight line that goes through the points in the graph
and look.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image35.png)

The points are much closer to the line in the QQ plot indicating that
the uniform distribution is a better fit.

So if you\'re ever wondering which distribution matches your data well
you could use QQ plots to answer that question ok.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image36.png)

One last thing before we\'re done !

What if we want to compare the original data set to another one this
second one is much smaller.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image37.png)

The new data set only has four quartiles quartiles are just quantiles
when you only have four of them.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image38.png)

So we determine four quartiles for the original data set and compare
those .

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image39.png)

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image40.png)

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image41.png)

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image42.png)

And just like we did when we compared the data set that we gathered to
the normal distribution and the uniform distribution we plot a QQ plot
by drawing horizontal and vertical lines representing the quantiles from
the two data sets that we collected.

And where the two lines intersect we draw a dot and we just repeat this
process for each pair of quantiles until we have all the quantiles
represented on the graph.

Hooray !!

Now we\'ve got all the quantiles plotted on our QQ graph.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image43.png)

Now at a straight line to determine how similar the distributions are.

![](media/STATQUEST-32-STATISTICS_FUNDAMENTALS-GRAPHIQUES_QUANTILES_QUANTILES_Q-Q-Plot/image44.png)

With just a few quantiles in our plot it\'s hard to have a definitive
answer about whether or not the two data sets have similar
distributions.

But you get the idea if we collected more data we\'d have more quantiles
and would know more.
