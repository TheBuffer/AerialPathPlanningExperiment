# AerialPathPlanningExperiment
Semantic Segmentation and Path Planning on Aerial Images Experiment

A Machine Learning experiment using a U-Net Model and a Probabalistic Road Map Planner to Find obstacles and plot a path from start point to the end point on a given Aerial Map

Consists of 2 ipynb Notebooks

NOTEBOOK 1 - SegmentationLearning.ipynb : Used to build a Unet model with a VGG19 Encoder and Train it on the dataset

NOTEBOOK 2 - SegmentAndPathFinding.ipynb : Used to load the trained weights of the Unet Model, finds out the point obstacles in the aerial picture and uses a PRM Planner to plot a path through it, and translates it into instructions as well as a visual representation.

Dataset Used: http://dronedataset.icg.tugraz.at

![alt text](https://https://github.com/TheBuffer/AerialPathPlanningExperiment/blob/main/aerialpicture.png?raw=true)

![alt text](https://https://github.com/TheBuffer/AerialPathPlanningExperiment/blob/main/roadplot.png?raw=true)