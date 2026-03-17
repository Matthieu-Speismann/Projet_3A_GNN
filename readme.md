### You'll need to create a virtual environment in which you'll install the `requirments.txt` file. 
This should avoid majority of the incompatibility issues. I personnaly used Python 3.11.9 during this project.

- If you enconter difficulties with the dependencies and incompatibilities concerning Keras and Tensorflow:
1. The `.ipynb` files always start by checking the imports. If it run wells (by printing the versions of your modules) you're free to go. 
2. Otherwise, try [configuring](https://github.com/tensorflow/gnn/blob/main/tensorflow_gnn/docs/guide/keras_version.md) your TensorfFlow module.

### Datasets' source:
1. Mutag: https://storage.googleapis.com/download.tensorflow.org/data/mutag.zip
   from the official TensorFlow-GNN exemple: https://github.com/tensorflow/gnn/blob/main/examples/notebooks/intro_mutag_example.ipynb
3. Mutagenicity: https://networkrepository.com/Mutagenicity.php 
