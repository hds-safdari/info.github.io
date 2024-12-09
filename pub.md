[Home](index.md) :: [Selected Publications](pub.md) :: [Google Scholar](https://scholar.google.com/citations?user=H-9OPuIAAAAJ&hl=en) :: [CV](Hadiseh_Safdari_CV.pdf) :: [linkedin](https://linkedin.com/in/hadiseh-safdari-238540153) 
## Selected publications 




### Community detection and anomaly prediction in dynamic networks

**Summary**

This research paper introduces DynACD, a novel probabilistic model for detecting anomalies in dynamic networks.
DynACD integrates community detection to establish a baseline of typical network behavior, 
identifying anomalies as deviations from this established structure. The model is evaluated on both synthetic and real-world datasets, 
demonstrating superior performance compared to existing methods. A case study using football player transfers showcases DynACD's ability 
to detect anomalies influenced by factors like club wealth and national leagues, as well as identify potential data errors. The model's 
probabilistic framework allows for the interpretation of anomaly detection results, enhancing its practical usability.


<div style="text-align: center;">
    <img src="Genoa_connections_T1.png" alt="Genoa Transfermarkt datasets" style="max-width: 100%; height: auto;">
    <p><em>Figure 1: Genoa transfer network. Visualization of player transfers to and from Genoa involving various clubs at different time steps. There is a consistent presence of transfers with Juventus and Inter Milan at most time steps, T, shown by red edges.
</em></p>
</div>

[DOI](https://doi.org/10.1038/s42005-024-01889-y) [GitHub](https://github.com/hds-safdari/DynACD)





### Generative Model for Reciprocity and Community Detection in  Directed Networks

**Summary**

This research paper introduces a novel probabilistic generative model, called CRep, designed to analyze and model reciprocity and community structure within directed networks. 
Unlike previous models that treat these aspects separately or make simplifying assumptions about edge independence, CRep incorporates both community memberships 
and a reciprocity parameter to more accurately represent the complex interplay between these factors in real-world networks. The model uses an 
efficient expectation-maximization algorithm for parameter inference and a benchmark generative model for synthetic data creation. 
The effectiveness of CRep is demonstrated through experiments on both synthetic and real-world datasets, showing superior 
performance in edge prediction and reproducing observed reciprocity values. The authors provide an open-source implementation of their code.
<!-- ![Image](erasmus_example.png) --> 


<div style="text-align: center;">
    <img src="erasmus_example.png" alt="Reciprocity Patterns in the Erasmus Network" style="max-width: 100%; height: auto;">
    <p><em>Figure 2: Reciprocity Patterns in the Erasmus Network. This figure illustrates how different universities in the Erasmus student exchange network exhibit a range of 
    reciprocity patterns in their partnerships with other universities. The figure visualizes these patterns in terms of how the outgoing 
    edges of a given university are driven by academic preference versus the reciprocation of student exchanges from partner universities.
</em></p>
</div>



[DOI](https://doi.org/10.1103/PhysRevResearch.3.023209) [GitHub](https://github.com/mcontisc/CRep)
<!-- [https://github.com/hds-safdari/DynCRep](GitHub)  [https://latentnetworks.github.io/vimure/](GitHub) -->



### Latent Network Models to Account for Noisy, Multiply-Reported Social Network Data

**Summary**

In an interdisciplinary project in collaboration with anthropologists \cite{de2023latent}, we addressed challenges in reconciling contradictory responses in social network data. We proposed a probabilistic model incorporating ties reported by multiple individuals to estimate unobserved network structure. The model considers parameters for each reporter's tendency of over- or under-reporting relationships and a term for "mutuality." Algorithmic implementation based on variational inference enables scalable applications. Application to real datasets demonstrated strong evidence of mutuality and highlighted the significance of addressing issues in survey-based network data gathering and analysis. We released open-source efficient algorithmic implementations that are scalable to large network datasets 




### Anomaly, reciprocity, and community detection in Static and Dynamic Networks

**Summary**

Anomaly detection is a foundational problem in the area of data analysis. In networked systems, where individual entities interact in pairs, anomalies are observed when patterns of interactions deviate from patterns considered regular. Properly defining what regularity means relies on developing expressive models for describing the observed interactions. This is crucial for tackling anomaly detection in networks. Among the many well-known models for networks, latent variable models - a class of probabilistic models - offer promising tools to capture the intrinsic features of the data. To this end, we proposed probabilistic generative approaches that incorporate domain knowledge, such as community membership and reciprocity, as a fundamental model for regular behavior in Networks, and thus flag potential anomalies deviating from this. Community membership shapes the building blocks of a null model to identify the normal interaction patterns. The structural information enters the model through latent variables for community membership and anomaly parameters. The algorithms aim at inferring these latent parameters and then output the labels identifying anomalies on the network objects (nodes/edges). In addition, we considered the situation where networks and anomalies evolve, as observed in realistic situations. Hence we developed a dynamic version of the model as well 
<!-- 
![Image](Genoa_connections_T1.png) -->
<!-- [safdari2024community,safdari2023anomaly,safdari2022anomaly]() -->




### Noise-driven cell differentiation and the emergence of spatiotemporal patterns, Safdari, Kalirad, et al., 2020, _PLOS ONE_

![Image](cell_fate.png)

**Summary**

This PLOS ONE research article presents a noise-driven differentiation
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

[https://doi.org/10.1371/journal.pone.0232060](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0232060)



### Game theoretical approach to Metabolic pathways

**Summary**

This interdisciplinary project proposed a mathematical model to explain the switch between biochemical pathways in yeast in terms of evolutionary strategies. This model postulated that individuals in a population play a mixed strategy at the biochemical level to metabolize glucose. This approach not only sheds some light on the varieties of metabolic regulations that can be utilized by the individuals in the population in competition with others for a common resource, but it would also allow a better understanding of the causes of the switch between aerobic and anaerobic respiration, e.g., in cancer cells, and similar phenomena observed in nature.

![Image](gameTheory.png)





<!-- ### Scaled Brownian Motion

**Summary**

A stochastic process in anomalous diffusion, especially Scaled Brownian Motion (SBM) a highly non-stationary Gaussian process.  Characterizing statistical properties of models for anomalous diffusion is a crucial point in analyzing data received from single particle tracking measurements. Particularly, from both theory and simulation points of view, we studied aging effects (time-span between system preparation and the start of the measurements) on statistical features such as first passage time density and ergodicity behavior of confined and unconfined SBM. For aged SBM, ensemble-averaged mean squared displacement (MSD) which had power law dependence on time, tends to be the time-averaged MSD. This second average is particularly important for the analysis of single particle tracking data and it is at the heart of the phenomenon of ergodicity breaking. In particular, in the strong aging limit, they converge to each other and ergodicity is restored. Besides, confined SBM in the presence of aging is a unique process in which the ensemble average tends to plateau. For strong aging, again ergodicity is restored. Moreover, we investigated the ergodicity breaking parameter as a measure of scattering of different trajectories. We represented its full behavior for all values of anomalous exponent within a general approach, which could be applied to other anomalous processes. -->

Summaries were generated by [NotebookLM](https://notebooklm.google).