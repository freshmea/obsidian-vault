---
Date: 2023-12-13T11:54:24
tags:
  - ROS2
  - 자동차
  - 아이디어
  - 서브넷
---

### 주제 : 자동차 ROS2 적용 전장 부품
----
### 메모 : 
> ROS2의 운용은 기본적으로 ip/port로 인식이 된다. 자동차 시스템은 can 통신으로 이루어 지는데 can통신으로 DDS의 동기화가 될 수 있을 것인가?
> can 통신이 불가능하다면 wifi 또는 LTE 로 자동차 전장부품을 연결해도 되는가? 안정성? 
> 랜선을 통해서 ROS2 전장부품들을 엮어서 subnet을 구성 할 수는 없는가? 
> 시리얼 COM 포트을 통해서 subnet을 구성 할 수는 없는가?
> - 테슬라 차량은 내부 보안은 폐쇄적인 CAN통신으로 외부망을 이욯하는 전자기기는 LAB방식의 통식을 사용한다고 한다.[^1] 
> - 다만 차량용 Ethernet 은 일반 Ethernet과 운용 방식이 다르다[^2][^3]



### 연결문서
- 

### 출처(참고문헌)
[^1]: https://www.carguy.kr/news/articleView.html?idxno=40865
[^2]: https://blog.naver.com/PostView.naver?blogId=lagrange0115&logNo=222681220169
[^3]: https://blog.naver.com/vectorteam/220747831633
