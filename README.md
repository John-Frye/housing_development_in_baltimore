# Housing Development: Assessing Opportunity Zones in Baltimore, MD 
## Background Information 
In West Baltimore’s historic Harlem Park neighborhood, where 96.9% of the total population are Black or African American, [one out of every three houses are vacant and abandoned](https://health.baltimorecity.gov/sites/default/files/47%20Sandtown.pdf). Harlem's Park's urban blight results from Baltimore's [long history of "red-lining,"](https://www.npr.org/2018/08/07/632497683/in-baltimore-the-gap-between-white-and-black-homeownership-persists) where mortgage loan companies excluded predominantly black neighborhoods from mortgage relief in the wake of the Great Depression. This practice led to de facto racial and economic segregation that persists in the form of Baltimore's "Black Butterfly." Neighborhoods in this area feature high rates of home abandonment and poor infrastructure, which contribute to [many social inequities](https://journalistsresource.org/studies/government/municipal/abandoned-buildings-revitalization/) like rampant crime, drug abuse, and limited economic and social mobility. To alleviate this issue, the federal government passed the 2017 Tax Cuts and Jobs Act to heavily reduce income taxes and bolster capital flow into the poorest areas of the country. The legislation created [the Opportunity Zones initiative](https://taxfoundation.org/final-tax-cuts-and-jobs-act-details-analysis/#:~:text=The%20Tax%20Cuts%20and%20Jobs%20Act%20would%20reform%20the%20individual,and%20simplifying%20the%20tax%20code). Areas within Baltimore that are in need of commercial investment are designated as an “Opportunity Zone,” and investors are guaranteed tax benefits when they funnel their cash into community funds that finance community housing projects and local businesses.

## Problem Statement
How successful are Opportunity Zones in Baltimore at stimulating economic growth without contributing to gentrification, and what additional risk factors can we focus on to improve the effectiveness of such government initiatives? 

## Data Questions
Which metrics of housing development are statistically significant in regards to percent-nonwhite (an indicator of neighborhoods within the Black Butterfly)? Does private investment decrease mortgage affordability in Baltimore? What impact have Opportunity Zones had on metrics of housing development? 

## Data Sources


## Data Answer 
While many of the data analysis’ variables are not statistically significant when compared to race, the metric used to gauge neighborhoods in the black butterfly, many of the variables are statistically significant and correlated when compared directly to one another. Mortgage Affordability and Average Small Business Investment share a correlation of -0.27, meaning that mortgage affordability decreases on average when small business investment increases. This correlation is statistically significant, having a p-value of 0.007. The relationship between mortgage affordability and small business investment in Baltimore is modeled below:

![alt_text](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/Screen%20Shot%202020-12-16%20at%202.33.18%20PM.png)

The negative correlation between small business investment and mortgage affordability highlights how gentrification could present an issue for the Opportunity Zones’ development track. Notably, mortgage affordability has a correlation of 0.6 with percent non-white, meaning that non-white neighborhoods in their current state have more affordable mortgages. This finding supports long-held beliefs that Baltimore’s redlining practices segregated largely black populations into areas that, consequently, experienced low real estate values. Mortgage affordability is interestingly more prevalent in lower income neighborhoods. Again, this fact highlights that low income, black populations are vulnerable to gentrification’s sudden price rises.

Furthermore, fast commute times are negatively correlated at -0.3 with percent non-white, meaning that predominantly non-white neighborhoods experience longer commute times. Given the -0.5 correlation between percent non-white and household income in Baltimore, this finding aligns with previous analysis on the link between long commute times and lower household income. 

The multiple regression model and cluster analysis confirmed the statistical significance and validity of the datasets relevant to housing and community development. To evaluate the effectiveness of Opportunity Zones, we can look at data trends of each variable before and after the implementation of the program in 2017 to determine whether or not the increase in private investment in these Zones are fueling economic growth. 

![alt_text](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/mortgage_affordability.png)

Mortgage affordability decreased by roughly 0.5% after the implementation of opportunity zones. Because this decrease follows a trend of decreasing affordability over time, we cannot derive any conclusions as to whether or not Opportunity Zones themselves are responsible for the trend. As mentioned, mortgage affordability is negatively correlated to small business investment. Declining mortgage affordability is certainly a risk created by opportunity zones, but we cannot conclude if opportunity zones’ investment packages have made a significant impact on mortgage as of yet. 

![alt_text](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/household_income.png)

The steady upward trendline for average household income is a promising indicator of growing capital flow and business opportunities within Opportunity Zones. 

![alt_text](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/Commute_Times.png)

The percentage of workers with low commute times has also decreased in Baltimore since 2018. The consistent decrease in the percentage of low commute times prior to 2017 indicates that the Opportunity Zones are not likely responsible for a rise in commute length. However, they have not stabilized or reversed the trend of lengthening commute times. 

![alt_text](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/Owner_Occupied.png)

In recent years, the percentage of owner-occupied houses in Baltimore has been decreasing. After the implementation of Opportunity Zones, the percentage has plateaued. We therefore cannot derive any conclusions from this finding, as there is no clear indication that Opportunity Zones have stabilized the number of homeowners living in their own properties. 

Data before and after the Opportunity Zones initiative is inconclusive on whether private investment in these areas contributed to the improvement in housing and neighborhood vitality. Although we observe a steady increase in average household income, there are no consistent trendlines for the remaining variables. A possible explanation for this, and an important point to note, is that efforts in community development programs need to be sustained over long periods of time for us to observe a substantial change in data trends. Baltimore’s poorest neighborhoods struggle with crime, drug use, inadequate healthcare, etc., and all of these issues are connected to the city’s failing infrastructure. 

In addition, the variables of interest in our data analysis not capturing the successes or shortcomings of Opportunity Zones is most likely due to the limited open datasets available for analysis. Datasets examining rates of commercial lending, mortgage loans, and private investments in each neighborhood would have given more insight into economic activity and cash inflows.  

Of note, none of our identified target areas in Cluster 3 overlapped with any Opportunity Zones, despite their low standards of living. 

## Final Recommendations 

A comprehensive overview of our recommendations [can be accessed here](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/Recommendation_Frye_Tien.pdf). A condensed version of our recommendations....


![alt_text](https://github.com/John-Frye/housing_development_in_baltimore/blob/main/Screen%20Shot%202020-12-16%20at%205.18.34%20PM.png)
