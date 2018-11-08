# eomcs-java-project

[엄진영의 코딩스쿨]에서 강의하는 "자바 프로젝트 실습" 교육 과정의 소스를 보관하는 저장소이다.
자바 프로그래밍 기술을 단계별로 익힐 수 있도록 프로젝트를 버전으로 구분해 놓았다.
각 버전 별로 자바의 주요 기술을 어떻게 활용하는 지 그 방법을 배울 수 있다.
또한 버전을 따라 공부하다 보면 과거에서 최근까지 애플리케이션 아키텍처가
어떻게 변화해 왔는지 간접적으로 경험할 수 있다.
이는 오래전에 구축된 시스템에서 최근에 구축된 시스템까지 유지보수 해야하는 개발자에게
특히 도움이 될 것이다.


## 대상자

- 자바 기본 문법을 공부중인 분
- 서블릿/JSP를 학습하였거나 학습하려는 분
- C/C++, Python 등 다른 프로그래밍 언어를 알고 있는 데, 자바 프로그래밍을 빠르게 배우고 싶은 분
- 자바 기본 문법을 공부하였는데 어떻게 응용해야 할 지 모르겠는 분
- 다양한 오픈 소스를 자바 애플리케이션에 개발에 적용하는 방법을 배우고 싶은 분
- 스프링 프레임워크 기반 프로젝트에 참여중이거나 참여할 예정인 분
- 자바 웹 애플리케이션 프로젝트의 유지보수를 맡고 있거나 맡을 예정인 분


## 학습 목표

이 교육과정을 통해 다음을 배울 수 있다.  

- 자바 언어에서 제공하는 각종 문법의 목적을 이해하고 활용하는 방법
- 애플리케이션 개발에 디자인 패턴을 적용하는 방법
- 스프링 프레임워크, 마이바티스 등 오픈 소스 프레임워크를 프로젝트에 적용하는 방법
- 웹 애플리케이션의 아키텍처의 발전 과정을 이해

## 프로젝트 버전 및 학습 목표

### 0.1 개발 도구 준비하기

- OpenJDK 11 설치 및 환경 설정
- Eclipse 2018-09 설치 및 환경 설정
- Visual Studio Code 설치 및 환경 설정
- Scoop(Win)/Homebrew(macOS) 패키지 관리자 설치
- Gradle 빌드 도구 설치
- Git 형상관리 도구 설치
- MariaDB 데이터베이스 설치

### 0.2 강의 자료 가져오기

- github.com 사이트에 가입하기
- github.com 의 저장소를 로컬(개발 PC)로 복제하기

### 0.3 개인 저장소 만들기

- github.com 에 개인 저장소 만들기
- github.com 의 개인 저장소를 로컬로 복제하기

### 1.0 - 자바 애플리케이션 프로젝트 만들기

- `그레이들`을 이용하여 프로젝트 디렉토리를 구성하는 방법
- `아파치 메이븐` 프로젝트의 디렉토리 구조를 이해하기
- `그레이들`로 빌드하고 실행하는 방법

### 1.1 - `이클립스 IDE`로 프로젝트 다루기

- `그레이들`을 이용하여 `이클립스` 호환 프로젝트로 전환하는 방법
- `이클립스` 워크스페이스로 프로젝트를 가져오는 방법
- `이클립스`에서 빌드하고 실행하는 방법

### 1.2 - github.com에 프로젝트 공유하기

- .gitignore 파일을 편집하는 방법
- github.com 의 저장소에 프로젝트를 공유하는 방법

### 1.3 - 리터럴과 콘솔 출력 다루기

- 값을 콘솔로 출력하는 방법

### 1.4 - 변수와 키보드 입력 다루기

- 키보드로부터 값을 입력 받는 방법
- 값을 저장하기 위해 변수를 이용하는 방법

### 1.5 - 배열과 흐름 제어문 활용하기

- 배열을 활용하여 여러 개의 데이터를 저장하는 방법
- 반복문과 조건문을 사용하여 실행 흐름을 제어하는 방법

### 1.6 - 클래스로 데이터 타입을 만들기

- 클래스를 활용하여 여러 개의 데이터를 한 단위로 묶는 방법
- 클래스와 인스턴스의 관계를 이해하기
- 인스턴스와 레퍼런스의 관계를 이해하기

### 1.7 - 기본 문법의 활용
 
- 변수, 상수, 연산자, 조건문, 반복문, 블록, 배열 등 프로그래밍 기본 문법의 종합 활용법

### 1.8 - 메서드의 존재 이유

- 메서드를 활용하여 코드를 기능 단위로 분리하는 방법
- 리팩토링: 메서드 추출(Extract Method)

### 1.9 - 클래스로 메서드를 분류하기

- 클래스를 이용하여 관련 메서드를 묶어 관리하는 방법

### 2.0 - 패키지로 클래스를 분류하기

- 패키지를 이용하여 관련 클래스를 분류하는 방법

### 2.1 - 클래스 변수와 클래스 메서드의 한계

- 클래스 변수와 메서드의 한계를 이해하기

### 2.2 - 인스턴스 변수와 인스턴스 메서드가 필요한 이유

- 인스턴스 변수와 메서드를 사용하는 방법
- 인스턴스 변수를 사용할 때의 이점
- 인스턴스 메서드를 사용하는 이유 

### 2.3 - 생성자가 필요한 이유

- 인스턴스를 사용하기 전에 필요한 값을 준비하는 방법
- 생성자의 용도 이해

### 2.4 - 인스턴스 연산자와 메서드

- 메서드를 활용하여 인스턴스 값을 다루는 연산자를 정의하는 방법
- 캡슐화와 셋터/겟터의 의미

### 2.5 - UI 코드와 데이터 처리 코드를 분리하기

- 데이터 처리 코드를 캡슐화하는 방법
- 캡슐화를 통해 얻을 수 이점 이해하기 

### 2.6 - 다형성과 형변환 응용

- 데이터 처리 클래스를 일반화하여 재사용성을 높이는 방법
- 다형적 변수의 활용해야 하는 이유
- 형변환이 필요한 이유

### 2.7 - 제네릭을 사용하는 방법과 이점

- Object 타입의 한계를 극복하는 제네릭 활용법

### 2.8 - CRUD 기능 완성

- 수업/회원/게시판에 대해 CRUD 완성하기

### 2.9 - ArrayList 대신 Linked List 자료구조 사용하기

- Linked List 자료구조를 구현하는 방법
- Linked List 의 구동원리 이해하기
- ArrayList와 LinkedList의 장단점 비교하기
- 중첩 클래스의 활용

### 3.0 - Stack 자료구조 구현과 활용

- Stack 자료구조를 구현하는 방법
- Stack 의 구동원리 이해하기
- Stack 의 활용 사례
- 상속의 활용

### 3.1 - Queue 자료구조 구현과 활용

- Queue 자료구조를 구현하는 방법
- Queue 의 구동원리 이해하기
- Queue 의 활용 사례
- 상속의 활용

### 3.2 - 사용 규칙을 정할 때는 인터페이스를 활용하자!

- 인터페이스를 이용하여 사용 규칙을 정의하는 방법
- 인터페이스의 용도와 이점을 이해하기

### 3.3 - `Iterator` 디자인 패턴의 활용

- 목록을 다루는 자료구조와 상관없이 일관된 방법으로 데이터를 꺼내는 방법
- `Iterator` 디자인 패턴의 용도와 이점을 이해하기
- 익명 중첩 클래스의 활용

### 3.4 - 자바 컬렉션 API 사용하기

- 자바에서 제공하는 자료구조 구현체를 활용하는 방법

### 3.5 - `Command` 디자인 패턴의 활용

- `Command` 디자인 패턴으로 메서드를 객체화하는 설계 방법
- `Command` 디자인 패턴의 활용

### 3.6 - 예외가 발생했을 때 시스템을 멈추지 않게 하는 방법

- 예외 처리 문법을 사용하는 방법
- 예외 처리 문법의 존재 의미와 이점

### 3.7 - 파일 입출력 API의 활용

- 애플리케이션을 종료한 후에도 계속 데이터를 유지할 방법
- 파일 입출력 API를 활용하여 데이터를 읽고 쓰는 방법

### 3.8 - 바이너리 형식으로 입출력하는 방법

- 바이너리 입출력 스트림 클래스를 사용하여 객체의 필드 값을 바이너리 형식으로 읽고 쓰는 방법
- DataInputStream/DataOutputStream을 사용하는 방법

### 3.9 - 직렬화와 역직렬화를 이용하여 객체를 통째로 읽고 쓰기

- 직렬화 하는 방법과 역직렬화 하는 방법
- `java.io.Serializable` 인터페이스와 `serialVersionUID` 스태틱 변수 