# Performance-Metric
This Repository contains scratch implementations of the famous metrics used to evaluate machine learning models.
<br>
<h1> abc</h1>
<pre>
<font color='red'><b>A.</b></font> This Repository is done as hard coding exercise. We usually use <strong>sklearn.metrics<a href='https://scikit-learn.org/stable/modules/model_evaluation.html'>sklearn.metrics</a></strong> to evaluate all themodels we use. It is equally important to know the logics behind them and how they perform under different situations.
   <b>Note 1:</b> in this data you can see number of positive points >> number of negatives points
   <b>Note 2:</b> use pandas or numpy to read the data from <b>5_a.csv</b>
   <b>Note 3:</b> you need to derive the class labels from given score</pre> $y^{pred}= \text{[0 if y_score < 0.5 else 1]}$

<pre>
<ol>
<li> Compute Confusion Matrix </li>
<li> Compute F1 Score </li>
<li> Compute AUC Score, you need to compute different thresholds and for each threshold compute tpr,fpr and then use               numpy.trapz(tpr_array, fpr_array) <a href='https://stackoverflow.com/q/53603376/4084039'>https://stackoverflow.com/q/53603376/4084039</a>, <a href='https://stackoverflow.com/a/39678975/4084039'>https://stackoverflow.com/a/39678975/4084039</a> Note: it should be numpy.trapz(tpr_array, fpr_array) not numpy.trapz(fpr_array, tpr_array)</li>
<li> Compute Accuracy Score </li>
</ol>
</pre>
