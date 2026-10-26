UDCT v7.14: Exploratory QUMOND Hessian and Phase-Space Consistency Tests (Steps 01–50)

Author: Won Shik Paik
Affiliation: Independent Researcher, Auckland, New Zealand
Version: v7.14
Publication date: 27 October 2026
Research status: Pre-preregistration exploratory working paper

Publication and Repository

Zenodo DOI: https://doi.org/10.5281/zenodo.23663161

GitHub repository: https://github.com/wspaik5/UDCT_v7.14_PrePreregistration_Exploratory

Overview

UDCT v7.14 consolidates 50 stages of exploratory computational research concerning gravitational-field structure, three-dimensional Hessian diagnostics, Jeans-equation consistency, and phase-space distribution-function (DF) positivity in dwarf-galaxy-motivated modified-gravity models.

The study builds on QUMOND and discusses its relationship to Milgrom's 2023 generalized QUMOND (GQUMOND) framework. Computing Hessian diagnostics does not, by itself, establish implementation of the complete GQUMOND field equations.

The objective is to document numerical results, mathematical assumptions, consistency boundaries, and reproducibility evidence rather than claim a new validated gravitational theory.

Principal Findings

1. Hessian and Jeans Diagnostics

The earlier stages investigate gravitational-field derivatives, Hessian behavior, and Jeans-equation consistency.

Hessian eigenvalues, Jeans second moments, phase-space DF positivity, and dynamical stability are distinct physical and mathematical tests. Their results must not be treated as interchangeable.

2. Distribution-Function Positivity

The later computational branch studies an isolated spherical Plummer gravitational source with a family of tracer-density profiles.

Under the stated central-scaling and regularity assumptions, the leading asymptotic DF coefficient changes sign around the tracer-shape exponent p = 1.5.

At exactly p = 1.5, the leading coefficient vanishes. The sign of the complete DF at equality remains unresolved without higher-order analysis.

This is a conditional asymptotic result, not a universal positivity boundary for all modified-gravity models.

3. Osipkov–Merritt Anisotropy

Step 50 identifies a local finite-window tangency at approximately:

- Tracer-shape exponent: p = 1.5
- Anisotropy radius: r_a/a = 0.466466787396
- Tangency location: r/a = 0.474097552832
- Investigated radial interval: 0.25 ≤ r/a ≤ 0.75

This result applies to the specified model and numerical window. It does not establish global DF positivity across the complete accessible energy domain.

4. Hydrus I and Observational Scope

Hydrus I provides observational motivation and selected model inputs.

Observationally motivated model calculations are not equivalent to directly fitting the complete individual-star line-of-sight velocity dataset.

The early three-dimensional Hessian calculations and the later isolated spherical DF inversions are separate computational branches.

Files

The repository contains:

- UDCT_v7.14_Detailed_Paper_Download.pdf — Comprehensive 20-page research paper with mathematical discussion, numerical findings, figures, limitations, and step-by-step technical commentary.
- UDCT_v7.14_Reproducibility_Download.zip — Archived reproducibility materials accompanying the research paper.

For detailed equations, source-level explanations, figures, and individual computational stages, consult the PDF and the ZIP archive.

Reproducibility and Limitations

Earlier archived audits reported successful reexecution of five selected scripts and agreement across 13 generated output files.

Independent replication of all 50 computational stages has not been established.

Negative phase-space DF values indicate inconsistency under the specified equilibrium potential, tracer-density, and anisotropy assumptions. They do not independently establish dynamical instability or falsify MOND, QUMOND, or GQUMOND generally.

This publication is an exploratory research record, not a completed confirmatory preregistration or peer-reviewed observational validation.

Selected References

1. Bekenstein, J., & Milgrom, M. (1984). Does the missing mass problem signal the breakdown of Newtonian gravity? Astrophysical Journal, 286, 7–14. https://doi.org/10.1086/162570
2. Milgrom, M. (2010). Quasi-linear formulation of MOND. Monthly Notices of the Royal Astronomical Society, 403, 886–895. https://doi.org/10.1111/j.1365-2966.2009.16184.x
3. Milgrom, M. (2023). Generalizations of quasilinear MOND. Physical Review D, 108, 084005. https://doi.org/10.1103/PhysRevD.108.084005
4. Koposov, S. E., et al. (2018). Snake in the Clouds: a new nearby dwarf galaxy in the Magellanic bridge. Monthly Notices of the Royal Astronomical Society, 479, 5343–5361. https://doi.org/10.1093/mnras/sty1772
5. Wolf, J., et al. (2010). Accurate masses for dispersion-supported galaxies. Monthly Notices of the Royal Astronomical Society, 406, 1220–1237. https://doi.org/10.1111/j.1365-2966.2010.16753.x
6. Walker, M. G., & Peñarrubia, J. (2011). A method for measuring (slopes of) the mass profiles of dwarf spheroidal galaxies. Astrophysical Journal, 742, 20. https://doi.org/10.1088/0004-637X/742/1/20
7. McGaugh, S. S., Lelli, F., & Schombert, J. M. (2016). Radial acceleration relation in rotationally supported galaxies. Physical Review Letters, 117, 201101. https://doi.org/10.1103/PhysRevLett.117.201101

Future Research

Subsequent investigations may address the higher-order DF asymptotics at p = 1.5, full-energy-domain positivity, alternative anisotropy prescriptions, external-field effects, and direct observational comparisons with individual stellar velocities.

A more extensive mathematical and source-by-source commentary may be published separately.

Citation

Paik, W. S. (2026). UDCT v7.14: Exploratory QUMOND Hessian and Phase-Space Consistency Tests (Steps 01–50) (Version v7.14). Zenodo.

https://doi.org/10.5281/zenodo.23663161

License

The Zenodo publication is distributed under the Creative Commons Attribution 4.0 International (CC BY 4.0) license.
