# Unit_extractor
Extract and produce data sets for both TDT multiunit data or spike-sorted single unit data. This code takes a table organizing your electrophysiological recordings. This is then used to loop through all of the recordings (can be done manually if your file structure does not match the one used here). For FRA analysis, this code will save a dBxkHz matrix for each unit, which can be analyzed using the tuninator repo (LINK HERE). The same can be done for RLF data (no uploaded pipeline for this, yet, but will be added to the tuninator at a later time). 
---
#### Table of Contents

1. [Set up](#setup)
2. [Functions Overview](#main_func)
3. [Output](#output)

---



<a name="setup" />

## Set up

Make sure machine has anaconda installed
To set up, 
download the github files to your computer either by manually clicking the download button or by cloning this repository.
download the needed packages (main dependency lies with pandas being at least version 2.2.1 to use the new map function).

```
conda activate your_env
conda install pandas,matplotlib,seaborn,scipy,numpy
pip install tdt

```
Once you have needed packages proceed with opening the files

```
cd 'your/repo/path'
jupyter notebook 
```
naviagte to .ipynb file, and open.


<a name="main_func" />

## Functions Overview

load_experiments()
load_data()
test_data()
make_fra()

---

<a name="output" />



## Output files
Placeholder text

[^1]: Guo et al. 2012,Robustness of Cortical Topography across Fields, Laminae, Anesthetic States, and Neurophysiological Signal Types [paper link](https://www.jneurosci.org/content/32/27/9159).
