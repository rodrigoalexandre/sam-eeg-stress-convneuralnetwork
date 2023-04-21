<div align="center">

# sam-stress-convneuralnetwork-keras

<div align="justify">
Project developed for the study presented in the article "A Convolutional Neural Network model to detect stress levels in electroencefalogram signals".
<br><br>
This study proposes a Convolutional Neural Network (CNN) model for classifying stress levels using electroencephalogram data. The model was trained on data from the SAM 40 Dataset. This dataset has records of brain activity of 40 individuals who were monitored while performing certain stress-inducing activities. The CNN model achieved an accuracy rate of 99.34% in predictions.
<br><br>
The CNN model performed better (accuracy vs. computational costs) than the Multilayer Perceptron (MLP) model proposed in the sam-stress-multilayerperceptron-keras project, as can be seen in the following comparative table:
<br><br>
| Model | Project                                 | Teste Accuracy | Trainable Parameters | Data augmentation |
| ----- | --------------------------------------- | -------------- | -------------------- | ----------------- |
| CNN   | sam-stress-convneuralnetwork-keras      | 99.34%         | 45,563               | 7,700 samples     | 
| MLP   | sam-stress-multilayerperceptron-keras   | 94.14%         | 363,011              | 4,224,000 samples |
<br><br>
The libraries used in the project were: Tensorflow, Keras, scikit-learn, Pandas, scipy, Imbalanced-learn, Matplotlib and Seaborn. 

