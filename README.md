# Covid-Vaccination-Analysis
Tools Used: Pandas, Matplotlib, Scipy

The above mentioned tools are used to analyse a Covid vaccination data set and do statistical analysis based on state wise, no of people vaccinated and no of people who need to be vaccinated.

# Getting the data:
* We are using pandas read_excel method for reading the excel file.
* Pandas will create a dataframe we will store that dataframe in data varirable.
* We are using pandas head method for displaying top 5 row of that dataframe.

# Modifiying the Data For Our Use:
* We are going to visualize the probability concepts like Normal Distribution, Three Sigma rule, z-index.
* We are going to do those things in the percentage of people vaccinated data.
* But in our dataset we don't have percentage of people vaccinated data, so we need to Calutate it from the existing dataset.
* We can calculate the percentage of people vaccinated by dividing number of people taken the first dose by total population of the state.
* Pandas made it very easy,we can just divide the two divide two dataframe to get that.

# Normal Distribution:
* First we are getting mean and Standard deveation from the percentage data using pandas describe function.
* Then We are using matplotlib plot function to plot of the curve.
* We are giving sorted list of the percentage Data as X Axis.
* Y-Axis is the is probability Density function from Scipy.
* Then we are using `matplotlib' show function to show the results.

# Three Sigma Rule:
* We can Calculate it using the scipy cumulative distribution function cdf.
* We can print the % of our calculations fall in between one standard deviation Distance ,two and three respectively.

# Z-index:
* In the Python We don't need that Table scipy provide that in the form of cdf cumulative probability function.
* We can just pass the value of Z and find the cumulative probablity.
