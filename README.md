# A_Study_on_Video_Games_Sales

### Project Overview

The aim of this project is to study different visualization methods, while analysing one particular video game sales dataset to get useful information required by a client, through further exploration of the concepts of visual representation, presentation, and interaction, using platforms such as Tableau and PowerBI.

### Data Sources

The dataset used in this project is named “vgsales” and can be described as a video games sales dataset. The different observations show a video game and its correspondent information details while presenting 11 columns and 16598 rows. The mentioned dataset can be accessed at https://www.kaggle.com/code/faisaljanjua0555/eda-video-games-sales.
The data dictionary shown below presents each variable along with its respective description and domain:

Name | Description | Domain |
--- | --- | --- | 
Rank | ordered ranking of the sales | Integer |
Name | Name of the game | Nominal |
Platform | Platform on which the game was released | Nominal |
Year | Year the game was released | Integer |
Genre | Genre of the game | Nominal |
Publisher | Publisher of the game | Nominal |
NA_Sales | Sales (in millions) of the game in North America | Float |
EU_Sales | Sales (in millions) of the game in Europe | Float |
JP_Sales | Sales (in millions) of the game in Japan | Float |
Other_Sales | Sales (in millions) of the game in the rest of the world | Float |
Global_Sales | Total sales all over the world | Float |

### Persona and Questions

The user is an investor who is looking for a game project to invest in, while studying the video games world, with the purpose of helping to develop and produce a new video game. The user is trying to find an answer to 3 simple and 1 complex question:

Simple questions:

* What are the publishers that have the highest profit in selling video games? (Q1)
* How do the sales of the most profitable platforms change for each region? (Q2)
* When comparing the “Action” and “Sports” genres, which one has shown more profit growth (genre trends)? (Q3)
  
Complex question:

* What is the publisher that has the highest profit in selling video games of the most popular genre between the years 2000 and 2020? (Q4)

### User Requirements

1. To answer the previous questions, user requirements that show what the user needs to visualize are defined below:
  * A good view would be a bar plot that shows the value of the global sales for the publishers that present the highest values.
  * A filter could also be used to select just the top 10 publishers.
  * The user can highlight the most profitable publisher by creating a new calculated field.
2. To answer Q2 the user needs to visualize the nominal comparison relationship between “Platform” and the measure variables “NA_Sales”, “EU_Sales”, “JP_Sales”, and “Other_Sales”, while comparing its values.
  * A good view would be a clustered bar chart so that the user can easily see how the profit of each platform varies in each region.
  * The user could use a platform filter, according to global sales, to only visualize a certain number of the top profitable platforms.
3. To answer Q3 the user needs to visualize the time series relationship between “Year” and “Global_sales" variables.
  * A good view would be a scatter plot with “Global_sales" on the y-axis and “Year” on the x-axis.
  * A genre colour mark can be useful to distinguish each of the genre categories by assigning different colours to their curves.
  * To be able to visualize different genre curves throughout the years, a genre filter could be used, as it will show each genre curve of sales while giving the user the option to choose which genre(s) to     visualize and or compare in the plot.
  * The option to show trend lines should be activated, so the user can easily see and compare different genre trends.
  * A new filter could be used to visualize the curve/trend of these genre categories in a specific year range.
4. To answer Q4 the user must use the view created when answering Q1 while observing what the most popular genre is and its correspondent top publisher.
  * The user needs to create a new view that displays the most popular genres. A treemap to plot the “Genre” with “Names” variables could be used to see the frequency for each genre (how many games belong to each genre).
  * These views should be loaded in a dashboard.
  * The filter widgets must be applied to all worksheets.
  * It is essential that the user interacts with the genre treemap, while also visualizing the top publishers’ bar plot (view that answers Q1).
  * The user must also interact with the year filter, to select the appropriate year range to answer the question.

### Design

The following design shows the final solution achieved using the Tableau software, based on the first draft previously presented.

<img src="https://github.com/user-attachments/assets/477fc211-a290-4c8f-8453-2aa270c4600a" alt="Tableau Dashboard" width="500"/>





