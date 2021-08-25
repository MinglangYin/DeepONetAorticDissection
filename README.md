# Simulating progressive intramural damage leading to aortic dissection using an operator-regression neural network

Code and data will be publicly available after the peer review process is complete.

# Abstract
Aortic dissection progresses via delamination of the medial layer of the wall. Notwithstanding the complexity of this process, insight has been gleaned by studying \textit{in vitro} and \textit{in silico} the progression of dissection driven by quasi-static pressurization of the intramural space by fluid injection, which demonstrates that the differential propensity of dissection can be affected by spatial distributions of structurally significant interlamellar struts that connect adjacent elastic lamellae. In particular, diverse histological microstructures may lead to differential mechanical behavior during dissection, including the pressure--volume relationship of the injected fluid and the displacement field between adjacent lamellae. In this study, we develop a data-driven surrogate model for the delamination process for differential strut distributions using DeepONet, a new operator--regression neural network. The surrogate model is trained to predict the pressure--volume curve of the injected fluid and the damage progression field of the wall given a spatial distribution of struts, with in silico} data generated with a phase-field finite element model. The results show that DeepONet can provide accurate predictions for diverse strut distributions, indicating that this composite branch-trunk neural network can effectively extract the underlying functional relationship between distinctive microstructures and their mechanical properties. More broadly, DeepONet can facilitate surrogate model-based analyses to quantify biological variability, improve inverse design, and predict mechanical properties based on multi-modality experimental data.
