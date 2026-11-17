# team6-linux-docker-study

현대 AI 인사이트 캠퍼스 6팀의 **리눅스·도커 팀별 스터디** 레포예요. 실습 파일과 학습 정리를 모아요.

- 기간: 2026.11.18 ~ 12.23 (6주)
- 사이트: https://thswogh.github.io/team6-linux-docker-study/
- 진행: 월·수 조 단위 발표, 목 8교시 공통 실습

## 폴더 구조

```
practice/    실습 파일 (w주차-주제/ 폴더로)
docs/        GitHub Pages로 공개되는 학습 정리
  notes/내영문이름/w주차-주제.md
templates/   글 템플릿 (note-template.md)
```

## 학습 정리 규칙

1. **주 1편 이상** 작성해요. 직접 친 명령어 기록이 꼭 들어가야 해요.
2. `templates/note-template.md`를 복사해서 `docs/notes/내영문이름/` 아래에 올려요.
3. 파일명은 `w주차-주제.md` (영문 소문자, 하이픈). 예: `w2-permission.md`
4. 인터넷 글을 참고했으면 출처를 적고 내 말로 바꿔 써요.

## 올리는 방법

`main`에 바로 올리지 않고 브랜치와 PR로 올려요. 조장이 리뷰하고, 승인되면 병합해요.

```
git clone https://github.com/thswogh/team6-linux-docker-study
git switch -c 내이름/w2-permission
git add .
git commit -m "[이름] w2 권한 정리 추가"
git push -u origin 내이름/w2-permission
```

Git이 어렵다면 GitHub 웹에서 파일을 올리고 "Create a new branch"를 고르면 PR이 만들어져요.

## 올리면 안 되는 것

- 비밀번호, 토큰, API 키, `.env` 파일
- 이메일·주소 등 개인정보가 보이는 스크린샷
- 큰 파일(영상 등)은 링크만 남겨요

이 레포와 사이트는 **공개**돼요. 공개해도 되는 내용만 올려요.
