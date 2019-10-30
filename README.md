# literate-umbrella
## How to use

  * Clone repo and `pip install -r requirements.txt` 
  * Run python train.py the model will train only for 5 epochs
  * Start the mlflow ui by typing `mlflow ui` 
  * Go to `localhost:5000` to see the ui
  
Model weights can be downloaded through the ui


TODO; The weights are saved already in /storage/snapshots in production but they are only copied when the training is over, I should look into it how to copy them faster so this is shown in the MLflow UI.
callback ModelCheckpoint from keras saves the weights after every epoch, implement this in the mlflow example to show the functionality.






