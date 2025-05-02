# C5 - Generalization Theory & the Bias-Variance Trade-off: RMSE Evaluation
Essential concept of Generalization Theory and the Bias-Variance Trade-off using RMSE (Root Mean Squared Error) to evaluate model performance. Visuals and hands-on tasks demonstration on how to balance model complexity and make smart decisions based on training, validation, and test set results.

This project is all about understanding one of the most important ideas in machine learning: how to make sure your model not only performs well on data it has seen before but also on new, unseen data.
## We explore:
	•	Generalization Theory: How models make predictions beyond their training data.
	•	The Bias-Variance Trade-off: Finding the sweet spot between too simple and too complex models.
	•	RMSE Evaluation: Using the Root Mean Squared Error to measure and compare how good different models are.

⸻

## What’s Inside
	•	Train, Validate, Test:
We split data into training, validation, and test sets to check how well our models generalize.
	•	RMSE Calculation:
RMSE tells us how far off our model’s predictions are from the real answers.
	•	Low RMSE = better performance.
	•	High RMSE = poor predictions.
	•	Model Selection:
We pick the best model by looking for the one with the lowest validation RMSE.
	•	Visualizations:
visual plots to compare RMSEs across different models and spot overfitting or underfitting.

⸻

## Example Result

We found that one of the models had a test set RMSE of ~9.5, meaning its predictions were about 9.5 units off, on average, when applied to new data.

⸻

## Why This Matters

We learn:
	•	Why you can’t trust a model that’s only good on training data.
	•	How to balance complexity vs. simplicity using the bias-variance trade-off.
	•	How to measure model performance the right way using RMSE.

Machine learning isn’t just about fitting data, it’s about making reliable predictions. 

⸻

## Tech Stack
	•	Python 
	•	Scikit-learn
	•	Matplotlib & Seaborn for visualization
	•	Polynomial Regression & RMSE metrics
