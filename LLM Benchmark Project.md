## LLM Benchmark Dashboard/Visualizations

### Open source LLMs:

- bloom-176b 
- cerebras-gpt-13b, cerebras-gpt-7b
- chatglm-6b
- codegen-16B-mono, codegen-16B-multi
- dolly-v2-12b
- eleuther-pythia-12b, eleuther-pythia-7b
- falcon-40b, falcon-7b
- fastchat-t5-3b
- gpt-j-6b, gpt-neox-20b
- gpt4all-13b-snoozy

- llama-2-70b
- mpt-7b
- oasst-pythia-12b
- replit-code-v1-3b
- stablelm-base-alpha-7b
- starcoder-16b, starcoder-base-16b



### Data Sets/Benchmark

Common benchmarks include: 

- Chatbot Arena Elo
  - Users chat with two anonymous bots side by side and vote for the preferred one. 
- HellaSwag (few-shot)
  - Give llm models challenging commonsense questions. Can machines perform human level commonsense inference?
- MMLU (Massive Multitask Language Understanding)
  - including humanities, social sciences, and STEM. 
- LAMBADA
  - capabilities of models for text understanding by means of a word prediction task.
- HumanEval. 

Maybe the lab have different preferences on the datasets? Special tasks for llms? What are the evaluation criteria? (factual accuracy, coherence, relevance? model size? text size?)

### Computing Resources

Models require extensive computing power. For example, for bloom 176b, 

![image-20240305212320249](https://raw.githubusercontent.com/PhoebeCheng9911/image/main/img/image-20240305212320249.png)

Does the lab providing computing units? 

### Hosting Platform

GCP or AWS 

### Dashboard Front End

- https://github.com/AmaduKamara/leaderboard-app 

![image-20240305205939061](https://raw.githubusercontent.com/PhoebeCheng9911/image/main/img/image-20240305205939061.png)

### Goal

What's the deliverable for this project? A leaderboard showing different llm's perforamnce on benchmark dataset? 



### Reference

- https://github.com/LudwigStumpp/llm-leaderboard
- https://crfm.stanford.edu/helm/lite/latest/#/leaderboard