<h2><img align="center" src="https://github.com/NVIDIA-NIM-Agent-Blueprints/generative-virtual-screening/blob/main/nvidia-logo.png?raw=true">NVIDIA NIM Agent Blueprints: Generative Virtual Screening for Drug Discovery</h2>

[![Open In AI Workbench](https://img.shields.io/badge/Open_In-AI_Workbench-76B900)](https://ngc.nvidia.com/open-ai-workbench/aHR0cHM6Ly9naXRodWIuY29tL05WSURJQS1CaW9OZU1vLWJsdWVwcmludHMvZ2VuZXJhdGl2ZS12aXJ0dWFsLXNjcmVlbmluZw==)

![Generative Virtual Screening for Drug Discovery-r2 (1)](https://github.com/user-attachments/assets/dbb1795a-7e3f-4363-9b20-4bc4d67d04bb)

The NVIDIA BioNeMo Blueprint for generative virtual screening shows how generative AI and accelerated NIM microservices can be used to design optimized small molecules smarter and faster.

<hr>

### Quick Start

```bash
cd deploy
docker compose up
cd ../src
jupyter notebook
```

### Quick Start With NVIDIA AI Workbench

[NVIDIA AI Workbench](https://www.nvidia.com/en-us/deep-learning-ai/solutions/data-science/workbench/) is a development environment manager that enables data scientists and developers to create, customize, collaborate, and migrate AI workloads and applications seamlessly across GPU systems, from laptops to cloud.

If you do not have NVIDIA AI Workbench installed, first complete the installation for AI Workbench [here](https://docs.nvidia.com/ai-workbench/user-guide/latest/installation/overview.html). 

1. Fork this Project to your own GitHub namespace and copy the link

   ```
   https://github.com/[your_namespace]/<project_name>
   ```
   
2. Open the NVIDIA AI Workbench App. Select a location to work in. 
   
3. Clone this Project onto your desired machine by selecting **Clone Project** and providing the GitHub link.
   
4. Wait for the project to build. You can expand the bottom **Building** indicator to view real-time build logs. 
   
5. When the build completes, set the following configurations.

   * `Environment` &rarr; `Secrets`. Specify the ``NGC_CLI_API_KEY`` as a project secret. [Details](https://github.com/NVIDIA-NIM-Agent-Blueprints/generative-virtual-screening/tree/main/deploy#get-your-api-key)

6. Under `Environment` &rarr; `Compose`, select **Start**. This will pull and start the three NIM containers in the blueprint, which can take some time. 

   * You can track progress under the ``Output`` widget. Specify ``Compose`` from the dropdown menu. 

7. On the top right of the AI Workbench window, select **Open Jupyterlab**. It should automatically open in a new browser window.

8. Navigate to ``src/generative-virtual-screening.ipynb`` and get started!

### Get Started

* [Deploy](deploy/)
* [Source code](src/)

### Set Up With Docker Compose

Navigate to the [deploy](deploy/) directory to learn how to start up the NIMs.

## Notebook

An example of how to call each generative virtual screening step is located in `src/generative-virtual-screening.ipynb`.

### Additional Documentation

You can try this Blueprint and find its Blueprint Card on [build.nvidia.com](https://build.nvidia.com/nvidia/generative-virtual-screening-for-drug-discovery)

