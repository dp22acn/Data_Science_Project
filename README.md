# Data_Science_Project
Project Title: MATH AND MYTH: A NETWORK APPROACH TO MAHABHARATA

Project Overview
This project is based on Creating A network from text and Doing Social network Analysis on Mahabharata
This project aims to model the Mahabharata as a real-world social network, breaking its characters, events, and relationships into a network structure. By applying social network analysis techniques, this study reveals insights into the complex web of interactions and power dynamics in the Mahabharata.

Technologies Used
Python
NetworkX
Pandas
Matplotlib for visualization
Ghepi Network Analysis Software
Data Source
Mahabharata books from online source  https://sacred-texts.com/hin/maha/index.htm

Methodology:

Data Preprocessing: Cleaned and structured the data to identify characters, events, and relationships.
Network Construction: Built a social network by mapping characters and their interactions.
Analysis: Applied various network metrics, such as centrality, clustering coefficient, and average path length, to understand the social structure.
Visualization: Ghepi’s visualization libraries were used to create interactive social network graphs.

Project Summary
This project explores two distinct approaches to creating networks from a book using graph theory. Both methods aim to represent the relationships and interactions in the text as a meaningful network structure:

Manual Approach:
In this method, the dataset is carefully curated by manually reading the book, extracting relevant information, and constructing the network. This process ensures accuracy and attention to detail in mapping the relationships between entities.

Automated Approach:
This approach leverages Natural Language Processing (NLP) techniques, specifically a Named Entity Recognition (NER) model, to extract entities and relationships directly from the book. The extracted data is then processed to build the network automatically, providing a scalable and efficient alternative to the manual method.

Both approaches aim to provide insights into the narrative structure, emphasizing the versatility of combining traditional graph theory with advanced NLP techniques.

Use of Python and Gephi for Statistical Calculations and Better Results
Python in Both Approaches
Python plays a central role in both the manual and automated approaches of this project by providing the necessary tools for data extraction, processing, and analysis. Python is a versatile language with various libraries that are perfect for working with natural language and network data. In this project, it serves the following key functions:

Data Extraction:

In the manual approach, Python is used to organize and structure the information manually extracted from the book. Although the data extraction is done by reading the book, Python helps automate some of the processes, such as identifying keywords, cleaning text, and storing the extracted data in a format suitable for graph construction.
In the automated approach, Python is used to apply a NER (Named Entity Recognition) model, which automatically extracts entities (e.g., characters, places, events) and relationships (e.g., interactions, actions) from the raw text of the book.
Graph Construction:

After extracting the necessary data, Python libraries such as NetworkX are used to construct the network from the extracted entities. The relationships between entities are modeled as edges, and the entities themselves are represented as nodes in the graph.
Statistical Analysis:

Ghepi is used to perform various statistical and network metrics calculations. These include:
Degree Centrality: Identifying the most connected nodes.
Clustering Coefficient: Understanding the tendency of nodes to form clusters.
Path Length: Analyzing the shortest distance between nodes.
These metrics help in understanding the structure and behaviour of the network, leading to better insights.

Gephi is a powerful open-source tool used for visualizing and analyzing large networks. It complements Python by providing an intuitive graphical interface and advanced algorithms for statistical calculations, which allow for deeper insights into the structure of the network.

Visualization:

Gephi is particularly effective for visualizing networks. After constructing the graph in Python, the network is exported to a Gephi-compatible format (e.g., GEXF). Gephi's visualization features allow users to see the network in a visually intuitive manner, which helps in identifying key nodes, clusters, and network patterns.
Visual Layouts: Gephi provides various layouts (e.g., Force Atlas, Yifan Hu) to display the network in meaningful ways, making it easier to analyze the relationships and overall structure.
Advanced Statistical Calculations:

Gephi offers advanced algorithms that can be applied to networks, such as:
Modularity: Identifying communities within the network.
Betweenness Centrality: Determining nodes that act as bridges between different parts of the network.
PageRank: Measuring the importance of each node.
These statistical calculations, when used in conjunction with Python’s analysis, provide a more comprehensive view of the network’s structure and dynamics.
Refining Results:

By using Gephi's statistical analysis tools, the results from Python’s calculations are validated and refined. The ability to interact with the network visually and apply various algorithms allows for a better interpretation of the dataset.
Comparison with Real-World Networks
After building the networks using both the manual and automated approaches, the next step of the project involves comparing these mythological networks to real-world social networks. This comparison highlights the structural similarities and differences between the two, allowing us to draw meaningful conclusions about how mythological narratives mirror human society in terms of relationships, interactions, and social dynamics.

Steps in the Comparison Process
Real-World Social Networks:
Real-world social networks (such as those found on social media platforms, organizational structures, or even biological networks) are complex systems made up of interconnected entities (individuals, organizations, etc.). These networks are often characterized by metrics such as:

Degree Centrality: Identifying key influencers or central figures in the network.
Clustering Coefficient: Understanding the extent to which individuals form groups or communities.
Average Path Length: The average distance between individuals in the network, representing communication or relationship closeness.
Betweenness Centrality: Identifying individuals who act as bridges between different communities.
The same metrics are applied to the mythological networks to assess their structure.

Mythological Networks:
The mythological networks constructed in the project represent the relationships and interactions between characters and events within a narrative, such as in the Mahabharata or other mythological texts. These networks exhibit similar properties:

Nodes: Characters, places, or significant events.
Edges: Interactions, relationships, or influence among nodes.
Structural Patterns: Communities, cliques, or clusters based on the narrative arcs.
By applying Python and Gephi, network metrics like degree centrality, clustering coefficient, and path length are computed to understand the mythological network's structure.

By comparing mythological networks to real-world social networks, it becomes evident that mythological narratives often reflect the social dynamics of human societies. Despite their fantastical settings, the relationships, power structures, and social behaviour in these stories mirror the complex interactions that occur in real-world communities.

Network Metrics: The similarity in metrics like clustering, centrality, and path length between the two types of networks highlights the universality of social interaction patterns across time and cultures.
Cultural Insights: These findings suggest that mythological stories may not only serve as moral or religious narratives but also as representations of how ancient societies viewed relationships, power, and social structures.
Thus, the project shows that mythological networks are not only an artistic and literary tool but also an insightful way to study the social structures of past societies, offering a bridge between fiction and reality.



The analysis of the Mahabharata as a social network revealed several key insights:

Central characters like Krishna and Arjuna play pivotal roles in the network and influence events.
The network has an average path length of 2, and a clustering coefficient of 0.35, highlighting tight-knit groups within the larger narrative.


## License
[![License: CC BY-NC-ND 4.0](https://img.shields.io/badge/License-CC%20BY--NC--ND%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-nd/4.0/)


This dataset is licensed under the [Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License](https://creativecommons.org/licenses/by-nc-nd/4.0/).

- You may view the dataset for personal and academic purposes.
- Redistribution, modification, or commercial use is not permitted.

For permissions beyond the scope of this license, please contact [devendrapeddoju@gmail.com].




