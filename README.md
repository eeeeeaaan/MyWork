# Portfolio

블랙 테마 개인 포트폴리오 사이트. 순수 HTML/CSS/JS로 작성되어 있어 빌드 과정 없이 바로 GitHub Pages로 배포할 수 있습니다.

## 구조

```
index.html      메인 페이지 (섹션: 소개 / 학력 / 기술 스택 / 수상 내역 / 프로젝트 / 활동 이력 / 연락처)
css/style.css   스타일 (블랙 배경 + 라임 포인트 컬러의 에디토리얼 무드)
js/main.js      모바일 메뉴, 스크롤 리빌 애니메이션, 프로젝트 필터
```

## 내용 채우기

`index.html` 안의 아래와 같은 자리표시자(placeholder) 텍스트를 실제 내용으로 바꿔주세요.

- 이름 / 별명 / 소속 / 한 줄 소개
- `you@example.com`, `https://github.com/USERNAME`, 전화번호
- 학력, 기술 스택, 수상 내역, 활동 이력
- 프로젝트 카드 (`.project-card`) — 커버 이미지는 `.cover-1 ~ 4` 클래스의 그라디언트 placeholder이며, 실제 이미지로 교체하려면 `<a class="project-cover ...">` 내부에 `<img>`를 추가하세요.

## 로컬 미리보기

별도 빌드 없이 `index.html`을 브라우저로 열거나, 간단한 정적 서버로 실행하면 됩니다.

```bash
npx serve .
```

## GitHub Pages 배포

1. 이 프로젝트를 GitHub 저장소에 push 합니다. (예: `portfolio` 저장소)
2. 저장소 **Settings → Pages** 로 이동
3. **Source**: `Deploy from a branch` 선택
4. **Branch**: `main`, 폴더는 `/ (root)` 선택 후 저장
5. 잠시 후 `https://<username>.github.io/<repo-name>/` 주소로 배포됩니다.
