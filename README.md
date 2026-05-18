# ⚡ NEO LOTTO (네오 로또)

**"행운을 잡는 가장 볼드한 방법"**

**NEO LOTTO**는 네오 브루탈리즘(Neo Brutalism) 디자인 시스템을 기반으로 한 감각적인 로또 번호 생성 및 운세 플랫폼입니다. 단순한 기능성을 넘어 강렬한 색상, 볼드한 테두리, 역동적인 타이포그래피를 통해 사용자에게 즐겁고 개성 있는 경험을 제공합니다.

## ✨ 주요 기능

### 1. ⚡ 메인 번호 생성기 (Main Generator)
<img width="1892" height="874" alt="image" src="https://github.com/user-attachments/assets/673d6502-f23b-4685-83bd-1db72e4fef98" />

*   **파일**: `index.html`
- **랜덤 번호 추첨**: 자바스크립트 표준 난수 알고리즘을 활용한 로또 6/45 번호 생성.
- **무한 루프 타이핑 효과**: 메인 타이틀에 적용된 감각적인 타이핑 애니메이션.
- **기록하기 (History)**: 생성된 번호를 로컬 스토리지에 저장하고 영수증 스타일로 관리.
- **이미지로 저장**: html2canvas를 활용하여 나만의 행운 티켓을 이미지 파일로 소장.

### 2. 🌙 꿈해몽 번호 변환기 (Dream Interpreter)
<img width="1894" height="898" alt="image" src="https://github.com/user-attachments/assets/77ecc08c-3444-4046-ad2c-a8378dc83d44" />
*   **파일**: `dream-lotto.html`
*   **기능**: 사용자가 꾼 꿈의 키워드(예: 돼지, 불, 똥)를 입력하면 고유 알고리즘을 통해 관련된 행운의 숫자로 변환해 줍니다.

### 3. 🐾 AI 동물상 테스트 (Animal Face AI)
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

## 🎨 디자인 철학: 네오 브루탈리즘 (Neo Brutalism)
- **강렬한 대비**: 고대비 색상 조합과 볼드한 검은색 테두리(`4px`).
- **정직한 레이아웃**: 그림자 효과(`box-shadow`)와 날카로운 각을 활용한 입체감.
- **역동적인 모션**: 스크롤 리빌(Scroll Reveal) 애니메이션과 안정적인 타이핑 효과.

## 🛠 기술 스택 (Tech Stack)

*   **Frontend**: HTML5, CSS3 (Custom Variables), JavaScript (Vanilla ES6+)
*   **Libraries**: 
    *   `html2canvas`: 티켓 이미지 캡처 기능
    *   `Intersection Observer API`: 스크롤 애니메이션 구현
*   **Fonts**: 
    *   `Outfit`: 제목 및 버튼용 볼드 폰트
    *   `Space Grotesk`: 본문 및 기술적 텍스트용
    *   `Noto Sans KR`: 가독성 높은 한글 폰트
*   **Analytics**: Google Analytics (GTAG), Microsoft Clarity

## 🚀 설치 및 실행 (How to Run)

1. 저장소를 클론합니다.
   ```bash
   git clone https://github.com/dazxyhhy/product-builder.git
   ```
2. 브라우저에서 `index.html`을 엽니다.

---
*Disclaimer: 본 서비스는 재미를 위해 제작되었으며 실제 당첨을 보장하지 않습니다. 과도한 복권 구매는 삶에 지장을 줄 수 있으니 유의하시기 바랍니다.*
