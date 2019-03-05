Frequency table is a way of displaying categorical data in a way to understand groupings.

An example is marriage status:
Groupings would be how many users for particular marriage status

Frequency charts are the most common way to summarize categorical data
Bar charts are the most common way to visualize categorical data

As a note, would stay away from pie charts for complex categorical visuals (hard to read)

4 main aspects of histograms
1. shape
2. center
3. spread
4. outliers

Shape is the form of the graph. Left scewed, right scewed, bell shape
Center is mean or median
Spread is the range of data, the variance, standard deviation
Outliers, data points that fall below normal points on the graph

What do we mean "Standard Deviation"?
Deviation is the act of departing from accepted standard, or normal. So standard deviation is just asking "Does the data match the median or mean or is it dispersed to other areas?

Low deviation means it fits the graph (bell shape) and median response
High deviation means values observered are spread out (not necessarily the average)

Unimodal - only has one mode or "one peak" like in the bell curve
bimodal - two peaks

Where bar charts are used for categorical data, Histograms are used for quantitative data

Right skewed = right tail (left is higher than right)
Left skewed = left tail (right is higher than left)

IQR - Interquartile Range
IQR is another way of calculating range on a histogram (or set of quantitative data)
IQR is calculated by taking Q3 - Q1 or 75% percentile minus 25% percentile

Example of this would be:
Q1 = 20
Q3 = 25.5

25.5 - 20 = range of 5.5

df.describe works for py for getting data about a set

right skew makes mean greater than median
left skew makes mean less than median

Why is this? The way that mean is calculated is sensitive to extreme values, or in our cases, the values either on the right (right skew... outliers) or left (left skew... outliers)

Standard Deviation is a good way to the let the user know where exactly the data is falling. You can have a range of 14-100, but if Standard Deviation is 68-87, that gives a better picture of where most of the data is
