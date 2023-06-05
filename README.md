         #                           PROJECT NAME: IMO-EXAM-SCORE PROJECT

##                                           Aim of this project
In this project we try to understand whether there is any type of relationship between the numbers the student scores and year as well as hours of study by using different plots. Different plots like bar graphg, line graph, dor plot, pie chart, Donut chart, histogram is used here to make conclusions.


### **This project is completely done on basis of a data set that contain different scores of students in IMO examnination over past years.** 

### In the begining of the project we have to undertsand the data set provided in the page in comma separated value or popularly knows as '.csv file'. Here are some specifications of the data set--
* The data set contains 15 observations
* Along 12 variables
* The data set contains only numerical values
* There are no string objects in the data set

## **Starting of the project and explanation of each step**

### 1. Importing required packages:
Here first we import different packages sucg as **Matplotlib.pyplot**, **Numpy**, **Pandas**. On top of that we also use the **style module** of matplotlib and the **inline module** to make the plots more attractive.

### 2. Getting the required data:
Here we get the data from the google drive. To attach the Google colab and google drive we import drive from google colab and merge the file named **'IMO_EXAM-SCORE.csv'** as data using read_csv() function of Pandas library.

### 3. Checking the data:
The next step is the most general step involved in analysis of the data set. It is called previewing the data. In this step we can check the whole data set, check number of columns, number of rows etc. 

### 4. Starting of analysis:
In this step we start our analysis by storing the variable names in short variables names to avoid misprint or other mistakes. It is a good practice to save time and spend the saved time in other type of analysis.

### 5. Checking trend in different subjects over years:
We know to check trend or change of a object with respect to another variable can be easily interpreted using line chart. So in this case we use line charts to:
* Track changes in Maths and Physics Scores over years.
* Track changes in Chemistry and Biology Scores over years.
* Track changes in Computer Score over years.
* Tracking all subject scores in a single plot.
* Understanding the trend in total marks scored over years.
* Observing trend in the hours of study per year.

### 6. Checking relationship between continuous variables:
We know relationship between continuous variables can be easily interpreted by the dot plot popularly known as scatter plot. Using this we try to estimate the received numbers of:
* Maths versus Physics Score.
* Maths versus Chemistry Score.
* Maths versus Computer Score.
* Maths versus Biology Score.
* Each plot makes a different pattern.

### 7. Data Preparation step:
Here we perform **data preparation** step by **filtering** the data we needed from the data set. As the data set is not so long, we can easily observe the data set and can know that in 2017 the scores in all subjects were the heights. So in order to filter the observations of 2017, we use the row index which is 7 in this case along with the **.loc** method which stands for label based attribute.

### 8. Checking contribution of different subject scores in 2017:
To check the contribution we generally think what percentage of area is grabed by a specific thing, considering the whole area as **100%**. In such case **Pie Charts** and **Donut Charts** are very useful as using them we can easily show the percentage contribution of subjects in total score.

### 9. To check the distribution of Maths Score:
Using Histogram we can visualize the frequency in which the student gets a variety of numbers. From this plot we can conclude that the student:
* Gets 100 once
* Above 95 and below 100 7 times and so on.

### 10. Plotting histogram and density plot:
Using Histogram we can say the frequency of the Math Score. But using Density plot will help us in which year the number in Maths score are denced near a point. It looks like a line plot and it always ranges from 0 to 1.

### 11. Plotting a horizontal Bar chart:
Here using horizontal bar chart I plot distribution of marks over years. To plot a horizontal bar chart **plt.barh()** function is used which comes under the matplotlib.pyploy library.

