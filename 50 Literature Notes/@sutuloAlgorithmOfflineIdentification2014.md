---
category: literaturenote
tags: System identification, Ship manoeuvrability, White noise, Genetic algorithm, Hausdorff's metric, Mathematical model, paper4
citekey: sutuloAlgorithmOfflineIdentification2014
status: unread
dateread:
---

> [!Cite]
> Sutulo, S., & Guedes Soares, C. (2014). An algorithm for offline identification of ship manoeuvring mathematical models from free-running tests. _Ocean Engineering_, _79_, 10–25. [https://doi.org/10.1016/j.oceaneng.2014.01.007](https://doi.org/10.1016/j.oceaneng.2014.01.007)

>[!Synth]
>**Contribution**:: 
>
>**Related**:: 
>

>[!md]
> **FirstAuthor**:: Sutulo, Serge  
> **Author**:: Guedes Soares, C.  
~    
> **Title**:: An algorithm for offline identification of ship manoeuvring mathematical models from free-running tests  
> **Year**:: 2014  
> **Date**:: 2014-03-15  
> **Citekey**:: sutuloAlgorithmOfflineIdentification2014  
> **itemType**:: journalArticle  
> **Journal**:: *Ocean Engineering*  
> **Volume**:: 79   
> **Pages**:: 10-25  
> **DOI**:: 10.1016/j.oceaneng.2014.01.007    

> [!link]-
> zotero_link:: [ScienceDirect Full Text PDF](zotero://select/library/items/WD85S9FS)


> [!Abstract]
>
> An identification algorithm for ship manoeuvring mathematical models has been developed. The identification procedure is based on the classic genetic algorithm used for minimizing a distance between the reference and recovered time histories. The distance was measured using 5 different metrics including the Hausdorff metric. Validation of the algorithm was carried out using simulated responses artificially polluted with the white noise of various levels. It was demonstrated that by only using the Hausdorff metric it was possible to reach necessary robustness of the identification algorithm.
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
- <mark class="hltr-yellow">"Adequacy of the core manoeuvring mathematical also can only be reached approximately: even the validation itself may present problems especially when it goes about the full model including effects of the hydrodynamic interactions, response to gusty wind and sea waves (Hensen, 1999)”</mark> [Page 1](zotero://open-pdf/library/items/WD85S9FS?page=1&annotation=CABW2ILM) 
 
- <mark class="hltr-green">"But this still does not make simple the task of creation of an adequate mathematical model even when the full-scale data are accurate and reliable (which is rarely the case!).”</mark> [Page 1](zotero://open-pdf/library/items/WD85S9FS?page=1&annotation=CEWCAK57) 
 
- <mark class="hltr-yellow">"All practical manoeuvring mathematical models are highly schematised and although in principle can be tuned to provide a satisfactory reproduction of the true motion, there are no simple theoretical methods for estimating their parameters.”</mark> [Page 1](zotero://open-pdf/library/items/WD85S9FS?page=1&annotation=3ZQ4AKCD) 
 
- <mark class="hltr-yellow">"Due to various reasons, most modern ship mathematical models can be called “physical” or—to be more precise—“mechanical” as they are based on principles and equations of classic mechanics.”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=5DELC56Q) 
 
- <mark class="hltr-yellow">"ANN algorithms may have certain advantages as they do not imply any a priori structure of the ship mathematical model. But the absence of any physical ground behind the ANN model represents, at the same time, a natural disadvantage of ANN models as they cannot be extended, modified or tuned without full retraining which is not always possible.”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=JFXL8ZMB) 
 
- <mark class="hltr-yellow">"At the same time, it is relatively simple to measure kinematical parameters during the motion resulting from some well-defined steering programme.”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=AR2JWJJF) 
 
- <mark class="hltr-yellow">"If the structure of the mathematical model is established a priori, just the values of the parameters of the model are to be estimated and it goes then about the parametric identification”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=3PWIHKS6) 
 
- <mark class="hltr-yellow">"Often the models are tuned manually before being implemented in bridge simulators although such approaches are rarely even mentioned in the literature.”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=DNXK4ZLS) 
 
- <mark class="hltr-yellow">"According to Ljung and Söderström (1983) “the offline identification is the determination of a model of a system using a batch of measured data where the whole batch is available at all stages of the procedure””</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=WLQMV5MS) 
 
- <mark class="hltr-yellow">"the online identification presumes the measuring and identification processes running in parallel though typically with a certain lag of the latter”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=MZXK7QWZ) 
 
- <mark class="hltr-green">"It was discovered very soon that the problem of identifying parameters of a rather complex and realistic ship manoeuvring model is ill-posed and at high noise levels typical for the sea trials data heavily biased estimates and, as result, useless models could be obtained. Abkowitz (1980, 1988) was only able to fight the observed cancellation effect through elimination of “inconvenient” terms which, however, could lead to models with limited applicability as certain regression terms may only become significant in special conditions like sailing in wind.”</mark> [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=GK38AL6F) 
 
- <mark class="hltr-yellow">"two-step method”</mark> [Page 3](zotero://open-pdf/library/items/WD85S9FS?page=3&annotation=YXY57EHI) 
 
- <mark class="hltr-yellow">"a 20–20 zigzag with the 35 turn was not rich enough to guarantee reliable estimation of all regression coefficients and optimized pseudo-random binary sequences were suggested as alternative”</mark> [Page 3](zotero://open-pdf/library/items/WD85S9FS?page=3&annotation=XWCT4ACQ) 
 
![[80 Meta/81 Attachments/sutuloAlgorithmOfflineIdentification2014/image-5-x301-y351.png]] 
 
- <mark class="hltr-yellow">"The Hausdorff metric”</mark> [Page 5](zotero://open-pdf/library/items/WD85S9FS?page=5&annotation=K53ERRGZ) 
 
- <mark class="hltr-green">"sufficiently informative for reliable estimation of all parameters of interest. Ideally, the phase trajectories resulting from such manoeuvres should fill some sufficiently large domain in the state space but it is practically impossible to achieve with the standard means of control”</mark> [Page 5](zotero://open-pdf/library/items/WD85S9FS?page=5&annotation=W99D4YG3) 
 
- <mark class="hltr-green">"Some impression about informative power of these manoeuvres can be obtained from the projections of the phase trajectories on the plane β  r0”</mark> [Page 5](zotero://open-pdf/library/items/WD85S9FS?page=5&annotation=JXGQ44I7) 
 
- <mark class="hltr-yellow">"It is clear from Eq. (1) that any uncertainties in the initial conditions of the velocities will result in unlimited growth of deviations from the true trajectory and from the true heading angle values. For instance, in the latter case the error grows linearly i.e. as δψ0t, where δψ0 is the error in the initial condition for the heading.”</mark> [Page 6](zotero://open-pdf/library/items/WD85S9FS?page=6&annotation=RNB2JZ7F) 
 
![[80 Meta/81 Attachments/sutuloAlgorithmOfflineIdentification2014/image-6-x46-y276.png]] 
 
- <mark class="hltr-yellow">"Exclude all generalized coordinates from the observation vector.”</mark> [Page 7](zotero://open-pdf/library/items/WD85S9FS?page=7&annotation=34QZL9UL) 
 
- <mark class="hltr-yellow">"The third option was followed in the present study which means that two manoeuvring mathematical models are considered close to each other when during any manoeuvre close are time histories for the rudder angle, velocities of surge and sway and for the rate of yaw”</mark> [Page 7](zotero://open-pdf/library/items/WD85S9FS?page=7&annotation=KA9XYCRG) 
 
- <mark class="hltr-yellow">"the Hausdorff metric seems to be a rather natural measure of the distance between sets of values of two functions and it found wide applications in computer vision”</mark> [Page 15](zotero://open-pdf/library/items/WD85S9FS?page=15&annotation=34DUM5II) 
 


%% Import Date: 2024-03-12T09:24:48.283+01:00 %%
