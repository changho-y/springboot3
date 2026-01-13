# 간단한 웹 프로그램

## sbb 페이지를 요청했을 때 문자열 출력하도록 만들기

<img width="852" height="308" alt="image" src="https://github.com/user-attachments/assets/597c570b-9e12-4075-ace2-9a405a6f53e9" />

- URL을 입력하면 오류를 알리는 화면이 등장한다.
- 404 : 브라우저가 요청한 페이지를 찾을 수 없다는 의미

### 컨트롤러를 작성하여 URL에 대한 매핑을 추가

- 클라이언트의 페이지 요청이 발생하면 스프링 부트는 가장 먼저 컨트롤러에 등록된 URL 매핑을 찾고, 해당 URL 매핑을 발견하면 연결된 메서드를 실행한다.

<img width="558" height="227" alt="image" src="https://github.com/user-attachments/assets/e2ce13e3-9b0a-4ab3-9603-591369226767" />
