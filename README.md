# Scenario and model files of *Thermoanaerobacter kivui*

This repository contains the metabolic model and scenarios used to analyze glucose metabolism in *Thermoanaerobacter kivui*. It uses CNApy [1] and Escher [2]-based visualization.

The scenario model variants are:

- wild type as ``wt_glucose_all_fluxes.scen``
- MTHFR2fdx knockout (Δ*metVF*) as `metVFKO_glucose_all_fluxes.scen`
- MTHFR2fdx knock-out and MTHFR2nadh knock-in (Δ*metVF ldh::metF*) as `metVFKO_metFKI_glucose_all_fluxes.scen`

The model is named `Tkivui.sbml` having an respective CNApy project `Tkivui.cna`. It was created based on an *A. woodii* model [3]. All details of what was changed can be found under the respective publication supplements under the title:

**Disrupting the Wood-Ljungdahl pathway in the thermophilic acetogenThermoanaerobacter kivui facilitates high yield hydrogen production**

## Reference

[1] [CNApy: a CellNetAnalyzer GUI in Python for analyzing and designing metabolic networks](https://doi.org/10.1093/bioinformatics/btab828)

[2] [Escher: A Web Application for Building, Sharing, and Embedding Data-Rich Visualizations of Biological Pathways](https://doi.org/10.1371/journal.pcbi.1004321)

[3] [Thermodynamic metabolic modeling of growth and bioproduction potential of the acetogen Acetobacterium woodii with and without redox cofactor swaps](https://doi.org/10.1016/j.synbio.2026.05.007)
