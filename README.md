# AI Literature Analysis

Analysis of AI research topic trends over time, with [BERTopic](https://maartengr.github.io/BERTopic/index.html).

## Setup

This project includes a [Devcontainer](https://containers.dev/) for one-click
setup, with e.g. [Github CodeSpaces](https://github.com/features/codespaces).

To run, first add your [Kaggle secrets](https://www.kaggle.com/docs/api#getting-started-installation-&-authentication):

```bash
export KAGGLE_USERNAME=xxxxxxxxxxxxxx
export KAGGLE_KEY=xxxxxxxxxxxxxx
```

Then run Jupyter Lab:

```bash
python -m venv venv
source ./venv/bin/activate
pip install .
jupyter lab
```
