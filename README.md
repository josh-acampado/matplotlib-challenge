# matplotlib-challenge

Overview; Included is an analysis of the performance of SCC drug, Capomulin. Within the notebook are various dataframes and graphs that reference the overall performance of Capomulin in comparison to other treatment regimens, as well as a control-placebo group.

General Observations of Data:

Capomulin could be considered one of the most successful drug regimens among this group. When compared to the control, the placebo, the average tumor volume of mice treated with Capomulin was lower by roughly 14 mm3. The data set also had a low variance, and standard deviation, meaning that the drug regimen is more likely to produce results in line with the test. Most other drugs, with the exception of one, stayed around the average weight of the placebo, plus or minus 2mm3.

The only other drug to perform as well as, if not better than, Capomulin was Ramicane. Upon reviewing the summary dataframe, one can see that Ramicane performs better in all categories, namely average tumor volume, variance, and standard deviation. In turn, this means that Ramicane produces a slightly larger reduction in tumor volume, and can be more consistent in the treatment. Upon reviewing the boxplots, while Capomulin appears to have a smaller IQR, Ramicane proves to be lower overall, having lower upper and lower whiskers, also visualizing the lower average tumor volume, represented by the orange lines on the box plot.

One thing to keep in mind when testing the drug regimen further, and to ultimately observe if the drug moves past the animal testing phase, is that the weight of the subject will correlate to the overall volume of the tumor. As seen in the scatter plot, there is a positive correlation between average tumor volume and mouse weight. When trying to garner more information, such as average tumor volume loss, it would be crucial to use a sample size where the average weight of the subject is relatively uniform to properly access the success rate of the drug. Alternatively, using two different weight groups would also prove to be a point of interest to compare the overall effects of the drug on different weights, or ultimately different BMIs.
