# Family Sync (우리집 일정) 정책 문서 저장소

가족 일정 공유 앱 **Family Sync (우리집 일정)** 의 공개 정책 페이지를 보관하는 저장소입니다.
앱 설정 화면과 Google Play 스토어 등록 정보(개인정보 처리방침 URL, 데이터 삭제 URL)에서 이 페이지들을 연결합니다.

- 대상 앱 패키지명: `com.familysync.family_sync`
- 문서 언어: 한국어

## 공개 URL (GitHub Pages)

| 문서 | URL |
|---|---|
| 홈 | https://enterbong.github.io/familiysync_app_policy/ |
| 개인정보 처리방침 | https://enterbong.github.io/familiysync_app_policy/privacy-policy.html |
| 서비스 이용약관 | https://enterbong.github.io/familiysync_app_policy/terms-of-service.html |
| 계정 및 데이터 삭제 안내 | https://enterbong.github.io/familiysync_app_policy/account-deletion.html |

> **GitHub Pages가 아직 꺼져 있다면**: 저장소 **Settings > Pages**에서
> Source를 **Deploy from a branch**, Branch를 **`main`**, 폴더를 **`/ (root)`** 로 선택하고 Save 하세요.
> 저장 후 1~2분 내에 위 URL이 활성화됩니다.

## 파일 구성

```text
index.html                  # 정책 문서 홈 (카드형 링크)
privacy-policy.html/.md     # 개인정보 처리방침
terms-of-service.html/.md   # 서비스 이용약관
account-deletion.html/.md   # 계정 및 데이터 삭제 안내 (Google Play Data deletion 링크용)
assets/style.css            # 공통 스타일 (외부 CDN 의존 없음)
```

HTML은 스토어/앱 연결용 공개 페이지이고, Markdown은 동일 내용의 원본(리뷰·수정용)입니다.
**내용을 수정할 때는 md와 html을 함께 갱신하세요.**

## 문서 작성 기준

- 2026-07-11 기준 앱 코드(`/workspace/family_sync`)와 README/docs를 분석해 **실제 기능·실제 수집 항목 기준**으로 작성했습니다.
- 앱이 수집하지 않는 정보(위치정보, 광고 식별자, 연락처 등)는 수집하지 않는다고 명시했습니다.
- 위치 공유 기능은 보류(dormant, UI 비노출) 상태이며, 문서에는 "현재 위치정보를 수집하지 않음 + 향후 도입 시 별도 동의/정책 개정" 원칙으로 반영했습니다.

## 남은 TODO

- [ ] 운영자명 / 연락처 이메일 / 사업자 정보 기입 (문서 내 `TODO` 표시 위치)
- [ ] 시행일 확정 (스토어 출시일)
- [ ] 출시 전 운영자/법무 검토
- [ ] Google Play Console **Data safety** 입력값과 문서 내용 대조
- [ ] 앱 내 원스톱 계정 삭제 기능 구현 후 account-deletion 문서 갱신

## 주의

⚠️ 이 저장소의 문서는 법률 자문이 아닌 초안입니다. 실제 출시 전에 반드시 운영자/법무 검토를 거치세요.
