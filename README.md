<div id="top"></div>

<!-- PROJECT LOGO -->
<br />

<h3 align="center">Biasing the quantum vacuum to control macroscopic probability distributions
</h3>

  <p align="justify">
    Code and data for paper "Biasing the quantum vacuum to control macroscopic probability distributions", preprint available on <a href="https://arxiv.org/abs/2303.03455">arXiv</a>.
    <br />
  </p>
</div>

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About</a>
      <ul>
        <li><a href="#built-with">Numerical methods</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>


<!-- ABOUT THE PROJECT -->
## About

This repository contains codes and data published in the above-mentioned manuscript. The methods presented here can be used to analyze weakly-biased optical parametric oscillators (OPO): 

<ul>
  <li>Numerical modeling of the two experimental configurations mentioned above, consisting in the combination of:</li>        
    <ul>
        <li> Stochastic differential equation model </li> 
        <li> Density matrix model </li>         
    </ul>        
  <li>Experimental data</li>
      <ul>
        <li> Power-dependent data generates plots for Figures 2 and 3 </li> 
        <li> Time-dependent data generates plots for Figure 4 </li>         
    </ul>        
</ul>

<p align="right">(<a href="#top">back to top</a>)</p>

### Numerical methods: implementation

Our numerical methods utilize some existing libraries and packages:

* [NLopt](https://nlopt.readthedocs.io/en/latest/) for optimization.

If you use some of those methods, please cite them as well, as appropriate. 

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

To get a local copy up and running follow these simple example steps.

### Installation

Clone the repository
   ```sh
   git clone https://github.com/charlesrc/pbit-opo.git
   ```

### Python Prerequisites

Python sections of the code were written in Python 3.9.7. To download required Python packages, you can use the following command (preferably in a virtual environment):
* Python Requirements
  ```sh
  pip install -r requirements.txt
  ```

### Julia Prerequisites

Julia sections of the code were written in Julia 1.6.1. To download required Julia packages, you can use the following command (preferably in a virtual environment):
* Julia Requirements
  ```sh
  Pkg.add(["PyCall", "PyPlot", "Peaks", "Statistics", "LinearAlgebra", "SparseArrays", "GSL", "DifferentialEquations", "Sundials", "LsqFit", "Printf", "Interpolations", "DelimitedFiles", "JLD2"])
  ```

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

All questions, inquiries, or suggestions should be addressed to the corresponding authors of the manuscript:

* Charles Roques-Carmes - [@personal_website](https://roques-carmes.com) - chrc@stanford.edu
* Yannick Salamin - salamin@mit.edu 
* Project Link: [https://github.com/charlesrc/pbit-opo](https://github.com/charlesrc/pbit-opo)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments


* This material is based upon work supported in part by the U.S. Army Research Office and was accomplished under Cooperative Agreement Number W911NF-18-2-0048.
* Yannick Salamin acknowledges support from the Swiss National Science Foundation (SNSF) through the Early Postdoc Mobility Fellowship No. P2EZP2-188091.

<p align="right">(<a href="#top">back to top</a>)</p>
