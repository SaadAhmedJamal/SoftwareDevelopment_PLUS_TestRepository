# Dealing with Python Environment

### Created a Python environment
Created the environment ```` myenvThree ```` myenvThree using Anaconda Graphical User Interface.
Installed python library plotly in the newly created environment.

### Exported the file using Command Line Interface (CLI)
Following commands in Anaconda CLI were used to create the requirements file and exporting the python environment. 
For requirements file in txt format:
``` conda env export > myThree.txt ```
For exporting the python environment yml file:
``` conda env export > myThree.yml into yml file ```

The commands were taken from the [Link](https://stackoverflow.com/questions/48278769/export-import-conda-environment-and-package-including-local-files) 

![image](https://user-images.githubusercontent.com/28218597/165750197-3cefbae2-66c9-4161-81fd-f17e80cfbc87.png)


### Commitited a conda environment
Using GitHUB Online Interface, myenvThree was commited.
Forked the repo as done before in the course 
Under the repositories tab forked repo's can be seen.

## Recreated the environment

``` conda env create -f softdevenv.yml ```
The environment can be forked from the repository [pochsarah/PLUS_softwaredev_2022](https://github.com/pochsarah/PLUS_softwaredev_2022)
The repository was cloned onto hard drive and the Python environment ```` softdevenv ```` was recreated through following steps in CLI. 


![image](https://user-images.githubusercontent.com/28218597/165758386-17676782-aac1-4d8f-8a6a-ff7b58207888.png)

_ Modify the environment (i.e. installed plotly as it was not included already!)

![image](https://user-images.githubusercontent.com/28218597/165759785-2d35b90c-39b4-4968-a1c1-60ace7563a72.png)




### Update the requirements file (i.e. export the modified environment)
using the export command exported the requirements file @requirements_softdevenv_updated file.

### Add, commit and push the new requirements file
Used GITHUB online

### Create a pull request (and accept, reject or comment on the request from someone else!)
Created a pull request to the repositories [@PullRequest](https://github.com/pochsarah/PLUS_softwaredev_2022)

## Diffuculties:
The problem arised in recreating the environment due to dependencies.
In the python environment file, seperate out the dependencies that are highlighted in command line prompt 
and use ``` pip: ``` before it. This lets the compiler know that these dependecies can be installed later.

