In the 2nd paper – System identification of Vessel Manoeuvring Models [[@alexanderssonSystemIdentificationVessel2022a]] – three major problems where addressed:
> [!Paper 1 to Paper 2]  
>> * Manoeuvring → Expand to 3DOF (three degrees of freedom).
>> * Handle noise → Find estimator for he higher order time derivatives – velocity and acceleration. 
>> * System identification → Find appropriate mathematical model → Identify parameters.

| Box modelling                         | Meaning                                                                                                                                                                                                                                                                                                                          |
| ------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| <mark class="hltr-white">White</mark> | involves applying physical principles to ensure that no observed data is required. One example is computational fluid dynamics (CFD). Semi-empirical models, in which unknown physical constants have been derived from historical experiments, could also be considered white-box models [[@leifssonGreyboxModelingOcean2008]]. |
| <mark class="hltr-grey">Grey</mark>   | means that parameters do not have physical significance and that the objective is to find an effective model that fits the observed data [[@lindskogToolsSemiphysicalModelling1995]]                                                                                                                                             |
| <mark class="hltr-black">Black</mark> | is using a combination of white-box and black-box modeling methods to ensure that both a physical model and data are used. This concept is also referred to as semi-physical modeling, hybrid modeling, or semi-mechanistic modeling in the literature [[@leifssonGreyboxModelingOcean2008]]                                     |

Many ==system based manoeuvring models== have been developed during the years.
The model is assumed to have ==Markov property==, meaning that future states depend only on the current state. The model can thus be expressed as a ==state space model==.

Surge, sway, and yaw have very low frequencies during manoeuvres, so added masses and other hydrodynamic derivatives can be assumed as constants [[@fossenHandbookMarineCraft2011a]].

System identification methods must handle imperfections in the data from measurement noise and model uncertainty. Pre-processing of data and a method to choose an appropriate manoeuvring model is thus needed.
### Proposed parameter estimation method
The proposed parameter identification technique (PIT) involves a ==Extended Kalman filter (EKF)== together with a ==Rauch Tung Striebel (RTS)== smoother.
The method runs in iteration:
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-7-x105-y599.png]] 

The iteration converges towards parameters that predicts the model test with better and better accuracy:
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-7-x133-y371.png|500]] 
### Generalization
The general aim of developing a manoeuvring model with parameter estimation is to develop a model that can generalize outside the known data. ==Holdout evaluation== is used during the parameter estimation, where the data is split into ==training==, ==validation==, and ==testing== data sets – to avoid an overfitted model. 
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-11-x130-y475.png]] 

An overfitted model may overpredict the forces during validation. The model works as long as the states are similar to the training data. However, when extrapolating, it is easy to imagine that the balance between these massive derivatives is disturbed, giving significant extrapolation errors very quickly.
![[80 Meta/81 Attachments/alexanderssonSystemIdentificationVessel2022a/image-13-x126-y530.png]] 

![[Paper 2 canvas.canvas|Paper 2 canvas]]
