# robotic-vision
*Implementations and explorations of several pipelines and algorithms in Robotic Vision, as part of the Mobile Robotics (Monsoon 2020) class.*


<p align="center">
  <img src="https://user-images.githubusercontent.com/43912285/105778545-9aafab80-5f92-11eb-8451-2cd011412f9d.png" width=400>
</p>


## Contents

### Set-1
Set-1 consists of a basic overview of **euclidean transformations**, **ways of representing rotations** as well as an animation and explanation of the infamous **gimbal lock**.

### Set-2
Set-2 first looks at **non-linear optimizations** - the various algorithms and their characteristics. It then implements the **iterative closest point** algorithm (using singular value decomposition) for registering point clouds with known correspondences.

### Set-3
This set implements **camera calibration** using the direct linear transform algorithm, then goes on to look at the characteristics of **camera calibration matrices** and **epipolar lines**.

### Set-4
Set-4 implements **1D and 2D euclidean pose-graph optimisation for SLAM** from scratch, as well as with the aid of the `jax` auto-differentiation library. It then compares the results with those obtained using the **`g2o` solver**, using **`evo` to analyse the trajectories**. It also looks at the **challenges and possibilities of research in SLAM**.

### Set-5
Set-5 first looks at **dense stereo reconstruction** and the **iterative PnP** algorithm. It also peeks into the theory behind **structure from motion** pipelines and **bundle adjustment**.

## Setup

Please install the dependencies listed in `requirements.txt` before running the Jupyter Notebooks. Use of a virtual environment is recommended.

_**Disclosure:** These implementations are part of an undergraduate course on Mobile Robotics, and are meant to be learning excersizes. They may not be the cleanest or most efficient of implementations._
