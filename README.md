# CVMix in GOTM

Notebooks to rerun the [GOTM](https://gotm.net/portfolio/) simulations and reproduce the figures described in the manuscript ["Integrating CVMix into GOTM (v6.0): A consistent framework for testing, comparing, and applying ocean mixing schemes" published in Geoscientific Model Development (2021)](https://gmd.copernicus.org/articles/14/4261/2021/).
These notebooks make use of the Python tools for GOTM [gotmtool](https://github.com/qingli411/gotmtool), which is included as a submodule.
Use
```
git submodule update --init --recursive
```
to check out the submodule.

Run
```
./gotm_env_init.py
```
in `gotmtool/` and follow the steps to set up the environment for gotmtool.
An active Python environment is required.
