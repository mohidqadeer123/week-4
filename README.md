# Week 4

This week's lab is meant to introduce you to some useful methods and processes for cleaning data. In particular, we will cover the following:

- merging datasets
- the data frame index
- accessor functions
- applying functions
- map, reduce, and filter
- melt and pivot

This week we will also introduce Python modules and files.

## Setup

1. [Fork](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/working-with-forks/fork-a-repo#forking-a-repository) this repository.
2. [Create a Codespace](https://docs.github.com/en/codespaces/developing-in-a-codespace/creating-a-codespace-for-a-repository#creating-a-codespace-for-a-repository) for your repository. Use this to view the lab notebook.
3. This week' exercise will require you to create a separate GitHub repository. Your submission for this week will be *that* repository, not this one. See the *exercises.ipynb* notebook for more details.

## Packages Available:

The environment for this week is built with the following environment.yml:

```yml
name: week-4
dependencies:
  - python=3.11
  - pip
  - pip:
    - ipykernel  # for Jupyter Notebook
    - streamlit
    - seaborn
    - pandas
    - numpy
```

*Note: you are welcome to install more packages in your codespace, but they will not be used by the autograder.*