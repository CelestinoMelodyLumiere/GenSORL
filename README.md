# Event Causality Identification via Structure optimization and Reinforcement Learning


## GenSORL

# Requirements

The dependency packages can be installed with the command:

```
pip install -r requirements.txt
```


Datasets
==========
1. Download the dataset (It is recommended to skip this step and proceed directly to Step[2] and Step[3])  
    [EventStoryLine](https://github.com/tommasoc80/EventStoryLine)  
    [Causal-TimeBank](https://github.com/paramitamirza/Causal-TimeBank)

2. Download the data utilized by the authors of the paper
All data, Please contact with writer;

[//]: # (    [All data&#40;Google Drive&#41;]&#40;https://drive.google.com/drive/folders/1Kqzzyeh4DUbsLoVfVAmzWX16NqKLSd8X?usp=sharing&#41;)
    
3. Extract and overwrite  
    Step[1] - Extract the folder and copy the dataset to the datasets folder.  
    Step[2] - Extract the folder to the project directory, overwriting the existing datasets folder.


# Usage

1. Prepare data\
Extract data from the ESL dataset: In the preprocessor.py file located at ```.\datasets\preprocessor.py```, set ```dataset = 'ESL'```.(Default)\
Extract data from the Causal-TB dataset: In the preprocessor.py file located at ```.\datasets\preprocessor.py```, set ```dataset = 'Causal-TB'```.\
and run:

```
python datasets/preprocessor/preprocessor.py
```


2. Train model:
```
sh ESL_bash.sh
```
or Select training dataset: In the datasets.py file located at ```.\data_modules\datasets.py```, change "ESL" to "Causal-TB" in line 143.
```
sh CausalTB_bash.sh
```


# Acknowledgement

[//]: # (Part of our code is borrowed from [code]&#40;https://github.com/hieumdt/GenECI&#41;, many thanks.)
Part of our code is borrowed from code, many thanks.