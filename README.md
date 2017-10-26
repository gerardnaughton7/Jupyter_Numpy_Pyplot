# Jupyter_Numpy_Pyplot
Problem sheet. Where we will use Jupyter Numpy and pyplot to display Iris data set.

# Our objectives for this Problem sheet were:

Problem set: Jupyter, pyplot and numpy

These problems relate to Jupyter, numpy, and pyplot. We will use the famous iris data set. Save your work as a single Jupyter notebook file in a GitHub repository. Include any required data files, a README, and a gitignore file in the repository.

1. Get and load the data

Search online for Fisher’s iris data set, find a copy of the data, download it and save it to your repository. If it is not in CSV format, use whatever means (Excel, notepad++, visual studio code, python) to convert it to CSV and save the CSV version to your repository also. Open your Jupyter notebook for this problem sheet, creating a new one if needed, and load the CSV file into a numpy array.

2. Write a note about the data set

In a markdown cell at the start of your notebook, write a short description of the iris data set, complete with references.

3. Create a simple plot

The dataset contains five variables: sepal length, sepal width, petal length, petal width, and species. Use pyplot to create a scatter plot of sepal length on the x-axis versus sepal width on the y-axis. Add axis labels and a title to the plot.

4. Create a more complex plot

Re-create the above plot, but this time plot the setosa data points in red, the versicolor data point in green, and the virginica data points in blue. Setosa, versicolor, and virginica are the three possible values of the species variable. Add a legend to the plot showing which species is in which colour.

5. Use seaborn

Use the seaborn library to create a scatterplot matrix of all five variables.

6. Fit a line

Fit a straight line to the variables petal length and petal width for the whole data set. Plot the data points in a scatter plot with the best fit line shown.

7. Calculate the R-squared value

Calculate the R-squared value for your line above.

8. Fit another line

Use numpy to select only the data points where species is setosa. Fit a straight line to the variables petal length and petal width. Plot the data points in a scatter plot with the best fit line shown.

9. Calculate the R-squared value

Calculate the R-squared value for your line above.

10. Use gradient descent

Use gradient descent to approximate the best fit line for the petal length and petal width setosa values. Compare the outputs to your calculations above.

## In my Jupyter Notebook you able to view the solutions for these questions

# How to use my solution on Jupyter NoteBook 

1. Firstly download anaconda in order to code in python. You can download anaconda through this link and following their instructions: https://www.anaconda.com/download/

2. Download my repository to your computer using clone or download methods

3. When you downloaded anaconda you will have recieved a anaconda terminal called anaconda prompt. if you search on your computer it should pop up. Once open navigate to your repository where my download is. 

4. Once in the directory type the command "Jupyter Notebook". This shall open a browser displaying your Jupyter notebook folder. Then just click on IrisDataSet.ipynb and the solutions should be there. With Jupyter notebook you will be able to manipulate the data and change the code.

5. Alternatively if you just want to click on my IrisDataSet.ipynb on my github repository it will bring us to a non editable version. But here you can view the code and the data.
