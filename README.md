# ARAL-Kids: Augmented Reality Android-Based Learning for Kids

## Table of Contents
+ [About](#about)
+ [Built Using](#built_using)
+ [Prerequisites](#prerequisites)
+ [Getting Started](#getting_started)
+ [Installing](#installing)
+ [Usage](#usage)
+ [Contributing](#contributing_guide)


## About <a name = "about"></a>
```ARAL-Kids``` is a marker-based Augmented Reality (AR) Android-based learning application designed to enhance the interactiveness of students, specifically prekindergarten students. This capstone project aims to provide alternative learning tools that foster a dynamic, interactive, and engaging learning environment.

## Built Using <a name = "built_using"></a>
```Unity Editor Version: 2022.3.13f1``` ```VuforiaSDK 10.20```

## Prerequisites <a name = "prerequisites"></a>

+ Download and install [Unity Hub](https://unity.com/download). After installing the Unity Hub, download the ```Unity Editor Version: 2022.3.13f1```.
+ Create an account on [Vuforia Developer Portal](https://developer.vuforia.com/vui/auth/register) and download the latest [Vuforia SDK](https://developer.vuforia.com/downloads/sdk) version.

## Getting Started <a name = "getting_started"></a>
To run this project on your local machine, [Fork or Download this repository](https://github.com/eenlpe1/ARAL-Kids) and open it with ```Unity Editor Version: 2022.3.13.f1```.

## Installing <a name = "installing"></a>
+ To try the prototype of this project, download and install the APK [ARAL-Kids Mobile Application](https://drive.google.com/file/d/1LhXU8r-SrSfWhzUknltH_WbkbsOM6aR9/view?usp=drive_link).
+ Download the [Image Markers](https://docs.google.com/document/d/1EMSi11wak6yni6lPFKq5jrbNdm7JzKUnlOzjTEMUmPU/edit?usp=sharing) at this link.
  
### System Requirements
+ The minimum android version to run the mobile application is ```Android Version 8.0 (Oreo/API Level 26) or later```.
+ Must support ```ARCore``` via ```Vuforia Fusion```.
  - Vuforia Fusion is a set of technologies designed to provide the best possible AR experience on a wide range of devices.
+ At least ```64GB Internal Storage``` and ```4GB of RAM``` or more are required to store and retrieve the data that is needed for the best AR experience, it will be stored in a local storage (mobile phone) for the offline usage of the application so that, students’ can access the application without internet or mobile data connections.

End with an example of getting some data out of the system or using it for a little demo.

## Usage <a name = "usage"></a>
Once you have installed the ```ARAL-Kids Mobile Application``` and downloaded the ```Image Markers```, open the mobile application, and once the app is opened, place the camera next to the image markers to project the 3D models and try to explore it.


## Contributing Guide <a name ="contributing_guide"></a>

### General
- The [Codebase Structure](./CODEBASE_STRUCTURE.md) has detailed information about how the various files in this project are structured.
- Please ensure that any changes you make are in accordance with the [Coding Guidelines](./CODING_GUIDELINES.md) of this repo.
  
### Submitting changes

- Fork the repo
  - [ARAL Kids Repository](https://github.com/eenlpe1/ARAL-Kids)
- Check out a new branch based and name it to what you intend to do:
  - Example:
    ````
    $ git checkout -b BRANCH_NAME
    ````
    If you get an error, you may need to fetch fooBar first by using
    ````
    $ git remote update && git fetch
    ````
  - Use one branch per fix / feature
- Commit your changes
  - Please provide a git message that explains what you've done.
  - Please make sure your commits follow the [Conventions](https://gist.github.com/robertpainsi/b632364184e70900af4ab688decf6f53#file-commit-message-guidelines-md).
  - Commit to the forked repository.
  - Example:
    ````
    $ git commit -am 'Add some fooBar'
    ````
- Push to the branch
  - Example:
    ````
    $ git push origin BRANCH_NAME
    ````
- Make a pull request
  - Make sure you send the PR to the <code>fooBar</code> branch.
  - Travis CI is watching you!

If you follow these instructions, your PR will land pretty safely in the main repo!
