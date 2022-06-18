* * *

과제 계획서
===========
* * *
교과목명: C++
----

지도교수: 컴퓨터공학과 심재창
-------------------------
과제명: C++종합 팀과제(소켓통신 실습샘플)
--------------------
팀명: 1팀
--------
팀장 및 참여인원 담당업무
------
>1)팀장/김현빈/컴퓨터공학과/3학년/010-2013-8345/계획서 작성, 발표

>2)팀원/이준석/컴퓨터공학과/3학년/010-84285923/자료조사,산출물 구현

>3)팀원/권윤호/컴퓨터공학과/3학년/010-8995-8735/자료조사, 발표자료 생성 및 발표

#1.과제요약
---
본 과제는 유튜브, 동영상 스트리밍 서비스, 온라인게임 등이 활성화된 현재, 이러한 인터넷의 기반이되는 네트워크통신의 구조를 파악하고, 이를 socket을 활용하여 직접 구현해 보는 과정을 정리한다. Socket을 활용하여 네트워크 통신에 필연적인 서버와 클라이언트를 구현할 수 있으며, 가장 대중적인 프로토콜인 TCP/IP 및 UDP 통신 프로토콜의 통신과정을 MFC를 통해 최종적으로 구현하고 각각의 샘플을 산출한다.


##2.과제 개요 
---
1)과제 배경 : 

1922년에 발표된 windows API의 C언어 함수들을 Wrapping 하여 C++언어의 클래스화 한 라이브러리인 mfc는 과거에 비해서는 미약하지만 현재까지 해외와 국내에서 대두되는 라이브러리이다. 이 mfc는  별도의 라이브러리 없이 윈도우즈용 GUI 응용프로그램을 개발하려면 운영체제가 제공하는 C언어 기반의 Windows API를 써야하는데, 단순히 운영체제의 여러 기능들을 노출시켜주는 C함수들의 집합일 뿐이기 때문에 복잡한 UI를 작성하는 등의 고차원적인 작업을 할때에는 필연적으로 코드 노가다가 수반되지만 이러한 문제점을 해결하기 위해 클래스형태로 쓸수 있게 해주는 것이 MFC이다.

2)과제 필요성 :

다양한 분야에서 통신이란 가장 핵심이며 기초가 되고있다. 이제 우리의 삶과 땔래야 땔 수 없는 존재가 되어버린 SNS나 온라인 게임, 메타버스 등 본 과제를 정확하게 이해하고 구현해보는 활동을 통해 이러한 유망한 분야로의 확장연구를 위한 중요한 기반을 다지는 활동이 될 것이다. 따라서 본 프로젝트를 통해 통신의 기초가 되는 SOCKET을 정확하게 이해하고 이를 MFC로 구현해보며 정확한 개념 적립과 실습 경험을 쌓을 수 있도록 한다. 

3)과제 선택 동기 :

우리 일상에 가장 친숙하지만서도 이해하기 어려운 인터넷 이라는 주제가 흥미로웠고 이를 MFC를 통해 충분히 구현할 수 있는 난이도라 판단하여 주제로 선정하였다. 또한 소켓을 이용한 통신을 응용할 수 있는 여지가 많고, 이번 연구를 통하여 더 확장된 연구도 가능할것 이라는 점이 매력적으로 느껴져 이 주제를 결정하게 되었다.


###3.과제 목표 및 내용 
---
1)정량적 정성적 목표

정량적 목표 :

-팀원 모두가 UDP, TCP/IP통신과 얼굴인식 알고리즘을 이해하고 설명할 수 있다. 

-정해진 기간 내에 과제를 작성한다.

-소켓 통신을 구현하고 클라이언트가 보낸 이미지에서 서버가 얼굴을 추출하여 클라이언트에게 리턴한다.

-본 프로젝트를 통해 누구나 실습해볼 수 있는 샘플 프로그램을 제시한다.


정성적 목표 :

-원래의 계획처럼 제대로 수행한다.

-팀원들의 목표들은 기준점을 정하여 팀원과 팀장이 함께 평가한다.

-팀 프로젝트 과정 중 정해진 일정을 완벽하게 수행하도록 한다.

-팀 프로젝트 과정 중 팀원의 의견을 존중하고 조율하며 프로젝트에 임한다.

[정성적 평가 기준]

|평가점수|점수기준|완성도|기간|
|-------|-------|------|----|
|A|90점 이상|충족|해당 과제를 정해진 시간에 준하여 완성하였는가|
|B|80점 이상 90점 미만|약간 미달|해당 과제의 정해진 기간을 2일 이하로 어겼는가|
|C|70점 이상 80점 미만|매우 미흡|해당 과제의 정해진 기간을 3일 이상으로 어겼는가|
|D|70점 미만|별도의 조치가 필요한 매우 심각한 상황|별도의 조치가 필요한 심각한 상황인가|

[정량적 평가 기준]

|평가점수|점수기준|달성률|
|-------|-------|-----|
|A|90점 이상|목표 대비 100%이상|
|B|80점 이상 90점 미만|목표 대비 90%이상|
|C|70점 이상 80점 미만|목표 대비 80%이상|
|D|70점 미만|목표 대비 70%미만|

2)과제의 내용 :

https://www.google.com/url?sa=t&source=web&rct=j&url=https://jay-ji.tistory.com/m/26&ved=2ahUKEwjJmLXunfP3AhUNA6YKHZ6mDKIQFnoECAYQAQ&usg=AOvVaw3XCrQ4Elr7BwStMTRDnAgD 
를 참고 수정을 통해 최종 구현물을 만들 예정. 


####4. 결과물 
---
• 예상 결과물 :

누구나 쉽게 따라할 수 있는 실습 샘플 및 통신의 기초개념 도식화(그림자료) 등. 

• 기대효과 및 활용방안 : 

개념 정리와 기초적인 방법으로 구현하는것을 목표로 정했다. 본 결과물을 보고 관련 자료를 조금만 찾아보면 누구나 쉽게 실습해보고 본 프로젝트에 적용된 개념을 정리할 수 있도록 한다. 또한 이를 교육용으로 다듬어 어디서든지 실습 프로그램 예제로 사용할 수 있도록 한다. 

#####5. 수행일정 
---
|  |05.18~23|05.23|05.25~26|05.27~06.1|06.2~5|06.5~7|06.8|06.10|06.11|미정|
|--|--------|-----|--------|----------|------|------|----|-----|-----|---|
|작업내용|계획서 정리|계획서 제출|관련 개념 조사 및 정리|MFC프로그램 예제 샘플 정리 및 구현 실습|구현물 통합 및 완성 어플리케이션 시연|논문양식 보고서 작성|PPT|리플릿|산출물 시연 동영상 촬영 및 유튜브|산출물 제출|

######6. 참고문헌 및 자료 
----
[1] [MFC]TCP/IP 소켓프로그래밍. https://jay-ji.tistory.com/m/26 (accessed February 7,2018). 

[2]licongxing/WinlPC_socket)TCP.https://github.com/licongxing/WinIPC_Socket_Tcp(accessed November 6,2018)

[3]소켓과 MFC를 이용한 채팅 프로그램 개발하기 - 서버편. https://sonny777.tistory.com/m/20 (accessed March 6.2019)

[4]MFC 소켓 프로그래밍 - 채팅 프로그램(서버, 클라이언트).https://sh-itstory.tistory.com/m/71(accessed October 11.2019)

[5]MFC- 소켓통신(C++). https://m.blog.naver.com/PostView.naver?isHttpsRedirect=true&blogId=rkttndk&logNo=221436188895 (accessed January 7.2019)


