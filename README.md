# Train Eigenfaces

Simple model that trains on a preprocessed excerpt of the “Labeled Faces in the Wild”, aka [LFW](http://vis-www.cs.umass.edu/lfw/)

The dataset includes 7 classes (individuals):

Ariel Sharon
Colin Powell
Donald Rumsfeld
George W Bush
Gerhard Schroeder
Hugo Chavez
Tony Blair

## To run:

`poetry run train`

This will train your model and save it in the `model` folder. It will also compute the predictions for the test dataset
