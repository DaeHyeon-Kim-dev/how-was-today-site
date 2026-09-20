# how-was-today-site

[오늘 어땠어?](https://apps.apple.com/kr/) iOS 앱의 공개 페이지.

- `index.html` — 소개
- `support.html` — 지원 · 자주 묻는 것 (App Store 지원 URL)
- `privacy.html` — 개인정보 처리방침 (대한민국 PIPA)
- `privacy-en.html` — Privacy Policy (미국 CCPA/CPRA · 일본 APPI)
- `tokushoho.html` — 特定商取引法に基づく表記 (일본 유료 앱 필수)

**출시 지역은 한국·일본·미국이다. 유럽에는 내지 않는다.**
그래서 영문판은 **GDPR 문서가 아니다** — 법적 근거(6조)·이동권(20조)·유출 통지(33조)·
진정권(77조)·EU 대리인(27조) 절이 없다. 적용되지 않는 법을 인용하지 않기 위해서다.
유럽에 낼 계획이 생기면 스킬의 `en` 로케일로 다시 뽑아야 한다.

**두 방침은 번역 관계가 아니다.** 한국어판에는 권익침해 구제기관·개인정보 보호책임자가 있고,
영문판에는 캘리포니아 권리(CCPA/CPRA)·일본 APPI 절이 있다. 서로 상대에게 없는 절이다.

앱 소스는 별도 비공개 저장소에 있다. 이 저장소에는 **공개해도 되는 것만** 둔다.

GitHub Pages로 서비스한다. `.nojekyll`이 있어 Jekyll을 거치지 않고 파일을 그대로 낸다 —
`.md`를 쓰면 링크가 `.html`로 바뀌면서 깨지기 때문이다.
