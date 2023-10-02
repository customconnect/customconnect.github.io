# GitHub Blog 글쓰기

## 준비사항
- `https://github.com/sigmadream/gitblog-templates` 클론
- `[id].github.io`를 저장소 이름으로 설정

## 저장소의 README.md 및 각 종 정보를 수정
- README.md 파일 수정
- 저장소 소개 등에 필요한 정보를 수정

## 메타데이터를 기반으로 한 사이트 정의
- `_config.yml`
        - 사이트 제목, 간단한 소개와 같은 블로그 사이트 전반에 필요한 내용은
        `name`, `description`, `email`, `github` 등과 같이 필요한 항목을 수정하여 저장소에 반영

## 글쓰기
- `_posts` 폴더에서 새로운 파일을 작성
- 파일 이름은 다음과 같은 구조로 되어 있습니다.
        `yyyy-MM-dd-URL`
- 기사의 메타데이터를 수정
        - `title` 기사(글) 제목
        - `author` 작성자 이름
        - `tags` 글의 핵심 주제
- 글을 작성
        - 본문에서 가장 큰 '제목'은 `h2`
