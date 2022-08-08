#RNAloc_MPRA

code related to manuscript https://www.biorxiv.org/content/10.1101/2021.04.27.441590v1

all scripts are written for python=3.7.6, pandas=1.0.1, Bio=1.76

mapping_barcodes_and_umis:
Jupyter notebook for mapping library barcodes and counting unique molecular identifiers in targeted sequencing of the 3'UTR reporter library. Sample data is provided in the folder example_data.

LibraryDesign:
Jupyter notebook of the design of the full 3'UTR library starting from previously published datasets provided. Note that in the subset where RBP motifs are being mutated a randomly generated sequence is introduced. The exact sequence will be different in every run so that the resulting library is (in these specific variants) not necessarily identical to the one used for MPRA testing.
