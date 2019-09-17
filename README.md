# Analysis-of-Life-Expectancy-by-County

## Introduction
This project analyzes the relationship between life expectancy and obesity prevalence, smoking prevalence, physical activity prevalence, diabetes prevalence, and alcohol use prevalence on the country level with interest in the differences between life expectancy in counties which are urban and counties which are rural. It was done as a senior research project in Economics.

Go to (Analysis of Life Expectancy by County Megan Tan.docx) to view the research paper and (Analysis of Life Expectancy by County.nb) to view the source code.

## Some discussion
- Rural counties have lower life expectancy (by about .5 year for males and 1 year for males), but also higher rates of smoking, obesity, and diabetes, and lower rates of physical activity and alcohol use
- Consistent with prior research, smoking prevalence and diabetes prevalence are associated with decreased life expectancy, and physical activity prevalence is associated with increased life expectancy
- Unexpectedly, alcohol use is associated with increased life expectancy. This is probably due to the way alcohol use is defined (any use of alcohol in the past 30 days counts) and also due to the fact that people in urban counties both drink more and live longer.
- Inconsistent with prior research, obesity prevalence is associated with increased life expectancy but only in males (females show a decreased life expectancy which is consistent with prior research). This may be because our model has many explanatory variables which are not independent from each other. For example, obesity prevalence is highly related to diabetes prevalence. A simple ordinary least squares regression of life expectancy on obesity prevalence shows a negative relationship.
- The higher life expectancy in urban counties is partially explained through the differences in the behaviors (explanatory variables) in urban counties. However, the majority of the difference in life expectancy is unexplained in the model used in this study. Some explanations for the higher life expectancy in urban counties may be because healthcare and education is more accessible in urban counties. More research is needed to explain this difference.