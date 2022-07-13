# Stony Rise Insect Light-trapping 1992-2019

Jupyter notebook to visualise data from a long-term insect light-trapping dataset published to Zenodo as a Darwin Core Archive including sample events and representative images of many of the recorded species.

See [Catches of numerous insect species in Rothamsted 160W light trap at Devonport, Tasmania, 1992-2019](https://doi.org/10.5281/zenodo.6793249). The data may also be [accessed through GBIF](https://www.gbif.org/dataset/044f96bc-3bf2-4a38-9f7c-8808ab48dbf1).

The dataset ZIP file includes the following files used in this notebook:

 * **event.csv** - Darwin Core sample event records for each period in which insects were collected in the trap
 * **taxon.csv** - Darwin Core taxon records for each species (or operational taxonomic unit) sampled and monitored for at least some part of the period 1992-2019, including identifiers for the first and last events in which the species was monitored and, where representative images exist for these taxa, paths to the image files inside the ZIP file
 * **occurrence.csv** - Darwin Core occurrence records indicating presence/absence and counts of individuals for each taxon in each event in which it was monitored
 * **image/** - Folder containing image files referenced in taxon.csv