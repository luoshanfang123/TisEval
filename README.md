## TisEval
we propose the general toxicity
and bias evaluation framework TisEval, the first
comprehensive and systematic evaluation of Chi-
nese LLMs from the perspectives of toxicity and
bias. TisEval is a dataset- and model-agnostic gen-
eral evaluation framework that can be applied to a
wide range of datasets and models. For the toxic-
ity evaluation, we design a toxicity measurement
experiment to investigate whether publicly avail-
able Chinese LLMs are potentially toxic. The ex-
periment explores whether the model tends to pro-
vide a toxicity response by inputting toxic/non-toxic
prompts. 
该仓库包含部分测评的中文大规模语言模型源码，
其他模型，如 EVA，PANGU 和 BELLE 模型源码，可从相关官方仓库这里获取

## Note

BELLE 评估需要将 BELLE 仓库放在工作目录下，具体可查看 `chat.py #21`。
https://github.com/LianjiaTech/BELLE

EVA
https://github.com/thu-coai/EVA

pangu-alpha
https://github.com/huawei-noah/Pretrained-Language-Model
