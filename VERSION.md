# Version


# TODO 
  - Android 10 버전으로 변경된 부분 해결 [관련링크](https://developer.android.com/about/versions/10/behavior-changes-10?hl=ko)


# 1.2.08 (2020-10-05 23:23) beta
  - 앨범에서 영상클릭 시 죽는 버그 수정(10/5 완료)
  - 자동재생 시 "이전영상" "현재영상" 으로 텍스트 표시(10/5 완료)
  - keypoint 영상과 함께 db 에 저장(10/4 완료)
  - 앨범에서 마지막으로 본 영상 표시(10/4 완료)
  - 녹화 후 자동재생 play sleep x0.5 로 수정(10/4 완료)
  - 앨범에서 영상 간 간격표시(10/4 완료)
  - thumbnail 관련 deprecated 수정, PlayerActivity(10/4 완료)


# 1.2.05 (2020-09-12 1am) beta version release
  - 버그 해결 
    - PlayerActivity.java – line 2 / ai.golf.carry.PlayerActivity.togglePlay / 비정상 종료 (9/12 완료)
    - Preview.java – line 73 /ai.golf.carry.camera.Preview.startPreview / 비정상 종료 (9/12 완료)
    - **노트10, 노트10+, S20 에서 죽는 문제인지는 확인해봐야함.**
  - 녹화 후 자동재생 video1: 전전 영상 ,  video2: 전 영상 (9/12 완료)




# SOME VERSION
  - 리스트 당겨서 새로고침 정도 조절 (5/9 완료)
  - 앨범에서 스크롤 다운했을 때 상단 바 숨김 (5/9 완료)
  - 녹화화면에서 밝기조절 (5/12 완료)
  - 녹화화면 필드모드
  - 메인에 유튜브 컨텐츠 삽입 (5/18 완료)
  - 메인 내 영상 표시 방식 변경 (진행중)
  
  - 영문버전 출시 (번역필요: 앱 내, 구글플레이 소개문구, 캡쳐 이미지, 영상)
  - 프로필 이미지 표시 방법 결정 후 수정 ( 아이콘/로고/(+)내이미지 )
  
  
# 1.2.00 (2020-05-05 1am)
  - 영상에 태깅 기능
  - 앨범에서 태그로 필터 기능
  - 문의하기 기능
  - 이용약관/공지사항을 git markdown 으로 관리
  - 녹화화면 튜토리얼 변경
  - 메인/설정/재생/비교/화면 UI 변경
  
  - 몇몇 activity 제거하고 공통 fragment 로 수정
    

# TODO LIST
    
  - TODO : 옵션으로 녹화 완료 시 플래쉬 한번 깜박이기
  - TODO : 소스정리 
  - TODO : 녹화완료 후 자동재생 (미러링 세로로 나오도록?)
    

## 이전 업데이트 내역

# 1.1.06 (2020-03-25 1am)
  - 촬영 화면에서 저장된 영상의 썸네일 표시 ( 3/21 완료 )
  - 재생화면에서 두번터치로 굿샷 태그 설정 ( 3/21 완료 )
  - Main목록에 굿샷태그 표시 ( 3/21 완료 )
  - Low battery 표시 ( 3/21 완료 )
  - 설정에 배터리 절전모드 ( 3/21 완료 )
  - 영상 재생화면 UI 변경
  
  - 1.1.05 에서 비정상종료 NullPointerException 수정 ( 3/16 완료 )
  - 영문버전에서 내경험입력 화면 죽는 버그 수정 ( 3/18 완료 )
  - 촬영도중 홈화면으로 나갔을 때 모델실행하는 버그 수정 ( 3/21 완료 )
  

# 1.1.05 (2020-03-14 3am)
  - admob 계정 변경 ai.golf.carry
  - record 화면 tutorial 표시 위치 맞춤
  
---
  
# 1.1.04 (2020-03-13 5pm)
  - firebase Crashlytic 추가 ( 3/12 완료 )
  - 비교보기화면 일부폰에서 간혈적 멈춤 현상 수정 ( 3/12 완료 )
  - firebase .json 재반영 ( 3/13 완료 )
  - 사이즈 최적화로 apk 크기 50% 줄임 ( 3/13 완료 )
  - 앨범 no data text 표시 ( 3/13 완료 )
  
---
  
# 1.1.03 (2020-03-12 3am)
  - admob 계정 변경 carryadmob ( 3/11 완료 )
  - 녹화 가이드 팝업에서 원 위치 일부 폰에서 맞지 않음. ( 3/12 완료 )
    > 화면 높이와 하단 기본 navigation bar 의 높이를 폰마다 분리하는 방식이 다름.. (~~개고생~~)
  - 업데이트 알림 방식 변경. ( 3/11 완료 )
    > 플레이스토어의 출시노트에서 정보 조회  
    > 버전은 다음과 같이 작성 : update-version : [여기에버전]  
    > 알람은 다음과 같은 문구가 있어야함 : [notice]  
  - 버그 수정
    > 재생화면 마지막 영상 삭제 시 IndexOutOfBoundsException 수정 ( 3/11 완료 )  
    > Media player IllegalStateException 처리 ( 3/11 완료 )

---

# 1.1.02 (20-03-10)
  - splash 화면에 현재 버전표시 ( 3/10 완료 )
  - S20 또는 LG 에서 녹화 시 RGB 값 오류 수정 ( 3/10 완료 )
  - main list 당겨서 refresh ( 3/10 완료 )
  - "Ready" 여성/남성 목소리 추가. 설정화면 ( 3/10 완료 )

---

# 1.1.00 (20-03-09)
  - carry folder 의 동영상 싱크. 앱 최초 실행 시 ( 3/8 완료 )
  - 전면광고 ( 5건이상 녹화 후 종료 후, 비교 재생 후 toggle 방식 ) ( 3/8 완료 )
  - 싱글 플래이 재생속도 기능 추가 ( 3/8 완료 )
  - 앱에 통계 추가. firebase ( 3/8 완료 )
  - 앨범에서 삭제->취소 기능 버그 수정 ( 3/8 완료 )
    
---

# 1.0.7 ~ 1.0.9 (20-03-07)
  - 업그래이드 후 리스트 초기화 현상 수정
  - 버그 수정 (테스트 코드 미삭제 부분 제거)
    
---

# 1.0.6 (20-03-05)
  - 메인 리스트에 배너광고추가
  - smart_banner, 10초마다 reloadAd, mainActivity가 background일 때 reload 안함.
    
---

# 1.0.5 (20-03-04)
  - 프로덕션 배포 최초 버전.
  - include model file using encryption
  - https://play.google.com/store/apps/details?id=ai.golf.carry


    


    
    
