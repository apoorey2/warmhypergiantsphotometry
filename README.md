Photometric Variability of Warm Hypergiants in M31 & M33

Authors: Ashi Poorey, Prof. John Martin

Abstract

Warm Hypergiants (WHGs) are rare, extremely luminous A–F type supergiants occupying a transitional region of the Hertzsprung–Russell diagram near the Humphreys–Davidson limit and the yellow void. These stars are believed to undergo unstable evolutionary phases accompanied by enhanced mass loss, making them important laboratories for understanding the late stages of massive stellar evolution.

This project investigates long-term photometric variability in ten Warm Hypergiants located in the nearby galaxies M31 and M33 using more than twelve years of optical photometry. The primary goal is to determine whether these stars exhibit statistically significant periodic variability capable of driving atmospheric instability and episodic mass-loss events.

Time-series analysis combines weighted Lomb–Scargle periodograms, red-noise modeling, bootstrap significance testing, and phase-folded light-curve analysis. In addition to searching for periodic signals, the project characterizes stochastic variability through comparisons of power-law, autoregressive (AR(1)), and white-noise models using Whittle likelihood statistics. Candidate periods are evaluated against both white-noise and red-noise false alarm thresholds to distinguish genuine stellar variability from correlated noise processes.

The resulting variability classifications reveal a diverse population, including stars exhibiting short-period oscillations, multi-year variability, and objects dominated by stochastic red-noise behavior. These results provide insight into the role of pulsations and atmospheric instability in shaping the evolutionary pathways of massive stars.

⸻

Project Overview

Warm Hypergiants are among the most luminous evolved stars known and may represent a brief transitional phase between Red Supergiants, Luminous Blue Variables, and other evolved massive-star populations. Understanding their variability is critical for constraining mass-loss mechanisms and late-stage stellar evolution.

This project combines photometric time-series analysis, statistical modeling, and astrophysical interpretation to investigate variability across a sample of ten Warm Hypergiants in M31 and M33.

⸻

Data & Methods

Data Sources

* Multi-epoch V-band photometry spanning approximately 12 years
* 10 Warm Hypergiants located in M31 and M33
* Archival observations compiled through the Local Group Galaxy Survey monitoring program

Analysis Pipeline

Data Preparation

* Removal of invalid photometric measurements
* Quality filtering using magnitude uncertainties
* Construction of calibrated light curves
* Measurement of variability amplitudes

Period Search

* Weighted and unweighted Lomb–Scargle periodograms
* Frequency searches spanning days to decade-scale periods
* Detrended light-curve analysis
* Best-period identification from peak periodogram power

Statistical Significance Testing

* False Alarm Probability (FAP) calculations
* Bootstrap resampling methods
* White-noise false alarm levels
* Red-noise false alarm levels derived from simulated variability distributions

Red Noise Characterization

To distinguish true periodicity from stochastic variability, multiple noise models are fit to each star:

* Power-law noise models
* Autoregressive AR(1) processes
* White-noise models

Model parameters are estimated using Whittle likelihood optimization and compared through negative log-likelihood statistics.

Bootstrap Simulations

* 1000+ Monte Carlo realizations per target
* Parameter distribution estimation
* Confidence interval determination
* Empirical significance thresholds for period detection

Visualization

* Light curves with photometric uncertainties
* Lomb–Scargle periodograms
* Red-noise significance spectra
* Zoomed period-detection diagnostics
* Phase-folded light curves
* Model-comparison visualizations

⸻

Results

Preliminary analysis reveals a diverse range of variability behaviors:

* Stars exhibiting highly significant periodic variability
* Stars with variability on timescales ranging from weeks to several years
* Objects dominated by stochastic red-noise processes
* Evidence that some candidate periods remain significant even after accounting for correlated noise

The project enables robust separation of genuine periodic signals from noise-driven variability, providing stronger constraints on the physical mechanisms operating in Warm Hypergiant atmospheres.

⸻

Scientific Goals

* Identify statistically significant periodic variability in Warm Hypergiants
* Quantify the role of stochastic red-noise processes in massive-star variability
* Investigate whether pulsations contribute to enhanced mass-loss episodes
* Improve observational constraints on the evolutionary state of Warm Hypergiants
* Compare variability behavior across the M31 and M33 populations

⸻

Skills & Tools Applied

Astronomy & Astrophysics

* Stellar evolution
* Massive-star variability
* Photometry
* Time-domain astronomy

Statistical Methods

* Lomb–Scargle periodograms
* False Alarm Probability analysis
* Red-noise modeling
* AR(1) processes
* Power-law spectral analysis
* Bootstrap resampling
* Monte Carlo simulations
* Whittle likelihood estimation

Software & Programming

* Python
* NumPy
* SciPy
* Astropy
* Matplotlib
* Time-series analysis pipelines
* Scientific data visualization


References
Ejaz, A., Dodson-Robinson, S., & Haley, C. (2025, December 20). Red noise-based false alarm thresholds for astrophysical periodograms via Whittle’s approximation to the likelihood. arXiv.org. https://arxiv.org/abs/2512.18205
