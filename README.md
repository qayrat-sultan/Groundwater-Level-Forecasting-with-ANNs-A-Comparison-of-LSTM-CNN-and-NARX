# Установка проекта и формирование модели
Работает на Windows, NVIDIA CUDA 11.5 

## Установка нужных библиотек в виртуальной среде
Открываем командную строку с помошью <b>cmd</b>
```
1. mkdir new_folder
2. cd new_folder
3. virtualenv venv
4. venv\Scripts\activate

5. pip install -r req.txt
```
Перезагрузка системы Windows. После перезагрузки повторим 2 и 4 ые пункты в командной строке

### Собираем модель

```
python LSTM_seq2seq.py
```

#### Придется подождать много времени (зависит от вашего железа)


### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).




# Groundwater Level Forecasting with ANNs: A Comparison of LSTM CNN and NARX
doi of this repo:  
[![DOI](https://zenodo.org/badge/290500651.svg)](https://zenodo.org/badge/latestdoi/290500651)   

doi of according publication:
https://doi.org/10.5194/hess-25-1671-202

This repository enables you to reproduce the results and apply the groundwater level forecasting methodology of:     
*Wunsch, A., Liesch, T., Broda, S., Groundwater level forecasting with artificial neural networks: a comparison of long short-term memory (LSTM), convolutional neural networks (CNNs), and non-linear autoregressive networks with exogenous input (NARX)*

Contact: [andreas.wunsch@kit.edu](andreas.wunsch@kit.edu)

ORCIDs of authors:   
A. Wunsch:  [0000-0002-0585-9549](https://orcid.org/0000-0002-0585-9549)   
T. Liesch:  [0000-0001-8648-5333](https://orcid.org/0000-0001-8648-5333)   
S. Broda:  [0000-0001-6858-6368](https://orcid.org/0000-0001-6858-6368)   

For a detailed description please refer to the publication.
Please adapt all absolute loading/saving and software paths within the scripts to make them running, you need Matlab and Python software for  a successful application. We further use the Python Package [BayesianOptimization](https://github.com/fmfn/BayesianOptimization) by [fmfn](https://github.com/fmfn). To run the Python Code please download and install this package.

### Content Overview:
* /CNN - Python Code   
Contains Python scripts of the models and necessary example files.

* /LSTM - Python Code   
Contains Python scripts of the models and necessary example files.

* /NARX - Matlab Code   
Contains Matlab scripts of the models and necessary example files.
