# machine-learning-alloys-search
Data fore the article: "Accelerating high-throughput searches for new alloys with active learning of interatomic potentials" by K.Gubaev et. al

Contains training sets and equilibrated structures for CuPd, CoNbV and AlNiTi alloys.

In "CuPd" and "CoNbV" folders the training sets are in "train.cfg" files and the structures equilibrated by MTP are in "relaxed.cfg" files.

In "AlNiTi" folder the training sets for the corresponding stages of relaxation are in "train_1st_stage.cfg" and "train_2nd_stage.cfg" files. 

The structures equilibrated at different stages are in "relaxed_1st_stage.cfg" and "relaxed_2nd_stage.cfg" files. 

The structures from the "relaxed_2nd_stage.cfg" file, which lie within 1-,2-,3- and 4-sigma intervals from the convex hull built by MTP are in files "chosen_1sigma.cfg", ..., "chosen_4sigma.cfg" files.
