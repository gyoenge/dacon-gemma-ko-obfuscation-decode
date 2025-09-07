# DACON Restoring Obfuscated Korean Review   
## gemma model 

- Event: DACON Korean Review Obfuscation AI Competition (February 2025)
  [DACON Competition Link](https://dacon.io/competitions/official/236446/overview/description)
- Theme: Developing an AI algorithm to reconstruct obfuscated Korean reviews into their original form
- Idea: **LoRA fine-tuning of beomi/gemma-ko-7b model** on the given training dataset
- Individual participation, My best score : 0.67534

### Preview 

<p align="center">
<img width="60%" alt="dacon_koreview_decode_mockup" src="https://github.com/user-attachments/assets/7577cb85-d6f7-4fc8-81da-51d858ba4603" />
</p>  

### Description 

#### GPU environment 

- We utilized runpod.io cloud service 
- H200 SXM (train) + RTX 4090 (inference) + A40 (aug, test, etc)

#### Code description 

- dataset : `train.csv`, `trains_augmented_1,2.csv`, `test.csv`
- submition file : `sample_submission.csv`, `submission.csv` 

- baseline code : `baseline.ipynb`
- finetune code : `finetune_1,2,3.ipynb`
- data augmentation code : `augmentation_1,2.ipynb`
- inference code : `inference.ipynb`

- weights : `lora_adapter_7b/`, `lora_adapter_7b_2/`, `lora_adapter_7b_3/`

- test code : `tests.ipynb`
- finetune hyperparameter & score recode : `finetune_recode.csv`
