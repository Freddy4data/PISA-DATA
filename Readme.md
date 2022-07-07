# Pisa 2012 Data Exploration

## Dataset

PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. This survey examines

how well students have learned the school curriculum,
how well prepared they are for life beyond school.
Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science. Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy. The dataset can be found  https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip. To understand the dataset variables https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv.

## Summary of Findings

- In the exploration, there is a high postive correlation between all the assessments taken by the student. A correlation of 0.93 between the maths score amd science score was expected because a student's performance in maths is in a certain way dependent on his/her understanding of sciences. A student that performs well in sciences is expected to perform well in maths as well as otherwise. Reading being a general test of knowlegde should most likely almost always be correlated on the student's performance in other assessments.
- I found out that most of the students in this research reside in Mexico, Italy, Spain, Canada and Brazil while the least represented is Liechtenstein.
- I realised that only very few students disagree with the statement 'I can succeed with enough effort'. It is also expected that student that disagreed won't put enough effort in the assessment and likely would have had low scores. It was later proven to be the case.
- 48.8%(i.e majority) of the student learn by studying the most important parts of a discipline, 31.2% learn by relating new knowledge to existing knowledge while only 20.0% learn by heart.
- There some interesting correlations between gender and the three subjects. Female students seem to do a lot better on the reading scores than male students, this is seen to be true across the whole range of data, as seen in the box plots. 
- Male students seem to do slightly better than female students in the upper band of scores in mathematics and science (though also slightly worse in the lower range of scores in science), however, female students are more likely to achieve average score across all three subjects – i.e. they have less variance across the scores.
- 50% of the top performers are students from Asia which is quite understandable due to the level and quality of education over there. the other 50% being Europian countries. Countries coming at the bottom mainly from South America and middle east with Peru coming last.
- The effect of internet access was highly significant on each of the scores of the students. Students with internet access performed much better than students without internet access and this is quite relatable as the internet provides answers to complex questions related to all fields of study which will be beneficial to the students.
- Students with one- or two-parents show similar mean scores, while those students who grew up without parents show an overall lower score of almost 100 points lower.
- Students who strongly disagree with the statement 'I can succeed with enough effort' show lower overall scores than the rest of the students.
- The most effective learning strategies in decreasing order are: relating to existing concepts > studying what is most important > studying from memory.
- There is a positive correlation between the educational level of the parents and the scores of the students i.e the higher the level of education, the higher the score and vice vesa.

## Key Insights for Presentation

- For the presentation, I focused on the effect of numerous variables in the data set on the scores of the students. I start by showing the distribution of the total score using a histogram. The plot clearly showed that the total scores were normally distributed and was centered aroung 1500 points.
- I then went on to show the distribution of the qualfications of the parents of the students using a well labelled count plot. I found out that more than 50% of the parents have at least a general upper secondary qualification.
- I then went on to show the correlation between the mean scores of each of the assessments taken using a well labelled reg plot with a suitable trend line which showed the strong positive correlation between them.
- I further analysed the distribution of the average scores of each of the assessment taken based on countries using a well labelled clustered bar chart.
- I then visualized the effect of some factors like family structure, perceived control, learning strategies and parents educational qualification on the total scores using a well labelled violin plot to see the quartiles clearly.
- I also visualized the distribution of the scores per gender in each country using a well labelled point plot. I found out that:
> It is evident that the boys slightly outperformed the girls in maths in almost all the countries except for Iceland, Jordan and Qatar. As earlier shown, boys performed better generally at Maths compared to girls.
> The girls outperformed the boys in every country for the reading assessment in this dataset and they were really large margins between them for some countries like Finland, Germany, Jordan, Bulgaria, UAE, Qatar e.t.c
> For the science scores, there was very little seperating them in almost all the countries except for Jordan and Qatar where the females clearly performed better. 
- I went on to visualize the total and parents educational qualification with respect to social class and immigration status using a well labelled point plot with the right formatting and color. The result of the analyzation was that:
NB: Social class measures the number of belongings at home
> A higher level of Education by the parents leads to a better score for the student. As can  be seen on the graph, the students having parents with the highest level of education and highest possession(high social class) have the highest scores and vice versa.
> It can also be seen that in the lower social class, the maximum grade peak is reached with a parental education of ISCED 3B, 4. 
> Although the impact of parent's educational background is positively correlated to student's grades, it is more noticable in families with native-born parents. In the case of parents with an educational level up to ISCED 2, students with second-generation immigrant parents show better test scores while students having parents with highest qualification and native-born have the highest scores.
- Finally, I visualized the total score and learning strategies with respect to the perceived control using a well labelled point plot with the right formatting and color. The result of the analyzation was that:
NB : perceived control shows to what extent does the student identify with the statement "I can succeed with enough effort".
> Across every learning strategy, strongly disagreeing with the statement above will lead to a lower score compared to other options regardless of the learning strategy while the reverse is the case with the students who strongly believe in success inherent from inputing enough effort.
> students that learn by means of relating new concepts to existing ones and strongly agree with the statement above most usually will have the highest scores.
