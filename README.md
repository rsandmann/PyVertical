![om-logo](https://github.com/OpenMined/design-assets/blob/master/logos/OM/horizontal-primary-trans.png)

![Tests](https://github.com/OpenMined/PyVertical/workflows/Tests/badge.svg?branch=master)
![License](https://img.shields.io/github/license/OpenMined/PyVertical)
![OpenCollective](https://img.shields.io/opencollective/all/openmined)

# PyVertical

A project developing Privacy Preserving Vertically Distributed Learning.

- :lock: Links vertically partitioned data
         without exposing membership
         using Private Set Intersection (PSI)
- :eye: Trains a model on vertically partitioned data
        using SplitNNs,
        so only data holders can access data

## Requirements
This project is written in Python.
The work is displayed in jupyter notebooks.

To install the dependencies,
we recommend using Conda:
1. Clone this repository
1. In the command line, navigate to your local copy of the repository
1. Run `conda env create -f environment.yml`
    - This creates an environment `pyvertical-dev`
    - Comes with most dependencies you will need
1. Activate the environment with `conda activate pyvertical-dev`
1. Run `pip install syft[udacity]`
1. Run `conda install notebook`

N.b. Installing the dependencies takes several steps to circumvent versioning incompatibility between
`syft` and `jupyter`.
In the future,
all packages will be moved into the `environment.yml`.

## Contributing
Pull requests are welcome.
For major changes,
please open an issue first to discuss what you would like to change.

Read the OpenMined
[contributing guidelines](https://github.com/OpenMined/.github/blob/master/CONTRIBUTING.md)
and [styleguide](https://github.com/OpenMined/.github/blob/master/STYLEGUIDE.md)
for more information.

## Contributors
|  [![TTitcombe](https://github.com/TTitcombe.png?size=150)][ttitcombe] | [![Pavlos-P](https://github.com/pavlos-p.png?size=150)][pavlos-p]  | [![H4ll](https://github.com/h4ll.png?size=150)][h4ll]
| :--:|:--: |:--:|
|  [TTitcombe] | [Pavlos-p]  | [H4LL]

## Testing
We use [`pytest`][pytest] to test the source code.
To run the tests manually:
1. In the command line, navigate to the root of this repository
1. Run `python -m pytest`

CI also checks the code conforms to [`flake8`][flake8] standards
and [`black`][black] formatting

## License
[Apache License 2.0](https://choosealicense.com/licenses/apache-2.0/)

[black]: https://black.readthedocs.io/en/stable/
[conda]: https://docs.conda.io/en/latest/
[flake8]: https://flake8.pycqa.org/en/latest/index.html#quickstart
[pytest]: https://docs.pytest.org/en/latest/contents.html

[ttitcombe]: https://github.com/ttitcombe
[pavlos-p]: https://github.com/pavlos-p
[h4ll]: https://github.com/h4ll