# AerialPathPlanningExperiment
Semantic Segmentation and Path Planning on Aerial Images Experiment

A Machine Learning experiment using a U-Net Model and a Probabalistic Road Map Planner to Find obstacles and plot a path from start point to the end point on a given Aerial Map

Consists of 2 ipynb Notebooks

NOTEBOOK 1 - SegmentationLearning.ipynb : Used to build a Unet model with a VGG19 Encoder and Train it on the dataset

NOTEBOOK 2 - SegmentAndPathFinding.ipynb : Used to load the trained weights of the Unet Model, finds out the point obstacles in the aerial picture and uses a PRM Planner to plot a path through it, and translates it into instructions as well as a visual representation.

Dataset Used: http://dronedataset.icg.tugraz.at

![aerialpicture](https://user-images.githubusercontent.com/62299190/220090323-e13dd088-431a-4dca-bc29-a34706087048.png)            
![roadplot](https://user-images.githubusercontent.com/62299190/220090388-bc8c3238-1293-4097-90ea-2c355022875c.png)
