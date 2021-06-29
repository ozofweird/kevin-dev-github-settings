# kevin-dev-github-settings

![](https://img.shields.io/badge/version-0.0.1-brightgreen)

## Index
- [kevin-dev-github-settings](#kevin-dev-github-settings)
  - [Index](#index)
  - [About](#about)
  - [Overview](#overview)
  - [Getting Started](#getting-started)
    - [Create Token](#create-token)
    - [labels.json 정의](#labelsjson-정의)
    - [labels.json 적용](#labelsjson-적용)
    - [Issue/PR Template](#issuepr-template)
  - [Contributing](#contributing)
  - [Authors](#authors)
  - [References](#references)
  - [Commit messages (Gitmoji)](#commit-messages-gitmoji)

## About
Issue, PR 템플릿 생성을 위한 프로젝트입니다.

## Overview
커스텀 Issue, PR 템플릿을 사용할 수 있습니다.

## Getting Started

### Create Token

repo scope를 활성화한 LABEL_TOKEN 생성 ([https://github.com/settings/tokens](https://github.com/settings/tokens))

### labels.json 정의
```
[
  {
    "name": "Priority: Critical",
    "color": "8c001a",
    "description": "우선순위 긴급"
  }
]
```

### labels.json 적용
```
npx github-label-sync --access-token [액세스 토큰] --labels labels.json [계정명]/[저장소 이름]
```

### Issue/PR Template
- .github 생성
- .github/pull_request_template.md 생성
- .github/ISSUE_TEMPLATE 생성
- .github/ISSUE_TEMPLATE/*_template.md 생성

## Contributing
ozofweird

## Authors
- [ozofweird](https://github.com/ozofweird) - **Kevin Ahn** - <이메일@gmail.com>

## References
- https://github.com/modolee/github-initial-settings
  
---

## Commit messages (Gitmoji)

|Gitmoji|Code|Description|
|:-----:|:---:|:--------:|
|🎨|art|파일/코드 구조 개선|
|🩹|adhesive_bandage|간단한 수정|
|⚡️|zap|성능 향상|
|🔥️|fire|코드나 파일 삭제|
|🐛️|bug|버그 해결|
|🚑️|ambulance|긴급 수정|
|✨️|sparkles|새로운 기능|
|📝️|memo|문서 추가/수정|
|💄️|lipstick|화면 UI 추가/수정|
|🎉️|tada|프로젝트 시작|
|✅️|white_check_mark|테스트 추가/수정|
|🔒️|lock|보안 이슈 수정|
|🔖️|bookmark|릴리즈/버전 태그|
|🚧|construction|작업 진행 중|
|💚|green_heart|CI 빌드 수정|
|⬇️|arrow_down|의존성 버전 다운|
|⬆️|arrow_up|의존성 버전 업|
|📌|pushpin|특정 버전 의존성 고정|
|👷|construction_worker|CI 빌드 시스템 추가/수정|
|📈|chart_with_upwards_trend|분석, 추적 코드 추가/수정|
|♻️|recycle|코드 리팩토링|
|➕|heavy_plus_sign|의존성 추가|
|➖|heavy_minus_sign|의존성 제거|
|🔧|wrench|설정 파일 추가/수정|
|🔨|hammer|개발 스크립트 추가/수정|
|🌐|globe_with_meridians|다국어 지원|
|💩|poop|안좋은 코드 추가|
|⏪|rewind|변경 내용 되돌리기|
|🔀|twisted_rightwards_arrows|브랜치 합병|
|👽|alien|외부 API 변화로 인한 수정|
|🚚|truck|리소스 이동/이름 변경|
|💥|boom|놀라운 기능 소개|
|🍱|bento|에셋 추가/수정|
|💡|bulb|주석 추가/수정|
|💬|speech_balloon|스트링 파일 추가/수정|
|🗃|card_file_box|데이버베이스 관련 수정|
|🔊|loud_sound|로그 추가/수정|
|🔇|mute|로그 삭제|
|📱|iphone|반응형 디자인|
|🙈|see_no_evil|gitignore 추가|