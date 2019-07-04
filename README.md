# DCO2


This repository contains the Python code used for data processing, statistical
analysis and visualization described in the following paper:

Belteki G, Lin B, Morley CJ.
**Weight-correction of carbon dioxide diffusion
coefficient (DCO$_2$) reduces its inter-individual variability and improves its
correlation with blood carbon dioxide levels in neonates receiving
high-frequency oscillatory ventilation.**
_Pediatr Pulmonology_ 2017 Oct;52(10):1316-1322.
doi:10.1002/ppul.23759. Epub 2017 Jul 6. PubMed PMID: 28682001.

Link to the paper: https://onlinelibrary.wiley.com/doi/abs/10.1002/ppul.23759

Contact: gusztav.belteki@addenbrookes.nhs.uk; gbelteki@aol.com

____


The outputs (numbers, tables, graphs) of the cells of the Jupyter Notebooks
(.ipynb files) have been suppressed in order to comply with copyrights.
Some of the corresponding data and graphs can be found in the paper and its
only supplementary material.

This code can be viewed in any web browser. If the code is displayed (rendered)
 in Github, copy and paste the URL (web adress) of the Notebook into **nbviewer**
(https://nbviewer.jupyter.org) for a read-only display.

To run the code, you need to use Jupyter.
The raw ventilator data are not shared but the user can run this code on his or
her own data obtained in the same format.

____

Packages required to run this Notebook:

Python version: 3.5.3

IPython version: 5.3.0

pandas version: 0.20.1

matplotlib version: 2.0.2

NumPy version: 1.12.1

SciPy version: 0.19.0

I recommend downloading these packages using the freely availably Anaconda
built: https://www.continuum.io/downloads

____

The Notebook also depends on the supplied helper files which should be in the
same directory as the .ipynb notebook files.

gb_loader.py

gb_stats.py

gb_transform.py

gb_visualizer.py
