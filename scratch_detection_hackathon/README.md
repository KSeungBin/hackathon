# 2021 부품 품질 검사 영상 AI 학습데이터 해커톤 우수상
```diff
Object Detection, Classification, Segmentation 3단계 모델을 거쳐 선박, 자동차 등의 대형물에 대한 흠집 탐지
```

## File Description
1. make_yolo_datasets.ipynb: build image and annotation datasets
2. train_yolov5.ipynb: train YOLOv5 on our dataset
3. yolo_model_inference.ipynb: enter weight and image path in 'inference' function 
4. build_dataset_for_cls_seg.ipynb: build datasets for classification and segmentation
5. detected_image_classification.py: train and test classification model
6. model > unet.py: DoubleUNet = tuning UNet + apply Double Loss Function
7. data_analysis_for_segmentation.py: train and test segmentation model
8. presentation > scratch detection_바다의 왕자_공모전 우수상.pdf: presentation material
     
  
## Project Description
1. YOLOv5 모델 학습으로 바운딩 박스 자동 생성 후 불량으로 예측되는 영역 추출
2. EfficientNet 모델 학습으로 바운딩 박스 안의 이미지에 대한 정상/불량 여부 판정
3. UNet의 커스텀 모델인 DoubleUNet 모델 학습으로 불량으로 판정된 이미지에 대해 흠집이 있는 부분을 세밀하게 탐지
4. 제품 공정이 마무리된 후에 불량품을 선별해 다시 제품을 해체하는 역방향의 공정은 부품의 품질을 저하시키고, 산업 재해의 위험성을 높임
5. 위와 같은 비효율을 줄이는 모델을 개발함으로써 해커톤에서 우수상을 수상함  
     
<img src="https://user-images.githubusercontent.com/90584177/202718837-db8c7327-8f0b-4645-ae96-8b9be10bf742.png" width="400" height="600"><img src="https://user-images.githubusercontent.com/90584177/202718866-29b074af-a0bc-4b7b-809b-b11345e1113d.jpg" width="400" height="600">  
