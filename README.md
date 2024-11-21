## Knowledge Graph Construction for Football Analysis

This project focuses on applying **Knowledge Graph** (KG) technology to football analysis. The main objective was to develop a knowledge graph that captures relationships between **teams**, **matches**, **players**, and their **performance metrics**. The knowledge graph provides a structured framework to uncover detailed insights into player and team performance, including data for further analysis (e.g. tactical, strategic decisions).

### Key Contributions:
- **Data Collection & Verification**: Collected datasets for the 2022/2023 season from multiple sources, including match outcomes from *Football Data.co.uk* and player statistics from *FBref.com*. The data was cleaned and verified to ensure accuracy, with a focus on removing inconsistencies and addressing missing values.
  
- **Building the Knowledge Graph**: Developed a robust KG by defining **classes** and **relationships** between football entities, such as players, teams, and matches. The data was converted into RDF format and structured into a graph with entities represented as nodes and relationships as edges. 

- **Data Quality Checks**: Performed rigorous checks to ensure data quality, focusing on the consistency and completeness of match and player data. Several SPARQL queries have been employed to identify and resolve inconsistencies.

- **Data Analysis**: Used the knowledge graph to analyze player and team performance. A particular focus was placed on assessing player contributions within their teams and identifying emerging talent.

- **Visualizations**: Created visualizations to show player contributions and identify key performers in matches. For example, an histogram was generated to highlight significant players in high-stakes matches, and pie charts were used to represent the contribution of top players to team performance.

- **Talent Scouting**: Used the knowledge graph to highlight emerging young talents by filtering players based on age and their contribution to goals and assists. 

### Technologies Used:
- **Python**: Primary programming language for data collection, processing, and analysis.
- **SPARQL**: Query language used to interact with the knowledge graph and extract meaningful insights.
- **NetworkX**: For graph construction and analysis.
- **Pandas**: For data cleaning and manipulation.
- **Matplotlib/Seaborn**: For data visualization.

### Further Research:
The next steps for this project will involve **extracting embeddings** from the knowledge graph. These embeddings will encode the relationships and properties of entities (e.g., players, teams, matches) and integrated with **machine learning algorithms**. By combining embeddings with advanced predictive models, the project would aim to predict match outcomes, future performance trends,  and identify players likely to excel in different match scenarios.

