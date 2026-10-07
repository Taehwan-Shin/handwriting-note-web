# 손필기 요약노트 만들기 (웹 버전)

교과서 PDF·캡처를 넣으면 AI(OpenRouter)가 요약 원고를 쓰고, 손글씨 글꼴로 굿노트용 PDF와 A4 인쇄용 PDF를 만듭니다.

**바로 사용하기: https://taehwan-shin.github.io/handwriting-note-web/**

- 서버가 없는 정적 페이지입니다. API 키, 교과서 파일, 결과 PDF는 모두 방문자의 브라우저 안에서만 처리됩니다.
- API 키는 각자 [openrouter.ai/keys](https://openrouter.ai/keys)에서 발급해 넣습니다. 키는 그 브라우저에만 저장됩니다.
- 교과서 내용은 방문자의 브라우저에서 OpenRouter로 직접 보냅니다.

## 출처
- 노트 작성 규칙, 렌더러, 2022 개정 교육과정 자료: [xodn0109-glitch/goodnotes-handwriting-note](https://github.com/xodn0109-glitch/goodnotes-handwriting-note)
- 글꼴: 학교안심 받아쓰기 (KERIS, SIL Open Font License). 웹에서 쓰기 위해 원본 TTF를 WOFF2 형식으로 압축만 했습니다. 자세한 내용은 [FONT-NOTICES.md](FONT-NOTICES.md)를 참고하세요.
