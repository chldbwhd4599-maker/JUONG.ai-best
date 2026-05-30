# CMF Studio

> Color · Material · Finish — 제품 디자이너를 위한 재질 미리보기 & 스펙 카드 생성기

![status](https://img.shields.io/badge/version-0.1-e0a347) ![license](https://img.shields.io/badge/license-MIT-blue)

## 소개

이 프로젝트는 **제품·산업 디자이너가 CMF(Color, Material, Finish)를 빠르게 탐색하고 스펙 카드로 뽑아내는 웹 도구**입니다.

베이스 컬러를 고르고 재질·마감(무광 / 새틴 / 유광 / 메탈 / 우드 / 세라믹)을 선택하면, 그 조합이 실제로 어떻게 보이는지 실시간 렌더 구(sphere)로 확인하고, HEX·RGB·HSL·마감 노트·추천 대비색이 담긴 스펙 카드를 이미지로 내보낼 수 있습니다. 외부 라이브러리·빌드·서버 없이 HTML 파일 하나로 동작합니다.

## 주요 기능

- **실시간 재질 렌더** — 컬러와 재질을 바꾸면 6종 마감별 광택·반사가 즉시 구에 반영
- **CMF 스펙 카드** — HEX / RGB / HSL, 마감별 실무 노트, 추천 대비색을 자동 생성
- **PNG 내보내기** — 스펙 카드를 공유·발표용 이미지로 다운로드
- **CSS 변수 복사** — `--base`, `--base-rgb`, `--base-hsl` 토큰을 클릭 한 번에 복사
- **프리셋 팔레트** — 디자이너용 베이스 톤을 빠르게 적용
- **의존성 제로** — 단일 HTML, 오프라인 동작, GitHub Pages 바로 호스팅 가능

## 사용 방법

1. **다운로드** — 이 저장소를 클론하거나 `index.html`을 내려받습니다.
   ```bash
   git clone https://github.com/<your-id>/cmf-studio.git
   ```
2. **실행** — `index.html`을 브라우저에서 열면 끝입니다. (또는 GitHub Pages로 배포)
   ```
   open index.html      # macOS
   start index.html     # Windows
   ```

## 라이선스

MIT License
