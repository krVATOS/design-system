# VATOS Design System

VATOS Design System은 VATOS의 문서, 발표자료, 보고서, 웹 콘텐츠, 데이터 표, 시각화 자료 등 다양한 산출물에 공통으로 적용되는 디자인 기준이다.

이 저장소는 `README.md`, `DESIGN.md`, `skill.md`, `assets/`, `specs/`, `references/`, `examples/`를 중심으로 운영한다.

---

## Purpose

이 디자인 시스템의 목적은 다음과 같다.

- VATOS 산출물의 브랜드 일관성 유지
- 문서, PPT, 보고서, 웹 콘텐츠의 디자인 품질 편차 감소
- AI 기반 문서 작성 시 참고할 수 있는 공통 기준 제공
- 컬러, 타이포그래피, 레이아웃, 컴포넌트, 테마 사용 기준 정리
- 외부 제출용 문서의 전문성, 신뢰감, 수정 가능성 확보
- 공식 로고 자산의 일관된 사용 기준 관리

---

## File Structure

```text
vatos-design-system/
├─ README.md
├─ DESIGN.md
├─ skill.md
├─ assets/
│  └─ logos/
│     ├─ CI_VATOS_logo_signature_slogan.png
│     ├─ CI_VATOS_logo_symbol_wordmark.png
│     ├─ CI_VATOS_wordmark_only.png
│     ├─ CI_VATOS_symbol_only.png
│     └─ CI_VATOS_dark_signature_slogan.png
├─ specs/
│  ├─ ppt-base.md
│  └─ word-base.md
├─ references/
│  └─ ref_layout_ppt.pptx
└─ examples/
   └─ HTML 예시 파일
```

| Path | Role |
|---|---|
| `README.md` | 디자인 시스템의 목적, 사용 방법, 운영 기준을 설명하는 안내 문서 |
| `DESIGN.md` | VATOS 디자인 기준, 토큰, 규칙, AI 작성 기준을 담은 핵심 기준서 |
| `assets/logos/` | VATOS 공식 로고 이미지 보관 폴더 |
| `specs/ppt-base.md` | PPT 산출물 작성 시 우선 적용할 슬라이드 레이아웃, 안전 영역, 밀도, 표 안정성 규격 |
| `specs/word-base.md` | Word 또는 일반 문서 산출물 작성 시 우선 참고할 문서 안정성 규격 |
| `references/ref_layout_ppt.pptx` | PPT 레이아웃, 위치, 정렬감, 마스터 슬라이드 용어를 확인하기 위한 참고 파일 |
| `examples/` | HTML 문서, 웹형 보고서, 시각화 자료 작성 시 참고할 예시 파일 보관 폴더 |

---

## Core Concept

VATOS Design System은 다음 방향성을 기준으로 한다.

```text
Refined, Urban, Professional, Technical, Trustworthy
```

VATOS 산출물은 화려한 장식보다 정보 구조, 가독성, 명확한 메시지 전달을 우선한다.

전문적이지만 낡지 않고, 현대적이지만 가볍지 않은 균형을 지향한다.

---

## Design Rule Priority

VATOS 산출물을 작성할 때 판단 우선순위는 다음과 같다.

1. 사용자가 제공한 원문 내용과 명시 요청
2. 산출물 유형별 규격 파일: `specs/`
   - PPT: `specs/ppt-base.md`
   - Word: `specs/word-base.md`
3. `DESIGN.md`
4. `assets/logos/`에 보관된 VATOS 공식 로고 자산
5. 사용자가 제공한 이미지, 아이콘, 템플릿 자산
6. `references/`에 보관된 참고 자료
   - PPT 레이아웃/마스터 슬라이드 참고: `references/ref_layout_ppt.pptx`
7. `examples/`에 보관된 HTML/웹형 문서 예시
8. `README.md`에 정의된 사용 방법과 운영 기준

AI 또는 작성자는 원문에 없는 내용을 임의로 추가하지 않는다.  
디자인 판단이 필요한 경우에는 임의로 확정하지 않고, 사용자가 확인할 수 있는 예시 또는 대안을 먼저 제시한다.

---

## Document Type Specs

문서 타입별 세부 규격은 `specs/` 하위 파일을 우선 참고한다. HTML 문서, 웹형 보고서, 시각화 자료를 작성할 때는 파일명을 일일이 지정하지 않아도 `examples/` 폴더의 예시들을 함께 참고한다.

| Output Type | Primary Spec | Additional Reference | Rule |
|---|---|---|---|
| PPT / Presentation | `specs/ppt-base.md` | `references/ref_layout_ppt.pptx` | 슬라이드 안전 영역, 중앙 배치, 콘텐츠 밀도, 마스터 슬라이드 용어, 레이아웃 위치를 함께 확인한다. |
| Word / General Document | `specs/word-base.md` | `DESIGN.md` | 여백, 페이지 흐름, 표 안정성, 불필요한 빈 페이지 방지를 우선한다. |
| HTML / Web Document | `DESIGN.md` | `examples/` | HTML 문서, 웹형 보고서, 시각화 자료는 예시 파일의 톤, 구조, 레이아웃 방식을 참고한다. |

`references/ref_layout_ppt.pptx`는 PPT 내용 작성용 원본이 아니라, 레이아웃과 위치를 참고하기 위한 디자인 참조 파일이다.

---

## DESIGN.md Sections

`DESIGN.md`는 기본 디자인 섹션과 VATOS 전용 확장 섹션으로 구성한다.

### Basic Design Sections

| Section | Description |
|---|---|
| `Overview` | VATOS Design System의 목적과 적용 범위 |
| `Colors` | 브랜드 컬러, 텍스트 컬러, 배경색, 보조 컬러, 상태 색상 기준 |
| `Typography` | 서체, 계층, 크기, 사용 규칙 |
| `Layout` | 정보 흐름, 여백, 그리드, 반응형 원칙 |
| `Elevation & Depth` | 보더, 그림자, Surface 단계 기준 |
| `Shapes` | Radius와 형태 기준 |
| `Components` | 카드, 표, 버튼, 배지, Notice Box, Metric Block 등 공통 컴포넌트 |
| `Do's and Don'ts` | 디자인 시스템 적용 시 지켜야 할 핵심 기준 |

### VATOS Extended Sections

| Section | Description |
|---|---|
| `Theme Variants` | Dark Theme, Light Theme, Urban Navy Theme 사용 기준 |
| `Brand Assets` | VATOS 로고, 심볼, 이미지, 아이콘 사용 기준 |
| `AI Writing Rules` | AI로 문서 작성 시 정확성, 보안, 저작권, 수정 가능성 기준 |
| `Change Log` | 버전 관리 기준과 변경 이력 |

---

## How to Use

### For AI Document Creation

AI에게 문서 작성을 요청할 때는 산출물 유형별 `specs/`를 먼저 확인하고, 공통 디자인은 `DESIGN.md`를 기준으로 삼는다. HTML 문서나 시각화 자료를 작성할 때는 `examples/` 폴더의 예시도 함께 참고한다.

권장 요청 방식:

```text
VATOS Design System의 specs/와 DESIGN.md 기준을 적용해서 작성해줘.

문서 목적:
대상 독자:
산출물 형식:
반영할 원문:
적용할 테마:
사용할 로고:
강조할 내용:
제외할 내용:
수정 가능 형태 필요 여부:
```

예시:

```text
VATOS Design System의 DESIGN.md 기준을 적용해서 고객 제출용 제안서 초안을 작성해줘.

문서 목적: 신규 고객사 제안
대상 독자: 고객사 임원 및 실무 담당자
산출물 형식: PPT
적용 규격: specs/ppt-base.md
참고 레이아웃: references/ref_layout_ppt.pptx
적용할 테마: Urban Navy Theme + Light Theme
사용할 로고: assets/logos/CI_VATOS_dark_signature_slogan.png
강조할 내용: 기술 전문성, 안정성, 도입 효과
제외할 내용: 내부 비용, 담당자 개인정보
수정 가능 형태: 필요
```

---

## Logo Assets

VATOS 공식 로고는 `assets/logos/` 하위에 보관한다.

| Logo Asset | File Path | Usage |
|---|---|---|
| Primary Signature + Slogan | `assets/logos/CI_VATOS_logo_signature_slogan.png` | 밝은 배경용 공식 시그니처. 회사소개서, 제안서, 외부 배포용 문서 표지와 브랜드 영역 |
| Symbol + Wordmark | `assets/logos/CI_VATOS_logo_symbol_wordmark.png` | VA 심볼과 VATOS 워드마크 조합. 일반 문서, 본문 상단, 표지 보조 로고 |
| Wordmark Only | `assets/logos/CI_VATOS_wordmark_only.png` | 공간이 좁은 영역, 하단 푸터, 보조 브랜드 표기 |
| Symbol Only | `assets/logos/CI_VATOS_symbol_only.png` | 아이콘, 워터마크, 썸네일, 작은 브랜드 마크 |
| Dark Background Signature | `assets/logos/CI_VATOS_dark_signature_slogan.png` | 어두운 네이비 계열 표지, 섹션 구분, Closing 화면 |

Markdown 문서에서 로고를 표시해야 할 경우에는 이미지를 문서에 직접 삽입하지 않고, 상대 경로로 참조한다.

```markdown
![VATOS Logo](assets/logos/CI_VATOS_logo_signature_slogan.png)
```

---

## Design Usage Principles

### Colors

- Urban Navy는 VATOS의 주요 브랜드 다크 배경으로 사용한다.
- Premium Dark는 검은색 메인 컬러가 아니라 깊이감 보조 다크 톤으로 사용한다.
- Vatos Cyan은 브랜드 포인트 컬러로 제한적으로 사용한다.
- Vatos Cyan을 성공, 개선, 완료 의미로 사용하지 않는다.
- Warm Coral, Soft Sage, Warm Amber는 보조 컬러로만 사용하며, Vatos Cyan을 대체하지 않는다.
- 상태 의미는 Semantic Color를 사용한다.

### Typography

- 기본 서체는 Pretendard를 사용한다.
- 하나의 산출물 안에서 여러 서체를 섞지 않는다.
- 제목은 단순 라벨이 아니라 핵심 메시지가 드러나도록 작성한다.
- 본문은 긴 문단보다 간결한 bullet 구성을 우선한다.

### Layout

- 한 페이지 또는 슬라이드에는 하나의 핵심 메시지를 중심으로 구성한다.
- 정보량이 많으면 페이지, 슬라이드, 섹션을 분리한다.
- 여백은 빈 공간이 아니라 정보 구조를 만드는 요소로 사용한다.
- 표, 카드, 차트, 긴 본문을 한 화면에 과도하게 혼합하지 않는다.

### Components

- 컴포넌트는 장식이 아니라 정보 구조를 명확하게 하기 위한 요소로 사용한다.
- 카드 하나에는 하나의 주제만 담는다.
- 표는 헤더, 단위, 기준, 정렬 규칙을 명확히 적용한다.
- Badge와 Tag는 색상만으로 의미를 전달하지 않고 텍스트 라벨을 함께 사용한다.

### Theme

- 모든 산출물을 Dark Theme로 만들지 않는다.
- 정보량이 많은 본문은 Light Theme를 우선 사용한다.
- 표지, 섹션 구분, Closing에는 Dark Theme 또는 Urban Navy Theme를 사용할 수 있다.
- 회사소개서, 제안서, 영업용 소개 자료에는 Urban Navy Theme를 우선 적용한다.

---

## Brand Asset Rules

VATOS 로고와 브랜드 자산은 승인된 파일만 사용한다.

- 공식 로고 파일은 `assets/logos/` 하위 자산을 사용한다.
- 로고 색상, 비율, 형태를 임의로 변경하지 않는다.
- 로고에 그림자, 테두리, 그라데이션, 효과를 추가하지 않는다.
- 밝은 배경과 어두운 배경에 맞는 로고를 구분해서 사용한다.
- 로고를 장식 패턴처럼 반복 사용하지 않는다.
- AI가 VATOS 로고나 유사 로고를 새로 생성하지 않는다.
- 외부 이미지나 아이콘은 출처와 사용 가능 여부가 명확한 경우에만 사용한다.
- Markdown 문서에는 로고 이미지를 직접 삽입하지 않고 상대 경로로 참조한다.

---

## AI Writing Rules

AI는 VATOS 문서 작성 시 다음 기준을 따른다.

- 제공된 원문에 없는 내용을 임의로 추가하지 않는다.
- 고객사명, 프로젝트명, 수치, 일정, 금액, 계약명은 원문 기준으로 유지한다.
- 자료에 없는 내용은 `추가 확인 필요` 또는 `자료 미제공`으로 표시한다.
- 성능 개선율, 비용 절감률, 매출 효과 등은 근거 없이 과장하지 않는다.
- 고객사 자료, 계약 정보, 개인정보, 계정 정보, 내부 대외비 자료는 업로드 가능 여부를 사전에 확인한다.
- 외부 배포용 문서는 사람이 최종 검수한다.
- 산출물은 가능한 한 수정 가능한 형태로 작성한다.
- 로고가 필요한 경우 `assets/logos/` 하위 공식 로고 파일을 사용한다.

---

## Editable Output Principle

PPT, Word, Excel, HTML 등 수정 가능한 산출물에서는 로고와 원본 이미지 자산을 제외한 요소를 가능한 한 편집 가능한 형태로 작성한다.

- 텍스트는 편집 가능한 텍스트로 작성한다.
- 표는 편집 가능한 표로 작성한다.
- 카드, 다이어그램, 프로세스 구조는 도형과 텍스트로 구성한다.
- 차트는 가능한 한 편집 가능한 차트로 작성한다.
- 슬라이드 전체, 표, 카드, 텍스트 묶음을 통이미지로 삽입하지 않는다.
- 로고, 사진, 스크린샷, 승인된 원본 이미지는 이미지로 사용할 수 있다.

---

## Final Review Checklist

산출물 작성 후 아래 항목을 확인한다.

- [ ] 원문 내용이 누락 없이 반영되었는가?
- [ ] 원문에 없는 내용을 임의로 추가하지 않았는가?
- [ ] VATOS 컬러 시스템을 따르는가?
- [ ] Brand Color와 Semantic Color를 구분했는가?
- [ ] Urban Navy와 Premium Dark의 역할을 올바르게 사용했는가?
- [ ] Vatos Cyan을 포인트 컬러로만 사용했는가?
- [ ] Supporting Colors를 브랜드 메인 컬러처럼 사용하지 않았는가?
- [ ] Pretendard 또는 지정된 대체 서체를 사용했는가?
- [ ] 정보량이 많은 영역은 밝은 배경과 충분한 여백을 사용했는가?
- [ ] 표 정렬 기준을 지켰는가?
- [ ] 수치 데이터에 단위, 기준, 조건이 표시되었는가?
- [ ] 공식 로고를 `assets/logos/` 하위 파일 기준으로 사용했는가?
- [ ] 로고 색상, 비율, 형태를 변경하지 않았는가?
- [ ] 색상만으로 의미를 전달하지 않았는가?
- [ ] 과한 그림자, 과한 라운드, 과한 장식 효과를 사용하지 않았는가?
- [ ] 고객 제출용 문서가 캐주얼하거나 가벼워 보이지 않는가?
- [ ] 외부 자료 사용 시 출처와 사용 가능 여부를 확인했는가?
- [ ] 산출물이 가능한 한 수정 가능한 형태인가?

---

## Version

| 항목 | 내용 |
|---|---|
| Version | alpha |
| Revision | 2026.07.07 |
| Last Updated | 2026.07.07 |
