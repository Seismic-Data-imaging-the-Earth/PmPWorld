# The Moho-reflected PmP Wave
<p align="center">
  <img src="https://github.com/Seismic-Data-imaging-the-Earth/PmPWorld/blob/master/source/photos/PmPShow.png" />
</p>

---

[![PyPI - License](https://img.shields.io/pypi/l/seisbench)](https://github.com/seisbench/seisbench/blob/main/LICENSE)
[![GitHub Workflow Status](https://img.shields.io/github/workflow/status/seisbench/seisbench/main_push_action)](https://github.com/seisbench/seisbench)
[![Read the Docs](https://img.shields.io/readthedocs/seisbench)](https://seisbench.readthedocs.io/en/latest/)
[![PyPI](https://img.shields.io/pypi/v/seisbench)](https://pypi.org/project/seisbench/)
[![Python 3.7](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-360/)
[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.5568813.svg)](https://doi.org/10.5281/zenodo.5568813)

The Seismology Benchmark collection (*SeisBench*) is an open-source python toolbox for 
machine learning in seismology.
It provides a unified API for accessing seismic datasets and both training and applying machine learning algorithms to seismic data.
SeisBench has been built to reduce the overhead when applying or developing machine learning techniques for seismological tasks.

## Getting started

SeisBench offers three core modules, `data`, `models`, and `generate`.
`data` provides access to benchmark datasets and offers functionality for loading datasets.
`models` offers a collection of machine learning models for seismology.
You can easily create models, load pretrained models or train models on any dataset.
`generate` contains tools for building data generation pipelines.
They bridge the gap between `data` and `models`.

The easiest way of getting started is through our colab notebooks.

| Examples |  |
|---|---|
| Dataset basics | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/main/examples/01a_dataset_basics.ipynb) |
| Model API | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/main/examples/01b_model_api.ipynb) |
| Generator Pipelines | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/main/examples/01c_generator_pipelines.ipynb) |
| Applied picking | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/main/examples/02a_deploy_model_on_streams_example.ipynb) |
| Using DeepDenoiser | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/main/examples/02b_deep_denoiser.ipynb) |
| Training PhaseNet (advanced) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/main/examples/03a_training_phasenet.ipynb) |
| Creating a dataset (advanced) | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/seisbench/seisbench/blob/additional_example_workflows/examples/03b_creating_a_dataset.ipynb) |

Alternatively, you can clone the repository and run the same [examples](https://github.com/seisbench/seisbench/tree/main/examples) locally.

For more detailed information on Seisbench check out the [SeisBench documentation](https://seisbench.readthedocs.io/).

---

## References

* [Li et al. 2022. Moho Complexity in Southern California Revealed by Local PmP and Teleseismic Ps Waves](https://agupubs.onlinelibrary.wiley.com/doi/abs/10.1029/2021JB023033)

* [Ding et al. 2022. Deep Neural Networks for Creating Reliable PmP Database with a Case Study in Southern California](https://doi.org/10.48550/arXiv.2112.07655)


