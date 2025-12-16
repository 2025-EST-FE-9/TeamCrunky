# Project Name
롯데웰푸드 사이트의 메인/배너 페이지를 따라서 제작하는 웹 프로젝트


## Procject Information
본 프로젝트는 롯데웰푸드 공식 홈페이지를 기반으로 실무에서 자주 사용되는 반응형 레이아웃, 캐러셀 인터랙션,
그리고 Tailwind CSS 기반의 유틸리티 설계를 학습·적용하기 위해 진행한 팀 프로젝트입니다.


## Project Goal
- Tailwind CSS 유틸리티 기반 설계 경험
- 실제 서비스 수준의 레이아웃 구조 이해
- Flex / Grid + clamp() / media query를 활용한 반응형 설계 역량 강화
- 협업을 통한 코드 구조 분리 및 통합 경험


## Screen Preview
🏠 Main Page
<table> <tr> <th align="center">Desktop</th> <th align="center">Mobile</th> </tr> <tr> <td align="center"> <img src="/img/main.html.png" width="420" /> </td> <td align="center"> <img src="/img/main.html(mobile).png" width="220" /> </td> </tr> </table>
🅰️ Sub Page – Banner A (Global)
<table> <tr> <th align="center">Desktop</th> <th align="center">Mobile</th> </tr> <tr> <td align="center"> <img src="/img/bannerA(global).html.png" width="420" /> </td> <td align="center"> <img src="/img/bannerA(global).html(mobile).png" width="220" /> </td> </tr> </table>
🅱️ Sub Page – Banner B (Bus)
<table> <tr> <th align="center">Desktop</th> <th align="center">Mobile</th> </tr> <tr> <td align="center"> <img src="/img/bannerB(bus).html.png" width="420" /> </td> <td align="center"> <img src="/img/bannerB(bus).html(mobile).png" width="220" /> </td> </tr> </table>


## Tech Stack
- HTML5
- CSS3
- Tailwind CSS
   ㄴ 유틸리티 기반 스타일링으로 클래스 충돌 최소화
   ㄴ 협업 환경에서 빠른 UI 구현 가능
- Canva (PPT)
   ㄴ 발표 자료 및 시각적 구조 정리
- Git / Github
   ㄴ 파일 통합 및 협업

⚙️ Implemented Features
- Layout & UI
   ㄴ 모바일 / 데스크톱 반응형 레이아웃
   ㄴ Flex / Grid 기반 콘텐츠 정렬
   ㄴ clamp()를 활용한 폰트 및 레이아웃 스케일링
- Interaction (No JavaScript)
   ㄴ Hover 기반 인터랙션
   ㄴ 카드형 캐러셀 UI
   ㄴ 드롭다운 메뉴
   ㄴ 탭 리스트 / 검색 컨트롤
   ㄴ Breadcrumb UI
   ㄴ 입력 요소 커스텀 스타일링
      → input + label + peer 패턴 활용


## AI Leverage
- 레이아웃 구조 설계 아이디어 도출
- Tailwind 클래스 조합 및 인터랙션 패턴 설계 보조


## Limitations / Improvements
- 반복코드에 대한 컴포넌트화
- 테일윈드 공식 문서에 없는 값을 커스텀 하려면 직접 CSS 파일 필요
- 테일윈드 공식 문서에서 제공되지 않는 코드
- CSS 지식


## What We Learned
- 테일윈드CSS 프레임워크의 실무적 장단점 체감
- JS없는 인터랙션 설계 경험
- 반응형 레이아웃의 구조 이해
- Positioning과 레이어 개념의 실제 활용


## 📂 Folder Structure
├── main.html
│   └── bannerA(global).html
│   └── bannerB(bus).html
├── img/
└── _draft/ #통합 전 개인 작업 폴더 
    └── 김준민- headerFooter
    └── 심수완- mainA(1~3)
    └── 김선관- mainB(4~6)
    └── 서우주- bannerA(global)/
    └── 권창은- bannerB(bus)/


## 👥 Team
- 김준민: 헤더/푸터/플로팅메뉴(main)
- 심수완: 메인페이지 1~3(main)
- 김선관: 메인페이지 4~6(main)
- 서우주: 글로벌 IR 안내페이지 (bannerA)
- 권창은: 버스 배너 페이지 (bannerB)



