# data-science-project

## [Data visualization](https://github.com/azharctp/data-science-project/tree/main/Data_visualization)
### The datasets used for the visualization project are 
* **['State/UT-wise Accidents Classified According to Type of Traffic Violations during 2018'](https://data.gov.in/resource/stateut-wise-accidents-classified-according-type-traffic-violations-during-2018)** 
* **['Sub Divisional Monthly Rainfall from 1901 to 2017'](https://data.gov.in/resource/sub-divisional-monthly-rainfall-1901-2017)**

The analysis of the data was done by using different plots such as bar plots, line plots, scatter plots, and box plots. 

### Bar plot and line plot 
<br/><img src='/Data_visualization/plots/bar_line_plot.png'>
By analyzing the data, the numbers for the cases due to overspeeding are very high compared to others. So it is good to plot the same separately. From the above plot, it can be inferred that the number of accidents due to overspeeding is high in 6 states, crossing 20,000 cases. The number of injuries due to overspeeding is more than the number of cases in some states which shows that more than a single person was injured in some accidents, it can be co-passengers or third parties. In some states such as Bihar, and Punjab, the number of deaths to the total cases ratio is higher. The same is evident from the plot as the number of death pointers lies in the upper part of the bar representing a number of cases.  

### Line plot 
<br/><img src='/Data_visualization/plots/line_plot.png'>

In this plot, the number of deaths by accidents due to causes other than overspeeding is analyzed. The accidents caused by 'Jumping red light' have less death toll compared to others. The statistics of UP are alarming as the deaths due to three violations, 'drunken driving/consumption of alcohol & drug', 'driving on wrong side' and 'use of mobile phone' is very high even though overspeeding cases were less as seen previously. 'Driving on the wrong side' is a major cause of death in many states. This must be due to head-on collision due to traffic coming from the opposite direction which can be fatal.

### Scatter Plot
<br/><img src='/Data_visualization/plots/scatter_plot.png'>

The above scatter plot shows that certain states or UTs are ranked high in all cases and some others ranked low in all cases. This can be a reflection of the stringent and lenient following of traffic rules in those states. Ranking of overspeeding and driving on the wrong side goes in a similar trend in most cases.

### Box Plot

<br/><img src='/Data_visualization/plots/box_plot.png'>

The boxplot shows the rainfall for the period from June to September for South-Indian subdivisions. Coastal Karnataka receives the highest during the period followed by Kerala. The horizontal line represents the median and the green triangle represents the mean in the figure. Tamil Nadu receives the lowest rainfall among the subdivisions for the period.

## [Twitter sentiment analysis](https://github.com/azharctp/data-science-project/tree/main/Twitter_sentiment_analysis)
A total of 10,000 tweets containing equal subsets of positive and negative tweets were used in the analysis project. The model uses the data to train and classify unseen tweets into positive and negative tweets.

**Training and test accuracies at the end of training.**

Train accuracy at the end of training= 0.9932
Test accuracy = 0.9932

**Training and test accuracies at the end of training after removing 5 emoticons**

Training accuracy at the end after removing emoticons = 0.7284
Test accuracy after removing emoticons = 0.6892

Both test and training accuracies were reduced once the 5 emoticons were removed. This is due to the high weightage given to the emoticons while labeling the dataset. The emoticons are a kind of direct representation of the kind of tweet compared to individual word counts and removing them from the model training resulted in a defective model.

## Notes
======
Please pip install the specific requirements.txt before running the codes for the project.
