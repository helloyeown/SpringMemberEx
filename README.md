# 토이 프로젝트 : 회원 도메인에서의 주문, 할인 예제

   - 스택🔧
      - 서버 : Spring Boot 3.2.2 (지금은 스프링 없는 순수한 자바로만 개발을 진행, 프로젝트 환경설정을 편리하게 하려고 스프링 부트를 사용)
      - Java 17ver
   - 비즈니스 요구사항
      - 회원
         - 회원을 가입하고 조회할 수 있다.
         - 회원은 일반과 VIP 두 가지 등급이 있다.
         - 회원 데이터는 자체 DB를 구축할 수 있고, 외부 시스템과 연동할 수 있다. (미확정)
      - 주문과 할인 정책
         - 회원은 상품을 주문할 수 있다.
         - 회원 등급에 따라 할인 정책을 적용할 수 있다.
         - 할인 정책은 모든 VIP는 1000원을 할인해주는 고정 금액 할인을 적용해달라. (나중에 변경 될 수 있다.)
         - 할인 정책은 변경 가능성이 높다. 회사의 기본 할인 정책을 아직 정하지 못했고, 오픈 직전까지 고민을 미루고 싶다. 최악의 경우 할인을 적용하지 않을 수 도 있다. (미확정)
           
       
      ![image](https://github.com/helloyeown/SpringMemberEx/assets/128343741/e0cd6658-4cca-479a-a62c-34a61cc95260)
     
      ![image](https://github.com/helloyeown/SpringMemberEx/assets/128343741/1f0b969f-72c0-489a-952e-07899e497f06)
     
      ![image](https://github.com/helloyeown/SpringMemberEx/assets/128343741/df7c8adb-85ae-4010-9f50-159749ecb0b8)


