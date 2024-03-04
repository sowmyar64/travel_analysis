# travel_analysis
Top Indian places to visit
# Introduction
Welcome to an extensive exploration guide showcasing must-visit destinations across India. This curated dataset offers detailed insights into each location's unique characteristics, serving as a valuable resource for travelers and enthusiasts alike. From historical landmarks to religious shrines and natural wonders, this dataset provides a comprehensive glimpse into India's diverse and rich cultural heritage.

# Objective
The objective of this dataset is to provide travelers and enthusiasts with valuable information and insights into must-visit destinations across India. It aims to offer detailed descriptions of each location's unique characteristics, including historical significance, religious importance, and natural beauty. By serving as a comprehensive resource for planning travel itineraries, exploring India's cultural heritage, and discovering hidden gems, this dataset seeks to promote a deeper understanding and appreciation of India's diverse cultural landscape through curated exploration.
In pursuit of the objective to provide travelers and enthusiasts with valuable information and insights into must-visit destinations across India, this dataset will undergo the following steps:
1) Ensure data quality and consistency by addressing missing values, outliers, and duplicates.
2) Standardize data formats and rectify any inconsistencies in column names or values to enhance data integrity.
3) Utilize EDA techniques to analyze data distributions, trends, and interrelationships effectively.
4) Summarize and visually represent key features using descriptive statistics, histograms, scatter plots, and heat maps.
5) Identify correlations between various features.
6) Uncover potential patterns or anomalies in the dataset.
7) Employ various visualization tools and libraries, such as matplotlib, Seaborn, and Plotly, to gain insights into the characteristics and distributions of the features.
8) Generate both static and interactive visualizations, including plots and charts, for comprehensive data exploration and presentation.


# About Dataset
This dataset is a curated exploration guide that encompasses must visit destinations across India. It serves as an extensive resource for travelers and enthusiasts alike, offering detailed insights into each location's unique characteristics. From historical landmarks to religious shrines and natural wonders, this dataset is a window to India's diverse and rich cultural heritage.

Column Descriptions:
- Zone: Geographical region of the place within India, categorizing it into zones like Northern, Southern, etc.
  
- State: The state in which the place is located, providing a regional context.
  
- City: The city or town where the destination is situated.
  
- Name: The name of the tourist spot or landmark.
- Type: Classification of the place, such as Temple, War Memorial, or Natural Park.
- Establishment Year: The year in which the place was established or discovered.
- Time Needed to Visit (hrs): Estimated duration in hours to thoroughly visit the place.
- Google Review Rating: The average Google review rating for the place, indicative of its popularity and visitor satisfaction.
- Entrance Fee in INR: The cost of admission in Indian Rupees.
- Airport within 50km Radius: Indicates if there is an airport within 50 kilometers of the place for accessibility.
- Weekly Off: The day of the week when the place is closed to visitors.
- Significance: The importance or role of the place, such as Historical, Religious, or Environmental.
- DSLR Allowed: Indicates whether visitors are permitted to use DSLR cameras at the location.
- Number of Google Reviews (in lakhs): The total number of Google reviews in lakhs (hundreds of thousands) that the place has received.
- Best Time to Visit: Suggested time of the day for visiting the place to have the best experience.

# 2. Methodology
### Data Collection
Gather relevant datasets from sources such as Differentiated Thyroid Cancer Recurrence.

### Data Cleaning
Identify and address missing values, outliers, and inconsistencies in the datasets to ensure data integrity and accuracy.

### Exploratory Data Analysis (EDA)
Explore the datasets to understand distributions, trends, and relationships between variables using descriptive statistics and data visualization techniques to uncover captivating insights into India's top destinations.

# Visualization

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/741b2e37-a171-4112-8618-1ec96e5a92ae)

#### Distribution of Landmarks by Zone:
The visualization illustrates the distribution of landmarks across different zones in India, revealing areas with higher concentrations of landmarks.


![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/4c96f247-d6d4-417b-9276-7ce17566e100)

#### Top 10 States by Number of Landmarks:
By highlighting the top 10 states with the highest number of landmarks, the visualization offers insights into the geographical distribution of landmarks across India.


![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/c8e8bf3a-767c-4f1b-8301-4357d237cf00)

#### Top 20 Types of Landmarks:
This visualization showcases the prevalence of various types of landmarks, with religious sites like temples and mosques dominating the list, providing insights into the cultural and religious significance of these landmarks in India.


![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/ec9428b8-f892-46a5-9f29-a6aca3087cdf)

Distribution of Establishment Years:
- The histogram shows the distribution of establishment years for landmarks.
- The x-axis represents the establishment year, while the y-axis indicates the number of landmarks established in each year or range of years.
- From the visualization, it appears that the number of landmarks established increases gradually over time, with some fluctuations in certain periods.

  ![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/6ee52a89-6653-4c31-b8fd-f27b7928e96c)
Review Ratings vs. Entrance Fees:
- The scatter plot displays the relationship between Google review ratings and entrance fees for landmarks.
- The x-axis represents Google review ratings, while the y-axis indicates entrance fees in INR.
- Each point on the scatter plot represents a landmark, and its position indicates its review rating and entrance fee.
- From the visualization, it's observed that there's no clear pattern or correlation between review ratings and entrance fees. Landmarks with varying review ratings have entrance fees distributed across a wide range.

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/c776effc-1a99-4710-923b-91bce92d57ae)

Distribution of Time Needed to Visit:
The histogram visually represents the distribution of time required to visit landmarks within the dataset.
- On the x-axis, the time needed to visit each landmark is displayed in hours, while the y-axis indicates the number of landmarks requiring a particular duration for visitation.
- The visualization reveals that most landmarks have a varied range of time needed for visitation, with peaks representing the frequency of landmarks requiring specific durations.
- This insight aids travelers in planning their itineraries by providing an understanding of the expected duration for visiting each landmark.

  ![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/ae13a9c1-6592-45d9-9d9e-09559e027283)

  Best Time to Visit Landmarks:
  -  The x-axis represents the number of landmarks, while the y-axis indicates the best time to visit.
  -  Each bar represents the number of landmarks suitable for visiting during specific times of the day.
  -  From the visualization, it's observed that the distribution of best times to visit landmarks varies, with some landmarks being ideal for visiting during all times of the day, while others are more suited 
     for specific times such as morning, afternoon, evening, or night.


![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/221cf769-e541-45b2-90c5-1219d4884a11)

Distribution of Landmarks by Historical Era:
- The bar plot illustrates the distribution of landmarks categorized into different historical eras based on their establishment year.
- Each era, such as Ancient India, Medieval India, Early Modern India, Colonial India, and Post-Independence, is represented on the y-axis.
- The x-axis indicates the number of landmarks belonging to each historical era.
- From the visualization, it's evident that landmarks are distributed across various historical periods, providing insights into the historical significance and evolution of landmarks over time.

