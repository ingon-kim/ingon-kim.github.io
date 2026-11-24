# CLAUDE.md

김인곤 개인 홈페이지(https://ingon-kim.github.io). Jon Barron 템플릿 기반의 순수 HTML 사이트예요. 빌드 과정이 없어요.

## 구조

- `index.html`: 페이지 전체. 소개, 링크, 논문 목록을 직접 고쳐요.
- `stylesheet.css`: Jon Barron 최신 템플릿 원본 그대로예요. 이 사이트만의 스타일은 `index.html`의 `<style>` 블록에 있어요.
- `images/`: 프로필 사진과 논문 썸네일(620×306, 2패널).
- `data/`: CV PDF.
- `.nojekyll`: GitHub Pages가 Jekyll 빌드를 하지 않게 해요.

## 콘텐츠 규칙

- 영어만 써요.
- 논문 정보는 원문(게재 논문)과 대조한 값이에요. 추측으로 바꾸지 않아요.

## 미리보기

```bash
python3 -m http.server 4000
```

## 배포 · 커밋

- GitHub Pages가 `main` 브랜치를 그대로 서빙해요. push가 곧 공개예요.
- 커밋은 Conventional Commits 형식으로 써요.
