# Shoppingmall Site

'index' => 잘 나가는 상품 10개 소개


'/about' => 회사 소개


'/product' => 상품 목록


'/product/1'=> 상품 목록 상세 게시물


'/contact' => 오시는 길


'/qna' => Q&A 목록


'/qna/1'=> Q&A 상세 게시물


'/notice' => 자유게시판, 1:1게시판 선택 페이지


'/notice/free' => 자유게시판 목록


'/notice/free/1' => 자유게시판 상세 게시물


'/notice/onenone' => 1:1 상담 안내


'/notice/onenone/1'  => 1:1 상담 상세 게시물

---
### 3.2 프로젝트 URL 구조
|app: accounts |views 함수 이름|html 파일이름   |
|:------------|:------------|:------------|
|'signup/'     |signup        |signup.html   |
|'login/'      |login         |login.html    |
|'logout/'     |logout        |N/A|
|'profile/'    |profile       |profile.html  |
|'change_password/'|change_password|change_password.html|
|'profile_update/'|profile_update|profile_update.html|

|app: main |views 함수 이름|html 파일이름|
|:--------|:------------|:---------|
|'/'       |index         |index.html|
|'about/'  |about         |about.html|
|'contact/'  |contact         |contact.html|

|app: product |views 함수 이름|html 파일이름|
|:--------|:------------|:---------|
|'<int:pk>/'  |product_detail         |product_detail.html|
|'search/'|product_search|product_search.html|
|404|404(없는 페이지)|404.html|
|403|403(권한 없는 페이지)|403.html|



