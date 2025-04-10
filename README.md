# Bibliography Search with Open Deep Research

## 🚀 Quickstart

Ensure you have API keys set for your desired search tools and models.

Available search tools:

* [ArXiv](https://arxiv.org/) - Academic papers in physics, mathematics, computer science, and mor

### Using the package

```bash
pip install open-deep-research
```

Create a `.env` file using the template from `.env.example` to fill out neccessary information.

```bash
# Azure
AZURE_OPENAI_API_KEY=XXX
AZURE_OPENAI_DEPLOYMENT_NAME=XXX
AZURE_OPENAI_ENDPOINT=XXX
MODEL_PROVIDER=azure_openai
OPENAI_API_VERSION=XXX
```

See [src/open_deep_research/graph.ipynb](src/open_deep_research/graph.ipynb) for example usage in a Jupyter notebook
