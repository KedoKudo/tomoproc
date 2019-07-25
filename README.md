# tomoproc

This repository, __tomoproc__ provides necessary toolkits for the pre&amp;post processing of tomography data collected at

* 1-ID@APS
* 6-BM-A@APS
* 6-ID-D@APS

## Quick start

```bash
>> tomorpocer --help
Usage:
    tomoprocer.py morph    <CONFIGFILE>
    tomoprocer.py prep     <CONFIGFILE>
    tomoprocer.py recon    <CONFIGFILE>
    tomoprocer.py analyze  <CONFIGFILE>
    tomoprocer.py -h | --help
    tomoprocer.py --version

Options:
  -h --help     Show this screen.
  --version     Show version.
```

## Required 3rd-party libraries

* __tomopy__: conda install -c conda-forge tomopy
* __docopt__: pip install docopt
* __vtk__: pip install vtk


## Docker

Container building recipe for using tomoproc.

## Dev Note
07-25-2019: It appears that __tomopy__ has to be installed before anything else to ensure dependencies within the package is resolved.
