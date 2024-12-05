# Generation of Python functions using LLM

## Ollama server

You can run Ollama server using docker:
```
docker run -d -v ollama:/root/.ollama -p 11434:11434 --name ollama ollama/ollama
```
or using python libraries ollama-python or ollama-js. I would recommend using ollama docker with the 8b or smaller llms. Especially if you have office computer without GPU with around 16 GB of RAM.

## Steps to Create and Use the Conda Environment:

Create the Environment: Run the following command in your terminal:

```bash

conda env create -f environment.yml
```
Activate the Environment:

```bash

conda activate ollama_function_gen
```
Add the Environment to JupyterLab: Install the environment as a kernel for JupyterLab:

```bash

python -m ipykernel install --user --name ollama_function_gen --display-name "Python (ollama_function_gen)"
```
Launch JupyterLab: Start JupyterLab and select the kernel Python (ollama_function_gen):

```bash
jupyter lab
```
