# Build BERT and GPT from 0️⃣
[🇯🇵日本語版](./README_JP.md)


![](https://miro.medium.com/v2/resize:fit:1400/1*TzGwyi1TrqcIPV4WMU3sVg.png)

# Encoder

## [BERT](./Encoder/BERT/)
1. [Overview](./Encoder/BERT/overview.ipynb)
2. [Pre-training](./Encoder/BERT/pre-training.ipynb)
3. [Fine-tuning](./Encoder/BERT/fine-tuning.ipynb)
4. [Visualization-BertViz](https://github.com/jessevig/bertviz) 

## ROBERTA 
BERT vs RoBERTa  
1. RoBERTa use more pre-training data  
2. RoBERTa only trained on MLM tasks, and it uses dynamic masking.

# Decoder

## GPT(`Todo`)
1. [Overview](./Decoder/GPT/overview.ipynb)
2. [Pre-training](./Decoder/GPT/pre-training.ipynb)
3. [Fine-tuning](./Decoder/GPT/fine-tuning.ipynb)

## [Llama](./Decoder/Llama/) (`Todo`)
llama vs GPT   
    1. RoPE  
    2. RMSNorm  
    3. SwiGLU  
    4. Flash Attention  
    5. Pre-normalization  



# Quick Start
```
git clone \\
conda create -n "bert_gpt_test" python = 3.12
conda activate bert_gpt_test
pip install -r requirements.txt
```

### TO-DO
1. Roberta vs BERT
2. Encoder-Decoder: T5, BART
3. GPT, Llama