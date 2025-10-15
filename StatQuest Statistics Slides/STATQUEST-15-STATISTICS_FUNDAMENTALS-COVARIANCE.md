<https://www.youtube.com/watch?v=qtaqvPAeEJY&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=15>

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image1.png)

Today we\'re going to talk about covariance and this is part 1 in a
two-part series on covariance and correlation.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image2.png)

Note : this stack quest assumes that you are already familiar with the
concept of variance.

If not check out the quest.

The link is in the description below.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image3.png)

In the stack quest on variance we\'ve started with the number of mRNA
transcripts for gene X from 5 different cells.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image4.png)

And if mRNA transcripts aren\'t your thing you could think that we
counted the number of green apples in five different grocery stores.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image5.png)

Then we estimated the mean x-bar

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image6.png)

and then we estimated the variance.

De Do Boop BAM.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image7.png)

And that\'s our review of variance.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image8.png)

Now imagine that in addition to counting mRNA transcripts for gene X we
also counted gene Y transcripts in the same 5 cells.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image9.png)

Alternatively you can imagine we counted the number of red apples in the
same 5 grocery stores.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image10.png)

Note : if you\'re wondering why gene Y is perpendicular to gene X don\'t
sweat it the reason will become clear in just a bit.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image11.png)

anyway just like we did for gene X we can estimate the mean for gene y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image12.png)

and since gene Y is on the y axis we will use Y bar to represent its
mean value

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image13.png)and we can estimate the variance T 2 2 2 2
2 2 2 2 2 2 2

BAM !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image14.png)

So far we\'ve estimated the mean and variance for two different genes
measured in the same five cells.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image15.png)

Alternatively you could imagine we estimated the mean and variance for
two different types of apples counted in the same five grocery stores.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image16.png)

Since these measurements were taken from the same cells or the same
grocery stores we can look at them in pairs.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image17.png)

For example this pair of measurements came from the same cell

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image18.png)

and both measurements are less than their respective mean values.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image19.png)

This pair of measurements came from another cell

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image20.png)

and both measurements are greater than their respective mean values.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image21.png)

Since the measurements were taken in pairs the question is : do the
measurements taken as pairs tell us something that the individual
measurements do not ?

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image22.png)

Covariance is one way to try to answer this question.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image23.png)

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image24.png)

Since the measurements came from the same cells or grocery stores we can
plot each pair as a single dot by combining the values on the x and y
axes.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image25.png)

Now generally speaking we see that cells with relatively low values for
gene X also have relatively low values for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image26.png)

and cells with relatively high values for gene X also have relatively
high values for gene Y.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image27.png)

This relationship low measurements for both genes and some cells and
high measurements for both genes and other cells can be summarized with
this line.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image28.png)

Note : the line that represents this particular relationship has a
positive slope

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image29.png)

and it reflects the positive trend where the values for gene X and gene
Y increase together.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image30.png)

In other words if you told me that there were a lot of transcripts for
gene X in a cell

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image31.png)

then the trend suggests that the same cell should have a large number of
transcripts for gene Y.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image32.png)

Likewise if you told me that you had a low value for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image33.png)

then the trend suggests that the same cell should have a small number of
transcripts for gene X.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image34.png)

If the data had looked like this

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image35.png)

and relatively low values for gene X correspondent with relatively high
values for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image36.png)

and relatively high values for gene X correspondent with relatively low
values for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image37.png)

then the relationship would have a negative slope

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image38.png)

and reflect the negative trend that the values for gene X increase as
the values for gene y decrease.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image39.png)

If the data had looked like this

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image40.png)

and every value for gene X was paired with the same value for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image41.png)

then there would be no trend positive or negative between gene X and
gene Y.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image42.png)

This is because if you told me that you got the same measurement for
gene Y found in all of the other cells

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image43.png)

then we would not know if the same cell should have a relatively small
value for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image44.png)

or a relatively large value

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image45.png)

or any other value.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image46.png)

Likewise if every value for Jean Y was paired with the same value for
Jean X there would be no relationship.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image47.png)

This is because if you told me that you got the same measurement for
gene X found in all of the other cells

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image48.png)

then we would not know if the same cell should have a relatively small
value for gene T

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image49.png)

or a relatively large value

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image50.png)

or any other value.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image51.png)

The main idea behind covariance is that it can classify three types of
relationships.

1\. relationships with positive trends.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image52.png)

2\. relationships with negative trends

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image53.png)

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image54.png)

and 3. times when there is no relationship because there is no trend.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image55.png)

Okay we just covered the main idea behind covariance.

It\'s so important that I\'m going to repeat it, covariants can classify
these three types of relationships :

1.  relationships with positive trends

2.  relationships with negative trends

3.  and 3 times when there is no relationship because there is no trend.

BAM !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image56.png)

The other main idea behind covariance is kind of a bummer.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image57.png)

Covariance in and of itself is not very interesting.

What I mean by this is that you will never calculate covariance and be
done for the day.

Instead covariance is a computational stepping-stone to something that
is interesting like correlation.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image58.png)

Like repeating myself let me repeat the second main idea behind
covariance.

Covariance is a computational stepping-stone to something that is
interesting like correlation.

La covariance est un tremplin informatique vers quelque chose qui est
intéressant, comme la corrélation

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image59.png)

So let\'s talk about how covariance is calculated

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image60.png)

covariance is calculated with a slightly nasty looking thing

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image61.png)

to get an intuitive sense for how covariance is calculated let\'s go
back to the mean value for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image62.png)

and extend the green line to the top of the graph

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image63.png)

and then extend the red line that represents the mean for Jean why to
the edge of the graph.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image64.png)

Now let\'s focus on the leftmost data point.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image65.png)

Since it\'s to the left of the solid green line we see that it is less
than the mean value for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image66.png)

and since it is below the solid red line we see that it is less than the
mean value for gene y.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image67.png)

Now let\'s plug in the gene X measurement for this cell

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image68.png)

and the main value for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image69.png)

and that gives us this difference

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image70.png)

which is negative since it is to the left of the mean.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image71.png)

Now let\'s plug in the gene Y measurement for this same cell

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image72.png)

and the mean value for gene Y and that gives us this difference

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image73.png)

which is negative because it is below the mean

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image74.png)

and since both differences are negative

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image75.png)

multiplying them together gives us a positive value.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image76.png)

Now we do the same thing for the next data point.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image77.png)

Again since it is to the left of the solid green line we can see that it
is less than the mean for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image78.png)

and since it is below the solid red line we can see that it is less than
the mean for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image79.png)

so we plug in the values for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image80.png)

and that gives us a negative difference.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image81.png)

Now we plug in the values for gene Y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image82.png)

and that gives us another negative difference.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image83.png)

Again since both differences are negative multiplying them together
gives us a positive value.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image84.png)

So we see that when the values for gene X and gene Y are both less than
their respective averages we end up with positive values.

BAM !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image85.png)

The remaining three cells are to the right of the solid green line so we
see that they are all greater than the average value for gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image86.png)

and they are all above the solid red line so we see that they are also
greater than the average value for gene y

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image87.png)

thus when we plug in the values

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image88.png)

and do the math

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image89.png)

we end up with positive values

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image90.png)

too in the math I\'m doing the math hip-hip-hooray I\'m doing the math
hip hip hooray hip hip hooray.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image91.png)

So we see that when both values are greater than their respective means
we end up with positive numbers.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image92.png)

In summary data in these two quadrants contribute positive values to the
total covariance.

Bamm.

Hooray.

We\'ve calculated these terms for each cell

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image93.png)

the Sigma tells us to add up each term

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image94.png)

and then we divide by the number of measurements in which in this case
is 5-1

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image95.png)

and ultimately we end up with a covariance equal to 116.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image96.png)

Since the covariance value 116 is positive it means that the slope of
the relationship between gene X and gene Y is positive.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image97.png)

In other words when the covariance value is positive we classify the
trend as positive.

Double bam !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image98.png)

Note : the covariance value itself isn\'t very easy to interpret and
depends on the context.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image99.png)

For example the covariance value does not tell us if the slope of the
line representing the relationship is steep

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image100.png)

or not steep.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image101.png)

It just tells us that the slope is positive.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image102.png)

More importantly the covariance value doesn\'t tell us if the points are
relatively close to the dotted line

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image103.png)

or relatively far from the dotted line.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image104.png)

Again it just tells us that the slope of the relationship is positive.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image105.png)

Note we\'ll talk about why the covariance value is so hard to interpret
later.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image106.png)

And remember even though covariance is hard to interpret it is a
computational stepping stone to more interesting things.

BAM !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image107.png)

Now let\'s imagine we got different values for gene Y.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image108.png)

Just like before we can graph the data using pairs of X and y-axis
values.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image109.png)

The mean value for gene X is the same as before seventeen point six

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image110.png)

and the mean value for jean y is 20 point 2.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image111.png)

Now let\'s focus on the data point on the far left.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image112.png)

Since the measurement for gene X is to the left of the solid green line
we can see that it is less than the mean value.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image113.png)

However the measurement for gene Y is above the solid red line so we see
that it is greater than the mean value.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image114.png)

Thus when we plug in the numbers and do the math

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image115.png)

we end up with a negative number.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image116.png)

And the same thing happens to the next data point

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image117.png)

we end up with a negative number.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image118.png)

So if one value is less than its mean and one value is more than its
mean we end up with a negative number.

BAM !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image119.png)

Likewise these cells also result in negative numbers because they are
greater than gene X\'s mean and less than gene Y's mean.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image120.png)

In summary data in these quadrants contribute negative values to the
covariance.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image121.png)

Now we add up each term

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image122.png)

and then we divide by the number of measurements in which is 5-1.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image123.png)

And ultimately we end up with a covariance equal to negative 100 5.15.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image124.png)

Since the covariance value negative 100 5.15 is negative it means that
the slope of the relationship between gene X and Gen Y is negative.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image125.png)

Again covariance doesn\'t tell us if the slope is steep or not

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image126.png)

and more importantly covariance doesn\'t tell us if the points

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image127.png)

or relatively close to the line or relatively far

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image128.png)

just that the slope is negative.

BAM !!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image129.png)

Now let\'s calculate the covariance for when there is no trend.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image130.png)

In this case every value for gene X corresponds to the same value for
gene Y.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image131.png)

First we calculate the means

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image132.png)

then we do the math for the first point

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image133.png)

the difference from gene X\'s average is negative 14 point 6

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image134.png)

and the difference from jean Weis average

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image135.png)

is zero and anything times zero is zero.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image136.png)

So the value for the first data point is zero.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image137.png)

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image138.png)

Likewise because the differences between the gene y-values in the gene y
average are all 0 all of the remaining terms are 0

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image139.png)

Doing the rest of the math gives us 0 in the numerator and the whole
thing equals 0.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image140.png)

Likewise when every value for Jean Y corresponds to the same value for
gene X the covariance equals zero.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image141.png)

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image142.png)

In this last case we can see that even though there are multiple values
for gene x and y there is still no trend because as gene X increases
gene Y increases and decreases.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image143.png)

In other words the negative value for this point

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image144.png)

is cancelled out by this positive point

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image145.png)

and this positive point

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image146.png)

is canceled out by this negative point

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image147.png)

and the covariance equals zero.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image148.png)

So we see that the covariance equals zero when there is no relationship
between gene X and gene y.

Double BAM !!!

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image149.png)

Now let\'s talk about why the covariance value is hard to interpret.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image150.png)

To see why the covariance value is difficult to interpret let\'s go all
the way back to looking at just gene X

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image151.png)

and calculate the covariance between gene X and itself.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image152.png)

Just like before we can plot the data

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image153.png)

and mean value for gene X is the same as before 17.6

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image154.png)

and we use 17.6 on the y-axis as well.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image155.png)

Now we are ready to calculate the covariance.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image156.png)

Note : in this case the same data are on both axes and that means x
equals y and x bar equals y bar

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image157.png)

so we can replace Y with X and y bar with X bar

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image158.png)

and then we can multiply X minus X bar times X minus X bar

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image159.png)

and we are left with a formula for estimating variance.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image160.png)

In other words the covariance for gene X with itself is the same thing
as the estimated variance for gene X.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image161.png)

Now when we do the math we get 102.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image162.png)

Since the covariance value is positive we know that the relationship
between gene X and itself has a positive slope.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image163.png)

So let\'s move the graph and the covariance value over here

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image164.png)

and see what happens when we multiply the data by two.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image165.png)

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image166.png)

Now the X and y axis labels on the right are twice what they are on the
left

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image167.png)

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image168.png)

and the new mean values are twice what they were before

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image169.png)

but the relative positions of the data did not change

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image170.png)

and each dot still falls on the same straight line with positive slope.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image171.png)

In other words the only thing that changed was the scale that the data
is on.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image172.png)

However when we do the math we get covariance equals four hundred eight

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image173.png)

which is four times what we got before.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image174.png)

Thus we see that the covariance value changes even when the relationship
does not.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image175.png)

In other words covariance values are sensitive to the scale of the data
and this makes them difficult to interpret.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image176.png)

The sensitivity to scale also prevents the covariance value from telling
us if the data are close to the dotted line that represents the
relationship

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image177.png)

or far from it.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image178.png)

In this example the covariance on the left when each point is on the
dotted line is 102

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image179.png)

and the covariance on the right when the data are relatively far from
the dotted line is 381.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image180.png)

So in this case when the data are far from the line the covariance is
larger.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image181.png)

Now let\'s just change the scale on the right hand side

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image182.png)

and recalculate the covariance

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image183.png)

and now the covariance is less for the data that does not fall on the
line.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image184.png)

If you\'re thinking I sure wish there was something to describe
relationships that wasn\'t sensitive to the scale of the data then
you\'re in luck.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image185.png)

Calculating covariance is the first step in calculating correlation.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image186.png)

Correlation describes relationships and is not sensitive to the scale of
the data

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image187.png)

and we\'ll talk about correlation more in the next video in this series.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image188.png)

It\'s also worth mentioning that covariance values are used as stepping
stones in a wide variety of analyses.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image189.png)

For example covariance values were used for principal component analysis
PCA and are still used in other settings as computational
stepping-stones to other more interesting things.

BAM.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image190.png)

In summary covariance is a way to classify three types of relationships.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image191.png)

1\. when the covariance is positive it means the relationship has a
positive slope

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image192.png)

2\. when the covariance is negative it means the relationship has a
negative slope.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image193.png)

and 3. when covariance equals zero there is no relationship because
there is no trend.

![](media/STATQUEST-15-STATISTICS_FUNDAMENTALS-COVARIANCE/image194.png)

The covariance value itself is difficult to interpret however it is
useful for calculating correlations and in other computational settings.
