## Blog v1.0.0
Spring Framework를 사용하여 제작한 Blog 입니다.

현재의 제 실력이 어느정도인지 알려드리고자 개발하게 되었습니다.



## 개발 환경
* 메인언어 : JAVA v1.8
* 프레임워크 : Spring v4.3.2
* DB : MariaDB v10.1.x

## 사용 기술
* 포스팅 : 권한에 따른 차등적인 CRUD 기능 제공
* 댓글 : ajax 를 사용하여 등록/삭제 기능 제공
* 이메일 : Google SMTP 를 이용한 이메일전송 기능 제공
* 다국어 : session 에서 locale 정보를 가져온 후, properties 파일을 통한 국문/영문 다국어 제공
* 에디터 : CKEditor v4 사용
* XssFilter : lucy-xss-servlet-filter 사용

## 사용 예제
* 댓글에서 등록 기능은 권한없이 이용 가능하지만, 회원가입 제도가 없는 관계로 수정기능은 미제공, 삭제기능은 admin 에게만 권한이 부여됩니다.
* 포스팅 기능은 [로그인 페이지](http://myhyem.cafe24.com/signIn.do)에서 테스트계정 ID : test , PW : test1234 으로
로그인 후, 사용가능합니다.
* 푸터 영역에 있는 Email 기능은 개발자의 이메일 주소로 내용이 전송되는 기능입니다.
* 현재 포스팅 등록에서 이미지 첨부 기능에 문제가 발생하여 수정중에 있습니다.

## 업데이트 내역
* 1.0.0
  * 배포
