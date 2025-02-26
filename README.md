📊 Social Media Usage Analysis

This project analyzes social media usage patterns based on survey data. It explores factors like time spent on social media, platform preferences, and demographic details to uncover insights into user behavior.

📂 Project Structure

├── smmh.csv                           # Survey dataset  
├── social_media_analysis.ipynb        # Jupyter Notebook for data analysis  


🛠️ Tools & Libraries Used
	•	Python
	•	Pandas — Data manipulation and analysis
	•	Matplotlib — Data visualization

📊 Dataset: smmh.csv

The dataset contains survey responses with the following fields:
	•	Timestamp — Time of survey submission
	•	Age, Gender, Relationship & Occupation Status — Basic demographics
	•	Organization Affiliation — Type of organizations respondents are part of
	•	Social Media Usage — Whether they use social media or not
	•	Platforms Used — Popular platforms like Instagram, Twitter, Facebook
	•	Time Spent — Average time spent on social media daily
	•	Posting Frequency — How often respondents post content

Example data:

Timestamp, Age, Gender, Relationship Status, Occupation Status, Social Media Usage, Platforms, Time Spent, Posting Frequency  
2024-02-01, 21, Female, Single, Student, Yes, Instagram, 3 hours, Daily

📈 Analysis Goals
	•	User Demographics: Understand the age, gender, and occupation breakdown of users.
	•	Platform Preferences: Find out which platforms are most popular among respondents.
	•	Usage Patterns: Analyze how much time users spend on social media and their posting frequency.
	•	Behavior Insights: Study correlations between demographics and social media habits.

⚙️ How to Run the Project
	1.	Clone the repository:

git clone https://github.com/your-repo/social-media-analysis.git  
cd social-media-analysis

	2.	Create a virtual environment (optional but recommended):

python -m venv venv  
source venv/bin/activate    # On Windows: venv\Scripts\activate

	3.	Install dependencies:

pip install pandas matplotlib

	4.	Launch Jupyter Notebook:

jupyter notebook

	5.	Run the Notebook:
Open social_media_analysis.ipynb and execute the cells to perform the analysis and visualize the results.

📊 Key Insights (Example)
	•	Most Popular Platform: Instagram is the most used platform.
	•	Age vs Time Spent: Younger users tend to spend more time online.
	•	Posting Behavior: Students are more likely to post daily compared to professionals.

🚀 Future Improvements
	•	Sentiment Analysis: Analyze content sentiment from user posts.
	•	Clustering & Segmentation: Group users into clusters based on behavior.
	•	Interactive Dashboards: Use libraries like Plotly or Streamlit for dynamic exploration.

