# Play-With-Football

## 개요
- 축구 동호인을 위한 축구 매칭 경기장 예약 팀관리등을 위한 시스템을 만든다.
- MSA 구조로 여러가지 REST API를 만들며 서비스별로 다른언어를 활용하여 여러가지 언어를 학습한다.
- 다른 생활체육 종목도 추가 가능하도록 구조를 만든다.

## 서비스 
### 회원 java spring boot jpa
- 경기에 참가할 사용자
- 구글, 네이버, 카카오톡등 인증 사용
- 회원은 팀에 속할 수도 있고 아닐수도 있음(용병)
- 팀에 소속된 회원도 용병참가 가능
- 여러팀에 속할 수 있음..(?)
- 경기장 관리자...
### 팀 go gin
- 경기를 위한 팀 관리
- 팀별 선수 관리
- 팀별 회비 내역 관리
- 선수 등번호
- 팀총무, 회장등 설정 여러명 가능(팀관리자)
### 경기장 node express
- 경기장 관리
- 경기장 시간별 사용 신청
### 경기결과 python flask
- 선수별 팀별 경기 결과 기록
### 경기 매칭 추천
- 이건 추후..
- 비슷한 실력, 시간대, 장소에서 경기하는 팀 추천
