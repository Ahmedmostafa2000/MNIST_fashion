# fashion_Mnist
I wanted to upload a cnn on fashion_mnist because it is kind of more challenging than mnist, but then I realised I made the same model that I did on mnist, So I decided to use keras_tuner and try it for the first time and make some change

keras tuner is basicly a tuning library that uses combinations but also evaluates the models on the way

For one epoch the model with the mnist architicture got 75% accuracy and got 85% for two epochs

Using tuning the model was able to identify the best parameters for one epoch to achieve 86%, on the cost of trying the 12 model combinations though, but I think it is fair because I could add more epochs on the best model and be sure that it is the best choice of hyperbarameters

### Note: I removed the output of the tuning search cell because the verbose kind of lagged
