# Epigenetic Data Boosts the Accuracy of Recombination Hotspot Prediction by Machine Learning Models

## Introduction

Genetic recombination plays an integral role in generating genetic diversity in a population, but the mechanisms of the
processes governing double-strand break (DSB) formation and subsequent ligation remain poorly understood. Recent
advances in machine learning as applied to genetic data have demonstrated an ability to predict the location of
recombination hotspots in the genome based on raw DNA sequences. However, these models neglect potential contributing
factors from epigenetic marks and chromatin structure. Specifically, H3K4me3 and H3K36me3 are known to be correlated
with the activity of PRDM9, a zinc finger protein that plays a role in determining sites of recombination in humans and
mice, and open chromatin structure is required for the activity of the DSB-forming protein, Spo11. Furthermore, some
correlation may exist between hotspot regions and SNP density. We demonstrate using simple classification models that
the accuracy of hotspot prediction is significantly improved with the inclusion of ChIP-Seq epigenomic data, DNase
hypersensitivity data, and Single Nucleotide Polymorphism (SNP) density data. A similar trend was observed in our deep
learning model consisting of a hybrid deep convolutional and recurrent neural network trained on the new datasets as
added features. This allowed us to produce a comprehensive predictive model for locations of hotspots in the human
genome. Concurrently, we utilized the Gibbs sampling motif discovery technique in an attempt to discover binding motifs
for Spo11 and PRDM9. These results combined will help shed light on the mechanisms of recombination and set the stage
for better informed GWAS and linkage analysis studies.

## Links

[Report](https://github.com/lcwong0928/hotspot-prediction/blob/main/results/report.pdf) \
[Presentation](https://github.com/lcwong0928/hotspot-prediction/blob/main/results/presentation.pdf)
