<!-- [Home](index.md) :: [Selected Publications](pub.md) :: [Google Scholar](https://scholar.google.com/citations?user=H-9OPuIAAAAJ&hl=en) :: [CV](Safdari_CV.pdf) :: [linkedin](https://linkedin.com/in/hadiseh-safdari-238540153)  -->

<!-- [Home](index.md) :: [Selected Projects and Publications](pub.md) :: [<img src="pngwing.png" alt="Google Scholar" style="width: 16px; height: 16px; vertical-align: middle;">](https://scholar.google.com/citations?user=H-9OPuIAAAAJ&hl=en) :: [<img src="LinkedIn_logo_initials.png" alt="LinkedIn" style="width: 16px; height: 16px; vertical-align: middle;">](https://linkedin.com/in/hadiseh-safdari-238540153) :: [CV](Safdari_CV.pdf) -->


[Home](index.md) :: [Selected Projects and Publications](pub.md) :: [<img src="pngwing.png" alt="Google Scholar" style="width: 16px; height: 16px; vertical-align: middle;">](https://scholar.google.com/citations?user=H-9OPuIAAAAJ&hl=en) :: [<img src="LinkedIn_logo_initials.png" alt="LinkedIn" style="width: 16px; height: 16px; vertical-align: middle;">](https://linkedin.com/in/hadiseh-safdari-238540153):: [<img src="github-mark.png" alt="GitHub" style="width: 20px; height: 20px; vertical-align: middle;">](https://github.com/hds-safdari)


## Selected Publications 




### Community detection and anomaly prediction in dynamic networks

**Summary**

This  project introduces DynACD, a novel probabilistic machine learning model for detecting anomalies in dynamic networks.
DynACD integrates community detection to establish a baseline of typical network behavior, 
identifying anomalies as deviations from this established structure. The model is evaluated on both synthetic and real-world datasets, 
demonstrating superior performance compared to existing methods. A case study using Transfermarkt dataset, which contains information on player transfers
among European men’s football clubs, showcases DynACD's ability 
to detect anomalies influenced by factors like club wealth and national leagues, as well as identify potential data errors. The model's 
probabilistic framework allows for the interpretation of anomaly detection results, enhancing its practical usability.
[(Commun Phys, , Nature Portfolio 7, 397 (2024))](https://doi.org/10.1038/s42005-024-01889-y) [(GitHub)](https://github.com/hds-safdari/DynACD)
<br>

<div style="text-align: center;">
    <img src="Genoa_connections_T1.png" alt="Genoa Transfermarkt datasets." style="max-width: 100%; height: auto;">
    <p><em>Figure 1: Genoa transfer network. Visualization of player transfers to and from Genoa involving various clubs at different time steps. 
    There is a consistent presence of transfers with Juventus and Inter Milan at most time steps, T, shown by red edges.
</em></p>
</div> 


<br><br><br>



### Generative Model for Reciprocity and Community Detection in  Directed Networks

**Summary**

This  project developes a novel probabilistic generative model, called CRep, designed to analyze and model reciprocity and community structure within directed networks. 
Unlike previous models that treat these aspects separately or make simplifying assumptions about edge independence, CRep incorporates both community memberships 
and a reciprocity parameter to more accurately represent the complex interplay between these factors in real-world networks. The model uses an 
efficient expectation-maximization algorithm for parameter inference and a benchmark generative model for synthetic data creation. 
The effectiveness of CRep is demonstrated through experiments on both synthetic and real-world datasets, showing superior 
performance in edge prediction and reproducing observed reciprocity values. The authors provide an open-source implementation of their code.
[(Phys. Rev. Research 3, 023209 (2021))](https://doi.org/10.1103/PhysRevResearch.3.023209) [(GitHub)](https://github.com/mcontisc/CRep) 

<br>

<div style="text-align: center;">
    <img src="erasmus_example.png" alt="Reciprocity Patterns in the Erasmus Network." style="max-width: 100%; height: auto;">
    <p><em>Figure 2: Reciprocity Patterns in the Erasmus Network. This figure illustrates how different universities in the Erasmus student exchange network exhibit a range of 
    reciprocity patterns in their partnerships with other universities. The figure visualizes these patterns in terms of how the outgoing 
    edges of a given university are driven by academic preference versus the reciprocation of student exchanges from partner universities.
</em></p>
</div>


<br><br><br>



### Latent Network Models to Account for Noisy, Multiply-Reported Social Network Data

**Summary**

This interdisciplinary project introduces VIMuRe, a new probabilistic model for analyzing noisy, multiply-reported social network data. 
The model accounts for individual reporter biases (over- or under-reporting) and "mutuality"—the tendency to report reciprocal relationships. 
VIMuRe's efficiency allows it to scale to large networks, utilizing variational inference. 
The model is validated through simulations and applied to two empirical datasets (Nicaragua and Karnataka), 
demonstrating improved accuracy in estimating network structure and reciprocity compared to traditional methods. 
The findings highlight the importance of considering mutuality and reporter reliability when interpreting social network data.
[(Journal of the Royal Statistical Society Series A: Statistics in Society  (186)  3, 355–375 (2023))](https://doi.org/10.1093/jrsssa/qnac004) [(GitHub)](https://latentnetworks.github.io/vimure/)
<br>

<div style="text-align: center;">
    <img src="nicaragua_example_reports.png" alt="Example of individual reliabilities." style="max-width: 160%; height: auto;">
    <p><em>Figure 3: Illustration of reporter reliability and tie confirmation in a social support network from a Nicaraguan community.
    Pie charts highlight different configurations of reported and confirmed ties for selected reporters, emphasizing variations in reporting behavior and mutuality.
</em></p>
</div>

<br><br><br>




### Anomaly detection and community detection in networks


**Summary**

This work presents a probabilistic generative model for anomaly detection in networks, ACD, leveraging community structure to define regular interaction patterns. 
The model incorporates latent variables representing community memberships and anomalous edges, enabling simultaneous inference of both. 
An expectation-maximization algorithm efficiently estimates these variables, and the model's performance is validated using synthetic and 
real-world datasets. Experiments demonstrate improved community detection by removing or adding edges identified as anomalies, showcasing the model's flexibility and robustness. 
The findings suggest that understanding network community structure enhances the accuracy of anomaly detection. 
[(Journal of Big Data (9), 122 (2022))](https://doi.org/10.1186/s40537-022-00669-1) [(GitHub)](https://github.com/hds-safdari/Anomaly_Community_Detection)

<br>

<div style="text-align: center;">
    <img src="polbooks_hardCD_removing.png" alt="The network of POLBOOKS (Books about US politics)." style="max-width: 160%; height: auto;">
    <p><em>Figure 4: The network of POLBOOKS (Books about US politics). The plot shows enhanced community detection through the removal of anomalous edges (panel (b)). 
    Red edges indicate those identified as anomalies and removed before reanalysis. Red rectangles denote pairs of nodes that are connected by the edges inferred as anomalous. 
    Cyan rectangles demonstrate the nodes that changed their community membership, after removing the aforementioned anomalous edges. 
    Cyan edges in panel (a) present the edges connected to these. Panel (c) indicates Ground Truth Communities.
</em></p>
</div>



<br><br><br>



### Noise-driven cell differentiation and the emergence of spatiotemporal patterns, Safdari, Kalirad, et al., 2020, _PLOS ONE_

**Summary**

The interdisciplinary  research project developes  a noise-driven differentiation
(NDD) model of cell differentiation and pattern formation. The model
incorporates intrinsic cellular noise, stochastic cell division, and cell
signaling to explain how phenotypic diversity emerges and leads to
spatiotemporal patterns in cell populations. Simulations using a cell
aggregation model support the model's predictions, showing that noise alone
can generate heterogeneity, while signaling introduces spatial order. The
authors compare their model to existing models, highlighting its unique
approach of separating and analyzing different noise sources. Finally, the
study discusses the implications of the NDD model for understanding the
evolutionary transition from unicellularity to multicellularity. 
[(Plos one 15 (4), e0232060 (2020))](https://doi.org/10.1371/journal.pone.0232060) [(GitHub)](https://github.com/hds-safdari/Noise_Driven_Cell_Differentiation) 
<br>


<div style="text-align: center;">
    <img src="cell_fate.png" alt="The phase-portrait diagram for the NDD model." style="max-width: 75%; height: auto;">
    <p><em>Figure 5:  In a bistable switch, two attractors (red semicircles) and, consequently, two phenotypes are available: 
    A and B. The likelihood of a switch choosing state A over B depends on the number of the transcription factor associated with state A (TFX) 
    relative to the number of the transcription factor associated with state B (TFY), as well as the noise in its environment.
</em></p>
</div> 


 
<br><br><br>


### Game theoretical approach to Metabolic pathways

**Summary**

This research paper uses computational modeling and game theory to investigate the Crabtree effect in yeast, 
focusing on the switch between fermentation and respiration for ATP production. The authors propose a metabolic 
switch model where individual yeast cells dynamically adjust their strategy based on glucose availability, 
resulting in population-level heterogeneity. This contrasts with traditional game-theoretical models that assume distinct 
subpopulations with fixed strategies. The study uses stochastic simulations to explore the model's behavior under varying 
glucose conditions and proposes an experimental method to distinguish between mixed-strategy and distinct-subpopulation scenarios. 
The findings could have implications for understanding cancer metabolism and developing new therapies.
[(Journal of Theoretical Biology 531, 110912 (2021))](https://doi.org/10.1016/j.jtbi.2021.110912) [(GitHub)](https://github.com/Kalirad/Making_ATP_fast_and_slow)  

<br>

<div style="text-align: center;">
    <img src="gameTheory.png" alt="A simple regulatory network to explain utilizing both ATP-producing pathways." style="max-width: 75%; height: auto;">
    <p><em>Figure 6:  The proposed regulatory network imagines a simple switch between fermentation and respiration based on the experimental data.
</em></p>
</div>



<br><br><br>

<!-- ### Scaled Brownian Motion

**Summary**

A stochastic process in anomalous diffusion, especially Scaled Brownian Motion (SBM) a highly non-stationary Gaussian process.  Characterizing statistical properties of models for anomalous diffusion is a crucial point in analyzing data received from single particle tracking measurements. Particularly, from both theory and simulation points of view, we studied aging effects (time-span between system preparation and the start of the measurements) on statistical features such as first passage time density and ergodicity behavior of confined and unconfined SBM. For aged SBM, ensemble-averaged mean squared displacement (MSD) which had power law dependence on time, tends to be the time-averaged MSD. This second average is particularly important for the analysis of single particle tracking data and it is at the heart of the phenomenon of ergodicity breaking. In particular, in the strong aging limit, they converge to each other and ergodicity is restored. Besides, confined SBM in the presence of aging is a unique process in which the ensemble average tends to plateau. For strong aging, again ergodicity is restored. Moreover, we investigated the ergodicity breaking parameter as a measure of scattering of different trajectories. We represented its full behavior for all values of anomalous exponent within a general approach, which could be applied to other anomalous processes. -->

<!-- Summaries were generated by [NotebookLM](https://notebooklm.google). -->