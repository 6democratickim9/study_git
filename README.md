### 1. 생활코딩 html css javascript 학습내용 및 코드 업로드

* HTML

  * ```<strong><u>강조하고 싶은 글자</u></strong>```
  * ```<img src"이미지 주소 첨부" width="100%">```
  * 새로운 창을 만드려면 target = "blank"

  

* CSS

  * tag<class<id
  * 더 가까이에 있는 명령이 더 큰 영향력을 갖는다.
  * block level element(태그랑 같음)
  * inline level element(자기 자신의 컨텐츠 크기만큼의 크기를 갖는 엘리먼트)
  * 자기 부피만큼 쓰게하려면 display: inline/block;
  * 컨텐츠와 테두리 사이 간격 만드려면 padding/margin 으로 패딩 사이 간격 정하기

  

* JAVA SCRIPT

  * 실행은 script 태그로

  * 변수 선언 시 ```var 변수이름```

  * CSS와 자바 스크립트의 백그라운드 컬러 호출 방식에는 차이가 있다.

    ``` background-color: ; /  backgoundColor: ;```

  * 자바스크립트는 상호작용하는 언어이기 때문에 시간의 순서에 따라 실행된다!

  * if (document.querySelector('#id값').value =='')

  * var 변수선언 = 저장하고 싶은 변수의 값

    <script>

    ```'+변수이름[i]+'-->i 안에 있는 값은while 문에 따라 값 바뀜```

    </script>

  

  * ```function 함수이름 (인자설정){```

    ``` 함수 내용 ``` 

    ```return (리턴 값 있으면 리턴값 설정)```

    ```}```

  

  * ```함수 호출(매개변수);```

  

  * onclick 안에서 this --> tag 를 가리키는것

  * 독립함수--> this에는 버튼이 없어서 전역객체가 됨

  * 배열 = []

    객체 = {}(딕셔너리형)

    >  객체 삽입 시

    1. 객체.키 이름 = "value(문자형)";
    2. 객체 ["키 이름"] = "value";

    * --> 2번은 불러올 때: 객체 이름.["키값"]

    * for 문 돌려서 출력 시 document.write(객체 이름[키])

    ``` 객체이름.함수이름(프로퍼티) = function(){```

    ```for (var key in this(= 객체자신))--> 메소드```

    ```}```

    * == function 함수이름(){}

    * 실행 시: 객체이름.함수이름();