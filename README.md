# MC-Font-Data

## 파일 구조
### Font 파일 구조
형식 | 이름 | 추가 설명
---|---|---
String | Language Name | 언어명
Int | Glyph Length | GlyphData의 길이
GlyphData | | 글자 데이터

### GlyphData
형식 | 이름 | 추가 설명
---|---|---
Int | Character | 문자
Float | Width | 문자의 너비
Float | Bold Width | 스타일이 Bold일 경우의 Width
