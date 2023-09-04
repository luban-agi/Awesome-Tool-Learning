<!-- <div style="text-align: center;">

    <h1><img src="assets/logo.png" height="28px" /> Tool Learning Papers </h1>

</div> -->

# Awesome Tool Learning

[![Awesome](https://awesome.re/badge.svg)](https://github.com/luban-agi/Awesome-Tool-Learning) 
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](https://opensource.org/licenses/MIT)
![](https://img.shields.io/github/last-commit/luban-agi/Awesome-Tool-Learning) 
![](https://img.shields.io/badge/PRs-Welcome-red)

Awesome papers and tools on tool learning.

## 📜 Table of Contents

- [📚 Papers](#-papers)
  - [📑 Survey](#-survey)
  - [🏋️‍♂️ Tool Use Via Fine-tuning](#-tool-use-via-fine-tuning)
  - [📖 Tool Use Via In-Context Learning](#-tool-use-via-in-context-learning)
  - [🧪 Evalution](#-evalution)
- [📱 Applications](#-applications)
- [🎉 Contributors](#-contributors)

## 📚 Papers

### 📑 Survey

- **Augmented Language Models: a Survey**, Preprint 2023.02 

  *Grégoire Mialon, Roberto Dessì, Maria Lomeli, Christoforos Nalmpantis, Ram Pasunuru, Roberta Raileanu, Baptiste Rozière, Timo Schick, Jane Dwivedi-Yu, Asli Celikyilmaz, Edouard Grave, Yann LeCun, Thomas Scialom* [[pdf](https://arxiv.org/abs/2302.07842)]

- **Tool Learning with Foundation Models**, Preprint 2023.04 

  *Yujia Qin, Shengding Hu, Yankai Lin, Weize Chen, Ning Ding, Ganqu Cui, Zheni Zeng, Yufei Huang, Chaojun Xiao, Chi Han, Yi Ren Fung, Yusheng Su, Huadong Wang, Cheng Qian, Runchu Tian, Kunlun Zhu, Shihao Liang, Xingyu Shen, Bokai Xu, Zhen Zhang, Yining Ye, Bowen Li, Ziwei Tang, Jing Yi, Yuzhang Zhu, Zhenning Dai, Lan Yan, Xin Cong, Yaxi Lu, Weilin Zhao, Yuxiang Huang, Junxi Yan, Xu Han, Xian Sun, Dahai Li, Jason Phang, Cheng Yang, Tongshuang Wu, Heng Ji, Zhiyuan Liu, Maosong Sun* [[pdf](https://arxiv.org/abs/2304.08354)]

- **A Survey on Large Language Model based Autonomous Agents**, Preprint 2023.08

  *Lei Wang, Chen Ma, Xueyang Feng, Zeyu Zhang, Hao Yang, Jingsen Zhang, Zhiyuan Chen, Jiakai Tang, Xu Chen, Yankai Lin, Wayne Xin Zhao, Zhewei Wei, Ji-Rong Wen* [[pdf](https://arxiv.org/abs/2308.11432)]

### 🏋️‍♂️ Tool Use Via Fine-tuning

- **WebGPT: Browser-assisted question-answering with human feedback** Preprint 2021.12

  *Reiichiro Nakano, Jacob Hilton, Suchir Balaji, Jeff Wu, Long Ouyang, Christina Kim, Christopher Hesse, Shantanu Jain, Vineet Kosaraju, William Saunders, Xu Jiang, Karl Cobbe, Tyna Eloundou, Gretchen Krueger, Kevin Button, Matthew Knight, Benjamin Chess, John Schulman* [[pdf](https://arxiv.org/abs/2112.09332)]

- **TALM: Tool Augmented Language Models** Preprint 2022.05 

  *Aaron Parisi, Yao Zhao, Noah Fiedel* [[pdf](https://arxiv.org/abs/2205.12255)]

- **WebShop: Towards Scalable Real-World Web Interaction with Grounded Language Agents** NeurIPS 2022.07

  *Shunyu Yao, Howard Chen, John Yang, Karthik Narasimhan* [[pdf](https://arxiv.org/abs/2207.01206)],[[github](https://webshop-pnlp.github.io/)]

- **Toolformer: Language Models Can Teach Themselves to Use Tools** Preprint 2023.02

  *Timo Schick, Jane Dwivedi-Yu, Roberto Dessì, Roberta Raileanu, Maria Lomeli, Luke Zettlemoyer, Nicola Cancedda, Thomas Scialom* [[pdf](https://arxiv.org/abs/2302.04761)]

- **ToolCoder: Teach Code Generation Models to use API search tools** Preprint 2023.05

  *Kechi Zhang, Huangzhao Zhang, Ge Li, Jia Li, Zhuo Li, Zhi Jin* [[pdf](https://arxiv.org/abs/2305.04032)]

- **WebCPM: Interactive Web Search for Chinese Long-form Question Answering** ACL 2023.05

  *Yujia Qin, Zihan Cai, Dian Jin, Lan Yan, Shihao Liang, Kunlun Zhu, Yankai Lin, Xu Han, Ning Ding, Huadong Wang, Ruobing Xie, Fanchao Qi, Zhiyuan Liu, Maosong Sun, Jie Zhou* [[pdf](https://arxiv.org/abs/2305.06849)]

- **ToolkenGPT: Augmenting Frozen Language Models with Massive Tools via Tool Embeddings** Preprint 2023.05 

  *Shibo Hao, Tianyang Liu, Zhen Wang, Zhiting Hu* [[pdf](https://arxiv.org/abs/2305.11554)][[github](https://github.com/Ber666/ToolkenGPT)]

- **Making Language Models Better Tool Learners with Execution Feedback** Preprint 2023.05

  *Shuofei Qiao, Honghao Gui, Huajun Chen, Ningyu Zhang* [[pdf](https://arxiv.org/abs/2305.13068)]

- **Gorilla: Large Language Model Connected with Massive APIs** Preprint 2023.05

  *Shishir G. Patil, Tianjun Zhang, Xin Wang, Joseph E. Gonzalez* [[pdf](https://arxiv.org/abs/2305.15334)]

- **GPT4Tools: Teaching Large Language Model to Use Tools via Self-instruction** Preprint 2023.05

  *Rui Yang, Lin Song, Yanwei Li, Sijie Zhao, Yixiao Ge, Xiu Li, Ying Shan* [[pdf](https://arxiv.org/abs/2305.18752)],[[github](https://github.com/StevenGrove/GPT4Tools)]

- **ToolAlpaca: Generalized Tool Learning for Language Models with 3000 Simulated Cases** Preprint 2023.06 

  *Qiaoyu Tang, Ziliang Deng, Hongyu Lin, Xianpei Han, Qiao Liang, Le Sun* [[pdf](https://arxiv.org/abs/2306.05301)]

- **WebGLM: Towards An Efficient Web-Enhanced Question Answering System with Human Preferences** KDD 2023.06

  *Xiao Liu, Hanyu Lai, Hao Yu, Yifan Xu, Aohan Zeng, Zhengxiao Du, Peng Zhang, Yuxiao Dong, Jie Tang* [[pdf](https://arxiv.org/abs/2306.07906)]

### 📖 Tool Use via In-Context Learning

- **PAL: Program-aided Language Models** Preprint 2022.11

  *Luyu Gao, Aman Madaan, Shuyan Zhou, Uri Alon, Pengfei Liu, Yiming Yang, Jamie Callan, Graham Neubig* [[pdf](https://arxiv.org/abs/2211.10435)],[[github](https://reasonwithpal.com/)]

- **Program of Thoughts Prompting: Disentangling Computation from Reasoning for Numerical Reasoning Tasks** Preprint 2022.11

  *Wenhu Chen, Xueguang Ma, Xinyi Wang, William W. Cohen* [[pdf](https://arxiv.org/abs/2211.12588)]

- **ART: Automatic multi-step reasoning and tool-use for large language models** Preprint 2023.03

  *Bhargavi Paranjape, Scott Lundberg, Sameer Singh, Hannaneh Hajishirzi, Luke Zettlemoyer, Marco Tulio Ribeiro* [[pdf](https://arxiv.org/abs/2303.09014)]

- **TaskMatrix.AI: Completing Tasks by Connecting Foundation Models with Millions of APIs** Preprint 2023.03

  *Yaobo Liang, Chenfei Wu, Ting Song, Wenshan Wu, Yan Xia, Yu Liu, Yang Ou, Shuai Lu, Lei Ji, Shaoguang Mao, Yun Wang, Linjun Shou, Ming Gong, Nan Duan* [[pdf](https://arxiv.org/abs/2303.16434)]

- **HuggingGPT: Solving AI Tasks with ChatGPT and its Friends in Hugging Face** Preprint 2023.03

  *Yongliang Shen, Kaitao Song, Xu Tan, Dongsheng Li, Weiming Lu, Yueting Zhuang* [[pdf](https://arxiv.org/abs/2303.17580)]

- **OpenAGI: When LLM Meets Domain Experts** Preprint 2023.04

  *Yingqiang Ge, Wenyue Hua, Kai Mei, Jianchao Ji, Juntao Tan, Shuyuan Xu, Zelong Li, Yongfeng Zhang* [[pdf](https://arxiv.org/abs/2304.04370)]

- **ChemCrow: Augmenting large-language models with chemistry tools** Preprint 2023.04

  *Andres M Bran, Sam Cox, Andrew D White, Philippe Schwaller* [[pdf](https://arxiv.org/abs/2304.05376)]

- **GeneGPT: Augmenting Large Language Models with Domain Tools for Improved Access to Biomedical Information** Preprint 2023.04

  *Qiao Jin, Yifan Yang, Qingyu Chen, Zhiyong Lu* [[pdf](https://arxiv.org/abs/2304.09667)]

- **Chameleon: Plug-and-Play Compositional Reasoning with Large Language Models** Preprint 2023.04

  *Pan Lu, Baolin Peng, Hao Cheng, Michel Galley, Kai-Wei Chang, Ying Nian Wu, Song-Chun Zhu, Jianfeng Gao* [[pdf](https://arxiv.org/abs/2304.09842)],[[github](https://chameleon-llm.github.io/)]

- **ChatCoT: Tool-Augmented Chain-of-Thought Reasoning on Chat-based Large Language Models** Preprint 2023.05

  *Zhipeng Chen, Kun Zhou, Beichen Zhang, Zheng Gong, Wayne Xin Zhao, Ji-Rong Wen* [[pdf](https://arxiv.org/abs/2305.14323)]

- **CREATOR: Disentangling Abstract and Concrete Reasonings of Large Language Models through Tool Creation** Preprint 2023.05

  *Cheng Qian, Chi Han, Yi R. Fung, Yujia Qin, Zhiyuan Liu, Heng Ji* [[pdf](https://arxiv.org/abs/2305.14318)]

- **Large Language Models as Tool Makers** Preprint 2023.05

  *Tianle Cai, Xuezhi Wang, Tengyu Ma, Xinyun Chen, Denny Zhou* [[pdf](https://arxiv.org/abs/2305.17126)],[[github](https://github.com/ctlllll/LLM-ToolMaker)]

- **MultiTool-CoT: GPT-3 Can Use Multiple External Tools with Chain of Thought Prompting** ACL 2023.05

  *Tatsuro Inaba, Hirokazu Kiyomaru, Fei Cheng, Sadao Kurohashi* [[pdf](https://arxiv.org/abs/2305.16896)],[[project](https://github.com/InabaTatsuro/MultiTool-CoT)]

- **RestGPT: Connecting Large Language Models with Real-World Applications via RESTful APIs** Preprint 2023.06

  *Yifan Song, Weimin Xiong, Dawei Zhu, Cheng Li, Ke Wang, Ye Tian, Sujian Li* [[pdf](https://arxiv.org/abs/2306.06624)]

- **AssistGPT: A General Multi-modal Assistant that can Plan, Execute, Inspect, and Learn** Preprint 2023.06

  *Difei Gao, Lei Ji, Luowei Zhou, Kevin Qinghong Lin, Joya Chen, Zihan Fan, Mike Zheng Shou* [[pdf](https://arxiv.org/abs/2306.08640)],[[project](https://showlab.github.io/assistgpt/)]

- **GEAR: Augmenting Language Models with Generalizable and Efficient Tool Resolution** Preprint 2023.07

  *Yining Lu, Haoping Yu, Daniel Khashabi* [[pdf](https://arxiv.org/abs/2307.08775)]

- **Skills-in-Context Prompting: Unlocking Compositionality in Large Language Models** Preprint 2023.08

  *Jiaao Chen, Xiaoman Pan, Dian Yu, Kaiqiang Song, Xiaoyang Wang, Dong Yu, Jianshu Chen* [[pdf](https://arxiv.org/abs/2308.00304)]

- **Tool Documentation Enables Zero-Shot Tool-Usage with Large Language Models** Preprint 2023.08

  *Cheng-Yu Hsieh, Si-An Chen, Chun-Liang Li, Yasuhisa Fujii, Alexander Ratner, Chen-Yu Lee, Ranjay Krishna, Tomas Pfister* [[pdf](https://arxiv.org/abs/2308.00675)]

- **TPTU: Task Planning and Tool Usage of Large Language Model-based AI Agents** Preprint 2023.08

  *Jingqing Ruan, Yihong Chen, Bin Zhang, Zhiwei Xu, Tianpeng Bao, Guoqing Du, Shiwei Shi, Hangyu Mao, Xingyu Zeng, Rui Zhao* [[pdf](https://arxiv.org/abs/2308.03427)]

### 🧪 Evalution

- **API-Bank: A Benchmark for Tool-Augmented LLMs** Preprint 2023.04

  *Minghao Li, Feifan Song, Bowen Yu, Haiyang Yu, Zhoujun Li, Fei Huang, Yongbin Li* [[pdf](https://arxiv.org/abs/2306.08640)]

- **On the Tool Manipulation Capability of Open-source Large Language Models** Preprint 2023.05

  *Qiantong Xu, Fenglu Hong, Bo Li, Changran Hu, Zhengyu Chen, Jian Zhang* [[pdf](https://arxiv.org/abs/2305.16504)]

- **Evaluating and Improving Tool-Augmented Computation-Intensive Math Reasoning** Preprint 2023.06

  *Beichen Zhang, Kun Zhou, Xilin Wei, Wayne Xin Zhao, Jing Sha, Shijin Wang, Ji-Rong Wen* [[pdf](https://arxiv.org/abs/2306.02408)]

- **ToolQA: A Dataset for LLM Question Answering with External Tools** Preprint 2023.06

  *Yuchen Zhuang, Yue Yu, Kuan Wang, Haotian Sun, Chao Zhangu* [[pdf](https://arxiv.org/abs/2306.13304)]
  
- **ToolLLM: Facilitating Large Language Models to Master 16000+ Real-world APIs** Preprint 2023.07

  *Yujia Qin, Shihao Liang, Yining Ye, Kunlun Zhu, Lan Yan, Yaxi Lu, Yankai Lin, Xin Cong, Xiangru Tang, Bill Qian, Sihan Zhao, Runchu Tian, Ruobing Xie, Jie Zhou, Mark Gerstein, Dahai Li, Zhiyuan Liu, Maosong Sun* [[pdf](https://arxiv.org/abs/2307.16789)]

- **AgentBench: Evaluating LLMs as Agents** Preprint 2023.08

  *Xiao Liu, Hao Yu, Hanchen Zhang, Yifan Xu, Xuanyu Lei, Hanyu Lai, Yu Gu, Hangliang Ding, Kaiwen Men, Kejuan Yang, Shudan Zhang, Xiang Deng, Aohan Zeng, Zhengxiao Du, Chenhui Zhang, Sheng Shen, Tianjun Zhang, Yu Su, Huan Sun, Minlie Huang, Yuxiao Dong, Jie Tang* [[pdf](https://arxiv.org/abs/2308.03688)]


 <!--## ⏱️ Benchmark

|     DataSet Name          | Quantity of Tools | Samples |
| :-----------------------: | ----------------- | ------- |
| [**ToolBench**](https://drive.google.com/drive/folders/1yBUQ732mPu-KclJnuQELEhtKakdXFc3J)  | 16464 | 10K |
| [**moss-003-sft-plugin-data**](https://huggingface.co/datasets/fnlp/moss-003-sft-data/tree/main) | 4 | 300K |
|  [**GPT4Tools**](https://drive.google.com/file/d/1JKIT-Or1of7TJuWvmrJpPoOx0cLdcWry/view?usp=share_link)  | 22 | 71K |
|   [**Gorilla**](https://github.com/ShishirPatil/gorilla/tree/main/data/apibench)   | 1645 | 16450 |
-->

## 📱 Applications

- [Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT): An experimental open-source attempt to make GPT-4 fully autonomous. ![GitHub Repo stars](https://img.shields.io/github/stars/Significant-Gravitas/Auto-GPT)

- [LangChain](https://github.com/langchain-ai/langchain): Building applications with LLMs through composability. ![GitHub Repo stars](https://img.shields.io/github/stars/langchain-ai/langchain)

- [DB-GPT](https://github.com/eosphoros-ai/DB-GPT): Revolutionizing Database Interactions with Private LLM Technology. ![GitHub Repo stars](https://img.shields.io/github/stars/eosphoros-ai/DB-GPT)

## 🎉 Contributors

<a href="https://github.com/luban-agi/Awesome-Tool-Learning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=luban-agi/Awesome-Tool-Learning"/>

</a>
