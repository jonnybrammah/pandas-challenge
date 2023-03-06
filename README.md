# pandas-challenge
---

## Project Description

This project analyzes data from fifteen schools (seven District schools and eight Charter schools) to determine the effects, if any, of per student budget, school size, and the type of school itself on the school's average scores in reading and math assignments, and their overall passing rate (students attaining 70% or greater in both the reading and math assignments).
To complete this analysis, the information was read from csv files into a Jupyter notebook and analyzed using Pandas. In all cases, the data was combined into a large dataframe, and then grouped into the relevant variable to display the results as summary dataframes.

---

## Analysis Results

- Contrary to what is likely the prevailing belief, a higher budget per student does **not** lead to an increase in the overall passing rate of students within the school. Schools with budgets of less than $585 per student have average overall passing rates of approximately 90%, whereas schools in the highest category of $645 - $680 per student have passing rates of roughly 54%. The schools in between these extremes show the same pattern.
- School size does have a marked effect on the overall passing rate, with small- and medium-sized schools both having overall passing rates of roughly 90% each (89.88% for small schools and 90.62% for medium ones). Large schools, on the other hand, have passing rates of only 58%. For this analysis, "small" is defined as fewer than 1000 students, large is defined as 2000-5000 students and medium is between these two extremes.
- Finally, charter schools do appear to have a higher passing rate than district schools. Charter schools' average passing rate is around 90% and District schools' average passing rate is closer to 54%. However, on the whole there are more small- and medium-sized Charter schools and all District schools are classified as large, so this effect could be a consequence of school size.

Further analysis could include the effect of class sizes, rather than school sizes, on student attainment and to further analyze if this is more impactful than the size of the school overall.

![Charter Schools Vs Public Schools](https://www.nctq.org/dms/images/Feb_PTT.png)
