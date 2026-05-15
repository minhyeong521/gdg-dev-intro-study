# 개발 입문 4주차

[자기소개 홈페이지](https://gdg-dev-intro-study-delta.vercel.app)

## branch
- develop을 보면 1개 코드가 뒤쳐졌다 나옴
- develop에는 week4세팅이 없고 main에는 있을때
- develop에 다른거 넣기

## Git Stage
- .github는 숨긴 항목 처리 되있어서 파일탐색기로 들어가서 보기 > 표시 > 숨긴항목을 체크하면 된다. 

- 이 안의 파일들로 git이 우리 파일을 관리하고 있음
- index라는 곳에 add를 한 정보들이 들어가게 됨
- add를 하면 index 용량이 늘어남 -> 새로운 파일이 추가됬구나 알 수 있음
- commit을 하면 commit id가 생김 -> de0e717이런 느낌

## 충돌 실험
- pull request를 날리면 예전에 썻던 템플릿이 나온다. 자동으로 합칠 수 없다고 나오고 브랜치가 충돌이 되서 해결이 필요함
- develop에 어떤 내용, main에 어떤 내용이 있고 뭐를 고를래 이런 느낌으로 나옴, 선택을 해도 되고 직접 코드를 써도 됨

## convention
- 관습, 관례

### commit convention
- feat, fix, docs, style, refactor, chore
- 컨벤션이 있는 이유: 커밋을 안 눌러봐도 어떤 의도로 썻는지 알 수 있게 하는게 중요함
- 브랜치도 이름짓는 방식이 있다
1. feat: 새로운 기능을 추가할 때
2. fix : 버그를 수정할 때
3. docx: 문서 수정
4. style: 코드 의미에 영향을 주지 않는 변경
5. refactor: 코드 리펙토링
6. test: 테스트 코드를 추가하거나 수정했을 때
7. chore: 빌드 작업, 패키지 매니저 설정 변경 등

#### 예시
``` Bash
git commit -m "feat: wrapper 컴포넌트 제작"
```


## github flow
- github에서 권장하는 방식으로, 단순하고 직관적이다. 
- <b>핵심 원칙</b>: 
    1. main 브랜치는 항상 배포 가능해야 함
    2. 새로운 작업은 main에서 따온 새로운 브랜치에서 한다
    3. 작업이 끝나면 pull request를 한다
    4. 팀원들과 코드 리뷰 후 승인되면 merge한다
    5. 병합된 main은 즉시 배포한다. 

- <b>장점</b> : 흐름이 단순하고 의사소통이 중심이 된다. 빠른 배포에 유리하다
- <b>단점</b> : 테스트 자동화가 중요하다. 


