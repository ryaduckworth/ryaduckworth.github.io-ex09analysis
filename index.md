---
# Do not edit the text between these lines!
layout: default
---




# Rya and Camrie's Analysis 

## Our Inquiry
Our idea was that the course should upload detailed video explanations of Comp 110 concepts because it will further elaborate difficult material for students in the class.
We planned to support this idea through analysis of difficulty, student majors, and student interest in the class concepts. 

## Coding Summary
We began by loading the survey data using read_csv_rows and converting it into a columnar format, then used head to verify the data structure.
We then selected the columns related to student interest and the difficulty of material to see if there was a correlation that suggested a need for more video resources. We also used our custom filter_by_threshold function to focus on students who find the material challenging (difficulty score of 5 or higher).
We then used count to see the distribution of difficulty scores across the class to determine how many students might benefit from extra video explanations.
Then, we created visualizations using the data from the survey (difficulty, major, and interesting columns) to see if there was a correlation between the variables. 

## Analysis Visualizations
<img src="/static/imgs/bar_graph.png" alt="Image of Bar Graph of Difficulty Distribution" width="500"/>

*Figure 1: This bar graph shows the distribution of difficulty ratings across the class.*

<img src="/static/imgs/box_plot.png" alt="Image of Box Plot Comparing Difficulty to Major" width="500"/>

*Figure 2: This box plot compares student difficulty ratings across different majors.*

<img src="/static/imgs/heatmap.png" alt="Image of Heatmap Comparing Difficulty to Interest" width="500"/>

*Figure 3: This heatmap shows the correlation between student interest levels and course difficulty.*

## Conclusion
Based on our analysis, we recommend the implementation of detailed video explanations. 

Our analysis focused on students who found the material challenging, as indicated by a difficulty rating of 5 or higher. 
    The count plot found that most students (151) rated the class difficulty a 5 out of 7
    The box plot comparing difficulty to major found that even though most majors found this course challenging, non-stem majors had a more difficult time on average. 
    The heatmap comparing interest level and difficulty found that students who were interested in the topics were less challenged than those who were not as interested in the course material. 

To refine this idea, we could also compare difficulty to previous experience with coding. Moreover, the videos themselves can include knowledge checks to ensure students are retaining the information presented in the videos.

Potential costs of this idea include more time committment for professors and TAs. If knowledge checks are implemented, then videos could be seen as less of a study tool and more as an assignment. Due to videos being posted online, student attendance in lecture might decrease.

