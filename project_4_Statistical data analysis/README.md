# Development of  mobile phone plan for telecom operator.

__Client__ - a mobile operator.

__Input Data__ - nformation from 500 users: their demographics, geographical location, the mobile phone plan they are currently using, and the number of calls and messages they made in 2018.

__Target__ - analyze customer behavior and determine which mobile phone plan is more advantageous.

__What's Done__:

1. Data Preprocessing:

- Analyzed data from 5 source files.
- Modified index columns.
- Corrected data types.
- Replaced '0' values with small values for calls and internet sessions.
- Creation of new features.

2. Exploratory Data Analysis (EDA) performed:

- Conducted a detailed comparison of two mobile phone plans.
- Analyzed mean, variance, and standard deviation.
- Created graphical representations, including histograms and boxplots.
- Applied the 3-sigma rule to assess calls, messages, and internet sessions.

3. Hypotheses tested:

- Rejected the hypothesis that the average revenue of users on two different mobile phone plans is the same.
- Accepted the hypothesis that the average revenue of users from Moscow and other regions is the same.
- Rejected the hypothesis that the average revenue of users on the "Ultra" and "Smart" mobile phone plans is the same, indicating that the "Smart" plan generates lower revenue than the "Ultra" plan.
- Based on the analysis, the "Ultra" mobile phone plan was determined to be the better option.


__Tools used__ - pandas, NumPy, Matplotlib, SciPy.