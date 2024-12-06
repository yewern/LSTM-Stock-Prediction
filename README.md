<h1 align="center">📘 Stock Prediction Using Multivariate LSTM</h1>

<h3>📖 Project Overview</h3>
<p>
    This project explores predicting stock prices using a <strong>Multivariate LSTM Model</strong>. 
    The model integrates <em>technical</em>, <em>fundamental</em>, and <em>macroeconomic indicators</em> 
    to forecast the next-day closing price of Microsoft Corporation's stock. 
    The research incorporates feature selection, hyperparameter tuning, and robust evaluation to optimize model performance. 
    It also represents my very first hands-on experience with <strong>deep learning</strong> using Python.
</p>

<h3>🔑 Key Highlights</h3>
<ul>
    <li><strong>Indicators Used:</strong>
        <ul>
            <li><em>Fundamental:</em> P/E Ratio, PEG Ratio.</li>
            <li><em>Technical:</em> Moving Average, Relative Strength Index (RSI), Price Rate of Change (ROC), and others.</li>
            <li><em>Macroeconomic:</em> Gold price, Oil price, U.S. Treasury Yield, and U.S. Dollar Index.</li>
        </ul>
    </li>
    <li><strong>Hyperparameter Tuned:</strong>
        <ul>
            <li>Activation Functions</li>
            <li>Number of LSTM Units in a Layer</li>
            <li>Optimizer’s Learning Rate</li>
            <li>Batch Size</li>
            <li>Timestep</li>
        </ul>
    </li>
    <li><strong>Methodology:</strong> Applied the CRISP-DM framework for data mining, combining stepwise regression at significance level of 95% for feature selection and extensive hyperparameter tuning to enhance LSTM performance.</li>
    <li><strong>Results:</strong> Achieved an RMSE of <code>0.0081</code> with the optimal configuration of predictors and hyperparameters.</li>
</ul>

<h3>📂 Resources</h3>
<ul>
    <li><a href="https://www.kaggle.com/datasets/yewernwong/msfts-historical-stock-price-and-indicators" target="_blank">Dataset on Kaggle</a></li>
</ul>

