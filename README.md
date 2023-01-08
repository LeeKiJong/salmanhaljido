![image](https://user-images.githubusercontent.com/52438368/195626643-c52b4fc1-4eac-4cf2-9b47-6ce773432e8d.png)
## 목차
[1. 서비스 소개](#1-서비스-소개)  
[2. 주요 기능](#2-주요-기능)  
[3. 기술 스택](#3-기술-스택)  
[4. 시스템 구성도](#4-시스템-구성도)  
[5. 실행 방법](#5-실행-방법)  
[6. 팀원 소개](#6-팀원-소개)  

# 1. 서비스 소개
<img src="https://user-images.githubusercontent.com/52438368/211190426-b197ef48-cde6-4104-8658-44b91a5106e3.png" height="300px" />  

**살만할지도**는 신혼부부를 위한 주거 지역 추천 서비스 입니다.  
신혼부부가 주거 지역을 고를 때 해당 지역을 직접 가보기에는 시간과 정보가 부족하기 때문에 인터넷에 의존적이라는 문제점에 착안하여 쉽고 편하게 이용할 수 있는 웹 서비스를 개발하였습니다.  
좋은 주거 환경을 찾고 있거나 기호에 맞는 주거 지역을 구하는 신혼부부들이 사용할 수 있습니다.  

📊 [노션 바로가기](https://cumbersome-eel-2ce.notion.site/bedc7f705856408e9b5bb121a7af4389)  

🎞 [실행 영상 다운로드](https://github.com/LeeKiJong/salmanhaljido/raw/master/Project%202.avi)
### 📆 프로젝트 기간
2022년 8월 29일 ~ 10월 14일 (약 7주)  
프론트 3명, 백엔드 2명
# 2. 주요 기능
### ✅ 카테고리 추천 기능
사용자 유형을 선택하면 비슷한 환경의 사람들이 선택한 카테고리를 추천해주는 기능 입니다.  
기혼, 자가용, 반려동물, 자녀 유무를 선택하면 검색 횟수 기준과 평점 기준 중 원하는 것을 골라 추천받을 수 있습니다.
<img src="https://user-images.githubusercontent.com/52438368/195627044-56c12e5f-443d-4d4a-93ee-da201fbb97b4.png" height="70px" />
![image](https://user-images.githubusercontent.com/52438368/211190426-b197ef48-cde6-4104-8658-44b91a5106e3.png)
![image](https://user-images.githubusercontent.com/52438368/211190578-f4e047c7-e396-4b76-b329-f97e46e39467.png)
### ✅ 주거 지역 추천 기능
지역, 선호하는 환경, 평균 전세/매매 가격을 설정하면 그에 맞춰 주거 지역을 추천해주는 기능 입니다.  
선호하는 환경은 카테고리 중요도를 선택함으로써 설정할 수 있습니다. 교통, 재난, 안전, 의료, 반려동물, 교육, 문화, 생활의 8가지 카테고리가 있으며 각각의 세부 카테고리에 대한 중요도를 상, 중, 하로 설정할 수 있습니다.  
최대 8개의 주거 지역을 시군구 단위로 추천해주며, 이에 대한 순위를 볼 수 있습니다. 각 지역의 8가지 카테고리에 대한 점수와 상세 데이터 또한 확인할 수 있습니다.

### ✅ 게시판 기능
임신/출산, 육아/교육, 생활/건강, 사회/정책, 부동산 관련 뉴스를 조회할 수 있는 기능 입니다.  
각 카테고리에서 신혼부부에게 유용한 정보를 확인할 수 있으며, 검색을 통해 원하는 뉴스만을 조회할 수 있습니다.

# 3. 기술 스택
## backend
### local
|intellij|jdk 11|spring boot|docker|
|:---:|:---:|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/52438368/195626893-c78d6450-04fc-4d25-b1f7-de3777ce55de.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195626943-e172849b-a81d-4584-9e94-a4c8275bae57.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195626992-13753380-523f-4f3e-8962-2da9c67f7ef7.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627001-da558b56-28a4-424b-8dea-199b0e740c5e.png" height="70px" />|
### server (ec2)
|docker|jenkins|nginx|mariaDB|MongoDB|apache spark|
|:---:|:---:|:---:|:---:|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/52438368/195627001-da558b56-28a4-424b-8dea-199b0e740c5e.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627021-b948587f-f8ce-47ba-ba55-242a5d12fdd9.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627044-56c12e5f-443d-4d4a-93ee-da201fbb97b4.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627063-c5152bf1-8aa5-4c75-8a13-eff91601d75c.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195972407-5d1dd93a-3ac6-4ef0-a2bf-cce62ca3f1c8.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627079-47a38a5d-7c67-470c-bea3-c9cc1b16b5a4.png" height="70px" />|
## frontend
|HTML|CSS|JavaScript|
|:---:|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/52438368/195627115-bc672bbb-001c-4e15-b603-8fd01fac12c1.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627130-8209c379-e1c2-4cc9-89fe-14d364823d9c.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627148-c8f95876-db67-479e-972b-6caaa74d1265.png" height="70px" />|

|React|Redux|Sass|Mui|Mapbox|
|:---:|:---:|:---:|:---:|:---:|
|<img src="https://user-images.githubusercontent.com/52438368/195627189-0cb77e7a-fb83-4ad2-ab3b-c5d559ed2cc6.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627207-614f859d-fcad-4683-a43e-fa5498b07085.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627227-55eff34c-f049-4b9b-9700-a326d10c2572.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627241-b4224add-7dc9-4601-9e6a-a56df61df90e.png" height="70px" />|<img src="https://user-images.githubusercontent.com/52438368/195627255-dc38bbb0-81b4-4dc9-b442-e71131b8b2a8.png" height="70px" />|

# 4. 시스템 구성도

![시스템_구성도](https://user-images.githubusercontent.com/52438368/211197354-f92ef83a-0474-46de-b32d-9ff8bff21f11.png)

# 5. 실행 방법
## backend
### CI/CD  
gitlab(back branch) push or merge -> jenkins webhook -> auto build  

### docker logs
![docker](https://user-images.githubusercontent.com/52438368/195627374-48f7e9e9-f1cd-49cf-813a-6bd8f6519a65.png)
```
docker logs
ex ) docker logs --tail 300 salmanhaljido_server_bluedocker logs --tail 300 salmanhaljido_server_blue
```

### 에러 대처 방법
path 에러가 발생할 경우 로컬 path로 변경 후 실행

src/main/resources/data -> local path

## frontend
1. 레포지토리를 clone 받는다.
```bash
git clone https://lab.ssafy.com/s07-bigdata-dist-sub2/S07P22D110.git
```
2. `front` 폴더에서 `package.json`에 정의된 모듈을 설치한다.
```shell
npm install
```
3. 환경 변수를 설정한다.
 - 이를 위해 [Mapbox API](https://www.mapbox.com)의 access token을 발급받아야 한다.
 - `front` 폴더에서 `.env` 파일을 생성하고 아래 내용을 기입한다.
 ```plain
 REACT_APP_MAPBOX_ACCESS_TOKEN={발급받은 Mapbox API access token}
 ```
4. 프로그램을 실행시킨다.
```shell
npm start
```

# 6. 팀원 소개
|김주영|박진경|이기종|이상민|이재영|
|:---:|:---:|:---:|:---:|:---:|
|front(팀장)|front|back|back(팀장)|front|
