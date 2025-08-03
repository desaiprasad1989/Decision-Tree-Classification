#### Decision-Tree-Classification (Binary Classification Model)

**Dataset:** Heart Disease
 > **Author:** Prasad Desai

### Objective: 
The Heart Disease dataset is a multiclass classification problem, The dataset is target feature is classified into 5 classes, but the classes 1,2,3 and 4 are not classified into any stages of the disease, so we will check and work on the dataset if the it works with the binary classification, we will merge the classes into one class, the features based on the 12 inputs. The objective of this assignment is to apply Decision Tree Classification to a given dataset, analyse the performance of the model, and interpret the results. Using Evaluation Matrics, Accuracy Score, precision score, F1 score, ROC AUC score, confusion matrics and classification report.

### Dataset Description:

<table>
  <tr>
    <th>Features</th>
    <th>Feature Description</th>
  </tr>
  <tr>
    <td>age</td>
    <td>Age in years</td>
  </tr>
  <tr>
    <td>sex</td>
    <td>Gender : Male - 1, Female -0 </td>
  </tr>
  <tr>
    <td>cp</td>
    <td>Chest pain type</td>
  </tr>
  <tr>
    <td>trestbps</td>
  	<td>Resting blood pressure</td>
  </tr>
  <tr>
    <td>chol</td>
  	<td>cholesterol measure</td>
  </tr>
  <tr>
    <td>fbs</td>
  	<td>(fasting blood sugar > 120 mg/dl) (1 = true; 0 = false)</td>
  </tr>
  <tr>
    <td>restecg</td>
  	<td>ecg observation at resting condition,   -- Value 0: normal
        -- Value 1: having ST-T wave abnormality (T wave inversions and/or ST elevation or depression of > 0.05 mV)
        -- Value 2: showing probable or definite left ventricular hypertrophy by Estes' criteria</td>
  </tr>
  <tr>
    <td>thalch</td>
  	<td>maximum heart rate achieved</td>
  </tr>
  <tr>
    <td>exang</td>
  	<td>exercise induced angina</td>
  </tr>
  <tr>
    <td>oldpeak</td>
  	<td>ST depression induced by exercise relative to rest</td>
  </tr>
  <tr>
    <td>slope</td>
  	<td>the slope of the peak exercise ST segment</td>
  </tr>
  <tr>
    <td>thal</td>
  	<td>Thal</td>
  </tr>
  <tr>
    <td>num</td>
  	<td>target [0=no heart disease: classify the data distribution based on the data as bwlow
1,2,3,4 = stages of heart disease ]</td>
  </tr>
</table>
