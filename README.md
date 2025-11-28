# quantile-delta-mapping
This repository contains the code related to a quantile delta mapping approach to filling in Line-P data.

# One-time setup
- Line P CTD
- NEP36

To download:
```
cd /path/to/data/directory # Ex: ~/data/
wget https://hpfx.collab.science.gc.ca/dfo/SD-Ocean/Training/observations/ctd/lineP_CTD_training.csv
wget https://hpfx.collab.science.gc.ca/dfo/SD-Ocean/Training/models/NEP36-CanOE/NEP36_along_LineP.nc

```

Assuming you have a new python environment (via venv, conda, or pyenv), install the required packages
```
pip install -r requirements.txt
```

# To Run
Start up a jupyter server
```
jupyter lab
```
and your browser should pop up. Open the notebook and update the variables `ctd_path` and `nep36_path`