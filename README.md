# Hi! My name is Jordan Pappas. Welcome to my data science portfolio. 
I am an emerging data scientist/product manager trained in identifying strategic opportunities to provide business value, and I am driven to build data-driven stories to propel organizations forward. My academic research background is in health economics, and some of my pending publications are detailed below.


<br />


# [U.S. Oil & Gas Development Clustering (Pending Publication)](https://github.com/jordanjpappas/Oil_Gas_Cluster_Analysis)
“Stylized Trends in 21st Century US Onshore Oil and Gas Drilling Geography from Cluster Analysis.”

### Coauthors:
- Jordan Pappas, University of Rochester
- Richard DiSalvo, Princeton University

### Abstract:
<br /> The last two decades have witnessed revolutionary changes in America’s upstream oil and gas industry, with a meteoric rise in total production and a shift in where this production takes place. Many researchers have used the shift in the geographic location of drilling to study the effects of oil and gas development on local communities. In this paper we seek, to the extent possible, a stylized representation of this recent geographic shift. Specifically, we ask to what extent the timing of drilling across counties in the contiguous United States over the last two decades can be explained by places of old drilling versus places of new drilling, or if there are significant shares of additional categories of counties, e.g. places that have experienced both. 

To this end, we employ finite mixture models fit to data on county-level drilling shares by year. We find that two clusters reduce the sum of squared errors by about one third, while third and fourth clusters add only 7.5 and 5 percentage points additional explanatory power, respectively. Our main takeaway is that counties can be categorized into old versus new drilling, with relatively little room for additional typologies. Our approach allows us to spatially identify old drilling and new drilling counties, which we map and compare with well-known oil and gas fields.

### Technical Achievements:
- Study geographic development of oil and gas industry across US using cluster finite mixture models fit to county-level time series data.
- Imported natural gas data in CSV format containing 1 million rows. Write R scripts to clean data using packages like dplyr, reshape2, tidyverse.
- Apply machine learning algorithms such as finite mixture and clustering models using FlexMix package.
- Prepare research paper for publication using ggplot2, Microsoft Word.

### Figures:

![](/images/O&G-cluster_maps.png)
Figure 2: Maps of Drilling Counties by Cluster. Rows vary by the number of clusters in the model: the topmost row shows the one-cluster model, the middle row shows the two-cluster model, and the last row shows the three-cluster model. Columns vary by the cluster in which each county is classified. Thus, the first plot (top-left corner) highlights all counties in our analytic sample. The second row of plots splits counties into two clusters: early drilling (the left plot) and late drilling (the right plot). The third-row splits counties into three clusters: early drilling, middle drilling, and late drilling. Clusters are always ordered by the “peak year,” i.e. year of the maximum parameter.



<br /> 

--------------------------------------------------------------------------------------------------------------------------------------------------------------------

<br /> 



# [U.S. Drug-Related Disorders Data Visualization (Pending Publication)](https://github.com/jordanjpappas/Opioid_Dynamics)
“Dynamics in drug-related disorders from 1999-2018 in the U.S.”

### Coauthors:
- Jordan Pappas, University of Rochester
- Andrew Boslett, University of Rochester

### Abstract:
<br /> The U.S. is currently in the midst of a drug overdose epidemic. In 2018, 3.6% of the U.S. population misused prescription pain relievers, and there were 67,376 drug overdose deaths, more than X times the count in 1999. As the scale of the epidemic has grown, there has been a corresponding increase in the academic literature on drug overdose deaths, with studies highlighting trends in drug overdoses across time and space and characteristics of drug overdose decedents. 

Yet, drug overdose deaths are only a fraction of all deaths associated with drug use. People die from drug-related disorders, which reflect long-term addiction and behavior change due to drug use. In this paper, we fill a gap in the literature by describing trends in drug-related disorders in the U.S. from 1999 to 2018. We identify trends nationally and by state, focusing on areas with large relative changes in deaths involving drug-related disorders over time. We examine trends in drug-related disorders by drug class, with a particular focus on opioid-related disorders. We describe demographic and socio-economic characteristics of decedents of drug-related disorders and compare them to those of decedents from drug overdoses. 

### Technical Achievements:
- Examine drug abuse in non-drug overdose deaths in US mortality database from 1999 – 2018.
- Collected CDC mortality dataset in RDS format containing 200,000 rows. Cleaned in R using packages like dplyr, reshape2, tidyverse.
- Estimate from data analysis suggests severity of drug abuse in non-drug overdoses from 1999 to 2018 was 20% higher than current estimates.
- Prepare research paper for publication using ggplot2, LaTeX.

### Figures:

![](/images/OP-overdose_and_disorder_trends.png)
Figure 1: Trends in deaths from drug overdoses and drug-related disorders from 1999-2018. Notes: In this figure, we display the annual number of deaths from drug overdoses and drug-related disorders from 1999-2018. These estimates are based on National Center for Health Statistics’ Multiple Cause of Death Data. 
