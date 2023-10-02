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

## 글쓰기 보충

GitHub Pages에서 이미지와 표를 사용할 경우 캡션을 표시할 수 있는 방법이 없을 수도 있으니, 이미지와 표는 본문에서 '잘' 설명해야 됩니다.

### 이미지 추가
- 정적 파일, 위치가 중요
        - https://customconnect.github.io/images/20231002/01.jpg
        - {{site.baseurl}}/images/20231002/01.jpg

### 표 추가
- `https://www.tablesgenerator.com/markdown_tables`
- 복잡한 표는 만들 수 없음
- 웹에서 표를 제시할 때는 간략하게 제시하시고, 복잡한 형태의 표(자세한) 것들은 가능하면 이미지로 제공
- 원본 기사(PDF, 출판물)이 존재한다면 해당 표를 설명하는 과정에서 원본 기사를 Ref를 제시하거나, PDF의 링크를 제공

## 사이트 기능 추가

### 댓글
- `https://disqus.com/` 가입
- `...install on my site...` 선택 후 
- 사이트 개설(shortname) 설정
- `_config.yml`에 붙여넣기(shortname)
- disqus > admin > advenced > Trusted Domain 설정
        - [id].github.io

### GA4
- `https://marketingplatform.google.com/intl/ko/about/analytics/`
- GA4 관련 스트림ID를 발급 후
- `_config.yml`에 설정