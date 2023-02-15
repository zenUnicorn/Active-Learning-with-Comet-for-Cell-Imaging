# Active-Learning-with-Comet-for-Cell-Imaging
Active Learning with Comet for Cell Imaging

## Comet
Comet works with existing ML libraries and has built-in team collaboration, Comet lets you track code, experiments, and results on ML projects. It’s fast, simple, and free for open source projects.

Installation

`pip`

```python
pip install comet_ml
```

`Conda`

```python
conda install -c anaconda -c conda-forge -c comet_ml comet_ml
```

`Notebook and Google Colab`



```python
# For Comet to start tracking a training run,
# just add these two lines at the top of
# your training script:
import comet_ml

experiment = comet_ml.Experiment(
    api_key="<Your API Key>",
    project_name="<Your Project Name>"
)

# Metrics from this training run will now be
# available in the Comet UI
```

## What is Cell imaging ⛓



Built with ❤ Python
