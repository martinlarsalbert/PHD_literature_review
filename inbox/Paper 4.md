
```todoist
name: PhD ToDo
filter: "#PhD"
```

## Literature review
Did the following search on [scopus](https://www-scopus-com.proxy.lib.chalmers.se/search/form.uri?display=basic#basic):
````
ship AND ( manoeuvring OR maneuvering ) AND experiment AND identification
````
Also extended the search with [researchrabbit](https://researchrabbitapp.com/home) "Similar work".

```dataview  
TABLE
title as Title,  
year as Year
WHERE contains(tags, "paper4")
SORT Year ASC, Date ASC
```

## Read papers
[[@skjetneNonlinearShipManoeuvering2004]]
[[@sutuloAlgorithmOfflineIdentification2014]]
[[@luoParameterIdentificationShip2016]]
[[@revestidoherreroTwostepIdentificationNonlinear2012]]

## Summary
To obtain the maneuvering parameters, such as advance, transfer, and overshoots, three ways are available [Page 1](zotero://open-pdf/library/items/FVV4DHGM?page=1&annotation=IKCZG5PR) :
* no-simulation, which refers to the database method, full-scale trial, or free-running model test. 
* systembased maneuvering simulation, in which the database method, empirical formulas, captive model test, computational methods, and [[system identification]] combined with full-scale trials or free-running model tests can be adopted. 
* CFD based maneuvering simulation

Adequacy of the core manoeuvring mathematical also can only be reached approximately: even the validation itself may present problems especially when it goes about the full model including effects of the hydrodynamic interactions, response to gusty wind and sea waves [[@hensenShipBridgeSimulators1999]] [Page 1](zotero://open-pdf/library/items/WD85S9FS?page=1&annotation=CABW2ILM) 

But this still does not make simple the task of creation of an adequate mathematical model even when the full-scale data are accurate and reliable (which is rarely the case!). [Page 1](zotero://open-pdf/library/items/WD85S9FS?page=1&annotation=CEWCAK57) 

All practical manoeuvring mathematical models are highly schematised and although in principle can be tuned to provide a satisfactory reproduction of the true motion, there are no simple theoretical methods for estimating their parameters. [Page 1](zotero://open-pdf/library/items/WD85S9FS?page=1&annotation=3ZQ4AKCD) 

Most modern ship mathematical models can be called “physical” or—to be more precise—“mechanical” as they are based on principles and equations of classic mechanics. [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=5DELC56Q) 

It is relatively simple to measure full scale kinematical parameters during the motion resulting from some well-defined steering programme. [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=AR2JWJJF)

[[parameter identification]]

It was discovered very soon that the problem of identifying parameters of a rather complex and realistic ship manoeuvring model is ==ill-posed== and at high noise levels typical for the sea trials data heavily biased estimates and, as result, useless models could be obtained. [[@abkowitzMEASUREMENTHYDRODYNAMICCHARACTERISTICS1980]] was only able to fight the observed cancellation effect through elimination of “inconvenient” terms which, however, could lead to models with limited applicability as certain regression terms may only become significant in special conditions ==like sailing in wind==. [Page 2](zotero://open-pdf/library/items/WD85S9FS?page=2&annotation=GK38AL6F) 

[[optimized pseudo-random binary sequences]]

<mark class="hltr-yellow">"The Hausdorff metric”</mark> [Page 5](zotero://open-pdf/library/items/WD85S9FS?page=5&annotation=K53ERRGZ) 

[[persistence of excitation]]

Any uncertainties in the initial conditions of the velocities will result in unlimited growth of deviations from the true trajectory and from the true heading angle values. For instance, in the latter case the error grows linearly i.e. as δψ0t, where δψ0 is the error in the initial condition for the heading. [Page 6](zotero://open-pdf/library/items/WD85S9FS?page=6&annotation=RNB2JZ7F) 
Exclude all generalized coordinates from the observation vector, so that only $r,u,v,delta$ are considered [Page 7](zotero://open-pdf/library/items/WD85S9FS?page=7&annotation=34QZL9UL) 

[[difference method]]
[[system identification]]
[[extended Kalman filter]]
[[unscented Kalman filter]]
[[what is a model]]
[[fossen]]
