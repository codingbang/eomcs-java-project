# eomcs-java-project-5.3-server

MyBatis의 다양한 기능 활용법

- MyBatis의 다양한 기능을 사용하는 방법


## 프로젝트 - 수업관리 시스템  

`MyBatis`에게 제공하는 다양한 기능을 사용하면 좀 더 편리하게 코드를 작성할 수 있다.

### ver 5.3.0 - `MyBatis` SQL 매퍼에서 사용할 값 객체(Value Object)에 별명을 부여한다.

SQL 매퍼 파일에서 자바 클래스를 지정할 때 패키지 이름까지 지정해야 한다. 그런데 MyBatis 설정 파일에서 클래스에 대한 별명을 등록해두면 SQL 매퍼 파일에서 사용하기 편하다.

- mybatis-config.xml
    - `<typeAliases/>` 태그를 사용하여 별명을 등록한다.
- XxxMapper.xml
    - 클래스 이름을 지정할 때 별명을 사용한다. 

##### 실습 결과

`eomcs-java-project-client`프로젝트의 `ClientApp`을 실행한다.
```
이전과 같다.
```

## 실습 소스

- com/eomcs/lms/mapper/BoardMapper.xml 변경
- com/eomcs/lms/mapper/MemberMapper.xml 변경
- com/eomcs/lms/mapper/LessonMapper.xml 변경
- com/eomcs/lms/mapper/PhotoBoardMapper.xml 변경
- com/eomcs/lms/mapper/PhotoFileMapper.xml 변경
