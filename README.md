# TensorBoard


This project provides a Tensorboard AMP "plugin" for Cloudera Machine Learning (CML).  

As stated on Tensorflow's homepage, [TensorBoard](https://www.tensorflow.org/tensorboard/)  provides the visualization and tooling needed for machine learning experimentation:

- Tracking and visualizing metrics such as loss and accuracy
- Visualizing the model graph (ops and layers)
- Viewing histograms of weights, biases
- Projecting embeddings to a lower dimensional space
- Displaying images, text, and audio data
- Profiling TensorFlow programs



The AMP comes prepopulated with 

**Tracking Visualizations** (loss and accuracy)

**A Model Graph** 

![](/images/TensorboardGraphs.png)

**Visualizations of Weights and Biases** 

![](/images/TensorboardHistograms.png)



To launch this project on CML:

**As ML Prototype** - In a CML workspace, click "New Project", add a Project Name, select "ML Prototype" as the Initial Setup option, copy in the [repo URL](https://github.com/hortonworks-sk/tensorboard-cml-amp.git), click "Create Project", click "Configure Project"