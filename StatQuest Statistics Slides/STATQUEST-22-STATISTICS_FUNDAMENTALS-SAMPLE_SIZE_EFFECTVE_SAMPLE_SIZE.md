<https://www.youtube.com/watch?v=67zCIqdeXpo&list=PLblh5JKOoLUK0FLuzwntyYI10UQFUhsY9&index=23>

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image1.png)

Today we\'re going to be talking about sample size and effective sample
size, they\'re gonna be clearly explained.

This stat quest builds on what we learned in the stat quest on technical
and biological replicates.

So if you\'re not already familiar with those concepts, you better check
that stat quest out ASAP.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image2.png)

Let\'s start with a simple example.

Let\'s imagine we are interested in testing a hypothesis about gene
expression in blue dudes.

If you\'re a mouse geneticist you can think of blue dudes as a specific
strain of mouse.

If you\'re interested in trees you can think of blue dudes as a specific
type of tree.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image3.png)

We start with a blue dude

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image4.png)

And then we take a blood sample and then we use that blood sample to
measure gene expression.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image5.png)

Then we do the same thing with another blue dude.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image6.png)

And then lastly we do the same thing with a third blue dude.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image7.png)

We\'ve got 3 measurements from three separate blue dudes.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image8.png)

Since we\'re interested in reporting gene expression in blue dudes, n
equals three, where n is short hand for 'sample size'.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image9.png)

On the other hand, if we\'re interested in reporting gene expression in
blue ladies, then N equals zero.

Duh !!!

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image10.png)

If we measure gene expression twice in each blue dude and we still
wanted to report a result that applied to dudes the sample size would
still be three.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image11.png)

These pairs of measurements are technical replicates and tell us about
the accuracy of our method for measuring gene expression.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image12.png)

They don\'t tell us about differences between blue dudes.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image13.png)

If we were interested in describing the accuracy of our method for
measuring gene expression and were not interested in describing dudes
then we would count the technical replicates.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image14.png)

In this case N equals four.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image15.png)

Technical replicates only count when we want to describe a method (and
not people or mice or something else).

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image16.png)

So far so good !

Everything is pretty straight forward.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image17.png)

Now let\'s look at something a little more complicated.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image18.png)

Let\'s imagine we wanted to test a hypothesis that applied to dudes in
general (not just blue dudes).

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image19.png)

In this case it is important that in addition to blue dudes, we measure
orange dudes and green dudes.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image20.png)

And here in equals 3.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image21.png)

Still no big deal, but what if the blue dude had a twin ?

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image22.png)

And we added that due to the study and we measured his gene expression.

What\'s the sample size now is it 3 or 4 ?

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image23.png)

It\'s actually somewhere in between.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image24.png)

While these twins are clearly two different and separate people their
genomes are the same and thus their gene expression will be highly
correlated compared to the other dudes in the study.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image25.png)

If we know (or can calculate) the correlation between the twins we can
calculate their effective sample size.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image26.png)

For example, suppose we calculated the correlation between the twins to
be 0.7.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image27.png)

The equation for the effective sample size is : the number of samples
divided by one plus the number of samples minus one times the
correlation.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image28.png)

So we plug in the numbers for the number of samples and the correlation

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image29.png)

and then we do the math we end up with 1 point 1 8.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image30.png)

When the correlation is high between the twins, instead of being counted
as two people, they are counted as one point 1 8 people.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image31.png)

Now let\'s see what happens when the correlation is low.

This time it\'s equal to 0.1.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image32.png)

Again we can use the equation for the effective sample size to figure
out how many people.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image33.png)

These two people actually are first plug in the numbers t

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image34.png)

hen do the math in this case we got 1 point 8 2 just a little bit less
than 2.

When the correlation is low between the twins they almost count as much
as two people.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image35.png)

In practice calculating the effective sample size can be more
complicated but you get the general idea samples that are highly
correlated don\'t count as individual samples.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image36.png)

In summary :

1\. if we want to report about the accuracy of a method the sample size
is just the number of technical replicates.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image37.png)

In this case N equals 3.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image38.png)

If we want to report about blue dudes or a specific strain of mouse or
tree or whatever then the sample size is the number of blue dudes.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image38.png)

In this case N equals 3.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image39.png)

If we want to report about all kinds of dudes or all kinds of mice we
need to take correlations into account when calculating the sample size.

![](media/STATQUEST-22-STATISTICS_FUNDAMENTALS-SAMPLE_SIZE_EFFECTVE_SAMPLE_SIZE/image40.png)

If the correlation between blue dudes is 0.7 the effective sample size
is three point one eight.

If the correlation between blue dudes is zero point one, the effective
sample size is three point eight two.
