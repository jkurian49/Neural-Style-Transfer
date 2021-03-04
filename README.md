# Neural-Style-Transfer

This implementation of neural style transfer (NST) algorithm is a component of the Transformation project for ECE471 Machine Learning in Architecture. NST was implemented in Tensorflow according to [1] and is an adaption of the original algorithm from the 2015 paper by Gatys et al. [2].


The provided Colab file can be used to apply NST to an arbitrary set of user-provided content and style images. After cloning this repo in the first cell, add your own style and content images into the respective folders, then run the rest of the cells. The program will output a zip file containing the stylized images produced from all possible combinations of style and content images. 

## References
[1] https://www.tensorflow.org/tutorials/generative/style_transfer
[2] https://arxiv.org/abs/1508.06576
