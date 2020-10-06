# Short Bio About Me
I am currently a staff scientist at Argonne National Laboratory, working on high performance scientific computing and machine learning and deep learning.

I graduated from the University Illinois at Urbana-Champaign in 2016 with a Physics PhD, and joined Argonne as a postdoc. In Argonne, my research has been gradually switch over to high performance computing and data science. I first worked on developing density function thoery and many-body perturbation theory codes (Qbox and WEST), porting and optimizing them on new HPC platforms. 

## PhD Study
I focused on computational condensed matter physics. In particular, I used first-principle approaches such as density functional theory and quantum Monte Carlo

## Current Research @ Argonne
### Exascale Computing Project
I am working on the ExaHDF5 project. The purpose is to deliever high performant HDF5 library on exascale platforms. One of my focus is system-aware HDF5 development. In the next generation platforms, we have hierachical storage system. One question is how to utilize the deep storage hierachy to efficiently move data from the lower level storage end such as the parallel file system to the compute node. Recently, we developed a cache VOL, in which we use the node-local storage to cache data to improve the parallel I/O performance. We have hiden the complexity in the HDF5 library and implement everything within the so0-called virtual object layer (VOL) framework. The users can in principle adopt this without changing of their codes. We expect many heavy check-pointing workloads and read intensive applications will gain significant benefit from our iimplementation

### Argonne Data Science Project
[more details to come]

### Physics
[more details to come]

