This lead to the paper "Analysis of roll damping model scale data" [[@alexanderssonAnalysisRollDamping2021]]. A roll damping database was assembled, to train the ML model. 

System identification was used to identify an appropriate ==mathematical model== for the roll motion dynamics. A linear, quadratic, or cubic model where attempted as described in the differential equations below.

![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-3-x383-y488.png|200]] 

![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-3-x359-y467.png|300]] 
 	 
![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-3-x369-y409.png|300]] 
### Inverse dynamics regression
Two different parameter identification techniques were attempted to identify the damping terms $B_{(\bullet)}$, where the so called "derivation approach" turned out to be the best. In this approach the differential equations of the models are just treated as a linear regression problem. The identification technique was later referred to as ==inverse dynamics (ID) regression==. 

> [!note] > A problem with ID is that the whole state of the system must be known; In this case the roll angle including its first and second time derivatives ($\theta,\dot{\theta},\ddot{\theta}$ ) must be known, which is often not the case for model test or ship operational data.

The quadratic model was found to describe the roll motion dynamics with sufficient accuracy.
![[80 Meta/81 Attachments/alexanderssonAnalysisRollDamping2021/image-4-x322-y65.png]] 

> [!note] > The process to find the appropriate mathematical model and to identify the parameters within it is referred to as ==system identification==. With the mathematical model defined, the parameters are found with ==parameter identification==.

### Physics informed models
Semi-empirical calculations with the simplified Ikeda's (SI) method proposed by  [[@kawaharaSimplePredictionFormula2011a]] was conducted with the aim to blend it with ML to form a ==physics informed model==. This did not work in this first paper, mainly because the SI method was not giving good predictions. Since most of the ships in the database had larger beam to draught ratios, outside the limits of the method. This was identified as a problem with this method, which was left for future work – which I have not addressed in this research.
> [!note] > The physics informed model can also be referred as a ==grey box== model, but physics informed model is probably a more accurate description, since grey box model has a broader definition. [[@ljungPerspectivesSystemIdentification2010]]
> <mark class="hltr-green">"This means that it is beneficial to shrink the model set as much as possible using physical (or other) insights into the nature of the object.”</mark> [Page 5](zotero://open-pdf/library/items/MSAWPCSS?page=5&annotation=AM2M7TBQ) 
