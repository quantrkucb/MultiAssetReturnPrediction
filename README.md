# MultiAssetReturnPrediction
A project completed at UC Berkeley under supervision of Dr Ali Kakhbod. The goal of this project was to understand feature importance across different asset classes, and to build a multi-factor model that achieves reasonable return predictions. Our team consisted of Ajay Kumar, Rohit Chaturvedi, Gurmeet Bedi, Rishi Kumra and Sudhansh Dua.

The code cannot be shared due to a NDA. However, our results and paper are available.

## Overview
This project focuses on understanding factors that drive multi-asset returns and volatility to construct dynamic and optimal portfolios. Key highlights include:

-**Multi-Asset Factor Model**: Predicts returns for five asset classes: Commodities, Equities, Treasuries, FX, and REITs.
-**Feature Development**: Utilizes features from Macro Fundamentals, Technical Analysis, Pattern Recognition, Cross-Sectional Returns, and Hidden Markov Model-based regime classifiers.
-**Feature Importance Analysis**: Examines how adding or removing factor categories impacts R² of returns and portfolio Sharpe ratios.
-**Ensemble Methods**: Explores variance prediction, improving out-of-sample (OOS) R² for realized volatility, with an average OOS R² of 0.17 from 2017 to 2023.
-**Utility Maximization**: Implements Sharpe and Mean-Variance Optimization (MVO) for portfolio construction.
