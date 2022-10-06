# montage_project
이미지 분류 모델 구축하기
https://www.notion.so/wew1202/3-fd4156cf77c844e5a7d12a8e064ebdee



- montage_preproess.ipynb : 전처리
- montage_CNN,RESNET50.ipynb : CNN 으로 age,gender,hairstyle,face classfication
- montage_RESNET50_0.ipynb : RESNET50 으로 age, hairstyle 0번째 방법으로 classfication
  - 0.전처리 + 헤어스타일 라벨 5개 + 증강(32089개)  = 0.66
- montage_RESNET50_1.ipynb : RESNET50 으로 hairstyle 1번째 방법으로 classfication
  - 1. 전처리+ 헤어스타일 라벨 3개 + 증강x(8701개) =0.67
- montage_RESNET50_2 : RESNET50 으로 hairstyle 2-1번째 방법으로 classfication
  - 2.전처리 + 헤어스타일 라벨 3개 + 증강(32089개) =0.70
- montage_RESNET50_7.ipynb : RESNET50 으로 hairstyle 7번째 방법으로 classfication
  - 7. 전처리 + 헤어스타일 라벨 5개 + 증강(21757)+ 콜백(p=2,c=에폭,텐서보드,lr=reduce)
