# Tests_with_SynthMorph
This repository contains the code I used during my six months internship at KTH Royal Institute of Technology in Flemingsberg. The goal of these codes is to see how SynthMorph reacts with images from the projection data domain and the code I used to see if it was possible to train SynthMorph with this same kind of data.

To carry out these tests, I used the Synthmorph demo code, which can be found at the following link: https://colab.research.google.com/drive/1GjpjkhKGrg5W-cvZVObBo3IoIUwaPZBU?usp=sharing

In all the code where sinograms are generated, I used the foreward projection operator from a public GitHub: https://github.com/odlgroup/odl/blob/master/examples/tomo/filtered_backprojection_cone_2d.py

In order to skip SynthMorph training and save time, I have used in some notebooks a file with the weights of the model already trained with pairs of 2D label maps. In the notebooks the file is explicitly named weights_of_the_U-Net_trained_with_2D_label_maps.h5. 
This file can be recovered via the following link: https://drive.google.com/uc?id=1xridvtyEWgWsWJPYVrQfDCtSgbj2beRz
