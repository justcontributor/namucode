# 나무코드 Namucode

[나무위키](https://namu.wiki)의 Monaco 편집기의 VSCode 확장 프로그램 버전입니다. 많은 기능이 추가될 예정입니다.

- [설치](#설치)
- [기능](#기능)
    - [텍스트 강조 기능](#텍스트-강조-기능-syntax-highlighting)
    - [자동완성 기능](#자동완성-기능-snippet)
    - [커맨드 기능](#커맨드-기능-command-palette)
- [업데이트 로그](#업데이트-로그)
- [참고](#참고)

## 설치
나무코드는 VSCode 확장 프로그램으로, VSCode Marketplace에서 다운받을 수 있습니다.

링크: https://marketplace.visualstudio.com/items?itemName=null

## 기능
### 텍스트 강조 기능 (Syntax Highlighting)
나무코드는 텍스트 강조를 지원합니다.\
기존 에디터보다 더 세세한 강조가 지원됩니다.

------
나무위키의 '나무위키' 문서 비교샷

### 자동완성 기능 (Snippet)
나무코드는 편의를 위한 자동완성을 지원합니다.\
쉽게 `ctrl+space`로 자동완성 목록을 볼 수 있습니다.\
현재 자동완성 목록은 다음과 같습니다.

 - **child** - 하위 문서 틀을 삽입합니다.
 - **detail** - 상세 내용 틀을 삽입합니다.
 - **detailanchor** - 상세 내용 틀을 앵커와 함께 삽입합니다.
 - **detailparagraph** - 상세 내용 틀을 문단 번호와 함께 삽입합니다.
 - **file** - 파일을 삽입합니다.
 - **folding** - [ 펼치기 · 접기 ] 문법을 삽입합니다.
 - **include** - 틀을 삽입합니다.
 - **link** - 링크할 문서명과 문서에서 보여지는 명칭이 있는 링크를 생성합니다.
 - **navertv** - 네이버TV 영상을 삽입합니다.
 - **parent** - 상위 문서 틀을 삽입합니다.
 - **relate** - 관련 문서 틀을 삽입합니다.
 - **youtube** - 유튜브 영상을 삽입합니다.

### 커맨드 기능 (Command Palette)
여기서 커맨드는 `F1`시 나오는 커맨드 팔레트의 커맨드들을 지칭합니다.\
`F1`을 눌러 아래의 목록을 검색하거나 단축키를 이용하면 적용됩니다.\
커맨드 목록은 다음과 같습니다.

 - **문단 한단계 높이기** `ctrl+↑(up)` - 선택한 범위 내에서 문단을 한단계 높인다.\
 == 개요 == → === 개요 ===
 - **문단 한단계 낮추기** `ctrl+↓(down)` - 선택한 범위 내에서 문단을 한단계 낮춘다.\
 === 개요 === → == 개요 ==
 - **문자 링크화하기** - 선택한 문자를 링크로 만든다.
 선택 -> [[선택]]

## 업데이트 로그
### 1.0
**2022.07.03**
- 텍스트 강조 추가
- 자동완성 추가 (12개)
- 커맨드 추가 (3개)
- 기타 등등
## 참고
 - 나무위키 문법 도움말 - https://namu.wiki/w/나무위키:문법%20도움말
 - Textmate Grammar - https://macromates.com/manual/en/language_grammars
 - VSCode Extension Sample - https://github.com/microsoft/vscode-extension-samples