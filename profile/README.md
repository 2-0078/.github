# 🍰 Piece of Cake - 실물자산 조각 투자 플랫폼

## 📋 목차
1. [✨ 기획](#1--기획)
2. [👥 팀원 소개](#2--팀원-소개)
3. [🛠️ 개발 환경](#3-️-개발-환경)
4. [📱 주요 기능](#4--주요-기능)
5. [🏗️ 설계 문서](#5-️-설계-문서)
6. [🤝 프로젝트 규칙](#6--프로젝트-규칙)
7. [🚀 포팅 매뉴얼](#7--포팅-매뉴얼)
8. [🔒 보안 및 성능](#8--보안-및-성능)
9. [📚 API 문서](#9--api-문서)

## 1. ✨ 기획

📅 **개발 기간** : 2025년 4월 30일 ~ 7월 10일

🌐 **홈페이지** : https://mobile.pieceofcake.site/

### 🎯 프로젝트 비전

**"Investment is Easy and Fun"**

Piece of Cake는 한정판 신발, 고가의 시계 등 다양한 실물자산을 조각으로 나누어 투자할 수 있는 조각 거래 플랫폼입니다. 소액으로도 고가 자산에 투자하고 수익을 창출할 수 있는 서비스를 제공합니다.

### 🌟 주요 특징

- **조각 투자**: 고가 자산을 작은 조각으로 나누어 소액 투자 가능
- **실시간 거래**: 조각 상품의 실시간 거래 및 가격 변동 추적
- **공모**: 새로운 자산 투자를 위한 투자자 모집
- **AI 가격 예측**: 인공지능 기반의 자산 가격 예측 서비스
- **투표 기반 경매**: 투자자 투표로 경매 진행 여부 결정 후 실시간 입찰 시스템

## 2. 👥 팀원 소개

<div align="center">
<table>
  <tr>
    <td align="center"><a href="https://github.com/Sujin31">👑 이수진</a></td>
    <td align="center"><a href="https://github.com/JungDongSeop">정동섭</a></td>
    <td align="center"><a href="https://github.com/LeeYeongin">이영인</a></td>
    <td align="center"><a href="https://github.com/EUNSEO-YA">오은서</a></td>
    <td align="center"><a href="https://github.com/corosica">정진우</a></td>
  </tr>

  <tr>
    <td align="center"><div style="background: #6366f1; color: white; padding: 4px 8px; border-radius: 12px; font-size: 12px;">⚙️ Backend & Leader</div></td>
    <td align="center"><div style="background: #059669; color: white; padding: 4px 8px; border-radius: 12px; font-size: 12px;">⚙️ Backend</div></td>
    <td align="center"><div style="background: #059669; color: white; padding: 4px 8px; border-radius: 12px; font-size: 12px;">⚙️ Backend</div></td>
    <td align="center"><div style="background: #059669; color: white; padding: 4px 8px; border-radius: 12px; font-size: 12px;">⚙️ Backend</div></td>
    <td align="center"><div style="background: #dc2626; color: white; padding: 4px 8px; border-radius: 12px; font-size: 12px;">🖥️ Frontend</div></td>
  </tr>

  <tr>
    <td align="center">
      팀장<br>
      서비스간 집계 전반<br>
      공모 서비스<br>
      공모 Read 서비스<br>
    </td>
    <td align="center">
      계정 / 회원 / 알림 서비스<br>
      경매 / 투표 서비스<br>
      데이터 관리<br>
    </td>
    <td align="center">
      상품/Read서비스<br>
      실시간 데이터 서비스<br>
      조각 상품 서비스<br>
    </td>
    <td align="center">
      인프라<br>
      조각 체결 서비스<br>
      게시판 / 댓글 서비스<br>
    </td>
    <td align="center">
      프론트엔드 전반<br>
    </td>
  </tr>
</table>
</div>

## 3. 🛠️ 개발 환경

### 핵심 기술 스택
- **Backend**: Java 17, Spring Boot 3.5.0, Spring Cloud 2025.0.0-RC1
- **Frontend**: Next.js 15.3.3, React 19.0.0, TypeScript, TailwindCSS 4.0
- **Database**: MySQL 8.0, MongoDB, Redis 7.0
- **Message Queue**: Apache Kafka, Spring Kafka
- **Infrastructure**: Docker, AWS, Netflix Eureka
- **External APIs**: 한국투자증권 API, 토스페이먼츠 API, OpenAI API

### 🖥️ FrontEnd 
<div align="center">
  <img src="https://img.shields.io/badge/Next.js%2015.3.3-000000?style=flat&logo=nextdotjs&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/React%2019.0.0-61DAFB?style=flat&logo=react&logoColor=black" height="28"/>
  <img src="https://img.shields.io/badge/TailwindCSS%204.0-06B6D4?style=flat&logo=tailwindcss&logoColor=white" height="28"/></br>
  <img src="https://img.shields.io/badge/Zustand-FF6B35?style=flat" height="28"/>
  <img src="https://img.shields.io/badge/NextAuth.js-9C33FF?style=flat" height="28"/>
  <img src="https://img.shields.io/badge/ECharts-AA344D?style=flat" height="28"/>
  <img src="https://img.shields.io/badge/Toss%20Payments-0064FF?style=flat" height="28"/>
</div>

### ⚙️ BackEnd
<div align="center">
  <img src="https://img.shields.io/badge/Java%2017-ED8B00?style=flat&logo=openjdk&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Spring%20Boot%203.5.0-6DB33F?style=flat&logo=springboot&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Spring%20Cloud%202025.0.0-6DB33F?style=flat&logo=spring&logoColor=white" height="28"/></br>
  <img src="https://img.shields.io/badge/MySQL%208.0-4479A1?style=flat&logo=mysql&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Redis%207.0-DC382D?style=flat&logo=redis&logoColor=white" height="28"/></br>
  <img src="https://img.shields.io/badge/Spring%20Data%20JPA-6DB33F?style=flat&logo=spring&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/QueryDSL-4285F4?style=flat" height="28"/>
  <img src="https://img.shields.io/badge/Spring%20Security-6DB33F?style=flat&logo=springsecurity&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Apache%20Kafka-231F20?style=flat&logo=apachekafka&logoColor=white" height="28"/></br>
  <img src="https://img.shields.io/badge/Swagger-85EA2D?style=flat&logo=swagger&logoColor=black" height="28"/>
  <img src="https://img.shields.io/badge/Gradle-02303A?style=flat&logo=gradle&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Redisson-DC382D?style=flat&logo=redis&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/OpenFeign-6DB33F?style=flat&logo=spring&logoColor=white" height="28"/>
</div>

### 🐳 Infrastructure & DevOps
<div align="center">
  <img src="https://img.shields.io/badge/AWS-FF9900?style=flat&logo=amazonaws&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Netflix%20Eureka-E50914?style=flat" height="28"/>
  <img src="https://img.shields.io/badge/Spring%20Gateway-6DB33F?style=flat&logo=spring&logoColor=white" height="28"/></br>
  <img src="https://img.shields.io/badge/Spring%20Actuator-6DB33F?style=flat&logo=spring&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white" height="28"/>
  <img src="https://img.shields.io/badge/GitHub%20Actions-2088FF?style=flat&logo=githubactions&logoColor=white" height="28"/>
</div>

## 4. 📱 주요 기능

### 📱 화면 미리보기
<div align="center">
  <table>
    <tr>
      <td align="center"><strong>로그인</strong></td>
      <td align="center"><strong>회원가입</strong></td>
      <td align="center"><strong>공모</strong></td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/93a0b947-414b-4955-aa46-78e8ac38d09e" alt="로그인 화면" width="250"/>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/d7b56be8-39ab-45f7-b2e5-6bf0c549fbf4" alt="회원가입 화면" width="250"/>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/333b06ba-21ed-4b6c-abcf-1a3384905d4a" alt="공모 화면" width="250"/>
      </td>
    </tr>
  </table>
  
  <table>
    <tr>
      <td align="center"><strong>공모-투표</strong></td>
      <td align="center"><strong>공모-경매</strong></td>
      <td align="center"><strong>조각</strong></td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/a118e951-9493-4a34-b17a-f1637f98ea76" alt="공모-투표 화면" width="250"/>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/bdff1998-1ace-437a-8b1a-ae86e8d7ba1f" alt="공모-경매 화면" width="250"/>
      </td>
      <td align="center">
        <img src="https://github.com/user-attachments/assets/baea81e2-fb30-4387-9036-0be6e9e09be0" alt="조각 화면" width="250"/>
      </td>
    </tr>
  </table>
  
  <table>
    <tr>
      <td align="center"><strong>상품판매</strong></td>
      <td align="center"><strong>댓글</strong></td>
      <td align="center"><strong>AI 예측가</strong></td>
    </tr>
    <tr>
      <td align="center">
        <!-- 상품판매 GIF 추가 예정 -->
        <img src="https://github.com/user-attachments/assets/aa884be9-9aad-4e99-b6ee-5131a408e5ab" alt="상품판매 화면" width="250"/>
      </td>
      <td align="center">
        <!-- 댓글 GIF 추가 예정 -->
        <img src="https://github.com/user-attachments/assets/75460749-fa67-45b7-b014-6fa7f836065e" alt="댓글 화면" width="250"/>
      </td>
      <td align="center">
        <!-- AI 예측가 GIF 추가 예정 -->
        <img src="https://github.com/user-attachments/assets/17ff09d4-d8b6-4e34-9d65-7f81159aa8cd" alt="AI 예측가 화면" width="250"/>
      </td>
    </tr>
  </table>
</div>

### 1. 사용자 관리 (AuthService + MemberService)
- **회원가입/로그인**: 이메일, 전화번호 SMS 인증
- **JWT 인증**: 무상태 토큰 기반 인증 시스템
- **비밀번호 관리**: 비밀번호 변경/재설정 기능
- **프로필 관리**: 닉네임, 프로필 이미지 업로드

### 2. 상품 관리 (ProductService + ProductReadService)
- **상품 등록**: AI 기반 가격 예측과 함께 상품 등록
- **카테고리 관리**: 메인/서브 카테고리 분류 시스템
- **상품 조회 최적화**: 읽기 전용 서비스로 성능 최적화
- **상품 상태 관리**: 공모, 투표, 경매 단계별 상태 관리

### 3. 조각 투자 (PieceService)
- **조각 생성**: 상품을 작은 조각으로 분할
- **조각 분배**: 공모 완료 후 조각 분배 시스템
- **실시간 거래**: 조각 매매 기능 (매수/매도)
- **소유권 관리**: 조각별 소유자 추적 및 보유 현황
- **SSE 시세 스트리밍**: 실시간 호가 및 체결가 업데이트

### 4. 공모 (FundingService)
- **공모 등록**: 새로운 자산 공모 등록
- **공모 참여**: 동시성 처리를 통한 공모 참여 시스템
- **공모 상태 관리**: READY, FUNDING, COMPLETED, CANCELLED 상태 관리
- **찜하기 기능**: 관심 공모 상품 찜하기 및 관리

### 5. 실시간 경매 (AuctionService)
- **투표 시스템**: 조각 보유자들이 경매 진행 여부를 투표로 결정
- **경매 자동 생성**: 투표 과반 수 찬성 시 자동으로 경매 생성
- **실시간 입찰**: 동시성 처리를 통한 실시간 입찰 시스템
- **SSE 실시간 업데이트**: 현재 최고 입찰가, 입찰자 등 실시간 확인

### 6. 결제 시스템 (PaymentService)
- **토스페이먼츠 연동**: 안전한 결제 처리
- **가상 지갑 관리**: 가상 지갑 잔액 관리 및 충전/출금
- **브랜드페이**: 토스 브랜드페이 연동
- **거래 내역**: 상세 거래 기록 관리

### 7. 알림 시스템 (AlertService)
- **실시간 알림**: SSE 기반 실시간 알림 전송
- **공용 알림**: 공모 시작/종료, 상품 가격 변동 등
- **개인 알림**: 거래 성공, 투표 종료, 경매 결과 등
- **알림 타입**: 12가지 알림 타입 지원

### 8. 커뮤니티 (BoardService + ReplyService)
- **게시판**: 공지사항, 이벤트, FAQ, 커뮤니티 게시판
- **댓글 시스템**: 댓글, 대댓글, 좋아요 기능
- **AI 문의 응답**: OpenAI 기반 자동 문의 응답
- **커뮤니티 관리**: 조각 상품별 커뮤니티 게시판

### 9. 실시간 데이터 (RealTimeDataService)
- **한국투자 API 연동**: 실시간 주식 시세 연동
- **SSE 시세 스트리밍**: 실시간 호가 및 체결가 스트리밍
- **차트 데이터**: 분봉, 일봉, 기간별 시세 제공
- **WebSocket 연결**: 실시간 데이터 수신 및 처리

### 10. 배치 처리 (BatchService)
- **차트 데이터 집계**: 분/일/월/연단위 가격 집계
- **베스트 상품 집계**: 인기 상품 통계
- **자산 통계**: 사용자별 자산 현황 집계
- **스케줄링**: 정기적인 데이터 처리 작업

## 5. 🏗️ 설계 문서

### 마이크로서비스 구조
<img width="2857" height="1326" alt="Image" src="https://github.com/user-attachments/assets/1d535975-6376-42bd-8d06-c181098f7a88" />

### ERD
<img width="1278" height="719" alt="Image" src="https://github.com/user-attachments/assets/b0588143-8a21-406a-8bd7-2fe0d3551795" />
<img width="1276" height="718" alt="Image" src="https://github.com/user-attachments/assets/52de1506-c5c4-42a9-9a9d-e7034a68e390" />

### 서비스 목록 및 역할

<div align="center">

| 서비스명 | 포트 | 역할 및 기능 |
|:-------:|:----:|:-----------:|
| **gateway** | 8000 | API Gateway, 라우팅, JWT 인증, CORS 처리 |
| **eureka** | 8761 | 서비스 디스커버리, 서비스 등록 및 발견 |
| **authService** | 8081 | 사용자 인증, JWT 토큰 관리, 로그인/회원가입, SMS 인증 |
| **memberService** | 8082 | 사용자 프로필 관리, 회원 정보 CRUD |
| **productService** | 8083 | 상품 관리, 카테고리 관리, AI 가격 예측 서비스 |
| **productReadService** | 8084 | 상품 조회 최적화, 공모/조각 상품 읽기 전용 서비스 |
| **pieceService** | 8085 | 조각 생성/분배, 실시간 거래, 소유권 관리, SSE 시세 스트리밍 |
| **fundingService** | 8086 | 공모 등록/관리, 공모 참여, 찜하기 기능 |
| **auctionService** | 8088 | 실시간 경매, 입찰 관리, 투표 시스템, SSE 가격 업데이트 |
| **paymentService** | 8089 | 토스페이먼츠 연동, 가상 지갑 관리, 브랜드페이 |
| **boardService** | 8090 | 게시판 (공지사항, 이벤트, FAQ, 커뮤니티), AI 문의 응답 |
| **replyService** | 8091 | 댓글 관리, 대댓글 기능, 좋아요 기능 |
| **alertService** | 8092 | 실시간 알림, SSE 스트리밍, 공용/개인 알림 |
| **realTimeDataService** | 8093 | 한국투자 API 연동, 실시간 주식 데이터, SSE 시세 스트리밍 |
| **batchService** | 8094 | 차트 데이터 집계, 베스트 상품 집계, 자산 통계 |

</div>

## 6. 🤝 프로젝트 규칙

### 브랜치 전략
- **main**: 프로덕션 배포 브랜치
- **develop**: 개발 통합 브랜치
- **feature/***: 기능 개발 브랜치
- **fix/***: 긴급 수정 브랜치

### 커밋 메시지
```
feat: 새로운 기능 추가
fix: 버그 수정
docs: 문서 수정
style: 코드 포맷팅
refactor: 코드 리팩토링
test: 테스트 추가
chore: 빌드 업무 수정
```

## 7. 🚀 포팅 매뉴얼

### 환경 준비
```bash
# 필수 소프트웨어 설치
- Java 17+
- Node.js 18+
- MySQL 8.0+
- Redis 7.0+
- Docker & Docker Compose
```

### 🔧 의존성 및 라이브러리

#### 백엔드 공통 의존성
```gradle
dependencies {
    implementation 'org.springframework.boot:spring-boot-starter-data-jpa'
    implementation 'org.springframework.boot:spring-boot-starter-web'
    implementation 'org.springframework.boot:spring-boot-starter-data-redis'
    implementation 'org.springframework.cloud:spring-cloud-starter-netflix-eureka-client'
    implementation 'org.springframework.cloud:spring-cloud-starter-openfeign'
    implementation 'org.springframework.kafka:spring-kafka'
    compileOnly 'org.projectlombok:lombok'
    runtimeOnly 'com.mysql:mysql-connector-j'
    annotationProcessor 'org.projectlombok:lombok'
    
    // Spring Security & JWT
    implementation 'org.springframework.boot:spring-boot-starter-security'
    implementation 'io.jsonwebtoken:jjwt-api:0.12.5'
    implementation 'io.jsonwebtoken:jjwt-impl:0.12.5'
    implementation 'io.jsonwebtoken:jjwt-jackson:0.12.5'
    
    // API Documentation
    implementation 'org.springdoc:springdoc-openapi-starter-webmvc-ui:2.7.0'
    
    // Validation
    implementation 'org.springframework.boot:spring-boot-starter-validation'
    
    // Redis (Redisson)
    implementation 'org.redisson:redisson-spring-boot-starter:3.34.1'
    
    // QueryDSL
    implementation 'com.querydsl:querydsl-jpa:5.1.0:jakarta'
    annotationProcessor 'com.querydsl:querydsl-apt:5.1.0:jakarta'
}
```

#### 프론트엔드 주요 패키지
```json
{
  "dependencies": {
    "next": "15.3.3",
    "react": "19.0.0",
    "react-dom": "19.0.0",
    "typescript": "^5",
    "tailwindcss": "^4.0",
    "next-auth": "^4.24.10",
    "zustand": "^4.4.1",
    "echarts": "^5.5.1",
    "react-hook-form": "^7.53.2"
  }
}
```

### 포팅 절차

> **[1단계] Git 클론 및 프로젝트 폴더 이동**
> ```bash
> # 각 서비스별 저장소 클론
> git clone https://github.com/2-0078/0078-eureka.git
> git clone https://github.com/2-0078/0078-gateway.git
> git clone https://github.com/2-0078/0078-authService.git
> git clone https://github.com/2-0078/0078-memberService.git
> # ... 기타 서비스들
> git clone https://github.com/2-0078/FE-mobile.git
> ```

> **[2단계] 환경 설정 파일 수정**
> ```bash
> # 각 서비스의 application.yml 파일 수정
> # - 데이터베이스 연결 정보
> # - Redis 연결 정보
> # - JWT 시크릿 키
> # - 외부 API 키 (한국투자증권, 토스페이먼츠, OpenAI)
> ```

> **[3단계] DB 마이그레이션 진행**
> ```bash
> # MySQL 데이터베이스 생성
> # 각 서비스별 스키마 생성
> # JPA DDL 자동 생성 또는 초기 데이터 삽입
> ```

> **[4단계] 서비스 실행 순서**
> ```bash
> # 1. Eureka 서버 (포트: 8761)
> cd 0078-eureka && ./gradlew bootRun
> 
> # 2. Gateway (포트: 8000)
> cd 0078-gateway && ./gradlew bootRun
> 
> # 3. 각 마이크로서비스 실행
> cd 0078-authService && ./gradlew bootRun
> cd 0078-memberService && ./gradlew bootRun
> # ... 기타 서비스들
> 
> # 4. 프론트엔드 실행
> cd FE-mobile && npm install && npm run dev
> ```

## 8. 🔒 보안 및 성능

### 보안 특징
- **JWT 인증**: 무상태 토큰 기반 인증
- **CORS 설정**: 교차 출처 리소스 공유 제어
- **입력 검증**: Bean Validation 기반 데이터 검증
- **SQL 인젝션 방지**: JPA 기반 안전한 데이터 접근

### 성능 최적화
- **Redis 캐싱**: 자주 조회되는 데이터 캐싱
- **분산 락**: Redis 기반 동시성 제어
- **배치 처리**: 대용량 데이터 처리 최적화

## 9. 📚 API 문서

### Swagger UI
각 서비스는 Swagger UI를 통해 API 문서를 제공합니다.

- **Gateway**: http://localhost:8000/swagger-ui/index.html
- **개별 Service**: http://localhost:${service-port}/swagger-ui/index.html

## 📞 문의 및 지원

### 개발팀 연락처
- **GitHub 조직**: https://github.com/2-0078
- **문의사항**: 각 서비스 레포지토리의 Issues 활용

---

**Piece of Cake** - Making Investment Simple and Accessible for Everyone 🍰✨
