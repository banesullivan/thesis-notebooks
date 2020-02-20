# Thesis Notebooks

The Jupyter notebooks included in Bane Sullivan's MS thesis.

The data files and Python Jupyter notebooks included here will reproduce the
data figures in my thesis for the FORGE geothermal project and the Mount St. Helens
hydrogeophysical project using PyVista.

To recreate the figures in the notebooks, first install the dependencies using
anaconda after downloading this repository:

```bash
conda env create -f environment.yml

conda activate thesis-environment
```

Then, extract the Mount St. Helens data archive by unzipping `data/MSH.zip`
into the `data/` directory.

Finally, launch Jupyter notebook and open the notebooks:

```bash
jupyter notebook
```


## Contents

- `environment.yml`: The Anaconda Python virtual environment specification file for installing all dependencies needed to run the code included in this appendix.
- `data/FORGE.omf`: Data from the FORGE geothermal research site in the Open Mining Format (OMF) version 1.0 specification.
- `data/MSH.zip`: Data from Kristen Marberry's thesis investigating hydrological conditions near Mount St. Helens.
- `data/salt_body.ply`: An example polygonal mesh of a salt body.
- `Kriging.ipynb`: Reproducible workflow demonstrating the use of external software for geostatistical model building with the PyVista framework.
- `Mt_St_Helens.ipynb`: Reproducible workflow demonstrating the synthesis of various geoscientific datasets under the PyVista framework for visual fusion.
- `Comparison.ipynb`: A comparison of code to visualize the given polygona mesh (`data/salt_body.ply`) using VTK alone and PyVista.
