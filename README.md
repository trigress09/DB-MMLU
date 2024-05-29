# Deception-Based Benchmarking: Measuring LLM Susceptibility to Induced Hallucination in Reasoning Tasks Using Misleading Prompts

This is the repository for [Deception-Based Benchmarking](https://www.google.ca) by Rukun Dou. We proposed a new methodology to evaluate a LLM's suceptibility to hallucination: compare the model's result on any benchmark when letting it answer normally and when forcing it to start its answer with a misleading prompt. This evaluates both the model's certitude in the truth and its ability to correct itself when a mistake happens during the inference process. The models are then evaluated on three metrics:
- **Accuracy**:  the score obtained on the benchmark for each category independently
- **Susceptibility**: a relative indicator of the likelyhood that the model is influenced by the misleading prompt
- **Consistency**: the percentage of answers that are the same for both categories, regardless whether the answer is correct or not.

![A diagram illustrating the process of DB Benchmarking](diagram.jpeg "DB Benchmarking Process")

We created a new dataset derived from [MMLU](https://arxiv.org/abs/2009.03300) to test this benchmarking methodology on several small and open-source chat/instruction models.

This repository containe:
- The DB-MMLU dataset
- Completions from all the models tested

### Results

### Contact

### Citation
