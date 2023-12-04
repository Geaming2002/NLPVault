<h1 align="center">NLPVault</h1>

<div align="center">
    Contributed by 
    <a href="https://github.com/Geaming-CHN">Geaming</a>
</div>


## Table of Contents
<!-- TOC -->

- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Papers](#papers)
    - [Model](#model)
    - [CoT](#cot)
    - [Retrieval Enhanced LLM](#retrieval-enhanced-llm)
    - [Text Generation](#text-generation)
    - [Agents](#agents)
    - [Benchmark](#benchmark)
    - [Others](#others)
- [Models](#models)
- [Datasets](#datasets)
- [Tools & Libraries](#tools--libraries)
- [Tutorials & Guides](#tutorials--guides)
- [Resources](#resources)
- [Projects](#projects)

<!-- /TOC -->


## Introduction

参考了[[Awesome-Story-Generation](https://github.com/yingpengma/Awesome-Story-Generation)]所搭建的自己的NLP资料仓库。主要聚焦于NLP的LLM及其在各个领域中的应用。因为是由我自己整理的资料，可能存在错误，欢迎大家随意提PR或者issue。

与我联系：`jm.li4@siat.ac.cn`

## Papers

***NLP各个领域论文链接link，在每个领域中按照主题，年份进行排序，√是我用来记录是否阅读的符号，无特殊意义，~表示泛读***😎

Eg. √`ACL-2023` **Title** [paper] [code] .. [authors]

### Model

- ~`ArXiv-2023` **Advancing Transformer Architecture in Long-Context Large Language Models: A Comprehensive Survey** [[paper](https://arxiv.org/abs/2311.12351)][[code](https://github.com/Strivin0311/long-llms-learning)][Y Huang, J Xu, Z Jiang, J Lai…]

- ~`ArXiv-2023` **A survey on long text modeling with transformers** [[paper](https://arxiv.org/abs/2302.14502)][Z Dong, T Tang, L Li, WX Zhao]

### CoT

- `ACL-2023 findings` **Towards reasoning in large language models: A survey** [[paper](https://arxiv.org/abs/2212.10403)][[code](https://github.com/jeffhj/LM-reasoning)][J Huang, KCC Chang]

- √`ACL-2023` **Interleaving retrieval with chain-of-thought reasoning for knowledge-intensive multi-step questions** [[paper](https://arxiv.org/abs/2212.10509)][[code](https://github.com/stonybrooknlp/ircot)][H Trivedi, N Balasubramanian, T Khot…]

- √`ICLR-2023` **Automatic chain of thought prompting in large language models** [[paper](https://arxiv.org/abs/2210.03493)][[code](https://github.com/amazon-science/auto-cot)][Z Zhang, A Zhang, M Li, A Smola]

- √`NeurIPS-2022` **Chain-of-thought prompting elicits reasoning in large language models** [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/9d5609613524ecf4f15af0f7b31abca4-Abstract-Conference.html)][J Wei, X Wang, D Schuurmans…]

### Retrieval Enhanced LLM

- `ArXiv-2023` **Learning to Filter Context for Retrieval-Augmented Generation** [[paper](https://arxiv.org/abs/2311.08377)][[code](https://github.com/zorazrw/filco)][Z Wang, J Araki, Z Jiang, MR Parvez…]

- √`ArXiv-2023` **Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection** [[paper](https://arxiv.org/abs/2310.11511)][[code](https://selfrag.github.io/)][A Asai, Z Wu, Y Wang, A Sil, H Hajishirzi]

- ~`ArXiv-2023` **A Step Closer to Comprehensive Answers: Constrained Multi-Stage Question Decomposition with Large Language Models** [[paper](https://arxiv.org/abs/2311.07491)][[code](https://github.com/alkaidpku/DQ-ToolQA)][H Cao, Z An, J Feng, K Xu, L Chen, D Zhao]

- ~`ArXiv-2023` **Chain-of-Note: Enhancing Robustness in Retrieval-Augmented Language Models** [[paper](https://arxiv.org/abs/2311.09210)][W Yu, H Zhang, X Pan, K Ma, H Wang, D Yu]

- √`ArXiv-2023` **KNN-LM Does Not Improve Open-ended Text Generation** [[paper](https://arxiv.org/abs/2305.14625)][S Wang, Y Song, A Drozdov, A Garimella…]

- √`ArXiv-2023` **Replug: Retrieval-augmented black-box language models** [[paper](https://arxiv.org/abs/2301.12652)][W Shi, S Min, M Yasunaga, M Seo, R James…]

- √`ArXiv-2023` **Rethinking with retrieval: Faithful large language model inference** [[paper](https://arxiv.org/abs/2301.00303)][[code](https://github.com/HornHehhf/RR)][H He, H Zhang, D Roth]

- √`ICLR-2023` **Generate rather than retrieve: Large language models are strong context generators** [[paper](https://arxiv.org/abs/2209.10063)][[code](https://github.com/wyu97/GenRead)][W Yu, D Iter, S Wang, Y Xu, M Ju, S Sanyal…]

- `ArXiv-2022` **Atlas: Few-shot learning with retrieval augmented language models** [[paper](https://arxiv.org/abs/2208.03299)][[code](https://github.com/facebookresearch/atlas)][G Izacard, P Lewis, M Lomeli, L Hosseini…]

- √`EMNLP-2022` **Training language models with memory augmentation** [[paper](https://arxiv.org/abs/2205.12674)][[code](https://github.com/princeton-nlp/TRIME)][Z Zhong, T Lei, D Chen]

- √`NeurIPS-2021` **End-to-end training of multi-document reader and retriever for open-domain question answering** [[paper](https://proceedings.neurips.cc/paper_files/paper/2021/hash/da3fde159d754a2555eaa198d2d105b2-Abstract.html)][[code](https://github.com/DevSinghSachan/emdr2)][D Singh, S Reddy, W Hamilton…]

- √`NeurIPS-2020` **Retrieval-augmented generation for knowledge-intensive nlp tasks** [[paper](https://proceedings.neurips.cc/paper/2020/hash/6b493230205f780e1bc26945df7481e5-Abstract.html)][P Lewis, E Perez, A Piktus, F Petroni…]

- √`ICLR-2020` **Generalization through memorization: Nearest neighbor language models** [[paper](https://arxiv.org/abs/1911.00172)][U Khandelwal, O Levy, D Jurafsky…]

- √`ICML-2020` **Retrieval augmented language model pre-training** [[paper](http://proceedings.mlr.press/v119/guu20a.html?ref=https://githubhelp.com)][K Guu, K Lee, Z Tung, P Pasupat…]

- `ACL-2019` **Latent retrieval for weakly supervised open domain question answering** [[paper](https://arxiv.org/abs/1906.00300)][K Lee, MW Chang, K Toutanova]

### Text Generation

- √`ACL-2023` **STORYWARS: A Dataset and Instruction Tuning Baselines for Collaborative Story Understanding and Generation** [[paper](https://arxiv.org/abs/2305.08152)][[code](https://github.com/ylndu/storywars)][Y Du, L Chilton]

    - P.S. 论文中附的代码仓库链接已经404，试图和作者取得联系(2023/11/20 15:30)。

- √`ArXiv-2023` **Retrieval meets Long Context Large Language Models** [[paper](https://arxiv.org/abs/2310.03025)][P Xu, W Ping, X Wu, L McAfee, C Zhu, Z Liu…]

- √`NeurIPS-2022` **Factuality enhanced language models for open-ended text generation** [[paper](https://proceedings.neurips.cc/paper_files/paper/2022/hash/df438caa36714f69277daa92d608dd63-Abstract-Conference.html)][[code](https://github.com/nayeon7lee/FactualityPrompt)][N Lee, W Ping, P Xu, M Patwary…]

- √`EMNLP-2022` **Re3: Generating longer stories with recursive reprompting and revision** [[paper](https://arxiv.org/abs/2210.06774)][[code](https://github.com/yangkevin2/emnlp22-re3-story-generation)][K Yang, Y Tian, N Peng, D Klein]

- √`ArXiv-2021` **Automatic story generation: Challenges and attempts** [[paper](https://arxiv.org/abs/2102.12634)][A Alabdulkarim, S Li, X Peng]

- √`AAAI-2019` **Plan-and-write: Towards better automatic storytelling** [[paper](https://ojs.aaai.org/index.php/AAAI/article/view/4726)][[code](https://bitbucket.org/VioletPeng/language-model)][L Yao, N Peng, R Weischedel, K Knight…]

### Agents

### Benchmark

- √`ACL-2023` **WikiHowQA: A Comprehensive Benchmark for Multi-Document Non-Factoid Question Answering** [[paper](https://aclanthology.org/2023.acl-long.290/)][[code](https://lurunchik.github.io/WikiHowNFQA/)][V Bolotova-Baranova, V Blinov…]

### Others

- √`ArXiv-2023` **Lost in the middle: How language models use long contexts** [[paper](https://arxiv.org/abs/2307.03172)][NF Liu, K Lin, J Hewitt, A Paranjape…]



## Models

***NLP模型和算法***

## Datasets

***常用NLP数据集链接和描述***

## Tools & Libraries

***NLP工具和库***

## Tutorials & Guides

***NLP入门和高级教程***

## Resources

***其他资源，包括但不限于会议视频、博客文章、讲座笔记等***

## Projects

***有趣的NLP项目***

