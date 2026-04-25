# 국기 골든벨 — 아시아·유럽편

아시아·유럽 국가의 국기를 맞추는 골든벨 퀴즈. 사회 과목 학습용.

## 라이브 데모

<https://jin-ttao.github.io/world-flag-quiz/>

## 원본 출처

이 게임은 [킹수학 (KingsMath.com)](https://kingsmath.com)이 제작한 [`king_so_flag`](https://github.com/kingsmath/web-games)를 기반으로 합니다.

원본 저장소: <https://github.com/kingsmath/web-games>

## 라이선스

[CC BY-NC 4.0 (저작자표시-비영리 4.0 국제)](https://creativecommons.org/licenses/by-nc/4.0/deed.ko) — 원본 라이선스를 그대로 상속합니다.

- 학교 수업, 개인 학습 등 비영리 용도로 자유롭게 사용·수정·배포할 수 있습니다.
- **상업적 이익을 얻는 모든 행위(광고 부착, 유료화 등)는 엄격히 금지됩니다.**
- 다른 곳에 게재할 경우 원작자(킹수학) 출처 표기 의무를 유지해야 합니다. (게임 시작 화면에 이미 출처 표기 포함)

## 변경 내역 (원본 대비)

- 출제 범위를 **아시아·유럽 국가로 한정** (국가 풀: easy 35 / medium 27 / hard 19)
  - 분류 기준: 한국 교과서 기준 (튀르키예·러시아·코카서스 3국·중앙아시아 포함, 키프로스=유럽)
- **원작자 GA4 추적 코드 제거** (배포 환경에서 원작자에게 트래픽 데이터가 흘러가지 않도록)
- 페이지 메타정보 한정 표기 (title, description, keywords)
- i18n `domain_txt` 모든 언어에서 빈 문자열로 통일

## 로컬 실행

별도 빌드·서버 불필요. `index.html`을 브라우저로 열면 됩니다.

```bash
open index.html
```

## 외부 의존 (CDN)

- Tailwind CSS, Font Awesome, Google Fonts (Jua / Noto Sans KR)
- 국기 이미지: [flagcdn.com](https://flagcdn.com)
