# cafe-w
카페 W 클론 프로젝트 - Position Absolute
---
## 목표
  1. 시멘틱 마크업
  2. 웹 접근성 준수
  3. SEO 준수
  4. git/github 협업
  5. 한 달간의 성장 확인
## 사용 기술
  1. html/css
  2. git/github
  3. zoom
## 컨벤션
  1. BEM
  2. Conventional Commit
  3. vs code 설정 통일
  4. class명은 K.C. id명은 C.C로 통일
---
## 마크업시 고려한 것
  ### section recommend-beverage
  1. figure 안에 img와 figcaqtion 따로 a 래핑.
  ### section recommend-leacture
  1. li 안에 모달창 마크업, 모달창에 h4
  2. 모달창, 별점, 닫기 버튼, 아이콘 등 모듈화를 위한 네이밍(class="close-btn").
  3. table로 만든 모달창의 상세정보에서, id, headers 속성을 사용. 키와 값을 명시적으로 연결.
  ### section review
  1. section 영역 안에 독립된 리뷰로 article
  2. 긴 인용문(블록 레벨)이므로, blockqutoe 사용.
  ### section brochure
  1. 영역 전체 링크인데, 요소 각각을 a로 묶음.
  ### section video

  ### section reserve

  ### section medal
  1. h1, p, a 로 마크업 후, 메달 렌더링을 위한 div 래핑.
  ### section store
  1. 단순 문구로 보이는 매장 종류를 ul로 마크업.
  2. 매장 관련 이미지로, 추후 변경 또는 추가가 될 수 있으므로 마크업함.