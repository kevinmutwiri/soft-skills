# Data Visualization

> [home](./README.md)

- [Bar charts](#bar-charts)
- [Clustered Bar Chart](#clustered-bar-chart)
- [Line Charts](#line-charts)
- [Pie Charts](#pie-charts)
- [Stacked Bar Chart](#stacked-bar-chart)
- [Clustered Bar Chart](#clustered-bar-chart)
- [Histogram](#histogram)
- [Scatter Plot](#scatter-plot)
- [Bubble Charts](#bubble-charts)
- [Improving Charts & Graphs: Labeling](#improving-charts-graphs-labeling)
- [Improving Charts & Graphs: Units](#improving-charts-graphs-units)
- [Improving Charts & Graphs: Position and Format](#improving-charts-graphs-position-and-format)
- [Improving Charts & Graphs: Titles](#improving-charts-graphs-titles)
- [Manipulation of Charts](#manipulation-of-charts)

## Intro to Charts

For your audience to understand your data and the story you want to tell with it, you will often need to present that data in the form of visuals. 

Understanding charts is another key professional skill to have in your toolkit.

Let’s get started by observing the chart below

<img width="1920" height="1080" alt="eb5db6c98a9ed227b0b33a735cdebaf5405ccbf2" src="https://github.com/user-attachments/assets/230eee79-167c-42c6-87d7-dee25eead738" />

There are 5 major elements in this chart that you should take note of. These elements are delineated in the next image below.

<img width="1920" height="1080" alt="75decce8f68934db8cc687e3a8b6bb84f9224a2d" src="https://github.com/user-attachments/assets/240ade33-acd3-4b5d-a3a1-50b9ebdc951d" />

From the image, you will realize that the 5 elements are:

- Chart Title
- Vertical Axis Title
- Horizontal Axis Title
- Axes Labels
- Data Labels

For almost all of the charts and graphs, you will use for visualisations, these core elements will be enumerated below

**What information is the first chart giving us?**
If you answered that the chart is giving us information about the number of people infected with the COVID-19 virus, then you are right. How did we know this? It was because of the Chart Title.

Before we explain the different elements, let’s get rid of all the elements you saw and see how the chart will look like below.

<img width="1920" height="1080" alt="8bcc87d1333231f6fcd7735d5b3e38fa662318c7" src="https://github.com/user-attachments/assets/06e9303e-36eb-4077-a14b-5b0757607a6c" />

That is an extremely sad-looking chart.

### 1. Chart Title

The chart title is arguably the most important piece of the chart. It is the element that lets the audience know what your chart is about. Your chart titles should be descriptive enough such that at first glance, your audience knows what information the chart intends to give them. However, the title should also be brief and concise so that the graph is not cluttered. It is usually placed at the top of the chart. Let’s add the chart title now to see the effect.

<img width="1920" height="1080" alt="ca5e734f89cbaa77a920cb5d3ed7307f069d8dc2" src="https://github.com/user-attachments/assets/23ceeaf1-4ece-4238-a652-25b86d64cf04" />

At least now we have a sense of what those bars represent. However, that is not enough. Let’s add more elements.

### 2. Horizontal Axis Titles and Vertical Axes Titles

The next pieces of elements on the chart we will discuss are the axes titles. These titles are also very important. They help people figure out what exactly is plotted on the chart/graph. Once again, make these titles concise and descriptive. As part of making the titles descriptive, make sure to add the unit of measurement for the axes where relevant. In the graph you saw above, imagine if the vertical axis did not have figures, we would not know what the number represents (i.e., whether the number is people or regions, etc). As such, it is important to include the units to make your charts a bit more descriptive. After adding the axes titles to our chart, we have the image below.


<img width="1920" height="1080" alt="98abbfc78294fdc72f7632e4f8e3d334866b71f6" src="https://github.com/user-attachments/assets/913ad7e5-5ae3-4aa2-aaee-207d5b015652" />

### 3. Axes Labels

Our chart has the chart title as well as the vertical and horizontal axis titles. However, this is still not enough information for people to understand what this graph is showing. The axes label the number of infected people ranging from 50,000 to 300,000 in three different Countries. We can tell what bar belongs to what Country and what value each bar corresponds to because the axes have been labelled. However, we can do one more thing to make it even better.

<img width="1920" height="1080" alt="c3f12130da34b0828db0c029bab636164dc3c9df" src="https://github.com/user-attachments/assets/930c5d02-6598-418c-ac50-ac1682f40866" />

Add data labels to the bar.

### 4. Data Labels

Even though the last chart shown gives us all the necessary information we need to understand the visualisation without having someone explain what is going on there, it is still a tad hard to map each country to the corresponding infection cases. The data labels will facilitate this process for us. Data labels uniquely identify each bar or data point in the chart for us to make the value of that data point easily recognizable. Let us now add the data labels.

<img width="1920" height="1080" alt="b2eb2dde05230c52647161ff64ec077512447b40" src="https://github.com/user-attachments/assets/0e70aad3-b692-4eaf-ab7d-f06e3bd188a9" />

Great! Now we do not have to guesswork on the exact value of cases for each country.

**Caution**:
Data labels do not always enhance the comprehensiveness of the chart. Sometimes, they take away from the chart’s clarity and make it messier, so use data labels wisely

## Bar charts

Bar charts are one of the most common ways to visualize data. Why? It’s quick to compare information, revealing highs and lows at a glance. Bar charts are especially effective when you have numerical data that splits nicely into different categories so you can quickly see trends within your data. They are best used to:

- show change over time
- compare different categories
- compare parts of a whole.

There are two types of simple bar charts:

### Vertical or column chart

This is the most common data visualization you will find and in a lot of cases the most effective at conveying information. This is the type we have seen so far where the bars are moving upwards or are vertical.

<img width="1920" height="1080" alt="28fbe2496f51b3700beb07c6c2b2d45d847dde57" src="https://github.com/user-attachments/assets/d6004576-8c24-4f52-a2bb-12efa0b1d5fc" />

### Horizontal bar chart

This is a bar chart where the bars are horizontal. See the image below. This data visualization is very similar to column charts in their use. The only difference is that a horizontal bar chart is better at displaying long category titles.

<img width="1920" height="1080" alt="baafc61fdfc6ad541610da8df2a7ae422cc5dd2f" src="https://github.com/user-attachments/assets/fc5b1244-d4bd-441c-a250-12e42a4c0b2f" />


## Clustered Bar Chart

A clustered bar chart displays multiple bars side by side within each category or group. Each cluster represents a different category, and the bars within each cluster represent different subcategories or data points. It:

- Is best used for comparing values across different categories or subcategories.
- Helps identify patterns or trends within the data.
- Allows observation of relative differences or similarities between the bars.
- Is particularly useful for visualizing segmented data with distinct groups or subgroups.

<img width="1920" height="1080" alt="bc158adbd72a87ecf8fe17d8cdd4a55925583d26" src="https://github.com/user-attachments/assets/f7a6f031-d398-43ac-a5bb-aba72958d23b" />

## Line Charts

Line charts are right up there with bars as one of the most frequently used chart types. Line charts connect individual numeric data points. The result is a simple, straightforward way to visualize a sequence of values.

When to use line charts: Viewing trends in data over time.

Examples: Stock price change over a year period, website page views during a month, revenue growth by quarter.

You can observe from the line chart below that has some of the chart elements described in the previous section.

<img width="1920" height="1080" alt="40ed62b1c724759ac11e99decb1a9673feb3396c" src="https://github.com/user-attachments/assets/b23d2311-dbdc-4c80-b170-5669487173e2" />

## Pie Charts

A pie chart is a circular graph that shows the relative contribution that different categories contribute to an overall total. They are generally used to show percentage or proportional data and usually, the percentage represented by each category is provided next to the corresponding slice of pie. The total of all the percentages shown in the pie chart should be 100. Pie charts are good for displaying data for around 6 categories or fewer. When there are more categories it is difficult for the eye to distinguish between the relative sizes of the different sectors and so the chart becomes difficult to interpret. Pie charts are most commonly misused. If you are trying to compare data, leave it to bar charts.

See below some images of a pie chart.

<img width="1920" height="1080" alt="40c5f393c20a4d0a51622e2aabf414c43205e36b" src="https://github.com/user-attachments/assets/235b5461-3bb1-4cf2-a087-6744401131db" />

If you are following the content closely, you will realise that pie charts break a few rules you learned about the basic structure of the chart. For starters:

- Pie charts have no vertical and horizontal axes and as such, they do not have vertical and horizontal titles. The only title you see on pie charts is the chart title.
- Again, because pie charts have no axes, they do not have axes labels. They do, however, have category/section/pie labels as seen from the above chart. “Sci-fi”, “Thrillers” and “Comedy” are category labels.
- Finally, each category has a data label as shown by the percentages in the above chart.

Sometimes, pie charts are also shown this way:

<img width="1920" height="1080" alt="ca62f1e2e7dbf78b75de36798dea1e1502e456cf" src="https://github.com/user-attachments/assets/22e90884-c9ac-4c2e-bfaa-e489a8c70f0b" />

In the image above, the sections of the pie only have the data labels on them while the section/category labels are shown as some sort of key on the side. This key is called the legend. The legend is helpful when each category/section/pie has a unique and differentiating colour.

That’s a lot of charts and graphs. The table below is a quick summary to help you choose the most appropriate type of chart to use in any given scenario.

<img width="772" height="270" alt="image" src="https://github.com/user-attachments/assets/9b717ae3-c119-4957-9583-85a7e0a94e9b" />

## Stacked Bar Chart

The stacked bar chart is great for adding another level of detail to a bar chart. You can do this by adding another dimension to your vertical bar chart that will further divide the measure into sub-groups. The sub-groups are then colour-coded on each bar as illustrated in the example below:

<img width="1920" height="1080" alt="2f74b71068b9477d4eac113b686699f38ec01431" src="https://github.com/user-attachments/assets/0bbb3de2-7cc6-4432-a05b-6cdd89f31ac2" />

The example above shows the number of Sales in dollars per Quarter with a further division of sales by Region (by adding the different Regions to the Colour shelf). This view is not ideal for comparing individual sales by region across each quarter, on the other hand, the view does allow you to compare overall sales per quarter and the sub-division of those sales by region. For instance, we can see that Q4 (the 4th quarter) is clearly the champion in sales amount. Within Q4, it is clear that the Americas brought in the most sales. Like every chart type, the effectiveness of a stacked bar chart depends on what you’re analysing.

**So, how do we create a stacked bar chart?**
Let’s watch [the following video](https://www.youtube.com/watch?v=pH0dx-7TDVE), done in Excel and note the steps as they are the same for Google Sheets.


## Clustered Bar Chart

displays more than one data series in clustered vertical columns. Each data series shares the same axis labels, so vertical bars are grouped by category. Clustered columns allow the direct comparison of multiple series, but they become visually complex quickly. They work best in situations where data points are limited.

<img width="1920" height="1080" alt="0633ed8c95e57094650380512baccb87ad2c240f" src="https://github.com/user-attachments/assets/18eaebf8-8b70-4685-b2b3-b274229bcdef" />

As you can see in the chart above, also known as a clustered chart, one can easily see how each region performs against each other in the various quarters. Additionally, it allows us to see how each region’s sales have changed during the year. Following are some the pros and cons of using this type of chart. Click through the interactives to learn more.

**Pros**
- Allow direct comparison of multiple data series per category
- Can show change over time

**Cons**
- More difficult to compare a single series across categories
- Become visually complex as categories or series are added

**Tips**
- Limit data series and categories
- Avoid all 3D variants

The side-by-side bar chart is just like the stacked bar chart except we’ve un-stacked them and put the bars side by side along the horizontal axis. In [this video](https://www.youtube.com/watch?v=dgsjIZKNfEU), you will see how to create a side-by-side chart (notice how at the end the instructor creates a unique type of stacked bar chart).

## Histogram

A histogram is a plot that lets you discover, and show, the underlying frequency distribution (shape) of a set of continuous data. This allows the inspection of the data for its underlying distribution (e.g., normal distribution), outliers, skewness, etc. An example of a histogram, and the raw data it was constructed from, is shown below.


<img width="1920" height="1080" alt="1df7e84fa59a5b9731510952ae5c48df175d5bdb" src="https://github.com/user-attachments/assets/571c028f-c1f1-4045-8161-26f1ed50aa75" />

Continuous data refers to data that can take any value within a given range. It can be measured with great precision and includes decimal or fractional values. Continuous data is essentially infinite and allows for a smooth and unbroken spectrum of possibilities. Examples of continuous data include height, weight, temperature, and distance.

How do you construct a histogram from a continuous variable?
Let’s use the below data to understand how to create a histogram.



36	25	38	46	55	68	72	55	36	38
67	45	22	48	91	46	52	61	58	55

To construct a histogram from a continuous variable you first need to split the data into intervals, called bins. In the example above, age has been split into bins, with each bin representing 15 years starting at 20 years. Each bin contains the number of occurrences of scores in the data set that are contained within that bin. For the above data set, the frequencies in each bin have been tabulated along with the scores that contributed to the frequency in each bin (see below):

Bin	Frequency	Scores Included in Bin
20-30	2	25, 22
30-40	4	36, 38, 36, 38
40-50	4	46, 45, 48, 46
50-60	5	55, 55, 52, 58, 55
60-70	3	68, 67, 61
70-80	1	72
80-90	0	-
90-100	1	91

Notice that, unlike a bar chart, there are no “gaps” between the bars (although some bars might be “absent” reflecting no frequencies). This is because a histogram represents a continuous data set, and as such, there are no gaps in the data (although you will have to decide whether you round up or round down scores on the boundaries of bins).

### Choosing the correct bin width

There is no right or wrong answer as to how wide a bin should be, but there are rules of thumb. You need to make sure that the bins are not too small or too large. Consider the histogram we produced earlier (see above), then look at the following histograms using the same data, but have either much smaller or larger bins, as shown below:

<img width="1920" height="1080" alt="7ac72aa54a3d8e843ecbbe78e1ffd3c132332f75" src="https://github.com/user-attachments/assets/d73f1a0e-b0c8-4336-a7e1-caebb1827292" />

<img width="1920" height="1080" alt="bf51966a9e885a5331dc20d4c1cc9a06e0b8673b" src="https://github.com/user-attachments/assets/96de138a-9179-45e5-a2cd-644a8dbca564" />

We can see from the histogram on the left that the bin width is too small because it shows too much individual data and does not allow the underlying pattern (frequency distribution) of the data to be easily seen. At the other end of the scale is the diagram on the right, where the bins are too large, and again, we are unable to find the underlying trend in the data.

Histograms are based on the area not the heights of bars
In a histogram, each bar’s size shows how many times something happened in a specific range. The height alone doesn’t tell the full story—it’s the combined height and width of the bar that gives the complete picture. Sometimes people think the height alone shows how often things occurred, but that’s only true when all the bars are the same width. If the bars have different widths, you need to look at both the height and the width to understand the frequency.

### What is the difference between a bar chart and a histogram?

The major difference is that a histogram is only used to plot the frequency of score occurrences in a continuous data set that has been divided into classes, called bins. Bar charts, on the other hand, can be used for a great deal of other types of variables including ordinal and nominal data sets.

[This is how to make and use a histogram chart on Excel or Google Sheets.](https://www.youtube.com/watch?v=is14ehdy7jo)


## Scatter Plot

The scatter plot, also known as a scatter diagram, scatter chart, scattergram, or scatter graph, is useful to compare two different measures for patterns. It is useful when showing relationships with various data points. The big difference with a scatter plot is that both axes in the chart are asures rather than dimensions.

In Figure 1 below, we’re examining the height and weight measurements of NBA players (Weight is on the x-axis and Height on the y-axis).

<img width="1600" height="900" alt="ENT100_6 11_Scatter Plot_V2" src="https://github.com/user-attachments/assets/9c7ffc95-5d9e-42c1-97f7-805b932c3d90" />

Just from a casual glance, we can see that height and weight are two closely related variables. There seems to be a trend where the more weight an NBA player has, then the taller they tend to be. Let’s change things up a bit and look at the height and weight of NBA players over the years. The results are shown in Figure 2 below:

<img width="1600" height="900" alt="ENT100_6 11_Multiple Line Graph_V3" src="https://github.com/user-attachments/assets/3b1a30f7-8b96-4536-9615-1ccde3fc227a" />

Over two decades, the weight and height of NBA players dropped. This scatter plot shows evidence of how the bodies of NBA players have changed over time. We can attribute this trend to basketball becoming a much faster, and more perimeter-oriented game, so it makes sense that players are getting leaner. [This](https://www.youtube.com/watch?v=ImswjwF35mE) is how you make a scatter plot

## Bubble Charts

Bubble charts or bubble graphs are extremely useful graphs for comparing the relationships between data objects in 3 numeric-data dimensions: the X-axis data, the Y-axis data, and data represented by the bubble size. Essentially, bubble charts are like XY scatter graphs except that each point on the scatter graph has an additional data value associated with it that is represented by the size of a circle or “bubble” centered around the XY point.

Bubble Chart Example 1: This chart shows the relationship between “Profit” (Y-Axis), “Cost” (X-Axis), and “Probability of Success (%)” (Bubble Size).

<img width="1600" height="900" alt="ENT100_6 11_Bubble Chart_V2" src="https://github.com/user-attachments/assets/8abcd606-64d6-48aa-a238-c9b8217fd4bb" />

The size of the red bubble is the smallest, detailing the least likely probability of success. The blue bubble shows the largest probability of success as the bubble is the largest.

Bubble Chart Example 2: The same as Example 1, but the bubble size variable has been removed so now it is displayed as a scatter chart.

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/f22cda31-9a42-4155-bafc-665849bb734f" />

### Bubble Charts in Business

Bubble charts are often used in business to visualize the relationships between projects or investment alternatives in dimensions such as cost, value, and risk. By visualizing project portfolios using bubble charts, you can find clusters of relatively attractive projects in one area of the graph, such as areas of high value, low cost, and/or low risk, and compare them with relatively less attractive projects in a different area of the graph, such as an area of low value, high cost, and/or high risk.


In the bubble chart examples above, the most desirable quadrant is in the upper left (higher profit and lower cost) and the least desirable quadrant is the lower right (high cost and lower profits). Bubbles with larger areas have higher probabilities of success.

Let’s watch [this video](https://www.youtube.com/watch?v=bUv_pEO9ZFc) to learn how to create a Bubble Chart.


## Improving Charts & Graphs: Labeling

Once you’ve built a draft of your chart, the next step in creating an impactful visualization is making sure all of its elements are labeled appropriately. The text components of a graph give your reader visual clues that help your data tell a story and should allow your graph to stand alone, outside of any supporting narrative.

Labeling Categories and Axes
It’s important to find a balance between giving enough information to your audience and keeping your text simple. Make sure you include enough information to explain the data you’re presenting while keeping the text simple enough so it doesn’t clutter the graph.

<img width="1200" height="1200" alt="image" src="https://github.com/user-attachments/assets/8d7dbc80-6644-4a3b-9c83-276e7190ae2f" />

In our Winter Olympic Games example, the horizontal axis shows the number of medals won by each country over the years. When creating a graph, it’s common to go through a couple of iterations of the axis labels and chart titles. Once you’ve picked an axis title, think about how your reader could interpret that information. An axis title of “Medals” seems straightforward enough, but what exactly do we mean? Medals won? Medals lost? Medals won in 2018 alone? Medals won in any Winter Olympic games? Your chart title can help clarify these questions, and your axis title also allows you to tell your story.

Instead of Medals, let’s title the horizontal axis with “Total Olympic Medals Won (1924 to 2018).” Using the word “total” ensures the reader knows you’re talking about all medals, not only one kind (gold, silver, or bronze) or from one event. “Olympic” ensures your reader knows that you’ve shared only the Olympic medals, not a total of Olympic and Paralympic medals. And finally, “1924-2018” reminds your reader of what years the medals were won. Alternately, as we’ve shown here, you can include some of those details in the chart title

## Improving Charts & Graphs: Units

When we refer to units, we’re talking about things like “percentages”, “dollars”, “millions”, or other descriptors that make sure your reader knows what kind of information you’re displaying. These are important if you’re sharing data that are in percentages instead of counts or if a multiplier has been used (for example, millions of dollars instead of just dollars).

<img width="684" height="487" alt="849940f9552a0e627da54b20a63b5ea5164395fa" src="https://github.com/user-attachments/assets/4f89976f-f8f1-44bc-ba98-326be27de638" />

It’s important to be clear in labelling your units. Some quick checks to walk through when you’re assessing your axis titles:

- Make sure you’re consistent if you’re displaying multiple types of data using a dual-axis graph: you don’t want to display two variables with one in months and a second in years on the same axis!
- Instead of using abbreviations or acronyms, write out the full unit (for example, millimetres instead of mm).
- Symbols can sometimes be a helpful alternative to words in text, but make sure to clearly state what a symbol represents. For example, you could use “$” instead of the word “dollar.” However, this symbol is used with the currency of more than 30 countries, so you should specify which country’s currency you mean (e.g. US$, A$, Mex$).

## Improving Charts & Graphs: Position and Format

Once you’ve built a draft of your chart, the next step in creating an impactful visualization is making sure all of its elements are labeled appropriately. The text components of a graph give your reader visual clues that help your data tell a story and should allow your graph to stand alone, outside of any supporting narrative.

Labeling Categories and Axes
Horizontal axis titles should be aligned parallel to the axis labels. Format them in a font size large enough to read, but not so large that it dominates the graph.

Vertical Axis Labels Debate

There’s some debate over whether or not vertical axis labels should be aligned parallel to the axis or not. On the one hand, aligning the text vertically makes it very clear that it’s directly associated with the vertical axis. There’s often more room to write the axis title text if it’s rotated at a 90-degree angle. On the other hand, humans are not very good at reading vertical text, and readers may find themselves squinting and turning their heads to understand the chart. If you have enough room and the axis title text is short, consider keeping the text level instead of rotating it.


We’ve also included two examples below that show what to avoid when placing your vertical axis titles.

<img width="1920" height="1920" alt="image" src="https://github.com/user-attachments/assets/99b70271-7407-4c21-9855-db39bfc78314" />

Individual category labels should be clearly marked too. Make sure any words and numbers are easy to read: your reader should not have to play contortionist games with his or her neck to get a good look at what you’re trying to share in your graph. A few tricks for formatting your axis labels:

Where possible, avoid rotating text on an angle, which is often used in vertical bar charts to force long text labels to fit but is difficult to read. If you find yourself with a horizontal axis using rotated, dense labels, try changing your chart type to a horizontal bar which will make the labels easier to read.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1f9c650e-6cdf-425d-8b23-44c72472b394" />

Simplify your labels. Even if your data were originally formatted with long strings of text for each category you’re trying to display, think about what you can simplify without losing meaning.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/9452a89f-5681-4bc3-ad87-c78371da756e" />

Use boldface text and italics sparingly and only where they have meaning. For example, you might use boldface for a category label for a data point you’re highlighting.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a6eb82bf-4bf9-4fc0-924c-7f8ce66e0ac2" />

## Improving Charts & Graphs: Titles

At last! Now comes the opportunity to tell your story in 1-2 lines of text using your chart title. The title should succinctly tell your reader what message this graph or chart has been designed to convey. It doesn’t have to be a complete sentence, but it should be free of complicated language and syntax.

Audience Consideration
It’s important to think about who your audience is and where your graph is going to be published when writing your chart title: are you a journalist adding the chart to an article, a blogger creating a very visual post, or perhaps a scientist going for a peer-reviewed publication? Scientists may need to clearly articulate the relationship displayed between their variables whereas a journalist may want to give some spin to the title to emphasize the message they want to share.


The most basic graph titles clearly state the relationship between the independent variable on the horizontal axis and the dependent variable on the vertical axis. For example, we called our medal count graph, “Countries With Most Medals at the Winter Olympic Games.” This title tells the reader that we’re looking at the total medals won (medal count) by country, limited to the top ten in the years between 1924 and 2018. Each element of the chart title we’ve created adds value and tells something to the reader. There’s nothing wrong with titles like these: while somewhat dry, they’re straightforward and clearly tell your reader what is on the graph.
You can also approach a title as an opportunity to state the conclusion your reader should draw from your graph. For example, if we had chosen to highlight the Russia medal count. If you want to highlight that Russia ranked second in the overall medal count, you could title the graph, “Russia ranks second for most medals won in the Winter Olympics Games.” Often you see these leading titles in newspapers and other publications telling a specific story. The chart title provides an extra opportunity to emphasize and amplify your message—use it!

## Manipulation of Charts

Now that you know how to use visualization as a tool to improve the analysis you have done, it is important to touch on an important aspect of data analysis.

Data analysis isn’t only about coming to an answer but coming to the right answer which is logically sound and ethically based. Ethics comes in, in how you use the data as well as how you present it. Some people manipulate and distort graphs knowingly and unknowingly. There are serious ramifications when people manipulate charts, from being legally sued to losing your business, to altering voters’ and people’s mindsets on various topics.


As ethical leaders of tomorrow, it is crucial to understand data manipulation to avoid making mistakes and recognize flaws in others’ work. Take a look at [this video](https://www.youtube.com/watch?v=x-rDVXVwW9s) with examples of misleading graphs and charts that have influenced public perception on various topics.
As you watch make note of:

- What is cherry-picking
- The use of cumulative data instead of annual data
- How pie charts and bar graphs can be used to misrepresent data.

 [here](https://www.youtube.com/watch?v=E91bGT9BjYk) is another eye-opener on how to spot misleading graphs. As you watch and listen to the examples, note the key things to look out for when looking at a graph.
