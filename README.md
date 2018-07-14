<h1> Personalized Medicine Redefining Cancer Treatment </h1>
<p>Personalized Medicine Redefining Cancer Treatment is a real world data set from Kaggle. Memorial Sloan Kettering Cancer Center (MSKCC) launched this competition, accepted by the NIPS 2017 Competition Track,  because we need your help to take personalized medicine to its full potential.</p>

<h3>Features</h3>
<ul>
<li>Id: The id of the row used to link the mutation to the clinical evidence (Numerical)</li>
<li>Gene:  The gene where this genetic mutation is located (Categorical)</li>
<li>Variants: The aminoacid change for this mutations (Categorical)</li>
<li>Text: Text collected from the clinical evidences (Text)</li>
<li>Class: 1-9 the class this genetic mutation has been classified on (Numeric)</li>
</ul>

<h3>Dataset</h3>
<ul>
<li>Total points : 3321 </li>
<li>Train points : 2490 (75%) </li>
<li>Test points : 831 (25%)</li>
</ul>

<h3>Featurization</h3>
<ul>
<li>Gene : One hot encoding (247-Dimensions) </li>
<li>Variants : One hot encoding (2266-Dimensions) </li>
<li>Text : One hot encoding only for top 2500 tf-idf words (2500-Dimensions) </li>
</ul>

<h3> Machine Learning Model </h3>

<ul> Logistic Regression
<li> Log loss: 0.94 </li>
<li> misclassification error : 31% </li></ul>
