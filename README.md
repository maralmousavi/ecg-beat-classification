# ECG beat classification
 Diagnosis of Diseases by ECG Using <b>Classical Machine Learning Algorithm</b> and <b>Deep Neural Network</b>

### Classical Machine Learning Algorithm
- Logistic Regression = accuracy: 91%
- Random Forest Classifiery = accuracy: 97%
- Histogram-based Boosting Classifier = accuracy: 93%
- XGBoost Classifier = accuracy: 92%

### Deep Neural Network
-  DNN = accuracy: 94%

### Dataset
The [MIT-BIH Arrhythmia Database](https://physionet.org/content/mitdb/1.0.0/) contains 48 half-hour excerpts of two-channel ambulatory ECG recordings, obtained from 47 subjects studied by the BIH Arrhythmia Laboratory between 1975 and 1979.
<br>
<br>
Number of Samples: 109446
<br>
Number of Categories: 5
<br>
Sampling Frequency: 125Hz
<br>
Data Source: Physionet's MIT-BIH Arrhythmia Dataset
<br>
Classes: ['N': 0, 'S': 1, 'V': 2, 'F': 3, 'Q': 4]
- N : Non-ecotic beats (normal beat)
- S : Supraventricular ectopic beats
- V : Ventricular ectopic beats
- F : Fusion Beats
- Q : Unknown Beats

![Graph](https://github.com/maralmousavi/ECG-beat-classification/blob/master/images/all-category.png)

### Acuracy Classical Algorithm
![Graph](https://github.com/maralmousavi/ECG-beat-classification/blob/master/images/accuracy-classical-algorithm.png)

### Acuracy Deep Neural Network
![Graph](https://github.com/maralmousavi/ECG-beat-classification/blob/master/images/accuracy-dnn-algorithm.png)

#### Model Accuracy-Loss Plot
![Graph](https://github.com/maralmousavi/ECG-beat-classification/blob/master/images/model-accuracy-loss.png)

#### Graph of the Deep Neural Network
![Graph](https://github.com/maralmousavi/ECG-beat-classification/blob/master/images/graph-deep-neural-network.png)

## Note:
 - extract dataset.zip file for testing source code
 
## Collaborators
- [Taher Fattahi](https://www.github.com/taherfattahi)

## License
[MIT](https://choosealicense.com/licenses/mit/)
