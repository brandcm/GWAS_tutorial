# GWAS Tutorial
This repository contains files associated with a tutorial on genome-wide association study or GWAS data and analysis using [beat synchronization](https://www.nature.com/articles/s41562-022-01359-x) as an example.

All but one of the necessary files are currently present in the repository. To retrieve the PED file, navigate to the cloned repo and run the following command:
```
wget https://ucsf.box.com/shared/static/79b3r82waw35j7fgtqwufqhbqbrm4jxj.gz
```

To run the tutorial, create a Conda environment using the provided YML file, activate the environment, and launch Jupyter Lab:

```
conda env create -f environment.yml
conda activate GWAS_tutorial  # OR conda activate {new_environment_name}
jupyter lab
```

Questions or feedback? Please email colin.brand@ucsf.edu.
