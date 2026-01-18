# 💍 MYSTIC RING (신비한 반지)

**"운명을 확인하는 신비한 공간"**


**MYSTIC RING**은 반지의 제왕 세계관의 신비로운 분위기를 테마로 한 웹 애플리케이션 플랫폼입니다. 단순한 로또 번호 생성을 넘어, 꿈해몽, 관상 테스트, 운세 스토리 등 다양한 서브 콘텐츠를 통해 사용자에게 특별한 서사적 경험과 소소한 즐거움을 제공합니다.

## ✨ 주요 기능 및 프로젝트

### 1. 🔮 신비한 반지 로또 (Main Generator)
<img width="1892" height="874" alt="image" src="https://github.com/user-attachments/assets/673d6502-f23b-4685-83bd-1db72e4fef98" />

*   **파일**: `index.html`
*   **핵심 기능**:
    *   **랜덤 번호 생성**: 절대 반지의 힘을 빌린다는 컨셉의 로또 6/45 번호 추첨 애니메이션.
    *   **운명 각인 (History)**: 마음에 드는 번호를 로컬 스토리지에 영구 저장하고 언제든 열람 가능 (영수증 스타일 UI).
    *   **반응형 디자인**: 모바일과 데스크톱 모두에 최적화된 실제 복권 용지 스타일의 UI.
      


### 2. 🌙 꿈해몽 번호 변환기 (Dream Interpreter)
<img width="1894" height="898" alt="image" src="https://github.com/user-attachments/assets/77ecc08c-3444-4046-ad2c-a8378dc83d44" />

*   **파일**: `dream-lotto.html`
*   **기능**: 사용자가 꾼 꿈의 키워드(예: 돼지, 불, 똥)를 입력하면 고유 알고리즘을 통해 관련된 행운의 숫자로 변환해 줍니다.



### 3. 🐾 힐링 쉼터 (Animal Face AI)
<img width="1882" height="880" alt="image" src="https://github.com/user-attachments/assets/f42b72ca-5652-43a2-a658-7ab1d77e9226" />

*   **파일**: `animal-test.html`
*   **기능**: 사용자의 사진을 분석하여 강아지상, 고양이상 등 닮은 동물상을 찾아주는 AI 기반 심리 테스트입니다. (이미지는 서버로 전송되지 않습니다)
*   **모델**: Teachable Machine 활용



### 4. 🗣️ 행운 공유소 (Community)
<img width="1886" height="868" alt="image" src="https://github.com/user-attachments/assets/3af4dd75-4f65-497c-9e9c-a851cbe7b59b" />
<img width="1888" height="894" alt="image" src="https://github.com/user-attachments/assets/56ad37d6-210f-4aa4-b929-81e7ea8eb7d7" />

*   **파일**: `share-luck.html`
*   **기능**: 사용자들이 자신의 행운을 공유하고 댓글을 남길 수 있는 소통 공간입니다.


### 5. 📜 운명의 기록관 (Blog)
<img width="1892" height="892" alt="image" src="https://github.com/user-attachments/assets/34a6b158-3048-4378-b8f4-2a93c73647e6" />
<img width="1892" height="894" alt="image" src="https://github.com/user-attachments/assets/be75baf5-35a3-4a9c-af54-4ba9dfea94b0" />

*   **파일**: `blog.html`
*   **콘텐츠**: 확률, 통계, 운명론에 관한 흥미로운 읽을거리를 제공하며, 각 스토리 하단에서 바로 번호를 생성해볼 수 있도록 연동되어 있습니다.

### 모바일 화면
<img width="790" height="634" alt="image" src="https://github.com/user-attachments/assets/c5978981-8a1c-488a-8b93-84593a3eb5eb" />


## 🛠 기술 스택 (Tech Stack)

*   **Frontend**: HTML5, CSS3, JavaScript (Vanilla ES6+)
*   **Design**: 
    *   Flexbox & Grid Layout
    *   Responsive Web Design (Mobile First)
    *   CSS Animations (Keyframes)
*   **Storage**: Browser LocalStorage (No Backend required for core features)
*   **Fonts**: Google Fonts (Cinzel, Nanum Myeongjo, Libre Barcode 39)

## 🚀 설치 및 실행 (How to Run)

이 프로젝트는 별도의 빌드 과정이나 백엔드 서버가 필요 없는 **정적 웹사이트(Static Website)**입니다.

1. 저장소를 클론합니다.
   ```bash
   git clone https://github.com/dazxyhhy/product-builder.git
   ```
2. `product-builder` 폴더 내의 `index.html` 파일을 더블 클릭하거나 브라우저로 엽니다.
3. 바로 모든 기능을 사용할 수 있습니다.

## 📁 폴더 구조 (Structure)

```
product-builder/
├── index.html          # 메인 (로또 생성기 + 운명 각인)
├── dream-lotto.html    # 꿈해몽 변환기
├── animal-test.html    # 동물상 테스트
├── share-luck.html     # 행운 공유소 (게시판)
├── blog.html           # 블로그 메인
├── contact.html        # 예언 신청 및 문의
├── privacy.html        # 개인정보처리방침
├── story-*.html        # 블로그 스토리 상세 페이지들
└── assets/             # 이미지 및 정적 리소스
```

## 🎨 테마 및 스타일

*   **Dark Mode (Default)**: 검은 가죽 질감과 금색 폰트를 사용한 고급스럽고 신비로운 분위기.
*   **Light Mode**: 오래된 양피지와 지도 느낌을 주는 클래식한 분위기.
*   모든 페이지 우측 상단의 토글 버튼을 통해 테마를 자유롭게 변경할 수 있습니다.

---
*Disclaimer: 본 프로젝트는 재미를 위해 제작되었으며, 제공되는 번호나 운세 결과는 과학적 근거가 없습니다. 로또 당첨을 보장하지 않습니다.*

---

## 🔄 React 전환 계획 (React Migration Plan)

현재 사이트는 순수 HTML, CSS, JavaScript로 구성되어 있어 페이지가 늘어날수록 관리가 어렵습니다. 코드의 재사용성을 높이고 유지보수를 용이하게 하기 위해 React 기반의 프로젝트로 전환할 계획입니다.

1.  **Vite를 사용한 React 프로젝트 환경 설정**
    -   빠른 개발 서버와 최적화된 빌드 환경을 위해 Vite를 도입합니다.

2.  **공통 레이아웃 컴포넌트 생성**
    -   모든 페이지에서 재사용되는 `Header`, `Footer`, `NavigationBar` 등의 공통 UI를 컴포넌트로 분리합니다.

3.  **React Router를 사용한 페이지 라우팅 구현**
    -   각 HTML 페이지에 해당하는 경로를 설정하고, 페이지 간의 원활한 이동을 구현합니다.

4.  **페이지별 컴포넌트 전환**
    -   `index.html`을 시작으로 각 HTML 페이지의 내용을 React 컴포넌트 (`.jsx`)로 점진적으로 옮깁니다.
    -   기존 CSS와 JavaScript 로직을 각 컴포넌트에 맞게 통합하고 최적화합니다.

5.  **상태 관리 및 기능 고도화**
    -   컴포넌트별로 나뉘었던 상태(State)를 효율적으로 관리하고, React의 기능을 활용하여 사용자 경험을 개선합니다.
