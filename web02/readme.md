## web02 : 웹 프로그래밍의 기초 다지기

  - Http protocol : 웹 브라우저와 웹 서버 사이의 데이터 통신 규칙 </br>
    => SOAP나 RESTful은 Http를 응용하거나 확장한 기술
  
    웹 브라우저 ---- Request ---> 웹서버 </br>
    웹 브라우저 <--- Response ---- 웹서버
    
  - Header
    - 일반 헤더(General-header) : 요청, 응답 모두에 적용할 수 있는 헤더
      - 종류 : Cache-Control, Connection, Date, Pragma, Trailer, Transfer-Encoding,<br>Upgrade, Via, Warning
    - 요청 헤더(Request-header) : 요청시에 적용할 수 있는 헤더
      - 종류 : Accept, Accept-Charset, Accept-Encoding, Accpet-Language, Authorization,<br>Expect, From, Host, If-Match, If-Modified-Since, If-None-Match, If-Range, If-Unmodified-Since,<br> Max-Fowards, Proxy-Authorizaion, Range, Referer, TE, User-Agent
    - 응답 헤더(Response-header) : 응답시에 적용할 수 있는 헤더
      - 종류 : Accpet-Ranges, Age, ETag, Location, Proxy-Authenticate, Retry-After, Server,<br>Vary, WWW-Authenticate
    - 엔티티 헤더(Entity-header) : 보내거나 받는 본문 데이터를 설명하는 헤더
      - 종류 : Allow, Content-Encoding, Content-Language, Content-Location, Content-MD5,<br> Content-Range, Content-Type, Expires, Last-Modified, 기타 확장 헤더들...
      
  - HTTP Request : 요청 라인, 요청 헤더, 공백 라인, 요청 데이터로 구성
    - 요청 라인(Request-Line) : 요청 메시지의 첫 라인. 메서드, 요청 자원, 프로토콜 버전으로 구성<br>
    ex) GET / HTTP/1.1      <= "메서드 (공백) 요청URL (공백) HTTP버전"의 형식으로 한 라인 구성
    - 요청 헤더(Request-Header) : 서버가 요청 처리시 참고하라고 클라이언트가 웹 서버에게 알려주는 정보<br>
    ex) User-Agent :  Mozila/5.0(Macinetosh; Intel Mac OS X10_13_6) ......    <= 이런 형식으로 구성
      - User-Agent의 경우 클라이언트의 정보를 서버에게 알려주는 헤더.<br>웹 서버가 이 헤더를 분석해 요청자의 OS와 브라우저를 구분.
  - HTTP Response : 
  
  - GET : 
  - POST :
