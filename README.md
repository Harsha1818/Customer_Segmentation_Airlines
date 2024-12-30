# Customer_Segmentation_Airlines


Project Description:

This project presents an analysis and prediction of road crash outcomes using various machine learning techniques. The data set from the ArcGIS API contains comprehensive information about crash severity, road conditions, and environmental factors. Machine learning models, such as Random Forest and Gradient Boosting, were used to uncover important factors, while clustering algorithms, including DBSCAN and Fuzzy C-Means, identify patterns and high-risk zones that can provide practical insights into improving road safety.

Software requirement:Python 3.7 or later
Operating System: Windows 10, macOS, or Linux
Libraries required:
pip install pandas numpy geopandas matplotlib seaborn folium requests scikit-learn scikit-fuzzy

Running the project:

1. Open the project using Jupyter Notebook, Visual studio code, Google collar or any other tool to open the .ipynb file.

2.You can start running from the first cell and execute each of it in the sequential order.The notebook contains sections for data retrieval , data preprocessing, data visulaizations, model training and clustering analysis.

3.The dataset is retrieved from the ArcGIS API using a Python function. Running this cell might  take a few minutes due to the large dataset size and API pagination. Wait till this cell is executed successfully.

4.For preprocessing and visualizations run the cells accordingly.There is code for geographic data exploration where you can visualize from the maps and the rendering of these maps might take few minutes depending on your system's processing power.You can use zoom controls or your mouse to navigate the maps.Also you can click on markers or clusters to view crash details.


5.Run the cells for trading the machine learning models and clustering analysis.The models are evaluated using the metrics and  useful insights are obtained from clustering.

6.DBSCAN clustering and Fuzzy C means clustering might take few minutes to execute as there are over 8000000 records and adjusting the parameter values to optimize clustering performance.








