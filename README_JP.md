# BERTとGPTを0️⃣から構築する
[🇬🇧English Version](./README.md)

![](https://miro.medium.com/v2/resize:fit:1400/1*TzGwyi1TrqcIPV4WMU3sVg.png)

# エンコーダー

## [BERT](./Encoder/BERT/)
1. [概要](./Encoder/BERT/overview.ipynb)
2. [事前学習](./Encoder/BERT/pre-training.ipynb)
3. [ファインチューニング](./Encoder/BERT/fine-tuning.ipynb)
4. [可視化-BertViz](https://github.com/jessevig/bertviz)

## ROBERTA
BERT vs RoBERTa
1. RoBERTaはより多くの事前学習データを使用
2. RoBERTaはMLMタスクのみで学習され、動的マスキングを使用

# デコーダー

## GPT(`TODO`)
1. [概要](./Decoder/GPT/overview.ipynb)
2. [事前学習](./Decoder/GPT/pre-training.ipynb)
3. [ファインチューニング](./Decoder/GPT/fine-tuning.ipynb)

## [Llama](./Decoder/Llama/) (`TODO`)
Llama vs GPT
    1. RoPE
    2. RMSNorm
    3. SwiGLU
    4. Flash Attention
    5. 事前正規化

# クイックスタート
```
git clone \\
conda create -n "bert_gpt_test" python = 3.12
conda activate bert_gpt_test
pip install -r requirements.txt
```

### 今後の予定
1. Roberta vs BERT
2. エンコーダー-デコーダー: T5, BART
3. GPT, Llama