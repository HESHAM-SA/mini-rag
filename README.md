# mini-rag

## Requirements

- Python 3.10 or later

#### Install Python using Miniconda

1) Download and install Miniconda from [here](https://docs.anaconda.com/free/miniconda/#quick-command-line-install)

2) Create a new environment using the following command:

```bash
conda create -n mini-rag python=3.10
conda activate mini-rag
```
#### (Optional) Setup you command line interface for better readability
```bash
export PS1="\[\033[01;32m\]\u@\h:\w\n\[\033[00m\]\$ "
```



## Instioalion packges 
```bash
pip install -r requirements.txt
```

## setup system variabls 
```bash
cp .env_example .env
```
example: replace .env_example to .env file and put your openai key



