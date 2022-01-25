# MSTICPy - CyberSecurity with Jupyter Notebooks

## PyCascades 2022

Ian Hellen


This repo contains the Jupyter notebook and PowerPoint presentation
used in the talk (Sat 5th Feb 2022).

A lot of the examples in the notebook (most of those shown in the presentation)
will run standalone.

# Slides

![Slides](PyCascades-2022-Slides.gif)

The slides are available as:
- [Accessible Powerpoint](PyCascades-2022.pptx)
- [PDF](./PyCascades-2022-Slides.pdf)
- [GIF](PyCascades-2022-Slides.gif)

# Notebook

[Notebook](MSTICPy-pycascades2022.ipynb)

## Running the notebook in MyBinder
[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/ianhelle/pycascades2022/HEAD?labpath=MSTICPy-pycascades2022.ipynb)

## Running locally
### Installing MSTICPy

The ones that use MSTICPy require installing MSTICPy in your Python
environment. Minimum Python version is 3.6, we recommend
Python 3.8 or later.

```bash
pip install msticpy
```
[Installing MSTICPy](https://msticpy.readthedocs.io/getting_started/Installing.html)

### MSTICPy Configuration

Some of the examples also require configuration settings.
A sample `msticpyconfig.yaml` is available in this repo.

The GeoIP lookup examples need a Maxmind GeoLite account (this is free).
You must get the API key from your account settings and add it to the
MSTICPy settings. The second code cell in the notebook let's you
configure MSTICPy settings - choose the GeoIP Providers tab and
add `GeoIPLite`.
After entering the settings click, **Update** and then
**Save Settings**

The examples using Threat Intelligence sources need one or more
threat intelligence providers, e.g. Virus Total and AlienVault OTX.
Create accounts at one or more of these and obtain API keys from
your account settings.

In the MSTICPy settings, go to the TIProviders tab, add the
appropriate provider and fill in the settings.

After entering the settings click, **Update** and then
**Save Settings**

[Configuring MSTICPy](https://msticpy.readthedocs.io/getting_started/SettingsEditor.html)

# Other useful references

[MSTICPy Github](https://github.com/microsoft/msticpy)

[MSTICPy DataProviders](https://msticpy.readthedocs.io/data_acquisition/DataProviders.html)

[MSTICPy Pivot Functions](https://msticpy.readthedocs.io/data_analysis/PivotFunctions.html)

[MSTICPy Visualizations](https://msticpy.readthedocs.io/Visualization.html)


[MSTICPy Sample notebooks](https://github.com/microsoft/msticpy/docs/notebooks)