# PISA Data 2012

This was the fifth and last project of Udacity's Data Analyst Nanodegree.

## Dataset

PISA is a survey that examines students from compulsory education on how well prepared they are for life after school. This investigation focuses on the PISA Survey from 2012, with data belonging to around 500K students from 65 different countries.

The file provided by Udacity for this dataset contained data from a total of 485'490 students, grouped in 636 columns.
The dataset contains not only the results from the exam in each category, but also lots of information on the students' background, including variables like country of residence, number of family members and their level of education, possessions or access to different facilities at home and at school.

The main feature of this dataset is the score obtained by the students in each discipline and the potential for understanding how a number of different background factors can impact these scores and therefore the level of preparation for students around the world.

Analyzing such a complex dataset entirely requires a lot of time. For this project, I simplify the dataset by keeping only the following selection of background variables:

- Student's country of residence.
- Student's country economic level (OECD or not).
- Student's gender.
- Student's parents' level of education.
- Access to internet at school and at home.

In addition to these independent variables I keep the results for the three main disciplines: mathematics, reading and science.

## Summary of Findings

The exploratory analysis provided the following findings:

1. The 3 score variables follow a clear normal distribution, ranging from 200 to 800 points each.

![Score distribution](/images/fig01.jpg)

2. Not all countries are equally represented in the survey. While many of the 65 countries in the dataset have a similar number of entries (between 0.9 and 1.5% of the survey population each), about 15 of them go significantly above or below these values.

![Score distribution](/images/fig03.jpg)

3. The 3 score variables show a linear correlation. This correlation is slightly weaker between math and reading scores adn stronger between math and science scores.

![Score distribution](/images/fig08.jpg)

4. No clear relationship is found between student's gender and their scores, with the exception of reading, where female students seem to perform better than male students.

![Score distribution](/images/fig09.jpg)

5. Students from OECD countries present better results in the exams.

![Score distribution](/images/fig12.jpg)

6. Students' whose parents have a higher level of education also obtain better scores.

![Score distribution](/images/fig14.jpg)

7. The use of internet at school doesn't seem to provide better test results. On the contrary, in non-OECD countries, students who claim to use internet at school show slightly lower performance in all 3 disciplines.

![Score distribution](/images/fig17.jpg)


## Key Insights for Presentation

In the presentation, I first show the correlation between the scores obtained by students in each of the 3 disciplines. We see this through a series of scatterplots comparing each discipline to the other two.

Afterwards, I focus on the relationship between each of the 4 background independent variables with the scores, using the violin and box plots obtained in the exploratory visualization. No modification is done to any of the plots.
