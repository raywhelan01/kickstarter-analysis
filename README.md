# kickstarter-analysis

Performing analysis on kickstarter data to uncover trends

### Module 1 Challenge

In this module's challenge we isolated the Kickstarter project dataset to analyze the subset of theatre projects in order to give Louise insights she can use to plan the launch of her own kickstarter project. I first looked at the outcomes of the kickstarter projects by the fundraising goal of each project to see what goal amounts had higher rates of success. Then, I analyzed the outcomes by the date of when each project launched to see when would be the optimal time for Louise to launch her project. Upon performing these analyses, several key insights were found:

<ol>
<li>For the play category, smaller fundraising goals ultimately led to higher chances of success. While the relationship isn't entirely linear, it is clear as shown <insert chart> that the more ambitious the fundraising goal the lower the chance of success.</li>
  
[Chart 1](https://github.com/raywhelan01/kickstarter-analysis/blob/master/Outcome%20by%20fundraising%20goal.png)
  
<li>However, there is one major caveat of note. While not shown in the chart, the number of projects launched rapidly diminishes as the fundraising goal increases. Thus, the statistical significance of this insight is in question as there may not be enough well-run high dollar value projects to forecast Louise's chances of success for her own project should she choose a higher rundraising goal.</li>
  
<li>Oddly, the play subcategory doesn't have a single canceled project out of more than 600. Some more analysis on why this is the case when most other project categories have a number of canceled campaigns could reveal additional insights to aid Louise.</li>

<li>In our second chart <insert here> we can see that the number of successful theater campaigns spikes dramatically in June. At first glance it seems as if June is the best time of the year to submit a fundraising project.</li>
  
[Chart 2](https://github.com/raywhelan01/kickstarter-analysis/blob/master/Outcome%20by%20Month.png)
  
<li>However, by changing the chart format to show each outcome likelihood as a percentage of all projects submitted for each month, we see that the summer spike is due more to the increased number of projects submitted during these months rather than the likelihood of a successful outcome. This new chart shows that there isn't a huge benefit to submitting the poject during one time of the year or another, except that it may be wise to avoid the month of december which does show a dramatic decrease in success rates.</li>

[Chart 3](https://github.com/raywhelan01/kickstarter-analysis/blob/master/Percent%20outcome%20by%20month.png)
</ol>
