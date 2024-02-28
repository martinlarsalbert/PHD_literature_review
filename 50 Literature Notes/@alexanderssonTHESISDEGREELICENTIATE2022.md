---
category: literaturenote
tags: lic_thesis
citekey: alexanderssonTHESISDEGREELICENTIATE2022
status: unread
dateread:
---

> [!Cite]
> Alexandersson, M. (2022). _THESIS FOR THE DEGREE OF LICENTIATE OF ENGINEERING Rigid Body Ship Dynamics System Identification in Calm Waters_. [https://doi.org/10.13140/RG.2.2.23950.02889](https://doi.org/10.13140/RG.2.2.23950.02889)

>[!Synth]
>**Contribution**:: 
>
>**Related**:: 
>

>[!md]
> **FirstAuthor**:: Alexandersson, Martin  
~    
> **Title**:: THESIS FOR THE DEGREE OF LICENTIATE OF ENGINEERING Rigid Body Ship Dynamics System Identification in Calm Waters  
> **Year**:: 2022  
> **Date**:: 2022-12-01  
> **Citekey**:: alexanderssonTHESISDEGREELICENTIATE2022  
> **itemType**:: thesis    

> [!LINK] 
>
>  [Full Text PDF](file://C:/Zotero/storage/63QB3GCR/Alexandersson%20-%202022%20-%20THESIS%20FOR%20THE%20DEGREE%20OF%20LICENTIATE%20OF%20ENGINEERING.pdf).

> [!Abstract]
>
> It is common today that operational data is recorded onboard ships within the Internet
of Ships (IoS) paradigm. This enables the possibility to build ship digital twins as
digital copies of the real ships. Predicting the ship’s motions with ship dynamics could
be an important sub-component of these ship digital twins. A model for the ship’s
dynamics can be identified based on observations of the ship’s motions. The identified
model will have model uncertainty due to imperfections and idealizations made in
physical model formulations as well as uncertainty from errors in the measurement
data, which can be very pronounced when using full scale operational data. It is
easier to develop accurate models with low model uncertainty using data obtained in
a controlled laboratory environment where the measurement errors are much lower,
especially in calm water conditions. The prediction model should be able to describe
scenarios that a ship has never encountered before, which is possible if much of the
underlying physics has been identified. Grey-box modelling is a technique which
combines operational data with physical principles to achieve this.
The objective of this thesis is to develop system identification methods for grey
box models with good generalization of the model scale rigid body ship dynamics in
calm waters.
A model development procedure is proposed to handle the model uncertainty
through the selection of candidate models based on a hold-out evaluation procedure.
The measurement noise is handled by an iterative preprocessor, which uses an extended
Kalman filter (EKF) and a Rauch Tung Striebel (RTS) smoother that uses an initially
estimated predictor model from semi-empirical formulas.
It is demonstrated that the ship’s roll motion with high accuracy can be described
using a quadratic damping model. For the more complex manoeuvring models,
multicollinearity is a large problem where the appropriate complexity needs to be
selected with the bias-variance trade-off between underfitting or overfitting the data.
Hold-out turning circle tests were predicted with high accuracy for the wPCC and
KVLCC2 test case ships with models from the proposed development procedure and
parameter estimation method.
The proposed methods can produce prediction models with high generalization
given that a suitable model structure has been selected from the candidate models
and an appropriate split in the hold-out evaluation of the model development process
has been applied.
>.
> 
# Notes
%% begin notes %%
- First thing
- Second thing
things to add each time you import:

%% end notes %%

>.



# Annotations%% begin annotations %%



### Imported: 2024-02-28 11:31 am



<mark style="background-color: #ffd400">Quote</mark>
> Extended Kalman filter

<mark style="background-color: #ffd400">Quote</mark>
> Inverse dynamics

<mark style="background-color: #ffd400">Quote</mark>
> Multicollinearity

<mark style="background-color: #ffd400">Quote</mark>
> Ship digital twin

<mark style="background-color: #ffd400">Quote</mark>
> Ship manoeuvring

<mark style="background-color: #ffd400">Quote</mark>
> System identification


%% end annotations %%

%% Import Date: 2024-02-28T11:31:58.406+01:00 %%
