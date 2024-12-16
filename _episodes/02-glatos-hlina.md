---
title: Estimating Detection Efficiency of Acoustic Receivers Using glatos
teaching: 0
exercises: 0
---

This page archives the lesson materials for "Estimating Detection Efficiency of Acoustic Receivers Using `glatos`", given by Ben Hlina at the 2024 OTN Symposium ECR Workshop. 

**Abstract**

Currently there are multiple methods used to estimate detection efficiency of acoustic receivers. Typically, these methods use transmitter drift tests or stationary deployed transmitters/receivers at predetermined distances (e.g., 100, 250 m, ect.) from a representative receiver to estimate short-term detection efficiency. There are, however, limited protocols and knowledge about deploying and understanding detection efficiency of acoustic receivers over longer durations such as a multi-year study. Therefore, we developed a standard operating procedure and a function in the package `glatos` to assist in understanding changes in detection efficiency over the course of a two-year fish movement study. We observed daily and seasonal changes in detection efficiency that might not be incorporated into existing and future acoustic telemetry studies. We recommend users to follow the developed operating procedures to account for changes in the detection efficiency of acoustic receivers over their study period. The goal of this workshop is to: 1) walk users through what detection efficiency is, what variables influence it, and how to deploy and design an effective detection efficiency methodology to incorporate into your study; 2) how to use a new functions in `glatos` and other packages to preliminary estimate detection efficiency; and 3) demonstrate how to estimate daily detection efficiency over the course of study period at a given distance. Attendees will leave the workshop having a better understanding of how acoustic receivers operate, how to use a new function in `glatos`, and how to design and deploy their own detection efficiency study within their overall study.

The estimating detection efficiency of acoustics receivers using `glatos` workshop will entail users learning how acoustic transmitters and receivers work, what influences the ability of an acoustic receiver to hear a detection, and how to design a preliminary and long-term detection efficiency study. Users will be guided through a vignette that has been recently added to the package `glatos` on how to effectively calculate initial detection efficiency at given locations (e.g., 100, 250, 500, and 750 m away from a receiver) over a short time period (e.g., 24 hr). This vignette will also guide users through using a new function in `glatos` that allows the user to estimate the distance that can be expected for a given detection efficiency (e.g., 50%) to occur based on preliminary data. Lastly, users will walk through how to redeploy sentinel transmitters to further estimate detection efficiency over the course of their study and will be shown an example of what they could potentially see for a given study system.

**Code**

The code and data are available at [this repository.](https://github.com/benjaminhlina/glatos-detection-efficiency/tree/main) Instructions for accessing the GitHub repository are on the [setup page](/2024-symp-ecr-setup/setup.html).

**Presentation Slides**
The Powerpoint Presentation (.pptx file) for Ben Hlina's workshop can be downloaded from [this link](/2024-symp-ecr-setup/Resources/detection-effeicency-workshop.pptx).