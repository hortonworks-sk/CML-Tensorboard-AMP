# TensorBoard


This project provides a Tensorboard AMP "plugin" for Cloudera Machine Learning (CML).  

As stated on Tensorflow's homepage, [TensorBoard](https://www.tensorflow.org/tensorboard/)  provides the visualization and tooling needed for machine learning experimentation:

- Tracking and visualizing metrics such as loss and accuracy
- Visualizing the model graph (ops and layers)
- Viewing histograms of weights, biases
- Profiling TensorFlow programs



The AMP comes prepopulated with 

**Tracking Visualizations** (loss and accuracy)

**A Model Graph** 

![](/images/TensorboardGraphs.png)

**Visualizations of Weights and Biases** 

![](/images/TensorboardHistograms.png)



**To launch this project on CML As ML Prototype** 

1. In a CML workspace, click "New Project" 
2. Add a Project Name, 
3. Select "ML Prototype" as the Initial Setup option, copy in the [repo URL](https://github.com/hortonworks-sk/tensorboard-cml-amp.git), 
4. Click "Create Project"
5. Navigate to the newly created project
6. In the project click "Launch Project"

Tensorboard Take 5 minutes to install 

**To Access Tensorboard, after insallation** 

1. Click Applications in the leftt menu within CML
2. Click Tensorboard UI in the list of applications

