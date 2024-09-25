# Web Crawling
## 회원의 Coupang 주문내역을 크롤링하는 python code   


  * selenium 라이브러리를 이용해 Chrome 브라우저로 쿠팡 사이트에 로그인한다.

  * 날짜, 상품 이름, 수량, 가격 등 주문 관련 정보들을 크롤링한 후 dictionary 형태로 저장한다.

  * DB 구축에는 MongoDB 사용을 위해 pymongo 라이브러리를 사용한다.

  * 개인 MongoDB 를 사용했다. 이 때 필요한 uri 는 MongoDB Atlas 접속 후 Cluster - Connect - Connecting with MongoDB Driver 에서 확인할 수 있는 connection string 을 이용해 MongoDB 에 접속한다.
