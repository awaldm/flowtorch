# flowTorch

**flowTorch** - a Python library for analysis and reduced order modeling of fluid flows

*flowTorch* is developed primarily by the [Flow Modeling and Control group](https://www.tu-braunschweig.de/en/ism/research-workgroups/flow-modelling-and-control) led by [Richard Semaan](r.semaan@tu-braunschweig.de). The development is financed by the German Research Foundation (DFG) within the research program [FOR 2895](https://www.dfg.de/en/funded_projects/current_projects_programmes/list/projectdetails/index.jsp?id=406435057&sort=nr_asc&prg=FOR)


> unsteady flow and interaction phenomena at high speed stall conditions

with the primary goal to investigate flow conditions that lead to [buffeting](https://en.wikipedia.org/wiki/Aeroelasticity#Buffeting) at airfoils in the transonic flow regime.

**flowTorch is still under construction. The initial release is planned for January 2021.**

## Why *flowTorch*?

The *flowTorch* project was initiated to facilitate the processing and analysis of massive flow datasets having hundreds several **terabytes** in size. Its main applications are closely reflected by the *flowTorch* sub-packages:

| package | content |
| :------ | :-------|
|flowtorch.data | data loading, domain reduction, and sampling, e.g., using *sparse spatial sampling* (S<sup>3</sup>) |
| flowtorch.analysis | algorithms for dimensionality reduction, including *proper orthogonal decomposition* (POD), *dynamic mode decomposition* (DMD), and variants thereof |
| flowtorch.rom | reduced-order modeling using [cluster-based network models (CNM)](https://github.com/fernexda/cnm) |

*flowTorch* uses the [PyTorch](https://github.com/pytorch/pytorch) library as a backend for data structures, data types, and linear algebra operations on CPU and GPU. Some features that *flowTorch* focuses on include:

- parallel data processing on multiple CPUs and GPUs
- mixed-precision operations (single/double)
- user-friendly Python library that integrates easily with popular tools and libraries like *Jupyterlab*, *Matplotlib*, or *Numpy*
- a rich documentation with plenty of beginner-friendly but also realistic tutorials
- interfaces to common data formats like [OpenFOAM](https://www.openfoam.com/), [CGNS](https://cgns.github.io/), and [netCDF](https://www.unidata.ucar.edu/software/netcdf/) 

## Getting started

The central source of knowledge is the [flowTorch documentation](link). There you find

- [installation](link) instructions for users
- instructions for developers
- [examples](link)
- [Python API](link)

## Getting help

If you encounter any issues using *flowTorch*, please use the repository's [issue tracker](https://github.com/AndreWeiner/flowtorch/issues). Consider the following steps before and when opening a new issue:

0. Have you searched for similar issues that may have been already reported? The issue tracker has a *filter* function to search for keywords in open issues.
1. Click on the green *New issue* button in the upper right corner and describe your problem as detailed as possible. The issue should state what **the problem** is, what the **expected behavior** should be, and, maybe, suggest a **solution**. Note that you can also attach files or images to the issue.
2. Select a suitable label from the drop-down menu called *Labels*.
3. Click on the green *Submit new issue* button and wait for a reply.

## Reference

**TODO:** add citeable reference

## License

*flowTorch* is [GPLv3](https://en.wikipedia.org/wiki/GNU_General_Public_License)-licensed; refer to the [LICENSE](https://github.com/AndreWeiner/flowtorch/blob/main/LICENSE) file for more information.

