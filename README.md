# Scaffold for Python Project 
Demo for creating scaffold for python project

## Create Repo and Copy to Cloud Environment
* Create Github Repo [scaffold-python](https://github.com/nichtea01/scaffold-python)
* Open Azure [Cloud Shell](https://portal.azure.com/#allservices/category/All)
* Create ssh-keys in Azure Cloud Shell: ssh-keygen -t rsa
* From Cloud Provider create SSH file .ssh/id_rsa.pub using command: ssh-keygen -t rsa
* Upload SSH key to Github, see doc [Managing Deploy Keys](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/managing-deploy-keys#deploy-keys)

## Clone Repo to Cloud Environment
* git clone [git@github.com:nichtea01/scaffold-python.git](git@github.com:nichtea01/scaffold-python.git) 
* add files below for python scaffold
  - [x] Makefile
  - [x] requirements.txt
  - [x] hello.py
  - [x] test_hello.py

## Setup Pyton Virtual Environment
* check python version: python3 -V 
* setup virtual environment: python3 -m venv ~/.scaffold-python
* activate virutal environment: source ~/.scaffold-python/bin/activate

## Run Tests
* make install
* make lint
* make test
