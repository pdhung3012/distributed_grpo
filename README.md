# distributed_grpo

In this code, we attempt to test the GRPO training by following steps:

1. Download the input datasets and sample lora adapter models.
2. Replace DPOConfig and DPOTrainer with corresponding GRPO APIs in the grpo_dist.py.
3. Running the updated code with arguments provided in grpo_run.sh script.
   - You need to change the locations of datasets/ fine-tuned models to your local locations.
   
