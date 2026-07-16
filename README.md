# AdZero Filters

애드제로(AdZero) iOS/iPadOS 앱이 사용하는 **Safari Content Blocker 필터 데이터** 공개 배포 저장소입니다. 앱은 이 저장소의 JSON을 내려받아 기기 안에서 검증한 뒤 원자적으로 교체합니다. 방문 URL, 검색어, 차단 기록 등 사용자 데이터는 이 저장소로 전송되지 않습니다.

| 파일 | 내용 | 원출처 |
|---|---|---|
| `blocker_korean.json` | 한국 사이트 필터 + AdZero 히토미 호환 규칙 16개 | [YousList](https://github.com/yous/YousList) |
| `blocker_ads.json` | 일반 광고 필터 | [EasyList](https://easylist.to/) |
| `blocker_privacy.json` | 추적기·분석 스크립트 + AdZero 호환 규칙 | [EasyPrivacy](https://easylist.to/) |
| `blocker_annoyance.json` | 쿠키 배너·구독 유도 등 방해 요소 | [Fanboy's Annoyance List](https://easylist.to/) |
| `blocker_custom.json` | 사용자 규칙 목록의 유효한 초기값 | AdZero |
| `blocker_privacy_extra.json` | 원격 필터와 병합하는 AdZero 호환 보충 규칙 | AdZero |
| `build_report.json` | 생성 시각·출처 URL·라이선스·규칙 수·제한 적용 결과 | AdZero |
| `SHA256SUMS` | 배포 파일 무결성 체크섬 | AdZero |

## 변경 사항

- 공개 원본 필터 데이터를 Safari Content Blocker JSON 형식으로 제공한다.
- 파일별 카테고리 분리, Safari 구조 검증, 중복 제거, 145,000개 안전 한도를 적용한다.
- `blocker_korean.json`에는 Hitomi 광고 팝업을 차단하되 검색·작품 열기·다음 페이지 이동을 해치지 않도록 검증한 AdZero 규칙 16개를 덧붙인다.
- `blocker_privacy.json`에는 광고/추적 성능 회귀 테스트용 AdZero 규칙을 덧붙인다.

정확한 빌드 정보는 `build_report.json`, 라이선스와 저작자 표시는 `FILTER_LICENSES.md`를 확인하세요.

> 이 저장소는 필터 **데이터**만 배포합니다. 여기에 표시된 필터 데이터 라이선스는 AdZero 앱·확장 프로그램의 실행 코드에 적용되지 않습니다. 앱 실행 코드는 별도의 AdZero 소유 코드입니다.
