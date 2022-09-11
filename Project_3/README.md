# (Pisa 2021: an overview of Math, reading and science students scores in ODCE and non ODCE countries )
## by (Mohamed Lamouchi)


## Dataset

> Since 2000, the OECD has attempted to evaluate the knowledge and skills of 15-year olds across the world through its Pisa test. More than 510,000 students in 65 economies took part in the latest test, which covered maths, reading and science, with the main focus on maths - which the OECD state is a "strong predictor of participation in post-secondary education and future success."
The triennial results provide a wealth of data - from which countries are making the biggest improvements in education ranking to how the gender gap varies by subject. We've picked out some key figures from the report.

>The full 2012 PISA dataset can be found[link] https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1581581520574000

>The PISA data dictionary, which gives a brief  of each feature.[link]https://www.google.com/url?q=https://www.google.com/url?q%3Dhttps://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisadict2012.csv%26sa%3DD%26ust%3D1554482573645000&sa=D&source=editors&ust=1662431241064260&usg=AOvVaw1blCYcuOqpG3ewgMPpun2G

>The original PISA 2012 dataset contained information from 485,490 students and 646 features. After our data cleaning process, we condensed the number of features to 18: country, OECD_country, gender, Mother_Schooling, Mother_Job ,Father_Schooling, Father_Job, cellular_phones, computers,books_at_home, computer_programming, At_Home_Internet_connection, At_school_Internet_connection, Immigration_status, Family_wealth, overall math score, Reading score and  Science score. All features were converted to category type except Math, reaing, sciecne score and Family weatlh.



## Summary of Findings

> Student from Mexico and Italy lead in term of number of student with more than 30000, followed by Spain Canda Brazil Australia United Kingdom.
>  Shanghai leads the three test foloowed by Asiatic countries. that in Math Reading and science fellowed in second place by Singapore and Hong kong
>it can be observed that the math scores for males and females looks very similar - normally distributed, with similar means (roughly between 400 to 450) and similar range (slightly below 200 to slightly above 800). But overall Male students perform better than Female in math.
This trend become more in favort for Female and become more simimlar in Science score
>2/3 of student come from OECD, countries with high-income economies with a very high Human Development Index (HDI) and are regarded as developed countries. 
> There is clear dominance for OECD countries specially in median score but the gap reduce for outperformer, there is probably due the a better educatif system
>There is a strong corrolation betwwen Math score and reading and science score, Family wealth does not have an impact on scores.
>Immigration status does affect Pisa scores as first and second generation performs wors than "native.
>The number of computer clearly have a positive correlation on scores but strangely programming have a negative impact on the three scores.

## Key Insights for Presentation

> For this presentation, we narrowed my focus to the following 2 approaches:

### Approach 1:Pisa 2012 score in countries level

>Here we examine the realation between differents scores  for countries 
Comparing the scores of each country in each subject, it seems that Asian countries are more prominent in each subject
>Using horizontal bars we generate graph containning the top 20 coutries in term of number of students We can observe that student from Mexico and Italy lead in term of number of student with more than 30000, followed by Spain Canda Brazil Australia United Kingdom.
>Shanghai leads the three test foloowed by Asiatic countries. that in Math Reading and science fellowed in second place by Singapore and Hong kong
And If we look now on top performer countries that have the most outperforming students Asiatics countries still lead inn every metrics That's the mark of educatif system that provide a high quality education for it students
>And overall OECD countries sems to have a educatif system that performs 

### Approach 2: Pisa 2012 score in Family and indivudual level

>Here we examine the relationship between  gender, Mother_Schooling, Mother_Job ,Father_Schooling, Father_Job, cellular_phones, computers,books_at_home, computer_programming and 
>If we compare between Math reading and science scores by a random sample of 1000 student and by gender we can see a positive corrolation between math, reading and science. We can also see that Male performls better on Math while Female better on reading, for science they both do equally.
>With a heat map we confirm the score correllation but allso we can see that Family wealth does not have corrolation with math reading or science score.
Immigration status does affect Pisa scores as first and second generation performs wors than "native. Thre is high corrolation between math reading and science score, what is remarkable that computer programming has a negative effect on Math reading and sciecne score Student with parent who have a full timle job and a higher education perform better

**To convert my Jupyter Notebook slides, navigate to the terminal and follow these steps:**
1. Navigate to `/Communicate-Data-Findings/`
2. type `jupyter nbconvert pisa2012_explanatory.ipynb --to slides --template output_toggle.tpl --post serve`

**To deal with the original dataset, download the full original PISA 2012 dataset linked above and move it to the `/data/` folder.**.
