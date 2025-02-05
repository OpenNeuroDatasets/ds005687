# 2016GinRatAnesth

The dataset is composed of three types of data, anat, func, and asl measures, from 38 subjects. 
Four anesthetics are evaluated. 

The collection and content of this dataset "2016_gin_rat_anesth" is described in details in: 

BECQ, G.J.-P.C., HABET, T., COLLOMB, N., et al. Functional connectivity is preserved but reorganized across several anesthetic regimes. NeuroImage, 2020, p. 116945-116945. 

@article{Becq2020Functional, title={Functional connectivity is preserved but reorganized across several anesthetic regimes", author={Becq, Guillaume J.-P. C. and Habet, Tarik and Collomb, Nora and Faucher, Margaux and Delon-Martin, Chantal and Coizet, Véronique and Achard, Sophie and Barbier, Emmanuel L.}, journal={NeuroImage}, publisher={Elsevier}, volume={219}, pages={116945}, year={2020}, doi={https://doi.org/10.1016/j.neuroimage.2020.116945} } 


## Abstract

Under anesthesia, systemic variables and CBF are modified. 
How does this alter the connectivity measures obtained with rs-fMRI ? 
To tackle this question, we explored the effect of four different anesthetics on Long Evans and Wistar rats with multimodal recordings of rs-fMRI, systemic variables and CBF. 
After multimodal signal processing, we show that the blood-oxygen-level-dependent (BOLD) variations and functional connectivity (FC) evaluated at low frequencies (0.031 – 0.25 Hz) do not depend on systemic variables and are preserved across a large interval of baseline CBF values. 
Based on these findings, we found that most brain areas remain functionally active under any anesthetics, i.e. connected to at least one other brain area, as shown by the connectivity graphs. 
In addition, we quantified the influence of nodes by a measure of functional connectivity strength to show the specific areas targeted by anesthetics and compare correlation values of edges at different levels. 
These measures enable us to highlight the specific network alterations induced by anesthetics. 
Altogether, this suggests that changes in connectivity could be evaluated under anesthesia, routinely used in the control of neurological injury.


## Anesthesia

At the beginning of the experiment, animals receive a gaseous mixture, composed of isoflurane and a mixture of 80% air and 20% oxygen, inhaled through a funnel. 
A level of 5% isoflurane is given during 2 min followed by a level of 2% during 10 min (Fig. B.7). 
During the animal preparation, ears are filled with a mix of gel (ocry-gel) and wax, to limit air-related susceptibility artifacts in the images. 
After this common induction, four anesthetics are evaluated:
- Isoflurane (Iso): the level of isoflurane is set to 1% to be in a regime showing persistent behavior of spontaneous BOLD fluctuations (Wang et al., 2011). 
To evaluate the impact of strain, this anesthetic was evaluated in both Long-Evans and Wistar rats.
- Etomidate (Eto) (B. Braun, Melsungen, Germany): An administration in two stages is performed with a bolus of 10 mg/kg/min (3 min) injected in association with isoflurane at 4% during initiation, followed by a continuous intravenous infusion at 0.5 mg/kg/min.
- Medetomidine (Med) (Domitor, medetomidine hydrochloride; Orion Corporation, Espoo, Finland): An administration in two stages is performed with a bolus of 0.24 mg/kg injected subcutaneously in association with isoflurane at 4% during initiation, followed by a continuous infusion at 0.05 mg/kg/h.
- Urethane (Ure): A bolus of 1.25 g/kg is injected intraperitoneally (Rolland et al., 2013). 
The use of this anesthesia is well regulated and rats are euthanized at the end of the experiment because of the carcinogenic toxicity of this agent.
- A group of dead rats (Dead) was created by sacrificing 4 animals just before the experiment.
Overall, 6 groups were evaluated: Eto-L (n = 7), Iso-L (n = 6), Iso-W (n = 7), Med-L (n = 7), Ure-L (n = 7), Dead (n = 4). 

## From sourcedata to rawdata

Routines to transform data and metadata in `/sourcedata` to rawdata using [brkraw](https://github.com/BrkRaw/brkraw) v0.3.7 are available in `/code`. 






