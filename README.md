# Blogpost
Write a Data Science Blog Post

## 1. Installations / Libraries

- Python 3
- numpy 1.18.4
- pandas 1.0.4
- matplotlib 3.2.1
- Seaborn 0.10.1

## 2. Project Motivation

I have choosen a Dataset of my own: The Data of the PISA 2012 Assessment. Specifically, in the past there has been a 'PISA Data Visualization Competition' and the orignal Dataset which has been used can still be downloaded:

http://www.oecd.org/pisa/pisaproducts/datavisualizationcontest.htm

**About the Survey Date:**<br>
PISA is a survey of students' skills and knowledge as they approach the end of compulsory education. It is not a conventional school test. Rather than examining how well students have learned the school curriculum, it looks at how well prepared they are for life beyond school.

**Around 510,000 students in 65 economies took part in the PISA 2012 assessment of reading, mathematics and science representing about 28 million 15-year-olds globally.** Of those economies, 44 took part in an assessment of creative problem solving and 18 in an assessment of financial literacy.

I am interested in how the four independent variables
- 'Gender', 
- 'Age at Start of Primary education', 
- 'Age at First use of computers' and 
- 'Out-of-School Study Time - Homework'<br>

affect various dependent variables such as<br>

- qualitative factors ('Satisfaction') as well as 
- quantitative factors ('Score in Mathmatics')

**Specifically, I am going to address the following Questions but I am going to explore other Correlations as well:**

- Do students who use Computers first early in their Life spend more time using the Computer?
- Do male Students make use of Computer programming more frequently?
- Does spending more time on Homework translates into higher Scores in mathematics and is there a Gender-Difference?

## 3. File Descriptions

- README.MD: Provides a Project Overview
- ANALYSIS.IPYND: Share my code and data wrangling/modeling techniques
- PISA2012.CSV: The whole Dataset of the PISA 2012 Assessment, unfortunately way to large to upload it to GitHub, can be downloaded here: http://www.oecd.org/pisa/pisaproducts/datavisualizationcontest.htm
- PISADICT2012.CSV: Data Dictionary for the PISA2012.CSV File

## 4. Summary of the results of the analysis
- For in-depth-analysis please refer to my MEDIUM Blog Post
- There seems to be a slightly positive correlation between the Perceived Satisfaction at School and the Start of Primary education. Students who start later are more satisfied.
- There seems to be a slightly positive correlation between the Perceived Easiness of Friends-Making and the Start of Primary education. For Students who start later it is easier to make friends.
- There is an overall negative trend. Many students spend rather little time of computer use, few students spend rather much time of computer use.
- There seems to be a slightly negative correlation between the Time of computer use (mins) and the Age-Category at First use of computers. Students who start early using computers spend on average more time using them.
- Overall there seems to be a slightly negative correlation between the Frequency of Computer programming and the Age-Category at First use of computers. Students who start early using computers are programming more frequently (i.e. 'Often').
- There seems to be a Gender-Gap: Women are less likely to program frequently. The overall relationship between the Frequency of Computer programming and the Age-Category at First use of computers seems not to be gender-specific, but there is a significant gap between both genders in absolute terms regarding the Frequency of Computer programming.
- There seems to be a positive correlation between the Out-of-School Study Time (Homework) and the Score in mathematics, but only to a certain point. The overall relationship between the Out-of-School Study Time (Homework) and the Score in mathematics seems not to be gender-specific, but there is a gap between both genders in absolute terms regarding the Score in mathematics. Despite women spend on average more time on Out-of-School Study they have at almost every bin of Out-of-School Study Time lower Scores in mathematics than men.

## 5. Licensing, Authors, Acknowledgements, etc.
 - I got some inspirations from the successfull Submissions of the 'Data Visualization Contest @ use!R 2014'
 - However the Ideas could not be transferred directly 
 - http://mi2.mini.pw.edu.pl:8080/SmarterPoland/PISAcontest/
 
