![](https://www.staffanstorpshk.se/images/1271/37381/1272819.JPG)
This note is describing the "read thread" through my PhD research.

Here are the the papers and theses with me as first author till today:
```dataview  
TABLE
title as Title,  
itemType as Item,  
year as Year,
contribution as Contribution
WHERE FirstAuthor = "Alexandersson, Martin" AND itemType != "dataset"  
SORT Year ASC, Date ASC
```
---

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
Machine learning (ML) was a very hot topic when this PhD project started in January 2020. My initial hypothesis was that if we could just gather enough data – fantastic prediction models could be created with ML. I also realized that I was in a very good position to do it – having worked almost 10 years gathering and analysing dynamic time series data from the maritime dynamics laboratory (MDL) at the RISE SSPA Maritime Center. The objective was to build ML prediction models of the ship dynamics, addressing the whole seakeeping and manoeuvring problem. It was however decided to start with something simpler, only focusing on one degree of freedom – roll. 

> [!Info]  
>> [[system identification]] was first intended as a "quick" intermediate step, to build databases toward the ML endeavours, but turned out to be the direction or "red thread" of the entire PhD project. 

Structure and workflow of the appended papers to achieve the thesis objectives.
```mermaid
flowchart TD
    Paper1[Paper 1] --> B(Handle noise)
    Paper1 --> C(System identification)
    Paper1 --> Paper15(Paper1.5)

    B --> Paper2[Paper 2]
    C --> Paper2

    Paper2 --> Multicollinearity(Multicollinearity) --> Generalization(Generalization)
    Generalization --> Paper3[Paper 3] --> PI(Physics informed model)
    experiments(New tests?) --> 7mdata(Field study tests)
 

    7mdata(Field study tests) --> Paper4[Paper 4]
    PI --> Paper4
    differenceMethod(Difference method?) --> Paper4
    PCA(PCA) --> Paper4
    Blackbox(Blackbox) --> Paper4

    Multicollinearity --> differenceMethod
    Multicollinearity --> PCA
    Multicollinearity --> Blackbox
```

[[Paper 1 Analysis of roll damping model scale data]]
Paper 1.5? [[@alexanderssonPredictionRollMotion2021]]
[[Paper 2 System identification of Vessel Manoeuvring Models]]
[[Paper 3 System identification of a physics informed ship model for better predictions in wind conditions]]
[[Paper 4]]

[[DEMOPS meetings]]
```mermaid
gantt

dateFormat  YYYY-MM-DD

title PhD plan

section Thesis
90% Thesis           :active,   2024-03-13,2024-09-01
Apply                :          2024-09-01, 1d
Send to opponent     :          2024-10-01, 1d
Waiting              :          2024-10-01, 2024-11-01
Feedback             :          2024-11-01, 1d
Print                :          2024-11-25, 1d
D-day                :          2024-12-18, 1d

section Paper 4
SI field study test  :active,   2024-03-13,2024-06-01
Writing              :active,   2024-06-02,2024-06-24

```

```todoist
name: PhD ToDo
filter: "#PhD"
```

