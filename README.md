# montage_project
이미지 분류 모델 구축하기

  <a href="https://www.notion.so/wew1202/2-62a3b8c8f5aa486facdd88e5c2a79dd6">![Notion](https://img.shields.io/badge/Notion-%23000000.svg?style=for-the-badge&logo=notion&logoColor=white)


### 주제 및 선정 이유

들어오는 손님 안면 데이터를 이용하여

나이,성별,헤어/ 얼굴형,눈썹

분류 모델을 만들자. →나이,성별,헤어를 이용한 마케팅 분석,마케팅 자료 사용


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
