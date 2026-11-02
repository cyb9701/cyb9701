# 최유빈 (Yubin Choi)

**앱, 서버, 웹을 함께 만드는 프로덕트 개발자**

"어떻게 짤까"보다 "어떤 문제를 풀까"를 먼저 생각합니다.  
2020년부터 Flutter로 앱을 만들었고, 지금은 제품 전체를 개발합니다.  
AI Agent를 페어 파트너로 두고, 변화의 시점에 맞는 프로덕트를 만듭니다.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=LinkedIn&logoColor=white)](https://www.linkedin.com/in/yubin-choi/)
[![Velog](https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=white)](https://velog.io/@cyb9701)

## 지금 만드는 것

지티미디어에서 서비스 두 개를 개발하고 있습니다.

### [황금거위](https://www.goldgoose.kr)

광고를 보고 캐시를 모아 현금으로 전환하는 리워드 앱입니다.  
2026년 1월에 출시했고, 앱과 서버와 웹 개발을 맡고 있습니다.

[App Store](https://apps.apple.com/kr/app/id6756346292) · [Google Play](https://play.google.com/store/apps/details?id=kr.gtmedia.goldengoose)

| 영역 | 구성 | 기술 |
|------|------|------|
| 앱 | iOS, Android | Flutter, Riverpod |
| 서버 | 데이터베이스, Edge Functions | Supabase, PostgreSQL, Deno |
| 웹 | 홈페이지, 웹뷰, 관리자 페이지 | React, TypeScript, Vite |

### [피카 유니버스](https://www.pikauniverse.com)

포켓몬 카드 오리파와 TCG 리팩을 온라인으로 제공하는 서비스입니다.  
획득한 카드는 실물로 받거나 포인트로 전환합니다. 2026년 9월에 앱을 출시했습니다.

[웹사이트](https://www.pikauniverse.com) · [App Store](https://apps.apple.com/kr/app/id6807088276) · [Google Play](https://play.google.com/store/apps/details?id=kr.gtmedia.pikauniverse)

| 영역 | 구성 | 기술 |
|------|------|------|
| 앱 | iOS, Android | Expo, React Native |
| 서버 | 데이터베이스, 백엔드 함수 | Convex |
| 웹 | 사용자 웹, 관리자 페이지 | Next.js, React, TypeScript |

## 직접 만든 도구

매일 겪는 불편을 도구로 만들어 공개합니다.

### [claude-for-mac](https://github.com/cyb9701/claude-for-mac)

Claude 사용자를 위한 macOS 메뉴 바 앱입니다. Swift로 만들었습니다.

- **Claude UsageBar**: Claude Pro/Max 사용량을 메뉴 바에서 실시간으로 보여 줍니다. Claude Code CLI의 인증 정보를 재사용하므로 별도 로그인이 필요 없습니다.
- **Claude PromptPad**: 터미널의 줄바꿈과 한글 입력 문제를 피해 프롬프트를 작성합니다. 글로벌 단축키로 열고, 복사해서 터미널에 한 번에 붙여 넣습니다.

### [claude-plugins](https://github.com/cyb9701/claude-plugins)

Claude Code용 개인 플러그인 마켓플레이스입니다. 마켓플레이스 이름은 `cyb9701-claude-plugins`입니다.

```shell
/plugin marketplace add cyb9701/claude-plugins
/plugin install easy-claude-code@cyb9701-claude-plugins
```

`easy-claude-code` 플러그인은 앱 운영과 프롬프트 작성을 돕는 스킬을 제공합니다.

- **crashlytics-to-issue**: 해결되지 않은 Firebase Crashlytics 크래시와 ANR을 GitHub Issue로 동기화합니다.
- **crashlytics-issue-to-fix**: Issue를 격리된 git worktree에서 분석하고, Issue마다 PR을 하나씩 엽니다.
- **prompt-refine**: 원래 의도를 유지하면서 프롬프트를 Claude에 맞게 다시 씁니다.
- **skill-tree**: 활성화된 스킬을 표로 보여 줍니다.

## 경력

| 기간 | 회사 | 역할 | 주요 작업 |
|------|------|------|------|
| 2026.01 ~ 현재 | 지티미디어 | 프로덕트 개발자 | 황금거위, 피카 유니버스 |
| 2020.08 ~ 2025.05 | 주식회사 빌리오 | Flutter 개발자 | 빌리오 앱 |

## 기술

- **Mobile**: Flutter, Dart, Riverpod, React Native, Expo
- **Web**: React, Next.js, TypeScript, Vite
- **Backend**: Supabase, PostgreSQL, Deno, Convex
- **macOS**: Swift, SwiftUI
- **Tooling**: Claude Code, Git, GitHub Actions

## 글

<!-- BLOG-POST-LIST:START -->
- [[Dart] 컴파일 방식 이해하기](https://velog.io/@cyb9701/Dart-%EC%BB%B4%ED%8C%8C%EC%9D%BC-%EB%B0%A9%EC%8B%9D-%EC%9D%B4%ED%95%B4%ED%95%98%EA%B8%B0)
- [[개발] Mac 개발 환경 세팅](https://velog.io/@cyb9701/%EA%B0%9C%EB%B0%9C-Mac-%ED%99%98%EA%B2%BD-%EC%84%B8%ED%8C%85)
- [[Flutter] MediaQuery의 padding, viewPadding 와 viewInsets](https://velog.io/@cyb9701/Flutter-MediaQuery%EC%9D%98-padding-viewPadding-%EC%99%80-viewInsets)
- [[Flutter] 스크롤 방향에 따라 앱바 애니메이션 효과 주기](https://velog.io/@cyb9701/Flutter-%EC%8A%A4%ED%81%AC%EB%A1%A4-%EB%B0%A9%ED%96%A5%EC%97%90-%EB%94%B0%EB%9D%BC-%EC%95%B1%EB%B0%94-%EC%95%A0%EB%8B%88%EB%A9%94%EC%9D%B4%EC%85%98-%ED%9A%A8%EA%B3%BC-%EC%A3%BC%EA%B8%B0)
- [[Dart] Cloudsmith 이용해서 비공개 패키지 버전 관리하기](https://velog.io/@cyb9701/Dart-Cloudsmith-%EC%9D%B4%EC%9A%A9%ED%95%B4%EC%84%9C-%EB%B9%84%EA%B3%B5%EA%B0%9C-%ED%8C%A8%ED%82%A4%EC%A7%80-%EB%B2%84%EC%A0%84-%EA%B4%80%EB%A6%AC%ED%95%98%EA%B8%B0)
<!-- BLOG-POST-LIST:END -->

[전체 글 보기](https://velog.io/@cyb9701/posts)
