# eomcs-java-project-1.8

메서드의 존재 이유 I

- 메서드를 활용하여 코드를 기능 단위로 분리하는 방법
- 리팩토링: 메서드 추출(Extract Method)

## 프로젝트 - 수업관리 시스템  

### 과제 1: 각 명령어를 처리하는 코드를 메서드로 분리하라. 

`App` 클래스의 실행 결과는 이전 버전과 같다.

## 실습

### 관련 소스 

- src/main/java/App.java 변경

### 작업

- App.java
    - App.java.01 : 여러 메서드에서 공통으로 사용할 변수는 스태틱 변수로 선언한다.
    - App.java.02 : 수업 등록, 목록 출력 코드를 별도의 메서드로 분리한다.
    - App.java.03 : 회원 등록, 목록 출력 코드를 별도의 메서드로 분리한다.
    - App.java.04 : 회원 등록, 목록 출력 코드를 별도의 메서드로 분리한다.
    - App.java : 명령어 입력 받는 코드를 별도의 메서드로 분리한다.