# ETL Pipeline for Spotify Playlist Analysis

## Overview
This project implements an ETL (Extract, Transform, Load) pipeline using Databricks, Delta Lake, and Spark SQL to analyze a Spotify playlist dataset. The pipeline extracts data from Hive Metastore, transforms it to derive meaningful insights, and loads it into Delta Lake for further analysis and visualization.

## Features
- **Data Extraction**: Utilize Databricks to extract data from the Hive Metastore.
  
- **Data Transformation**: Leverage Spark SQL to perform transformations on the data.
  
- **Data Loading**: Use Delta Lake for efficient and reliable data storage.
  
- **Data Visualization**: Generate complex figures to visualize the distribution of musical features.
  
- **Error Handling and Validation**: Implement robust error handling and data validation to ensure the integrity of the pipeline.
  
- **Automated Trigger**: Set up an automated process to trigger the pipeline execution.

## Dependencies
- Databricks Runtime
- Spark SQL
- Delta Lake
- Python Libraries: `matplotlib`, `seaborn`

## Running the Program
1. Clone the repository to your local machine.
2. Import the `individual3.dbc` file into your Databricks workspace.
3. Attach the notebook to a Databricks cluster with the necessary configurations and libraries installed.
4. Run the notebook cells sequentially to execute the ETL pipeline.

## Data-Driven Recommendations
Based on the transformed data, we recommend the following actions to the hypothetical management team:
1. Focus on tracks with high energy for playlists aimed at physical activities.
2. Curate playlists by danceability score to target different audience moods and preferences.
3. Consider loudness levels to maintain a consistent auditory experience across songs.

## Visualization
The project includes complex figures showing the distributions of `danceability`, `energy`, and `loudness` among tracks. These visualizations aid in understanding the characteristics of the playlist tracks.

## Automated Trigger
The ETL pipeline is designed to be triggered automatically. The trigger setup details are documented within the notebook, ensuring that the pipeline runs on schedule or in response to specific events.

## Video Demo
A video demonstration of the ETL pipeline can be found here: 

## Conclusion
This project showcases the use of modern data engineering tools and practices to process and analyze large datasets effectively. The use of Delta Lake and Spark SQL demonstrates a reliable and scalable approach to data transformation and storage.

For any queries or further assistance with the pipeline, please open an issue in this repository.

