<h1>Cargo Network Time Series Forecasting</h1>

<p>This project focuses on analyzing and forecasting cargo network data using time series models. The goal is to predict future trends in the "Total domestic network" cargo data using models like ARIMA and VAR (Vector Autoregression).</p>

<h2>Features</h2>

<ul>
  <li>Exploratory Data Analysis (EDA) on the cargo dataset.</li>
  <li>Time series forecasting using ARIMA and VAR models.</li>
  <li>Visualization of historical data and future forecasts using Matplotlib.</li>
  <li>Handling and preprocessing time series data with Pandas.</li>
</ul>

<h2>Dataset</h2>

<p>The project utilizes a dataset named <code>CARGO.csv</code>, which contains information on the cargo network over time. The dataset includes the following columns:</p>

<ul>
  <li><strong>Year</strong>: The date for each observation.</li>
  <li><strong>Total domestic network</strong>: Cargo data for the domestic network, which is the target of the time series forecast.</li>
  <!-- Add other columns if necessary -->
</ul>

<h2>Requirements</h2>

<p>To run this project, you will need the following Python libraries:</p>

<ul>
  <li><code>pandas</code></li>
  <li><code>statsmodels</code></li>
  <li><code>matplotlib</code></li>
  <li><code>warnings</code> (for suppressing warnings)</li>
</ul>

<p>Install the dependencies using:</p>

<pre><code>pip install -r requirements.txt
</code></pre>

<h2>Model Architecture</h2>

<p>This project utilizes the following models for time series forecasting:</p>

<ul>
  <li><strong>ARIMA (AutoRegressive Integrated Moving Average)</strong>: A popular model for univariate time series forecasting, used to predict the "Total domestic network" cargo data.</li>
  <li><strong>VAR (Vector Autoregression)</strong>: A multivariate time series model that uses multiple variables for forecasting, suitable when multiple series are involved in the analysis.</li>
</ul>

<h2>Results</h2>

<p>The project evaluates the performance of the ARIMA and VAR models and generates visual forecasts for the "Total domestic network" cargo data. Time series plots and forecasts are provided to show the accuracy of the predictions.</p>

<h2>Customization</h2>

<p>You can adjust the following aspects of the project:</p>

<ul>
  <li><strong>Dataset path</strong>: Modify the dataset path in the notebook to point to your data source.</li>
  <li><strong>ARIMA/VAR parameters</strong>: Adjust the p, d, and q values for ARIMA, or tune the VAR model’s lag order based on the data.</li>
  <li><strong>Model selection</strong>: Test other time series models if necessary, such as SARIMA or Prophet.</li>
</ul>

<h2>Acknowledgments</h2>

<ul>
  <li>Thanks to the authors of <strong>Pandas</strong>, <strong>Statsmodels</strong>, and <strong>Matplotlib</strong> for their amazing tools that make time series forecasting easier.</li>
</ul>
