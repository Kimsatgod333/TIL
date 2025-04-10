# TIL
## 작업폴더 설명
* `html_basic/` : html기초 연습파일 모음
* `task/`: 과제제출 폴더, 파일 모음(폴더명은 날짜별로 구성)
* `README.md` : 배운 내용 기록, 어려운 점 및 막힌점 자유롭게 기록
### 2025-04-04 | HTML 3일차 문서와 레이아웃
* `h1~h6`, `p`, `br`, `strong`, `em`, `del`, `s` `sup`, `sub`
* 터미널에서 깃헙과 연결하는과정 및, 업로드 과정 반복연습 필요.
* &lt;, &gt; 잘 기억해둘것.
* 로고는 항상 h1인점 기억할것.
* &copy;로 ⓒ 를 만들수 있다.<< 중요
### 2025-04-07
* 보통 div는 블록태그에 쓰이나, 경우에 따라 인라인 태그를 묶을때에도 사용하는 경우도 있다. 
* span의 경우 span자체가 인라인이기 때문에 블록태그와 형제관계로 되는 경우에는 사용할수 없다.
* `div`, `span`
* 웹/앱 레이아웃 방향과 의미에 따라 2개 이상의 요소를 묶어주는 레이아웃 요소
* `div`는 생성 시 반드시 그룹을 구분할 수 있는 이름을 설정해야함. `span`은 선택
* 이름은 .class로 주는 이름과, #Id로 주는 이름이 있다. <<중요
* `.Class`: 반복유형 분류 시 사용, 반복지정가능 <<중요
* `#Id`: 전체 페이지 중 단 하나의 요소에만 지정 시 사용 <<중요
* Class, Id는 태그 관계없이 모든 태그에 적용할수 있음. <<중요
* 앞에 . , #이 붙은이유는 CSS에서 해당 태그를 사용할때 필요한 것으로, html에서는 사용하지 않으나, 중요함.
* 이름 작성시 주의 사항:반드시 용도에 맞는 의미가 있는 영단어를 사용해야함.(이름이 길다고 해서 이상하지 않음, 오히려 제대로된 의미를 가진 단어여야 좋음)
### HTML 구조 공부 순서
1. 클론 코딩 & 클론 디자인할 사이트 정하기
2. 피그마에서 와이어프레임 만들기(레이어, 폴더 이름 주의)
3. 피그잼에 일부 화면 넘겨서 태그 계획하기
4. 계획한 태그를 가족관계에 맞게 트리구조 만들기
5. Vs code에서 실제 HTML 작성하기(트리구조 순서에 맞게 바깥쪽 > 안쪽순서로)
### 다른 환경에서 git 이어서 작업하기
1. 새폴더 연결
2. `git clone 주소 붙여넣기`
3. `cd 파일명`으로 파일 연결하기
4. 수정할 내용 작업하기
5. 수정 완료 하면 저장하기
6. 저장후 `git status`로 저장한 내용이 제대로 저장되었는지 확인
7. `git add .`으로 스테이지로 이동
8. `git commit -m ''`으로 메모진행
9. `git push origin main`으로 깃허브에 업로드 진행
10. 깃허브에 접속하여 정상적으로 업로드 진행 되었는지 
11. 다시 원래 환경으로 돌아와서 작업 시작시, `git pull origin main`으로 기존에 작업 받은 내용을 내려받아 작업 진행