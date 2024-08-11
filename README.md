# Toronto-Police-Patrol-Heatmap
Utilizing AI to implement Starbucks Amazon ordering into their drive thrus
- Link to Final Mockup: https://drive.google.com/file/d/1VGFa2iyfqBCbBQI7n2QKwBWM6WOyQyb3/view?usp=sharing

This project is focused on developing a data-driven solution to enhance the Toronto Police Services' (TPS) response times to shooting incidents. The project involves analyzing historical data, building predictive models, and creating visual tools to optimize police patrols and reduce response times.

## Overview

The Toronto Police Services (TPS) management has identified a troubling trend of over 300 shooting incidents per year for the past six years. This project aims to provide TPS management with actionable insights through a comprehensive strategy, utilizing AI predictive modeling and heatmaps to identify high-risk areas and optimize patrol schedules.

## Project Structure

- **Background**: Analysis of the current challenges facing the TPS, particularly regarding the inability to meet the response time targets set in 1995.
- **Problem Statement**: Addressing the persistent issue of high shooting incidents and the need for a data-driven approach to enhance response times.
- **Proposed Solution**: 
  - Develop a predictive model to identify high-risk areas.
  - Create new divisional response time guidelines.
  - Integrate with existing TPS tools and provide training.
- **External Environment**: Consideration of regulatory constraints, privacy concerns, and the need for ethical AI implementation.
- **Descriptive Statistics**: Analysis of patterns in the data, such as times of day and locations with the highest incident rates.
- **Model Selection**: Justification for using Gradient Boosting Regression due to its efficiency in handling outliers and complex datasets.
- **Model Implementation**: Details on how the model was built, trained, and evaluated.
- **Limitations**: Discussion of challenges such as late reporting, dynamic police car movements, and budget constraints.
- **Recommendations & Conclusion**: Key suggestions for implementing the AI heatmap, updating response time guidelines, and integrating with TPS systems.

## Data and Tools Used

- **Data**: Historical data on shooting incidents in Toronto, including location, time, and incident severity.
- **Tools**: 
  - Python for data analysis and model development.
  - Google Distance Matrix API for calculating driving distances.
  - Folium for creating interactive heatmaps.
  - Gradient Boosting Regression for predictive modeling.

## Installation

To replicate or extend this project, ensure you have the following dependencies installed:

```bash
pip install pandas scikit-learn folium
```

You will also need access to the Google Distance Matrix API for calculating driving distances.

## Usage

1. **Prepare the Data**: Clean and preprocess the shooting incident data.
2. **Build the Model**: Train the Gradient Boosting Regression model using the preprocessed data.
3. **Generate Heatmaps**: Use the trained model to predict high-risk areas and visualize them on a heatmap.
4. **Calculate Response Times**: Utilize the Google Distance Matrix API to estimate response times based on the predicted high-risk areas.
5. **Implement and Test**: Integrate the solution with TPS systems and test its effectiveness in real-world scenarios.

## Limitations

- The model assumes a constant speed of 70 km/h, which may not reflect real-world conditions such as traffic, weather, or time of day.
- The solution currently assumes police cars are static, which may impact the accuracy of the patrol schedule recommendations.

## Future Work

- Expanding the model to include other types of crimes.
- Enhancing the patrol schedule recommendations by incorporating dynamic factors like traffic and weather conditions.
- Improving the model's accuracy by using real-time data.

## Contributors

- Annuj Kamalesan
- Parth Malviya
- Pratiksha
- Rupali Wadhawan
- Sadia Ashraf Charoo
- Sreekanth Potlabathini

## References

Please refer to the citations and references included in the original presentation for a detailed list of sources and additional reading.

---

This README provides an overview of the Toronto Police Patrol Program project, including its goals, methodology, and findings. For a more detailed explanation of the work done, please refer to the project documentation and code.
