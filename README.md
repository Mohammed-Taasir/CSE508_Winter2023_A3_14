# CSE508_Winter2023_A3_14

IR2022_A3_14
Assignment Info
Course: Information Retrieval [CSE508]
Semester: Winter 2023
Group: 14
Assignment 3

''' Repository Description
IR_Assignment_3.ipynb: all code with comments
Report.pdf: report with all the observations, formulae and explanations for assignment
Images: contains graphs and report images

''' .gitignore Description
All the data files are stored in the Dataset folder which is present in the root folder.

# Dataset Description
-Dataset chosen for this assignment is Wikipedia Vote Network, a network of who-votes-on-whom. The network is a bidirectional graph of 7115 nodes and 103689 edges. Nodes in the network represent wikipedia users and a directed edge from node i to node j represents that user i voted on user j.

# Code Explanation

## Q1

' Methodology

- Relevant libraries are imported
- File is read
- Adjacency Matrix, Adjacency List, Number of Nodes, Number of Edges, In-Degree List, Out-Degree List, Forward and Reverse Mapping of wikipedia users and nodes are created/determined
- Average In-Degree is calculated
- Average Out-Degree is calculated
- Node with Max In-Degree is calculated
- Node with Max Out-Degree is calculated
- Density of Network is calculated
- In-Degree Distribution is plotted
- Out-Degree Distribution is plotted
- Local Clustering Coefficient is calucalted for each node
- Local Clustering Coefficient Distribution is plotted
- Explanation
- Explanation of formulae, outputs and graphs can be found in the report

## Q2

' Methodology

- Relevant libraries are imported (NetworkX is used for this question)
- Directional Graph is made by reading the file
- PageRank score is calculated for each node and top 10 nodes with highest PageRank score are displayed
- Hubs score is calculated for each node and top 10 nodes with highest Hubs score are displayed
- Authority score is calculated for each node and top 10 nodes with highest Authority score are displayed
- Explanation
- Explanation and comparison of algorithms can be found in the report
