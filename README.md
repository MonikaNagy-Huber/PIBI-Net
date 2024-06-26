# Physics-Informed Boundary Integral Networks (PIBI-Nets): a Data-Driven Approach for Solving Partial Differential Equations
This notebook provides code to the PIBI-Net for the Laplace and Poisson equation with point sources.
Please reference to our paper **[paper](https://arxiv.org/abs/2308.09571)** if you use the code of the provided Jupyter-Notebooks or parts of it. 

## PIBI-Net Architecure
![architecture](https://github.com/user-attachments/files/15988448/architecture.pdf)

## Abstract
Partial differential equations (PDEs) are widely used to describe relevant phenomena in dynamical systems. In real-world applications, we commonly need to combine formal PDE models with (potentially noisy) observations. This is especially relevant in settings where we lack information about boundary or initial conditions, or where we need to identify unknown model parameters. In recent years, Physics-Informed Neural Networks (PINNs) have become a popular tool for this kind of problems. In high-dimensional settings, however, PINNs often suffer from computational problems because they usually require dense collocation points over the entire computational domain. To address this problem, we present Physics-Informed Boundary Integral Networks (PIBI-Nets) as a data-driven approach for solving PDEs in one dimension less than the original problem space. PIBI-Nets only require points at the computational domain boundary, while still achieving highly accurate results. Moreover, PIBI-Nets clearly outperform PINNs in several practical settings. Exploiting elementary properties of fundamental solutions of linear differential operators, we present a principled and simple way to handle point sources in inverse problems. We demonstrate the excellent performance of PIBI-Nets for the Laplace and Poisson equations, both on artificial datasets and within a real-world application concerning the reconstruction of groundwater flows.


