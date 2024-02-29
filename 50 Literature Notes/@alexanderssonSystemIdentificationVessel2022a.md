---
category: literaturenote
tags:
  - Extended
  - Kalman
  - filter
  - Inverse
  - dynamics
  - Multicollinearity
  - RTS
  - smoother
  - Ship
  - manoeuvring
  - System
  - identification
  - lic_paper
citekey: alexanderssonSystemIdentificationVessel2022a
status: unread
dateread:
---

> [!Cite]
> Alexandersson, M., Mao, W., & Ringsberg, J. W. (2022). System identification of Vessel Manoeuvring Models. _Ocean Engineering_, _266_, 112940. [https://doi.org/10.1016/j.oceaneng.2022.112940](https://doi.org/10.1016/j.oceaneng.2022.112940)

>[!Synth]
>**Contribution**:: 
>
>**Related**:: 
>

>[!md]
> **FirstAuthor**:: Alexandersson, Martin  
> **Author**:: Mao, Wengang  
> **Author**:: Ringsberg, Jonas W.  
~    
> **Title**:: System identification of Vessel Manoeuvring Models  
> **Year**:: 2022  
> **Date**:: 2022-12-15  
> **Citekey**:: alexanderssonSystemIdentificationVessel2022a  
> **itemType**:: journalArticle  
> **Journal**:: *Ocean Engineering*  
> **Volume**:: 266   
> **Pages**:: 112940  
> **DOI**:: 10.1016/j.oceaneng.2022.112940    

> [!link]-
> zotero_link:: [Full Text](zotero://select/library/items/AHWM4AXI)


> [!Abstract]
>
> Identifying the ship’s maneuvering dynamics can build models for ship maneuverability predictions with a wide range of useful applications. A majority of the publications in this field are based on simulated data. In this paper model test data is used. The identification process can be decomposed into finding a suitable manoeuvring model for the hydrodynamic forces and to correctly handle errors from the measurement noise. A parameter estimation is proposed to identify the hydrodynamic derivatives. The most suitable manoeuvring model is found using the parameter estimation with cross-validation on a set of competing manoeuvring models. The parameter estimation uses inverse dynamics regression and Extended Kalman filter (EKF) with a Rauch Tung Striebel (RTS) smoother. Two case study vessels, wPCC and KVLCC2, with very different maneuverability characteristics are used to demonstrate and validate the proposed method. Turning circle predictions with the robust manoeuvring models, trained on zigzag model tests, show good agreement with the corresponding model test results for both ships.
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
- See further notes in [[Paper 2 System identification of Vessel Manoeuvring Models]]
things to add each time you import:

%% end notes %%

>.
 
 Annotations
- <mark class="hltr-yellow">"system-based manoeuvring model”</mark> [Page 3](zotero://open-pdf/library/items/AHWM4AXI?page=3&annotation=AHKWLJWW) 
 ^0ff644
- <mark class="hltr-green">"white-box”</mark> [Page 3](zotero://open-pdf/library/items/AHWM4AXI?page=3&annotation=D55J35E4) 
 ^533d5b
- <mark class="hltr-green">"grey-box”</mark> [Page 3](zotero://open-pdf/library/items/AHWM4AXI?page=3&annotation=2LA7WA3I) 
 ^850df4  ^115561
- <mark class="hltr-green">"black-box”</mark> [Page 3](zotero://open-pdf/library/items/AHWM4AXI?page=3&annotation=4TZ28CDZ) 
 ^73a126  ^a7e5b2
- <mark class="hltr-green">"system identification methods must handle imperfections in the data from measurement noise and model uncertainty”</mark> [Page 4](zotero://open-pdf/library/items/AHWM4AXI?page=4&annotation=265CU5FV) 
 
- <mark class="hltr-green">"preprocessing of data and a method to choose an appropriate manoeuvring model is needed”</mark> [Page 4](zotero://open-pdf/library/items/AHWM4AXI?page=4&annotation=UHGNRAEM) 
 
- <mark class="hltr-yellow">"Extended the Kalman filter”</mark> [Page 4](zotero://open-pdf/library/items/AHWM4AXI?page=4&annotation=QZSLNDGL) 
 
- <mark class="hltr-yellow">"Rauch Tung Striebel”</mark> [Page 4](zotero://open-pdf/library/items/AHWM4AXI?page=4&annotation=3XDZXBRB) 
 
- <mark class="hltr-yellow">"Surge, sway, and yaw have very low frequencies during manoeuvres, so added masses and other hydrodynamic derivatives can be assumed as constants”</mark> [Page 4](zotero://open-pdf/library/items/AHWM4AXI?page=4&annotation=AK6ZD2JH) 
 
- <mark class="hltr-yellow">"state space model”</mark> [Page 5](zotero://open-pdf/library/items/AHWM4AXI?page=5&annotation=A2EF65I2) 
 
- <mark class="hltr-yellow">"𝐰 is the process noise, i.e., the difference between the predicted state by the manoeuvring model and the true state of the system”</mark> [Page 5](zotero://open-pdf/library/items/AHWM4AXI?page=5&annotation=3SM4F88T) 
 
- <mark class="hltr-yellow">"reversed manoeuvring problem”</mark> [Page 6](zotero://open-pdf/library/items/AHWM4AXI?page=6&annotation=ZM7W73UK) 
 
- <mark class="hltr-green">"prior knowledge about the ship dynamics”</mark> [Page 6](zotero://open-pdf/library/items/AHWM4AXI?page=6&annotation=C5T8UR79) 
 
- <mark class="hltr-yellow">"The iterative process”</mark> [Page 6](zotero://open-pdf/library/items/AHWM4AXI?page=6&annotation=WFQY82YT) 
 
- <mark class="hltr-yellow">"Markov property”</mark> [Page 6](zotero://open-pdf/library/items/AHWM4AXI?page=6&annotation=2YWVVB5I)  ^01a786
 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-7-x105-y599.png]] 
	- Flow chart over the proposed parameter estimation method  ^2d4490




- <mark class="hltr-yellow">"proposed parameter estimation method”</mark> [Page 7](zotero://open-pdf/library/items/AHWM4AXI?page=7&annotation=ILMFQ2RV) 
^5c7835
 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-7-x133-y371.png]]  ^e9d974
 
	- Simulation with: initial model, first and second iteration of the parameter estimation. 
 
- <mark class="hltr-green">"The general aim of developing a manoeuvring model with parameter estimation is to develop a model that can generalize outside the known data.”</mark> [Page 7](zotero://open-pdf/library/items/AHWM4AXI?page=7&annotation=3KDVCPFC) 
 
- <mark class="hltr-yellow">"holdout evaluation”</mark> [Page 7](zotero://open-pdf/library/items/AHWM4AXI?page=7&annotation=QDWVH2DA) 
 
- <mark class="hltr-green">"inverse dynamics”</mark> [Page 7](zotero://open-pdf/library/items/AHWM4AXI?page=7&annotation=6GFHSMWZ) 
 
- <mark class="hltr-yellow">"The hydrodynamic derivatives in the manoeuvring model are usually taken as the mean value of each regressed random variable, being the most likely estimate”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=UGA33PTY) 
 
- <mark class="hltr-yellow">"Monte Carlo simulations can be conducted with this distribution to study alternative realizations of the regression”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=KPPI5HJD) 
 
- <mark class="hltr-green">"Strong multicollinearity is a known problem for the manoeuvring models”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=UBWEW2WP) 
 
- <mark class="hltr-green">"The measured data will always contain process noise and measurement noise”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=T26F87QI) 
 
- <mark class="hltr-green">"The basic idea is that noise can be disregarded if it does not make sense from a physical point of view”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=GKDPAN7Z) 
 
- <mark class="hltr-green">"The problem with low-pass filter is that it is hard to know what cut-off frequency to choose”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=JSPQLNF9) 
 
- <mark class="hltr-green">"The system’s inverse dynamics require the entire states, including positions, velocities, and accelerations, to be known”</mark> [Page 8](zotero://open-pdf/library/items/AHWM4AXI?page=8&annotation=8AIEV3JL) 
 
- <mark class="hltr-yellow">"unscented Kalman filter”</mark> [Page 9](zotero://open-pdf/library/items/AHWM4AXI?page=9&annotation=EYH3LPGY) 
 
- <mark class="hltr-green">"The fact that both past and future data are known can be used to improve the filter”</mark> [Page 9](zotero://open-pdf/library/items/AHWM4AXI?page=9&annotation=ERU86LRM) 
 
- <mark class="hltr-green">"This figure shows that the RTS smoother is also needed to get an accurate estimate of the yaw acceleration”</mark> [Page 9](zotero://open-pdf/library/items/AHWM4AXI?page=9&annotation=FA4IHDAS) 
 
- <mark class="hltr-yellow">"wPCC”</mark> [Page 9](zotero://open-pdf/library/items/AHWM4AXI?page=9&annotation=SYUVIYCL) 
 
- <mark class="hltr-yellow">"KVLCC2”</mark> [Page 9](zotero://open-pdf/library/items/AHWM4AXI?page=9&annotation=BGA4XCGW) 
 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-10-x128-y539.png]] 
 
	- EKF and RTS on simulated data (real) with Gaussian noise added (raw) 
 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-11-x130-y475.png]] 
 
	- wPCC training, validation and testing datasets. 
 
- <mark class="hltr-green">"The hydrodynamic derivatives within the manoeuvring model can be identified exactly at ideal conditions for the parameter estimation with no measurement noise and a perfect estimator”</mark> [Page 11](zotero://open-pdf/library/items/AHWM4AXI?page=11&annotation=ISLGC59S) 
 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-12-x125-y413.png]] 
 
	- Average simulation error with MAVMM fitted on wPCC model test data using low-pass filters with various cut off frequency or EKF. 
 
- <mark class="hltr-green">"The over-prediction of forces with the AVMM can be explained by the large problems with multicollinearity”</mark> [Page 12](zotero://open-pdf/library/items/AHWM4AXI?page=12&annotation=7F9I54MJ) 
 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-13-x126-y530.png]] 
 
	- Validation of force models for wPCC ZigZag20/20. 
 
- <mark class="hltr-green">"identifying parameters in a manoeuvring model on data from simulations with the same manoeuvring model”</mark> [Page 16](zotero://open-pdf/library/items/AHWM4AXI?page=16&annotation=LFJDUM7R) 
 
- <mark class="hltr-green">"The model works as long as the states are similar to the training data. However, when extrapolating, it is easy to imagine that the balance between these massive derivatives is disturbed, giving significant extrapolation errors very quickly.”</mark> [Page 18](zotero://open-pdf/library/items/AHWM4AXI?page=18&annotation=EXC6HB44) 
 
	- generalization 
 
- <mark class="hltr-yellow">"follow the aspect of persistence of excitation, so that some of the hydrodynamic derivatives might not be identifiable”</mark> [Page 18](zotero://open-pdf/library/items/AHWM4AXI?page=18&annotation=JKVK93ZS) 
 


%% Import Date: 2024-02-29T11:50:19.643+01:00 %%
