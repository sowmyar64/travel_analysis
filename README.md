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
#### Distribution of Landmarks by Zone:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/741b2e37-a171-4112-8618-1ec96e5a92ae)

The visualization illustrates the distribution of landmarks across different zones in India, revealing areas with higher concentrations of landmarks.


#### Top 10 States by Number of Landmarks:

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/4c96f247-d6d4-417b-9276-7ce17566e100)

By highlighting the top 10 states with the highest number of landmarks, the visualization offers insights into the geographical distribution of landmarks across India.



#### Top 20 Types of Landmarks:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/c8e8bf3a-767c-4f1b-8301-4357d237cf00)

This visualization showcases the prevalence of various types of landmarks, with religious sites like temples and mosques dominating the list, providing insights into the cultural and religious significance of these landmarks in India.



#### Distribution of Establishment Years:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/ec9428b8-f892-46a5-9f29-a6aca3087cdf)


- The histogram shows the distribution of establishment years for landmarks.
- The x-axis represents the establishment year, while the y-axis indicates the number of landmarks established in each year or range of years.
- From the visualization, it appears that the number of landmarks established increases gradually over time, with some fluctuations in certain periods.


 #### Review Ratings vs. Entrance Fees:
  ![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/6ee52a89-6653-4c31-b8fd-f27b7928e96c)

- The scatter plot displays the relationship between Google review ratings and entrance fees for landmarks.
- The x-axis represents Google review ratings, while the y-axis indicates entrance fees in INR.
- Each point on the scatter plot represents a landmark, and its position indicates its review rating and entrance fee.
- From the visualization, it's observed that there's no clear pattern or correlation between review ratings and entrance fees. Landmarks with varying review ratings have entrance fees distributed across a wide range.


#### Distribution of Time Needed to Visit:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/c776effc-1a99-4710-923b-91bce92d57ae)


The histogram visually represents the distribution of time required to visit landmarks within the dataset.
- On the x-axis, the time needed to visit each landmark is displayed in hours, while the y-axis indicates the number of landmarks requiring a particular duration for visitation.
- The visualization reveals that most landmarks have a varied range of time needed for visitation, with peaks representing the frequency of landmarks requiring specific durations.
- This insight aids travelers in planning their itineraries by providing an understanding of the expected duration for visiting each landmark.


 #### Best Time to Visit Landmarks:
  ![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/ae13a9c1-6592-45d9-9d9e-09559e027283)


  -  The x-axis represents the number of landmarks, while the y-axis indicates the best time to visit.
  -  Each bar represents the number of landmarks suitable for visiting during specific times of the day.
  -  From the visualization, it's observed that the distribution of best times to visit landmarks varies, with some landmarks being ideal for visiting during all times of the day, while others are more suited 
     for specific times such as morning, afternoon, evening, or night.



#### Distribution of Landmarks by Historical Era:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/221cf769-e541-45b2-90c5-1219d4884a11)

- The bar plot illustrates the distribution of landmarks categorized into different historical eras based on their establishment year.
- Each era, such as Ancient India, Medieval India, Early Modern India, Colonial India, and Post-Independence, is represented on the y-axis.
- The x-axis indicates the number of landmarks belonging to each historical era.
- From the visualization, it's evident that landmarks are distributed across various historical periods, providing insights into the historical significance and evolution of landmarks over time.


#### Number of Landmarks by State and Types of Landmarks by State (Top 5 States):

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/03295c01-6acf-4285-9c8e-87c2ff350b37)
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/ee180eee-684d-4a52-9d29-c6bf0a8fd996)
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/27f1551e-7f3e-4959-9e2f-0bb6a4944f89)
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/e1a5694a-5dc4-4ce9-897f-a9f85314ae67)
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/6ecb66ad-4603-4cd5-b8c1-b32149690277)


The number of landmarks present in each state and sorts them in descending order based on the count. This provides an overview of the distribution of landmarks across different states in India.
For the top 5 states with the highest number of landmarks, the code generates individual bar plots to visualize the distribution of landmark types within each state. Each bar plot represents the top 10 types of landmarks found in the respective state, providing insights into the diversity of landmark types present in the most prominent states.



#### Distribution of Landmarks by Cultural Significance:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/6dee8f53-b48a-42af-8091-c0d5b9996635)


- The bar plot illustrates the distribution of landmarks categorized by their cultural significance.
- Each category of cultural significance, such as Historical, Religious, Nature, Recreational, and others, is represented on the y-axis.
- The x-axis indicates the number of landmarks belonging to each category.
- From the visualization, it's evident that landmarks are diverse in terms of cultural significance, with various categories including Historical, Religious, Nature, and more.
- This visualization provides insights into the cultural diversity and significance of landmarks, highlighting their importance in different aspects of culture and society.



#### Top 5 Rated Place Types:
![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/4efbca8b-4640-46a5-abf2-3a4f16bd0cd2)


- The bar plot displays the distribution of Google review ratings for the top 5 rated place types based on their significance.
- Each significance category, including Historical, Religious, Wildlife, Recreational, and Nature, is represented by a different color in the plot.
- The x-axis shows the Google review ratings, while the y-axis indicates the count of landmarks belonging to each rating category.
- From the visualization, it's evident that landmarks of different significance categories have varying distributions of Google review ratings.
- This visualization helps in understanding the overall ratings of the top-rated landmarks across different significance categories, providing insights into their popularity and public perception.


#### Average Google Review Rating by State:

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/a536d0b2-7b1a-4a31-863e-e3dd34dbd061)


- The bar plot represents the average Google review rating for landmarks across different states in India.
- Each state is represented along the x-axis, while the y-axis indicates the average Google review rating.
- The length of each bar indicates the average rating for landmarks in the respective state.
- From the visualization, it's evident that there are variations in the average Google review ratings across different states.
- This visualization provides insights into the overall satisfaction levels of visitors to landmarks in various states, helping travelers make informed decisions about their destinations.


#### Distribution of Landmarks by Significance and DSLR Allowed:

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/06116550-68c1-4c69-b149-cbebe2302a41)



- The bar plot illustrates the distribution of landmarks categorized by their significance and whether DSLRs (Digital Single-Lens Reflex cameras) are allowed for photography.
- Each category of significance, such as Historical, Religious, Environmental, and others, is represented along the y-axis.
- The bars are further divided into two colors representing whether DSLRs are allowed (Yes) or not allowed (No) for photography.
- The length of each bar indicates the count of landmarks belonging to each significance category and DSLR allowance status.
- This visualization offers insights into the policies regarding DSLR usage at landmarks across different significance categories, aiding photographers and enthusiasts in planning their visits and capturing memorable moments.



#### Correlation Matrix of Numerical Variables:

![image](https://github.com/sowmyar64/travel_analysis/assets/43263218/299775ef-19d3-42d6-9217-a9c7250e003a)



- The heatmap illustrates the correlation matrix of numerical variables extracted from the dataset, including Establishment Year, Time Needed to Visit in hours, Google Review Rating, Entrance Fee in INR, and Number of Google Reviews (in lakhs).
- Each cell in the heatmap represents the correlation coefficient between two numerical variables.
- The correlation coefficient ranges from -1 to 1, where:
    - A value close to 1 indicates a strong positive correlation.
    - A value close to -1 indicates a strong negative correlation.
    - A value close to 0 indicates no correlation.
- The intensity of the color in each cell indicates the strength of the correlation: darker shades represent stronger correlations.
- From the visualization, it's observed that:
   - Establishment Year and Entrance Fee in INR have a weak positive correlation.
   - Time Needed to Visit and Entrance Fee in INR have a moderate positive correlation.
   - Other variables show weak correlations with each other.


# Conclusion:
Based on the analysis and visualizations conducted on the "Indian Top Most Places to Visit" dataset, several conclusions can be drawn:

- Geographical Distribution: The dataset encompasses landmarks from various states across India, indicating the country's rich cultural and geographical diversity.

- Cultural Significance: Landmarks are categorized based on their cultural significance, including historical, religious, recreational, and natural landmarks, highlighting India's diverse cultural heritage.

- Visitor Experience: The dataset provides insights into visitor experiences, including Google review ratings, entrance fees, time needed to visit, and DSLR photography permissions, aiding travelers in planning their visits effectively.

- Historical Perspective: Landmarks are categorized into historical periods based on their establishment years, offering a glimpse into India's historical evolution from ancient times to the post-independence era.

- Correlation Analysis: Numerical variables such as establishment year, time needed to visit, Google review ratings, entrance fees, and number of Google reviews are analyzed for correlations, providing insights into potential relationships between these factors.

- Top Rated Landmarks: The dataset identifies the top-rated landmarks based on Google review ratings, allowing travelers to prioritize their visits to highly-rated destinations.
