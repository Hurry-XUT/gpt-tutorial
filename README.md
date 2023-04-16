# GPT Tutorial

* [Lecutre 1: ChatGPT账号注册](./lecture01.md)
* [Lecture 2: 基本概念和常用工具](./lecture02.md)
* [Lecture 3: 收费说明](./lecture03.md)
* [Lecture 4: ChatGPT API帮助手册](./lecture04.md)
* [FAQ: 常见问题](./chatgpt_faq.md)



# 文心一言

* [Lecture1: 文心一言网站使用和API使用申请](./baidu/lecture01.md)



## 开源模型

| Model      | 作者                                        | 参数量                                          | 训练数据量 | 训练成本                                                     | 推理成本                                                     |
| :--------- | ------------------------------------------- | ----------------------------------------------- | ---------- | ------------------------------------------------------------ | ------------------------------------------------------------ |
| LLaMA      | Meta                                        | 包括 70 亿、130 亿、330 亿、650 亿 4 种参数规模 |            |                                                              |                                                              |
| Alpaca     | Stanford                                    | 70亿                                            |            |                                                              |                                                              |
| Vicuna     | UC Berkeley, CMU, Stanford, UCSD and MBZUAI | 130亿                                           |            |                                                              |                                                              |
| Koala      | UC Berkeley                                 | 130亿                                           |            | 一台 Nvidia DGX 服务器与8个A100 GPU，需要6个小时训练完成2个epochs。在公共云计算平台上，预期训练成本不超过100美元。 |                                                              |
| Dolly 2.0  | Databricks                                  | 120亿                                           |            |                                                              |                                                              |
| ChatGLM    | 清华大学KEG 实验室和智谱AI                  | 1300亿                                          |            |                                                              | 支持在一台 **A100（40G \* 8）** 或 **V100（32G \* 8）服务器**上对千亿规模参数的模型进行推理 |
| 鹏程·盘古α | 鹏程实验室、华为、北大                      | 2000亿                                          |            |                                                              |                                                              |

Alpaca, Vicuna, Koala都是基于LLaMA衍生而来的，LLaMA目前仅用于学术、社会公益项目，不能用于商业化项目。

* [开源模型汇总](./open-source.md)
