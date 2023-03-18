<!DOCTYPE html>
<html>
<head>
	<title>Car Purchase Prediction using Regression</title>
</head>
<body>
	<h1>Car Purchase Prediction using Regression</h1>
  <p>This project aims to predict the price of a car based on its features such as make, model, year, mileage, and other relevant factors using regression analysis.</p>

<h2>Dataset</h2>

<p>The dataset used in this project contains information about car sales from a dealership. It includes the following columns:</p>

<ul>
	<li><code>Make</code>: Make of the car (categorical)</li>
	<li><code>Model</code>: Model of the car (categorical)</li>
	<li><code>Year</code>: Year of the car (numerical)</li>
	<li><code>Mileage</code>: Mileage of the car (numerical)</li>
	<li><code>Color</code>: Color of the car (categorical)</li>
	<li><code>Price</code>: Sale price of the car (numerical)</li>
</ul>

<h2>Requirements</h2>

<ul>
	<li>Python 3.6 or higher</li>
	<li>scikit-learn</li>
	<li>pandas</li>
	<li>matplotlib</li>
</ul>

<h2>Getting Started</h2>

<ol>
	<li>Clone this repository:</li>

	<pre>
		git clone https://github.com/&lt;username&gt;/car-purchase-prediction.git
	</pre>

	<li>Install the required packages:</li>

	<pre>
		pip install scikit-learn pandas matplotlib
	</pre>

	<li>Run the script to train and test the regression model:</li>

	<pre>
		python car_purchase_prediction.py
	</pre>

	<p>The script will output the accuracy of the trained model and a scatter plot showing the actual prices vs. predicted prices.</p>
</ol>

<h2>Customization</h2>

<p>You can customize the model by modifying the parameters in the <code>car_purchase_prediction.py</code> script. The following parameters can be adjusted:</p>

<ul>
	<li><code>TEST_SIZE</code>: Proportion of data used for testing (default: 0.2)</li>
	<li><code>RANDOM_STATE</code>: Random seed used for train-test split (default: 42)</li>
	<li><code>N_JOBS</code>: Number of CPU cores used for training (default: -1)</li>
</ul>

<p>You can also use different regression algorithms or tune hyperparameters to improve the accuracy of the model.</p>

<h2>License</h2>

<p>This project is licensed under the MIT License - see the <code>LICENSE</code> file for details.</p>
</body>
</html>
