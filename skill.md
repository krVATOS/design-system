---
name: vatos-design-system
description: VATOS 문서, 발표자료, 보고서, 제안서, 웹 콘텐츠, Markdown, HTML 산출물 작성 시 VATOS Design System 기준을 적용하는 스킬입니다. DESIGN.md와 README.md를 우선 참고하고, 공식 로고는 assets/logos/ 하위 자산만 사용합니다.
---

# VATOS Design System Skill

이 스킬은 VATOS의 문서, 발표자료, 보고서, 제안서, 웹 콘텐츠, Markdown, HTML 산출물을 작성하거나 수정할 때 VATOS Design System을 일관되게 적용하기 위한 기준이다.

## Reference Files

작업 시 아래 파일을 우선 참고한다.

```text
vatos-design-system/
├─ README.md
├─ DESIGN.md
└─ assets/
   └─ logos/
      ├─ CI_VATOS_logo_signature_slogan.png
      ├─ CI_VATOS_logo_symbol_wordmark.png
      ├─ CI_VATOS_wordmark_only.png
      ├─ CI_VATOS_symbol_only.png
      └─ CI_VATOS_dark_signature_slogan.png
```

## Priority

VATOS 산출물을 생성하거나 수정할 때 판단 우선순위는 다음과 같다.

1. 사용자가 제공한 원문 내용과 명시 요청
2. `DESIGN.md`
3. `assets/logos/`에 보관된 VATOS 공식 로고 자산
4. 사용자가 제공한 이미지, 아이콘, 템플릿 자산
5. `README.md`에 정의된 사용 방법과 운영 기준
6. 문서 유형별 목적과 독자

사용자가 명시한 요청이 있으면 해당 요청을 우선하되, 가능한 범위 안에서 VATOS Design System과 충돌하지 않도록 조정한다.

## Core Design Direction

VATOS 산출물은 다음 인상을 유지해야 한다.

```text
Refined, Urban, Professional, Technical, Trustworthy
```

화려한 장식보다 정보 구조, 가독성, 명확한 메시지 전달을 우선한다.  
전문적이지만 낡지 않고, 현대적이지만 가볍지 않은 균형을 유지한다.

## Color Rules

`DESIGN.md`에 정의된 컬러 기준을 따른다.

- Urban Navy는 VATOS의 주요 브랜드 다크 배경으로 사용한다.
- Premium Dark는 검은색 메인 컬러가 아니라 깊이감 보조 다크 톤으로 사용한다.
- Vatos Cyan은 브랜드 포인트 컬러로 제한적으로 사용한다.
- Vatos Cyan을 성공, 개선, 완료 의미로 사용하지 않는다.
- Warm Coral, Soft Sage, Warm Amber는 보조 컬러로만 사용하며, Vatos Cyan을 대체하지 않는다.
- 상태 의미는 Semantic Color를 사용한다.
- 순수 Black `#000000`을 기본 텍스트로 사용하지 않는다.

## Typography Rules

- 기본 서체는 Pretendard를 사용한다.
- Pretendard 사용이 어려운 경우 `Noto Sans KR`, `Malgun Gothic`, `Arial`, `sans-serif` 순서로 대체한다.
- 하나의 산출물 안에서 여러 서체를 섞지 않는다.
- 제목은 단순 라벨이 아니라 핵심 메시지가 드러나도록 작성한다.
- 본문은 긴 문단보다 간결한 bullet 구성을 우선한다.

## Layout Rules

- 한 페이지 또는 슬라이드에는 하나의 핵심 메시지를 중심으로 구성한다.
- 정보량이 많으면 페이지, 슬라이드, 섹션을 분리한다.
- 여백은 빈 공간이 아니라 정보 구조를 만드는 요소로 사용한다.
- 표, 카드, 차트, 긴 본문을 한 화면에 과도하게 혼합하지 않는다.
- 정렬 기준을 일관되게 유지한다.
- 숫자는 비교가 쉽도록 오른쪽 정렬한다.
- 긴 문장형 텍스트는 왼쪽 정렬한다.
- 상태, 구분, 여부처럼 짧은 값은 가운데 정렬한다.

## Theme Rules

산출물 목적과 정보량에 따라 테마를 선택한다.

- 표지, 섹션 구분, Closing에는 Dark Theme 또는 Urban Navy Theme를 사용할 수 있다.
- 정보량이 많은 본문, 표, 목록, 상세 설명은 Light Theme를 우선 사용한다.
- 회사소개서, 제안서, 영업용 소개 자료는 Urban Navy Theme와 Light Theme를 조합한다.
- 모든 산출물을 Dark Theme로 구성하지 않는다.
- Dark Theme에서는 Urban Navy를 메인 배경으로 사용하고, Premium Dark는 깊이감 보조 톤으로 사용한다.

## Brand Asset Rules

로고가 필요한 경우 `assets/logos/` 하위 공식 로고 파일만 사용한다.

| Logo Asset | File Path | Usage |
|---|---|---|
| Primary Signature + Slogan | `assets/logos/CI_VATOS_logo_signature_slogan.png` | 밝은 배경용 공식 시그니처 |
| Symbol + Wordmark | `assets/logos/CI_VATOS_logo_symbol_wordmark.png` | 일반 문서, 본문 상단, 표지 보조 로고 |
| Wordmark Only | `assets/logos/CI_VATOS_wordmark_only.png` | 공간이 좁은 영역, 하단 푸터 |
| Symbol Only | `assets/logos/CI_VATOS_symbol_only.png` | 아이콘, 워터마크, 썸네일 |
| Dark Background Signature | `assets/logos/CI_VATOS_dark_signature_slogan.png` | 어두운 네이비 계열 표지, 섹션 구분, Closing |

### Logo Restrictions

- 로고 색상, 비율, 형태를 임의로 변경하지 않는다.
- 로고에 그림자, 테두리, 그라데이션, 효과를 추가하지 않는다.
- 로고를 늘리거나 압축하거나 기울이거나 회전하지 않는다.
- AI가 VATOS 로고나 유사 로고를 새로 생성하지 않는다.
- Markdown 문서에서는 로고 이미지를 직접 삽입하지 않고 상대 경로로 참조한다.

예시:

```markdown
![VATOS Logo](assets/logos/CI_VATOS_logo_signature_slogan.png)
```

## AI Writing Rules

AI는 사용자가 제공한 원문과 자료를 기준으로 문서를 작성한다.

- 원문에 없는 내용을 임의로 추가하지 않는다.
- 고객사명, 프로젝트명, 제품명, 수치, 일정, 금액, 계약명, 실적 정보는 반드시 원문 기준으로 유지한다.
- 자료에 없는 내용은 추정하지 말고 `추가 확인 필요` 또는 `자료 미제공`으로 표시한다.
- 문장을 보기 좋게 다듬을 수는 있으나, 원문의 의미나 사실 관계를 변경하지 않는다.
- 성능 개선율, 비용 절감률, 매출 효과, 프로젝트 성과 등은 근거 없이 과장하지 않는다.
- 고객사 자료, 계약 정보, 견적 정보, 개인정보, 계정 정보, 내부 대외비 자료는 업로드 가능 여부를 사전에 확인해야 한다.
- 외부 배포용 문서는 사람이 최종 검수해야 한다.

## Editable Output Rules

PPT, Word, Excel, HTML 등 수정 가능한 산출물에서는 로고와 원본 이미지 자산을 제외한 요소를 가능한 한 편집 가능한 형태로 작성한다.

- 텍스트는 편집 가능한 텍스트로 작성한다.
- 표는 편집 가능한 표로 작성한다.
- 카드, 다이어그램, 프로세스 구조는 도형과 텍스트로 구성한다.
- 차트는 가능한 한 편집 가능한 차트로 작성한다.
- 슬라이드 전체, 표, 카드, 텍스트 묶음을 통이미지로 삽입하지 않는다.
- 로고, 사진, 스크린샷, 승인된 원본 이미지는 이미지로 사용할 수 있다.

## Output Behavior

사용자가 VATOS 문서 작성을 요청하면 다음 순서로 수행한다.

1. 문서 목적과 대상 독자를 파악한다.
2. 원문 내용과 필수 반영 정보를 확인한다.
3. 산출물 형식에 맞는 구조를 제안한다.
4. `DESIGN.md` 기준에 맞춰 컬러, 타이포그래피, 레이아웃, 컴포넌트를 적용한다.
5. 원문에 없는 내용은 임의로 추가하지 않는다.
6. 필요한 경우 사용자가 확인할 수 있는 시각화 예시나 대안을 먼저 제시한다.
7. 최종 산출 전 원문 정확성, 보안, 저작권, 브랜드 기준을 검토한다.

## Do Not

- Vatos Cyan을 성공 또는 개선 의미로 사용하지 않는다.
- Supporting Colors를 브랜드 메인 컬러처럼 사용하지 않는다.
- Premium Dark를 검은색 메인 배경처럼 남용하지 않는다.
- 순수 Black `#000000`을 기본 텍스트로 사용하지 않는다.
- 로고를 임의로 변형하지 않는다.
- 원문에 없는 내용을 임의로 추가하지 않는다.
- 고객 제출용 문서를 가볍거나 장난스럽게 표현하지 않는다.
- AI/노션 특유의 캐주얼한 카드형 디자인을 그대로 사용하지 않는다.

## Document Output Stability Rules

VATOS 문서 작성 시 결과물이 깨지지 않도록 아래 규칙을 반드시 따른다.

### 1. Output Format First

문서를 작성하기 전에 반드시 산출물 형식을 먼저 판단한다.

| Requested Output | Primary Format | Rule |
|---|---|---|
| Markdown 문서 | `.md` | 표준 Markdown만 사용한다 |
| HTML 문서 | `.html` | 단일 HTML 파일로 작성한다 |
| PPT 초안 | Markdown outline 또는 HTML preview | 실제 PPT가 필요한 경우 사용자가 명시해야 한다 |
| 보고서 초안 | Markdown | 본문, 표, 체크리스트 중심으로 작성한다 |
| 제안서 초안 | Markdown 또는 PPT outline | 슬라이드별 구조를 먼저 작성한다 |
| Word 문서 초안 | Markdown | 제목, 본문, 표 중심으로 작성한다 |

사용자가 산출물 형식을 명시하지 않은 경우 기본값은 Markdown이다.

### 2. Markdown Safety Rules

Markdown 문서를 작성할 때는 아래 규칙을 따른다.

- 표준 Markdown 문법만 사용한다.
- HTML 태그를 Markdown 안에 과도하게 섞지 않는다.
- CSS, JavaScript, iframe, external script를 포함하지 않는다.
- 표 안에 줄바꿈, HTML 태그, 긴 bullet을 넣지 않는다.
- 복잡한 표는 여러 개의 작은 표로 분리한다.
- 표가 너무 넓어질 경우 표 대신 bullet list 또는 카드형 섹션으로 작성한다.
- 이미지 경로는 상대 경로만 사용한다.
- 로고는 `assets/logos/` 하위 파일을 상대 경로로 참조한다.
- base64 이미지를 Markdown 안에 삽입하지 않는다.

### 3. HTML Safety Rules

HTML 문서를 작성할 때는 아래 규칙을 따른다.

- 단일 HTML 파일로 작성한다.
- 외부 CDN, 외부 CSS, 외부 JS를 사용하지 않는다.
- CSS는 `<style>` 태그 안에 포함한다.
- JavaScript는 꼭 필요한 경우에만 사용한다.
- React, Vue, Tailwind CDN, external font import를 사용하지 않는다.
- iframe을 사용하지 않는다.
- 이미지 파일은 상대 경로로 참조한다.
- 로고는 `assets/logos/` 하위 파일을 사용한다.
- 복잡한 애니메이션, 과한 hover 효과, 3D 효과를 사용하지 않는다.
- 모바일 대응은 단순한 media query 수준으로 처리한다.

### 4. PPT / Presentation Rules

PPT 또는 발표자료를 요청받은 경우, 먼저 슬라이드 구조를 작성한다.

슬라이드 작성 기본 순서:

1. 표지
2. 목차 또는 핵심 요약
3. 배경 / 목적
4. 주요 내용
5. 상세 설명
6. 기대 효과 또는 결론
7. Closing

PPT 초안을 Markdown으로 작성할 때는 아래 형식을 따른다.

```markdown
# 슬라이드 1. 제목

## 핵심 메시지
- ...

## 화면 구성
- 배경:
- 주요 요소:
- 사용할 로고:
- 컬러 테마:

## 본문 내용
- ...
```

PPT 디자인을 직접 생성할 때는 다음을 지킨다.

- 슬라이드 하나에는 하나의 핵심 메시지만 담는다.
- 표, 카드, 다이어그램은 수정 가능한 구조를 우선한다.
- 슬라이드 전체를 통이미지로 만들지 않는다.
- 텍스트는 텍스트로 유지한다.
- 표는 편집 가능한 표 또는 도형/텍스트 조합으로 구성한다.
- 로고, 사진, 스크린샷만 이미지로 사용한다.

### 5. Table Stability Rules

표가 깨지지 않도록 아래 기준을 따른다.

- 6개 컬럼을 초과하는 표는 지양한다.
- 긴 설명은 표 밖의 설명 문단으로 분리한다.
- 표 안에는 2줄 이상의 긴 문장을 넣지 않는다.
- 수치 컬럼은 오른쪽 정렬 기준으로 작성한다.
- 상태, 구분, 여부는 가운데 정렬 기준으로 작성한다.
- 설명, 비고, 처리내역은 왼쪽 정렬 기준으로 작성한다.
- 단위, 기준일, 조건은 표 제목 아래 또는 캡션으로 분리한다.

표가 복잡한 경우 아래 형식으로 대체한다.

```markdown
### 항목명

- 구분:
- 주요 내용:
- 수치:
- 상태:
- 비고:
```

### 6. Long Document Rules

긴 문서를 작성할 때는 한 번에 완성본을 만들지 않고, 아래 순서로 작성한다.

1. 문서 구조 초안
2. 섹션별 본문 작성
3. 표 / 카드 / 다이어그램 정리
4. 디자인 기준 적용
5. 최종 검토 체크리스트

긴 문서는 한 응답에 모두 압축하지 않는다.  
문서가 길어질 경우 섹션 단위로 나누어 작성한다.

### 7. Content Fidelity Rules

문서 작성 시 제공되지 않은 내용은 임의로 만들지 않는다.

- 회사 정보, 고객사명, 프로젝트명, 수치, 일정, 금액은 원문 기준으로 유지한다.
- 근거 없는 성과 수치, 개선율, 비용 절감률을 생성하지 않는다.
- 자료가 없는 경우 `추가 확인 필요` 또는 `자료 미제공`으로 표시한다.
- 디자인을 위해 내용을 과장하거나 의미를 바꾸지 않는다.

### 8. Safe Default Output

사용자가 별도 형식을 지정하지 않은 경우 기본 출력은 아래 기준을 따른다.

```text
Format: Markdown
Theme: Light Theme
Tone: Professional / Technical / Trustworthy
Structure: 제목 → 요약 → 본문 → 표 또는 목록 → 검토사항
Logo: 필요 시 assets/logos/ 상대 경로 사용
```

### 9. Do Not Generate

아래 항목은 생성하지 않는다.

- 깨질 가능성이 높은 복잡한 HTML
- 외부 CDN에 의존하는 코드
- 실행이 필요한 JavaScript 중심 문서
- base64 이미지가 포함된 Markdown
- 통이미지 형태의 문서
- 과도하게 넓은 Markdown 표
- 원문에 없는 수치나 성과
- 승인되지 않은 로고 또는 유사 로고
- VATOS 디자인 시스템과 다른 임의 스타일