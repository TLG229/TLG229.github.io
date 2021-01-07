---
layout: post
title: Historical Whaling Analysis
subtitle: A look at how technological advances impacted whaling
cover-img: /assets/img/whale_strikes_back.PNG
thumbnail-img: /assets/img/whale_strikes_back.PNG
share-img: /assets/img/path.jpg
tags: [whales, history, analysis]
---
The history of humans hunting whales goes back thousands of years; however, industrial innovations in the late 19th century massively tipped the scales in favor of the hunter. These innovations mark the beginning of an unfortunate era when whaling took off with a vengeance leading to what is claimed to be by Calpham, Baker and Ivashchenko in their 2015 paper, "Emptying the Oceans", in terms of sheer biomass, “...one of the greatest wildlife exploitation episodes in human history”.[1]  They estimate that between 1900-1999 approximately 2.9 million whales were killed and processed as compared to 34,656 whales killed and processed calculated from historic records spanning from 1784 - 1900.  

The study attributes several innovations which contributed to these new found capabilties including the transition from sailing ships using rowboats and men with hand thrown harpoons to the introduction of the steam-powered whale catcher, the exploding harpoon gun, and improvements of shore-based factory processing.  These particular innovations were introduced between 1868 and the 1870's. Steam-powered whale catchers were being used by the 1860's, the final version of the exploding harpoon gun was perfected n 1869, and improvements in shore-based factory processing to a modern industry standard were well underway in the 1870's. Finally, whaling expanded to the Antarctic waters in 1904 with shore based factories being replaced predominantly with "floating factories" by the mid-1920's. [2] 
 
Historical whaling records were obtained from WhalingHistory.org which is a collaboration between the New Bedford Whaling Museum and Mystic Seaport Museum which developed the world’s most comprehensive whaling history database. The data combines many sources including logbooks, journals, ship registers, newspapers, business papers, and custom house records. This particular analysis used the American Offshore Whaling Voyage (AOWV) database which dates from 1784 - 1920 and includes 466,134 records.  

This analysis wants to compare the number of whales killed before the technological innovations to the number of whales killed after the technological innovations to see if they’re significantly different from each other. A two-sample t- test was used to compare the two phases.

Phase 0 - <1868 - No technological innovations.  Whalers used sailing ships, rowboats, and  hand thrown harpoons. 

Phase 1 - >1868 < 1920 -  From the advent of the exploding harpoon gun with the steam whaler and off-shore factory improvements until the advancements and predominant use of factory ships and hunting in the antarctic waters.


H0:  μPhase 1 = μPhase 0
H1:  μPhase 1 ≠ μPhase 0

First, a look at the distribution of the records.

Phase 0 - The historical record distribution of records from 1748 - 1868 


Footnotes

[1] Emptying the Oceans https://pdfs.semanticscholar.org/301b/305d818d375c69e478dd502c18b52e88cd82.pdf?_ga=2.60799791.387049218.1609997617-375080215.1609997617

[2] (Basber, B. n.d)https://www.cnrs-scrn.org/northern_mariner/vol08/nm_8_1_21-37.pdf
