# Analysis of the Film Industry for Business Expansion
Recognizing the growing trend of major corporations producing original content, our company is embarking on the creation of a successful movie studio. To overcome our limited experience in film production, this project leverages a comprehensive analysis of various film industry datasets. Our objective is to extract data-driven insights that will illuminate the most profitable, well-received, and promising areas for investment. By integrating these datasets, we aim to identify current industry trends and provide actionable recommendations to guide our studio's film prioritization strategy.


## Business Understanding

The evolving landscape of streaming, global cinema, and digital distribution has transformed film production into a complex intersection of art and high-stakes business. To understand the drivers of film success, a thorough analysis of box office performance, critical reviews, audience preferences, and market trends is essential.

This analysis will address key business questions to inform strategic decision-making:

- **What genres are most consistently praised by critics?**
- **Which genres offer the highest potential for return on investment (ROI)?**
- **Are there directors whose films consistently achieve strong international performance?**
- **What languages are most commonly associated with successful films?**
By answering these questions, we aim to empower the new studio team with reliable data to go ahead with projects that resonate with audiences and maximize financial returns.
## Analysis Data

This project utilizes a powerful combination of industry datasets, each contributing unique insights to our understanding of the global film landscape:
- **The Numbers**: Providing crucial financial details such as production budgets and revenues, enabling accurate ROI calculations.
- **Box Office Mojo**: Offering data on gross earnings and overall box office performance.
- **Rotten Tomatoes**: Supplying critic and audience scores, along with valuable insights into review sentiment.
- **TheMovieDB**: Delivering rich metadata on movies, encompassing genres, languages, production countries, popularity metrics, and more.
- **IMDb Links**: Providing unique identifiers to facilitate cross-referencing of movies across all datasets.

### *1️⃣ Exploration of Data* 

This phase emphasizes a thorough understanding of the dataset by assessing its structure and identifying key columns essential for our analysis. We investigate potential relationships within the data and evaluate its cleanliness to determine if any areas require attention.

To achieve this, each team member explores different subsets of the data, focusing on understanding the distribution and data types while identifying any obvious issues, such as missing values or inconsistencies. The objective is to uncover initial patterns, pinpoint issues, and identify opportunities for further exploration, ultimately forming hypotheses that will guide the subsequent steps in our analysis.

### *2️⃣ Data Preparation & Cleaning* 
Following the initial exploration, we shift our focus to preparing the data for more in-depth analysis. This involves accurately merging various datasets to ensure that relationships are correctly explored.

We address any missing values through imputation, manage outliers, and carry out additional cleaning tasks, such as removing duplicates and resolving inconsistencies.

By structuring the data appropriately, we enable a deeper exploration of relationships while ensuring that the datasets are accurate, consistent, and ready for analysis. This stage is crucial for ensuring that the data is in a clean and usable state for modeling and deriving deeper insights.

### *3️⃣ Data Analysis*
#### Data Visualization
Team members investigate visual trends associated with genres, ratings, ROI, and other variables. Various visualization techniques, such as bar plots, box plots, histograms, and scatter plots, are employed to reveal patterns. The visual insights are cross-validated and shared within the team to enhance hypotheses and interpretations.

### *4️⃣ Business Recommendations*
The results are synthesized into clear, actionable insights for the new movie studio. All team members work together to ensure that recommendations align with the business objectives. The focus is on assisting decision-makers in prioritizing **genres**, **directors**, **languages**, and **film types** based on factors such as profitability, audience reception, and global appeal.

## Visualizations 
The following are the key visualizations that contributed to our understanding of the film industry:

#### 1️⃣ Understanding the Relationship between Genres and Ratings
![Top Genres by Average Rating (Audience vs Critic)](AvsC.png)

#### 2️⃣ Understanding the Relationship between Genre and ROI
![Normalized ROI per Genre](ROI.png)

#### 3️⃣ Understanding the Relationship between Language and Popularity
![Popularity Distribution by Top 20 Languages](lang.png)

#### 4️⃣ Understanding the Relationship between Directors and Worldwide Gross Earnings
![Top 10 Directors by Worldwide Gross](Dir.png)

## Summary
Our analysis indicates that G-rated and family-friendly films yield the highest ROI. Additionally, specific genres such as Drama and Animation consistently achieve strong ratings, while a select group of directors significantly contributes to higher foreign revenue. Although English remains the predominant language for popular films, non-English content also demonstrates potential. These insights can inform data-driven decisions regarding genre focus, content ratings, and director partnerships to ensure a successful market entry.