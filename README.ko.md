<div align="center">

🇰🇷 <b>한국어</b> · 🇺🇸 <a href="./README.md">English</a>

</div>

## 소개

정희진입니다. 소프트웨어 마에스트로 17기로 활동하고 있습니다. 백엔드는 Java와 Spring Boot로 시작했고, 지금은 Swift로 macOS 앱을 내놓고 있습니다. 메뉴바 포모도로 타이머 Pomopet을 만들어 Homebrew로 배포하고 있습니다. CodexBar에는 버그 제보 2건과 머지된 PR 4건을 남겼고, 제가 제보한 회귀는 v0.40.0에서 고쳐졌습니다.

이력서 & 포트폴리오: **[kes02.github.io](https://kes02.github.io/)**

## 오픈소스 기여

#### [steipete/CodexBar](https://github.com/steipete/CodexBar) · `Swift`

AI 코딩 도구의 사용량 한도를 메뉴바에서 한눈에 보여주는 macOS 앱입니다.

- Claude OAuth 계정 전환 버그를 **제보하고 근본 원인까지 분석**했습니다 ([#1785](https://github.com/steipete/CodexBar/issues/1785)).
- v0.38.0에서 **회귀를 발견해 재현**하고 별도 이슈로 올렸습니다 ([#1886](https://github.com/steipete/CodexBar/issues/1886)) → v0.40.0에서 고쳐졌고, 직접 확인 후 이슈를 닫았습니다.
- Claude **Max 사용량 배수(5x/20x)** 플랜 라벨에 표시하는 **기능 PR을 머지**했습니다 ([#1932](https://github.com/steipete/CodexBar/pull/1932)).
- 읽을 수 없는 Claude OAuth 자격 증명을 **재시도 불가 상태로 분류**해, 백그라운드 갱신이 헛된 재시도 대신 재인증 안내를 띄우도록 **수정 PR을 머지**했습니다 ([#2650](https://github.com/steipete/CodexBar/pull/2650)).
- Perplexity 프로모션 크레딧 만료일 포맷터를 `en_US_POSIX`로 **고정**해 사용자 로케일과 무관하게 날짜가 같게 보이도록 **수정 PR을 머지**했습니다. 로케일과 타임존에 흔들리지 않는 회귀 테스트도 함께 넣었습니다 ([#2651](https://github.com/steipete/CodexBar/pull/2651)).
- 중복된 프로바이더 문서를 정리한 **문서 PR을 머지**했습니다 ([#1801](https://github.com/steipete/CodexBar/pull/1801)).

## 프로젝트

**[Pomopet](https://github.com/kes02/Pomopet)**: 공부를 함께하고 싶은 펫을 입력하고, 펫과 함께 공부를 이어가는 macOS 메뉴바 포모도로 타이머. 일일 스트릭과 활동 잔디 기록을 지원합니다.
`Swift` · `SwiftUI` · `SwiftData` · [`homebrew-pomopet`](https://github.com/kes02/homebrew-pomopet)로 설치

**[jin-skills](https://github.com/kes02/jin-skills)**: 직접 만들어 쓰는 Claude Code 스킬 7개를 플러그인으로 묶은 모음. 커밋·PR 컨벤션, 티켓 작성, 웹 리서치 등을 다룹니다.
`Claude Code` · `Shell`

**[time-mirror](https://github.com/kes02/time-mirror)**: 예상 계획과 실제 계획을 나란히 놓고 보는 타임라인 플래너(PWA). 세운 계획대로 하루를 보냈는지 되돌아봅니다.
`TypeScript` · `PWA`

**[js-boj-fetch](https://github.com/kes02/js-boj-fetch)**: 사용자가 요청한 조건에 맞는 풀지 않은 백준 문제를 추천해 주는 서비스.
`JavaScript`

## 통계

| GitHub Stats | Top Languages |
| :---: | :---: |
| ![Heejin's GitHub stats](./profile/stats.svg) | ![Top Langs](./profile/top-langs.svg) |

<div align="center">
<img src="https://streak-stats.demolab.com?user=kes02&theme=tokyonight&hide_border=true" alt="GitHub 스트릭" />
</div>

## 연락처

[![Portfolio](https://img.shields.io/badge/Portfolio-222222?style=for-the-badge&logo=github&logoColor=white)](https://kes02.github.io/)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white)](https://velog.io/@kes02/posts)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:hjjung1220@gmail.com)
