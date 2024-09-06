# SupaBase
FireBase? No SupaBase is the better

## FireBase 와 SupaBase 의 차이점
***
### FireBase:
#### Baas (Backend as a Service)
- 서버 없이도 빠르게 앱을 출시할 수 있도록 나온 백엔드 플랫폼
- 파이어베이스는 기본적으로 가입 인증, 클라우드 호스팅, 실시간 데이터베이스, 파일 업로드를 할 수 있는 클라우드 저장소 등을 모두 제공한다.
- 이외에도 앱 기능 향상과 앱 성장을 위한 다양한 기능을 제공된다.
- 따라서 앱 개발자들이 백엔드에 신경 쓰지 않고 빠르게 개발할 수 있다.
#### FireBase의 장점
  - 다양한 서비스와 **폭넓은 연동지원**
  - 적용이 매우 쉽고 **문서화**가 잘되어있다.
  - **커뮤니티**가 매우 성숙한 프로덕트
  - 앱, 웹에서 사용할 수 있는 **NoSQL 기반**
#### FireBase의 단점
  - **오픈소스**가 아니다. (Vendor Lock-In : 특정 업체의 서비스나 솔루션에 종속되는 현상)
  - **복잡한 쿼리** 불가 (NoSQL 기반)
  - 유저가 많아졌을 때 **비용**이 많이 든다.
  - 앱 개발에는 월등히 좋으나 **웹 개발에 최적은 X**

### Supabase:
#### 핵심 기능 4가지
  - 수퍼베이스 데이터베이스 지원: PostgreSQL 기반의 실시간 데이터베이스를 지원
  - 인증 기능 : 소셜 로그인을 구현하거나 일반적인 회원가입 OTP 방식의 로그인을 모두 지원
  - 수퍼베이스 스토리지 : 파일 업로드 기능을 구현하거나 서명된 URL을 만들어 일정 시간 동안만 다운로드할 수 있는 고급기능 지원
  - Realtime : 실시간 채팅이나 실시간 알림 같은 기능을 쉽게 구현할 수 있도록 수퍼베이서 SDK와 API를 모두 지원
#### Supabase의 장점
  - **오픈소스** 프로젝트 (자체 서버구축 가능)
  - **PostgreSQL** 기반 (관계형 DB 장점을 살릴 수 있다)
  - Firebase 대비 **저렴**
  - **다양한 연동**방식 지원 (+ GraphQL,. API, SDK, DB Connection)
#### Supabase의 단점
  - 아직 성숙하지 않은 **커뮤니티** 기반 (국내에 잘 알려지지 않음)
  - 비교적 **적은 기능**들, 적은 서비스 연동 지원
  - 부족한 **문서화**,한글 문서 부족
  - Firebase보다 **높은 러닝커브** (Firebase 보다 학습 곡선이 높다)
#### 그럼에도 사용하는 이유
- 개인 또는 소규모 팀이 **풀스택 개발**을 하는데 필요한 대부분의 것들이 갖춰져 있다.
- 스타트업 or 개인 프로젝트 특성상 **복잡한 요구사항**이 생기기 쉬운데, 이를 대응하기가 훨씬 용이하다. (Postgre SQL 기반이면서 필수적인 모든 서비스들을 제공해 주기 떄문에 대응이 훨씬 용이)
- 보안상의 이슈로 직접 서버구축을 해야할 때, Supabase는 **비교적 쉽게 이전**이 가능하다. Vendor Lock-In 이슈 없이 유연하게 사용할 수 있다. (오픈소스)
