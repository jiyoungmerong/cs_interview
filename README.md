## cs 면접 대비

### 네트워크
<details>
  <summary>웹 통신의 큰 흐름 : https://www&#46;google&#46;com/ 을 접속할 때 일어나는 일</summary>
  </br>
</details>

<details>
  <summary>TCP와 UDP의 차이점</summary>
  </br>
</details>

<details>
  <summary>TCP 3, 4 way handshake에 대해 설명</summary>
  </br>
</details>

<details>
  <summary>HTTP와 HTTPS의 차이점</summary>
  </br>https://jiyoungmerong.tistory.com/138
</details>

<details>
  <summary>HTTPS에 대해서 설명하고 SSL Handshake에 대해서 설명</summary>
  </br>
</details>

<details>
  <summary>GET과 POST의 차이점에 대해서 설명</summary>
  </br>
</details>

<details>
  <summary>HTTP 메서드와 이것이 하는 역할</summary>
  </br>
</details>

<details>
  <summary>RESTful이란 무엇인지</summary>
  </br>
</details>

<details>
  <summary>CORS란 무엇인지</summary>
  </br>
</details>

<details>
  <summary>OSI7계층과 그 존재 이유, TCP/IP 4계층에 대해 설명</summary>
  </br>
</details>

<details>
  <summary>웹 서버 소프트웨어(Apache, Nginx)는 OSI 7계층 중 어디서 작동하는지 설명</summary>
  </br>
</details>

<details>
  <summary>웹 서버 소프트웨어(Apache, Nginx)의 서버 간 라우팅 기능은 OSI 7계층 중 어디서 작동하는지 설명</summary>
  </br>
</details>

### 운영체제

<details>
  <summary>프로세스와 스레드의 차이점</summary>
  </br>
</details>

<details>
  <summary>컨텍스트 스위칭</summary>
  </br>
</details>

<details>
  <summary>동기와 비동기의 차이(블로킹, 넌블로킹) / 장단점</summary>
  </br>
</details>

<details>
  <summary>멀티스레드 프로그래밍에 대해 설명</summary>
  </br>
</details>

<details>
  <summary>Thread-safe 하다는 의미와 설계하는 법</summary>
  </br>
</details>

<details>
  <summary>프로세스 동기화</summary>
  </br>
</details>

<details>
  <summary>교착상태와 기아상태의 해결방법</summary>
  </br>
</details>

<details>
  <summary>세마포어와 뮤텍스의 차이점</summary>
  </br>
</details>

<details>
  <summary>가상 메모리.</summary>
  </br>
</details>

<details>
  <summary>캐시의 지역성</summary>
  </br>
</details>

<details>
  <summary>프로세스 관련 용어를 설명</summary>
  </br>
  <p>PCB: 프로세스 제어 블록, 프로세스에 대한 중요한 정보를 저장한다.</p>
  <p>PC: 프로그램 카운터, 프로세스 실행을 위한 다음 명령의 주소를 표시한다.</p>
  <p>캐시메모리: 자주 사용되는 데이터가 저장되는 공간으로 CPU의 레지스터와 메모리 사이에서 병목 현상을 완화하는 장치이다.</p>
</details>

### 데이터베이스

<details>
  <summary>데이터베이스에서 인덱스를 사용하는 이유 및 장단점</summary>
  </br>
</details>

<details>
  <summary>트랜잭션</summary>
  </br>
</details>

<details>
  <summary>ACID에 대해서</summary>
  </br>
</details>

<details>
  <summary>트랜잭션 격리 수준(Transaction Isolation Levels)</summary>
  </br>
</details>

<details>
  <summary>정규화</summary>
  </br>
  <p>정규화는 데이터의 중복방지, 무결성을 충족시키기 위해 데이터베이스를 설계하는 것이다</p>
</details>

<details>
  <summary>JOIN</summary>
  </br>
</details>

<details>
  <summary>RDBMS vs NOSQL</summary>
  </br>
  <p>RDBMS는 데이터베이스를 이루는 객체들의 릴레이션을 통해서 데이터를 저장하는 데이터베이스이다. SQL을 사용해 데이터의 저장, 질의, 수정, 삭제를 할 수 있으며 데이터를 효율적으로 보관하는 것을 목적으로 하고 구조화가 중요하다.</p>
  <p>장점으로는 명확한 데이터 구조를 보장하고, 중복을 피할 수 있다.</p>
  <p>NOSQL은 RDBMS에 비해 자유로운 형태로 데이터를 저장한다. 또한 수평확장을 할 수 있고 분산처리를 지원한다. 다양한 형태의 NOSQL 데이터베이스가 있고, 대표적으로 key-value store, bigtable, dynamo, document db, graph db 등이 있다.</p>
  <p>둘은 대체될 수 있는 것이 아니고, 각각 필요한 시점에 적절히 선택해서 사용해야 한다. 둘 다 같이쓰는 상호보완적인 존재가 될 수도 있다.</p>
</details>

<details>
  <summary>Redis에 대해 설명</summary>
  </br>
  <p>Redis는 key-value store NOSQL DB이다. 싱글스레드로 동작하며 자료구조를 지원한다. 그리고 다양한 용도로 사용될 수 있도록 다양한 기능을 지원한다. 데이터의 스냅샷 혹은 AOF 로그를 통해 복구가 가능해서 어느정도 영속성도 보장된다.</p>
  <p>스프링에서는 세션을 관리하거나, 캐싱을 하는데에 자주 사용된다.</p>
</details>

<details>
  <summary>Redis와 Memcached의 차이점</summary>
  </br>
  <p>Redis는 싱글 스레드 기반으로 동작하고, Memcached는 멀티스레드를 지원해서 멀티 프로세싱이 가능하다.</p>
  <p>Redis는 다양한 자료구조를 지원하고, Memcached는 문자열 형태로만 저장한다.</p>
  <p>Redis는 여러 용도로 사용할 수 있도록 다양한 기능을 지원한다.</p>
  <p>Redis는 스냅샷, AOF 로그를 통해서 데이터 복구가 가능하다.</p>
</details>

<details>
  <summary>Elastic Search</summary>
  </br>
</details>

<details>
  <summary>Elastic Search의 인덱스구조와 RDBMS의 인덱스 구조의 차이점</summary>
  </br>
</details>

<details>
  <summary>Elastic Search의 키워드 검색과 RDBMS의 LIKE 검색의 차이점</summary>
  </br>
</details>

<details>
  <summary>MongoDB</summary>
  </br>
</details>

<details>
  <summary>CAP 이론과, Eventual Consistency</summary>
  </br>
</details>

### 자료구조/알고리즘

<details>
  <summary>시간 복잡도를 계산하라</summary>
  </br>
</details>

<details>
  <summary>배열과 링크드 리스트의 차이점</summary>
  </br>
</details>

<details>
<summary>List와 Set의 차이점</summary>
  </br>
</details>

<details>
  <summary>Hash Function, HashTable</summary>
  </br>
</details>

<details>
  <summary>Stack, Queue</summary>
  </br>
  <p><b>Stack</b></p>
  <p>스택은 선형 자료구조의 일종으로 마지막에 저장한 데이터를 가장 먼저 꺼내게 되는 LIFO(Last In First Out)방식의 자료구조이다. 스택의 사용 예시로는 웹 브라우저의 방문기록(뒤로가기), 실행 취소(undo) 등이 있다.</p>
  <p><b>Queue</b></p>
  <p>큐는 선형 자료구조의 일종으로 처음에 저장한 데이터를 가장 먼저 꺼내게 되는 FIFO(First In First Out)방식의 자료구조이다. 큐의 사용 예시로는 프린터의 인쇄 대기, 콜센터 고객 대기 시간 등이 있다.</p>
</details>

<details>
  <summary>Heap, Priority Queue</summary>
  </br>
</details>

<details>
  <summary>Tree, Binary Tree, BST, AVL Tree</summary>
  </br>
</details>

<details>
  <summary>BST의 최악의 경우의 예와 시간복잡도.</summary>
  </br>
</details>

<details>
  <summary>피보나치 수열을 코드로 구현하는 방법</summary>
  </br>
</details>

<details>
  <summary>DFS, BFS</summary>
  </br>
</details>

<details>
  <summary>정렬, 탐색</summary>
  </br>
</details>

### 암호학/보안(간단)

<details>
  <summary>비대칭키 암호화, 대칭키 암호화</summary>
  </br>
</details>

<details>
  <summary>단방향 암호화</summary>
  </br>
</details>

<details>
  <summary>JWT</summary>
  </br>
  <p>JWT란 토큰 인증 방식에서 쓰이는 것이라고 볼 수 있다. 다른 사용으론 데이터를 공유하는데도 사용할 수 있지만 일반적으론 토큰 인증 방식에서 사용된다.</p>
  <p>JWT는 헤더, 페이로드, 시그니쳐로 구분된다. 헤더는 토큰의 타입, 암호화 알고리즘을 담고 있고, 페이로드는 토큰의 정보를 담는 부분이며, 시그니처는 토큰의 정보가 신뢰할 수 있는것인지 판단할 수 있도록 한다.</p>
  <p>JWT는 세션 기반 인증과 주로 대비된다. 세션기반 인증은 서버에서 세션 정보를 관리해야하는 비용이 든다. 또한 분산환경에서도 관리하기 어렵드ㅏ. 하지만 JWT는 그 자체로 정보를 가지고 있기 때문에 세션의 단점을 보완할 수 있다.</p>
</details>

<details>
  <summary>OAuth</summary>
  </br>
</details>

<details>
  <summary>JWT와 OAuth의 차이점</summary>
  </br>
</details>

<details>
  <summary>SQL Injection</summary>
  </br>
</details>

<details>
  <summary>XSS</summary>
  </br>
</details>

<details>
  <summary>CSRF</summary>
  </br>
</details>

### 컴파일러

<details>
  <summary>스크립트 언어와 컴파일 언어를 나열하고 차이점</summary>
  </br>
</details>

## 언어 관련

### Java

<details>
  <summary>JVM의 구조</summary>
  </br>
</details>

<details>
  <summary>Java의 실행방식</summary>
  </br>
</details>

<details>
  <summary>GC가 무엇인지, 필요한 이유는 무엇인지, 동작방식 설명.</summary>
  </br>
</details>

<details>
  <summary>컬렉션 프레임워크</summary>
  </br>
</details>

<details>
  <summary>제네릭</summary>
  </br>
</details>

<details>
  <summary>애노테이션</summary>
  </br>
</details>

<details>
  <summary>오버라이딩과 오버로딩의 차이점</summary>
  </br>
</details>

<details>
  <summary>인터페이스와 추상클래스의 차이점</summary>
  </br>
</details>

<details>
  <summary>클래스와 객체에 대한 설명</summary>
  </br>
</details>

<details>
  <summary>정적(static)이란?</summary>
  </br>
</details>

<details>
  <summary>자바의 원시타입들은 무엇이 있으며 각각 몇 바이트를 차지하는지?</summary>
  </br>
</details>

<details>
  <summary>접근 제어자의 종류와 설명</summary>
  </br>
</details>

<details>
  <summary>객체지향에 대해서</summary>
  </br>
</details>

<details>
  <summary>SOLID(객체지향 5대원칙)에 대해서.</summary>
  </br>
  https://jiyoungmerong.tistory.com/53
</details>

<details>
  <summary>동일성(identity)와 동등성(equality)(equals(), ==)</summary>
  </br>
</details>

<details>
  <summary>원시타입과 참조타입의 차이점</summary>
  </br>
</details>

<details>
  <summary>String, StringBuilder, StringBuffer 각각의 차이</summary>
  </br>
</details>

<details>
  <summary>Checked Exception과 Unchecked Exception에 대한 설명. 스프링 트랜잭션 추상화에서 rollback 대상은 무엇인가?</summary>
  </br>
</details>

<details>
  <summary>Java8에서 추가된 기능</summary>
  </br>
</details>

<details>
  <summary>try-with-resource</summary>
  </br>
</details>

<details>
  <summary>강한 결합과 느슨한 결합</summary>
  </br>
</details>

<details>
  <summary>직렬화와 역직렬화</summary>
  </br>
</details>

<details>
  <summary>자바의 동시성 이슈(공유자원 접근).</summary>
  </br>
</details>

<details>
  <summary>Mutable 객체와 Immutable 객체의 차이점</summary>
  </br>
</details>

<details>
  <summary>자바에서 null을 안전하게 다루는 방법.</summary>
  </br>
</details>

#### Spring

<details>
  <summary>Spring DI/IoC의 동작방식</summary>
  </br> https://jiyoungmerong.tistory.com/65
</details>

<details>
  <summary>Spring Bean이란</summary>
  </br>
  <p>IoC 컨테이너 안에 들어있는 객체로 필요할 때 IoC컨테이너에서 가져와서 사용한다. @Bean 을 사용하거나 xml설정을 통해 일반 객체를 Bean으로 등록할 수 있다.</p>
</details>

<details>
  <summary>스프링 Bean의 생성 과정</summary>
  </br>
</details>

<details>
  <summary>스프링 Bean의 Scope</summary>
  </br>
</details>

<details>
  <summary>IoC 컨테이너의 역할</summary>
  </br>
</details>

<details>
  <summary>DI 종류는 어떤것이 있고, 이들의 차이?/summary>
  </br>
</details>

<details>
  <summary>Autowiring 과정</summary>
  </br>
</details>

<details>
  <summary>Spring Web MVC의 Dispatcher Servlet의 동작 원리</summary>
  </br>
</details>

<details>
  <summary>프론트 컨트롤러 패턴이란?</summary>
  </br>
</details>

<details>
  <summary>Servlet Filter와 Spring Interceptor의 차이점</summary>
  </br>
</details>

<details>
  <summary>Spring에서 CORS 에러를 해결하기 위한 방법</summary>
  </br>
</details>

<details>
  <summary>Bean/Component 어노테이션 차이점</summary>
  </br>
</details>

<details>
  <summary>POJO란 무엇인가? Spring Framework에서 POJO는 무엇이 될 수 있을까?</summary>
  </br>
</details>

<details>
  <summary>Spring Web MVC에서 요청 마다 Thread가 생성되어 Controller를 통해 요청을 수행할텐데, 어떻게 1개의 Controller만 생성될 수 있을까?</summary>
  </br>
</details>

<details>
  <summary>Filter는 Servlet의 스펙이고, Interceptor는 Spring MVC의 스펙이다. Spring Application에서 Filter와 Interceptor를 통해 예외를 처리할 경우 어떻게 해야 할까?</summary>
  </br>
</details>

<details>
  <summary>Spring Application을 구동할 때 메서드를 실행시키는 방법</summary>
  </br>
</details>

<details>
  <summary>의존성과 설정값을 생성자 인자로 주입해야 하는 이유.</summary>
  </br>
</details>

#### JPA

<details>
  <summary>JPA 영속성 컨텍스트의 이점(5가지)</summary>
  </br>
</details>

<details>
  <summary>JPA Propagation 전파단계</summary>
  </br>
</details>

<details>
  <summary>JPA를 쓴다면 그 이유</summary>
  </br>
</details>

<details>
  <summary>N + 1 문제는 무엇이고 이것이 발생하는 이유와 이를 해결하는 방법</summary>
  </br>
  <p>N + 1 쿼리 문제는 즉시 로딩과 지연 로딩 전략 각각의 상황에서 발생할 수 있다. 하위 엔티티들이 존재하는 경우 한 쿼리에서 모두 가져오는 것이 아닌, 필요한 곳에서 각각 쿼리가 발생하는 경우를 이른다.</p>
  <p>즉시 로딩에서 발생하는 이유는 JPQL을 사용하는 경우 전체 조회를 했을 때, 영속성 컨텍스트가 아닌 데이터베이스에서 직접 데이터를 조회한 다음 즉시로딩 전략이 동작하기 때문이다.<br>
  지연 로딩에서 발생하는 이유는 지연로딩 전략을 사용한 하위 엔티티를 로드할 때, JPA에서 프록시 엔티티를 unproxy 할 때 해당 엔티티를 조회하기 위한 추가적인 쿼리가 실행되어 발생한다.</p>
  <p>해결 방법으로는 Fetch Join이라고 불리는 JPQL의 join fetch를 사용하는 방법이 있으며, 또 다른 방법으로는 <code>@EntityGraph</code>를 사용하는 방법, <code>@Fetch(FetchMode.SUBSELECT)</code>를 사용하는 방법, <code>@BatchSize</code>를 사용해 조절하거나 전역적인 batch-size를 설정하는 방법이 있다.</p>
</details>

## 기타

### 트러블 슈팅

<details>
  <summary>대용량 트래픽에서 장애가 발생하면 어떻게 대응할 것인가?</summary>
  </br>
</details>

### 디자인 패턴

<details>
  <summary>싱글톤 패턴</summary>
  </br>
</details>

<details>
  <summary>가교 패턴(브릿지 패턴)</summary>
  </br>
</details>

<details>
  <summary>전략 패턴</summary>
  </br>
</details>

<details>
  <summary>빌더 패턴</summary>
  </br>
</details>

<details>
  <summary>팩토리 메서드 패턴</summary>
  </br>
</details>

<details>
  <summary>퍼사드 패턴</summary>
  </br>
</details>

### 테스트

<details>
  <summary>테스트 코드에 대해서 어떻게 생각하고, 어떻게 작성하는지?</summary>
  </br>
</details>

<details>
  <summary>TDD를 알고 있는지? TDD에 대해서 어떻게 생각하는지?</summary>
  </br>
</details>

<details>
  <summary>테스트 커버리지에 대해서 어떻게 생각하는지?</summary>
  </br>
</details>

### 인프라/클라우드

<details>
  <summary>AWS 인프라를 구축해보았다면 설명</summary>
  </br>
</details>

<details>
  <summary>로드 밸런서</summary>
  </br>
</details>

<details>
  <summary>리버스 프록시</summary>
  </br>
</details>

<details>
  <summary>Fault-tolerant(무정지) 시스템으로 가기 위해 필요한 방법</summary>
  </br>
</details>

### 컨테이너

<details>
  <summary>Docker란 무엇이고 컨테이너 가상화를 왜 사용할까?</summary>
  </br>
</details>

<details>
  <summary>컨테이너 환경에서의 디버깅은 어떤식으로 하며 상대적으로 어려운 점은?</summary>
  </br>
</details>

<details>
  <summary>CI/CD가 무엇인가요? 왜 CI/CD가 장점이 될까?</summary>
  </br>
</details>

### 커뮤니케이션

<details>
  <summary>어떤 기술이나 방법론이 좋아보일 때, 이를 어떻게 설득할 것인가요?</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>일정이 예상보다 지연될 것 같습니다. 어떻게 해결하실 것인가요?</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>팀원과의 갈등이 있었나요? 있었다면 어떻게 대처했나요?</summary>
  </br>
  <p></p>
</details>

### 개인의 역량

<details>
  <summary>본인이 수행한 프로젝트 중 상용화 가능한 프로젝트가 있나요?</summary>
  </br>
  <p></p>
</details>

<details>
  <summary>기술을 습득할 때 어떤 식으로 습득하나요?</summary>
  </br>
  <p></p>
</details>

### 최신기술에 관심이 있는지

<details>
  <summary>protobuf에 대해서 알고계신가요? 이것은 왜 사용할까요?</summary>
  </br>
</details>

<details>
  <summary>gRPC는 무엇이며, RPC는 무엇인가요? 왜 쓸까요?</summary>
  </br>
</details>

<details>
  <summary>쿠버네티스가 무엇인가요? 왜 쿠버네티스를 쓸까요?</summary>
  </br>
  <p></p>
</details>

### 웹 서버의 동작 과정

<details>
  <summary>WS와 WAS의 </summary>
  </br>
  <p></p>
</details>

