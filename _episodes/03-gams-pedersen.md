---
title: Using GAMs for Analysing Movement Data
teaching: 0
exercises: 0
---

This page archives the lesson materials for "Using GAMs for Analysing Movement Data", given by Eric Pedersen at the 2024 OTN Symposium ECR Workshop. 

**Abstract**

The first hour of the workshop will focus on what a GAM is, and the core concepts needed to interpret GAMs (basis functions, penalties, restricted maximum likelihood), with a focus on movement-relevant examples. The second hour of the workshop will focus on specific issues with applying GAMs to high-frequency movement data (handling big data sets, dealing with strong spatiotemporal autocorrelation in observations), as well as using GAMs to model special types of data. 
 
 The workshop will use the R package `mgcv` for fitting and estimating GAMs, and the `gratia` package for visualizing and interpreting GAM outputs. Attendees are expected to have at least some working experience with Generalized Linear models, and some familiarity with coding in R. 
 
 The workshop will include both lecture and live coding, with data and code provided to attendees to follow along. Please bring a laptop with R and Rstudio (or other IDE) installed, running at least version 4.1 of R. Attendees should also install the `gratia` package prior to the workshop.

 **Code**

  The code and data are available in [this ZIP archive](/2024-symp-ecr-setup/Resources/OTN2024-GAM4movement.zip). You can access them by downloading and extracting the archive, then opening the .Rproj file in RStudio. 