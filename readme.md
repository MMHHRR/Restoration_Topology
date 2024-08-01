# Restoration_Topology_Graph
> Research framework. Our research consisted 5 parts: 1) extracting urban features related to psychology restoration, including socioeconomic, perceptional, and spatial features; 2) constructing a city-level graph by aggregating urban features into road units as nodes and road topology as edges; 3) labeling nodes by using the PRS-11questionnaire to score and label each road unit; 4) training the model and making prediction by treating the city-level graph as input to predict urban restoration quality through GNNs-based models; and 5) conducting an overall analysis, which including evaluating model performance, examining spatial distribution, and spatial structure of restoration quality.

![image](https://github.com/user-attachments/assets/12d36337-7ef5-4964-96f3-d1df283f693f)

> Highlight: Embedding the spatial structure. First, a spatial graph of entities was constructed by inferring the adjacency relationships between pixels of the entities. Second, cross-graph links were established by calculating the cosine similarity between corresponding entities (i.e., same category) in two graphs. ResNet-18 was employed for entity embedding. Finally, treating roads as the smallest units, GCN was utilized to transform the street structure into vectors.

![image](https://github.com/user-attachments/assets/633e1514-832b-4e1e-9e76-f345ab0bae61)


# Citation

Ma, H., Zhang, Y., Liu, P., Zhang, F., & Zhu, P. (2024). How does spatial structure affect psychological restoration? A method based on graph neural networks and street view imagery. Landscape and Urban Planning, 251, 105171. doi:[10.1016/j.landurbplan.2024.105171](https://doi.org/10.1016/j.landurbplan.2024.105171)

BibTeX:
```
@article{MA2024105171,
 author = {Haoran Ma and Yan Zhang and Pengyuan Liu and Fan Zhang and Pengyu Zhu},
 doi = {https://doi.org/10.1016/j.landurbplan.2024.105171},
 journal = {Landscape and Urban Planning},
 pages = {105171},
 title = {How does spatial structure affect psychological restoration? A method based on graph neural networks and street view imagery},
 volume = {251},
 year = {2024}
}
```
