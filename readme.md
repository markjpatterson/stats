
# Stats 2024 Paper

## Question 2

### QUESTION 2

Q2. (a)

Given n1 = 110, z1=65 and n2=120,x2=70, calculate a 90% confidence interval for the
difference in the two proportions. Using the confidence interval, comment on the population
(5 Marks)

(TOTAL MARKS: 25)

proportions.

### Q2. (b)

Calculate and interpret the R2 value from the following sample data:
X = {7,19,33,42}; Y = {6, 10, 14,23}.

### a3

### Calculation of \( R^2 \) (Coefficient of Determination)

Given:
- \( X = \{7, 19, 33, 42\} \)
- \( Y = \{6, 10, 14, 23\} \)

The coefficient of determination \( R^2 \) measures the proportion of the variance in the dependent variable \( Y \) that is predictable from the independent variable \( X \).

To calculate \( R^2 \), we need to:
1. Find the regression line \( Y = a + bX \).
2. Calculate the predicted values \( \hat{Y} \).
3. Calculate the Total Sum of Squares (SST).
4. Calculate the Regression Sum of Squares (SSR).
5. Finally, calculate \( R^2 \).

Let's go through the steps.

#### 1. Calculate the regression coefficients \( a \) and \( b \)

The formulas for the slope \( b \) and intercept \( a \) are:

\[
b = \frac{n\sum(XY) - \sum X \sum Y}{n\sum X^2 - (\sum X)^2}
\]

\[
a = \frac{\sum Y - b\sum X}{n}
\]

#### 2. Calculate the predicted values \( \hat{Y} \)
\[
\hat{Y_i} = a + bX_i
\]

#### 3. Calculate SST (Total Sum of Squares)
\[
SST = \sum (Y_i - \bar{Y})^2
\]
where \( \bar{Y} \) is the mean of \( Y \).

#### 4. Calculate SSR (Regression Sum of Squares)
\[
SSR = \sum (\hat{Y_i} - \bar{Y})^2
\]

#### 5. Calculate \( R^2 \)
\[
R^2 = \frac{SSR}{SST}
\]

Now, let's perform these calculations. I'll do this step-by-step.

### Results

1. **Regression Equation**: 
   \[
   \hat{Y} = 1.852 + 0.451X
   \]
   
2. **Predicted Values \( \hat{Y} \)**:
   \[
   \hat{Y} = \{5.01, 10.43, 16.75, 20.81\}
   \]

3. **Total Sum of Squares (SST)**: 
   \[
   SST = 158.75
   \]

4. **Regression Sum of Squares (SSR)**:
   \[
   SSR = 145.24
   \]

5. **\( R^2 \) Value**: 
   \[
   R^2 = 0.915
   \]

### Interpretation

The \( R^2 \) value of approximately **0.915** indicates that about **91.5%** of the variability in the dependent variable \( Y \) is explained by the independent variable \( X \) in the regression model. This suggests a strong relationship between \( X \) and \( Y \) in this dataset.

Q2. (c)

Given E[X]=0.88, E[X2]=1.12, E[Y]=0.92,E[Y2]=1.14,E[XY]= 0.55, calculate the
(5 Marks)

(5 Marks)

(ii)

correlation between X and Y.

Q2. (d)

A race track is open to the public for both motorcycle and car use. The lap times (minutes) of
motorcycles is XM ~ N(u=3.4,o=1.4). The lap times of cars is Xc ~ N(p=3.6,o=0.78).

(i) Calculate the probability that the average lap time is between 3 and 4 minutes for
(4 Marks)
(6 Marks)

a group of ten motorcyclists.
Calculate the probability that a motorcycle is faster than a car.

(End of Question 2)