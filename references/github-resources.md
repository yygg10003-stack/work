# GitHub 연구 자료 목록 (경영학 연구용)

국제경영·전략경영, 마케팅·소비자행동, 연구방법론 연구에 쓸 수 있는 GitHub 공개 저장소를 모은 목록입니다.

- 조사일: 2026-10-07
- 모든 저장소는 조사일 기준으로 실제 존재하는지 확인했습니다.
- GitHub에는 **논문 원문보다 분석 코드·도구·데이터 수집 도구**가 주로 있습니다. 논문 검색은 아래 [5. 문헌 검색·리뷰](#5-문헌-검색리뷰) 도구나 Google Scholar, RISS, KCI, DBpia를 함께 쓰세요.

---

## 1. 연구방법론 · 통계 분석

### 구조방정식(SEM), 매개·조절효과

| 저장소 | 언어 | 용도 |
|---|---|---|
| [yrosseel/lavaan](https://github.com/yrosseel/lavaan) | R | 공분산 기반 구조방정식(CB-SEM)의 표준 패키지. 확인적 요인분석(CFA), 경로분석, 다집단 분석 |
| [sem-in-r/seminr](https://github.com/sem-in-r/seminr) | R | PLS-SEM(SmartPLS와 같은 방식)과 CB-SEM을 한 문법으로 추정. 조절효과(상호작용항) 지원 |
| [Kss2k/rmedsem](https://github.com/Kss2k/rmedsem) | R | lavaan·cSEM 등으로 추정한 모형의 매개효과 검정 (Baron & Kenny 1986, Zhao, Lynch & Chen 2010 방식) |
| [Kss2k/modsem](https://github.com/Kss2k/modsem) | R | 구조방정식에서 잠재변수 간 상호작용(조절효과) 분석 |
| [sfcheung/manymome](https://github.com/sfcheung/manymome) | R | 회귀·SEM 추정 후 매개, 조절, 조절된 매개효과 계산. PROCESS 매크로 대안으로 활용 가능 |

### 연구 설계 · 실험

| 저장소 | 언어 | 용도 |
|---|---|---|
| [DeclareDesign/DeclareDesign](https://github.com/DeclareDesign/DeclareDesign) | R | 연구 설계를 코드로 정의하고, 표본 크기와 검정력을 시뮬레이션으로 점검 |
| [oTree-org/otree-core](https://github.com/oTree-org/otree-core) | Python | 온라인 행동 실험·설문 플랫폼. 소비자 의사결정 실험, 게임이론 실험에 활용 |

### 재현성 · 오픈 사이언스

| 저장소 | 용도 |
|---|---|
| [leipzig/awesome-reproducible-research](https://github.com/leipzig/awesome-reproducible-research) | 재현 가능한 연구 사례·도구·튜토리얼 모음 |
| [Social-Science-Data-Editors/template_README](https://github.com/Social-Science-Data-Editors/template_README) | 사회과학 학술지 데이터 편집자들이 만든 재현 패키지 README 양식 |
| [lmu-osc/introduction-to-r](https://github.com/lmu-osc/introduction-to-r) | 연구자를 위한 R 입문 교육 자료 (LMU 오픈사이언스센터) |

---

## 2. 마케팅 · 소비자행동

### 선호 측정 (컨조인트 분석)

| 저장소 | 언어 | 용도 |
|---|---|---|
| [packagesR/conjoint](https://github.com/packagesR/conjoint) | R | 전통적 컨조인트 분석으로 소비자의 진술 선호 측정. 속성별 부분가치와 상대적 중요도 산출 |

### 텍스트 마이닝 (리뷰·SNS·소비자 의견 분석)

| 저장소 | 언어 | 용도 |
|---|---|---|
| [konlpy/konlpy](https://github.com/konlpy/konlpy) | Python | **한국어** 형태소 분석. 국내 쇼핑몰 리뷰·SNS 분석의 기본 도구 |
| [lsh23/textmining-tutorial](https://github.com/lsh23/textmining-tutorial) | Python | KoNLPy 기반 한국어 텍스트마이닝 튜토리얼 (토큰화, 문서 분류, 연관어 분석) |
| [juliasilge/tidytext](https://github.com/juliasilge/tidytext) | R | 텍스트 정리와 감성분석 |
| [quanteda/quanteda](https://github.com/quanteda/quanteda) | R | 사회과학용 정량 텍스트 분석 |
| [bstewart/stm](https://github.com/bstewart/stm) | R | 구조적 토픽 모형(STM). 문서 속성(예: 평점, 국가)에 따라 토픽이 어떻게 달라지는지 분석 |
| [MaartenGr/BERTopic](https://github.com/MaartenGr/BERTopic) | Python | 언어모델 기반 토픽 모델링. 다국어 리뷰 분석에 유용 |

---

## 3. 국제경영 · 전략경영

### 기업 데이터

| 저장소 | 언어 | 용도 |
|---|---|---|
| [statzhero/wrds](https://github.com/statzhero/wrds) | R | WRDS 데이터 접근 (Compustat 재무자료, 연결 테이블). **기관 구독 필요** |
| [dgunning/edgartools](https://github.com/dgunning/edgartools) | Python | 미국 SEC 공시(10-K, 10-Q, 8-K) 수집과 재무제표 추출. 사업보고서 텍스트로 전략 변화를 분석할 때 활용 |
| [PatentsView/PatentsView-DB](https://github.com/PatentsView/PatentsView-DB) | Python | 미국 특허 데이터베이스 구축 코드. 기업의 혁신·기술 역량 측정 |

### 국가 · 거시 데이터

| 저장소 | 언어 | 용도 |
|---|---|---|
| [vincentarelbundock/WDI](https://github.com/vincentarelbundock/WDI) | R | 세계은행 세계개발지표(WDI) 다운로드. 진출국의 GDP, 제도 수준 등 통제변수 구성 |
| [pachadotdev/wbstats](https://github.com/pachadotdev/wbstats) | R | 세계은행 API 검색과 다운로드 (WDI와 비슷한 기능, 다국어 메타데이터 지원) |

### 사건연구 (공시·M&A·해외진출 발표 효과)

| 저장소 | 언어 | 용도 |
|---|---|---|
| [JMSLab/eventstudyr](https://github.com/JMSLab/eventstudyr) | R | 패널 데이터 사건연구 추정 (Freyaldenhoven et al. 2021 권고 방식) |
| [nipfpmf/eventstudies](https://github.com/nipfpmf/eventstudies) | R | 주가 비정상수익률(CAR) 기반의 전통적 사건연구. 2019년 이후 업데이트 없음 |

> **문화적 거리(Hofstede 등)**: 검증된 GitHub 패키지를 찾지 못했습니다. Hofstede 차원 점수를 공식 출처에서 받은 뒤 R로 Kogut–Singh 지수를 직접 계산하고, 국가코드(ISO)로 WDI 자료와 합치는 방법을 추천합니다.

---

## 4. 논문 작성 도구

| 저장소 | 용도 |
|---|---|
| [quarto-dev/quarto-cli](https://github.com/quarto-dev/quarto-cli) | 분석 코드와 논문 본문을 한 문서로 작성해 Word·PDF·HTML로 출력 |
| [citation-style-language/styles](https://github.com/citation-style-language/styles) | APA 등 인용 스타일(CSL) 모음. Zotero·Quarto와 연동 |

---

## 5. 문헌 검색·리뷰

| 저장소 | 언어 | 용도 |
|---|---|---|
| [massimoaria/bibliometrix](https://github.com/massimoaria/bibliometrix) | R | 계량서지학 분석. 연구 동향, 공동인용 네트워크, 핵심 저자·학술지 분석. 경영학 체계적 문헌고찰에 많이 쓰임 |
| [ropensci/openalexR](https://github.com/ropensci/openalexR) | R | OpenAlex(공개 학술 DB)에서 논문 메타데이터 수집 |
| [J535D165/pyalex](https://github.com/J535D165/pyalex) | Python | OpenAlex API의 Python 클라이언트 |

---

## 연구 흐름별 조합 예시

1. **문헌고찰**: `openalexR`로 논문 수집 → `bibliometrix`로 연구 동향 분석
2. **설문 연구** (예: 소비자 태도 → 구매의도): `DeclareDesign`으로 표본 크기 점검 → `lavaan`으로 CFA → `seminr`(PLS-SEM)나 `lavaan`(CB-SEM)으로 구조모형 → `rmedsem`·`manymome`으로 매개·조절효과
3. **리뷰 분석** (예: 해외 브랜드에 대한 국내 소비자 인식): `konlpy`로 형태소 분석 → `stm`·`BERTopic`으로 토픽 도출 → `tidytext`로 감성분석
4. **국제경영 패널 연구** (예: 해외진출과 기업성과): `wrds`·`edgartools`로 기업자료 → `WDI`로 국가 변수 → 패널회귀 또는 `eventstudyr`로 사건연구

## 주의사항

- WRDS·Compustat은 소속 기관의 구독이 있어야 쓸 수 있습니다.
- 설문 원자료 등 개인정보가 담긴 데이터는 공개 저장소에 올리지 마세요.
- 패키지는 버전에 따라 사용법이 바뀔 수 있으니 실제로 쓸 때는 각 저장소의 README를 확인하세요.
