# PJ01_Backend_Ezen

조별 자바 프로젝트 CRUD

#1. 개요

학습한  CRUD 기술을 활용하여 이젠아카데미학원 홈페이지를 구현하고자 한다.


#2. DB 구성

프로젝트명 : Ezen Project 
작업명 : 게시판, 로그인, 회원가입 기능 구현
회원 테이블명 : ezen_member
게시판 테이블명 : ezen_board

![db구성](https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/2121e3ce-5c50-4d6b-aeaf-ca0f35898c09)


#3. 구성

이 프로젝트는  Java Server Pages(JSP), Servlet, HTML, CSS, 그리고 JavaScript를 활용한 웹 기반 애플리케이션입니다. JSP와 Servlet은 백엔드에서, HTML/CSS와 JavaScript는 프론트엔드에서 각각 활용되어 이 웹 애플리케이션의 구조를 형성하고 있습니다.

1)   Java Server Pages(JSP): JSP는 HTML 코드에 Java 코드를 삽입하여 동적 웹 페이지를 생성하고 서버측 컴포넌트를 개발하는 데에 사용되었습니다. 이를 통해 사용자 요청에 따라 동적으로 변경되는 웹 페이지를 만들 수 있습니다.
2)   Servlet: Servlet은 클라이언트의 요청을 처리하고, 그에 따라 응답을 생성하는 데 사용되었습니다. 이러한 과정은 이 프로젝트에서 백엔드 로직을 구현하는 데 필수적인 컴포넌트로 작용하고 있습니다. 또한, 클라이언트 요청에 따라 데이터를 처리하고 JSP에 전달하여 동적 웹 페이지를 생성하는 역할을 수행합니다.
3)   HTML/CSS: HTML과 CSS를 사용하여 프론트엔드를 구성하였습니다. HTML은 웹 페이지의 구조를 정의하는데 사용되었고, CSS는 웹 페이지의 레이아웃, 색상, 글꼴 등 디자인 요소를 스타일링하는 데 사용되었습니다.
4)   JavaScript: avaScript는 웹 페이지에서 동적인 기능을 구현하는 데 사용되었습니다. 이를 통해 사용자와 웹 페이지 간의 상호작용을 가능하게 하며, 페이지 내의 요소를 동적으로 업데이트할 수 있습니다.


#4. Work-Flow

![walk_flow](https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/93452860-db5a-489f-a0c7-8721b100695f)

![게시판](https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/a013c19f-15e1-4e37-896a-6544dc22c48e)



이 프로젝트는 기본적인 회원 관리 시스템과 게시판 기능을 중심으로 구성되어 있습니다. 사용자의 워크플로우는 아래와 같습니다.
1)   회원가입 :  사용자는 처음으로 시스템에 접근할 때 회원가입 프로세스를 거칩니다. 사용자는 필요한 개인 정보를 입력하고, 이 정보는 데이터베이스에 저장됩니다. 회원 가입이 완료되면 사용자는 자신의 계정으로 로그인할 수 있습니다.
2)   로그인:  로그인은 사용자가 시스템에 접근할 수 있는 권한을 부여받는 과정입니다. 사용자는 회원가입시 설정한 아이디와 비밀번호를 입력하여 로그인합니다.
3)   로그아웃:  사용자는 언제든지 시스템에서 로그아웃할 수 있습니다. 로그아웃하면 현재 세션이 종료되고, 다시 로그인해야 시스템을 이용할 수 있습니다.
4)   내 정보:  로그인한 사용자는 "내 정보" 섹션을 통해 개인 정보를 확인하고 수정할 수 있습니다. 사용자는 이메일, 아이디, 비밀번호 등의 정보를 업데이트 할 수 있습니다.
5)   글 작성:  로그인한 사용자는 게시판에서 새 글을 작성할 수 있습니다. 사용자는 제목과 내용을 입력하고, 이 글은 다른 사용자들이 볼 수 있도록 게시판에 게시됩니다.
6)   글 수정/삭제:  사용자는 자신이 작성한 글을 언제든지 수정하거나 삭제할 수 있습니다. 수정하려면 원하는 글을 찾아 수정 버튼을 눌러 변경 사항을 입력하고, 삭제하려면 삭제 버튼을 누릅니다.
7)   검색 기능: 게시판에서는 사용자가 특정 키워드를 기반으로 게시물을 검색할 수 있습니다. 이 기능은 사용자가 원하는 정보를 더 빠르게 찾는 데 도움을 줍니다.

이런 워크플로우는 사용자가 시스템을 쉽고 효과적으로 이용하도록 돕는 기본적인 프레임워크를 제공합니다. 이러한 각 단계는 사용자와 시스템 간의 상호작용을 최적화하고 사용자 경험을 향상시키는 데 중요한 역할을 합니다.

#5. 프로젝트 시연

1. 회원가입 및 로그인 관련

회원가입 1

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/30c8c03f-ce3f-499b-86dd-6fee9ec3f2f5

회원가입 2

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/39d42217-2ba1-4fb8-b303-90ab2d741800

회원정보수정

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/d2dcf902-7e1c-447f-be8f-8b0d419be109

회원탈퇴

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/c6dec211-0c29-4936-a96a-bcb97d7e9e18

로그인확인_공지사항

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/7817d119-6af3-4594-a0ce-0c6c1e7cecf4

2. 게시판 관련

게시판글쓰기

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/01d2931f-222d-40f8-a838-1948f8e61aac

글수정삭제

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/2824ad40-2f45-41e7-ab0f-48369184733f

게시판분류별서치

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/e402e2bb-d054-4280-b667-4364ebd63ade

3. 기타

관리자

https://github.com/cherrimy/PJ01_Backend_Ezen/assets/118973103/8c124ef6-f86b-4bfc-9d9f-21ce6b512d8a
