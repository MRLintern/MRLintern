## Hello 👋, I'm Matthew Lintern-Monro, but I go by Matt

### Contact Me:

* Tel (Mob): 07813661626
* <lintern121184@gmail.com>
 

### Interests
- Languages I prefer developing with: __C, Modern C++ and Fortran__. However, I've got a decent amount of experience using __MATLAB__ & __Python__ from my time working in the __Oil & Gas__ and __HR/Retail Analytics__ industries.
  

- __Machine Learning (Fluid Dynamics)__. E.g. Application of __Deep Learning Algorithms/Methods__ for replacing or augmenting __Conventional Numerical Solvers__ in __Fluid Dynamics__.
- __Machine Learning (Natural Language Processing)__. I've used this in a couple of jobs and it proved to be very informative. E.g. I used __Sentiment Analysis__ while working at Tesco to understand customer opinions of Tesco products.
- __Computational Science__. 
- __Scientific Programming__: E.g. __Modelling and Simulation__ of problems in __Fluid Dynamics__ & the __Physical Sciences__.


### What I'm up to?
- ___viscousRiver___: a __Modern C++__ solver for modelling a ___Viscous Fluid flowing through a Channel___. Makes use of the __Finite Element Method (FEM)__ and the __Eigen Template Library (Eigen)__ for the __Algebra__. Currently making this more modular; its all in 1 `main.cpp` source file.

- ___2D-NavierStokes_Flow___: a __C++__ solver for solving the __2D Navier-Stokes Equations__ for a fluid in a River/Open Channel. Makes use of the __Eigen Template Library (Eigen)__ to implement the __Successive Over Relaxation (SOR) Algorithm__. This project is essentially a __C++__ version of the ___NavierStokes-2D-ChannelFlow___ __Fortran__ solver. However, instead of using __Finite Differences__ it will use the __Finite Element Method (FEM)__. The __Mesh Points__ will be loaded into the application. The `meshPoints.dat` file from [viscousRiver](https://github.com/MRLintern/viscousRiver) will be used. Note: ___viscousRiver___ has to be run to use the resulting `meshPoints.dat` file.
 

- ___Linear-Solvers___: This is software, developed in __C++__, that compares the __Jacobi__, __Gauss-Seidel__ and __Successive Over Relaxation__ methods for solving __Linear Algebraic Systems__ of the form ___Ax = b___. The solvers/methods are developed using the __Eigen Library__. By compare, I mean, how long does it take for the solutions of ___Ax = b___ to converge for each method. Initially, a __serial__ approach is used, and then a __parallel__ approach using __OpenMP__. Performance metrics/indicators, such as, __speed-up__ and __efficiency__ will be calculated for the __parallel__ case.





### Projects that are Comming Up
- Re-developing the ___NavierStokes-2D-ChannelFlow___ __Fortran Solver__ from a __Serial__ to a __Parallel__ version, making use of __OOP__ techniques and the __OpenMP__ API.

  
- ___fastFLOW___: a solver for either ___burgerFLOW___ or ___viscousRiver___, using the __SYCL Framework__, the __Finite Element Method__ and the __Eigen C++ Template Library__. Initially this will be a project that looks at applying __Heterogeneous Computing__ to __Fluid Dynamics__. If this works out, I'd like to incorporate some sort of __Neural Network__.
- ___sigPro___. This is a __Dynamic Library (.SO)__ developed in __Modern C++__, (hopefully __C++20__), which allows the user to perform basic __Signal Processing__ tasks. E.g. converting __temporal data into frequency data__ via the __Discrete Fourier Transform (DFT)__.
- ___fastDFT___. Using __OpenCL__ to develop a solver for the __Discrete Fourier Transform (DFT)__.
- ___lidFlowFVM___. This is a __C++__ solver, which models __Lid-Driven Cavity Flow__. The __Discretization Method__ used will be the __Finite Volume Method (FVM)__. Everything else will be developed by myself.
- Developing __Unit Tests__ for a number of solvers developed in __C__. See repositories from __High Performance Computing Applications for Physical Simulation__. 
- A __Dynamic Library__ called ___cfvmLib___, developed in __C++__, (hopefully __C++20__), for problems in ___Fluid Dynamics___. The __Discretization Method__ used will be the __Finite Volume Method (FVM)__. __Linear__ problems will be tackled first; hopefully __Non-Linear__ problems will be tackled not too far down the line!
- __Linux Kernel__ called ___basix___.
- __Operating Systems: Three Easy Pieces__. I've been meaning to read this for years!
- __Compiler__ using __C__. Language implementation will (hopefully) be with __Rust__. 
- __Operating System__ developed in __Rust__. Project Name: ___ros___.
- __RDBMS (SQL)__ developed in __C++__. Hopefully look at doing this with __C++20__. Project Name: ___CDB++___. 
- __Distributed File System__ development in __Golang__. Project Name: ___GoDistIt___.
- __Rust__ version of __Git__. Project Name: ___RustIt___.
- __Compiler Development__ using __LLVM__.
- __Heterogeneous Programming__: Using __SYCL__ to develop a __Numerical Solver__ for the __Linear 2D Heat/Diffusion Equation__. Could be any __Partial Differential Equation__; TBC.

### Top Languages
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=MRLintern&layout=compact&theme=rose_pine&hide=jupyter%20notebook,javascript,html)](https://github.com/anuraghazra/github-readme-stats)



  

### Sample Projects
Some projects I'm quite chuffed with.

#### Scientific Computing

- [Application of the Shallow Water Equations to Problems in Oceanography & Planetary Atmospheres](https://github.com/MRLintern/Shallow_Water_Equations).
- [Navier-Stokes Equation Solver for 2D Open Channel Flow](https://github.com/MRLintern/NavierStokes-2D-ChannelFlow).
- [Application of the U-Net Convolutional Neural Network to Classify Salt and Sediment Structures in Oil & Gas Reservoirs](https://github.com/MRLintern/Salt_and_Sediment_Classification).
- [viscousRiver; A Modern C++ Solver which uses the Finite Element Method and the Eigen Template Library to Model a Viscous Liquid Flowing through an Open Channel/River](https://github.com/MRLintern/viscousRiver).

#### High Performance Computing Applications for Physical Simulation
- [2D Poisson Equation Solver with OpenMP](https://github.com/MRLintern/2D_Poisson_Equation_OpenMP).
- [2D Heat Equation Solver using OpenMP](https://github.com/MRLintern/2D-Heat-Equation_OpenMP).
- [2D Heat Equation Solver using MPI](https://github.com/MRLintern/2D_Heat_Equation-MPI).
- [1D Wave Equation Solver using MPI](https://github.com/MRLintern/1D_Wave-Equation-MPI).











                                                                                                       

  

  
    
 
