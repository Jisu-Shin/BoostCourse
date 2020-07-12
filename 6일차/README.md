# Day6 : 20-07-12
* HttpServlet은 **하나의 객체만** 생성한다

* HttpServlet은 init() -> service() -> destroy() Lifecycle를 갖는다

* destory()는 중간에 Servlet이 변경되었을 때 호출된다

* service() 메소드가 없어도 HttpServlet 상속받아서 doGet() doPost() 로 가능하다

* Servlet 이해가 가지 않아서 찾아봤다 :: 사용자가 로그인을 시도할때 서버는 사용자(클라이언트)의 아이디와 비밀번호를 확인하고 다음 페이지를 띄워주는 역할을 수행하는 것이 Servlet이다

* Enumeration<E> :: 인터페이스는 객체들의 집합에서 각각의 객체들을 하나씩 처리하는 메소드를 제공하는 컬렉션이다 그래서 new 연산자로 생성할 수가 없다
