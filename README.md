👋

**Drive to Survive Review Sentiment Analysis**

This project involves scraping reviews of the Netflix series "Drive to Survive" from IMDb, performing sentiment analysis on the collected reviews using a RoBERTa model, and visualizing the results.

**Project Structure**
*  dts_analysis.ipynb: Jupyter Notebook containing the analysis and visualization of the scraped reviews.
*  web_scraping.ipynb: Jupyter Notebook for scraping IMDb reviews using Selenium.
*  dts_review.csv: CSV file containing the scraped reviews.

**Dependencies**
*  Selenium
*  Pandas
*  NumPy
*  Hugging Face Transformers
*  Matplotlib
*  Seaborn

**Note**
Download the ChromeDriver executable and ensure it matches your installed version of Google Chrome. Place the executable in your project directory (For selenium).

**Usage**
Scraping Reviews:

*  Open web_scraping.ipynb in Jupyter Notebook.
*  Run the cells to scrape reviews from IMDb. The scraped reviews will be saved to dts_review.csv.

  
Sentiment Analysis:

*  Open dts_analysis.ipynb in Jupyter Notebook.
*  Run the cells to perform sentiment analysis on the scraped reviews using the RoBERTa model from Hugging Face.
*  Visualize the results of the sentiment analysis.

**The results of the sentiment analysis will include:**

*  Distribution of positive, negative, and neutral reviews.
*  Visualizations of review sentiments over time.
*  Word clouds of the most frequent words in positive and negative reviews.


**Contributions are welcome! Please open an issue or submit a pull request if you would like to contribute to this project.**
