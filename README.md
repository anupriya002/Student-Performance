<h1 align="center">CSCI 2000 - Scientific Data Analysis</h1> 
<h2 align="center"> How Students Perform on Exams Based on Cultural and Academic Background </h2> 

**Project Group 8 (Student names and Github Usernames);**
- Emma Monson – EmmieSue
- Anupriya Dubey – anupriya002
- Nicholas Kisson – Kxssoon
- Alexander Tran – Alexander-Tran



**Dataset Name:** Student Performance in Exams

**Dataset Source Link:** https://www.kaggle.com/spscientist/students-performance-in-exams

**References**:

Seshapanpu, J. (2018). Students Performance in Exams. Retrieved November 28, 2021, from https://www.kaggle.com/spscientist/students-performance-in-exams. 

# Introduction

We are reporting on American student scores on three standardized tests as well as the students gender, race, parent education, type of lunch and whether they prepared for the test or not. We are using this information to draw conclusions about the dataset.

The data we are using is the marks students in America achieved in three standardized tests. The data also surveys different things about the students, including their home life and if they completed a test prep. All the data is valid and accurate. None of the data needs to be cleaned or preprocessed before starting EDA.

The following entails a brief description of the dataset we utilized in out analysis.

**a)  The students gender;**

This data puts the students into two groups, whether they are female or male. There are more females than males in this study.

**b)  Race/ Ethnicity;**

This data groups the students based on their race and ethnic status. There are 5 groups in the dataset. They are labeled Group A, B, C, D, and E. Students are only apart of one group. The data does not specify which ethnic groups each letter group belongs to. Most students are apart of Group C.

**c)  Parental Level of Education;**

This dataset lists the parent(s) of the students highest level of education. It ranges from some high school all the way to master’s degree. It includes; some high school, high school, some college, associates degree, bachelor’s degree and master’s degree. Most students have a parent with at least some college education. 

**d)  Lunch;**

 This data lists what type of lunch the students normally eat. The options are standard and free/reduced. For our purposes we can assume that the students are eating this type of lunch every single day. We do not know what the content of the lunches are. Most students eat standard lunch.
 
**e)  Test preparation course;**

This data lists if the students completed a test preparation course prior to taking the three standardized tests. For our analysis, we can assume that the course includes practice in all three subjects (reading, writing and math). The data assumes the students rather completed the full course or did not do the course at all. There is no data if the students only did the course for one subject. We will assume that the students rather completed the course for all three subjects or none at all. Most students did not complete the test preparation course.

**f)  Math Score;**

 The subject of the first of the three standardized tests. The score of the students on the math exam. We do not know at what grade level or what math topics are being assessed. We also do not know the grade level of the students, or if they are even in the same grade level. The scores are collected in percentages that range from 0% to 100%. It is possible that some students did not complete the math exam since there are 2 students that scored under 10% (at least one of them is zero). For our analysis, we will assume all the students attempted the exam. The average on the test was 66%. 
 
**g)  Reading Score;**

The subject of the second of the three standardized tests. This data measures the students score on the reading exam. We hold the same assumptions about the reading scores as we do the math scores. The scores range from 17% to 100%. From this we know that all the students attempted the reading exam because they all received a mark. The average on the test was a 70%. 

**h)  Writing score;**

The subject of the last of the three exams. This data measures the students score on the writing portion of the exam. We hold the same assumptions that we did with the math and reading exams. The scores range from 10% to 100%. We know that all the students took this exam because every student received a mark for it. The average on this test was a 69%.


 
This dataset interested us because we are able to relate to the students. We too, would be able to meet the requirements of most of the data and take the tests. In my case, this data-set reminds me of the literacy test that we had to take in order to graduate high school. Although it did not include a math portion, the rest of the data is similar. Obviously, each student at my high school had a specific gender and race. Every student has parent(s) who completed a certain amount of education. For lunch options, students could bring their own lunch, buy lunch at the café, or go out for lunch. At my high school, there was an option to take a test preparation course after school. Students would go into different classes and the teacher would go over how to do well on the tests. There were also example questions for us to practice as homework. And just like the scores on the standardized tests, we did receive scores on our reading and writing portions of the exam. When we wrote the exam there was both a reading and writing portion.




# Discussion: A Closer Look at the Analysis Results

There are a multitude of things that we learned through the analysis of the chosen dataset. We had initially pursued this dataset in wake of satisfying our curiosity in regards to how external factors can individually and collectively impact a student’s exam scores. As we progressed in our analytical pursuit, our queries started to dive deeper into understanding not only how these factors affect exam performance, but also what they have to indicate about the education system and present day society.

Through analysis, it was observed that the students performed the best in reading and the worst in math. In mathematics, 17.6% of the students were seen to score above 80% and 48.7% and 45.6% scored above a 70 in reading and writing respectively. This information can be used in improving the current curriculum and educational model used to deliver learning material to students. Since the students seem to require the most help in math, adjustments to the curriculum can be made to offer additional help and tutoring services to students for math. Furthermore, additional approaches to teaching math must also be explored and utilized to replace or improve the current method, which are not proving to be as effective as expected.

Additionally, the scores of the students can also be utilized to analyse and identify the gender ratios across each racial group. As seen in the figure below, males have been seen performing better in math in comparison to females, whereas females are observed to outperform males in reading and writing Since group E scored the best in math, and males have been seen to perform better in math, it can be assumed that group E has more boys than girls. Furthermore, since Group C excelled in both reading and writing, and since girls have been observed to outperform boys in these areas, it can be supposed that Group C predominantly consists of females.

<img src="Blog Images/Figure 1.png" style=width:700px>
<h4><center>FIGURE 1</center></h4>



Along with what was mentioned above, we also came across many interesting things while analyzing our dataset. 

Something fascinating that we learned about through this dataset was the influence of parental education levels on a student’s scores and their completion of the test preparation course. We had anticipated a positive correlation in both cases, and had expected that the more educated the parents were, the more successful in school their children would be. This proved to be true for examination scores, as it can be seen below (FIGURE 2) that as the more educated a student’s parents are, the more likely they are to perform well in school. 


<img src="Blog Images/Figure 2.png" style=width:600px>
<h4><center>FIGURE 2</center></h4>

Keeping this in mind, we had then hypothesized that students that had parents from well 
educated backgrounds were more likely to also complete the test preparation course. However, this did not prove to be true as the contrary occurred instead. As seen below in Figure 3, students with parents with only some high school education made up the largest percentage of all the students that completed the test preparation course. Students with parents with a college diploma or higher did somewhat follow the trend of participating in the course, as the greater the parental education level, the more students completed the course. However, this correlation was relatively weaker.

<img src="Blog Images/Figure 3.png" style=width:500px>
<h4><center>FIGURE 3</center></h4>

Additionally, something that surprised us was the lack of correlation between the types of lunch eaten by students and the test preparation course completion. We had expected there to be a positive correlation between the two as we had thought that students that could afford standard lunches would also be the ones to complete the test preparation course. However, through analysis, we found out that there is actually no correlation between the types of lunches eaten and test preparation completion, as seen below in Figure 4.  In fact, we also found out that the majority of the students did not complete the test preparation course at all.

<img src="Blog Images/Figure 4.png" style=width:600px>
<h4><center>FIGURE 4</center></h4>

# Conclusion

**Reflection**

We learned that students who had parents who only have a high school education score less on tests than those whose parents did not graduate high school. We found that data odd because it differs from the overall trend of the graphs. This led us to wonder if there is a reason why students whose parents did not graduate high school score better on tests than those who did. A theory could be that those students appreciate their education more considering it was something that their parents may not have had access to. These students were also the most likely to take the prep course prior to writing the exams (have the highest percentage of students who took the prep course).


**Refinement**

If we were to improve the project, we would research the correlation between races and whether or not they took a test prep and if that influenced their scores on the exams. We could have also used a variety of graphs instead of just bar graphs to represent our data.


# Acknowledgement

*“This project was submitted as the final course project for CSCI 2000U “Scientific 
Data Analysis” during Fall 2021. The authors certify that the work in this 
repository is original and that all appropriate resources are rightfully cited.”*



```python

```
