# Southern Arm Control Launch

This project holds the files for launching the various projects in the Southern Arm Control workspace.

## Installation

To install the Southern Arm Control system download sac_setup from https://github.com/greenpro/sac_setup.git and run the setup.sh script for Ubuntu or the rpiSetup.sh script for Raspian.

## Files
CMakeList.txt
* This file holds the project configuration for building.

package.xml
* This file holds the project configuration for building.

## Folders
launch/
* This folder contains the launch files to launch the workspace projects.

## Notes
* This set of launch files should be the only ones called when launching something in the workspace.
* The only pieces of the launch files in this project should be launch includes for files from the other projects.
* Launch files in other projects should only include launch files from the immediate project.
