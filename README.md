# 🧾 Brief Introduction to the notebook:
I've been having an amazing time with Prometheus 2 over the last few weeks, and I have a handy little notebook to give that should get your SFT distillation projects started with minimum computing (colab, T4, CPU).

In brief, Prometheus 2 is an open-source approach for assessing LLM generations. It has an influence on dataset distillation since, before, GPT-4 was required for valid judgments. 
This puts a price tag on your distillation endeavors. I'll provide some links in the comments that go into further detail.

📚 In the notebook, I start from an SFT dataset (openbmb/UltraInteract_sft ) and apply prometheus 2 evaluations to it for factual validity. 

🧑🏼‍🔬 You can also chose from pre-defined rubics like helpfulness, harmlessness, honesty, and reasoning, or define custom rubrics for your use case.

🐭 The notebook uses a quantized version of prometheus 2 run in llama.cpp.

⏲️ The generations and evaluation are pushed to Argilla for review, so you can review the pipeline whilst it's running.


