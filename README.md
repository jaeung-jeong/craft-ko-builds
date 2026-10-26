# craft-ko-builds

storytold 오픈소스 편집기(VectorCraft 등)의 **한국어 UI 웹 빌드**.
업스트림 웹 릴리스에는 한글 폰트가 빠져 있어 UI가 □로 깨지므로,
`crates/text/web-fonts.txt`에 NanumGothic(OFL-1.1, craft-fonts 기본 등록 폰트)을
startup 폰트로 한 줄 추가해 다시 빌드한다. wasm/코드는 수정하지 않는다.

빌드 산출물은 이 저장소의 Releases에 zip으로 올라가며, AIMAKER 배포가 이를 설치한다.
라이선스: 업스트림과 동일 (MIT OR Apache-2.0), 폰트는 SIL OFL 1.1.
