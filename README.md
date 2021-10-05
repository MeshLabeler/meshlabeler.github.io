
# MeshLabeler
**MeshLabeler** is a tool to help label the unlabeled (*i.e new or self made*) dataset manually over a private network so that together can make the task easier with a friendly UI.


```mermaid
graph TD;
A[Unlabeled Dataset] --- B((Worker#1));
A --- C((Worker#2));
A --- D((Worker#3));
A --- E((...));
A --- F((Worker#n));
```

### Objective
Once an enthusiast tried to help the world then he collected some raw data for curiousity or for research purpose or may he tried something new with the existing information.  
  ![ Once an enthusiast tried to help the world ](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/pre.png)
 
But he needed to be labeled this unlabeled the new dataset, segment the unsegmented image or map the action segment of the video data. Thus he wanted the help of his well wishers, team members. The job became very hard as he had to collaborate this large dataset by excel sheet or some tools. Also needed to do a small brief on the tools.  

  ![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/traditional.png)

Now all of his friends now avoiding him and sorrowfully started to hate him. It persists and then...

![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/world_destroyed.png)

So to avoid these angers, annoyings and hates; This system with a friendly UI and easy collaborative with privately distributed network system helps to reduce the time and complexity for these labeling and segmenting tasks. 

![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/soln.png)

It is also a contributors friendly system where help together in a easy way to make the world better. 

![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/better_world.png)

### Supported :

| **Data type** | **File** | **Perform** | **Status**
| Text | csv | Multi-label, Label | Developing
| Image | jpg | Segmentation, Label, Multi-label, Annotation |Not yet
| Video | mp4 | Segmentation, Label, Multi-label |Not yet
| Audio | wav | Segmentation, Label, Multi-label |Not yet

### **Limitation :**

 - Manage only one dataset at a time.
 - Save file will produce a file.
