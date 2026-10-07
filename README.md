# 손필기 요약노트 만들기 (웹 버전)

교과서 PDF·캡처를 넣으면 AI(OpenRouter)가 요약 원고를 쓰고, 손글씨 글꼴로 굿노트용 PDF와 A4 인쇄용 PDF를 만듭니다.

**바로 사용하기: https://taehwan-shin.github.io/handwriting-note-web/**

- 서버가 없는 정적 페이지입니다. API 키, 교과서 파일, 결과 PDF는 모두 방문자의 브라우저 안에서만 처리됩니다.
- API 키는 각자 [openrouter.ai/keys](https://openrouter.ai/keys)에서 발급해 넣습니다. 키는 그 브라우저에만 저장됩니다.
- 교과서 내용은 방문자의 브라우저에서 OpenRouter로 직접 보냅니다. 기본 설정은 입력을 저장·학습하지 않는 제공사로만 보냅니다(`provider.data_collection: "deny"`).
- 외부 스크립트를 불러오지 않습니다. pdf.js까지 페이지에 들어 있고, 보안 정책(CSP)으로 OpenRouter 외의 통신을 막습니다.

## 출처
- 노트 작성 규칙, 렌더러, 2022 개정 교육과정 자료: [xodn0109-glitch/goodnotes-handwriting-note](https://github.com/xodn0109-glitch/goodnotes-handwriting-note)
- 글꼴: 학교안심 받아쓰기 (KERIS, SIL Open Font License). 웹에서 쓰기 위해 원본 TTF를 WOFF2 형식으로 압축만 했습니다. 라이선스 전문은 [OFL.txt](OFL.txt), 고지는 [FONT-NOTICES.md](FONT-NOTICES.md)에 있습니다.
- PDF 읽기: [pdf.js](https://mozilla.github.io/pdf.js/) 3.11.174, © Mozilla, Apache License 2.0 ([licenses/pdfjs-LICENSE.txt](licenses/pdfjs-LICENSE.txt))
- 2022 개정 교육과정 성취기준: 교육부 고시 (저작권법 제7조에 따른 비보호 저작물)
