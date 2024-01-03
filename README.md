## Set up Anaconda and virtual environment

After downloading and installing Anaconda into Windows properly, run the following command in CMD to create new environment

```sh
conda create -n llm-chatbot python=3.8
```

Check the environment in the list

```sh
conda env list
```

Activate the virtual environment with conda as follow

```sh
conda activate llm-chatbot
```

## Install and run Jupyterlab

After activate the virtual envrionment, we install the jupyterlab to run some notebook

```sh
pip install jupyterlab
```
Then, we run to enter the jupyter notebook

```sh
jupyter notebook
```
