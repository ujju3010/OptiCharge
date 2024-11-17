**EV Charging Station Optimization using Traffic Data and Intel AI Stack**

**Overview**

This project aims to optimize the placement of Electric Vehicle (EV) charging stations across New York City (NYC) by analyzing traffic patterns, identifying high-demand areas, and predicting suitable locations for new EV charging stations. Our approach integrates real-world traffic data, subway station data, and EV charging station data to provide a comprehensive solution for EV station placement using advanced machine learning techniques and the Intel AI Stack.

**Datasets Used**

1. **NYC Traffic Data (trend\_analysis dataset)**: Contains traffic volume counts recorded at different streets across NYC.
1. **Subway Station Data**: Provides geographical locations of subway stations across NYC.
1. **NYC EV Charging Stations**: Lists existing EV charging stations and their locations within the city.

**Technologies and Tools Used**

- **Python**: The main programming language used for data processing, analysis, and modeling.
- **K-means Clustering**: A machine learning algorithm used to categorize streets based on Average Annual Daily Traffic (AADT) values and predict optimal EV station locations.
- **Folium**: For visualizing NYC streets, existing EV stations, and potential new locations on an interactive map.
- **Geospatial Analysis**: Used to determine proximity between new station locations and subway stations within a 1km range.

**AI Intel Stack**

This project utilizes the Intel AI Stack to accelerate computations and improve model performance:

- **Intel oneDAL Library**: Used for efficient data analysis, preprocessing, and machine learning model implementation.
- **Intel Gaudi AI Accelerator**: Helps speed up training times for machine learning models.
- **Intel Tiber Cloud**: The platform used to host and deploy the model, providing scalability and optimized performance for handling large datasets and computations.

**How It Works**

1. **Traffic Analysis**: We processed the traffic data to calculate the Average Annual Daily Traffic (AADT) for each street in NYC, using traffic volume counts and geographic information.
1. **K-means Clustering**: By applying k-means clustering, we divided the streets into three categories: high, medium, and low traffic streets. We then identified streets with similar AADT values where EV stations can be installed.
1. **EV Station Prediction**: Based on clustering results and proximity to subway stations, new EV station locations are proposed.
1. **Visualization**: The project includes an interactive map displaying existing EV stations, new potential EV station locations, and subway stations, with a proximity analysis to find new locations near subways.

**Conclusion**

This project demonstrates the power of data-driven decision-making for EV infrastructure planning using real-world datasets and advanced AI technologies. By leveraging Intel’s AI stack, we were able to process vast amounts of data efficiently and propose solutions to optimize the placement of EV charging stations, enhancing accessibility and utility for electric vehicle users.


