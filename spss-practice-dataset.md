## SPSS Practice Dataset: Student Survey Data

This is a simulated dataset of 100 university students, containing various demographic, academic, and psychosocial variables that you can use to practice different SPSS analyses.

### Variables in the Dataset

**Demographic Variables:**
- ID: Participant identification number (1-100)
- Age: Student age in years (18-30)
- Gender: 1 = Male, 2 = Female, 3 = Non-binary
- ResidenceType: 1 = On-campus, 2 = Off-campus with family, 3 = Off-campus independent
- FirstGen: First-generation college student (0 = No, 1 = Yes)
- WorkHours: Hours worked per week at job (0-40)

**Academic Variables:**
- GPA: Grade point average (0-4.0 scale)
- Major: Academic major (1 = STEM, 2 = Social Sciences, 3 = Humanities, 4 = Business, 5 = Arts)
- StudyHours: Average hours spent studying per week (0-50)
- AttendanceRate: Percentage of classes attended (0-100)
- YearInSchool: 1 = Freshman, 2 = Sophomore, 3 = Junior, 4 = Senior

**Psychosocial Variables:**
- StressLevel: Self-reported stress (1-10 scale)
- SleepHours: Average hours of sleep per night (3-10)
- SocialSatisfaction: Satisfaction with social life (1-7 scale)
- Anxiety: Anxiety symptoms score (0-21)
- Depression: Depression symptoms score (0-21)
- Motivation: Academic motivation level (1-7 scale)
- ExerciseFreq: Days per week of physical exercise (0-7)

### Data

```
ID,Age,Gender,ResidenceType,FirstGen,WorkHours,GPA,Major,StudyHours,AttendanceRate,YearInSchool,StressLevel,SleepHours,SocialSatisfaction,Anxiety,Depression,Motivation,ExerciseFreq
1,19,1,1,0,0,3.5,1,25,95,1,6,7.5,5,8,6,6,3
2,20,2,1,0,10,3.2,3,20,88,2,7,7,4,10,8,5,2
3,18,2,1,1,0,3.8,2,30,98,1,5,8,6,7,4,7,4
4,21,1,2,0,15,3.1,4,15,75,3,8,6.5,3,12,10,4,1
5,22,2,3,0,20,3.4,1,22,82,4,7,6,4,9,7,5,3
6,19,3,1,0,5,3.6,5,18,90,1,6,7,5,8,6,6,2
7,20,1,2,1,25,2.8,4,10,65,2,9,5.5,2,14,12,3,0
8,21,2,3,0,15,3.3,2,20,85,3,7,6.5,4,10,8,5,2
9,23,1,3,1,30,3.0,1,15,70,4,8,6,3,11,9,4,1
10,18,2,1,0,0,3.9,3,28,95,1,4,8,6,6,3,7,5
11,20,1,1,0,10,3.5,1,25,90,2,6,7,5,8,6,6,3
12,19,2,2,1,20,3.0,2,18,75,1,8,6,3,12,10,4,1
13,22,1,3,0,25,3.2,4,15,80,4,7,6.5,4,9,7,5,2
14,21,2,1,0,5,3.7,5,22,92,3,5,7.5,6,7,5,6,4
15,18,3,1,1,0,3.4,3,20,85,1,6,7,4,9,7,5,2
16,23,1,3,0,35,2.9,4,12,70,4,9,5.5,3,13,11,3,1
17,20,2,2,1,15,3.3,1,22,85,2,7,6.5,4,10,8,5,3
18,19,1,1,0,0,3.8,2,28,95,1,5,8,6,7,4,7,4
19,21,2,3,0,20,3.1,3,15,75,3,8,6,3,12,9,4,2
20,22,1,3,1,30,2.7,4,10,65,4,9,5,2,14,12,3,0
21,19,2,1,0,5,3.6,5,24,90,1,6,7.5,5,8,6,6,3
22,20,3,2,1,15,3.2,1,20,80,2,7,6.5,4,10,8,5,2
23,21,1,3,0,25,3.0,2,15,75,3,8,6,3,11,9,4,1
24,18,2,1,0,0,3.9,3,30,98,1,4,8,6,6,3,7,5
25,22,1,2,1,20,3.3,4,18,85,4,7,6.5,4,9,7,5,2
26,19,2,1,0,0,3.7,1,25,92,1,5,7.5,5,7,5,6,4
27,20,1,2,0,15,3.4,3,20,85,2,6,7,4,9,7,5,3
28,21,2,3,1,25,2.9,4,12,68,3,9,5.5,3,13,11,3,1
29,23,1,3,0,30,3.1,2,15,75,4,8,6,3,11,9,4,2
30,18,3,1,1,0,3.5,5,22,90,1,6,7.5,5,8,6,6,3
31,20,2,1,0,10,3.6,1,24,92,2,5,7.5,5,7,5,6,4
32,19,1,2,1,20,3.0,2,15,75,1,8,6,3,12,10,4,1
33,22,2,3,0,25,3.2,4,18,80,4,7,6.5,4,9,7,5,2
34,21,1,1,0,5,3.8,3,28,95,3,4,8,6,6,4,7,4
35,18,2,1,1,0,3.3,5,20,85,1,7,7,4,10,8,5,3
36,23,1,3,0,35,2.8,4,10,65,4,9,5,2,14,12,3,0
37,20,3,2,1,15,3.2,1,20,80,2,7,6.5,4,10,8,5,2
38,19,1,1,0,0,3.7,2,25,90,1,5,7.5,5,7,5,6,4
39,21,2,3,0,20,3.0,3,15,75,3,8,6,3,12,9,4,1
40,22,1,3,1,30,2.9,4,12,70,4,9,5.5,2,13,11,3,1
41,19,2,1,0,5,3.6,5,24,90,1,6,7.5,5,8,6,6,3
42,20,1,1,0,10,3.4,1,22,85,2,7,7,4,9,7,5,3
43,21,2,2,1,20,3.1,2,18,80,3,8,6,3,11,9,4,2
44,18,1,1,0,0,3.9,3,30,98,1,4,8,6,6,3,7,5
45,22,3,3,1,25,3.2,4,15,75,4,7,6,4,10,8,5,1
46,19,2,1,0,0,3.7,1,25,95,1,5,7.5,5,7,5,6,4
47,20,1,2,0,15,3.3,3,20,85,2,7,7,4,10,8,5,2
48,21,2,3,1,25,2.8,4,10,65,3,9,5,2,14,12,3,0
49,23,1,3,0,30,3.0,2,15,75,4,8,6,3,11,9,4,1
50,18,2,1,1,0,3.6,5,22,90,1,6,7.5,5,8,6,6,3
51,20,1,1,0,10,3.5,1,24,92,2,6,7,5,8,6,6,4
52,19,3,2,1,20,3.1,2,15,75,1,8,6,3,12,10,4,1
53,22,2,3,0,25,3.3,4,18,80,4,7,6.5,4,9,7,5,2
54,21,1,1,0,5,3.8,3,28,95,3,4,8,6,6,4,7,5
55,18,2,1,1,0,3.4,5,20,85,1,7,7,4,10,8,5,3
56,23,1,3,0,35,2.7,4,10,65,4,9,5,2,14,12,3,0
57,20,2,2,1,15,3.2,1,20,80,2,7,6.5,4,10,8,5,2
58,19,1,1,0,0,3.7,2,25,90,1,5,7.5,5,7,5,6,4
59,21,3,3,0,20,3.0,3,15,75,3,8,6,3,12,9,4,1
60,22,1,3,1,30,2.9,4,12,70,4,9,5.5,2,13,11,3,1
61,19,2,1,0,5,3.6,5,24,90,1,6,7.5,5,8,6,6,3
62,20,1,1,0,10,3.5,1,22,85,2,6,7,4,9,7,5,3
63,21,2,2,1,20,3.1,2,18,80,3,8,6,3,11,9,4,2
64,18,1,1,0,0,3.9,3,30,98,1,4,8,6,6,3,7,5
65,22,2,3,1,25,3.2,4,15,75,4,7,6,4,10,8,5,1
66,19,3,1,0,0,3.7,1,25,95,1,5,7.5,5,7,5,6,4
67,20,1,2,0,15,3.3,3,20,85,2,7,7,4,10,8,5,2
68,21,2,3,1,25,2.8,4,10,65,3,9,5,2,14,12,3,0
69,23,1,3,0,30,3.0,2,15,75,4,8,6,3,11,9,4,1
70,18,2,1,1,0,3.6,5,22,90,1,6,7.5,5,8,6,6,3
71,20,1,1,0,10,3.4,1,20,88,2,7,7,4,9,7,5,2
72,19,2,2,1,20,3.2,2,18,85,1,7,6.5,4,10,8,5,3
73,22,1,3,0,25,3.1,4,15,78,4,8,6,3,11,9,4,1
74,21,3,1,0,5,3.7,3,25,90,3,5,7.5,5,7,5,6,4
75,18,2,1,1,0,3.5,5,22,88,1,6,7,4,8,6,6,3
76,23,1,3,0,35,2.8,4,12,68,4,9,5.5,2,13,11,3,0
77,20,2,2,1,15,3.3,1,20,82,2,7,6.5,4,10,8,5,2
78,19,1,1,0,0,3.8,2,28,95,1,4,8,6,6,4,7,5
79,21,2,3,0,20,3.0,3,15,75,3,8,6,3,12,9,4,1
80,22,1,3,1,30,2.7,4,10,62,4,9,5,2,14,12,3,0
81,19,3,1,0,5,3.5,5,22,88,1,6,7,5,8,6,6,3
82,20,2,1,0,10,3.6,1,25,92,2,5,7.5,5,7,5,6,4
83,21,1,2,1,20,3.0,2,15,78,3,8,6,3,11,9,4,1
84,18,2,1,0,0,3.9,3,30,96,1,4,8,6,6,3,7,5
85,22,1,3,1,25,3.1,4,15,72,4,8,6,3,12,10,4,1
86,19,2,1,0,0,3.7,1,25,94,1,5,7.5,5,7,5,6,4
87,20,1,2,0,15,3.4,3,20,85,2,6,7,4,9,7,5,3
88,21,3,3,1,25,2.9,4,12,68,3,8,5.5,3,13,11,3,1
89,23,2,3,0,30,3.0,2,15,75,4,8,6,3,11,9,4,2
90,18,1,1,1,0,3.6,5,22,90,1,6,7.5,5,8,6,6,3
91,20,2,1,0,10,3.5,1,24,92,2,6,7,4,8,6,6,4
92,19,1,2,1,20,3.1,2,15,75,1,8,6,3,12,10,4,1
93,22,2,3,0,25,3.2,4,18,80,4,7,6.5,4,9,7,5,2
94,21,3,1,0,5,3.8,3,28,95,3,4,8,6,6,4,7,5
95,18,2,1,1,0,3.4,5,20,85,1,7,7,4,10,8,5,3
96,23,1,3,0,35,2.8,4,10,65,4,9,5,2,14,12,3,0
97,20,2,2,1,15,3.3,1,20,80,2,7,6.5,4,10,8,5,2
98,19,1,1,0,0,3.7,2,25,90,1,5,7.5,5,7,5,6,4
99,21,2,3,0,20,3.0,3,15,75,3,8,6,3,12,9,4,1
100,22,1,3,1,30,2.8,4,12,68,4,9,5,2,13,11,3,1
```

### Instructions for Loading into SPSS

1. Copy the data section above into a text editor
2. Save it as a CSV file (e.g., "student_survey.csv")
3. Open SPSS
4. Go to File > Import Data > CSV Data...
5. Navigate to your saved CSV file and open it
6. In the import wizard, ensure that:
   - The first row is treated as variable names
   - Comma is selected as the delimiter
   - Each variable is assigned the correct measurement level:
     - ID: Scale
     - Age: Scale
     - Gender: Nominal
     - ResidenceType: Nominal
     - FirstGen: Nominal
     - WorkHours: Scale
     - GPA: Scale
     - Major: Nominal
     - StudyHours: Scale
     - AttendanceRate: Scale
     - YearInSchool: Ordinal
     - StressLevel: Ordinal
     - SleepHours: Scale
     - SocialSatisfaction: Ordinal
     - Anxiety: Scale
     - Depression: Scale
     - Motivation: Ordinal
     - ExerciseFreq: Scale
7. Click "OK" to import the data

### Value Labels

After importing, you may want to define value labels for categorical variables:

1. Go to Variable View
2. For each categorical variable, click in the "Values" cell and define the labels:
   - Gender: 1 = "Male", 2 = "Female", 3 = "Non-binary"
   - ResidenceType: 1 = "On-campus", 2 = "Off-campus with family", 3 = "Off-campus independent"
   - FirstGen: 0 = "No", 1 = "Yes"
   - Major: 1 = "STEM", 2 = "Social Sciences", 3 = "Humanities", 4 = "Business", 5 = "Arts"
   - YearInSchool: 1 = "Freshman", 2 = "Sophomore", 3 = "Junior", 4 = "Senior"

### Suggested SPSS Analyses to Practice

1. **Descriptive Statistics**:
   - Frequencies for categorical variables
   - Descriptives for continuous variables (mean, median, SD, etc.)
   - Explore command for detailed statistics with normality tests
   - Histograms, box plots, and other visualizations

2. **Correlational Analyses**:
   - Bivariate correlations between GPA and other variables
   - Partial correlations controlling for study hours
   - Scatterplots with regression lines

3. **Group Comparisons**:
   - Independent samples t-tests (e.g., GPA differences by gender)
   - One-way ANOVA (e.g., GPA differences across majors)
   - Chi-square tests for categorical variables

4. **Regression Analyses**:
   - Simple linear regression predicting GPA from study hours
   - Multiple regression predicting GPA from multiple predictors
   - Hierarchical regression adding blocks of predictors

5. **Advanced Analyses**:
   - MANOVA examining multiple outcome variables
   - Factor analysis to identify underlying dimensions in psychosocial variables
   - Reliability analysis (Cronbach's alpha) for scale variables
   - Cluster analysis to identify student profiles/types

6. **Data Manipulation Practice**:
   - Computing new variables (e.g., StudyEfficiency = GPA/StudyHours)
   - Recoding variables into categories
   - Split file analyses by gender or year in school
   - Selecting cases based on criteria

This dataset is designed to have meaningful relationships between variables so that your analyses will yield interesting results to interpret.
