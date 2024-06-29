#TASK1:
1]task1-variable:studied the rule of variable declarion in python.
2]task1-operators:studied various operator in python namely Arithmatic,Assignment,logical,identity,comparison,Bitwise,membership etc.
3]task1-list:studied the data type list and its method like append remove insert pop sort count accessing,copy reverse and its properties.
4]task1-tuples:studied how to declare tuple its method like count index etc.
5]task1-set:set declaration,properties like mutable,ordered,etc
6]task1-dictionary:declaratin of dict,methods like copy index pop and use of for loop for accessing
7]task1-string:declaration and use of functions like upper lower split strip replace etc.
8]task1-number:substeps like int float and complex,its method

#TASK2:
1]task2 if stmt:-use of if statement to check a single condition in various example like to check whether a number is positive negative,even odd etc.
2]task2 if else stmt:-used to check two condition in example like checking a number is even or odd,greater or smaller,negative or positive and other similar examples.
3]task2 if elif else:-to test multiple condition at a time if the above condition false then the next one to it is tested.studied examples like to ckeck whether number is positive negative or zero and other ssimilar examples.
4]task2 for loop:used for accessing the elements in a list tuple and its method.
5]task2 while loop:use of while loop to print a sequence of number print

#Task3:
In task3 we studied the break,pass,continue statement also we studies user defined functions like statistical(mean,median,mode,etc.)and logical(odd,even,grades)#break-functionality when break is encounted insided loop,the loop stops its execution and control is transferred to the statement immediately following the loop.use case:it is useful when you want to exist a loop as soon as certain condition is met,avoiden unnecessary iterations.#continue functionality:when continue is encounted, the current iteration is terminated,and the loop processed with the next iteration.use case:it is useful when you want to skip over some parts of the loop but continue with the nextiterations for instance,you might want to skip over even numbers or any specific condition  within a loop.#pass functionality:The pass statement does nothing and is used as placeholder.use case it is useful when statement is synthetically required,but you do not want any action to be taken commonly used during development as placeholder for future code,in empty function or class definition ,or within condional statement where you plan to add code later.#statistical user defined function-statistical functions are essential for data analysis and help summarizes and understand the data's property .mean is used to calculate average of list of numbers .median is used to find the middle value of alist numbers .mode is used to find the most frequently occuring values in list numbers variance is used to measures spread of numbers in a list from the mean. standard deviation is used to measure the amount of variation or dispersion of set values.percentile is used to determine the value below which a given percentage of observations fall range is used to calculate the difference between the maximum and minimum values in a list interquartile Range(IQR) is used to measure middle 50% of the data.covariance is used to measure how to variable change together.correlation coefficient used to measure the strenth and direction of the relationship between two variable.#logical user defined: 
is even purpose:check if a number is even.#is odd purpose check if no. is odd.#check palindrome purpose etc.

Task 4 -
#In task 4 we studied all about Numpy library.Starting with a basic introduction and ends up with creating and plotting random data sets,
and working with NumPy functions:
#NumPy is an open source project that enables numerical computing with Python. It was created in 2005 building on the early work of the Numeric and Numarray libraries.
NumPy will always be 100% open source software and free for all to use.
We studied  1) creating arrays, 2)array indexing ,3) slicing, 4)numpy data types ,5) copy or view, 6)array shape and reshape ,7)array itterating , 8)join , split, search , sort and filter .
Here 1D array , 2D array,3D array and multidimensional array are studied.
NumPy has some extra data types, and refer to data types with one character, like i for integers, u for unsigned integers etc.
Below is a list of all data types in NumPy and the characters used to represent them.
1)i - integer 
2)b - boolean
3)u - unsigned integer
4)f - float
5)c - complex float
6)m - timedelta
7)M - datetime
8)O - object
9)S - string
10)U - unicode string
11)V - fixed chunk of memory for other type ( void ) 
#Then we learn how to  generate Random Number.
NumPy offers the random module to work with random numbers.
#Data Distribution is a list of all possible values, and how often each value occurs.
Such lists are important when working with statistics and data science.
The random module offer methods that returns randomly generated data distributions. 
Then we see that generation of random numbers from particular distribution and visuallisation of that distribution .like normal distribution ,binomial, poisson , uniform, logistic, multinomial, exonential, chi-square,rayleighs,pareto,zipf distributions
To plot the graph of distribution
#from numpy import random
#import matplotlib.pyplot as plt
#import seaborn as sns
Then we use ufuncs stands for "Universal Functions" and they are NumPy functions that operate on the ndarray object.
We studied ufunctions like simple arithmatic , rounding decimals, logs, summations, products, differences, finding lcm,gcd, trignometric functions, hyperbolic function and set operations.

Task 5 -
In task 5 we studied the pandas library in python.
#we see creation of series and their operation .A Pandas Series is like a column in a table. It is a one-dimensional array holding data of any type.
#Then we see the data frame creation using dictionary and matrix ,and how to to read data in csv and xlsx file in panda library in python. 
#Data frame operation -
In data frame operation different methods of operation like value count , apply, unique, nunique,describe,merge,sort etc
#selection-
In selection we see that how to select data frame column and row by using (loc,iloc) function . 
#In pandas, selecting data from a DataFrame involves specifying which columns and/or rows you want to work with. 
#we can use several methods for selection, including .loc, .iloc, and boolean indexing. 
 Also conditional selection with how to add , delete and update column in the data frame .Also seen that indexing and removing indexing by set reset function.
 Operation between two columns like addition , substraction, multiplication and division are carried out .
#missing values
In missing values we studied checking missing values, how to drop missing values by row and by column and also filling missing values by mean ,median etc.By using function
#Using isnull(): This method returns a DataFrame of the same shape with boolean values indicating whether the data is missing (True) or not (False).
#we can drop rows that contain any missing values using dropna(axis=0):
#we can fill missing values with a specific value using fillna(value):

Task 6 - 
 In task 6 we studied the matplotlib and seaborn library.
 Matplotlib is a graph plotting library in python that serves as a visualization utility.
 #Pyplot
Most of the Matplotlib utilities lies under the pyplot submodule, and are usually imported under the plt alias:
#import matplotlib.pyplot as plt
#Plotting x and y points
The plot() function is used to draw points (markers) in a diagram.
In matplotlib we study matplotlib plotting with markers,lines,labels,grid,subplot,scatter plot,bars, histograms and pie charts .
#seaborn libraray-
Seaborn is a powerful and versatile data visualization library in Python, built on top of the popular Matplotlib library. 
It provides a high-level interface for drawing attractive and informative statistical graphics. 
Seaborn is particularly useful for visualizing complex datasets and for creating aesthetically pleasing visualizations with minimal code.
#import seaborn as sns
#In seaborn library we see different types of plotting of graphs such as distribution plot, box plot, violin plot, bar plot,scatter pot, 
line plot, heatmap, pair plot ,facet grid, regression plot , residual plot. 

Task 7-
#1] Numpy exercise:- solved problems related to array indexing slicing,creating arrays containg zeros ones generating random numbers from normal distribution,
using linspace addition of elements in an array calculate mean standard deviation, etc
#2]Ecommerce purchase exercise:- studied the how to read the file and found out the mean purchase price maximum and minimum purchase price,number of people having job title lawyer number of people making the purchase during the AM and how many people made the purchase during PM,5 most common Job Titles,person with the following Credit Card Number: 4926535242672853 ,number of people have American Express as their Credit Card Provider and made a purchase above $95,number of people have a credit card that expires in 2025,top 5 most popular email providers/hosts (e.g. gmail.com, yahoo.com, etc...)
#3] Salary exercise:-studied the data read the file and found out average BasePay,the highest amount of OvertimePay in the dataset,job title of JOSEPH DRISCOLL, How much does JOSEPH DRISCOLL make,name of highest paid person,name of lowest paid person,the average (mean) BasePay of all employees per year,number of unique job titles,the top 5 most common jobs,number of  Job Titles were represented by only one person in 2013, people have the word Chief in their job title,there a correlation between length of the Job Title string and Salary.

#Case study -
In this case study we download the titanic data from kaggle and import it to jupyter notebook.Then we find the missing values and filled the missing values by its mean ,and droped the variable like cabin,passenger id etc. Then we do label encoding for the categorical variable.
Then Performd the EDA i.e exploratory data analysis on titanic data such as bar plot,scatter plot,joint plot and pie chart .
From the graph it is seen that the females are survived more than males.The passengers who are in class 1st are most survived as compared to class 2nd and 3rd.
In titanic data survival is the dependent variable and other variables like age,sex,fare,sibps,embarked are independent variables.
Then we split data into train test and fit the algorithms like naive bayes,KNN, dicision tree and predict the text data using particular fitted model.
In model evaluation we find accuracy,classification report,confusion matrix,precision and recall for each algorithm .and compare it with each other and we may conclude that 
decision tree is the best model on the basis of prcision , accuracy and recall, Where the values of precision,accuracy and recall for dicision tree are high as compared to knn and naive bayes.

#Dashboard-
In this task we created a dashoard on project data i.e Airlines Delay classification in power bi dashboard.We download the airlines delay classification data from kaggle. In power bi we get the data from csv file then by using graphs ,sclicers,card and other features we create a dashoard in power bi.




