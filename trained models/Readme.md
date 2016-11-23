To load the model you can use the PICKLE library of from python

## Storing the model
import pickle
pickle.dump(model,open(filename,"wb"))

## Loading the model
loaded_model = pickle.load(open(filename,"rb"))
score = loaded_model(training_features,labels)
