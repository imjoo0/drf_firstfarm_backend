### 💡 프로젝트명
### 첫농 
<br>

① 아이디어  : 위치 기반 실시간 추천 연결 

② 아이디어  : 체험 카테고리 (시골 한달살기, 리틀포레스트체험 등)
농촌의 삶을 잠시 체험하고싶은 사람과 노동력을 제공 받고 숙소/식사를 제공해줄 농가를 연결 

③ 아이디어  : 단체 카테고리: 농가,지자체와 학교/동아리/단체 사이를 연결 (예비)
<br><br>
### 💡 아키텍처
#### - 사용 기술
    
    Python, Django, DRF
    
#### - 개발 환경
    - 웹 개발 환경
        - django_restframework
        - python
        - vsc **or** pycharm
    - 인공지능 개발 환경
        
        파이참
        
#### - 디자인
    - 색상 선택
    
    [Color Palette: #9EB23B #C7D36F #FCF9C6 #E0DECA - Color Hunt](https://colorhunt.co/palette/9eb23bc7d36ffcf9c6e0deca)
    
    [Color Palette: #FCF8E8 #94B49F #ECB390 #DF7861 - Color Hunt](https://colorhunt.co/palette/fcf8e894b49fecb390df7861)
    
<br><br>

### 💡 기능


#### 1. 로그인 / 회원가입 
    - 회원가입, 로그인
        - 소셜 로그인
        - 실패 시, 안내문구 삽입
        - 농가가 로그인 했을 때 / 참여자가 로그인 했을 때 구분 카테고리 필요
    - 로그아웃 기능
    
#### 2. Introduce 페이지
    - 페이지 소개 글 ( 이용설명 )
    
#### 3. 위치기반, 사용자 성향 기반 추천 페이지  (로그인 해야만 접근 가능)
    - 위치 기반 추천
    - 사용자 성향 기반 추천

#### 4. 지역별 검색 페이지  
    - 지역별 내용 검색

#### 5. 상세 페이지
    - 상세정보 나오기
    - 신청하기 (팔로우) (로그인했을 때만 가능 (로그인 시 활성화:hide/show))
    - 별점, 리뷰 보여주기
    - 길찾기 (네이버지도 연동)
    
#### 6. 첫농 생활 찾기 페이지
    - 여행지 검색
    - 검색 결과
    - (예비) 추천루트
    
#### 7. 마이페이지 (로그인 해야만 접근 가능)
    - 등급 정보 보여주기
    - 내가 간 일자리 보여주기
    - 내가 쓴 후기  보여주기
    - 개인정보 수정
    - 후기 작성 (팔로우 되어있어야만 가능)
    
#### 8. 공고 등록 페이지 (농장 사용자가 로그인 해야 접근 가능)
    - 공고 등록 기능
    
<br><br>
---


### 💡 와이어프레임
![Frame_1](https://user-images.githubusercontent.com/104473472/178113322-0c5da88b-c4f3-4bbf-b1cf-c48ed17eb59d.png)

