# Amazon SageMaker + HuggingFace 🤗
A couple of notebooks on Amazon SageMaker pulling data from HuggingFace and deploying it

## Notebook description
1. basic-hf shows how to deploy a simple bert-uncased model to a GPU instance. Switch it out for whatever instance we want
2. xlm-roberta-base - as the name suggests shows how to deploy XLM-RoBERTa-Base model to a CPU instance using a Deep Learning Container
3. vector-embedding-pretrained - shows how to pull pre-trained model artifacts and deploying it using a DL container along with a custom inference script
4. inf1 shows how to deploy the same bert-uncased model to Inf1 instance type and measure latency

## Challenge
Pull the [XLM-R](https://github.com/facebookresearch/XLM) pre-trained model and deploy it using SageMaker's `PyTorchModel` class. Create your own inference script and package it and send it to Amazon S3 and deploy using SageMaker

## Bonus Challege (for Amazon Custom Silicon)
neuron_torch trace the model and deploy it on inf2
