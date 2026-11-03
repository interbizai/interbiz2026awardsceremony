# 2026 INTERBIZ AWARDS · 인터비즈시스템 연말시상식 모바일 초대장

정적 웹페이지(빌드 과정 없음)입니다. GitHub Pages로 배포됩니다.

- 주소: https://interbizai.github.io/interbiz2026awardsceremony/
- 구성: `index.html` 한 장 + `assets/` (서체, 로고, 마스코트, 약도, 미리보기 이미지)

## 귀빈용 초대장 (받는 분 이름 표시)
- 초대장: https://interbizai.github.io/interbiz2026awardsceremony/vip/ (이름 없이 열면 '소중한 분'으로 표시)
- 링크 만들기: https://interbizai.github.io/interbiz2026awardsceremony/vip/make.html
  - 이름·직책을 넣으면 `vip/?to=...` 개인 링크가 만들어지고, 초대장에 "OOO 팀장님을 정중히 초대합니다"로 표시됩니다.
  - 여러 명은 한 줄에 '이름 직책'으로 적어 한 번에 만들 수 있고, 엑셀용으로 전체 복사할 수 있습니다.
- 임직원용과 달리 Got Talent 모집 안내와 공유 버튼이 없습니다.

## 수정 후 반영
`main` 브랜치에 커밋·푸시하면 GitHub Pages가 1~2분 안에 자동으로 다시 배포합니다.
(설정 위치: 저장소 › Settings › Pages › Source: Deploy from a branch, `main` / `(root)`)

## 카카오톡 공유 버튼
- 기본 동작: 휴대폰 공유 창을 열어 카카오톡을 선택할 수 있습니다. 공유 창이 없는 기기에서는 링크를 복사합니다.
- 카카오 공유 카드(큰 이미지 + '초대장 보기' 버튼)로 보내려면:
  1. [Kakao Developers](https://developers.kakao.com)에서 앱을 만들고 **JavaScript 키**를 확인합니다.
  2. 앱 설정 › 플랫폼 › Web에 `https://interbizai.github.io`를 등록합니다.
  3. `index.html`의 `var KAKAO_JS_KEY = '';` 에 키를 넣고 푸시합니다.

## 카카오톡 미리보기(썸네일)
`assets/og-image.jpg` (1200×600)가 링크 미리보기로 쓰입니다. 이미지를 바꾼 뒤 예전 미리보기가 보이면
Kakao Developers의 '공유 디버거'에서 주소를 넣고 캐시를 초기화하세요.

## 검색 노출
사내 행사용이라 `noindex` 메타 태그로 검색엔진 노출을 막아 두었습니다.
