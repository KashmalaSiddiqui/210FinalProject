# **210FinalProject**

The goal of this project is to explore and analyze Instagram activity data to uncover patterns and provide insights into personal engagement habits. The ultimate aim is to create a model that identifies trends in content consumption, author interaction, and engagement timelines. The insights gained could be expanded in the future to recommend optimal posting times and content strategies for higher interaction.

---

## **Dataset Description**

The dataset for this project consists of comprehensive data exported from my Instagram account. It includes details about posts, videos, and other activity, as well as my personal interactions (likes, comments, and views). The dataset is structured into the following components:

### **1. Post Details**
   - Information about viewed posts, including:
     - Post type: Photos, Reels, Stories, or standard posts.
     - Author data: The usernames of the post creators.
     - Timestamps for when the post was viewed.

### **2. Engagement Metrics**
   - Includes my interactions:
     - Likes: Posts that I liked, along with their authors and timestamps.
     - Comments: Comments I made, including their text and associated post authors.
     - Views: Videos and stories watched, along with timestamps.

### **3. Video and Story Data**
   - Details of videos and stories I viewed:
     - Number of views for specific authors.
     - Timestamps of viewing activity, showing trends over time.
     - Associated authors of videos or stories.

### **4. Ads and Topic Data**
   - Records of ads viewed or clicked, giving additional insight into content preferences.

---

## **Project Goals and Plan**

The primary objective of this project is to analyze Instagram data and build a framework to uncover behavioral patterns. The analysis will provide insights into:

### **1. Timeline Analysis**
   - Identify periods of peak engagement activity.
   - Analyze changes in viewing patterns over days, months, or years.

### **2. Author Interaction**
   - Identify which authors' content I interact with the most.
   - Categorize preferred types of authors or topics (e.g., travel, food, entertainment).

### **3. Content Categorization**
   - Analyze the types of content (Reels, Stories, standard posts) I consume the most.
   - Predict the kinds of posts I am likely to engage with based on historical data.

---

### **Plan**

#### **Data Collection and Preprocessing**
   - **Collection**: The dataset was downloaded from Instagram’s archive service.
   - **Preprocessing**:
     - Extract relevant fields (e.g., timestamps, authors, and post types) from the JSON data.
     - Normalize nested structures for analysis and convert timestamps into readable formats.
     - Clean and structure the data for machine learning tasks, such as encoding categorical variables (e.g., post types).

#### **Exploratory Data Analysis (EDA)**
   - Analyze:
     - Which authors or categories receive the most attention.
     - Content preferences (e.g., Reels vs. Stories).
     - Temporal trends in engagement activity (e.g., peak activity hours, days of the week).
   - Visualizations:
     - Bar charts to display top authors or content types.
     - Line graphs to represent engagement trends over time.
     - Heatmaps to showcase time-based activity.

#### **Feature Engineering**
   - Create features such as:
     - Time of viewing (e.g., hour of the day).
     - Day of the week.
     - Type of content consumed (e.g., video, photo, or carousel).
     - Author categorization (based on engagement history).

#### **Model Development**
   - **Goal**: Train a machine learning model to predict:
     - Engagement likelihood for specific types of content.
     - Temporal activity trends.
   - **Approach**:
     - Use regression models (e.g., Random Forest or Gradient Boosting) for predicting engagement trends.
     - Explore classification models (e.g., Logistic Regression or Neural Networks) for post categorization.
   - **Metrics**: Evaluate performance based on precision, recall, and F1 scores.

#### **Insights and Recommendation System**
   - **Recommendations**:
     - Provide personalized suggestions for authors and content categories based on engagement patterns.
     - Build a framework to predict whether a specific post (based on its type and timestamp) would resonate with me.
   - **Visual Output**:
     - Dashboards summarizing top content, activity trends, and author engagement.

---

## **Findings**

Through this project, I aim to:
   - Discover the authors and topics that dominate my activity feed.
   - Understand how my engagement patterns vary over time.
   - Identify the types of content I consume most frequently and predict future preferences.

### **What I Learned About Myself**
   - My Instagram activity reflects clear preferences for certain authors and topics.
   - Temporal trends reveal how my content consumption aligns with specific times of the day or week.
   - My engagement data (likes, comments, and views) provides valuable insight into my personal interests and evolving tastes.

---

## **Limitations and Future Work**

### **Limitations**
   - **Data Constraints**: The dataset only contains data provided by Instagram, which lacks rich details like hashtags or captions for posts.
   - **Content Context**: Without the actual post content or captions, it’s challenging to categorize topics precisely.
   - **Limited Scope**: Current analysis focuses on personal activity. Incorporating broader datasets (e.g., public user trends) could provide more robust insights.

### **Future Work**
   - Integrate natural language processing (NLP) to analyze text-based data, such as comments and captions.
   - Use computer vision techniques to analyze images and videos for content categorization.
   - Develop a machine learning model to recommend posts or predict content engagement likelihood.
   - Build an interactive dashboard to visualize engagement patterns and provide actionable insights.

This project provides a foundation for understanding Instagram activity and creating personalized engagement tools. The insights could also be applied to larger-scale social media analyses.
