# Social Network Analysis Project: Friends Episodes

## Project Overview

This project focuses on performing a Social Network Analysis (SNA) on the relationships among characters in the popular television series Friends. 
The goal is to uncover the essential characters, dynamics, and structure of the series using network analysis tools. 
The analysis includes building a graph based on relationship data, computing basic graph properties, visualizing the network, and applying various centrality measures to identify key characters. 
Additionally, the project explores dynamic simulations to study the spread of influence within the network.

## Team Members

•	Muhammet Emin Albayram (303991)

•	Ege John Isik (302991)

•	Adasu Akel (305201)

•	Berke Tayfun Akseki (303981)

## Project Structure

The project is divided into several weeks, each focusing on different aspects of the analysis:

### Week 1: Data Preparation and Basic Graph Analysis

•	Data Cleaning: The dataset was read and cleaned to remove irrelevant lines and prepare it for analysis.

•	Graph Creation: A graph was created from the cleaned data, and basic properties such as the number of nodes, edges, average degree, and density were computed.

•	Graph Visualization: The graph was visualized using a spring layout, with node sizes based on degrees and colors based on community detection.

### Week 2: Structural Analysis and Centrality Measures

•	Clustering and Transitivity: The network's structural aspects were evaluated using average clustering and transitivity tests.

•	Centrality Measures: Key characters were identified using PageRank and Betweenness Centrality. Joey was consistently identified as an important node in the network.

### Week 3: Dynamic Simulations

•	Activation Propagation: The impact of thresholds and cascade probabilities on activation propagation rates was investigated using dynamic simulations.

•	Contagion Scenarios: Contagion scenarios were generated to study the spread of influence within the network.

## Key Findings

•	Essential Characters: Joey was identified as a central character in the network, playing a crucial role in connecting other characters.

•	Network Structure: The network exhibits low transitivity, indicating limited communication outside the main nodes.

•	Influence Spread: Dynamic simulations revealed how influence spreads through the network, with implications for public health and marketing strategies.

## Tools and Libraries

The project utilizes the following Python libraries:

•	NetworkX: For graph creation, manipulation, and analysis.

•	Matplotlib: For graph visualization.

•	Pandas: For data manipulation and analysis.

•	NumPy: For numerical computations.

•	Scikit-learn: For data preprocessing.

## Dataset

The dataset used in this project is a text file (friends_episodes.txt) containing relationship data among the characters in Friends. Each line in the file represents a relationship between two characters.


## Code Overview
The project is implemented in a Jupyter Notebook (Main.ipynb). The notebook is divided into sections corresponding to each week's tasks, with detailed explanations and code snippets.

## Key Functions

•	read_relationships(file_path): Reads the relationship data from the text file and creates a list of edges.

•	create_graph(relationships): Creates a graph from the list of edges.

•	compute_graph_properties(G): Computes and displays basic graph properties such as the number of nodes, edges, average degree, and density.

•	draw_graph(G): Visualizes the graph using a spring layout, with node sizes based on degrees and colors based on community detection.

## How to Run the Code

1.	Install Dependencies: Ensure you have the required Python libraries installed. You can install them using pip:

    ```pip install networkx matplotlib pandas numpy scikit-learn```

2.	Download the Dataset: Place the friends_episodes.txt file in the same directory as the Jupyter Notebook.
  
3.	Open the Notebook: Open the SNA_Project_Group_K.ipynb notebook in Jupyter.
   
4.	Run the Cells: Execute the cells in the notebook sequentially to perform the analysis.
    
## Conclusion

This project provides a comprehensive analysis of the social network within the Friends series, highlighting key characters and the structure of their relationships. The findings offer insights into the dynamics of the series and have broader implications for understanding real-world social networks.

## Future Work

•	Extended Analysis: Explore additional centrality measures and community detection algorithms.

•	Comparative Studies: Compare the network structure of Friends with other TV series or real-world social networks.

•	Interactive Visualizations: Create interactive network visualizations using tools like D3.js or Plotly.

## Acknowledgments

We would like to thank our instructors and peers for their support and feedback throughout the project. Special thanks to the creators of Friends for providing such a rich dataset for analysis.

________________________________________

For any questions or further information, please contact the project team members.


