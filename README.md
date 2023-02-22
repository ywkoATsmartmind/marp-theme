# marp-theme
SmartMind marp-theme

## How to use?

1. VS Code Extension 설치: Extensions -> Marp for VS Code

2. 스마트마인드 테마 추가

Extension Settings -> `Markdown › Marp: Themes` -> `Add Item`

아래 remote url 주소를 추가해주세요.

```
https://raw.githubusercontent.com/smartmind-team/marp-theme/main/themes/theme.css
```

또는, vscode의 사용자 설정 파일에 아래와 같이 추가합니다.

```json
// settings.json
    "markdown.marp.themes": [
        "https://raw.githubusercontent.com/smartmind-team/marp-theme/main/themes/theme.css"
    ]
```

3. `.md` 파일 생성 후 메타데이터 설정하여 사용

```
---
marp: true
theme: smartmind
---

blah blah
```

check [example.md](./example.md)!


## Contribute

해당 레포지토리의 `themes/theme.css` 수정 후 PR 진행하세요. 템플릿 관련 필요한 이미지 파일 등은 `assets` 안에 넣어주세요.

## References

- [marp-vscode](https://github.com/marp-team/marp-vscode)
- [theme example - marpstyle](https://github.com/cunhapaulo/marpstyle)
- [theme example - academic](https://github.com/kaisugi/marp-theme-academic)