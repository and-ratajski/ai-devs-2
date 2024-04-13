# Coding asignments for AI Devs 2 course

## Set up conda environment

https://stackoverflow.com/a/58068850/16775898

### Create conda environment

```shell
conda create --prefix ./ai-devs-2 numpy matplotlib pandas ipykernel openai requests python-dotenv
```

### Change environment prompt

```shell
conda config --set env_prompt '({name})'
```

### Activate conda environment

```shell
conda activate ./ai-devs-2
```

### Launch notebook from base environment

```shell
conda decativate
conda activate base
conda install nb_conda_kernels
jupyter notebook
```

### Jupiter autocompletion

```shell
pip install jupyter-tabnine
jupyter nbextension install --py jupyter_tabnine
jupyter nbextension enable --py jupyter_tabnine
jupyter serverextension enable --py jupyter_tabnine
```