# KUIAI_hackathon
🏆 교내 해커톤 - 이미지 기반 패션 인플루언서 추천 알고리즘 설계
Image-based fashion influencer recommendation algorithm

🏆  **우수상**  

## 💻프로젝트 소개
1) 2022 고려대학교 , 한국산업기술진흥원(KIAT), 한국전자기술연구원(KETI) 공동개최 해커톤
2) 주제 : 의류 제조사와 개별 소비자를 대상으로 패션 인플루언서 추천 플랫폼 구축

- **작업기간** : 2023.01.16 ~ 2023.01.20
- **투입인원** : 4명 (14기 구은아, 김유민 김태영, 김혜림)
- **스킬 및 사용툴** `python`

<br>

## 사용 데이터
- 스타일 기반 이미지 데이터 (23개의 하위 패션스타일 카테고리로 분류)
- 인스타그램 인플루언서 게시물 데이터


## 배경

- 패션 산업에서의 추천시스템은 ‘사용자-제품' 쌍의 추천으로 개인의 성향 분석에 초점되어 있음
- 최근에는 패션 제품 제조사 및 소비자는 SNS의 인플루언서를 통해 정보를 탐색하는 경향 O
- 따라서 목표 : 패션 상품 정보 및 소비자 정보를 기반으로 제조사 OR 개인 소비자에게 맞춤형 인플루언서를 제안하는 추천시스템을 제작해보자


#### TASK 1. 이미지 분류 모델링
- 스타일 분류를 위한 모델링
- Model : Resnet / Accuracy : 0.4133


#### TASK 2. 인플루언서 스타일 분류
- 동일 모델로 인플루언서 스타일 분류 진행
- 이후, 좋아요 개수가 가장 높은 인플루언서의 스타일로 추천 제공
- 성별 및 사이즈를 반영하여 최종 알고리즘 설계

#### Task 3. 게시글 텍스트 기반 인플루언서 키워드 추출

#### Task 4. 프로토타입 구현

<img width="563" alt="image" src="https://github.com/miniminii/KUIAI_hackathon/assets/90626970/ed11c62d-a12c-41fc-af38-b15e3fed205b">






