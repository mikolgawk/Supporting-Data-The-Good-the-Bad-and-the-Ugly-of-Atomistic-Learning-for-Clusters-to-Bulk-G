# Supporting Data — The-Good-the-Bad-and-the-Ugly-of-Atomistic-Learning-for-Clusters-to-Bulk-Generalization

This repository contains supporting datasets and training scripts used in the study "The Good, the Bad, and the Ugly of Atomistic Learning for Clusters-to-Bulk Generalization". It provides dataset partitions, example input files, pre-trained heads, and a collection of training scripts (with and without gradient information) for experiments on cluster-to-bulk transfer learning.

## Repository Layout

- `datasets/`
	- `pre_trained_head/` — pre-trained head file.
	- `training_data/`
		- `delta_learning/` — datasets prepared for delta-learning training.
		- `direct_transfer_learning/` — datasets for direct and transfer learning training.
	- `validation_data/` — validation files.

- `training_scripts/`
	- `training_with_gradients/` — training scripts with gradients on.
	- `training_without_gradients/` — training scripts with gradients off.
	- Each of the above contains subfolders for `delta_learning`, `direct_learning`, `multihead_finetuning`, and `singlehead_finetuning`.






