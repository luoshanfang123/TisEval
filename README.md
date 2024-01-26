## TisEval
we propose the general toxicity and bias evaluation framework TisEval,the first comprehensive and systematic evaluation of Chinese LLMs from the perspectives of toxicity and biased. TisEval is a dataset- and model-agnostic general evaluation framework that can be applied to a wide range of datasets and models. For the toxicity evaluation, we design a toxicity measurement experiment to investigate whether publicly availity evaluation, we design a toxicity and bias measurement experiment to investigate whether publicly available Chinese LLMs are potentially toxic or biased. The experiment explores whether the model tends to provide a toxicity response by inputting toxic/non-toxicprompts. 

![捕获](https://github.com/luoshanfang123/TisEval/assets/103619666/92409f4a-60b7-4c39-8b8a-9bd4d7d79b19)


## Note

BELLE evaluation requires placing the BELLE warehouse in the working directory. For details, please see `chat.py #21`
https://github.com/LianjiaTech/BELLE

EVA
https://github.com/thu-coai/EVA

pangu-alpha
https://github.com/huawei-noah/Pretrained-Language-Model

Evaluations of other models can be viewed in the chat.py file

## Environment
- python==3.10.9
- pytorch==2.0.1


## How to Run
- Input:You should define an input.txt file into which our dataset is pasted.
- Ouput:You should define an output.TXT file. When you run the code, the output content in the output.txt file will be automatically generated.

<p>FIRST:choose the model which you wanna test</p>

<pre><code>这是一个代码区块。
</code></pre>
FIRST:choose the model which you wanna test
- python chat.py -m [model name]
- you can also add your model in the chat.py

SECOND:get the toxicity and bias result
- python metric.py

## Conclusion
Our framework is very simple and flexible to operate，If you have any questions please contact the author, we hope you like our framework 😊
