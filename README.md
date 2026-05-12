# Ex-Alta 3 Harnessing

This is the repository for Ex-Alta 3's harness documentation. This repo uses WireViz to visualize each harness, where harness information is written in a .yml file and then the diagrams are generated using the WireViz tool. Images of these diagrams should already be pre-generated in their respective folders in `./harnesses`, but in order to make changes, re-generate the images, or use another one of WireViz's tools, you will need to install the tool and its dependencies.


## Installation

1. WireViz is a Python tool, so install Python3 if your computer doesn't already have it (must be newer than Python 3.9).
2. You will need to install the GraphViz package for WireViz. This depends on your operating system, so follow the steps in [GraphViz's installation instructions](https://graphviz.org/download/) (I used Homebrew on MacOS).
3. This repository uses Poetry as a package manager. You will need to install Poetry, and it is probably best to follow their [installation instructions](https://python-poetry.org/docs/).
4. Once Poetry is installed, go to the root folder of the repository and run `poetry install`. This will install all the required packages.
5. Activate Poetry's virtual environment. First run `poetry env activate`, and it will return a command to activate the virtual environment (something like `source /Users/.../Library/Caches/pypoetry/.../bin/activate`). Copy and run that command. You should see `(ex3-harnessing-py3.xx)` appear at the start of the line in the terminal.
6. You are now ready to use WireViz! You can run `wireviz -h` to see all the commands. You can also check the [WireViz repo](https://github.com/wireviz/WireViz) for more ideas on what can be done with the tool.
7. When you are done make sure to deactivate the virtual environment by running `deactivate`. 

## Updates

If making any changes to the .yml files, make sure to recompile the images in the harness' folder to be the up to date version. 
- You can run `wireviz ./harnessess/EX3-0XX` from the repo's root directory

After all changes have been made, you will need to submit a merge request to push your changes to the AlbertaSat GitHub. Changes will be merged after they have been reviewed.




