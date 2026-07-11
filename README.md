# AdZero Filters

애드제로(AdZero) iOS 앱이 사용하는 Safari Content Blocker 규칙 배포 저장소입니다.
앱은 이 저장소의 JSON 파일을 주기적으로 내려받아 필터를 갱신합니다. 방문 기록 등 어떤 사용자 데이터도 이 저장소로 전송되지 않습니다.

| 파일 | 내용 | 원본 |
|---|---|---|
| `blocker_korean.json` | 한국 사이트 특화 | [List-KR](https://github.com/List-KR/List-KR) |
| `blocker_ads.json` | 일반 광고 | [EasyList](https://easylist.to/) |
| `blocker_privacy.json` | 추적기·분석 스크립트 | [EasyPrivacy](https://easylist.to/) |
| `blocker_annoyance.json` | 쿠키 배너 등 방해 요소 | [Fanboy's Annoyance List](https://easylist.to/) |
| `blocker_custom.json` | 앱 내 사용자 규칙 기본값 | AdZero |

## 라이선스 및 저작자 표시

이 저장소의 규칙 파일들은 아래 오픈소스 필터 목록을 [AdGuard SafariConverterLib](https://github.com/AdguardTeam/SafariConverterLib)로 Safari Content Blocker 형식으로 변환한 2차적 저작물이며, 원본과 동일한 라이선스 조건을 따릅니다.

- **List-KR** — [GPL-3.0-only](https://github.com/List-KR/List-KR/blob/master/LICENSE), © List-KR contributors
- **EasyList / EasyPrivacy / Fanboy's Annoyance List** — [GPL-3.0-or-later 및 CC BY-SA 3.0 듀얼 라이선스](https://easylist.to/pages/licence.html), © The EasyList authors

변환 파이프라인(원본 목록 → 본 JSON 생성 과정)의 소스는 요청 시 GPL-3.0 조건에 따라 제공됩니다.
