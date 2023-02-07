# EDA-on-global-terrorism
This project is based on the database maintained by researchers at the National Consortium for the Study of Terrorism and Response to Terrorism(START)

**INTRODUCTION**

![terrorism pics](https://user-images.githubusercontent.com/121782863/217160979-19f8978f-9eb4-4126-a033-f2f3498fc1e4.jpg)

Impact of global terrorism is increasing across different years due to violent extremism and many other reasons. We decided to took this project due to our mutual interest in analyzing global terrorism and the reasons behind it. Using 14 different analysis we were able to complete our task with the help of interactive and understandable visualisation using different types of libraries such as plotly,numpy,pandas,matplotlib etc. The Global Terrorism Database(GTD) is an open-source database which contains information of 181691 rows and 135 columns. While checking our dataset, analyzing columns and their values were challenging but through certain data wrangling operations i was able to convert our dataset to our own requirement. Graphs we plot on the each analysis were simple and by utilizing more libraries in python we made the graphs more interactive.

**PROBLEM STATEMENT**

The GTD includes systematic data on domestic as well as international terrorist incidents that have occured during this period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Response to Terrorism(START), headquartered at the University of Maryland. In this project we have explored and analysed the data and the findings has been visualized using graphs.

**DATASET INFORMATION**

Our dataset on global terrorism was a big csv file. By analyzing the dataset we came up with an idea to reduce our dataset to our own requirement. Because as we understood there are 135 columns which includes value missing columns and some columns with no data. We grabbed some required columns from our original dataset and created a new dataset with 16 unique columns which contains data based on year, day, region, country ,groups, target etc.. This helps us to analyze dataset more easily rather than taking the entire dataset on hand. Data wrangling operations such as .loc method, .rename method  helps us to clean the dataset and to create a new dataset. This also helps us to plot the graph more effectively using the variables.

Dataset : csv file for Global Terrorism Analysis

**ANALYTICS/GRAPHS USED**

After creating 14 different analysis/questions from our dataset. Our next task was to extract code for each questions. Through some pandas operations such as groupby and concantinating we were able to make the code much simpler and understandable. For graph plotting we used plotly, matplolib.pyplot, seaborn libraries. For showing overall trend we used simple line graphs with the help of matplotlib.pyplot and for making the graphs more interactive we used plotly and seaborn libraries. Plotly and seaborn libraries helps to identify the exact count of each variable with respect to another variable.Stacked bar graph is used when we had multiple data to be plotted in the same bar. By using the explode function in pie chart the visualization were made better by taking the part of the whole pie highlighted.

some of the graphs used

**Line graph using matplotlib.pyplot**

![Screenshot (44)](https://user-images.githubusercontent.com/121782863/217161329-b01dda06-d00a-4c84-a991-4bbe9333faba.png)

**stacked bar graph**

![Screenshot (43)](https://user-images.githubusercontent.com/121782863/217161465-c6d55012-ca69-4abd-809a-d0a52047f5fb.png)

**Bar graph using plotly**

![Screenshot (40)](https://user-images.githubusercontent.com/121782863/217161592-bf936237-c97b-462c-a5fa-66853ab0d384.png)

**pie chart**

![Screenshot (45)](https://user-images.githubusercontent.com/121782863/217161905-a6be3333-c2eb-46cb-a22d-7e65070ea552.png)



