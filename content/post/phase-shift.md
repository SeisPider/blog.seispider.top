---
title: "Danger in performing phase shift with Python for a time series" 
date: 2018-07-29T21:44:43+08:00
lastmod: 2018-07-29T21:44:43+08:00
categories: ["Python"] 
tags: ["Signal", "Python"]
draft: false
author: "Xiao Xiao"
---

For scientific purpose, we sometime needs to shift phase of time series with specfic angles.
To acheive this, transforming the time series to freqeuency domain with 
     $$F(\omega) = \int_{-\omega}^{\omega} f(t) e^{-i \omega t} dt$$

where $F(\omega)$ as Fourier spectrum of signal $f(t)$. Thus, the phase shift equals 
$$F_{sh}(\omega) = F(\omega) * e^{-i \alpha}$$ 
<!--more-->

