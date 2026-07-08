---
layout: default
title: Projects & Publications
description: Selected projects and publications by Hadiseh Safdari.
---

<section class="page-title">
  <p class="eyebrow">Selected projects and publications</p>
  <h1>Research at the interface of networks, inference, and dynamical systems.</h1>
  <p class="lede">
    These projects share a common goal: using probabilistic generative models to recover interpretable structure from data that are noisy, biased, incomplete, or evolving.
  </p>
</section>

<div class="timeline-note">
  The project summaries below emphasize modeling ideas, scientific motivation, and reusable computational tools.
</div>

<section class="project-list">
  <article class="project-card" id="microbial-interactions">
    <div>
      <p class="meta">Ongoing · Bayesian inference · Microbial ecology</p>
      <h2 class="pub-title">Learning microbial interactions from time-series data</h2>
      <p>
        Microbial communities are dense webs of interaction: species compete, cooperate, and reshape one another's fortunes as their environment shifts. But the data we collect on them is noisy, sparse, and shaped by the limits of what our instruments can measure.
      </p>
      <p>
        In this ongoing project, I am developing a Bayesian framework to infer how microbial species influence one another over time — and how those relationships respond to changing environmental conditions — directly from absolute-abundance time-series measurements. The approach is designed to handle the practical realities of such data, from measurement noise to detection limits, while keeping the inferred interactions interpretable and grounded in biological priors. The broader aim is to turn imperfect observational data into a principled, mechanistic picture of how a microbial ecosystem behaves. Manuscript in preparation.
      </p>
      <div class="tag-row">
        <span class="tag">Bayesian modeling</span>
        <span class="tag">Time series</span>
        <span class="tag">Microbial communities</span>
        <span class="tag">Environmental context</span>
      </div>
    </div>
    <div>
      <img src="microbial_interaction_inference_pipeline.png" alt="Microbial interaction inference pipeline">
      <p class="figure-note">Figure 1: From noisy microbial time series to a Bayesian model shaped by environmental context — recovering the hidden network of species interactions.</p>
    </div>
  </article>

  <article class="project-card" id="dynacd">
    <div>
      <p class="meta">Communications Physics · Nature Portfolio · 2024</p>
      <h2 class="pub-title">Anomaly detection in dynamic networks — DynACD</h2>
      <p>
        Networks evolve, and so does what counts as unusual within them. DynACD is a probabilistic model that learns the community structure underlying a dynamic network and flags interactions that deviate from that learned baseline, turning anomaly detection into a principled statistical inference problem rather than a heuristic one.
      </p>
      <p>
        Beyond outperforming existing methods on synthetic and real-world benchmarks, the model's probabilistic framework makes its results interpretable: applied to two decades of player transfers among European football clubs, it revealed anomalies shaped by club wealth and league boundaries, and even surfaced likely errors in the data itself.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.1038/s42005-024-01889-y">Paper</a>
        <a href="https://github.com/hds-safdari/DynACD">GitHub</a>
      </div>
    </div>
    <div>
      <img src="Genoa_connections_T1.png" alt="Genoa Transfermarkt transfer network">
      <p class="figure-note">Figure 2: Genoa transfer network. Player transfers to and from Genoa, including recurring connections with Juventus and Inter Milan.</p>
    </div>
  </article>

  <article class="project-card" id="crep">
    <div>
      <p class="meta">Physical Review Research · 2021</p>
      <h2 class="pub-title">Reciprocity and community structure in directed networks — CRep</h2>
      <p>
        If someone sends you a connection, how likely are you to send one back — and how does that tendency interact with the communities you belong to? Most models treat reciprocity and community structure separately, or assume network edges form independently. CRep breaks with both assumptions: it is a generative model that captures their joint effect, with an efficient expectation-maximization algorithm for inference and a companion benchmark for generating synthetic networks with tunable reciprocity.
      </p>
      <p>
        The result is markedly better edge prediction and networks that reproduce the reciprocity patterns actually observed in real data. The implementation is open source.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.1103/PhysRevResearch.3.023209">Paper</a>
        <a href="https://github.com/mcontisc/CRep">GitHub</a>
      </div>
    </div>
    <div>
      <img src="erasmus_example.png" alt="Reciprocity patterns in the Erasmus network">
      <p class="figure-note">Figure 3: Reciprocity patterns in the Erasmus student exchange network.</p>
    </div>
  </article>

  <article class="project-card" id="vimure">
    <div>
      <p class="meta">Journal of the Royal Statistical Society Series A · 2023</p>
      <h2 class="pub-title">Inferring social networks from noisy, conflicting reports — VIMuRe</h2>
      <p>
        When you ask two people about the same relationship, they often disagree. VIMuRe is a latent network model that treats survey-based social network data as what it really is — noisy, multiply-reported observations — and infers the underlying network while accounting for each reporter's tendency to over- or under-report, as well as mutuality in how ties are described.
      </p>
      <p>
        Built on variational inference, it scales to large networks, and applications to village datasets from Nicaragua and Karnataka show substantially more accurate estimates of network structure and reciprocity than conventional approaches. This project, a collaboration with statisticians and social scientists, underscores a central theme of my work: the measurement process is part of the model.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.1093/jrsssa/qnac004">Paper</a>
        <a href="https://latentnetworks.github.io/vimure/">Project</a>
      </div>
    </div>
    <div>
      <img src="nicaragua_example_reports.png" alt="Reporter reliability and tie confirmation in a social support network">
      <p class="figure-note">Figure 4: Reporter reliability and tie confirmation in a Nicaraguan social support network.</p>
    </div>
  </article>

  <article class="project-card" id="acd">
    <div>
      <p class="meta">Journal of Big Data · 2022</p>
      <h2 class="pub-title">Anomaly detection and community detection in networks</h2>
      <p>
        This work presents a probabilistic generative model for anomaly detection in networks, ACD, leveraging community structure to define regular interaction patterns. The model incorporates latent variables representing community memberships and anomalous edges, enabling simultaneous inference of both.
      </p>
      <p>
        An expectation-maximization algorithm efficiently estimates these variables, and the model's performance is validated using synthetic and real-world datasets. Experiments demonstrate improved community detection by removing or adding edges identified as anomalies, showcasing the model's flexibility and robustness.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.1186/s40537-022-00669-1">Paper</a>
        <a href="https://github.com/hds-safdari/Anomaly_Community_Detection">GitHub</a>
      </div>
    </div>
    <div>
      <img src="polbooks_hardCD_removing.png" alt="Community detection after removing anomalous edges in the POLBOOKS network">
      <p class="figure-note">Figure 5: Enhanced community detection through the removal of anomalous edges in the POLBOOKS network.</p>
    </div>
  </article>

  <article class="project-card" id="ndd">
    <div>
      <p class="meta">PLOS ONE · 2020</p>
      <h2 class="pub-title">Noise-driven cell differentiation and the emergence of spatiotemporal patterns</h2>
      <p>
        This interdisciplinary research project develops a noise-driven differentiation model of cell differentiation and pattern formation. The model incorporates intrinsic cellular noise, stochastic cell division, and cell signaling to explain how phenotypic diversity emerges and leads to spatiotemporal patterns in cell populations.
      </p>
      <p>
        Simulations using a cell aggregation model support the model's predictions, showing that noise alone can generate heterogeneity, while signaling introduces spatial order. The study discusses the implications of the model for understanding the evolutionary transition from unicellularity to multicellularity.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.1371/journal.pone.0232060">Paper</a>
        <a href="https://github.com/hds-safdari/Noise_Driven_Cell_Differentiation">GitHub</a>
      </div>
    </div>
    <div>
      <img src="cell_fate.png" alt="Phase portrait diagram for the noise-driven differentiation model">
      <p class="figure-note">Figure 6: A bistable switch with two phenotypic attractors.</p>
    </div>
  </article>

  <article class="project-card" id="metabolic-pathways">
    <div>
      <p class="meta">Journal of Theoretical Biology · 2021</p>
      <h2 class="pub-title">Game theoretical approach to metabolic pathways</h2>
      <p>
        This research paper uses computational modeling and game theory to investigate the Crabtree effect in yeast, focusing on the switch between fermentation and respiration for ATP production. The authors propose a metabolic switch model where individual yeast cells dynamically adjust their strategy based on glucose availability, resulting in population-level heterogeneity.
      </p>
      <p>
        This contrasts with traditional game-theoretical models that assume distinct subpopulations with fixed strategies. The study uses stochastic simulations to explore the model's behavior under varying glucose conditions and proposes an experimental method to distinguish between mixed-strategy and distinct-subpopulation scenarios.
      </p>
      <div class="pub-links">
        <a href="https://doi.org/10.1016/j.jtbi.2021.110912">Paper</a>
        <a href="https://github.com/Kalirad/Making_ATP_fast_and_slow">GitHub</a>
      </div>
    </div>
    <div>
      <img src="gameTheory.png" alt="Regulatory network for ATP-producing pathways">
      <p class="figure-note">Figure 7: A regulatory switch between fermentation and respiration.</p>
    </div>
  </article>
</section>
