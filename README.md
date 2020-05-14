[![HitCount](http://hits.dwyl.com/3D-Seismic-Attribute.svg)](http://hits.dwyl.com/ezygeo-ai/3D-Seismic-Attribute)
![GitHub contributors](https://img.shields.io/github/contributors/ezygeo-ai/3D-Seismic-Attribute)
![GitHub last commit](https://img.shields.io/github/last-commit/ezygeo-ai/3D-Seismic-Attribute)
![GitHub top language](https://img.shields.io/github/languages/top/ezygeo-ai/3D-Seismic-Attribute)
![GitHub language count](https://img.shields.io/github/languages/count/ezygeo-ai/3D-Seismic-Attribute)
![GitHub repo size](https://img.shields.io/github/repo-size/ezygeo-ai/3D-Seismic-Attribute)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/ezygeo-ai/3D-Seismic-Attribute)
[![LinkedIn](https://img.shields.io/badge/-LinkedIn-black.svg?style=flat&logo=linkedin&colorB=555)](https://www.linkedin.com/posts/hadyan-pratama-1177b713b_seismic-attribute-3dmodel-activity-6666550290327703552-aZi-)

The pupose of this repo is to reconstruct seismic attribute and visualize the result with 3D model visualization. We construct this using **Python** and **Jupyter Notebook IDE**.


## 3D Seismic Attribute: RMS Attribute Case
Reference: Seismic attributes [SEG Wiki](https://wiki.seg.org/wiki/Seismic_attributes)
Seismic SEGY data from [Kerry 3D](https://wiki.seg.org/wiki/Kerry-3D) 
We use [Segyio](https://github.com/equinor/segyio) to import .segy data and [Mayavi](https://docs.enthought.com/mayavi/mayavi/index.html) to create 3D Visualization 

First we apply the RMS amplitude algorithm to 2D [section](https://github.com/ezygeo-ai/3D-Seismic-Attribute/blob/master/KerryRMS.png)

<p align="center">
<img src="https://github.com/ezygeo-ai/3D-Seismic-Attribute/blob/master/KerryRMS.png" width="80%"></p>

And then apply the algorithm to seismic data [volume](https://github.com/ezygeo-ai/3D-Seismic-Attribute/blob/master/Kerry3DRMS.gif)

<p align="center">
<img src="https://github.com/ezygeo-ai/3D-Seismic-Attribute/blob/master/Kerry3DRMS.gif" width="80%"></p>
