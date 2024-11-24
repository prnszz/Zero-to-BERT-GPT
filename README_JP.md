# [BERT](./Decoder/BERT-jp/)  
$$自然言語 → エンコーダ → 二進数のコード  $$ 
$$自然言語 → BERT → 高次元ベクトル$$
1. [概要](./Encoder/BERT/overview.ipynb)
2. [事前学習](./Encoder/BERT/pre-training.ipynb)
3. [ファインチューニング](./Encoder/BERT/fine-tuning.ipynb)
4. [可視化-BertViz](https://github.com/jessevig/bertviz)

# [Llama](./Decoder/Llama-jp/)
$$二進数のコード → デコーダ → 自然言語 $$ 
$$高次元ベクトル(Embedされたprompt) → GPT → 自然言語$$
1. [概要](./Decoder/Llama-jp/overview.ipynb)
2. [事前学習](./Decoder/Llama-jp/pre-training.ipynb)
3. [ファインチューニング](./Decoder/Llama-jp/fine-tuning.ipynb)

![](https://miro.medium.com/v2/resize:fit:1400/1*TzGwyi1TrqcIPV4WMU3sVg.png)

# Quick Start
```
git clone \\
conda create -n "bert_gpt_test" python = 3.12
conda activate bert_gpt_test
pip install -r requirements.txt
```