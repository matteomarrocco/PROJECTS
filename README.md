### ⚽ **Football Performance Analysis Through Knowledge Graph Construction**

**Project Duration:** February 2024 - April 2024

In this project, I created a **football knowledge graph** to analyze match statistics and player performance data. The goal was to visualize the relationships between key **performance indicators** (KPIs), such as **progressive carries**, **passes**, **shots**, and **dribbles**, and understand how they correlate with overall match outcomes and player contributions.

#### **Objective:**
The primary objective was to create a structured, graph-based representation of football match data, enabling deeper insights into player performance and match dynamics. By constructing a knowledge graph, I was able to visually represent complex interactions between players, teams, and match events, which would traditionally be harder to analyze in tabular data.

#### **Approach & Methodology:**

1. **Data Collection & Integration:**  
   I began by gathering match statistics for multiple football games, focusing on player performance data from various matches. This included details such as passes, shots, goals, dribbles, and defensive stats. I then integrated the data into a unified dataset to construct the knowledge graph.

2. **Knowledge Graph Construction:**  
   Using **NetworkX**, I created a knowledge graph that represented various elements of the football matches. Nodes in the graph represented **players**, **teams**, **matches**, and specific **match events** (e.g., goals, assists, shots). The **edges** represented relationships, such as a player’s contribution to a match event, interactions between players during key moments, and connections between the match and the players involved.

3. **Top Player Identification:**  
   I used the graph to identify key players in each match. By focusing on metrics such as **progressive carries**, **passes**, **shots**, and **dribbles**, I identified which players were most impactful. The graph helped me to visualize the contribution of each player and how their actions connected with the success or failure of their team’s performance.

4. **Under-21 Player Performance:**  
   One interesting aspect of the project was to identify players under the age of 21 who made the most significant contributions to match outcomes. By filtering the knowledge graph for **Under-21 players**, I was able to see how young talent impacted the game. This was particularly insightful for discovering up-and-coming players who might not have been in the limelight but made crucial contributions to their teams’ performances.

5. **SPARQL for Querying the Graph:**  
   I leveraged **SPARQL** queries to query the graph and extract specific insights. For example, I could query the graph to find the top players for each match based on specific performance indicators, track players who consistently made key contributions, or even look at how team performance changed over the course of the season.

#### **Key Insights:**
- **Top Performers:** By analyzing the graph, I identified the top 5 players per match based on KPIs like progressive carries, passes, and dribbles, which are essential for measuring attacking and defending efforts.
- **Under-21 Talents:** A major insight was the identification of young players (Under-21) who were significantly contributing to match results, demonstrating how emerging talent impacts modern football.
- **Match Dynamics:** The graph helped in understanding the relationship between different match events and how certain actions (e.g., progressive carries, passes) were linked to goals or key moments in a match.
- **Team Dynamics:** It became evident that **team chemistry** and the connection between players played a significant role in achieving success on the field, as visualized through the graph's connected nodes.

#### **Technologies & Tools Used:**
- **Python**: Core language for data manipulation, analysis, and graph construction.
- **NetworkX**: Used for graph creation and analysis. The library was essential for building the structure of the knowledge graph, visualizing player connections, and extracting insights from the graph.
- **SPARQL**: Employed for querying and extracting specific relationships from the knowledge graph.
- **Pandas**: Used for handling, cleaning, and processing the match data before it was fed into the graph.
- **Matplotlib**: Utilized for graph visualization and plotting key results and relationships.

#### **Challenges Encountered:**
- **Data Quality & Consistency:** Football data often comes in raw, uncleaned formats, requiring significant preprocessing to make it usable. Many of the metrics were incomplete or had missing values, which required data imputation and normalization techniques to ensure the integrity of the knowledge graph.
- **Graph Complexity:** As the graph grew with more matches, players, and match events, it became increasingly complex. Optimizing the graph’s structure to ensure performance while maintaining a clear visualization was a key challenge.
- **SPARQL Query Optimization:** Writing efficient SPARQL queries to extract meaningful insights from large graphs posed challenges, especially when querying for highly specific or complex relationships.

#### **Outcome & Future Work:**
The project led to the successful creation of a **football knowledge graph** that provided valuable insights into match dynamics and player performance. It also allowed me to experiment with graph-based methods of analyzing sports data, which is a growing area of interest. The next steps would be to extend the analysis to include **season-wide data**, integrating **player transfers**, and creating **predictive models** using the graph to forecast match outcomes or player performance based on historical data.

This knowledge graph project not only deepened my understanding of **graph theory** but also showed me the potential of applying such methods in **sports analytics**, an area I'm eager to explore further.

---

### **Demo & Visualization**  
(If you have links to interactive visualizations or a demo of the graph, you can include them here.)

---

### **Key Takeaways:**
- **Football Knowledge Graphs** are powerful tools for understanding and visualizing player contributions and match dynamics.
- By integrating **performance data** into a knowledge graph, we can see connections that would otherwise remain hidden in traditional tabular formats.
- Graph-based analysis opens new doors in **sports analytics**, from player scouting to performance prediction.

