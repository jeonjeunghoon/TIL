# 오늘 공부한 내용

- 부트스트랩 적용
- WEB-INF 폴더

# 부트스트랩 적용

[Introduction](https://getbootstrap.com/docs/5.1/getting-started/introduction/)

1. 위 페이지 접속
2. CSS 목차의 코드를 jsp 파일의 </head> 전에 삽입
    
    ```html
    <head>
    	...
    	요기에 삽입
    </head>
    ```
    
3. JS 목차의 코드를 jsp 파일의 </body> 전에 삽입
    
    ```html
    <body>
    	...
    	요기에 삽입
    </body>
    ```
    
4. 필요한 기능의 코드를 <body> 부분에 삽입하면 된다.
    
    ```html
    <body>
    ...
    요기에 삽입
    ...
    js목차코드
    </body>
    ```
    

# WEB-INF

해당 폴더 안에 있는 `*.jsp` 파일은 브라우저에서 직접적으로 접근이 불가능하다. (아래와 같이)

- [localhost:8080/test.jsp](http://localhost:8080/test.jsp) —> 404 오류

반대로 web 폴더에 있는 `*.jsp` 파일은 직접적으로 접근이 가능하다.

- [localhost:8080/test.jsp](http://localhost:8080/test.jsp) —> 접근 성공

왜 이렇게 설계되었을까?

## WEB-INF

### 장점

- 유저의 직접 접근이 어려워 보안성이 높다.

### 단점

- 직접적으로 view를 볼 수 없다. 또한 직접적으로 볼 수 없기 때문에 `<a>` 태그로 이동이 불가능하며 Controller를 통해서만 이동이 가능하다.

## WEB

### 장점

- 직접적으로 접근할 수 있어 jsp 파일의 경과를 바로 확인 가능

### 단점

- 유저의 직접 접근이 가능해 보안성이 떨어진다.
