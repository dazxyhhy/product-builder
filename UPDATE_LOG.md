# 📝 최근 업데이트 기록 (2026-05-19)

## 1. 메인 타이틀 타이핑 효과 (Typewriter Effect)
- **기능**: "WAKE UP YOUR LUCK" 문구가 자동으로 타이핑되었다가 지워지는 무한 루프 애니메이션 적용.
- **기술**: JavaScript의 `setTimeout`을 활용한 재귀적 함수(`typeWriter`) 호출을 통해 글자 단위(substring) 출력 및 삭제 타이밍 제어.
- **안정성**: `h1` 태그에 `min-height` 및 `width: 100%` 속성을 적용하여 글자 길이에 상관없이 레이아웃 박스의 크기가 일정하게 유지되도록 구현.

## 2. 헤더 디자인 최적화
- **기능**: 스크롤 시 불투명하고 견고한 단색 배경이 적용되는 네오 브루탈리즘 스타일 유지.
- **기술**: JavaScript의 `window.addEventListener("scroll")`을 통해 스크롤 위치 감지 후 `.scrolled` 클래스 토글. CSS에서 `background: var(--card-bg)` 속성 적용으로 테마 연동.

## 3. 스크롤 애니메이션 (Scroll Reveal)
- **기능**: 사용자가 페이지를 내릴 때 메뉴 카드와 SEO 콘텐츠가 자연스럽게 나타나는 효과(Fade & Slide-in).
- **기술**: 브라우저의 `Intersection Observer API`를 활용하여 요소가 화면에 나타나는 시점(threshold)을 감지. CSS의 `.reveal`, `.reveal-left`, `.reveal-right` 클래스와 `transition` 속성을 조합하여 시각적 생동감 부여.

## 4. 배경 데코레이션 (스티커 효과)
- **기능**: 이모지 스티커들(!, ★, ⚡, 💰)이 부드럽게 떠다니는 감각적인 배경 연출.
- **기술**: CSS `@keyframes float` 애니메이션과 `transform: translateY() rotate() scale()` 속성을 조합하여 각 요소별로 상이한 주기(8s~18s)의 무한 루프(`infinite`) 움직임 부여.

## 5. 모바일 전용 드로어 메뉴 (Mobile Drawer Menu)
- **기능**: 모바일 화면에서 메뉴 버튼(hamburger)을 통해 열고 닫을 수 있는 사이드 드로어 메뉴 구현.
- **기술**:
    - **UI**: 네오 브루탈리즘 스타일의 볼드한 테두리와 강력한 그림자(`box-shadow`)가 적용된 드로어 디자인.
    - **인터랙션**: JavaScript로 `.active` 클래스를 토글하여 드로어와 오버레이(Overlay)의 애니메이션 제어.
    - **UX**: 모바일 전용 테마 변경 버튼을 드로어 하단에 배치하여 접근성 향상.

## 6. 모바일 반응형 레이아웃 개선
- **기능**: 다양한 모바일 기기 대응을 위해 헤더, 히어로 섹션, 로또 번호 결과 등의 레이아웃 최적화.
- **기술**: 미디어 쿼리(`max-width: 850px`, `max-width: 480px`)를 세분화하여 패딩, 폰트 크기, 요소 간격 등을 조정. 특히 로또 번호 공(ball)의 크기를 모바일 화면에 맞춰 유연하게 조절.
