# REST-Study
REST API study

### Representational State Transfer
wiki - REST is an architecture style for designing networked applications
표면적인 실체는 '스타일' 또는 '패턴'이라고 한다.

### RESTful API
REST한 방식의 api라는 건, 아래처럼 잘 설계된 API를 말한다.
- 웹을 근간으로 하는 HTTP Protocol기반이다.
- 리소스(자원)는 URI(Uniform Resoure Identifiers)로 표현하며 말 그대로 '고유'해야 한다.
- URI는 단순하고 직관적인 구조이어야 한다.
- 리소스의 상태는 HTTP Methods를 활용해서 구분한다.
- xml/json을 활용해서 데이터를 전송한다.(주로 json)

### CRUD
네트웍을 통해 웹 리소스(resource)를 다루기 위한 행위들. 각각의 행위를 처리하기 위한 HTTP methods(POST, GET, PUT, DELETE)가 있다.
- Create(Post)
- Retrieve(GET)
- Update(PUT)
- Delete(DELETE)

### API Design
- 복수명사를 사용(/movies)
- 필요하면 URL에 하위 자원을 표현.(/movies/23)
- 필터조건을 허용할 수 있음.(/movies?state=active)
<img width="530" alt="스크린샷 2020-10-12 오후 6 04 18" src="https://user-images.githubusercontent.com/31848384/95727588-4f101500-0cb5-11eb-88c4-493473939b66.png">

