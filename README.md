# scener dataset

A dataset of 10,000 unique 3D scenes, each containing rendered images and corresponding 3D models in various formats, derived from ShapeNet classes.

<hr>

Link to dataset [scener-dataset](https://github.com/imangali01/scener-dataset/releases/tag/v1.0)

To generate your own dataset download 
[Blender2.9.0](https://download.blender.org/release/Blender2.90/)

basic run command:
`blender --background --python main.py > ./logs/output.txt`

After generating for several hours, the program starts to work slowly, and it will need to be restarted, this is the code that will run the code on generation and runs it in the subprocess:
`python run.py > ./logs/output.txt`

### Metadata
- 10000 sample unique 3d scenes

Used classes from ShapeNet dataset:<br>
![metadata.png](https://github.com/imangali01/scener-dataset/blob/main/images/metadata.png)

Folder structure:
```
scener_dataset
├───1001104546554069805
│   ├───images
│   │       img_r_010.png
│   │       img_r_026.png
│   │       img_r_042.png
│   │       img_r_058.png
│   │       img_r_074.png
│   │
│   └───model
│           model.mtl
│           model.obj
│           model_32.binvox
│           model_32.npz
│           model_64.binvox
│           model_64.npz
│
├───1001319629564954782
│   ├───images
│   │       img_r_010.png
│   │       img_r_026.png
│   │       img_r_042.png
│   │       img_r_058.png
│   │       img_r_074.png
│   │
│   └───model
│           model.mtl
│           model.obj
│           model_32.binvox
│           model_32.npz
│           model_64.binvox
│           model_64.npz
...
```

### Dataset sample:<br>

#### 3D model:
![3d_models](https://github.com/imangali01/scener-dataset/blob/main/images/3d_models.png)

#### Rendered images
![rendered_images](https://github.com/imangali01/scener-dataset/blob/main/images/rendered_images.png)
