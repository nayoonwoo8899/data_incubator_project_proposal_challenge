# data_incubator_project_proposal_challenge


# Table of Contents
1. [Motivation](README.md#motivation)
2. [Data](README.md#data)
3. [Plots](README.md#plots)

# Motivation

This proposal is oriented toward a practical question concerning our everyday investor: is it better to invest in real estate, or stocks? If cash flow is needed in the immediate horizon, say one year, stocks beat real estate because of liquidity. Beyond such short time periods however, the average return advantage between stocks and real estate however depends on both country and time.

Generally speaking, stock investments may have larger return amplitudes but also higher volatilities, while real estate is considered to be a stable protection against inflation but may also be susceptible to speculation. Therefore macroeconomic factors such as mortgage activity, interest rate, GDP growth, and consumption data may be latent variables that explain some variance in the difference of the two returns and thereby help investors make decisions about asset allocation.

# Data

We download macroeconomic data from the [Jorda-Schularick-Taylor Macrohistory Database](http://macrohistory.net/data), which includes our target variables--asset prices over more than a century--as well as possible explaining variables from credit, economy, to monetary policies. The data are downloaded and also uploaded together with this GitHub repository in the data directory.

# Plots

To illustrate the motivation of the proposal, we have two iPython notebooks in the plots directory, showcasing preliminary exploration of data and the characterstics of the target variables. price_and_growth.ipynb is a notebook that graphs the normalized home and stock price index history for both USA and Japan, demonstrating the dependency of return patterns on both time and location. return_and_volatility.ipynb is a notebook that plots the actual one-year and five-year returns of USA and Japan home and stock price indices, giving a comparison between return amplitudes and volatilities.
