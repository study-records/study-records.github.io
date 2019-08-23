# study-records.github.io

### 목적
> “아무것도 남기지 않으면, 아무것도 남지 않는다.”

라는 전제 하에 기록할 만한 가치가 있는 내용을 정리해 두는 기술 블로그입니다.

### 설치 방법
https://help.github.com/en/articles/setting-up-your-github-pages-site-locally-with-jekyll 를 기본적으로 참고하시면 됩니다. (추가예정)

### 구조
* 현재 적용된 파일들에 대한 서술만 있습니다. 자세한 설명은 https://mmistakes.github.io/minimal-mistakes/docs/structure/ 참고하시면 됩니다.

.  
├ Gemfile &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# 다양한 Gem을 등록하는 파일. 루비에서 지원하는 패키지 시스템으로 필요한 프로그램을 넣습니다.  
├ _config.yml &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# 환경 설정 파일입니다.  
├ _data/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;# 커스텀 테마를 설정할 수 있는 디렉토리  
│&nbsp;&nbsp;&nbsp;&nbsp;└ navigation.yml   # 메인 네비게이션 링크들을 저장  
├ _posts/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # 카테고리 소개, 규칙, About 등의 문서들이 작성되는 공간입니다.
└ _(category-name)/ &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; # 카테고리에 해당하는 문서들을 작성해 두는 공간입니다.     
### 문서 작성 방법
1. category-name에 속하는 문서들은 _category-name 디렉토리에 저장합니다.
2. 제목은 "년-월-일-제목과-공백-작성자닉네임.md" 로 작성합니다.
3. 본문에 title과 author을 적습니다.
4. markdown 형식의 문서를 작성합니다.

(추가 예정)
