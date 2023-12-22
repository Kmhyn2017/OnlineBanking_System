# OnlineBanking_System

프로그래밍 언어: C#, Javascript, CSS, HTML
ASP.NET Framework 및 MVC를 사용하여 생성한 간단한 온라인 뱅킹 시뮬레이션 웹사이트

## 기능
로그인/등록

1. 성공적인 등록 시 확인 이메일 발송

2. 요청 시 활성화 이메일 재전송

3. OTP(일회용 비밀번호) 시스템을 사용한 안전한 비밀번호 재설정

4. 제출 전 실시간 양식 유효성 검사

5. 고객을 위한 새로운 은행 계좌 개설

6. 홈 대시보드에서 은행 계좌 활동 내역 분석

7. 각 계좌에 대한 거래 내역 확인

8. 고객 자체 계좌 간 자금 이체

9. 송금할 수 있는 수취인 생성 및 저장

10. 생성된 수취인에게 자금 이체

11. 더 이상 필요하지 않은 수취인 삭제

## 코드
개요
1. HomeController -> 로그인한 사용자가 접근 가능한 페이지 및 데이터 출력

2. UserController -> 사용자 관리, 즉 로그인, 가입, 확인 이메일 재전송, 비밀번호 잊어버림

3. AccountController -> 은행 계좌 관리, 즉 자금 이체, 새로운 계좌 개설

PayeeController -> 수취인 관리, 수취인에 대한 CRUD 기능
4. PayeeController -> Payee management i.e. CRUD functions for a Payee
