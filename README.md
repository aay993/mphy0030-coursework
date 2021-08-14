# MPHY0030: Programming Foundations for Medical Image Analysis 2021/22 

**Module lead**  
Yipeng Hu (yipeng.hu@ucl.ac.uk)  

|**Tutors**         | Email                     |
|:------------------|---------------------------|
|Zac Baum	        |zachary.baum.19@ucl.ac.uk  |
|Qianye Yang	    |qianye.yang.19@ucl.ac.uk   |

[UCL Moodle link][moodle_link]  

[moodle_link]: https://moodle.ucl.ac.uk/course/info.php?id=6306

## Development environments 
There is no requirement, in tutorials or assessed coursework, for what the development environment that needs to be used. However, technical support from this module is available for the setups detailed in the following documents, under `docs` folder.
- [Supported development environment for Python](./docs/dev_env_python.md)
- optional: [Supported development environment for MATLAB](./docs/dev_env_matlab.md)


## Python/MATLAB Tutorials

These are the tutorials under the `tutorials` folder using Python/MATLAB, with optionally assessed questions.

### MATLAB environment
MATLAB is a proprietary multi-paradigm programming language and numerical computing environment developed by MathWorks.

### Python environment
The tutorials require a few dependencies, numpy, scipy, matplotlib. Individual tutorials may also require other libraries which will be specified in the readme.md in individual tutorial folders (see links below).

Miniconda or Anaconda is recommended to set up the Python development environment.
```bash
conda create --name mphy0030 numpy scipy matplotlib 
```

### Image filtering 3d
Efficient high-dimensional image filtering  
[Tutorial][image_filtering_3d]

[image_filtering_3d]: ./tutorials/image_filtering_3d/readme.md

### Maximum intensity projection 
Inverting computerised tomography to obtain x-ray images  
[Tutorial][maximum_intensity_projection]

[maximum_intensity_projection]: ./tutorials/maximum_intensity_projection/readme.md

### Iterative closest point 
A point set registration algorithm, iterative closest point (ICP)  
[Tutorial][iterative_closest_point]

[iterative_closest_point]: ./tutorials/iterative_closest_point/readme.md

### Augmented reality on medical images
Display graphics overlaid with 3d medical imges  
[Tutorial][augmented_reality]

[augmented_reality]: ./tutorials/augmented_reality/readme.md

### 3DSlicer: Open-Source Medical Image Computing
Lecturer: Zachary Baum
Use existing open-source for visualizations in Jupyter Notebooks
[Tutorial][3d_slicer_jupyter]

[3d_slicer_jupyter]: ./tutorials/3d_slicer_jupyter/readme.md


### Paralell computing using PyTorch
The demo for guest lecture "Paralell computing using PyTorch", by Qianye Yang.
[Tutorial][pytorch_paralell_computing]

[pytorch_paralell_computing]: ./tutorials/pytorch_paralell_computing/readme.md