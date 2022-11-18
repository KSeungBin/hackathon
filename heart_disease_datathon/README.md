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
  
## Project Description
![HDAI-01](https://user-images.githubusercontent.com/90584177/202715255-5767174c-c8fa-4baa-8685-c06decc8a211.png)  
  
![HDAI-02](https://user-images.githubusercontent.com/90584177/202715327-e715131a-9a27-450a-9aa5-a77ed790d020.png)
  
![HDAI-03](https://user-images.githubusercontent.com/90584177/202715397-8033aa91-e8f7-4049-8963-413184afa5d5.png)  
  
![HDAI-04](https://user-images.githubusercontent.com/90584177/202715455-1c4bd95a-5c1b-4d62-b971-88f62dd3dd8b.png)  
  
![HDAI-05](https://user-images.githubusercontent.com/90584177/202715549-7a61b538-526c-42c6-ba52-381ca14ab583.png)
  
![HDAI-06](https://user-images.githubusercontent.com/90584177/202715576-c897391e-b3e3-4e0e-b8f6-fdfec6f3a616.png)  
  
![HDAI-07](https://user-images.githubusercontent.com/90584177/202715620-0db71857-db63-4770-acf0-c0f1339de220.png)  
  
![HDAI-08](https://user-images.githubusercontent.com/90584177/202715666-cbd87c23-57f2-4e93-9ed2-00274731ada5.png)  
  
![HDAI-09](https://user-images.githubusercontent.com/90584177/202715697-8ba55dd3-9776-4c8a-be78-1af19273d6ac.png)  
  
![HDAI-10](https://user-images.githubusercontent.com/90584177/202715733-fef5d6d2-9f25-41c5-b349-5a465caa326f.png)