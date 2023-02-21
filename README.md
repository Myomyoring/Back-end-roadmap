# Back-end-roadmap 따라가기🪴
## 참고용 로드맵
[2023 제로베이스 로드맵](https://zero-base.co.kr/event/media_BE_school_roadmap)   
[2023 제로초님 백엔드 로드맵](https://drive.google.com/file/d/1_9zjALIVisho4xIZzmU9W6NIam14UHrX/view)   

---
🔽 출처 : https://imsoncod.tistory.com/24   
🔽 원본 : https://roadmap.sh/backend
<br>

![백엔드 로드맵](https://blog.kakaocdn.net/dn/bq03dY/btrnCzNDlUE/EQPcSTH1TGR50KCBsnC5K1/img.png)

---

## Internet

### [인터넷이란?](https://namu.wiki/w/%EC%9D%B8%ED%84%B0%EB%84%B7)
- Internetional Network의 합성어로, 인터넷 프로토콜 스위트( [TCP](https://ko.wikipedia.org/wiki/%EC%A0%84%EC%86%A1_%EC%A0%9C%EC%96%B4_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C) / [IP](https://ko.wikipedia.org/wiki/%EC%9D%B8%ED%84%B0%EB%84%B7_%ED%94%84%EB%A1%9C%ED%86%A0%EC%BD%9C) )를 기반으로 하여 전 세계적으로 연결되어있는 컴퓨터 네트워크 통신망을 일컫는 말이다.<br>
- [프로토콜 (Protocol)](https://ko.dict.naver.com/#/entry/koko/066279eccf464602bd4e87f2d9c6bc81) : 컴퓨터와 컴퓨터간에 신호 송신의 순서, 데이터의 표현법, 오류 검출법 등의 데이터를 원활히 주고 받기 위한 규약이다.
  - TCP (Transmission Control Protocol) : 전송 제어 프로토콜. 클라이언트와 서버 간에 신뢰있게 안정적으로 순서대로 에러없이 주고 받을 수 있다. 지역네트워크(LAN) 혹은 광역네트워크(WAN)에서 원활한 통신을 가능하도록 하기 위한 통신규약(Protocol) 으로 정의한다.
  - IP (Internet Protocol)) : 인터넷 프로토콜. 네트워크 상의 컴퓨터 고유 주소이며, 총 4바이트로 되어 있다.
### [인터넷의 작동원리](https://developer.mozilla.org/ko/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work)
![단일네트워크](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-1.png)   
<br>
예전에 두 개의 컴퓨터가 통신이 필요할 때, 유선 케이블을 이용해 두 개의 컴퓨터를 연결해 통신했었다.<br>
하지만 여러 컴퓨터를 유선케이블로 하나하나 연결하는데엔 불편하고 한계가 생길 수 밖에 없다.<br><br>
![여러컴퓨터라면](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-2.png)   
<br>
이러한 문제를 해결하기 위해 라우터라고하는 특수한 소형 컴퓨터에 연결하게 된다.<br><br>
![그렇다면이렇게](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-3.png)
<br>
A컴퓨터와 B컴퓨터와 통신할 땐 C컴퓨터에 가지 않게 하면 단일 플러그와 10개 플러그가 있는 하나의 라우터가 필요하다.<br><br>
![확장 가능](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-5.png)
<br>
하지만 먼 곳까지는 통신이 불가능 해, 전화(전세계와 연결되어있기 때문에)를 이용한 전화시설로 처리할 수 있는 정보로 바꿔주는 모뎀이라는 특수장비가 필요하다.<br>
네트워크를 전화시설에 연결하게 되는데 그것을 인터넷 서비스 제공 업체 (Internet Service Provider, ISP)에 연결한다.<br>
![ISP](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/How_does_the_Internet_work/internet-schema-7.png)<br>
우리가 알고 있는 SKT, KT, LG U+에서 관리하게 된다.
### [HTTP란?](https://ko.wikipedia.org/wiki/HTTP)
- HyperText Transfer Protocol, 인터넷에서 데이터를 주고 받을 수 있는 프로토콜이다.

