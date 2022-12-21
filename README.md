# SO3_Equivariant_ProteinMPNN
## 📌 Master Thesis on Geometric Deep Learning on Protein Design
This is the code for the master thesis that introduce rotation invariant representation to ProteinMPNN


<!-- ABOUT THE RESEARCH -->
<h2 id="about-the-research"> :pencil: About The Research</h2>

**ProteinMPNN** is a message passing neural network that aims to find an amino acid sequence that will fold into a given structure. The full network is composed of an encoder and a decoder with 3 layers each. The network takes as inputs the 3D coordinates and computes the following information for each residue: (i) the distance between the N, Cα, C, O and a virtual Cβ atom, (ii) the Cα − Cα − Cα frame orientation and rotation, (iii) the backbone dihedral angles, (iv) the distances to the 48 closest residues. 
 
![image](./images/ProteinMPNN.png)

Building rotation invariant representation using [**Sperical Harmonics**](https://stevejtrettel.site/code/2022/spherical-harmonics), 3D coordinates of residule are expanded into radial and spherical basis, the combination of coefficients constitute an invariant representation.
![image](./images/Spherical_Expand.jpg)

Sperical Harmonics Visualisation [site](https://stevejtrettel.site/code/2022/spherical-harmonics)

## Dataset
Protein Data Bank

## Prerequisites

[![made-with-python](https://img.shields.io/badge/Made%20with-Python-1f425f.svg)](https://www.python.org/) <br>

<!--This project is written in Python programming language. <br>-->
The following are the major open source packages utilised in this project:
* Numpy
* SciPy
* Matplotlib
* Scikit-Learn
* Pytorch


<h2 id="folder-structure"> Folder Structure</h2>

   
      .  
      ├── images                                                       
      │    ├── ProteinMPNN.png                 
      │    └── Spherical_Expand.jpg
      │    
      │
      └── 


## 🎯 RoadMap



## Future Work
Benchmarking more physics-inspired representation methods

## Contributing
If you have any questions or suggestions towards this repository, feel free to contact me at xy2119@ic.ac.uk.

Any kind of enhancement or contribution is welcomed!
