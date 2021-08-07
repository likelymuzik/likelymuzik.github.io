---
layout: post
title:  "02. Hello World 출력하기"
date:   2021-08-07 18:00:00 +0900
categories: Java Github
---
다음 내용은 코드스쿼드 인프런 강의를 참고하여 작성하였습니다.  
[인프런 강의 링크](https://www.inflearn.com/course/java-codesquad/dashboard)

# Hello World 출력하기
-----
* ### 새로운 Project를 생성한다.
(cmd + N) 단축키를 활용하여 [Select a wizard] 창을 연다  
"java project"라고 입력하여 Project 생성메뉴를 선택한다.
![create_project](/assets/img/create_project.png)

* ### Project 이름을 정하고 JRE 버전을 선택한다.
[Finish] 버튼을 클릭하여 생성을 완료한다.  
![select_wizard](/assets/img/select_wizard.png)

* ### 똑같은 방식으로 Class를 생성한다.  
![create_class](/assets/img/create_class.png)
![class_hello](/assets/img/class_hello.png)

* ### Java 소스코드 입력  
```java
public class HelloWorld {
	public static void main(String[] args) {
		System.out.println("Hello World!");
	}
}
```

* ### 단축키를 활용하여 Java 프로그램을 실행한다. (Fn + cmd + F11)
정상적으로 "Hello World!"가 출력된 것을 확인할 수 있다.
![print_hello](/assets/img/print_hello.png)