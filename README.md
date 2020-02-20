# Thesis Notebooks

The Jupyter notebooks included in Bane Sullivan's MS thesis.

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
