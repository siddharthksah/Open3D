# Open3D 3D Point Cloud Manipulations


Below are instructions to implement in in your local system using a separate development environment using the [Conda](http://conda.pydata.org/docs/index.html) package management system which comes bundled with the Anaconda Python distribution provided by Continuum Analytics.

### Step 1:
[Fork and clone](https://github.com/siddharthksah/https://github.com/siddharthksah/Open3D) a copy of this repository on to your local machine.

### Step 2:
Create a `conda` environment called `open3d` and install all the necessary dependencies, the environment.yml file is uploaded in the repo for ease:

    $ conda env create --file environment.yml
    

### Step 3:
Activate the `open3d` environment:

    $ source activate open3d

To confirm that everything has installed correctly, type

    $ which pip

at the terminal prompt. You should see something like the following:

    $ ~/anaconda/envs/open3d/bin/pip

which indicates that you are using the version of `pip` that is installed inside the `pose-estimation` Conda environment and not the system-wide version of `pip` that you would normally use to install Python packages.

### Step 4:
Change into your local copy of the this repo:

    $ cd open3d

### Step 6:
Run the notebook:
conda install nb_conda -y
jupyter notebook

