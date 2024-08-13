1、Pytorch

从huggingface下载所需的预训练模型，将config.json、pytorch_model.bin、vocab.txt保存在单独的文件夹下，运行pytorch_text_clf.ipynb文件

Roberta中文预训练模型链接：
https://huggingface.co/hfl/chinese-roberta-wwm-ext
https://huggingface.co/hfl/chinese-roberta-wwm-ext-large
https://github.com/brightmart/roberta_zh

2、Paddlenlp

修改相应的模型名称，运行paddlenlp_text_clf.ipynb文件
目前代码是二分类的，多分类需要进行相应的修改
