# Prodigy_DS_Task4

This project aims to analyze and visualize sentiment patterns in social media data to understand public opinion and attitudes towards specific topics or brands. The analysis uses the Twitter dataset, which includes tweets labeled with sentiments such as positive, neutral, and negative. The project is structured into several key steps: data loading and initial inspection, data cleaning, exploratory data analysis (EDA), sentiment analysis, and visualization of sentiment patterns.

In the data loading and initial inspection step, the datasets are loaded from CSV files and inspected to understand their structure. The datasets include columns such as sentiment, id, date, query, user, and text. Unnecessary columns are dropped, and a text normalization function is applied to convert the text to lowercase, remove URLs, mentions, hashtags, and special characters, ensuring the data is in a consistent format.

Next, in the EDA step, the distribution of sentiments is visualized using count plots, and word clouds are generated for each sentiment category to highlight the most common words. These visualizations provide insights into the dataset and help identify any potential issues with the data. The cleaning process also includes removing rows with empty text to prevent errors during word cloud generation.

For sentiment analysis, the text data is vectorized using TF-IDF vectorization, converting the text into numerical features suitable for machine learning. A Logistic Regression classifier is then trained on the training data, and the model's performance is evaluated on the validation set using accuracy and classification reports. This step helps in building a predictive model to classify sentiments of new tweets.

Finally, the sentiment patterns are visualized over time and compared between different topics or brands. The validation data is processed to add predictions from the trained model, and sentiment distribution over time is plotted to observe trends. Additionally, sentiment distribution by topic is visualized using count plots, providing a comprehensive understanding of public sentiment towards various topics or brands over time.

This structured approach ensures that the sentiment analysis is thorough, interpretable, and useful for understanding public opinions on social media.
