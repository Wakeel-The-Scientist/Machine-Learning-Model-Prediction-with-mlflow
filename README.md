# Machine Learning Model Prediction with mlflow

## Overview
This script demonstrates loading a machine learning model using **MLflow**, making predictions, and organizing the results in a structured format.

## Steps Implemented
1. **Load Model**: Uses `mlflow.pyfunc.load_model()` to load a trained model.
2. **Make Predictions**: Uses the loaded model to predict outcomes on test data.
3. **Retrieve Feature Names**: Extracts feature names from the **Iris dataset**.
4. **Create a Results DataFrame**: Organizes actual and predicted values for easy analysis.

## Technologies Used
- **MLflow**: Model tracking and deployment.
- **Scikit-learn**: Dataset handling and preprocessing.
- **Pandas**: DataFrame manipulation and visualization.

## Expected Output
A structured DataFrame displaying:
- Feature values from `X_test`
- Actual class labels (`y_test`)
- Predicted class labels (`predictions`)

## Future Enhancements
- Save results to a CSV file for further analysis.
- Improve model interpretability using SHAP or feature importance analysis.
- Extend the script to support multiple datasets and models.

## Conclusion
This script efficiently loads a machine learning model, generates predictions, and structures the results for further evaluation. It serves as a foundational approach for model deployment and performance analysis.

