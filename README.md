# Tf2_PINNs_code
Gradient enhanced PINNs implementation in TensorflowV2, with Fourier features, custom activation function and residual connections.

This code is for a simple heat equation

$u_{t} = u_{xx} + e^{-t}sin(\pi x)(1+\pi^{2})$       

0<x<1 ;  0<t<1;

$u(x,0)$ = $sin(\pi x)$ , 0<x<1;

$u(0,t)$ =  $u(1,t)$ = $0$, 0<t<1;

Exact Solution : $u(x,t)$ = $e^{-t}sin(\pi x)$
