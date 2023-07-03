# Kvasir_Deep_Learning_Classification
For a CNN, use diagrams and a keras model, give the workings how to calculate the
number of parameters created by each operation, give an intuitive explanation of the
operation, design an example(s) that shows and explains the input and output for:
a) a 2D input image with a 1D conv operation,
b) a 3D input with a 2D conv,
c) a 2D input with a 3D conv.


CNN deep learning modelling in python, for early detection of Gastrointestinal diseases using Image Classification.
Here you are required to analyse the Kvasir-V2 dataset, 2.3GB, https://datasets.simula.no/kvasir/
Details are also given here: https://dl.acm.org/doi/pdf/10.1145/3083187.3083212. A useful github
repository is here: https://github.com/AfraHussaindeen/Kvasir-Dataset.
(i) Split the dataset random into train/validation/test 70:15:15 using set seed.
(ii) Find a baseline model, different to the one given in github. Give your performance and
compare to the model in the github reference. Explain what each layer of your network
is doing. Analyse the training curves.
(iii) Change some of the model parameters, e.g. number of layers, number of filters, number
of nodes in fully connected layers and show how this effects performance. Note best to
have a well performing small model. Explain also in your own words why the model’s
performance changes/does not change and analyse the training curves.
(iv) Complex. Change your model and analyse the new results and training curves using one
or more concepts; give an intuitive understanding of the concepts; suggestions on
concepts are:
a. Transfer learning
b. Effect of resizing the image
c. Using the following paper as a reference, https://arxiv.org/pdf/2201.03545.pdf, can
you implement 2-3 changes to see if this improves performance. Mixup and cutmix
are options here.
(v) As this dataset is not very large is it important to analyse the variability in the results.
Explain how you can analyse this variability?
