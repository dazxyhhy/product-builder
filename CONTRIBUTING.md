# 커밋 규칙 (Commit Conventions)

이 프로젝트는 일관된 커밋 히스토리 관리를 위해 **Conventional Commits** 스타일을 따릅니다.

## 1. 커밋 메시지 구조

```
<type>: <description>
```

## 2. 타입(Type) 규정

기존 히스토리 분석 결과, 다음과 같은 타입을 주로 사용합니다:

- **feat**: 새로운 기능 추가 (예: 블로그 글 추가, 새로운 페이지 생성)
- **fix**: 버그 수정 (예: 잘못된 링크 수정, 깨진 레이아웃 수정)
- **docs**: 문서 수정 (예: README 수정, 사이트맵 업데이트)
- **chore**: 빌드 업무 수정, 패키지 매니저 설정, 단순 설정 변경 (예: 도메인 변경, 사이트 인증 태그 추가)
- **refactor**: 코드 리팩토링 (기능 변화 없이 코드 구조만 개선)

## 3. 작성 가이드라인

- **언어**: 현재 프로젝트는 영문 커밋 메시지를 주로 사용하고 있으나, 상황에 따라 한글 사용도 가능합니다. 단, 한 프로젝트 내에서는 가급적 일관성을 유지합니다.
- **제목**: 제목은 50자 이내로 핵심 내용을 요약합니다.
- **마침표**: 제목 끝에 마침표(.)를 찍지 않습니다.
- **소문자 사용**: 타입(Type)은 항상 소문자로 작성합니다.

## 4. 실제 적용 사례 (Examples)

- `feat: Add two new blog posts and update blog index`
- `fix: Update Disqus shortname in share-luck.html`
- `chore: Add Google Site Verification tag`
- `docs: Update sitemap with new and enhanced articles`

---
이 규칙은 프로젝트의 가독성과 유지보수성을 높이기 위해 준수해 주시기 바랍니다.
