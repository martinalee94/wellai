# [🧘](https://emojipedia.org/yoga/) WellAI(웰라이)
  *언제 어디서나 당신의 건강을 책임지는 AI 홈트 서비스, 웰라이*


## 1. 프로젝트 소개 ✅
### 1.1 서비스 개요 및 배경 <br>
- 코로나 19의 시간을 거치며, 건강에 대한 중요성이 증대 되고 다른 사람들과의 접촉을 최소화하기 시작했습니다. <br>
그리고 점차 ‘집'에서 할 수 있는 활동에 관심을 가지기 시작했죠. <br>
그 중에서 웰라이는 집에서 건강을 지킬 수 있는, 인공지능(Aritificial Intelligence, AI)을 적용한 스마트한 홈트레이닝'서비스에 집중했습니다.  <br>
'내가 잘 따라하고 있나?', '이 자세가 맞는 자세인가?'를 고민하고, 운동을 어려워 하는 사람들을 대상으로 합니다.<br> 
실시간으로 AI가 당신의 움직임을 파악해서 도식화로 표시하고, 순운동시간을 기록해 줌으로써 실질적인 피드백을 받아 가실 수 있습니다.<br>
'요가'는 특별한 운동 기구가 필요 없고, 정적이지만 근력 향상과 심신 수련에 많은 도움을 주는 운동이죠.  <br> 
심적으로, 체력적으로 어려운 시간을 겪고 있는 현대인들에게 웰라이가 새로운 운동 라이프를 열어 드릴게요:)

<br>

### 1.2 서비스 목표 
**집에서도 요가학원 수업을 듣는 것처럼 실시간으로 자세 확인을 받으며 운동할 수 있다.**
- 운동 자세 가이드 영상을 보면서 요가 자세를 따라할 수 있다.
- 웹캠을 켜고 요가 자세를 취하면 AI가 운동 자세를 체킹해 준다.
- 연간/월간 순수 운동 시간, 예상 칼로리 소모량(회원 정보에 등록된 신체 정보 기반)을 확인할 수 있다.
- 본인이 답변한 선호 운동 타입을 바탕으로 코스를 추천 받을 수 있다.
- 코스에 대한 후기를 남기고, 북마크 할 수 있다.
- 원하는 코스를 검색할 수 있다.(검색 기준 - 제목/해시태그)

<br>

## 2. 서비스 기능 소개 ✅
### 2.1 메인페이지
![main](https://user-images.githubusercontent.com/39133877/158135753-f7b9851d-5c1b-4837-9a5d-df4f59f1e701.gif)

### 2.2 메인 기능
#### 1. 실시간 요가 자세 체킹
  - 요가 자세 가이드 영상 반복 재생
  - 순운동시간, 자세 별 제한시간 존재
  - 정확한 자세로 운동 시, 순 운동 시간 카운트 시작 및 스켈레톤 색상 초록색으로 변경
  - 정확하지 않은 자세로 운동 시 스켈레톤 색상 회색으로 변경
  - 정해진 순 운동 시간 채우면 자동으로 다음 자세로 넘어감
  - 순 운동 시간을 채우지 못 한 경우, 각 자세별 제한 시간이 지나면 자동으로 다음 자세로 넘어감  

![exer](https://user-images.githubusercontent.com/39133877/158132314-216a8675-8984-41de-93d4-68f6352d1b7f.gif)

<br>

#### 2. 개인 운동 기록
  - 연간, 월간 운동 기록 리포트 제공
  - 순 운동시간, 소모 칼로리 기록
  - 유저 운동 기록 대시보드(그래프)로 시각화

![mypage](https://user-images.githubusercontent.com/39133877/158133707-bbca7d0b-975c-44c7-a531-6f6f4cf1208f.gif)

<br>

#### 3. 회원관리
  - 회원가입, 로그인, 로그아웃
  - 개인 정보 수정 가능

![signup](https://user-images.githubusercontent.com/39133877/158133493-0472669f-2f7f-49ea-868e-5db8f2a6c135.gif)


<br>

### 2.2 서브 기능
#### 1. 코스 리뷰 기능
  - 코스에 대한 평점 및 리뷰 등록
  - 본인 작성 리뷰 이력 조회(마이페이지) 및 삭제
  - 최신 순, 오래된 순, 높은 평점 순, 낮은 평점 순으로 정렬(기본값 최신순)

![review](https://user-images.githubusercontent.com/39133877/158133408-b3562598-f2c2-4883-af0d-2c796c00996d.gif)

<br>

#### 2. 코스 검색
  - 검색한 키워드를 기반으로 코스 검색

![search](https://user-images.githubusercontent.com/39133877/158132862-97f3752a-eebd-4be1-a616-d7bb23047189.gif)

<br>

#### 3. 코스 추천
  - 유저 선호 운동 타입 정보를 기반으로 코스 추천

![recommend](https://user-images.githubusercontent.com/39133877/158133182-363381a1-8140-4e17-91f6-b5b2ba5ac9f1.gif)

<br>

#### 4. 코스 북마크(좋아요)
  - 선호 코스 북마크 및
  - 북마크 코스 리스트 조회(마이페이지)

<br>

- **관련 문서**
  - [와이어프레임](https://www.figma.com/file/0FC6VjrVkBBflLS2iMMo8U/확정본)
  - [요구 명세서](https://unruly-space-e0e.notion.site/a1fd4e5741974262860677ff806af234)
  - [프로젝트소개서](https://unruly-space-e0e.notion.site/AI-3-WellAi-bc717739a2d84acb9cc16e1d264c9c4e)

<br>



## 3. 사용한 기술 ✅
| 파트 | 기술 |
| ------ | ------ |
| Management |  <img src='https://img.shields.io/badge/gitlab-%23181717.svg?style=flat-square&logo=gitlab&logoColor=white'></a> <img src='https://img.shields.io/badge/Notion-%23000000.svg?style=flat-square&logo=notion&logoColor=white'></a>  <img src='https://img.shields.io/badge/figma-%23F24E1E.svg?style=flat-square&logo=figma&logoColor=white'> |
| 인공지능(AI) | <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=TensorFlow&logoColor=white"/></a> <img src="https://img.shields.io/badge/Keras-%23D00000.svg?style=flat-square&logo=Keras&logoColor=white"/></a>|
| 프론트엔드 | <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=React&logoColor=white"/></a> <img src="https://shields.io/badge/TypeScript-3178C6?logo=TypeScript&logoColor=FFF&style=flat-square"/></a>|
| 백엔드  | <img src="https://img.shields.io/badge/Django-092E20?style=flat-square&logo=Django&logoColor=white"></a> <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=PostgreSQL&logoColor=white"/></a> <img src="https://img.shields.io/badge/Gunicorn-499848?style=flat-square&logo=Gunicorn&logoColor=white"/></a> <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=Nginx&logoColor=white"/></a> <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=Docker&logoColor=white"/></a> |

<br>

## 4. 시스템 아키텍쳐 ✅
<img src="https://user-images.githubusercontent.com/39133877/159164408-c53e9bbe-20ef-4520-85df-4abde01cb017.png" width="600px"></img>


<br>

## 5. 데이터셋 ✅
- 요가 이미지 데이터 셋
  - [Yoga-82: A New Dataset for Fine-grained Classification of Human Poses](https://arxiv.org/abs/2004.10362)
  - [Yoga Pose Image classification dataset](https://www.kaggle.com/shrutisaxena/yoga-pose-image-classification-dataset)

<br>

## 6. 프로젝트 팀원 소개 ✅
| 이름 | 포지션 | 담당 업무 |
| ------ | ------ | ------ |
| **이영숙** | 팀장 / 백엔드 / 디자인 | 1. 유저 DB 설계 및 API 개발<br> 2. Docker 및 NGINX 배포 관리<br> 3. git submodule 레포지토리 관리<br> 4. 전체 서비스 페이지 디자인 <br>  |
| **최영훈** | 백엔드 | 1. 코스 DB 설계 및 API 개발 <br> 2. Docker 및 Gunicorn 배포 관리<br> 3. DB 데이터 삽입 및 생성|
| **김한예슬** | 인공지능 | 1. 인공지능 서비스 초기 기획,조사<br> 2.데이터 수집, 전처리, 모델로 전처리, 모델링, 모델 평가 및 선택<br> 3. 클라이언트 사이드 모델로 변환 및 경량화<br> 4. 메인 서비스 테스트 및 메인 서비스 테스트 코드 작성|
| **강경욱** | 프론트엔드 | 1. 마이페이지 구현 <br> 2. 실시간 영상 처리 서비스 구현 <br> 3. 토큰 플로우(access/refresh) 구현 |
| **홍준형** | 프론트엔드 | 1.회원가입 페이지 / 코스 페이지 구현<br> 2. 회원가입 / 코스 / 마이페이지 API 연동 |



<br>


## 7. 실행 방법 ✅
###### Backend
```
docker-compose up
```
###### Frontend
```
npm install
npm start
```
