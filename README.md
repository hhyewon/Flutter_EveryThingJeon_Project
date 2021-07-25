# 📌 Flutter_EveryThingJeon_Project
> 교내 모바일 학생증 제작 Project

## Goal
- 편리한 학교 생활을 위한 모바일 학생증 제작하기 (With. fultter)

## What is it?
- 모바일 학생증이 마련되지 않아 매번 학생증을 지참하고 다녀야하는 불편함을 개선하기 위해 제작하였습니다.
- 학교 생활에 익숙치 않은 신입생 및 학교 관계자에게 도움을 주고자 제작하였습니다.
- 교내에 학생증이 필요한 모든 서비스를 앱으로 대체할 수 있도록 제작하였습니다.
- 모두가 편리하게 사용할 수 있도록 UI를 구성하였습니다.


# 📌 panel
![image](https://user-images.githubusercontent.com/73240332/126888528-45920990-b065-4d2f-9bd1-7b3738b47af9.png)


# 📌 scenario
> 로그인
- 학교 홈페이지와 ID와 비밀번호를 연동하여 학교 홈페이지에 가입되어있는 학생이라면 누구나 별도의 회원가입 없이 로그인 할 수 있다.

> 메인화면
- 메인 페이지를 학생증과 동일하게 제작하여 프로필 사진, 이름, 생년월일, 소속 학과, 학번, 학적상태가 표시되게 한다.
- 도용방지선을 사용하여 움직이는 모바일 학생증만 유효하다는 문구를 추가해 다른 이용자가 해당 앱을 캡처해서 사용할 수 없도록 제한한다.
- 실제 학생증의 바코드를 그대로 사용하여 실물 학생증과 모바일 학생증을 구분하여 사용해야 하는 불편함이 발생하지 않도록 한다.

> 스터디룸, 독서실, 도서 예약
- 스터디룸, 독서실을 예약하기 위해 직접 방문 해야하는 불편함을 없애기 위해 실제 예약 시 필요한 장소 및 시간, 날짜를 입력 받도록 한다. 
- 원하는 자리를 선점할 수 없는 불편함을 없애기 위해 원하는 자리가 예약된 상태인지 확인할 수 있다.
- 도서 예약시에도 원하는 도서가 예약된 상태인지, 당장 대출할 수 있는 상태인지 표시해준다.
- 예약이 완료됐다면 상단에 예약정보가 표시된다.

> 공지사항
- 나의 할 일, 학사공지, 분실물 찾기를 표시해준다.
- 비대면 강의로 인해 유동적인 강의시간에 따른 힘들어진 스케쥴 관리와 많아진 과제들의 마감 기한을 따로 관리하기 힘든 점을 해당 앱으로 도움을 준다.
- 월, 일, 시간, 내용을 표시하여 관리한다.
- 학사공지의 경우 실제 학교 홈페이지 학사공지와 연동하여 사용한다. 
- 해당 카테고리의 더보기 아이콘(>)을 클릭하면 학교 홈페이지의 학사공지로 이동되도록 한다.
- 실제 학생들이 많이 이용하는 앱인 "에브리타임"의 자유게시판의 경우 분실물을 찾고 찾아주는 일이 빈번하지만 따로 분실물을 관리하는 카테고리가 존재하지 않는다.
- 해당 앱은 잦은 분실물에 대한 접근성을 위해 분실물 관리를 앱에서 진행한다.
- 잃어버린 사람과 찾아주길 원하는 사람 모두가 이용할 수 있도록 분실물 신고와 분실물 찾기를 나누어 이용할 수 있도록 유도한다.

> 위치
- "누구나" 이용할 수 있는 앱에 초점을 맞춰 제작한 페이지이다.
- 신입생들은 학교 지리가 익숙치 않아 수업 시간에 늦거나 가는 길을 몰라 번거롭게 지도 앱을 사용해 이동할 위치를 검색하여 이동하는 경우가 있다.
- 하지만 학교 내에서 다른 관으로 이동할 때 짧은 거리 이동으로 인해 제대로 경로가 표시되지 않거나 아예 경로가 검색되지 않는 경우가 잦다.
- 해당 앱은 "학교" 내의 위치만 관리하여 짧은 거리 이동을 중점으로 관리한다. 
- [현재 위치]에서 [이동하고자 하는 위치]를 설정하여 최적의 경로를 표시해주도록 한다.
- 또한 지도내에서 건물을 클릭하면 해당 관에 속한 과 등 건물에 대한 설명을 보여주도록 한다.
