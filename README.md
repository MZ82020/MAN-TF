# Geometry-Aware Deep Learning for 3D Skeleton-Based Motion Prediction

## Overview

In this paper, we propose a novel approach, MAN-TF, which combines Kendall's shape space with Lie group representations and transformers for accurate body movement characterization, with a focus on improving long-term prediction accuracy. 
In doing so, we model both rigid and non rigid transformations of the skeletons involved in human motion for smooth and plausible predictions in long-term horizons.

<img width="635" alt="Capture d'écran 2024-12-01 211716" src="https://github.com/user-attachments/assets/bfed4f4b-c23a-4e8a-a516-1fd6b469306f">

## Datasets

* H3.6m dataset is a 3D human pose dataset containing 3.6 million human poses.
Please visit http://vision.imar.ro/human3.6m/ in order to request access and contact the maintainers of the dataset.

* To obtain the GTA-IM dataset please check: https://github.com/ZheC/GTA-IM-Dataset#requesting-dataset 

* To obtain the PROX dataset please check: https://prox.is.tue.mpg.de/

## Train and Test

* Run the following jupyter "Train&Test_Transformer_Kendal_Lie_Human" to train and test the model in H3.6m

* Run the following jupyter "Train&Test_Transformer_Kendall_Lie_Gta" to train and test the model in GTA-IM

* Run the following jupyter "Train&Test_Transformer_Kendall_Lie_Prox" to train and test the model in PROX 

## Citation

If you find this useful, please cite our work as follows:

```
Not available.
```

## Notes
The repository is still under construction. Please let me know if you encounter any issues.

Best, 

