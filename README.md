Welcome to my University Projects Collection! 
This repository houses a compilation of diverse projects that I've worked on during my master in Data Science.

Here's a quick overview of what you can find in this repository:

**Human Action Recognition**: In this project for the Deep Learning for AI class, I implemented ResNet18 and VGG16 convolutional neural networks to classify human actions. I fine-tuned the models using PyTorch and evaluated their performance monitoring accuracy and loss function. The major challenge was preventing overfitting during fine-tuning. To address this, I employed various regularization techniques, such as dropout and data augmentation.

**Time series modeling and forecasting of gold price**: Gold, a well-known safe-haven investment and economic indicator, is under scrutiny. I have analyzed historical data to identify trends, seasonal variations, and potential outliers impacting the gold market. Additionally, I have determined the most suitable SARIMA model for the data and use it to forecast future average monthly gold prices.

**ANN for Image classification**: This project served as the culmination of a Statistical Learning course undertaken during my exchange period in Sweden. My teammate and I opted to address a multi-class classification challenge by implementing various neural networks. Specifically, we developed an Artificial Neural Network (ANN) featuring dropout layers and a Convolutional Neural Network (CNN). Our investigation focused on analyzing the patterns of loss and accuracy curves.

**Metropolis-Hastings and Hamiltonian Monte Carlo**: In our collaborative project, my colleagues and I delved into the computational aspects of two Markov Chain Monte Carlo (MCMC) algorithms: the Metropolis-Hastings algorithm (MH) and the Hamiltonian Monte Carlo (HMC). Our objective was to analyze the computational aspects of these algorithms and highlight their differences. Subsequently, we implemented both algorithms on a common distribution to observe and compare their respective behaviors. For the HMC implementation, we utilized the STAN package.

**Bayesian Ordinal Probit Regression**: For the final project in the "Bayesian Modelling" course, my colleague and I opted to construct a probit regression model for an ordinal response variable featuring six levels. Our approach involved implementing an algorithm comprising a Metropolis-Hastings step to update the cut-offs of the latent variable Z. Subsequently, we incorporated Gibbs steps to draw samples for the latent variable Z from its full conditional distribution, as well as additional Gibbs steps for sampling values of the regression coefficients. By doing so we were able to approximate the posterior distribution of the coefficients.

**Applied Linear Models**: This project provides a comprehensive overview of the topics covered in the Applied Linear Model course. Initially, I constructed a linear model incorporating all available predictors, including all possible interactions among them. Subsequently, utilizing various evaluation criteria, I identified the model with the optimal number of predictors. Furthermore, I conducted an analysis of collinearity issues and performed diagnostic assessments, leading me to apply a logarithmic transformation to the response variable. Subsequently, I conducted an ANOVA test to compare the selected predictors with a smaller subset. I provided interpretations for the estimated coefficients, assessed the goodness of fit of the model, and utilized the final model to predict values for new data points.



