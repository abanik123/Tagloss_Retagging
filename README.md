# Project Title: Modelling tag loss and retagging without permanent individual identification: An application to Antarctic fur seals
<h1>Project Overview</h1>

<p>
This repository contains R code, simulation scripts, and datasets used for modelling the tag-loss-retagging dynamics without a permanent mark
of Antarctic fur seals at Macquarie Island, Australia. The project is organized into three main components:
</p>

<ul>
    <li><strong>Case_Study Codes</strong> – R code for fitted models applied to the datasets.</li>
    <li><strong>Case_Study Data</strong> – Datasets corresponding to the case studies.</li>
    <li><strong>Simulation_Study Codes</strong> – Simulation scripts for evaluating model performance.</li>
</ul>

<p>
The models implemented include:
</p>
<ul>
    <li>Single-Regime (Homogeneous) Tag Retention Model</li>
    <li>Multi-Regime Tag Retention Model</li>
</ul>

<hr>
<h2>1. Case_Study Codes/</h2>

<p>This folder contains R code for two of our model formulations used for analysing the case study data:
</p>

<ul>
    <li>Single-Regime (Homogeneous) Tag Retention Model</li>
    <li>Multi-Regime Tag Retention Model</li>
</ul>

<p>
These scripts reproduce the case-study results presented in the associated research paper.
</p>

<h2>2. Case_Study Data/</h2>

<p>
This folder contains datasets used corresponding to the two model formulations:
</p>

<ul>
    <li> For Single-Regime (Homogeneous) Tag Retention</li>
    <li> For Multi-Regime Tag Retention</li>
</ul>

<hr>
<h2>3. Simulation_Study Codes/</h2>

<p>
This directory includes R scripts used to conduct simulation studies.
The provided scripts simulate a baseline scenario; however, users can modify the parameter values 
to match other scenarios using the values described in the paper.
</p>

<hr>

<h2>Requirements</h2>

<ul>
    <li>R (4.5.1)</li>
    <li>R packages commonly used for Bayesian modelling (e.g., <code>nimble</code>, <code>MCMCvis</code>, <code>tidyverse</code>,
      <code>dplyr</code>, <code>abind</code>)</li>
</ul>

<hr>

<h2>Usage</h2>

<ol>
    <li>Navigate to <strong>Case_Study/</strong> to reproduce analysis for this case study.</li>
    <li>Navigate to <strong>Simulation_Study/</strong> to run simulation experiments or modify parameters.</li>
    <li>Use the datasets in <strong>Data/</strong> when running or adapting scripts.</li>
</ol>
