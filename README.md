# REPAIR Model

The Risk-controlled Expansion Planning with Distributed Resources (REPAIR) is an innovative tool to support decisions around utility grid planning to prevent and mitigate the impact of outages caused by routine equipment failures (reliability) or by extreme events (resilience), such as storms, earthquakes or wildfires that long term interruption of service.

REPAIR is a risk-based optimization and decision-making model allowing informed and transparent “cost vs risk” decisions regarding infrastructural planning of electric utilities. The model considers long-term resilience and reliability planning strategies that rely on traditional infrastructure upgrade (e.g. circuit hardening, reinforcement, new substations, etc.) or new investment alternatives, such as DERs.

### Prerequisites

For using this package, you need to use Python 3.8+, along with the libraries
specified in requirements.txt.

To run the problem, a MILP solver needs to be installed. We recommend CBC, which is
free to use.


### Installing


For using this module, there are some python libraries that need to be installed. This can be done by cloning the project and running on the main folder:
```
pip install pipenv
pipenv shell
pipenv install
```

otherwise, by using the requirements file:

```
pip install -r requirements.txt
```


CBC can be installed for all platforms. For installation instructions, check the [github repository](https://github.com/coin-or/Cbc). The solver can be modified by modifying line 31 in run.py.


## Running

You can run the model by executing the following command in the main folder:

```
python run.py
```

which will output files in solutions folder.

## Modifying Dataset

In order to modify the data, there is a detailed set of files that can be modified, which are present in the example_case folder. By modifying this values, or by using a different folder entirely, the inputs from this model can be changed.


### Research

The mathematical models to support repair can be found in open access journal publications.

Publications:
- [Paper with final methodology and demonstration](https://ieeexplore.ieee.org/document/10115468)
- [Previous publication](https://www.mdpi.com/1996-1073/14/24/8482)

## Authors
Project Team

* **Miguel Heleno** - *Project PI* - [Miguel Heleno](miguelheleno@lbl.gov)
* **Alexandre Moreira** - *Project team* - [Alexandre Moreira](amoreira@lbl.gov)
* **Alan Valenzuela** - *Project team* - [Alan Valenzuela](alanvalenzuela@lbl.gov)
* **Joe Eto** - *Project team* - [Joe Eto](jheto@lbl.gov)



## Copyright Notice

Risk-controlled Expansion Planning with Distributed Resources (REPAIR) Copyright (c) 2025, The Regents of the University of California, through Lawrence Berkeley National Laboratory (subject to receipt of  any required approvals from the U.S. Dept. of Energy). All rights reserved.

If you have questions about your rights to use or distribute this software, please contact Berkeley Lab's Intellectual Property Office at IPO@lbl.gov.

NOTICE.  This Software was developed under funding from the U.S. Department of Energy and the U.S. Government consequently retains certain rights.  As such, the U.S. Government has been granted for itself and others acting on its behalf a paid-up, nonexclusive, irrevocable, worldwide license in the Software to reproduce, distribute copies to the public, prepare derivative  works, and perform publicly and display publicly, and to permit others to do so.


## Sponsors

The REPAIR model was sponsored by the US Department of Energy (DOE) through the Microgrids R&D and the Advanced Grid Modeling Programs from the Office of Electricity.

![alt text](others/usenergy.jpeg)