# WOUDC Jupyter Notebooks

A collection of data centre workflows implemented as
[Jupyter](http://jupyter.org) Notebooks.

# Development

Setting up a local environment:

```bash
virtualenv woudc
cd woudc
. bin/activate  # yes, that is a period
git clone https://github.com/woudc/woudc.git
cd woudc/notebooks
pip install -r requirements.txt
jupyter notebook --ip=0.0.0.0 --port=8000
```
