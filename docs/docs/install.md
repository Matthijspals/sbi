# Installation

`sbi` requires Python 3.8 or higher. A GPU is not required, but can lead to
speed-up in some cases. We recommend using a
[`conda`](https://docs.conda.io/en/latest/miniconda.html) virtual environment
([Miniconda installation
instructions](https://docs.conda.io/en/latest/miniconda.html)). If `conda` is
installed on the system, an environment for installing `sbi` can be created as
follows:

```commandline
# Create an environment for sbi (indicate Python 3.8 or higher); activate it
$ conda create -n sbi_env python=3.10 && conda activate sbi_env
```

Independent of whether you are using `conda` or not, `sbi` can be installed
using `pip`:

```commandline
pip install sbi
```

To test the installation, drop into a Python prompt and run

```python
from sbi.examples.minimal import simple
posterior = simple()
print(posterior)
```
