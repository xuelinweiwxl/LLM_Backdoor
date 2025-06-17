<!--
 * @Author: Xuelin Wei
 * @Email: xuelinwei@seu.edu.cn
 * @Date: 2025-06-17 21:37:51
 * @LastEditTime: 2025-06-17 22:28:15
 * @LastEditors: xuelinwei17 374094051@qq.com
 * @FilePath: /LLM_Backdoor/README.md
-->
# LLM Backdoor
A comprehensive library for studying and implementing backdoor attacks and defenses in Large Language Models (LLMs), LLM-powered agents, and LLM-based applications

## Table of Contents

- [Backdoor Attacks and Defenses Targeting LLM](#backdoor-attacks-and-defenses-targeting-llm)
- [Backdoor Attacks and Defenses Targeting LLM-powered Agents](#backdoor-attacks-and-defenses-targeting-llm-powered-agents)
- [Backdoor Attacks and Defenses Targeting LLM-based Applications](#backdoor-attacks-and-defenses-targeting-llm-based-applications)
- [Comprehensive Benchmarks for LLM Backdoor](#comprehensive-benchmarks-for-llm-backdoor)
- [Evaluation Metrics for LLM Backdoor](#evaluation-metrics-for-llm-backdoor)
- [Common LLMs](#common-llms)
- [Common Datasets](#common-datasets)  


## Backdoor Attacks and Defenses Targeting LLM

### Data poisoning attacks

### Weight poisoning attacks

### Hidden state attacks

### Chain-of-thought attacks

## Backdoor Attacks and Defenses Targeting LLM-powered Agents

## Backdoor Attacks and Defenses Targeting LLM-based Applications

## Comprehensive Benchmarks for LLM Backdoor

| Paper | Description | Publisher | Date | Links |
|-------|-------------|-----------|------|-------|
|BackdoorLLM: A Comprehensive Benchmark for Backdoor Attacks and Defenses on Large Language Models|BackdoorLLM is a comprehensive benchmark that provides standardized evaluation pipelines, diverse attack modalities, extensive experiments, and defense toolkits for systematically studying backdoor threats in text-generation LLMs.|arXiv|2024.08|[paper](https://arxiv.org/abs/2408.12798) [code](https://github.com/bboylyg/BackdoorLLM)|


## Evaluation Metrics for LLM Backdoor

## Common LLM Models

### Open-source Models








## Common Datasets

| Type | Dataset | Description | Size | Task Type | Link |
|------|---------|-------------|------|-----------|------|
| Text Classification | SST-2 | Stanford Sentiment Treebank V2 - Binary sentiment classification | 67,349 samples (8,544 test) | Sentiment Analysis | [Link](https://huggingface.co/datasets/SST-2) |
| Text Classification | AGNews | AG's News Topic Classification Dataset | 120,000 training + 7,600 test samples | News Classification | [Link](https://huggingface.co/datasets/sentence-transformers/agnews) |
| Instruction Following | Stanford Alpaca | Instruction-following dataset created by having GPT-4 generate responses to 52K instruction prompts | 52K samples | General Instructions | [Link](https://github.com/tatsu-lab/stanford_alpaca) |
| Safety & Bias | AdvBench | Benchmark for red teaming and testing LLM safety | 500+ adversarial prompts | Security Testing | [Link](https://github.com/llm-attacks/llm-attacks) |
| Safety & Bias | ToxiGen | Machine-generated toxic content dataset | 274K samples | Toxicity Detection | [Link](https://huggingface.co/datasets/toxigen/toxigen-data) |
| Safety & Bias | BOLD | Bias in Open-ended Language Generation Dataset | 23,679 prompts | Bias Evaluation | [Link](https://huggingface.co/datasets/AlexaAI/bold) |
| Mathematical Reasoning | GSM8K | Grade school math word problems | 8.5K training + 1K test samples | Math Word Problems | [Link](https://huggingface.co/datasets/openai/gsm8k) |
| Mathematical Reasoning | MATH | Advanced mathematics problems | 12,500 problems | Advanced Math | [Link](https://github.com/hendrycks/math) |
| Mathematical Reasoning | ASDiv | Elementary math word problems with detailed annotations | 2,305 problems | Math Word Problems | [Link](https://github.com/chaochun/nlu-asdiv-dataset) |
| Reasoning | CSQA | Commonsense Question Answering | 12,102 questions | Commonsense Reasoning | [Link](https://github.com/jonathanherzig/commonsenseqa) |
| Reasoning | StrategyQA | Yes/No questions requiring multi-hop reasoning | 2,780 examples | Strategic Reasoning | [Link](https://github.com/eladsegal/strategyqa) |
| Pattern Recognition | Letter | Last letter concatenation task | 100K examples | Pattern Recognition | [Link](https://huggingface.co/datasets/ChilleD/LastLetterConcat) |


### Additional Dataset Resources and Repositories

- [AwesomeLLMsDatasets](https://github.com/CAIRI-China/AwesomeLLMsDatasets) - A curated list of high-quality datasets for Large Language Models (LLMs) training and evaluation. Thanks to CAIRI-China for maintaining this comprehensive collection.






