## Steps to Create and Use the Environment:

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
