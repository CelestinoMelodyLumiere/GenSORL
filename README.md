# Event Causality Identification via Structure optimization and Reinforcement Learning


## GenSORL

# Requirements

The dependency packages can be installed with the command:

```
pip install -r requirements.txt
```


Datasets
==========

We provide all the datasets and prompts used in our experiments.

+ [[SEMEVAL]](dataset/semeval)

+ [[DialogRE]](dataset/dialogue)

+ [[TACRED-Revisit]](dataset/tacrev)

+ [[Re-TACRED]](dataset/retacred)

+ [[TACRED]](dataset/tacred)


# Usage

1. Prepare data\
Download the desired corpus (ESL, Causal-TB) and put it in folder ```.\datasets```
and run:
```
python datasets/preprocessor/preprocessor.py
```

2. Train model:
```
sh ESL_bash.sh
```
or
```
sh CausalTB_bash.sh
```


# Acknowledgement
Part of our code is borrowed from [code](https://github.com/hieumdt/GenECI), many thanks.
