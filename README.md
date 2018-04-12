## **Intro to Spatial Analysis and Maps with Python** for Maptime Seattle April 2018

*[Slides](https://docs.google.com/presentation/d/1bgnhRya1uaoB33nuqS2wNn6fboWoDjUWG5noWifhnKQ/edit?usp=sharing)

### Data Sources

* [Eclipse Data Source](http://xjubier.free.fr/en/site_pages/SolarEclipsesGoogleEarth.html)
* [City Data Source](http://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-populated-places/)
* Other sources are noted in the Jupyter Notebooks in this project

### Getting Started

* If you are familiar with [GitHub](http://www.github.com), fork (if you wish) and clone [the repository](https://github.com/christyheaton/Maptime_20180411). If not, download the repository and unzip to a working directory. Take note of where you put it!

* Install [Miniconda](https://conda.io/miniconda.html) for your operating system. Please choose the latest Python 3.x version. The [installation instructions](https://conda.io/docs/user-guide/install/index.html#regular-installation) might be helpful.

* You should now have access to an Anaconda command prompt, open it like you would any program. Note that you should see `(base)` somewhere in your prompt. This means you're in the base Conda environment, which we will now change. 

Navigate to the directory containing environment.yml (included in the repo).

```bash
cd [location where you saved the repo]/Maptime_20180411
```

* Create the Conda environent you will need to run the tutorial. Note: it is called `geopandasenv`. **This could take anywhere from 10-30 minutes to finish.**

```bash
conda env create environment.yml
```

* Now you can activate the environment.

```bash
source activate geopandasenv  # OSX and Linux
activate geopandasenv  # Windows.
```

* To open the Jupyter Notebooks included in this tutorial, in your Anaconda Prompt navigated to the Notebook directory, type in:

```bash
jupyter notebook
```

* If you ever want to deactivate the geopandasenv environment, type in the following:

```bash
source deactivate  # OSX and Linux
deactivate  # Windows.
```