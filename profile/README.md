# blog-plugins

> 한국어 블로그·SNS 콘텐츠 제작을 자동화하는 **Claude Code 플러그인 마켓플레이스**

## 무엇을 하는 조직인가요?

`blog-plugins`는 블로그·인스타그램 등 한국어 콘텐츠를 만들 때 반복되는 작업을
**Claude Code 안에서 바로** 처리할 수 있게 해주는 플러그인(스킬)을 모아두는 곳입니다.

썸네일 제작, 카드뉴스 구성, 본문 보조 같은 일을 매번 손으로 하지 않고,
사진과 짧은 텍스트만 주면 일관된 하우스 디자인으로 결과물을 뽑아내는 것이 목표입니다.

## 목표

- ✏️ **반복 작업 자동화** — 썸네일·카드뉴스 등 디자인 작업을 명령 한 번으로
- 🎨 **일관된 브랜드 톤 유지** — 고정된 하우스 디자인으로 시리즈 전체의 통일감 확보
- 🇰🇷 **한국어 콘텐츠에 최적화** — 한글 타이포그래피와 국내 SNS 포맷 기준
- 🧩 **재사용 가능한 스킬화** — 한 번 만든 워크플로를 누구나 설치해서 그대로 사용

## 포함된 플러그인

| 플러그인 | 설명 |
|----------|------|
| [blog-thumbnail-generator](https://github.com/blog-plugins/blog-thumbnail-plugin) | 사진 1장 + 한국어 텍스트(제목·카테고리·주제)로 1:1 정사각 블로그/SNS 썸네일을 2000×2000 PNG로 렌더 |

## 설치

Claude Code 안에서:

```
/plugin marketplace add blog-plugins/blog-thumbnail-plugin
/plugin install blog-thumbnail-generator@blog-plugins
```

설치 후 `/plugin list`로 확인할 수 있습니다.

---

문의나 제안은 각 저장소의 Issue로 남겨주세요.
