# RFlow - A workflow framework for end-to-end research

## Introduction

The rflow (or Reentrant Flow) project is Python framework for creating
Directed Acyclic Graph (DAG) workflows. Our goal is to aid developers
in developing end-to-end stages of data preprocessing, model fitting
and evaluation with less boilerplate code. Making reproducible
research easier for the 3D Shape Retrieval and Machine Learning
communities.

For more information see the following links:

* [Workflow
  tutorial](https://shrkit.gitlab.io/rflow/tutorial.html)
* [Reference
  documentation](https://shrkit.gitlab.io/rflow)
* [Sample MNIST character
  retrieval](https://gitlab.com/shrkit/shape-retrieval-toolkit/tree/master/experiments/mnist)
* [Multiview Deep Neural Net
  Experiment](https://gitlab.com/shrkit/multiview-dnn)
* [Retrieval using spectral Descriptors
  Experiment](https://gitlab.com/shrkit/spectral-retrieval)

This project is still under development.

## Getting Started

Currently, shrkit is only available on Linux systems and requires
Python 3. The required environment packages (Ubuntu):

```shell
$ sudo apt install git python3-venv python3-pip graphviz
```

For development setup, please refer to the [CONTRIBUTING
guide](CONTRIBUTING.md).

## Similar Projects 

* [Luigi](https://github.com/spotify/luigi) - Spotify's workflow tool.
* [Airflow](https://airflow.apache.org/) - Apache's workflow tool.
* [Weka](http://www.cs.waikato.ac.nz/ml/weka/) - Machine learning workflow and toolkit.
* [Microsoft Asure for Machine Learning](https://studio.azureml.net) -
  A GUI workflow for machine learning pipelines.
