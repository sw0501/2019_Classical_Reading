2019_Classical_Reading
======================
***
<2019 Interface Programming Exhibition - 고전독서 모의테스트 어플리케이션 개발>
***
2019년도 인터페이스 프로그래밍 전시회 고전독서 모의테스트 프로젝트 입니다.\
JAVA를 기반으로 안드로이드 어플리케이션을 제작하여 실제 Google Play Store에 게시하는 것을 목표로 합니다.\
JAVA에 대한 충분한 이해를 위해서 JAVA스터디와 주마다 정기적으로 회의 및 추가적인 스터디를 진행합니다.\
참여하는 팀원들이 안드로이드의 기초적인 지식들을 습득하고 오픈소스를 충분히 이해해서 다룰 수 있게 진행됩니다.\
개발기간은 8월 중순부터 12월 중순까지 진행됩니다. 시험기간 2주전부터는 회의와 스터디는 진행하지 않습니다.

# Member
### 팀장 주이식 - 총괄 개발, Github 관리, 스터디 진행
##### 팀원 박상욱 - 데이터베이스팀 개발, 기획
##### 팀원 김정연 - 위젯팀 개발
##### 팀원 백지오 - 위젯팀 개발
##### 팀원 최정민 - 부가기능팀 개발
##### 팀원 함유진 - 푸시 알림팀 개발
##### 팀원 황예원 - 푸시 알림팀 개발


# Application name: 고전독서 모의테스트

<개발목표>
----------
세종대학교 학생들의 고전독서 인증을 돕기위해 시험을 보기전 미리 테스트를 해볼 수 있는 모의테스트 어플을 개발한다.\

<개발에 필요한 기능>
-------------------

### 데이터베이스 사용 (이식,상욱)
* 자주 틀린 문제 -> 모든 사용자가 자주 틀린 문제와 내가 자주 틀린 문제를 정렬
* 내가 틀린 모든 문제
* 문제풀이
  - KeyWord: Youtube -> 안드로이드 스튜디오 수강신청 도우미 프로젝트 3강 - 회원 데이터베이스 구축  
            googling -> 안드로이드 PHP 통신 
### 푸시 알림 (예원,유진)
* 예약날짜확인, 주의사항 -> 알림을 사용해서 시험보는 날짜와 주의사항들을 전달
  - KeyWord : 안드로이드 GCM 푸시알림 구현 
* 출제된 시험문제 피드백 -> 시험횟수가 일정 횟수를 넘길때마다 출제된 문제에 대해 제보할 수 있게 알람을 줌
  - KeyWord : 안드로이드 GCM 푸시알림 구현 
### 일반적인 기능
* 줄거리
* 책 난이도
* 오류 및 문의사항
### 파싱(parsing)
* 독서경시대회 정보
* 인증예약(추후개발)
* 고전독서에 도움되는 사이트(추후개발)
### 위젯 (정연,지오)
* 날짜확인 위젯  
  - KeyWord : 안드로이드 홈 스크린용 위젯 만들기
* 자주틀린 문제 위젯 -> 자주 틀린 문제를 한문제씩 위젯에서 풀 수 있게 제공
  - KeyWord : 안드로이드 홈 스크린용 위젯 만들기, 위젯 기능구현 
### 부가기능 (정민,이식)
* 탭  
  - KeyWord : 안드로이드 네비게이션 드로어  
* 책 검색 및 즐겨찾기  
  - KeyWord : 안드로이드 액션바(툴바)에 검색기능 구현하기, EditText를 이용해 리스트뷰 검색기능 만들기  


<사용한 Open Source 목록>
------------------------

<참고한 문서 및 사이트>
-----------------------

정연
* 버튼만들기 + 인터넷 연결 : https://roddong.tistory.com/248
* 토스트 버튼 : https://roddong.tistory.com/247 
* 새 화면 띄우기 : https://roddong.tistory.com/253

상욱
* 버튼 생성 및 토스트 : https://redmuffler.tistory.com/425
* 버튼을 이용해 웹 페이지 띄우기 : https://hongku.tistory.com/205
* 버튼을 이용해 다음 화면 호출 : https://hongku.tistory.com/206
* 안드로이드 인터넷 퍼미션 : https://slobell.com/blogs/48


유진
* 버튼과 화면 전환 : https://blog.naver.com/bdh0702/221582338501
* 인터넷 연결과 토스트 띄우기 : https://m.blog.naver.com/PostView.nhnblogId=sks6624&logNo=150173583155&proxyReferer=https%3A%2F%2Fwww.google.com%2F

<주차별 진행사항>
-----------------
사전준비(8월 18일): 안드로이드 개발을 위한 기초 JAVA강의 + 깃허브 강의, 어플리케이션 기획 및 개발시 필요한 사항 정리\
1주차(8월 25일): 버튼만들기 과제체크, 파트 나누기, 프로젝트 목표에 대해서 설명
2주차(9월 17일): 파트 나누기 마무리, 프로젝트 진행에 대한 회의(격주로 오프라인 회의 진행, 매주 일요일마다 PR로 파트별 진행사항 보고)
