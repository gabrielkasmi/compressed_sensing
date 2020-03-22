# Readme 

This folder contains the material necessary to the replication of our experiments. 

## Organization of the folder
The folder is organized as follows : 

The folder ``images`` contains miscellaneous plots and images generated throughout our study 

The folder ```generative_model``` contains a script to build and train a GAN on you local machine and a notebook if you prefer to run it on Google Collab

The folder ```report``` contains the ```.pdf``` files of our theoretical report and of the slides.

The notebook ```cs_replication_mnist``` contains our experiments

The model ```generator_model_100.h5``` is a generator trained on 100 epochs, used in our replication


## Description 

The main file is ```cs_replication_mnist``` which contains our reconstruction of MNIST items using the LASSO method and our trials with the generative methods. The goal was to replicate Bora et al (2017) results with our custom-made generators.

The report (```report.pdf```) as well as the slides of the presentation (```beamer.pdf```) can be found in the ```report``` folder.

To this end, we wrote and trained a GAN on the MNIST dataset. The trained generator is in the file ```generator_model_100.h5```. We trained our model on 100 epochs using in practice for computationnal reasons Google's Collab tool. 

To train your own GAN on the MNIST dataset on your local machine, you can run the script ```generative_model.py```. Alternatively, you can run the notebook ```train_mnist_gan```. <b>Warning </b>:  training on a CPU may take hours. 
