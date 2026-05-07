# 개발 입문 스터디 3주차

[자기소개 홈페이지](https://gdg-dev-intro-study-delta.vercel.app)

## branch
- <b>나뭇가지</b>: 뭔가 코드를 나눠놓는 느낌
- main 말고 develop으로 브랜치 하나 만들기
- 그리고 나중에 합치면 됨

## css
- <b>인라인 방식</b>: 태그에 직접적으로 썼었음
- 근데 이제 css 파일 만들어서 



### 링크 태그
``` html
<link rel="stylesheet" href="./style.css">
```
- 요런 느낌으로 헤더쪽에 선언하고 css 파일 만들어 놓으면 됨

### css 파일 만들기
``` css
.zzang {
    display: inline-block; /* 글자 크기만큼만 배경색이 칠해지도록 변경 */
    color: white;
    background-color: red ;
    
    padding: 10px 30px;       
    margin: 15px;
    
    border: 5px solid green; 
    border-radius: 50px; 
}
``` 
-> 요런 느낌

## 색상 정의하는 다른 방법
1. <b>rgb</b>: R, G, B(빨강 초록 파랑)을 2의 8제곱까지 표현할 수 있는거 같음
2. <b>헥스코드</b>: 위 값을 16진수로 표현함, 앞에 샵 붙여줘야함

### 추가적인 색깔 정의 내용
- cascading: 약간 아까 색깔 적용할 때 우선 순위같은 느낌
- 그리고 해보니까 색깔 넣을 때 마우스로 색깔 지정할 수 있음

## margin과 padding
- <b>margin</b>과 <b>padding</b>은 뭔가 박스를 생각했을 때 margin은 바깥쪽을 담당하고, padding은 안 쪽을 담당하는 느낌.
- 간단히 생각했을 때 margin은 외부의 거리이고, padding은 내용 사이의 여백 느낌, 배경색이 칠해지는게 padding이다!!

### margin, padding 사용법
``` css
margin: 10px 10px 10px 10px; // 각각 상 우 하 좌 여백을 의미함
margin: 10px 10px; // 각각 상하, 좌우 여백을 의미함
margin: 10px; // 상하좌우를 통일
```
- padding도 똑같은 방식으로 사용함

## 마크다운 추가적인 것들

#### 코드블럭 
- 코드를 여기에 적을 때 블럭 만드는 것
- ` 3개를 쓰면 이 공간을 만들 수 있음

#### heading
- "#" 을 써서 h1, h2, h3 느낌으로 만드는 것
- 한개를 쓰면 h1으로 큰 제목, 두 개면 h2, 6개까지 되는 것 같음

#### bold
- ```<b></b>```를 써서 굵은 글씨 표현
- <b> 요런 </b> 느낌

#### list
```
- 
- // 이걸 쓰면 순서 없는 리스트 느낌

1. // 이런식으로 숫자를 쓰면 자동으로 숫자 리스트 생성됨
```
- 여기서 탭을 쓰면
    - 이런식으로
        - 계속 뭔가 만들어 나갈 수 
            1. 있는 느낌이고
            2. 이런 식으로 해서 사용이 가능하다.

#### link
```
[클릭할 이름](링크 주소)
```
- 이런 느낌으로 주소를 쓰면 되는 거 같다!