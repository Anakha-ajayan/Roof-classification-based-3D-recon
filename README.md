# **Roof Classification based 3D Reconstruction**

**Introduction**

This project focuses on reconstructing 3D models of building roofs from semantically labeled point cloud data.
The workflow involves segmenting individual building point clouds, classifying the roof type, replacing each roof with a representative 3D model at the correct absolute height, and reconstructing the full structure.

The input data (semantically labeled point clouds) is not included in this repository due to privacy policies.
The classification model is trained on the RoofN3D dataset, with an additional class added for flat roofs.


## Order of Execution

1. TALD1.ipynb
2. final.ipynb

## Acknowledgements

We sincerely thank the Indian Institute of Space Science and Technology (IIST) for providing the TALD dataset and their continuous support.
