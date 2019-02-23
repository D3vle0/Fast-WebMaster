# WebMaster
모바일 환경에서 인터넷 브라우저를 이용해 인터넷에 접속하면, 내가 가고자 하는 웹사이트의 링크를 입력하고 해당 페이지에서 다시 무언가를 검색하기 위해 자판을 두드려야한다. (예시로는 크롬-네이버검색)  
이런 번거로움을 해결하기 위해 내가 자주가는 검색엔진과 웹사이트를 단 한 번의 클릭으로 바로 갈 수 있는 페이지를 만들게 되었다.  
네이버와 구글 버튼은 검색어를 입력하면 해당 링크로 바로 갈 수 있다.  
네이버의 경우
```
https://search.naver.com/search.naver?sm=top_hty&fbm=0&ie=utf8&query=
```
뒤에 검색어 url query 가 붙는다. 구글은
```
https://www.google.com/search?q=
```
이런 문자열로 표현 가능하다.  
입력창에 검색어를 입력하면 위의 링크 뒤에 검색어 문자열을 합친 링크로 리디렉션 되게 JS 로 간단하게 코딩해보았다.
