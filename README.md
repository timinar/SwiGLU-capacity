# I compare the information capacity of SwiGLU and MLP layers

The information capacity is defined as the maximum size of the random dataset with random binary layers that can be learned by the model.

`capacity-animations.ipynb` contains the code to generate the plots and animations of the two-dimensional case, where the inputs can be plotted directly, and the labels are color-coded. We train a model on a small dataset with number of samples close to the number of parameters. Then we visualize the decision boundary by labelling a grid of points.