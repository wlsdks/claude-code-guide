# 클로드 코드 기초 — 비개발자를 위한 인터랙티브 가이드 (비공식)

코드를 몰라도 **Claude Code의 핵심 개념**을 직접 눌러보며 이해할 수 있는 한 페이지 학습 가이드입니다. 모든 개념을 버튼·애니메이션으로 시각화했고, 완전 입문자(비개발자) 눈높이로 만들었습니다.

> ⚠️ 이 자료는 **비공식 학습 자료**이며 Anthropic과 무관합니다. (자세한 내용은 맨 아래 “고지” 참고)

## 🔗 바로 보기 (Live)

| 언어 | 주소 |
|---|---|
| 🇰🇷 한국어 | **[wlsdks.github.io/claude-code-guide](https://wlsdks.github.io/claude-code-guide/)** |
| 🇺🇸 English | **[/en/](https://wlsdks.github.io/claude-code-guide/en/)** |
| 🇨🇳 中文 (简体) | **[/zh/](https://wlsdks.github.io/claude-code-guide/zh/)** |
| 🇯🇵 日本語 | **[/ja/](https://wlsdks.github.io/claude-code-guide/ja/)** |

좌측 상단 드롭다운으로 언제든 언어를 전환할 수 있어요.

## 특징
- **파일 하나(`index.html`)** 로 된 정적 웹페이지 — 설치·서버 불필요, 더블클릭으로 열림
- **23개 주제**를 버튼·시뮬레이션으로 직접 체험하며 학습
- **라이트/다크 테마 토글**(☀/☾)과 **확장 모드**(대형 화면·발표용 확대) 내장
- **반응형** — 휴대폰·노트북·대형 화면(24·27인치) 모두 최적화, 다크모드 자동/수동
- 어려운 용어는 **점선 툴팁 + 검색되는 용어 사전**으로 풀이
- **다국어** — 한국어 · English · 中文 · 日本語 (좌상단에서 전환)
- **검색 친화(SEO)** — 메타·hreflang·Open Graph·구조화 데이터(JSON-LD)·사이트맵 구성, 공유 카드(OG 이미지) 포함

## 다루는 내용 (23개 주제)
- **시작하기** — 클로드 코드란?(챗 vs 코드 비교), 어디서 쓰나
- **기초 개념** — 컨텍스트 창, 압축(compact), 세션 & 폴더, 토큰, 모델 고르기(model)
- **기억과 규칙** — CLAUDE.md, 메모리, 스킬
- **능력 확장** — MCP(도구 연결), 플러그인, 서브에이전트, 이미지 붙여넣기, 자동화(훅)
- **안전하게** — 계획 모드, 권한 모드, 되돌리기, 데이터 & 프라이버시
- **실전** — 슬래시 명령, 요금제, 사용 한도, 용어 사전

## 로컬에서 보기
`index.html` 을 브라우저로 열면 끝입니다. (인터넷이 되면 글꼴을 Google Fonts에서 불러오고, 안 되면 기본 글꼴로 표시됩니다.)

## 정확성에 대하여
내용은 **2026년 6월 기준** Anthropic 공식 문서를 참고해 작성했습니다. 다만 요금·사용 한도·자동 압축 임계치 등 일부 수치는 공개되지 않았거나 자주 바뀌므로, 가이드 안에서 공식 페이지 확인을 안내합니다. 토큰 수·모델 비교 막대 등 `예시` 표시가 붙은 값은 개념 이해용 근삿값/상대 비교입니다.

## 만든이
**최진안 (stark)** — [GitHub](https://github.com/wlsdks) · [LinkedIn](https://www.linkedin.com/in/WriteDev) · [Blog](https://curiousjinan.tistory.com/) · [Email](mailto:dig04059@gmail.com)

문의·제안은 이메일이나 LinkedIn DM, 또는 이 저장소의 이슈로 남겨주세요.

---

## 고지 (Notice)

이 가이드는 **비공식 교육 자료**이며 **Anthropic Inc.와 무관**합니다.
This is an **unofficial** educational guide, **not affiliated with or endorsed by Anthropic Inc.**

- **상표 / Trademarks** — “Claude”, “Claude Code”, “Anthropic”은 Anthropic Inc.의 상표입니다. 이 가이드는 제품을 설명·참조하기 위해 해당 명칭을 사용할 뿐이며, 어떤 공식 관계·승인도 의미하지 않습니다. (Anthropic 로고는 사용하지 않습니다.)
- **출처 / Attribution** — 이 가이드는 [Claude Code 공식 문서](https://code.claude.com/docs)와 [Claude 플랫폼 문서](https://platform.claude.com)를 **참고**하여 자신의 표현으로 작성했습니다. 공식 문서의 문구를 그대로 복제하지 않았습니다.
- **정확한 정보 / Official source** — 가장 정확한 정보와 공식 지원은 [공식 문서](https://code.claude.com/docs)와 [Anthropic 지원](https://support.anthropic.com)을 참고하세요.

문의/수정 제안은 이슈로 남겨주세요.
