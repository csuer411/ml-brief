# AI竞赛总结

- [2023IKCEST第五届“一带一路”国际大数据竞赛](https://aistudio.baidu.com/competition/detail/1030/0/introduction) （多模态、分类）rank 未知

​			erine-m-large+resnet101接注意力头，在baseline的基础上换backbone模型，OCR处理的img传入cap。

​			原数据集中中英混合，因此多语种模型更有优势。图片中含有文字信息，因此文字可以提取出来。（后续可以替换vision-encoder为blip、git等img-caption模型，因为手动对齐文字图像很难训练，不如统一）

- [讯飞AI开发者大赛 SD文案生成器](https://challenge.xfyun.cn/topic/info?type=copy-generation&option=phb) （多模态 img2txt) rank 未知

- [面向大语言模型的提示注入攻防竞赛](https://www.datafountain.cn/competitions/668/datasets) （llm 安全）200京东e卡

  ​    在网上查找诸多资料后前几次提交冲上7k分，但提示泄露和目标劫持一直没啥分。由于测试语言模型是黑箱模型，很抽象。拿了周冲刺奖励后放弃。

- [讯飞鸟类品种分类](https://challenge.xfyun.cn/topic/info?type=bird-species&option=phb) （CV）（无奖）

  ​     选取timm目前的几个sota模型，一直在0.96上不去。最后在赛题截止前痛失低保。后来发现榜上有好几个f1score=1的。。。被大佬震惊

