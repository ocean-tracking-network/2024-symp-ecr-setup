---
title: Setup
---

## Requirements

For the workshops, you will need R and RStudio installed on your computer.

## Installing R

1. Go to https://cran.r-project.org/mirrors.html and select one of the mirrors for the USA.

2. Click on the "Download" link of precompiled binary for the distribution that matches your operating system.
 
3. If you are installing to a Windows computer, click on "Download R for Windows" link. Under subdirectories, click on “base” and then “Download R 4.0.3 for Windows.”

4. If you are installing to a Mac, click "Download R for (Mac) OS X" and on the resulting webpage click the "R-4.0.3.pkg" link to download the installer to your computer.

5. Once R finishes downloading, click on the installer and follow the prompts. Make sure to "install as administrator" if you are on Windows. Otherwise, the default options are fine.

## Installing RStudio

1. Go to https://posit.co/download/rstudio-desktop/, click the Download button under the heading "Install RStudio" (you may have to scroll down). 

2. Click on 'Downloaded Installer' and follow the prompts for installing RStudio. Unless you have specific installation requirements, the default options are fine.

3. Once RStudio has finished installing, click on the program icon. RStudio should open with an active R console.

## Datasets and Code

There are four sets of data and code you will need for the ECR Workshop. Each corresponds to a lesson from a different presenter. 

Where the code is supplied as a ZIP archive, download it from the provided link and extract it to a location of your choice.

Where the code is supplied as a link to a Git repository, you have two options: 

1. If you are familiar with Git and its usage, then you may clone the repository to a location of your choice on your local machine using the `git clone [repository URL]` command. This requires some familiarity with Git, but will allow you to more easily incorporate updates to the code, should the instructor make them.

2. If you are not familiar with Git, then you can download the code as a ZIP archive and extract it to a location of your choice. This will make it slightly more cumbersome to update the code if the presenters make changes to it in the future, but it can be done without installing and setting up Git. 

Both options can be initiated by clicking the bright green `<> Code` button on the linked repository homepage. 

For **Hugo Flavio's ACTEL workshop**, the code and data are available in [this ZIP archive.](/Resources/FLAVIO_2024_OTN_workshop.zip) When you have extracted the archive, the code to run is in the five R files in the main directory, numbered 00 to 04. 

For **Ben Hlina's glatos Detection Efficiency Workshop**, the code and data are available at [this repository.](https://github.com/benjaminhlina/glatos-detection-efficiency/tree/main) When you have downloaded the archive, the code to be run can be found in the `R/glatos_detection_efficiency.R` file. 

Code for **Eric Pedersen's** workshop is still pending arrival. 

For **Jake Brownscombe's Telemetry With Machine Learning Workshop**, the code and data are available at [this repository.](https://github.com/jakebrownscombe/Telemetry_MachineLearning) When you have downloaded the archive, the code to be run can be found in the `worksheets/Telemetry_ML.R` file.





{% include links.md %}
