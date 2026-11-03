# 2026 INTERBIZ AWARDS · 인터비즈시스템 연말시상식 모바일 초대장

정적 웹페이지(빌드 과정 없음)입니다. Vercel에 그대로 배포됩니다.

- 주소: https://interbiz2026awardsceremony.vercel.app
- 구성: `index.html` 한 장 + `assets/` (서체, 로고, 마스코트, 약도, 미리보기 이미지)

## 수정 후 반영
`main` 브랜치에 커밋·푸시하면 Vercel이 자동으로 다시 배포합니다.

## 카카오톡 공유 버튼
- 기본 동작: 휴대폰 공유 창을 열어 카카오톡을 선택할 수 있습니다. 공유 창이 없는 기기에서는 링크를 복사합니다.
- 카카오 공유 카드(큰 이미지 + '초대장 보기' 버튼)로 보내려면:
  1. [Kakao Developers](https://developers.kakao.com)에서 앱을 만들고 **JavaScript 키**를 확인합니다.
  2. 앱 설정 › 플랫폼 › Web에 `https://interbiz2026awardsceremony.vercel.app`을 등록합니다.
  3. `index.html`의 `var KAKAO_JS_KEY = '';` 에 키를 넣고 푸시합니다.

## 카카오톡 미리보기(썸네일)
`assets/og-image.jpg` (1200×600)가 링크 미리보기로 쓰입니다. 이미지를 바꾼 뒤 예전 미리보기가 보이면
Kakao Developers의 '공유 디버거'에서 주소를 넣고 캐시를 초기화하세요.

## 검색 노출
사내 행사용이라 `noindex` 메타 태그로 검색엔진 노출을 막아 두었습니다.
