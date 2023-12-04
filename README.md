# Mathematics-and-Statistics InClass Assignment

## Link to the repository

**Link to the repository:https://github.com/ChloeH719/Mathematics-and-Statistics**

## Link to the video

**

## What is the task about?
**This Inclass Assignment examines the ability of processing datasets, generating plots and calculating statistics using Python.**

**Task 1 encompasses data preprocessing, visualization, and statistical analysis. Initial data cleansing ensures the integrity and validity of subsequent visualizations and statistical computations, which are pivotal for in-depth analysis. Visual representations, such as box plots, histograms, scatter plots, and line plots, are employed to facilitate an intuitive understanding of the data. Concurrently, statistical measures including the mean, median, mode, variance, standard deviation, skewness, and kurtosis are computed to provide a quantitative description of the dataset. These visual and statistical outputs offer insights into the data's inherent characteristics, such as linearity, normality, and variance homogeneity.**

**Task 2 shifts focus to discerning the dataset's nature, including aspects like multilabel/singlelabel classification, the distinction between continuous and discrete data, and categorical versus numerical data types, along with the interrelationships amongst variables. Appropriate analytical techniques, such as regression and classification, are identified and implemented. The efficacy of these models is assessed through metrics like p-value, R-squared, accuracy, mean squared error (MSE), root mean squared error (RMSE), and mean absolute error (MAE). Moreover, varying loss functions are applied according to the characteristic of the datasets, and their relative performance is scrutinized.**

**In conclusion, Tasks 1 and 2 collectively establish a comprehensive pipeline for data analysis, encompassing data preprocessing, visualization, statistical analysis, model development, and evaluation. The construction of models is informed and underpinned by the insights gleaned from statistical analyses.**

## What maths and statistics knowledge are involved?

**For Task1, the knowledge of descriptive statistics is involved, such as mean, median, mode, variance, standard deviation and skewness. The knowledge of data visualization is also involved, such as boxplot, histogram, scatter plot and line plot.**

**For Task2, the knowledge of inferential statistics is involved, such as p-value, R-squared, accuracy, mse, rmse and mae. The knowledge of regression and classification is also involved, such as linear regression, logistic regression and decision tree.**

## Implementation

### Libraries and Packages
```csv``` is used to read the csv file.

```numpy``` and ```math``` is used to calculate the statistics.
```pandas``` is used to process the data.

```matplotlib``` and ```seaborn``` are used to generate plots.

```scipy``` is used to calculate the skewness and kurtosis.

```sklearn``` is used to calculate the statistics and metrics.

```statsmodels``` is used to calculate the statistics.

```random``` is used to generate random numbers.

### Logics Used? Why?

**For Task1, the logic of data preprocessing is used, which is to clean up the data, numerize the data, remove the invalid or missing data to avoid error in the next step. The logic of data visualization is used, which is to generate plots to visualize the data. The logic of statistics calculation is used, which is to calculate the statistics and metrics to describe the data.**

**For Task2, the logic of data preprocessing is used, which is to clean up the data, numerize the data, remove the invalid or missing data to avoid error in the next step. The logic of model building is used, which is to build the model based on the analysis done with the statistics. The logic of model evaluation is used, which is to evaluate the performance of the models.**

## Outcomes
**The outcomes and rationale behind are explained in detail in the .ipynb files.**

## Challenges

### Data Preprocessing
**Some of the datasets contains a huge amount of missing data, after the preprocessing, some variables have only a few valid data left, which is not enough for further analysis. I chose to use other variables with enough valid data to do the analysis.**

### Data Visualization
**Due to the huge amount of data, some of the axis labels are not clear to read, I tried to rotate the labels and solved the problem.**

### Choosing the Right Plot
**As I am not familiar with some of the metrics and statistics, therefore it was hard to decide the plot to visualise the data, therefore I searched through StackOverflow for suggestions.**

## References
**https://learn.saylor.org/mod/book/view.php?id=55290&chapterid=40869**

**https://stackoverflow.com/questions/27144844/converting-multilabel-dataset-into-single-label**

**https://www.ucd.ie/ecomodel/Resources/QQplots_WebVersion.html**

**https://www.statology.org/q-q-plot-normality/**

**https://stackoverflow.com/questions/48009614/quantile-quantile-plot-using-python-statsmodels-api**

**https://www.statology.org/levenes-test-python/**

**https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.levene.html**

**https://docs.scipy.org/doc/scipy/reference/generated/scipy.stats.shapiro.html**

**https://statistics.laerd.com/spss-tutorials/testing-for-normality-using-spss-statistics.php**

**https://homework.study.com/explanation/what-is-the-shapiro-wilk-test-and-what-is-the-difference-between-the-levene-test.html**

**https://matplotlib.org/stable/gallery/subplots_axes_and_figures/subplots_demo.html**

**https://wires.onlinelibrary.wiley.com/doi/10.1002/widm.1318**

**https://machinelearningmastery.com/classification-versus-regression-in-machine-learning/**

**https://www.datacamp.com/tutorial/loss-function-in-machine-learning**

**https://cpatdowling.github.io/notebooks/regression_2**

**https://stats.stackexchange.com/questions/474738/how-do-i-intentionally-design-an-overfitting-neural-network**