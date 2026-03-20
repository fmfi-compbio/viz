--
title: Microbes Dataset
---

## Description

[American Gut Project](https://microsetta.ucsd.edu/american-gut-project/) collected stool samples from thousands of volunteers across the United States and identified their microbial composition using DNA sequencing. The data set also includes metadata about the volunteers, such as their diet, lifestyle, and health status. 

We will use microbial composition data preprocessed by the [Human Microbiome Compendium](https://microbiomap.org/) available on [Zenodo](https://zenodo.org/records/15122187) under the CC BY 4.0 license. The metadata about each sample were downloaded from the European Nucleotide Archive (ENA) using the study accession [PRJEB11419](https://www.ebi.ac.uk/ena/browser/view/PRJEB11419). 

## Files

* [`gut_taxonomic_table.csv`](./gut_taxonomic_table.csv): a table containing samples as rows and taxonomic groups as columns. Each cell contains the abundance of a particular taxonomic group in a given sample. The first column contains the sample ID within the set and the second column contains the project ID and the run ID (ERR).
* [`sample_data.csv`](./sample_data.csv): a table containing metadata for each sample, including the sample ID, run ID, title, and various metadata fields about the person who provided the sample (e.g., age, diet, health status). 

## Taxonomic levels

Each column in `gut_taxonomic_table.csv` represents some taxonomic group of microbes given by a list of hierarchical categories. For example column named `Bacteria.Bacillota.Bacilli.Lactobacillales.Lactobacillaceae.Lentilactobacillus` represents the genus Lentilactobacillus, which belongs to the family Lactobacillaceae, order Lactobacillales, class Bacilli, phylum Bacillota, and domain Bacteria. Each cell in that column contains the number of DNA sequencing reads that could be assigned to that taxonomic group in a given sample, which is a proxy for the relative abundance of that group of bacteria in the sample. 

Sometimes lower taxonomic levels may be missing, such as column `Archaea.Halobacteriota.NA.NA.NA.NA` which represents the number of reads that were classified at the phylum Halobacteriota in the domain Archaea, but the class, order, family, and genus levels could 
not be determined. 

It is customary to analyze the data at a specific taxonomic level, such as the family level, by summing the abundances of all taxa that belong to the same family. It is also a good idea to normalize the abundances to account for differences in the total number of sequencing reads obtained for different samples. This can be done by dividing each count by the total count in that sample. Samples with a low total count may be filtered out to avoid noise in the analysis.

## References

These two papers describe the data set and its processing in more detail. They may be hard to follow and use complex methods. You can take some inspiration but much simpler methods will be sufficient for our purposes.

* McDonald, D., Hyde, E., Debelius, J.W., Morton, J.T., Gonzalez, A., Ackermann, G., Aksenov, A.A., Behsaz, B., Brennan, C., Chen, Y. and DeRight Goldasich, L., 2018. American gut: an open platform for citizen science microbiome research. Msystems, 3(3), pp.10-1128. <https://doi.org/10.1128/msystems.00031-18>
* Abdill, R.J., Graham, S.P., Rubinetti, V., Ahmadian, M., Hicks, P., Chetty, A., McDonald, D., Ferretti, P., Gibbons, E., Rossi, M. and Krishnan, A., 2025. Integration of 168,000 samples reveals global patterns of the human gut microbiome. Cell, 188(4), pp.1100-1118. <https://doi.org/10.1016/j.cell.2024.12.017>
