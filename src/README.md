### NVIDIA BioNeMo Blueprint for Generative Virtual Screening in Drug Discovery

This directory contains a Jupyter notebook showing a complete example. Check out the
[notebook](./generative-virtual-screening.ipynb) itself for more explanation of
how the generative virtual screening pipeline works.

Assuming you have already deployed the NIMs using the provided docker compose yaml 
found in [deploy](../deploy), you should be able to start up a Jupyter notebook 
instance and get going immediately!

```bash
jupyter notebook
```

#### NVIDIA AI Workbench

For developers using [NVIDIA AI Workbench](https://www.nvidia.com/en-us/deep-learning-ai/solutions/data-science/workbench/) to run this blueprint, 

1. Deploy the NIMs by selecting **Start** under ``Environment`` > ``Compose``.
2. Select **Open Jupyterlab** on the top right and get started with the [notebook](./generative-virtual-screening.ipynb).

Full quickstart instructions can be found [here](https://github.com/NVIDIA-AI-Blueprints/generative-virtual-screening/blob/main/README.md#quick-start-with-nvidia-ai-workbench). 
