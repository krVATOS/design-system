---
name: vatos-design-system
description: VATOS 문서, 발표자료, 보고서, 제안서, 웹 콘텐츠, Markdown, HTML, PPT, Word 산출물 작성 시 VATOS Design System과 산출물 유형별 specs 기준을 적용하는 스킬입니다. 문서 유형별 작성 규격은 specs/를 우선 참고하고, 별도 디자인 요청이 없는 경우 specs/theme/document-theme-guide.md의 기본 문서 테마를 적용합니다.
---

# VATOS Design System Skill

이 스킬은 VATOS의 문서, 발표자료, 보고서, 제안서, 웹 콘텐츠, Markdown, HTML, PPT, Word 산출물을 작성하거나 수정할 때 VATOS Design System을 일관되게 적용하기 위한 기준이다.

## Reference Files

작업 시 아래 경로를 우선 참고한다.

```text
README.md
DESIGN.md
skill.md

specs/
assets/logos/
assets/theme/
references/
examples/
```

### Reference Usage Notes

- 저장소의 전체 구조와 사용 방법은 `README.md`를 참고한다.
- 공통 디자인 원칙, 컬러, 타이포그래피, 레이아웃, 컴포넌트 기준은 `DESIGN.md`를 따른다.
- 문서 작성 기본 테마는 `specs/theme/document-theme-guide.md`를 참고한다.
- 별도 디자인 요청이 없는 경우 `specs/theme/document-theme-guide.md`의 Urban Navy 기본 테마를 우선 적용한다.
- 기본 테마의 시각 기준 이미지는 `assets/theme/Theme-Urban-Navy.png`를 참고한다.
- PPT 또는 발표자료 작업은 `specs/ppt-base.md`를 우선 참고한다.
- Word 또는 일반 문서 작업은 `specs/word-base.md`를 우선 참고한다.
- PPT 레이아웃, 마스터 슬라이드 용어, 요소 위치, 정렬감, 여백감은 `references/` 폴더의 참고 자료를 확인한다.
- HTML 문서, 웹형 보고서, 시각화 예시가 필요한 경우 파일명을 특정하지 말고 `examples/` 폴더의 예시들을 함께 참고한다.
- 로고가 필요한 경우 `assets/logos/` 하위의 공식 로고 자산만 사용한다.
- 테마 참고 이미지가 필요한 경우 `assets/theme/` 하위의 테마 자산을 사용한다.

## Priority

VATOS 산출물을 생성하거나 수정할 때 판단 우선순위는 다음과 같다.

1. 사용자가 제공한 원문 내용과 명시 요청
2. 산출물 유형별 규격 파일: `specs/`
3. 문서 작성 기본 테마: `specs/theme/document-theme-guide.md`
4. 공통 디자인 기준: `DESIGN.md`
5. 공식 로고 및 테마 자산: `assets/logos/`, `assets/theme/`
6. 참고 레이아웃 자료: `references/`
7. 예시 산출물: `examples/`
8. 운영 안내: `README.md`
9. 문서 유형별 목적과 독자

PPT 또는 발표자료를 작성할 때는 `specs/ppt-base.md`를 우선 적용한다.  
PPT의 레이아웃, 위치, 정렬감, 마스터 슬라이드 용어는 `references/` 폴더의 참고 자료를 확인한다.  
Word 또는 일반 문서 산출물을 작성할 때는 `specs/word-base.md`를 우선 적용한다.  
HTML 문서, 웹형 보고서, 시각화 자료를 작성할 때는 `examples/` 폴더의 예시들을 함께 참고한다.

해당 산출물 유형의 규격 파일이 비어 있거나 없는 경우에는 `DESIGN.md`, `specs/theme/document-theme-guide.md`, 사용자의 명시 요청을 기준으로 작성한다.

## Core Design Direction

VATOS 산출물은 다음 인상을 유지해야 한다.

```text
Refined, Urban, Professional, Technical, Trustworthy
```

화려한 장식보다 정보 구조, 가독성, 명확한 메시지 전달을 우선한다.  
전문적이지만 낡지 않고, 현대적이지만 가볍지 않은 균형을 유지한다.

## Default Document Theme Rule

별도 디자인 요청이 없는 경우, VATOS 문서는 Urban Navy 기본 테마를 우선 적용한다.

```text
Theme Guide: specs/theme/document-theme-guide.md
Theme Reference: assets/theme/Theme-Urban-Navy.png
```

기본 테마 적용 범위는 다음과 같다.

- 표지: Urban Navy 배경, White 제목, Cyan 포인트
- 내지: Light Surface 기반, Navy accent, 얇은 보더, 정돈된 표와 카드
- 마무리 페이지: 표지와 동일한 Urban Navy 톤, Thank You 메시지, 회사 정보
- Header / Footer: 문서 정보, 슬로건, 페이지 번호, 옅은 구분선

단, 사용자가 별도 테마, 색상, 레이아웃, 문서 목적을 명시한 경우에는 사용자의 요청을 우선한다.

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

- 별도 디자인 요청이 없는 문서형 산출물은 `specs/theme/document-theme-guide.md`의 Urban Navy 기본 테마를 우선 적용한다.
- 표지, 섹션 구분, Closing에는 Dark Theme 또는 Urban Navy Theme를 사용할 수 있다.
- 정보량이 많은 본문, 표, 목록, 상세 설명은 Light Theme를 우선 사용한다.
- 회사소개서, 제안서, 영업용 소개 자료는 Urban Navy Theme와 Light Theme를 조합한다.
- 모든 산출물을 Dark Theme로 구성하지 않는다.
- Dark Theme에서는 Urban Navy를 메인 배경으로 사용하고, Premium Dark는 깊이감 보조 톤으로 사용한다.

## Brand Asset Rules

로고가 필요한 경우 `assets/logos/` 하위 공식 로고 파일만 사용한다.

### Logo Usage Rules

- 로고 색상, 비율, 형태를 임의로 변경하지 않는다.
- 로고에 그림자, 테두리, 그라데이션, 효과를 추가하지 않는다.
- 로고를 늘리거나 압축하거나 기울이거나 회전하지 않는다.
- AI가 VATOS 로고나 유사 로고를 새로 생성하지 않는다.
- Markdown 문서에서는 로고 이미지를 직접 삽입하지 않고 상대 경로로 참조한다.
- 구체적인 로고 파일명과 용도는 `DESIGN.md`의 Brand Assets 섹션을 따른다.

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
3. 산출물 형식을 확인한다.
4. 산출물 형식에 맞는 구조를 제안한다.
5. 산출물 유형별 규격 파일을 우선 확인한다.
   - PPT: `specs/ppt-base.md`
   - Word: `specs/word-base.md`
   - 기본 문서 테마: `specs/theme/document-theme-guide.md`
6. 별도 디자인 요청이 없으면 `assets/theme/Theme-Urban-Navy.png`의 Urban Navy 기본 테마를 적용한다.
7. HTML/웹형 문서는 `examples/` 폴더의 예시들을 함께 참고한다.
8. `DESIGN.md` 기준에 맞춰 컬러, 타이포그래피, 레이아웃, 컴포넌트를 적용한다.
9. 원문에 없는 내용은 임의로 추가하지 않는다.
10. 필요한 경우 사용자가 확인할 수 있는 시각화 예시나 대안을 먼저 제시한다.
11. 최종 산출 전 원문 정확성, 보안, 저작권, 브랜드 기준을 검토한다.

## Do Not

- Vatos Cyan을 성공 또는 개선 의미로 사용하지 않는다.
- Supporting Colors를 브랜드 메인 컬러처럼 사용하지 않는다.
- Premium Dark를 검은색 메인 배경처럼 남용하지 않는다.
- 순수 Black `#000000`을 기본 텍스트로 사용하지 않는다.
- 로고를 임의로 변형하지 않는다.
- 원문에 없는 내용을 임의로 추가하지 않는다.
- 고객 제출용 문서를 가볍거나 장난스럽게 표현하지 않는다.
- AI/노션 특유의 캐주얼한 카드형 디자인을 그대로 사용하지 않는다.
- 승인되지 않은 임의 스타일을 새로 만들지 않는다.

## Document Output Stability Rules

VATOS 문서 작성 시 결과물이 깨지지 않도록 아래 규칙을 따른다.

### 1. Output Format First

문서를 작성하기 전에 산출물 형식을 먼저 판단한다.

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

PPT 또는 발표자료를 요청받은 경우, 먼저 산출물 목적과 슬라이드 구조를 정리한다.  
PPT 작성 시에는 `specs/ppt-base.md`를 우선 적용하고, 공통 디자인 기준은 `DESIGN.md`를 따른다.  
레이아웃, 위치, 마스터 슬라이드 용어, 요소 간 여백감은 `references/` 폴더의 참고 자료를 확인한다.

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
- 적용 규격: specs/ppt-base.md
- 참고 자료: references/
- 기본 테마: specs/theme/document-theme-guide.md

## 본문 내용
- ...
```

PPT 디자인을 직접 생성할 때는 다음을 지킨다.

- `specs/ppt-base.md`를 우선 적용한다.
- 레이아웃, 위치, 정렬감, 마스터 슬라이드 용어는 `references/` 폴더의 참고 자료를 확인한다.
- 별도 디자인 요청이 없는 경우 표지와 Closing은 `specs/theme/document-theme-guide.md`의 Urban Navy 테마를 우선 참고한다.
- 기본 슬라이드 비율은 16:9를 기준으로 한다.
- 슬라이드 하나에는 하나의 핵심 메시지만 담는다.
- 주요 콘텐츠는 슬라이드 중앙 안전 영역 안에 배치한다.
- 콘텐츠 그룹 전체가 좌측 또는 우측으로 치우쳐 보이지 않도록 한다.
- 좌측 정렬 텍스트를 사용하더라도 콘텐츠 블록 전체는 중앙 안전 영역 안에 있어야 한다.
- 표, 카드, 차트, 다이어그램은 슬라이드 중앙축을 기준으로 균형 있게 배치한다.
- 배경 장식, 사선 레이어, 로고 위치를 기준으로 본문 콘텐츠를 정렬하지 않는다.
- 표지와 섹션 구분 슬라이드는 비대칭 구성이 가능하지만, 의도된 디자인이어야 한다.
- 표, 카드, 다이어그램은 수정 가능한 구조를 우선한다.
- 슬라이드 전체를 통이미지로 만들지 않는다.
- 텍스트는 텍스트로 유지한다.
- 표는 편집 가능한 표 또는 도형/텍스트 조합으로 구성한다.
- 로고, 사진, 스크린샷만 이미지로 사용한다.

### 5. Word / Document Rules

Word 또는 일반 문서 산출물을 요청받은 경우 `specs/word-base.md`를 우선 참고한다.  
공통 브랜드 컬러, 로고, 타이포그래피, 디자인 톤, 표 정렬, 수정 가능성 원칙은 `DESIGN.md`를 따른다.  
별도 디자인 요청이 없는 경우 표지, 본문 머리말/바닥글, 마무리 페이지는 `specs/theme/document-theme-guide.md`의 Urban Navy 기본 테마를 우선 참고한다.

- Word 문서는 표지, 제목 계층, 본문, 표, 주석, 검토 체크리스트가 깨지지 않도록 구성한다.
- 기본 여백과 페이지 흐름을 우선하며, 불필요한 빈 페이지가 생성되지 않도록 한다.
- 표가 한 페이지에서 과도하게 깨질 경우 표를 분리하거나 요약 표와 상세 표로 나눈다.
- Word 세부 규격은 `specs/word-base.md`를 기준으로 하며, 규격이 부족한 경우 `DESIGN.md`의 공통 문서 안정성 규칙을 따른다.

### 6. Table Stability Rules

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

### 7. Long Document Rules

긴 문서를 작성할 때는 한 번에 완성본을 만들지 않고, 아래 순서로 작성한다.

1. 문서 구조 초안
2. 섹션별 본문 작성
3. 표 / 카드 / 다이어그램 정리
4. 디자인 기준 적용
5. 최종 검토 체크리스트

긴 문서는 한 응답에 모두 압축하지 않는다.  
문서가 길어질 경우 섹션 단위로 나누어 작성한다.

### 8. Content Fidelity Rules

문서 작성 시 제공되지 않은 내용은 임의로 만들지 않는다.

- 회사 정보, 고객사명, 프로젝트명, 수치, 일정, 금액은 원문 기준으로 유지한다.
- 근거 없는 성과 수치, 개선율, 비용 절감률을 생성하지 않는다.
- 자료가 없는 경우 `추가 확인 필요` 또는 `자료 미제공`으로 표시한다.
- 디자인을 위해 내용을 과장하거나 의미를 바꾸지 않는다.

### 9. Safe Default Output

사용자가 별도 형식을 지정하지 않은 경우 기본 출력은 아래 기준을 따른다.

```text
Format: Markdown
Theme: Light Theme
Default Document Theme: specs/theme/document-theme-guide.md
Theme Reference: assets/theme/Theme-Urban-Navy.png
Tone: Professional / Technical / Trustworthy
Structure: 제목 → 요약 → 본문 → 표 또는 목록 → 검토사항
Logo: 필요 시 assets/logos/ 상대 경로 사용
```

### 10. Do Not Generate

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
