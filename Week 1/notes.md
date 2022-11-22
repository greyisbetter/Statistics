# Week 1
# II. Welcome and Introductions
## Course Welcome
> Statistics is the science to learn from data

**why statistical literacy is essential in data science:**
1. it provides the skills to assess whether the data are sufficient to answer the questions at hand. 
2. it establishes a rigorous framework for quantifying uncertainty. 

# III. Descriptive Statistics and Visualizing Information
## 1. Introduction
• Descriptive statistics: ways to summarize data with numbers and graphs.
- The two most important functions of descriptive statistics are:
	- Communicate information
	- Support reasoning about data

Two ways of summarize data
- Numerical summarize
- summarize using pictures

Chosing visualization is based on **Nature of the data** + **Goal of the visualizaiton**

## 2. Pie Chart, Bar Graph, and Histograms
**Graphical summaries of data**
- use a graphical summary, and that's because people prefer to look at pictures rather than at numbers. 
- Ways ot visualize data depend on the nature of the data and the goal of the visualization.

**For data that a qualitative, use a pie chart or a dot plot**
- Pie chart: each slice of the pie is sliced according to the corresponding percentage. 
- Dot plot: each horizontal line corresponds to one category. 

Adv. and Dis.
- The dot plot makes it easier to compare frequencies of various categories, while the pie chart allows more easily to eyeball what fraction of the total a category corresponds to.


**Bar graphs**
- When the data are quantitative, then they should be put on a number line. This is because the ordering and the distance between the numbers convey imortant information.	
- The bar graph is essentially a dot plot put on its side.

**The histogram**
- The histogram similar to bar graph but it allows to use blocks with different widths
- Area of blocks are proportional to frequency i.e., total area = 100%
- So the precentage falling into a block can be figured without a vertical scale since the total area equals 100%.
- But it's helpful to have a vertical scale (density scale). It's unit is '% per unit'.

__The histogram gives two kinds of information about the data:__
1. **Density (crowding)**: The height of the bar tells how many subjects there are for one unit on the horizontal scale. 

2. **Percentage (relative frequencies):** Those are given by
							area = height x width

## 3. Box-and-Whisker Plot and Scatter Plot
**The boxplot (box-and-whisker plot)**
- The boxplot depicts (visualize) five key numbers of data:
	- Lower whisker: smallest number in the data
	- Upper whisker: largest number in the data
	- Median: the middle of the box plot
	- Ist quartile: the number where a quarter of the data are smaller and three-quarters are larger.
	- IIIrd quartile: the number where three quarters of the data are smaller and one quarter are larger
- The boxplot conveys less information than a histogram, but it takes up less space and so is well suited to compare several datasets.
- the histogram depends on the choice of the intervals that we select for the blocks.

**The scatterplot**
- The scatterplot is used to depict (visualize) data that come as *pair*.
- Those data are plotted in a coordinate system which is called a scatter plot. 
- The scatterplot visualizes the relationship between the two variables.

## 3. Providing Context is Key for Statistical Analyses
- The purpose of a statistical analysis is typically to compare the observed data to some kind of reference. Therefore, it's very useful to provide context in graphical displays. 
	- 'The Visual Display of Quantitative Information' by Edward Tufte

- One way to provide context is by using the principle of small multiples. Like 
	- boxplot: 50 reading of temperature for each month of every month
	- line chart: Time series graph of unemployment rate of each state 

## 4. Pitfalls (unsuspected danger or difficulty) when Visualizing Information
- Sophisticated software makes it tempting to produce showy but poor visualization
- we are looking at three-dimensional blocks. So we are thinking we have to visualize volume when in fact we are just comparing heights

# IV. Numerical Summary Measures
## 1. Mean and Median
- For sumerizing data with one number, use the mean (=average) or the median.
- The median is the number that is larger than half the data and smaller than the other half.

__When__ to use __What__:
- Mean and median are the same when the histogram is symmetric.
- When the histogram is _skewed to the right(right side is much longer than the left side)_, then the mean can be much larger than the median. __Better to use Median__

__EXAMPLE:__
- If the median sales price of 10 homes is $ 1 million, then we know that 5 homes sold for $ 1 million or more.
- If we are told that the average sale price is $ 1 million, then we can't draw such a conclusion:
	=> Sum of the 10 sales prices is $ 10M
	=> If one sold for $ 8M
	=> then the avg sales price of the other 9 homes is ($ 2M)/9 = $ 200,000 approx. != $ 1M, So use median on these cases.


__Percentiles__
Example: The 90th percentile of income is $ 135,000: 90% of households report an income of $ 135,000 or less, 10% report more.

- The 75th percentile is called 3rd quartile
- The 50th percentile is the median
- The 25th percentile is called 1st quartile

## 2. Percentiles, the Five Number Summary, and Standard Deviation
- __Inter-quartile range__: Distance between 1st quartile and 3rd quartile in box plot. It's tells how much data is spead out.

**The standard deviation**
- A more commonly used measure of spread is the __Standard deviation__
- **Formula**
	- it looks at the difference of each number from its average: square the difference
	- then looks at the average of those squared differences.
	- takes the square root.
- x̄ stands for the average of the numbers x1,...,xn.
- The two numbers x̄ and σ are often used to summarize data. Both are sensitive to a few large or small data. 
- If the **histogram is very skewed** then use the median and the Interquartile range

