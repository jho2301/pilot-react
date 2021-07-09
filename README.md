## 파일럿 프로젝트 - React


## 시연

![main](https://user-images.githubusercontent.com/44419181/124958372-0e330a00-e055-11eb-85b7-aceecb85bd89.gif)

## 기술스택
사용기술 스택은 다음과 같습니다.

빌드 툴
- webpack + ts-loader

언어
- typescript

SPA 프레임웍
- react

CSS in JS
- styled-components

전역상태관리
- recoil

테스트 툴
- react-testing-library
- storybook

## 웹 VSCode 환경

https://github.surf/jho2301/pilot-react/blob/HEAD/results/jho2301/README.md

## 스토리북

https://60e72955ee4db40049b700f0-gnjvrwyqhk.chromatic.com/

## 주안점

- CRA 사용안하고 빌드툴 config파일부터 작성했습니다.
- 처음에 기능요구사항 구상하고 TDD로 코드짜려고 노력해봤습니다
- CDD 따라서 스토리북으로 가장 작은 컴포넌트 요소부터 작성하려고 했습니다.
- 클래스문법은 [APIClient](https://github.surf/jho2301/pilot-react/blob/HEAD/results/jho2301/src/util/API.ts)만들면서 적용해볼 수 있었습니다.
- 로그인 기억하기 기능 구현하면서 세션스토리지하고 로컬스토리지를 분리해 사용했습니다.
- 라우터가드 만들어봤습니다.
- 디자인은 심플하고 깔끔하게 구성하려고 했습니다.
- 최대한 코드의 중복을 없애고, 추상화, 레이어 분리하려고 고민 했습니다.
- 통합테스트 위주로 테스트 구성하려고 했습니다
- 테스트가 서버에 의존안하도록 목서

React 파일럿 프로젝트를 진행한다.

본인이 알고 있는 지식, 할 수 있는 모든것을 총 동원하여 만든다.

로그인을 통해 토큰을 입력받은 뒤 회원정보를 보여주는 페이지로 이동한다.

## PR

- React 프로젝트는 `./results/본인아이디`에 생성한다.
- README.md 마지막 `자랑하기`에 본인의 repository 주소를 넣고 PR

## 설치

1. [Docker](https://www.docker.com/) 설치
2. [Repository](https://github.com/leejaycoke/pilot-auth) Fork & Clone

```bash
$ docker build -t pilot-auth .
$ docker run --name pilot-auth -p 5000:5000 pilot-auth

# restart
$ docker start -a pilot-auth
```

> 서버가 재시작 되면 인증 토큰이 갱신됩니다.

## 요구 사항

- git (github)
- webstorm
- React
- Typescript
- Test Case 작성
- 자바스크립트 Object `{}` (type object 포함)의 사용을 하지말아보자!
- API 요청, 응답 데이터는 클래스를 이용

## 구현 내용

화면 구성, 디자인은 자유

### 로그인 페이지

아이디, 비밀번호를 입력하고 로그인하는 화면을 만든다.  
로그인이 완료되면 회원정보 페이지로 이동한다.

### 회원정보 페이지

회원정보를 보여주는 화면

## API 문서

[링크](https://github.com/leejaycoke/pilot-react/blob/master/API.md)

## 자랑하기

- [leejaycoke](https://github.com/leejaycoke/pilot-react/tree/main/results/hodolman) 예를들어 초보 개발자인데 한 번 해봤습니다. 피드백주세요
- [hojongs](https://github.com/leejaycoke/pilot-react/tree/main/results/hojongs) 프론트엔드 경험 전무하지만 Vue로 스타트 끊어봅니다!
- [jho2301](https://github.com/leejaycoke/pilot-react/tree/main/results/jho2301) 우아한테크코스 화이팅

