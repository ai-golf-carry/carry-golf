# CarryGolf

- [버전관리](/VERSION.md)


### Android Google play 개인정보취급방침
- [보기](/docs/private.txt)




---

# Open Carry

## youtube_v2.json 설명
CarryShotYoutubeJson python project 에서 make_json.py 를 실행하면    
json string 이 clipboard 에 copy 됨.   
이걸 youtube_v2.json 의 내용으로 붙혀넣기 하면 됨.   


- app 에서는 youtube_v2.json 을 보고
- python project 에서는 youtube.json 을 봄.
- **두 파일 모두 삭제하면 안됨**


## youtube.json 설명
**신중하게 수정할 것! 잘못 수정하면 앱에서 오류발생!**
```java
[
  {
    'lang':'ko',  /* 언어별 유튜브 리스트 */
    'list':
      [
        {
          'title':'당신을 위한 추천 레슨', /* 유튜브 목록 타이틀 */
          'playListId':'PL2KtS99uNp9V0MV2eJsDh_Yfmf5lscI-d',  /* 재생목록 ID */
          'channel':'' /* 채널 ID */
        },
        {
          'title':'박연습',
          'playListId':'PLVpetxH4Pz5tI7HDje4IVtRaZSwliogk_',
          'channel':'UC6sVX_-lnuq8LqsD7Lp4WMg'  /* 채널 ID 가 있으면 playListId 는 무시하고 채널의 모든 동영상을 view 많은 순으로 보여준다 */
        }
      ]
  },
  {
    'lang':'en',
    'list':
      [
        {
          'title':'당신을 위한 추천 레슨',
          'playListId':'PL2KtS99uNp9V0MV2eJsDh_Yfmf5lscI-d',
          'channel':''
        },
        {
          'title':'박연습',
          'playListId':'PLVpetxH4Pz5tI7HDje4IVtRaZSwliogk_',
          'channel':'UC6sVX_-lnuq8LqsD7Lp4WMg'
        }
      ]
  }
]
```

## tiktok.json 설명
  - order : 순서
  - name : 앱에서 보여질 텍스트
  - tag : 실제 검색할 텍스트

