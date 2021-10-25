# Train Eigenfaces

Simple model that trains on a preprocessed excerpt of the “Labeled Faces in the Wild”, aka [LFW](http://vis-www.cs.umass.edu/lfw/)

This demo was taken from [Scikit-learn](https://scikit-learn.org/stable/auto_examples/applications/plot_face_recognition.html)

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
