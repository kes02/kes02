<div align="center">

🇺🇸 <b>English</b> · 🇰🇷 <a href="./README.ko.md">한국어</a>

</div>

## About me

I'm Heejin. I started on the backend with Java and Spring Boot, and these days I write Swift for macOS. I built Pomopet, a menu-bar Pomodoro timer, and ship it through Homebrew. On CodexBar I have filed 2 bug reports and merged 4 PRs, two of them fixes. Most of my time goes into narrowing down what is actually broken, not into writing the patch.

Résumé & portfolio: **[kes02.github.io](https://kes02.github.io/)**

## Open source contributions

#### [steipete/CodexBar](https://github.com/steipete/CodexBar) · `Swift`

A macOS menu-bar app that keeps AI coding-tool usage limits visible at a glance.

- **Reported & root-caused** a Claude OAuth account-switching bug ([#1785](https://github.com/steipete/CodexBar/issues/1785)).
- **Caught & reproduced a regression** in v0.38.0 and filed a scoped follow-up ([#1886](https://github.com/steipete/CodexBar/issues/1886)) → fixed in v0.40.0, which I verified and closed.
- **Merged a feature PR** that surfaces the Claude Max usage multiplier (5x/20x) in the plan label ([#1932](https://github.com/steipete/CodexBar/pull/1932)).
- **Merged a fix PR** that classifies an unreadable Claude OAuth credential as a terminal refresh state, so background refresh stops retrying in vain and shows re-auth guidance instead ([#2650](https://github.com/steipete/CodexBar/pull/2650)).
- **Merged a fix PR** pinning the Perplexity promo-credit expiry formatter to `en_US_POSIX`, so the date renders the same regardless of the user's locale. It also adds regression tests that stay stable across locales and time zones ([#2651](https://github.com/steipete/CodexBar/pull/2651)).
- **Merged a docs PR** consolidating a duplicate provider section ([#1801](https://github.com/steipete/CodexBar/pull/1801)).

## Featured projects

**[Pomopet](https://github.com/kes02/Pomopet)**: a macOS menu-bar Pomodoro timer where you pick a pet to study with and keep going together, tracking daily streaks and an activity-grass log.
`Swift` · `SwiftUI` · `SwiftData` · install via [`homebrew-pomopet`](https://github.com/kes02/homebrew-pomopet)

**[time-mirror](https://github.com/kes02/time-mirror)**: a timeline planner (PWA) that sets your planned and actual timelines side by side, so you can look back on whether the day went the way you meant it to.
`TypeScript` · `PWA`

**[js-boj-fetch](https://github.com/kes02/js-boj-fetch)**: a Baekjoon problem recommender that suggests still-unsolved problems by your chosen conditions.
`JavaScript`

## Stats

| GitHub Stats | Top Languages |
| :---: | :---: |
| ![Heejin's GitHub stats](./profile/stats.svg) | ![Top Langs](./profile/top-langs.svg) |

<div align="center">
<img src="https://streak-stats.demolab.com?user=kes02&theme=tokyonight&hide_border=true" alt="GitHub streak" />
</div>

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-222222?style=for-the-badge&logo=github&logoColor=white)](https://kes02.github.io/)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=for-the-badge&logo=Velog&logoColor=white)](https://velog.io/@kes02/posts)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=Gmail&logoColor=white)](mailto:hjjung1220@gmail.com)
