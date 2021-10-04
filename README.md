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
Once an enthusiast tried to help the world the he collected some raw data.
![ Once an enthusiast tried to help the world ](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/pre.png)
But he needed to be labeled this unlabeled the new dataset and wanted the help of his/her well wishers, team members. The job became very painful as they have to collaborate this large dataset by excel sheet.
![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/traditional.png)
And then....
![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/world_destroyed.png)
But to avoid these anger, annoying etc etc ... [pore likhbo]
![enter image description here](https://raw.githubusercontent.com/MeshLabeler/meshlabeler.github.io/main/img/soln.png)
...help together in a easy way to make the world better. 
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
