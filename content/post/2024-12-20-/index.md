---
title: Laplacian operator in spherical coordinate system
author: Morphism28
date: '2024-12-20'
categories:
  - Physics
tags:
  - Laplacian operator
  - spherical coordinate system
output: pdf_document
---

啊

$$
\begin{aligned}
x &= r \sin \theta \cos \phi, \\
y &= r \sin \theta \sin \phi, \\
z &= r \cos \theta.
\end{aligned}
\tag{1}
$$
啊
$$ 
\begin{aligned} 
\boldsymbol{r} &= x \hat{\boldsymbol{e}}_x + y \hat{\boldsymbol{e}}_y + z \hat{\boldsymbol{e}}_z \\
               &= r \sin \theta \cos \phi \hat{\boldsymbol{e}}_x + r \sin \theta \sin \phi \hat{\boldsymbol{e}}_y + r \cos \theta \hat{\boldsymbol{e}}_z \\
               &= r (\sin \theta \cos \phi \hat{\boldsymbol{e}}_x + \sin \theta \sin \phi \hat{\boldsymbol{e}}_y + \cos \theta \hat{\boldsymbol{e}}_z)
\end{aligned}
\tag{2}
$$
我
$$
\begin{aligned}
\begin{cases}
\frac{\partial \boldsymbol{r}}{\partial r} = \sin \theta \cos \phi \hat{\boldsymbol{e}}_x + \sin \theta \sin \phi \hat{\boldsymbol{e}}_y + \cos \theta \hat{\boldsymbol{e}}_z \\
\frac{\partial \boldsymbol{r}}{\partial \theta} = r \cos \theta \cos \phi \hat{\boldsymbol{e}}_x + r \cos \theta \sin \phi \hat{\boldsymbol{e}}_y - r \sin \theta \hat{\boldsymbol{e}}_z \\
\frac{\partial \boldsymbol{r}}{\partial \phi} = -r \sin \theta \sin \phi \hat{\boldsymbol{e}}_x + r \sin \theta \cos \phi \hat{\boldsymbol{e}}_y
\end{cases}
\end{aligned}
\tag{3}
$$ 

(3)式中的向量两两正交, 于是定义如下正交的单位向量 $\hat{\boldsymbol{e}}_r$, $\hat{\boldsymbol{e}}_\theta$, $\hat{\boldsymbol{e}}_\phi$为:

$$
\begin{aligned}
\hat{\boldsymbol{e}}_r & = \sin \theta \cos \phi \hat{\boldsymbol{e}}_x + \sin \theta \sin \phi \hat{\boldsymbol{e}}_y + \cos \theta \hat{\boldsymbol{e}}_z \\
\hat{\boldsymbol{e}}_\theta & = \cos \theta \cos \phi \hat{\boldsymbol{e}}_x + \cos \theta \sin \phi \hat{\boldsymbol{e}}_y - \sin \theta \hat{\boldsymbol{e}}_z \\
\hat{\boldsymbol{e}}_\phi & = = -\sin \phi \hat{\boldsymbol{e}}_x + \cos \phi \hat{\boldsymbol{e}}_y
\end{aligned}
$$
我
$$
\begin{equation} 
\left\{\begin{aligned} \frac{\partial \boldsymbol{\mathbf{r}} }{\partial r} &= \sin\theta\cos\phi\, \hat{\boldsymbol{\mathbf{x}}} + \sin\theta\sin\phi\, \hat{\boldsymbol{\mathbf{y}}} + \cos\theta\, \hat{\boldsymbol{\mathbf{z}}} \\ \frac{\partial \boldsymbol{\mathbf{r}} }{\partial \theta} &= r\cos\theta\cos\phi\, \hat{\boldsymbol{\mathbf{x}}} + r\cos\theta\sin\phi\, \hat{\boldsymbol{\mathbf{y}}} - r\sin\theta\, \hat{\boldsymbol{\mathbf{z}}} \\ \frac{\partial \boldsymbol{\mathbf{r}} }{\partial \phi} &= -r\sin\theta\sin\phi\, \hat{\boldsymbol{\mathbf{x}}} + r\sin\theta\cos\phi\, \hat{\boldsymbol{\mathbf{y}}} \end{aligned}\right. \end{equation}
$$
