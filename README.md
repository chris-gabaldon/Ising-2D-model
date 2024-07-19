<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ising Model Monte Carlo Simulations</title>
</head>
<body>
    <h1>Ising Model Monte Carlo Simulations</h1>

    <h2>Overview</h2>
    <p>This repository contains a Jupyter Notebook that performs Monte Carlo simulations of the 2D Ising model. The notebook explores the correlation function and susceptibility of the system to estimate the critical temperature.</p>

    <h2>Notebook Description</h2>
    <p>The notebook is organized into several sections:</p>
    <ul>
        <li><strong>Correlation Function Calculation</strong>: Defines and uses functions to compute the correlation function <i>g(r)</i> for different temperatures. The results are fitted with an exponential decay to determine the correlation length <i>&xi;</i>.</li>
        <li><strong>Susceptibility and Critical Temperature</strong>: Calculates the susceptibility <i>&chi;</i> for different temperatures and estimates the critical temperature <i>T<sub>c</sub></i> by fitting the susceptibility peaks with a quadratic function.</li>
        <li><strong>Results and Analysis</strong>: Plots and analyzes the results to determine the critical temperature and the behavior of the correlation length. It compares the estimated critical temperature with theoretical values.</li>
    </ul>

    <h2>How to Use</h2>
    <ol>
        <li>Open the Jupyter Notebook file <code>ising_model_simulation.ipynb</code> in a Jupyter environment.</li>
        <li>Run the cells sequentially to execute the Monte Carlo simulations and analyze the results.</li>
        <li>Review the generated plots and results for insights into the Ising model's critical behavior.</li>
    </ol>

    <h2>Results Summary</h2>
    <ul>
        <li>The critical temperature obtained is <i>T<sub>c</sub> = 2.268 &plusmn; 0.002</i>, which is close to the theoretical value <i>T<sub>c</sub> = 2.27</i>.</li>
        <li>The notebook also shows how the correlation length <i>&xi;</i> behaves as a function of temperature and compares this with the critical temperature.</li>
    </ul>
</body>
</html>

