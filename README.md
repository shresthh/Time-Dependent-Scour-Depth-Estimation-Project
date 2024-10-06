# Time-Dependent-Scour-Depth-Estimation-Project
This repository contains code and information related to the project on "Estimation of Time-Dependent Scour Depth around Circular Bridge Piers: Application of Individual Machine Learning Models and Comparison"
## Overview
In this project, we address the critical issue of estimating time-dependent scour depth around bridge piers, a significant concern for the stability and safety of hydraulic structures. The objective is to predict how scour depth evolves over time, considering variations in flow scenarios.
We have employed two prominent machine learning algorithms, XGBoost and Random Forest, to create predictive models for time-dependent scour depth. These models take into account various parameters such as river bed properties, flow characteristics, bridge pier geometry, and time. Our focus is on evaluating and comparing the performance of these individual models using a range of evaluation metrics and visualization techniques.

## Full form of Abbreviations:
1. **dstf (Downstream Flow Depth)**: The depth of water flow measured downstream from a specific point, often used to assess the impact of flow on sediment transport.
2. **dste (Downstream Scour Depth)**: The depth of the scour hole formed downstream, indicating the extent of sediment removal due to water flow.
3. **e/b (Erosion to Bed Width Ratio)**: A ratio comparing the extent of erosion to the width of the riverbed, used to evaluate the impact of flow on the bed.
4. **h/b (Flow Depth to Bed Width Ratio)**: A ratio of the flow depth to the width of the riverbed, providing insight into flow characteristics relative to the channel size.
5. **vt/b (Velocity to Bed Width Ratio)**: A ratio of the flow velocity to the width of the riverbed, used to assess the potential for sediment transport.
6. **Fe (Froude Number - Erosion)**: A dimensionless number that describes the flow regime, indicating whether the flow is subcritical, critical, or supercritical, which affects erosion potential.
7. **v/vc (Velocity to Critical Velocity Ratio)**: A ratio comparing the actual flow velocity to the critical velocity needed to initiate sediment movement, used to predict sediment transport.

## Files and Folders
Random Forest VS Xgboost Analysis.ipynb: This file contains the code for training and evaluating the Random Forest model & XGBoost model for scour depth prediction.

README.md: You are reading it right now!

## Results
We provide comprehensive evaluation metrics and visualizations to compare the performance of the XGBoost and Random Forest models:

Root Mean Squared Error (RMSE)
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R-squared (𝑟^2)
Training and validation loss curves are also plotted for both models.

## Conclusion
This project showcases the application of individual machine learning models, specifically XGBoost and Random Forest, for predicting time-dependent scour depth around circular bridge piers. The evaluation metrics and visualizations help in comparing the performance of these models and provide valuable insights for hydraulic engineering applications.

Feel free to explore the code and adapt it for your own projects or research. If you have any questions or suggestions, please don't hesitate to get in touch.
