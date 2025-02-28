## dacon-gemma-ko-obfuscation

: dacon "난독화된 한글 리뷰 복원 AI 경진대회" 
(https://dacon.io/competitions/official/236446/overview/description)

- my best score : 0.67534
- env : (runpod.io) H200 SXM (train) + RTX 4090 (inference) + A40 (aug, test, etc)

### description 

- dataset : train.csv, trains_augmented_1,2.csv, test.csv 
- submition file : sample_submission.csv, submission.csv 

- baseline code : baseline.ipynb
- finetune code : finetune_1,2,3.ipynb
- data augmentation code : augmentation_1,2.ipynb
- inference code : inference.ipynb

- weights : lora_adapter_7b, lora_adapter_7b_2, lora_adapter_7b_3

- test code : tests.ipynb
- finetune hyperparameter & score recode : finetune_recode.csv
