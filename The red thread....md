![](https://www.staffanstorpshk.se/images/1271/37381/1272819.JPG)
Here are the the  papers and theses with me as first author till today:
```dataview  
TABLE
title as Title,  
itemType as Item,  
contribution as Contribution
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


