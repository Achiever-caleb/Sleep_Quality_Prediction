# Sleep_Quality_Prediction
This README provides detailed information on the predictive model developed for analyzing sleep and cognitive performance metrics based on physiological and behavioral variables.

## Performance Metrics
The model's evaluation was based on three key performance metrics:

- **Mean Absolute Error (MAE)**: 18.748
- **R-squared (R²)**: 0.138
- **Root Mean Squared Error (RMSE)**: 4.330

### Interpretation of Results
1. **MAE (Mean Absolute Error)**: Indicates that, on average, the model's predictions deviate by 18.748 units from the actual values.
2. **R-squared (R²)**: A positive R-squared value suggests that the model explains approximately 13.8% of the variance in the data.
3. **RMSE (Root Mean Squared Error)**: Demonstrates the magnitude of the error, which is approximately 4.330 units.

These performance metrics indicate moderate improvement, but further optimization and feature engineering may be required to enhance the model's predictive capabilities.

## Features Used
The model was trained on the following features:

1. **Sleep_Hours**: The number of hours the subject sleeps per night.
2. **Sleep_Quality_Score**: A subjective or objective score representing the quality of sleep.
3. **Daytime_Sleepiness**: Level of sleepiness experienced during the daytime.
4. **Stroop_Task_Reaction_Time**: Reaction time during a Stroop task, indicating cognitive processing speed.
5. **N_Back_Accuracy**: Accuracy during an N-back task, measuring working memory.
6. **Emotion_Regulation_Score**: Score reflecting the individual's ability to manage emotional responses.
7. **PVT_Reaction_Time**: Reaction time during a psychomotor vigilance task.
8. **Age**: The age of the subject.
9. **Gender**: The subject's gender.
10. **BMI (Body Mass Index)**: A measure derived from the subject's weight and height.
11. **Caffeine_Intake**: The amount of caffeine consumed by the subject.
12. **Physical_Activity_Level**: The subject's level of physical activity.
13. **Stress_Level**: The perceived stress level of the subject.

## Conclusion
The current model shows room for improvement. With careful tuning, feature engineering, and algorithm exploration, it can become a valuable tool for understanding the relationship between sleep patterns, cognitive performance, and physiological factors.

