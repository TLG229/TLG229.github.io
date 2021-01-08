---
layout: post
title: Historical Whaling Analysis
subtitle: A look at how technological advances impacted whaling
cover-img: /assets/img/whale_strikes_back.PNG
thumbnail-img: /assets/img/whale_strikes_back.PNG
share-img: /assets/img/path.jpg
tags: [whales, history, analysis]
---
The history of humans hunting whales goes back thousands of years; however, industrial innovations in the late 19th century massively tipped the scales in favor of the hunter. These innovations mark the beginning of an unfortunate era when whaling took off with a vengeance leading to what is claimed to be by Calpham, Baker and Ivashchenko in their 2015 paper, ["Emptying the Oceans",](https://pdfs.semanticscholar.org/301b/305d818d375c69e478dd502c18b52e88cd82.pdf?_ga=2.60799791.387049218.1609997617-375080215.1609997617) in terms of sheer biomass, “...one of the greatest wildlife exploitation episodes in human history”. They estimate that between 1900-1999 approximately 2.9 million whales were killed and processed as compared to 34,656 whales killed and processed calculated from historic records spanning from 1784 - 1900.  

The study attributes several innovations which contributed to these new found capabilties including the transition from sailing ships and rowboats using men with hand thrown harpoons to the introduction of the steam-powered whale catcher, the advent of exploding harpoon gun, and improvements of shore-based factory processing.  These particular innovations were introduced between 1868 and the 1870's. Steam-powered whale catchers were being used by the 1860's, the final version of the exploding harpoon gun was perfected n 1869, and improvements in shore-based factory processing to a modern industry standard were well underway in the 1870's. Finally, whaling expanded to Antarctic waters in 1904 with shore based factories being replaced predominantly with "floating factories" by the mid-1920's. [[2]](https://pdfs.semanticscholar.org/301b/305d818d375c69e478dd502c18b52e88cd82.pdf?_ga=2.60799791.387049218.1609997617-375080215.1609997617) 
 
Historical whaling records were obtained from [Whalinghistory.org](https://whalinghistory.org/av/) which is a collaboration between the New Bedford Whaling Museum and Mystic Seaport Museum which developed the world’s most comprehensive whaling history database. The data combines many sources including logbooks, journals, ship registers, newspapers, business papers, and custom house records. This particular analysis used the American Offshore Whaling Voyage (AOWV) database which dates from 1784 - 1920 and includes 466,134 records.  

This analysis compares the number of whales killed before the technological innovations to the number of whales killed after the technological innovations to see if they’re significantly different from each other. A two-sample t- test was used to compare the two phases.

Phase 0 - <1868 - No technological innovations.  Whalers used sailing ships, rowboats, and  hand thrown harpoons. 

Phase 1 - >1868 < 1920 -  From the advent of the exploding harpoon gun with the steam whaler and off-shore factory improvements until the advancements and predominant use of factory ships and hunting in the antarctic waters.


H0:  μPhase 1 = μPhase 0<br /> 
H1:  μPhase 1 ≠ μPhase 0

First, a look at the distribution of the records.

**Phase 0 - The historical record distribution of records from 1748 - 1868**

Median = 1844 <br /> 
IQR = 9 <br />
Q1= 1840   <br /> 
Q3= 1849  <br /> 

![image](/assets/img/record dist LT 1868.PNG)

**Phase 1 - The historical record distribution > 1868 to < =1920**

Median = 1887 <br /> 
IQR = 18 <br/>
Q1= 1878 <br /> 
Q2= 1896 <br /> 

![image](/assets/img/record dist GT 1868.PNG)

**The Distribution of Whales Tried <br />

The vast amount of records report 0 whales are killed or “tried”.  The maximum shown here is 10 however the original dataset has as many as 17 tries reported however anything greater than 10 was determined to be an outlier. As you can see, the data is skewed right.

![image](/assets/img/num whales tried.PNG)

**Frequency of the Types of Encounters<br />

Additionally, the vast amount of encounters were 'No Encounters', followed by Sightings and then, Strikes or kills. If a whale was sighted, there was a 64% chance of a strike.

![image](/assets/img/encounter frequency.PNG)

**Visualizations of Whales Tried Over Time <br />

This shows the two separate time periods I want to compare and the trend line which is moving up in the > 1868 phase.

![image](/assets/img/whales tried over time by period.PNG)

And this is what is looks like as a continuous line plot...

![image](/assets/img/whales tried over time line plot.PNG)

While visually it looks like the trend is increasing during the second phase of whaling after 1868 is it statistically significant? <br/>

**Two Sample T-test

When performing a 2 sample t-test the p value = 0.0 therefore H0 is rejected and Phase 1 ≠ Phase 2 indicating that the two phases are significantly different.






