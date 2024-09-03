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

**If you are not familiar with Git**, then you can download the code as a ZIP archive and extract it to a location of your choice. This will make it slightly more cumbersome to update the code if the presenters make changes to it in the future, but it can be done without installing and setting up Git. 

Click on the bright green `<> Code` button at the top of the linked repository, and select 'Download ZIP' from the dropdown. Once you have the ZIP archive, you can extract it to a location of your choice on your computer and open the R scripts in RStudio. 

**If you are familiar with Git**gi, then you may clone the repository to a location of your choice on your local machine using the `git clone` command. This requires some familiarity with Git, but will allow you to more easily incorporate updates to the code, should the instructor make them.

To clone a repository, you will need to have Git installed. If you want to use Git for this, you will need to install it. Follow the instructions on [this page.](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

Once you have installed Git, you will need to open a command line window. The appropriate program is `Terminal` on Mac OS computers, and `Command Prompt` or `Git Bash` on Windows computers. Navigate to the folder in which you want to put the files from the repository by using the `cd` ('Change Directory') command followed by the name of the folder (for example, `cd /Users/username/Documents/OTN_Symposium/Workshops`). 

Once you are in the folder you want, you can clone the repository into that folder with the `git clone` command. Below, we have provided two `git clone` commands that can be copied and pasted into your terminal window; however, if you wish to use GitHub's other cloning options, you are welcome to do so. 

For **Hugo Flávio's ACTEL Workshop**, run `git clone https://github.com/ocean-tracking-network/2024-ecrworkshop-actel`

For **Ben Hlina's glatos Detection Efficiency Workshop**, run `git clone https://github.com/benjaminhlina/glatos-detection-efficiency.git`.

For **Jake Brownscombe's Telemetry With machine Learning Workshop**, run `git clone https://github.com/jakebrownscombe/Telemetry_MachineLearning.git`.

For the other workshop archives, or for the raw links to the repositories, the appropriate links are provided below.

For **Hugo Flávio's ACTEL workshop**, the code and data are available at [this repository](https://github.com/ocean-tracking-network/2024-ecrworkshop-actel). The code to run is in the five R files in the main directory, numbered 00 to 04. 

For **Ben Hlina's glatos Detection Efficiency Workshop**, the code and data are available at [this repository.](https://github.com/benjaminhlina/glatos-detection-efficiency/tree/main) When you have downloaded the archive, the code to be run can be found in the `R/glatos_detection_efficiency.R` file. 

For **Eric Pedersen's GAMs workshop**, the code and data are available in [this ZIP archive.](/Resources/OTN2024-GAM4movement.zip) When you have extracted the archive, you can open the .Rproj file in RStudio. 

For **Jake Brownscombe's Telemetry With Machine Learning Workshop**, the code and data are available at [this repository.](https://github.com/jakebrownscombe/Telemetry_MachineLearning) When you have downloaded the archive, the code to be run can be found in the `worksheets/Telemetry_ML.R` file.





{% include links.md %}
