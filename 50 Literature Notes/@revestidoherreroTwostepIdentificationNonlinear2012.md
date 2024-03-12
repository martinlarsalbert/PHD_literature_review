---
category: literaturenote
tags: System identification, Hypothesis testing, Nonlinear ship models, Prediction error methods, Regression analysis, Unscented Kalman filter, paper4
citekey: revestidoherreroTwostepIdentificationNonlinear2012
status: unread
dateread:
---

> [!Cite]
> Revestido Herrero, E., & Velasco González, F. J. (2012). Two-step identification of non-linear manoeuvring models of marine vessels. _Ocean Engineering_, _53_, 72–82. [https://doi.org/10.1016/j.oceaneng.2012.07.010](https://doi.org/10.1016/j.oceaneng.2012.07.010)

>[!Synth]
>**Contribution**:: 
>
>**Related**:: 
>

>[!md]
> **FirstAuthor**:: Revestido Herrero, Elías  
> **Author**:: Velasco González, Francisco J.  
~    
> **Title**:: Two-step identification of non-linear manoeuvring models of marine vessels  
> **Year**:: 2012  
> **Date**:: 2012-10-15  
> **Citekey**:: revestidoherreroTwostepIdentificationNonlinear2012  
> **itemType**:: journalArticle  
> **Journal**:: *Ocean Engineering*  
> **Volume**:: 53   
> **Pages**:: 72-82  
> **DOI**:: 10.1016/j.oceaneng.2012.07.010    

> [!link]-
> zotero_link:: [ScienceDirect Full Text PDF](zotero://select/library/items/HJ4PM4A5)


> [!Abstract]
>
> This paper presents the identification of non-linear ship manoeuvring models. It is a gray box approach in which some of the parameters of the models are known, and where a novel identification scheme for non-linear manoeuvring models based on two steps is proposed. In the first step, the structure of the model is selected using the stepwise method, and the parameters which present greater uncertainty are estimated. In the second step, a refinement of the estimates in the first step is carried out using a non-linear prediction error method with the unscented Kalman filter. As an application example, we consider a modern high-speed trimaran ferry using a full-scale trial and simulated data sets.
>.
> 
# Notes

| <mark class="hltr-grey">Highlight Color</mark> | Meaning                       |
| ---------------------------------------------- | ----------------------------- |
| <mark class="hltr-red">Red</mark>              | Disagree with Author          |
| <mark class="hltr-orange">Orange</mark>        | Important Point By Author     |
| <mark class="hltr-yellow">Yellow</mark>        | Interesting Point             |
| <mark class="hltr-green">Green</mark>          | Important To Me               |
| <mark class="hltr-blue">Blue</mark>            | Notes After Initial Iteration |
| <mark class="hltr-purple">Purple</mark>        | Literary Note To Lookup Later |

%% begin notes %%
- First thing
- Second thing
things to add each time you import:

%% end notes %%

>.
 
 Annotations
- <mark class="hltr-yellow">"system identification”</mark> [Page 1](zotero://open-pdf/library/items/HJ4PM4A5?page=1&annotation=7WS6C4BY) 
 
- <mark class="hltr-green">"gray box”</mark> [Page 1](zotero://open-pdf/library/items/HJ4PM4A5?page=1&annotation=WWFFQI3G) 
 
- <mark class="hltr-green">"The zig-zag test is not designed for system identification, so it may not have enough persistence of excitation for the number of parameters in the model. That is, the”</mark> [Page 1](zotero://open-pdf/library/items/HJ4PM4A5?page=1&annotation=6NI9ZT39) 
 
- <mark class="hltr-green">"persistence of excitation”</mark> [Page 1](zotero://open-pdf/library/items/HJ4PM4A5?page=1&annotation=AXTT7QVP) 
 
- <mark class="hltr-green">"pectral characteristics of excitation signals do not reach far enough to excite the system dynamics.”</mark> [Page 2](zotero://open-pdf/library/items/HJ4PM4A5?page=2&annotation=4ILMRBYD) 
 
- <mark class="hltr-yellow">"it is very important to perform an adequated model structure”</mark> [Page 2](zotero://open-pdf/library/items/HJ4PM4A5?page=2&annotation=2Q2D3AJN) 
 
- <mark class="hltr-yellow">"Due to the fact that the number of parameters in the model may be high, some of these might not be identifiable using the zig-zag test.”</mark> [Page 2](zotero://open-pdf/library/items/HJ4PM4A5?page=2&annotation=H64WRV5G) 
 
- <mark class="hltr-yellow">"EKF is not robust to uncertainty in the model”</mark> [Page 2](zotero://open-pdf/library/items/HJ4PM4A5?page=2&annotation=NBTYWFN6) 
 
- <mark class="hltr-yellow">"model structure”</mark> [Page 3](zotero://open-pdf/library/items/HJ4PM4A5?page=3&annotation=WPXXS8GP) 
 
- <mark class="hltr-yellow">"The parametric models in (5) provide a suitable set of models in which it can be assumed that a true model belongs”</mark> [Page 3](zotero://open-pdf/library/items/HJ4PM4A5?page=3&annotation=6JLS9GPT) 
 
- <mark class="hltr-yellow">"local polynomial fixed-point smoother”</mark> [Page 3](zotero://open-pdf/library/items/HJ4PM4A5?page=3&annotation=5823AQDF) 
 
- <mark class="hltr-red">"The derivation of the Jacobian matrices used in the linearization is not trivial in most applications and often causes some difficulties in its implementation.”</mark> [Page 6](zotero://open-pdf/library/items/HJ4PM4A5?page=6&annotation=Q38UZ6TN) 
 
	- Jacobian matrixes are calculated with SymPy 
 
- <mark class="hltr-yellow">"UKF”</mark> [Page 6](zotero://open-pdf/library/items/HJ4PM4A5?page=6&annotation=SXQVQEMU) 
 
- <mark class="hltr-yellow">"Kalman filter tuning”</mark> [Page 7](zotero://open-pdf/library/items/HJ4PM4A5?page=7&annotation=Y96Z5HLI) 
 
- <mark class="hltr-yellow">"That is, if we believe that the model is accurate, we lower the covariance of the state noise, which reduces the influence of noise on the estimates. However, if the model is believed to be uncertain, we need to increase the state covariance so the filter uses innovations ðyk  ^ yk9k 1Þ to correct the predictions made with the uncertain model this reduces bias and increase noise in the estimates.”</mark> [Page 7](zotero://open-pdf/library/items/HJ4PM4A5?page=7&annotation=CRJ8T4KZ) 
 
- <mark class="hltr-yellow">"prediction error methods”</mark> [Page 7](zotero://open-pdf/library/items/HJ4PM4A5?page=7&annotation=5AXZ84TY) 
 
- <mark class="hltr-yellow">"Monte Carlo study of 100 realizations using the trimaran data”</mark> [Page 7](zotero://open-pdf/library/items/HJ4PM4A5?page=7&annotation=UNJ93SCX) 
 
- <mark class="hltr-yellow">"PEM-UKF estimator”</mark> [Page 7](zotero://open-pdf/library/items/HJ4PM4A5?page=7&annotation=SRGIX7Z2) 
 
- <mark class="hltr-yellow">"persistence of excitation”</mark> [Page 8](zotero://open-pdf/library/items/HJ4PM4A5?page=8&annotation=L9TRU63E) 
 
![[80 Meta/81 Attachments/revestidoherreroTwostepIdentificationNonlinear2012/image-8-x42-y453.png]] 
 


%% Import Date: 2024-03-12T16:03:37.753+01:00 %%
