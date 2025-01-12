# Urban Navigation using Scene Graphs

In this work, we are trying to solve the task of visual map-matching for precise localization in urban environments using scene graphs and GNNs.

We have two main modules:
1. Scene_Graph_Creator.ipynb - Using a VLM to transform 2D street view images into scene graphs with objects as nodes and spatial relations as edges.
2. SimGNN.ipynb - Using the [SimGNN framework]([url](https://github.com/gospodima/Extended-SimGNN/tree/master)) to learn similarity between graphs using real-world distance as the ground truth metric for supervision.

## Approach
<img width="962" alt="Overview of our approach" src="https://github.com/user-attachments/assets/1e40df4c-a831-4605-bd68-c5ee4a29eefd" />

## Results
Initial results (query image followed by top 3 retrieved nearest neighbors):

![image](https://github.com/user-attachments/assets/a0444eeb-427e-47b4-9c5f-b50fa726932e)
![image](https://github.com/user-attachments/assets/f7fe3dd3-4d94-4208-a463-cc2e4bdf5f07)
![image](https://github.com/user-attachments/assets/0073ae44-0ee9-4fd0-bfa1-a43cf239c0b6)
![image](https://github.com/user-attachments/assets/57631d00-e1b4-41af-b7ab-8c09ff004992)
