# Data-Visualization

What is Data Visualization?
Data visualization is a field in data analysis that deals with visual representation of data. It graphically plots data and is an effective way to communicate inferences from data.
Using data visualization, we can get a visual summary of our data. With pictures, maps and graphs, the human mind has an easier time processing and understanding any given data. Data visualization plays a significant role in the representation of both small and large data sets, but it is especially useful when we have large data sets, in which it is impossible to see all of our data, let alone process and understand it manually.

Data Visualization in Python:
Python offers several plotting libraries, namely Matplotlib, Seaborn and many other such data visualization packages with different features for creating informative, customized, and appealing plots to present data in the most simple and effective way.
Python provides various libraries that come with different features for visualizing data. All these libraries come with different features and can support various types of graphs. In this tutorial, we will be discussing four such libraries.

•	Matplotlib
•	Seaborn
•	Bokeh
•	Plotly

1. Matplotlib
Matplotlib is an easy-to-use, low-level data visualization library that is built on NumPy arrays. It consists of various plots like scatter plot, line plot, histogram, etc. Matplotlib provides a lot of flexibility

After installing Matplotlib, let’s see the most commonly used plots using this library.

a. Scatter Plot:
Scatter plots are used to observe relationship between variables and uses dots to represent the relationship between them. The scatter() method in the matplotlib library is used to draw a scatter plot. Scatter plots are widely used to represent relation among variables and how change in one affects the other. 

b. Line Chart:
Line Chart is used to represent a relationship between two data X and Y on a different axis. It is plotted using the plot() function.

c. Bar Chart:
A bar plot or bar chart is a graph that represents the category of data with rectangular bars with lengths and heights that is proportional to the values which they represent. The bar plots can be plotted horizontally or vertically. A bar chart describes the comparisons between the discrete categories. One of the axis of the plot represents the specific categories being compared, while the other axis represents the measured values corresponding to those categories.

d. Histogram:
A histogram is basically used to represent data in the form of some groups. It is a type of bar plot where the X-axis represents the bin ranges while the Y-axis gives information about frequency. The hist() function is used to compute and create a histogram. In histogram, if we pass categorical data then it will automatically compute the frequency of that data i.e. how often each value occurred.

e. Pie Chart:
A Pie Chart is a circular statistical plot that can display only one series of data. The area of the chart is the total percentage of the given data. The area of slices of the pie represents the percentage of the parts of the data. The slices of pie are called wedges. The area of the wedge is determined by the length of the arc of the wedge. It can be created using the pie() method.

f. 3D Plots:
Matplotlib was introduced keeping in mind, only two-dimensional plotting. But at the time when the release of 1.0 occurred, the 3D utilities were developed upon the 2D and thus, we have a 3D implementation of data available today.


2. Seaborn:
Seaborn is an amazing visualization library for statistical graphics plotting in Python. It provides beautiful default styles and color palettes to make statistical plots more attractive. It is built on the top of matplotlib library and also closely integrated into the data structures from pandas. 
Seaborn is built on the top of Matplotlib, therefore it can be used with the Matplotlib as well. Using both Matplotlib and Seaborn together is a very simple process. We just have to invoke the Seaborn Plotting function as normal, and then we can use Matplotlib’s customization function.

a. Scatter Plot:
Scatter plot is plotted using the scatterplot () method. This is similar to Matplotlib, but additional argument data is required.
Scatterplot can be used with several semantic groupings which can help to understand well in a graph. They can plot two-dimensional graphics that can be enhanced by mapping up to three additional variables while using the semantics of hue, size, and style parameters. All the parameter control visual semantic which are used to identify the different subsets. Using redundant semantics can be helpful for making graphics more accessible.

b. Line Plot:
Draw a line plot with the possibility of several semantic groupings. The relationship between x and y can be shown for different subsets of the data using the hue, size, and style parameters. These parameters control what visual semantics are used to identify the different subsets. It is possible to show up to three dimensions independently by using all three semantic types, but this style of plot can be hard to interpret and is often ineffective. Using redundant semantics (i.e., both hue and style for the same variable) can be helpful for making graphics more accessible.

c. Bar Plot:
Bar Plot in Seaborn can be created using the barplot() method. seaborn.barplot() method is used to draw a barplot. A bar plot represents an estimate of central tendency for a numeric variable with the height of each rectangle and provides some indication of the uncertainty around that estimate using error bars.

d. Histogram:
The histogram in Seaborn can be plotted using the histplot() function. After going through all these plots, you must have noticed that customizing plots using Seaborn is a lot more easier than using Matplotlib. And it is also built over matplotlib then we can also use matplotlib functions while using Seaborn.

e. Box Plot:
A boxplot is sometimes known as the box and whisker plot. It shows the distribution of the quantitative data that represents the comparisons between variables. boxplot shows the quartiles of the dataset while the whiskers extend to show the rest of the distribution i.e., the dots indicating the presence of outliers. It is created using the boxplot () method.

f. Violinplot:
It is similar to the boxplot except that it provides a higher, more advanced visualization and uses the kernel density estimation to give a better description about the data distribution. It is created using the violinplot () method.

g. Stripplot:
It basically creates a scatter plot based on the category. It is created using the stripplot() method.

h. Distribution Plots:
Distribution Plots are used for examining univariate and bivariate distributions meaning such distributions that involve one variable or two discrete variables.
we will be discussing 4 types of distribution plots namely:

• Distplot • Joinplot • Pairplot • Regplot

3. Bokeh:
Python Bokeh is a Data Visualization library that provides interactive charts and plots. Bokeh renders its plots using HTML and JavaScript that uses modern web browsers for presenting elegant, concise construction of novel graphics with high-level interactivity. 

Features of Bokeh:
•	Flexibility: Bokeh can be used for common plotting requirements and for custom and complex use-cases.
•	Productivity: Its interaction with other popular Pydata tools (such as Pandas and Jupyter notebook) is very easy.
•	Interactivity: It creates interactive plots that change with the user interaction.
•	Powerful: Generation of visualizations for specialized use-cases can be done by adding JavaScript.
•	Shareable: Visual data are shareable. They can also be rendered in Jupyter notebooks.
•	Open source: Bokeh is an open-source project.


4. Plotly:
Plotly is a Python library which is used to design graphs, especially interactive graphs. It can plot various graphs and charts like histogram, barplot, boxplot, spreadplot and many more. It is mainly used in data analysis as well as financial analysis. Plotly is an interactive visualization library. Here’s why –
•	Plotly has hover tool capabilities that allow us to detect any outliers or anomalies in numerous data points.
•	It allows more customization.
•	It makes the graph visually more attractive.
