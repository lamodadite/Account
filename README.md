# Account
계좌 시스템 개발 실습

<aside>
💡 계좌(Account) 시스템의 전반적인 구조와 기능 구현

</aside>

## 활용 기술

- Spring boot 2.6.x (JDK 11)
- Gradle
- Junit5
- H2 Database
- JPA
- Redis
- Mockito
- Lombok

## 엔티티 구조

![image](https://user-images.githubusercontent.com/102534186/184944651-6ebfb88e-41ac-4417-b3de-74caae5b40ab.png)

## 제공하는 기능(API)

### 계좌(Account) 관련 기능

1. 계좌 생성
2. 계좌 해지
3. 계좌 확인

### 계좌(Transaction) 관련 기능

1. 잔액 사용 (거래 생성)
2. 잔액 사용 취소 (거래 취소)
3. 거래 확인

### 사용자 관련 기능

→ 구현 간소화를 위해 DB에 데이터 자동 입력하도록 구현
