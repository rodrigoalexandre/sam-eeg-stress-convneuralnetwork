<div align="center">

# sam-stress-convneuralnetwork-keras

<div align="justify">
Project developed for the study presented in the article "A Convolutional Neural Network model to detect stress levels in electroencefalogram signals".
<br><br>
This study proposes a Convolutional Neural Network (CNN) model for classifying stress levels using electroencephalogram data. The model was trained on data from the SAM 40 Dataset. This dataset has records of brain activity of 40 individuals who were monitored while performing certain stress-inducing activities. The CNN model achieved an accuracy rate of 98.95% in predictions.
<br><br>
The CNN model performed better (accuracy vs. computational costs) than the Multilayer Perceptron (MLP) model proposed in the sam-stress-multilayerperceptron-keras project, as can be seen in the following comparative table:
<br><br>
 <table>
  <tr>
    <th>Model</th>
    <th>Project</th>
    <th>Teste Accuracy</th>
    <th>Trainable Parameters</th>
    <th>Data augmentation</th>
  </tr>
  <tr>
    <td>CNN</td>
    <td>sam-stress-convneuralnetwork-keras</td>
    <td>98.95%</td>
    <td>45,563</td>
    <td>7,700 samples</td>
  </tr>
  <tr>
    <td>MLP</td>
    <td>sam-stress-multilayerperceptron-keras</td>
    <td>94.14% </td>
    <td>363,011</td>
    <td>4,224,000 samples</td>
  </tr>
</table>

The libraries used in the project were: Tensorflow, Keras, scikit-learn, Pandas, scipy, Imbalanced-learn, Matplotlib and Seaborn. 
