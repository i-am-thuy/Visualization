# Visualization 

There are many useful tools in Python that can help analysts see trends and patterns in datasets, and I am no exception. Recently, I have been looking into Matplotlib and Seaborn - two of Python's best data visualization libraries. They support me in exploring the important features, and graphically depicting the data (Descriptive statistics). Specially, I can look at the boxplots to detect outliers from which to find the optimal ways in pre-processing data.
Thanks to the common TITANIC datasets - the likelihood of survival on the Titanic, I used the knowledge of these packages to begin to really practice on this real data.

From my perspective, an important aspect of the data scientist is to interpret their findings to those who may not be experts in the technical fields they specialize in. Graphics are the most powerful tool to achieve that goal, and mastering visualization techniques thus seems important. As always, I begin by setting up the coding environment by importing libraries such as pandas, numpy, matplotlib, and seaborn. Then select an available dataset from the US Department of Transportation that tracks flight delays.To load data, I used the pd.read_csv command and examined the data. I want to create a bar chart showing the average arrival delay for Spirit Airlines (airline code: NK) flights by month. I also created a heatmap to quickly visualize patterns in flight data. Each cell is color-coded according to its corresponding value.


