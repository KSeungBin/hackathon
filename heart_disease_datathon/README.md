# Heart Disease AI Datathon(21.10.27 ~ 21.12.07)
```diff
A2C, A4C VIEW에서의 좌심실 분할 AI 모델 개발
```

## File Description
1. confirm_A2C.ipynb: print DSC, JI of A2C image dataset
2. confirm_A2C_to_mask.ipynb: print DSC, JI of A2C mask dataset
3. confirm_A4C.ipynb: print DSC, JI of A4C image dataset
4. confirm_A4C_to_mask.ipynb: print DSC, JI of A4C mask dataset
5. unet_a2c.py: DoubleUNet = fine-tuning UNet + apply Double Loss Function  
  
※ DSC = 2TP / (2TP + FP + FN)  
※ JI = DICE / (2-DICE)  
  
