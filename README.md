# Cat-Dog-Classifier
Transfer learning allows us to train deep networks using significantly less data then we would need if we had to train from scratch. With transfer learning, we are in effect transferring the “knowledge” that a model has learned from a previous task, to our current one. The idea is that the two tasks are not totally disjoint, and as such we can leverage whatever network parameters that model has learned through its extensive training, without having to do that training ourselves.

This model can classify cats and dogs using a Deep Learning model. This model was made using transfer learning(MobileNet). It has a val_accuracy = 94%.
This model has been trained for 5 epochs.

## Dependencies
Keras conda installation
> conda install -c conda-forge keras

OpenCV conda installation
> conda install -c conda-forge opencv

Numpy conda installation
> conda install -c anaconda numpy




