<h1 align="center"> Business Problem </h1>

<figure>
  <p align="center">
    <img src="https://user-images.githubusercontent.com/120829907/225810957-0cf51731-45ae-41f9-afd4-43bf49331ee1.jpg" alt="rim" width="300" height="300">
  </p>
  <figcaption style="text-align: center;">Imagem de <a href="https://pixabay.com/pt/users/suzakara-10256827/?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=6009357">suzakara</a> por <a href="https://pixabay.com/pt//?utm_source=link-attribution&amp;utm_medium=referral&amp;utm_campaign=image&amp;utm_content=6009357">Pixabay</a></figcaption>
</figure>

<h2> 1.  Summary </h2>
<p> As patients with liver disease have been continous increasing, it is important to monitor data from blood tests to predict the disease. </p> 

<h2> 2.  Description </h2>
<p>This experiment aims to create a model to predict if a patient will have liver disease. It will showed all the process, since the cleaning until the use of algorithms</p>

<h2>3.  Data </h2>
<p>Dataset:
    <a href="https://archive.ics.uci.edu/ml/datasets/ILPD+(Indian+Liver+Patient+Dataset)">Indian Liver Patient Dataset </a>
</p>
<p> This data set contains 416 liver patient records and 167 non liver patient records.</p>
<p> The data set was collected from north east of Andhra Pradesh, India. Selector is a class label used to divide into groups(liver patient or not). </p>
<p> This data set contains 10 variables that are age, gender, total Bilirubin, direct Bilirubin, total proteins, albumin, A/G ratio, SGPT, SGOT and Alkphos. <p> 

<h2>4.  Features </h2>

<p> This data set contains 10 variables that are:<p>
<p>- Age<p>
<p>- Gender<p>
<p>- Total Bilirubin<p>
<p>- Direct Bilirubin<p>
<p>- Total proteins<p>
<p>- Albumin<p>
<p>-Albumin and Globulin Ratio<p>
<p>- Alamine Aminotransferase<p>
<p>- Alkaline Phosphotase<p>
<p>- Alamine Aminotransferase<p>

<h2>5. Type of Problem </h2>
<p> It is a binary classification problem, where given the above set of features and we need to predict if a given patient has a disease or not.<p>

<h2>6. Evaluation Metric(KPI) </h2>
<p> As we have a classification problem, we use the following metrics:<p>
<p> - Confusion Matrix = For getting a better clarity of the no of correct/incorrect predictions by the model <p>
<p> -  AUC ROC score= It is a metric that measures the ability of the model to distinguish between positive and negative classes, considering different thresholds for the probability of belonging to the positive class  <p>
<p> -  AUC = It is a metric similar to ROC AUC but with a focus on precision and recall. It is also suitable for imbalanced binary classification problems. <p>
<p> -  Acurracy =  It is a simple and widely used metric that measures the proportion of examples classified correctly out of the total number of examples  <p>

<h2>7. Results </h2>

 <table>
  <tr>
    <th> Algorithm</th>
    <th> ROC_AUC Score</th>
    <th> AUC Score</th>
    <th> Accuracy</th>
  </tr>
  <tr>
    <td>Logistic Regression</td>
    <td>0.705244</td>
    <td>0.738780</td>
    <td>67.38</td>
  </tr>
  <tr>
    <td>Decision Tree </td>
    <td>0.547317</td>
    <td>0.632805 </td>
    <td>60.28</td>
  </tr>
  <tr>
    <td>KNN</td>
    <td>0.532927</td>
    <td>0.532927</td>
    <td>60.28</td>
  <tr>
</table>

<h2>8. Conclusion </h2>
<p> According with the results the best algorithm to predict liver disease was Logistic Regression since the results were the greatest <p>