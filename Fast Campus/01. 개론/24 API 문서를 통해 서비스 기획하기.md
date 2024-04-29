---
강의: 협업을 위한 IT 지식
lecturer: 박철우
email: duck@hey.com
---
# 협업을 위한 IT 지식
## API 문서를 통해 서비스 기획하기
### API 이해
- Application Programming Interface 의 약자
- 응용 프로그램에서 사용할 수 있도록, 운영체제나 프로그래밍 언어가 제공하는 기능을 제어할 수 있게 만든 인터페이스

### 인터페이스
- 컴퓨터 시스템끼리 정보를 교환하는 공유 경계를 의미
- 터치스크린과 같은 일부 하드웨어 장치들은 인터페이스를 통해 데이터를 송수신할 수 있으며, 마우스 같은 장치들은 오직 시스템에 데이터를 전송만 하는 인터페이스를 제공함

### API 란?
- 프로그램 간 데이터를 주고 받는 방법, 소통의 매개체
- API 는 점원의 역할과 같다

![](https://i.imgur.com/KDOYMA3.png)
![](https://i.imgur.com/ihAek5m.png)

### API 종류
**Private API**
- 내부에서 사용되는 API 로 회사 내부 자체 제품과 서비스 운영, 개선하기 위해 사용되는 API
- 외부 및 제 3자에게 노출되지 않음
**Public API**
- 개방형 API 로, Open API 라고 부름
- 보편적으로 승인을 받아야 사용할 수 있음
- 누구나 제한 없이 API 를 사용할 수 있는 것이 특징
- 그렇다고 공짜는 아님! (Feat. 우혁 강사님)

### JSON
- JavaScript Object Notation 약자
- 데이터를 저장하거나 전송할 때 많이 사용되는 DATA 교환 형식
- 어떠한 통신 방법도, 프로그래밍 문법도 아닌 단순히 데이터를 표시하는 표현 방법
- 용량이 작아서 XML 을 대체해서 데이터 전송 등에 많이 사용됨

![](https://i.imgur.com/uMMWone.png)

### 서비스에서 API 가 사용되는 방식
- 한 가지 API 를 사용한 구조는 거의 없다
- 앱 화면과 앱 서버를 연결해주는 API & 앱 서버와 외부 시스템과 연결해주는 API 등 2 가지 이상의 API를 사용하는 경우가 대다수

![](https://i.imgur.com/0YurEpB.png)

### 카카오 우편번호 서비스
**우편번호 서비스**
- https://postcode.map.daum.net/guide
- 우편번호, 주소 검색 기능 API 를 무료로 제공 (사용량 제한 없음)

**카카오 우편번호 서비스 예시**
![](https://i.imgur.com/YBWprti.png)

### 오픈뱅킹 서비스
- https://www.openbanking.or.kr/
- 계좌실명조회, 거래내역조회, 이체, 잔액조회 등을 이용하여 핀테크 서비스를 만들 수 있음

![](https://i.imgur.com/WXmnCoa.png)

> [!NOTE] 서비스 기획자에게 API 는 ...
> 서비스 기획자 혹은 PM 이 개발자처럼 개발을 하는 것은 아니지만 이러한 API 를 통해서 서비스를 기획하는데 도움을 받거나 아이디어를 얻을 수 있음

### 공공데이터포털
- data.go.kr
- 찾고 있던 공공데이터가 있다면 공공데이터포털에 검색하면 거의 다 있음

**API 로 서비스 만들기**
- 공공데이터포털에서 제공하는 기상청, 전국 해수욕장 날씨 조회 서비스
- 이 API 를 사용하면 해운대 등의 해수욕장 날씨 체크 가능
- 페이지 하단에 창고 문서가 있는데 이것을 통해 API 활용 가이드를 볼 수 있음 (a.k.a 연동 정의서, 연동 규격)

![](https://i.imgur.com/hgNXcFr.png)

![](https://i.imgur.com/L141c9N.png)