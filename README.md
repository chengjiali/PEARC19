# PEARC19
[website](https://www.pearc19.pearc.org/program)
## Tutorial
#### Distributed deep learning
Objectives:
- To speed up deep learning training with multiple GPU / nodes

[Slides](./deep-learning.pdf)  
[The group](http://hidl.cse.ohio-state.edu)

#### Building containers images for HPC workloads
Objectives:
- NVIDIA builds its own container tool to run on HPC cluster to overcome the disadvantages of Docker and Singularity

[Slides and code](https://courses.nvidia.com/dli-event)

Event code:
- PEARC_HPC_CONT__AMBASSADOR_JULY19
- PEARC_MULTI_CONT__AMBASSADOR_JULY19

About Docker and Singularity:

Docker
- assume you root
- there is a file system where u can read & write
- distribute all the files to all the nodes, works in multinode env but have to mount folder \ pass /mere env variable manually, thats why use kubernetes.

singularity
- same user outside
- read only
- shared file system, by default mounted/ mered

#### Floating-point analysis tools
Objectives:
- Catch CUDA floating-point calculation exceptions, since CUDA has no mechanism to do that.
- Compiler optimizations

[Slides and code](http://fpanalysistools.org/pearc19/)
Access to remote server is turned off but source code is available. We can install the tools on discovery and play with it.

#### Rogues Gallery: Addressing Post-Moore Computing
[Slides](https://crnch-rg.gitlab.io/pearc-2019/)

#### Using the SPEC HPG Benchmarks for Better Analysis and Evaluation of Current and Future HPC Systems
[Slides](http://pages.iu.edu/~lijunj/pearc/)


## Panel
[Jupyter at Scale: HPC and Scientific Facilities](http://tiny.cc/pearc19-jupyter-hpc-bof)


## Paper
#### Harmony
harmony is a HARness MONitoring sYstem that is used to monitor the OLCF harness during acceptance.

[Github](https://github.com/olcf/harmony)

#### Shuffler
An image database for computer vision

#### Visualize the HPC cluster data
This is almost exactly same as what we are doing with the GPFS log visualization.

## Hackathon

Building sicnece gateways for HPC system.
- Building a web interface to submit and monitor jobs
- Create a new visualization gateway, COSMIC1, to display and manipulate image stacks for Biological purposes, such as image data from cryo-electron microscopy
- Distant Reader: from unstructured data to structured data

[More info](https://sciencegateways.org/engage/hackathon)

[PEARC18 Hackathon](http://nia.ecsu.edu/sgci/sgci_ci/ci2018/collage_006_HACKATHON18.html)

## Student modeling challenge
[Problems](https://drive.google.com/drive/folders/1ikH_0S4-IAaASiFJM0rO7rlPb6csPGEX)

[Parachute solution](https://docs.google.com/presentation/d/1bGjNnoPSTf41tFHQe36y0rKASok4wdosUgHWE-8CsMs/edit#slide=id.g5e1e4fca15_1_325)
