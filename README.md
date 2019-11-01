## Introduction to React Components ##

### Overview ###
이 코드는 React의 5 가지 주요 컨셉트를 연습하기 위한 code-along workshop입니다: 
1. React.Component class는 무엇이면 어떻게 instance를 instantiate 할 수 있는가.
2. React.Component 렌더하기. JSX를 이용하여 React.Elements 만들기.
3. 어떤 라이프 사이클 메서드가 있는지.
4. State은 어떻게 관리되는가.
5. 렌더된 React.Components에 어떻게 이벤트 핸들러를 붙히는가.
6. 컨트롤된, 컨트롤 되지 않은 필드

### Instructions ###
Index.jsx 파일에서 아래와 같이 컴포넌트를 만들어주세요
1. render 함수 체워넣어주세요
**[element 렌더링 문서](https://ko.reactjs.org/docs/rendering-elements.html)**
2. 유저의 email 주소 입력 값을 받기 위한 component state을 초기화 해주세요.
**[state와 lifecycle 문서](https://ko.reactjs.org/docs/state-and-lifecycle.html)**
3. 유저 email 주소를 최신화 하기 위한 method를 추가해주세요.
4. Component가 처음 mount 했을 때 'https://source.unsplash.com/random'에서 사진을 fetch 해오세요.
5. 윗 단계에서 Fetch 해온 사진을 유저의 프로필 사진으로 등록해주세요.
6. 폼 제출 method를 완성해주세요.
7. 완료 상태에 대한 메세지를 추가해주세요.
**[조건부 렌더링 문서](https://ko.reactjs.org/docs/conditional-rendering.html)**
8. 완성된 component들에 index.scss에 있는 className을 부여해주세요.

### Setup and Running ###
1. Make sure you're using the latest version of node
2. Run `yarn` to install dependencies.
3. Run `yarn dev` and visit the form on localhost:8080

Yarn 미설치인 경우 Yarn 설치 법(mac만)

Homebrew 사용하여 설치
```brew install yarn```

MacPorts 통해 설치 (Node 미설치인 경우 Node도 설치해줌)
```sudo port install yarn```


