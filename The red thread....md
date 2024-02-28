![](https://www.staffanstorpshk.se/images/1271/37381/1272819.JPG)
Here are the the  papers and theses with me as first author till today:
```dataview  
TABLE
title as Title,  
itemType as Item,  
contribution as Contribution,
year as Year
WHERE FirstAuthor = "Alexandersson, Martin" AND itemType != "dataset"  
SORT Year ASC, Date ASC
```
The following datasets have also been published:
```dataview  
TABLE
title as Title,  
itemType as Item,  
contribution as Contribution  
WHERE FirstAuthor = "Alexandersson, Martin" and itemType = "dataset"  
SORT Date ASC
```

The licentiate thesis [[@alexanderssonTHESISDEGREELICENTIATE2022]] consisted of the following to papers:
```dataview  
TABLE
title as Title,  
itemType as Item,  
contribution as Contribution  
WHERE contains(tags, "lic_paper")  
SORT Year Asc, Date ASC
```

# Summary
Machine learning (ML) was a very hot topic when this PhD project started in January 2020. My initial hypothesis was that if we could just gather enough data – fantastic prediction models could be created with ML. I also realized that I was in a very good position to do it – having worked almost 10 years gathering and analysing dynamic time series data from the maritime dynamics laboratory (MDL) at the RISE SSPA Maritime Center. The objective was to build ML prediction models of the ship dynamics, addressing the whole seakeeping and manoeuvring problem. It was however decided to start with something simpler, only focusing on one degree of freedom – roll. This lead to the paper "Analysis of roll damping model scale data" [[@alexanderssonAnalysisRollDamping2021]]. A roll damping database was assembled, to train the ML model. 

System identification was used to identify an appropriate model for the roll motion dynamics. A linear, quadratic, or cubic model where attempted as described in the differential equations below.

![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-3-x383-y488.png|200]] 

![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-3-x359-y467.png|300]] 
 	 
![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-3-x369-y409.png|300]] 
Different parameter identification techniques were attempted to identify the damping terms $B_{(\bullet)}$, where the so called "derivation approach" turned out to be the best. In this approach the differential equations of the models are just treated as a linear regression problem. The quadratic model was found to describe the roll motion dynamics with sufficient accuracy.

![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-4-x322-y65.png]] 
A side result from this paper was that the simplified formula proposed by  [[@kawaharaSimplePredictionFormula2011a]] was found to not work for larger beam to draught ratios, which unfortunately included most of the ships in the gathered database.


