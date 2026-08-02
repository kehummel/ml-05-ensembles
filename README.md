# ml-05-ensembles

[![Workflow Guide](https://img.shields.io/badge/Pro--Guide-pro--analytics--02-green)](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
[![Python 3.14](https://img.shields.io/badge/python-3.14%2B-blue?logo=python)](./pyproject.toml)
[![MIT](https://img.shields.io/badge/license-see%20LICENSE-yellow.svg)](./LICENSE)

> Professional Python project: combining models with ensemble methods.

## Project Description

This project focuses on learning to combine models to get better predictions.

We learn to:

- understand why ensembles outperform single models
- train random forests and gradient boosting models
- read feature importance scores
- tune key hyperparameters

## Example Notebook

Links:

- [ml_05_case.ipynb](notebooks/ml_05_case.ipynb)

## Working Files

You'll work with these areas:

- **data/raw** - raw data for exploration (only if you add a dataset)
- **docs/** - project narrative and documentation
- **src/mlstudio/** - the app is an example; run only (no need to modify)
- **notebooks/** - interactive analysis
- **pyproject.toml** - update authorship & links
- **zensical.toml** - update authorship & links

## Instructions (pro-analytics-02)

Follow the
[step-by-step workflow guide](https://denisecase.github.io/pro-analytics-02/workflow-b-apply-example-project/)
to complete:

1. Phase 1. **Start & Run**
2. Phase 2. **Change Authorship**
3. Phase 3. **Read & Understand**
4. Phase 4. **Modify**
5. Phase 5. **Apply**

### In a machine terminal (open in your `Repos` folder)

After you get a copy of this repo in your own GitHub account,
open a machine terminal in your `Repos` folder:

```shell
# Replace username with YOUR GitHub username.
git clone https://github.com/kehummel/ml-05-ensembles

cd ml-05-ensembles
code .
```

### Work Flow

For best results, follow the detailed instructions in
[pro-analytics-02 guide](https://denisecase.github.io/pro-analytics-02/).


## Findings and Visuals

### Phase 4

In phase 4 I compared single tree to ensembles for data on classification of diabetes. For this data set, the ensembles were less effective and single tree was the better option. Individual's glucose level was the feature of most importance.

Accuracy of Tests
(./docs/p4_ensembles.png)

Features listed in order of importance
(./docs/p4_importance.png)

[Phase 4 Notebook- ml_05_ensembles_hummel.ipynb](notebooks/ml_05_ensembles_hummel.ipynb)

### Phase 5

Update figures to present interesting results from your custom project:

(./docs/images/Figure_1.png)

![Provide](./docs/images/Figure_2.png)


## Project Documentation

Additional project instructions, terms, and notes:

[docs/index.md](docs/index.md)

[docs/index.md](docs/index.md)

## Citation

[CITATION.cff](./CITATION.cff)

## License

[MIT](./LICENSE)
