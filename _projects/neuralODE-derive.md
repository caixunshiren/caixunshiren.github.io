---
layout: page
title: Graph Convolutional Neural ODE
description: Mathematical derivation of the vectorized adjoint sensitivity method for GCNODE.
img: https://tkipf.github.io/graph-convolutional-networks/images/gcn_web.png
importance: 2
category: research | machine learning
github: https://github.com/caixunshiren/Vectorized-Adjoint-Sensitivity-Method-for-Graph-Convolutional-Neural-ODE
pdf: https://github.com/caixunshiren/Vectorized-Adjoint-Sensitivity-Method-for-Graph-Convolutional-Neural-ODE/blob/main/Vectorized_Adjoint_Sensitivity_Method_for_Graph_Convolutional_Neural_Ordinary_Differential_Equations_V_2.pdf
---

# Vectorized Adjoint Sensitivity Method for Graph Convolutional Neural ODE

## Abstract

This document, as the title stated, is meant to provide a vectorized implementation of adjoint dynamics calculation for Graph Convolutional Neural Ordinary Differential Equations (GCDE). The adjoint sensitivity method is the gradient approximation method for neural ODEs that replaces the back propagation. When implemented on libraries such as PyTorch or Tensorflow, the adjoint can be calculated by autograd functions without the need for a hand-derived formula. In applications such as edge computing and in memristor crossbars, however, autograds are not available, and therefore we need a vectorized derivation of adjoint dynamics to efficiently map the system on hardware. This document will go over the basics, then move on to derive the vectorized adjoint dynamics for GCDE.


See the full pdf [here](https://github.com/caixunshiren/Vectorized-Adjoint-Sensitivity-Method-for-Graph-Convolutional-Neural-ODE/blob/main/Vectorized_Adjoint_Sensitivity_Method_for_Graph_Convolutional_Neural_Ordinary_Differential_Equations_V_2.pdf)
