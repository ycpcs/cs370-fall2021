---
layout: default
title: "Lab Setup"
---

For this course, we will be using [CMake](https://cmake.org) to configure our build environment for proper compilation across different platforms. We will add each lab as a subdirectory into a single project to allow all of the labs to be visible in the same IDE window.

## Getting Started

Download [CS370\_Labs.zip](src/CS370_Labs.zip), saving it into the directory where you plan on placing all your labs.

Double-click on **CS370\_Labs.zip** and extract the contents of the archive into a subdirectory called **CS370\_Labs**

Open CLion, select **Open** from the main screen (you may need to close any open projects), and navigate to the **CS370\_Labs** directory. This should open the project and execute the CMake script to configure the toolchain.

Select Visual Studio for Windows or default for Mac OSX which will set the toolchain for all the labs we import into this project.

