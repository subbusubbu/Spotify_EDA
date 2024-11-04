# Spotify_EDA
Performed Exploratory Data Analysis (EDA) on the Spotify DataSet
In this project, I delved into Spotify’s 2023 dataset to explore what drives song popularity. I analyzed audio features like danceability, energy, and valence to see how they correlate with streaming success and built a predictive model to estimate song popularity based on these features. 🎧 My goal was to uncover actionable insights for music recommendation systems and improve listener engagement.

🔍 Project Overview
The project focused on two key questions:

Which audio attributes are linked to song popularity?
How can track features help predict future streaming counts?
To answer these, I performed data cleaning, exploratory data analysis (EDA), and created visualizations to highlight important attributes. Finally, I developed a predictive model to forecast a song’s streaming counts based on its features.

📈 Key Findings

Danceability, Energy, and Valence: These attributes showed a positive correlation with streaming counts, indicating listeners favor upbeat tracks 🕺💃.
Mode and Key: Songs in major keys were more popular, suggesting a preference for positive, bright tones among listeners.
Streaming Trends: Seasonal peaks in streaming, especially around popular releases, provided insights into optimal release timing.
Predictive Model: The linear regression model demonstrated a clear link between audio features and streaming counts, achieving an RMSE of around 566 million streams. This initial model provides a foundation, with room to explore advanced techniques. 🚀
🔑 Important Insights

Correlation Heatmap: I created a heatmap to visualize the attributes most associated with popularity, providing quick insights into impactful features.
Attribute Segmentation: Segmenting tracks by high danceability and energy scores showed they attract more listeners, useful for playlist curation and marketing. 🎶
Model Performance: Linear regression offered a strong starting point, highlighting areas for further feature engineering and model refinement.
🛠️ Modules and Tools

Data Processing: Used Pandas and NumPy for data manipulation and efficient computation.
Visualization: Created visualizations with Matplotlib and Seaborn, including scatter plots, heatmaps, and pair plots.
Machine Learning: Implemented Linear Regression with k-fold cross-validation using Scikit-Learn.
💡 Project Impact
This project refined my skills in EDA, data visualization, and predictive modeling, generating insights that could support recommendation systems, playlist curation, and music release strategies. With further exploration, this analysis demonstrates the power of data-driven decision-making in the music industry. 🎶✨
