# 🧠 LLM Reasoning Review

A curated collection of research papers focused on the **reasoning capabilities of Large Language Models (LLMs)**. This repository organizes and categorizes works that evaluate, benchmark, analyze, and summarize reasoning techniques used in LLMs.

---

## 🗂 Categories

- 📚 **Surveys & Meta-Analyses**
  - Literature reviews and taxonomies of LLM reasoning work
- 🔍 **Evaluation & Benchmarking**
  - Performance comparisons across tasks and models
  - New benchmarks and metrics
- 🧠 **Reasoning Techniques**
  - Chain-of-Thought prompting
  - Self-consistency, scratchpads, tool-augmented reasoning, etc.
---

## 📌 Paper List

## Survey
- **[A Survey of Reasoning with Foundation Models](https://arxiv.org/abs/2312.11562)**  
  *Jiankai Sun, Chuanyang Zheng, Enze Xie, Zhengying Liu, Ruihang Chu, Jianing Qiu, Jiaqi Xu, Mingyu Ding, Hongyang Li, Mengzhe Geng, Yue Wu, Wenhai Wang, Junsong Chen, Zhangyue Yin, Xiaozhe Ren, Jie Fu, Junxian He, Wu Yuan, Qi Liu, Xihui Liu, Yu Li, Hao Dong, Yu Cheng, Ming Zhang, Pheng Ann Heng, Jifeng Dai, Ping Luo, Jingdong Wang, Ji-Rong Wen, Xipeng Qiu, Yike Guo, Hui Xiong, Qun Liu, Zhenguo Li* • *Preprint'24*  
  📁 Tags: `evaluation`, `survey`
- **[Beyond Accuracy: Evaluating the Reasoning Behavior of Large Language Models -- A Survey](https://arxiv.org/abs/2404.01869)**  
  *Philipp Mondorf, Barbara Plank* • *Preprint'24*  
  📁 Tags: `evaluation`, `survey`
- **[Multimodal Chain-of-Thought Reasoning: A Comprehensive Survey](https://arxiv.org/abs/2503.12605), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/yaotingwangofficial/Awesome-MCoT)**  
  *Yaoting Wang, Shengqiong Wu, Yuecheng Zhang, Shuicheng Yan, Ziwei Liu, Jiebo Luo, Hao Fei* • *Preprint'25*  
  📁 Tags: `evaluation`, `chain-of-thought`, `survey`
- **[Reasoning with Large Language Models, a Survey](https://arxiv.org/abs/2407.11511)**  
  *Aske Plaat, Annie Wong, Suzan Verberne, Joost Broekens, Niki van Stein, Thomas Back* • *Preprint'24*  
  📁 Tags: `evaluation`, `survey`  
 <!-- 📝 Summary: One or two sentences describing the paper's contribution.-->

## Evaluation Benchmarks
### General reasoning tasks
- **[1.4 Million Open-Source Distilled Reasoning Dataset to Empower Large Language Model Training](https://arxiv.org/abs/2503.19633), [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="20" alt="Hugging Face" />](https://huggingface.co/datasets/a-m-team/AM-DeepSeek-R1-Distilled-1.4M)**
  *Han Zhao, Haotian Wang, Yiping Peng, Sitong Zhao, Xiaoyu Tian, Shuaiting Chen, Yunjie Ji, Xiangang Li* • *Preprint'25* 
  📁 Tags: `evaluation`, `benchmarks`, `general-reasoning-task`
  
### Code Generation
- **[BigCodeBench: Benchmarking Code Generation with Diverse Function Calls and Complex Instructions](https://arxiv.org/abs/2406.15877), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/bigcode-project/bigcodebench/tree/main), [[🏆Leaderboard]](https://bigcode-bench.github.io/))**
  *Terry Yue Zhuo, Minh Chien Vu, Jenny Chim, Han Hu, Wenhao Yu, Ratnadira Widyasari, Imam Nur Bani Yusuf, Haolan Zhan, Junda He, Indraneil Paul, Simon Brunner, Chen Gong, Thong Hoang, Armel Randy Zebaze, Xiaoheng Hong, Wen-Ding Li, Jean Kaddour, Ming Xu, Zhihan Zhang, Prateek Yadav, Naman Jain, Alex Gu, Zhoujun Cheng, Jiawei Liu, Qian Liu, Zijian Wang, Binyuan Hui, Niklas Muennighoff, David Lo, Daniel Fried, Xiaoning Du, Harm de Vries, Leandro Von Werra* • *ICLR 2025* 
  📁 Tags: `evaluation`, `benchmarks`, `code-generation`
<!-- MBPP, Humaneval, livecodebench-->
- **[HumanEval Pro and MBPP Pro: Evaluating Large Language Models on Self-invoking Code Generation](https://arxiv.org/abs/2412.21199), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/CodeEval-Pro/CodeEval-Pro/tree/main), [[🏆Leaderboard]](https://answers111.github.io/evalpro.github.io/leaderboard.html)**
  *Zhaojian Yu, Yilun Zhao, Arman Cohan, Xiao-Ping Zhang* • *Preprint'24*
  📁 Tags: `evaluation`, `benchmarks`, `code-generation`
- **[LiveCodeBench: Holistic and Contamination Free Evaluation of Large Language Models for Code](https://arxiv.org/abs/2403.07974), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/LiveCodeBench/LiveCodeBench), [[🏆Leaderboard]](https://livecodebench.github.io/leaderboard.html))**
  *Naman Jain, King Han, Alex Gu, Wen-Ding Li, Fanjia Yan, Tianjun Zhang, Sida Wang, Armando Solar-Lezama, Koushik Sen, Ion Stoica* • *Prepirnt'24* 
  📁 Tags: `evaluation`, `benchmarks`, `code-generation`
  
### Code Translation
<!-- CodeOceanTrans, CodeNet, Avatar -->
- **[CodeTransOcean: A Comprehensive Multilingual Benchmark for Code Translation](https://arxiv.org/abs/2310.04951), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/WeixiangYAN/CodeTransOcean), [[🏆Leaderboard]](https://yuchen814.github.io/CodeTransOcean/)**
  *Weixiang Yan, Yuchen Tian, Yunzhe Li, Qian Chen, Wen Wang* • *EMNLP 2023*
  📁 Tags: `evaluation`, `benchmarks`, `code-translation`
  
### Issue Resolution
<!-- SWE bench -->
- **[SWE-bench: Can Language Models Resolve Real-World GitHub Issues?](https://arxiv.org/abs/2310.06770), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/swe-bench/SWE-bench), [[🏆Leaderboard]](https://www.swebench.com/index.html)**
  *Carlos E. Jimenez, John Yang, Alexander Wettig, Shunyu Yao, Kexin Pei, Ofir Press, Karthik Narasimhan* • *ICLR 2024*
  📁 Tags: `evaluation`, `benchmarks`, `issue-resolution`

### Mathematical
- **[GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models](https://arxiv.org/abs/2410.05229), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/apple/ml-gsm-symbolic)**  
  *Iman Mirzadeh, Keivan Alizadeh, Hooman Shahrokhi, Oncel Tuzel, Samy Bengio, Mehrdad Farajtabar* • *Preprint'24*  
  📁 Tags: `evaluation`, `reasoning-quality`, `mathematics`
- **[LLaMA-Berry: Pairwise Optimization for O1-like Olympiad-Level Mathematical Reasoning](https://arxiv.org/abs/2410.02884), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/trotsky1997/MathBlackBox)**  
  *Di Zhang, Jianbo Wu, Jingdi Lei, Tong Che, Jiatong Li, Tong Xie, Xiaoshui Huang, Shufei Zhang, Marco Pavone, Yuqiang Li, Wanli Ouyang, Dongzhan Zhou* • *Preprint'24*  
  📁 Tags: `evaluation`, `reasoning-quality`, `mathematics` 
  
## LLM-Reasoning
- **[Large Language Models for Code Analysis: Do LLMs Really Do Their Job?”](https://arxiv.org/html/2310.12357v2#:~:text=This%20paper%20seeks%20to%20bridge,applications%20in%20this%20critical%20domain), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/aseec-lab/llms-for-code-analysis)**  
  *Chongzhou Fang, Ning Miao, Shaurya Srivastav, Jialin Liu, Ruoyu Zhang, Ruijie Fang, Asmita, Ryan Tsang, Najmeh Nazari, Han Wang, Houman Homayoun* • *Usenix Security 2024*  
  📁 Tags: `evaluation`, `llm-reasoning`, `code-task`

- **[Think Twice: Enhancing LLM Reasoning by Scaling Multi-round Test-time Thinking](https://arxiv.org/abs/2503.19855), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/aseec-lab/llms-for-code-analysis)**  
  *Xiaoyu Tian, Sitong Zhao, Haotian Wang, Shuaiting Chen, Yunjie Ji, Yiping Peng, Han Zhao, Xiangang Li* • *Preprint'25*  
  📁 Tags: `evaluation`, `reasoning-quality`, `improve-quality-of-reasoning`

 - **[LLM Reasoners: New Evaluation, Library, and Analysis of Step-by-Step Reasoning with Large Language Models](https://arxiv.org/abs/2404.05221), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/aseec-lab/llms-for-code-analysis)**  
  *Shibo Hao, Yi Gu, Haotian Luo, Tianyang Liu, Xiyan Shao, Xinyuan Wang, Shuhua Xie, Haodi Ma, Adithya Samavedhi, Qiyue Gao, Zhen Wang, Zhiting Hu* • *Preprint'25*  
  📁 Tags: `evaluation`, `reasoning-quality`, ``

- **[Learning to reason with LLMs](https://openai.com/index/learning-to-reason-with-llms/)**  
  *OpenAI*
  📁 Tags: `evaluation`, `reasoning-quality`, `o1`

- **[Evaluating the Generalization Capabilities of Large Language Models on Code Reasoning](https://arxiv.org/abs/2504.05518)**  
  *Rem Yang, Julian Dai, Nikos Vasilakis, Martin Rinard* • *Preprint'25*  
  📁 Tags: `evaluation`, `llm-reasoning`
  
## Reasoning-quality
### Code Task
- **[CodeMind: A Framework to Challenge Large Language Models for Code Reasoning](https://arxiv.org/html/2402.09664v3), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/r-eval/REval)**  
  *Changshu Liu, Shizhuo Dylan Zhang, Reyhaneh Jabbarvand* • *Preprint'24*  
  📁 Tags: `evaluation`, `reasoning-quality`, `code-task` 
- **[Reasoning Runtime Behavior of a Program with LLM: How Far Are We?](https://arxiv.org/abs/2403.16437#:~:text=code%20LLMs%20in%20various%20aspects%2C,adapt%20them%20to%20new%20benchmarks), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/r-eval/REval)**  
  *Junkai Chen, Zhiyuan Pan, Xing Hu, Zhenhao Li, Ge Li, Xin Xia* • *ICSE 2025*  
  📁 Tags: `evaluation`, `reasoning-quality`, `code-task`
  

### General Task
- **[Quantifying the Reasoning Abilities of LLMs on Real-world Clinical Cases](https://arxiv.org/abs/2503.04691), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/MAGIC-AI4Med/MedRBench)**  
  *Pengcheng Qiu, Chaoyi Wu, Shuyu Liu, Weike Zhao, Zhuoxia Chen, Hongfei Gu, Chuanjin Peng, Ya Zhang, Yanfeng Wang, Weidi Xie* • *Preprint'25*
  📁 Tags: `evaluation`, `reasoning-quality`, `medical-application`, `LLM-evaluation`
- **[DeepSeek-R1 Thoughtology: Let's <think> about LLM Reasoning](https://arxiv.org/abs/2504.07128), [<img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" width="20" alt="Hugging Face" />](https://huggingface.co/papers/2504.07128)**  
  *Sara Vera Marjanović, Arkil Patel, Vaibhav Adlakha, Milad Aghajohari, Parishad BehnamGhader, Mehar Bhatia, Aditi Khandelwal, Austin Kraft, Benno Krojer, Xing Han Lù, Nicholas Meade, Dongchan Shin, Amirhossein Kazemnejad, Gaurav Kamath, Marius Mosbach, Karolina Stańczak, Siva Reddy* • *Preprint'25*
  📁 Tags: `evaluation`, `reasoning-quality`, `LLM-evaluation`
- **[Leveraging LLM Reasoning Enhances Personalized Recommender Systems](https://arxiv.org/abs/2408.00802)**  
  *Alicia Y. Tsai, Adam Kraft, Long Jin, Chenwei Cai, Anahita Hosseini, Taibai Xu, Zemin Zhang, Lichan Hong, Ed H. Chi, Xinyang Yi* • *ACL 2024*  
  📁 Tags: `evaluation`, `reasoning-quality`, `personalized recommendation systems (RecSys)`
- **[GSM-Symbolic: Understanding the Limitations of Mathematical Reasoning in Large Language Models](https://arxiv.org/abs/2410.05229), [<img src="https://github.githubassets.com/images/modules/logos_page/GitHub-Mark.png" width="22" alt="GitHub repo" />](https://github.com/apple/ml-gsm-symbolic)**  
  *Iman Mirzadeh, Keivan Alizadeh, Hooman Shahrokhi, Oncel Tuzel, Samy Bengio, Mehrdad Farajtabar* • *Preprint'24*  
  📁 Tags: `evaluation`, `reasoning-quality`, `mathematics`
- **[Improving Rule-based Reasoning in LLMs via Neurosymbolic Representations](https://arxiv.org/html/2502.01657v1)**  
  *Varun Dhanraj, Chris Eliasmith* • *Preprint'25*  
  📁 Tags: `evaluation`, `reasoning-quality`, `mathematics`
- **[Improve Mathematical Reasoning in Language Models by Automated Process Supervision](https://arxiv.org/abs/2406.06592)**  
  *Liangchen Luo, Yinxiao Liu, Rosanne Liu, Samrat Phatale, Meiqi Guo, Harsh Lara, Yunxuan Li, Lei Shu, Yun Zhu, Lei Meng, Jiao Sun, Abhinav Rastogi* • *Preprint'24*  
  📁 Tags: `evaluation`, `reasoning-quality`, `mathematics`
- **[Medical Reasoning in LLMs: An In-Depth Analysis of DeepSeek R1](https://arxiv.org/abs/2504.00016)**  
  *Birger Moell, Fredrik Sand Aronsson, Sanian Akbar* • *Preprint'25*
  📁 Tags: `evaluation`, `reasoning-quality`, `medical-aaplication`, `human-evaluation`
  <!-- 📝 Summary: One or two sentences describing the paper's contribution. -->

