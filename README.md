# Design of Semantic Net
# Overview
This project focuses on exploring the practical applications of semantic networks for knowledge representation. 
Semantic networks are essential tools in various domains, including artificial intelligence and 
data modeling, providing a structured approach to organizing and connecting information. 
By implementing code that allows users to create and manipulate semantic networks with defined concepts and 
relationships, we aim to demonstrate the versatility and utility of this technology.

## Introduction
Semantic networks are a fundamental tool for knowledge representation and play a
crucial role in various domains, including artificial intelligence, data modeling, and information
retrieval. These networks are a structured way of organizing and connecting information, which
allows the representation of relationships between different entities. The use of semantic
networks facilitates a deeper understanding of the knowledge they encapsulate, making it a
valuable asset in the field of problem-solving.

Knowledge representation using semantic networks is integral in the realm of AI and
information processing. It enables machines to not only store information but also to reason,
query, and make inferences based on the relationships between different entities. This
knowledge representation approach has broad applications, from expert systems in healthcare
to semantic search engines on the web. In this report, we are going to go through how we
implemented our code, which serves as a practical demonstration of how semantic networks
can be applied to knowledge representation. It allows users to create and manipulate a
semantic network with defined concepts and relationships, offering a tangible example of how
this technology can be used.

## Background
We implemented the code using Python, which is one of the most well-known high-level
languages nowadays. We used two main libraries that helped in the implementation, NetworkX
and Matplotlib, let’s discuss them briefly.

### NetworkX Library
NetworkX is a powerful Python library for working with complex network
structures, making it an ideal choice for defining and manipulating the graph structure
in our code. It provides a wide range of tools for graph analysis and manipulation,
enabling the creation and management of nodes and edges, as well as various graph
algorithms.

### Matplotlib
Matplotlib, on the other hand, plays a crucial role in data visualization. In our
code, Matplotlib is used to create visual representations of the semantic networks. When
users choose the "Visualize Example Graph" and "Visualize General Graph" options,
Matplotlib is employed to render these graphs, complete with node labels and edge
relationships.

## Semantic Net Domain & Design
Semantic networks are a structured approach to knowledge representation, and their design is
fundamental to their utility. Our approach for a domain is a “Hospital”. The following figure
shows the general graph for our semantic net:



The graph explains the visualized relationship between 6 different parties: Doctor,
Patient, Hospital, illness, medication, and symptoms. Labels for relationships are shown in red.
To illustrate this better, we included a default example graph in our code, which the user
then can edit to their preference. The following figure shows the example graph:


## Implementation
Our implementation is structured as a menu, which the user can use to manipulate and edit the
semantic net. We are going to discuss each option in the menu and then give a sample output of
the program at hand.

### Program menu


#### 1 - Add/link nodes with the relationship:
Users can input the first node, the second node, and the relationship between them. For
example, adding a relationship "Dr. Mohammed Diagnoses Yazan" would result in the
creation of this connection.



#### 2 - Delete a node:
Users can delete nodes from the graph. If a node exists, it is removed.



#### 3 - Visualize Example Graph:
The code provides a visualization of the example graph discussed in the previous section.

#### 4 - Visualize General Graph:
The structure of the general graph is visualized, illustrating the predefined concepts and
relationships. This is to help the user understand how to logically build the relationships
between the nodes in a hospital domain.

#### 5 - Create Example Graph:
This option creates the default Example Graph, then the user can manipulate it using the option
1 and 2.

#### 6 - Search Node Path from Source to Destination:
Users can search for a path between two nodes in the example graph. The code will
display the path if it exists.



#### 7 - Search Nodes by Relationship:
Users can search for nodes connected by a specific relationship. The code will display
the nodes that share the specified relationship.



#### 8 - Exit Program

## Conclusion
In conclusion, our code showcases the practical utility of semantic networks in
knowledge representation and manipulation. These networks are integral to a wide range of
domains, including artificial intelligence, data modeling, and information retrieval.
By utilizing the NetworkX and Matplotlib libraries, our code provides a hands-on
example of how semantic networks can be employed to organize, visualize, and interact with
complex knowledge structures of a hospital system.
However, we tried to make the program as dynamic as possible, which means that the
user is free to change the domain from a hospital domain to an entirely different one. With that
being said, we can conclude that our program is a good educational and practical resource for
comprehending the significance of semantic networks and their pivotal role in structuring
knowledge for diverse applications.

## References
* Hagberg, A., Swart, P., & S Chult, D. A. (2008). Exploring network structure,
    dynamics and function using NetworkX. In Proceedings of the 7th Python in Science
    Conference (Vol. 11, pp. 11-15).
* Hunter, J. D. (2007). Matplotlib: A 2D graphics environment. Computing in Science &
    Engineering, 9(3), 90-95.
* [Aminelasheb. (Feb 2023). semantic-networks: applying the concepts of semantic
    networks using Python & NetworkX. GitHub.](https://github.com/aminelasheb/Semantic-Networks/tree/main)
* [Zinoviev, D. (2021, July 23). Semantic Networks. Medium.](https://medium.com/pragmatic-programmers/semantic-networks-493839cddade)
