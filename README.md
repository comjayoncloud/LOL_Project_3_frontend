# LOL_Project_3_Frontend

1. 기능
  - 리그오브레전드의 유저 한명의 최근 게임 전적 10개를 아이디를 통해 검색할 수 있다.
  - 한국서버, 미국서버 유저를 검색 할 수 있다.
  
  
2. 사용방법 (순서대로)
  - https://master.d1h809df4o8t0i.amplifyapp.com/jw.gg 에 접속
  - Korea 혹은 North america 서버를 선택, 아이디를 입력한후 엔터 혹은 체크표시를 누른다. 
    ex) korea - 빵뒤를흔드록바 , north america - cake
  - 검색결과 창에서 상단에 있는 Op.gg 아이콘을 누르면 초기화면으로 돌아간다.
  - 검색결과 창에서 전적갱신을 누르면 리프레쉬 할 수 있다.
  
  
3. 느낀점
  - 프론트엔드는 정말 다양하게 알야할 것 들이 많은 것 같습니다. React bootstrap을 사용해서 dropdown , spinner를 사용했습니다. react bootstrap에 있는 단어들은 일반적으로 사용하는 
    단어들이기 때문에 하나하나 알아야 할 것 같습니다. 또한 라이브러리들 또한 계속해서 나오기 때문에 발맞춰 트렌드를 아는 것도 중요하다고 느꼈습니다.
    리액트의 핵심인 상태관리 . 리액트가 나오게된 결정적인 이유인 양방향성 -> 단방향성, flux 구조, react-redux, react-redux toolkit, react query 다양한 라이브러리들이 나오게된 
    배경도 하나하나 이해가 되기 시작했습니다. 코드의 간소화 및 가독성을 높이기 위해 react redux를 사용하려 했으나, 더 쉽고 상태관리가 편한 react query를 다음 ver4에서 사용하려 합니     다.
    새로 구현한 것 중 하나인 op.gg의 게시판에서 인기 많은 글 들을 간단하게 프리뷰 해주는 컴포넌트를 만들 때, op.gg에서도 분명히 api를 통해 데이터를 가져왔을 거라 생각을 했습니다.
    처음엔 개발자도구에서 주로 elements와 console를 썼던 나는 데이터의 출처를 찾아보고 싶었고 elements에서 가져온 링크의 규칙을 찾아보았습니다. 하지만 찾을수가 없었고 이를 해결하기     위해 network를 활용 했습니다. 처음으로 network를 활용해보았고 거기서 데이터의 출처를 찾을 수 있었습니다. 개발자도구가 중요하다는 것을 느꼈고 데이터 출처를 확인한 순간 너무 재미있     었습니다.
    다음 ver4에선 코드를 간소화하며 가독성을 높이는 식으로 리팩토링을 하고자 합니다. 또한 class명, 변수,함수명을 정하는게 아직 너무 변변찮지만, 유명한 몇개 사이트들을 분석하며 그들은 
    어떻게 쓰고 있는지 파악하며 네이밍 스킬을 향상 시키고 싶습니다
    
    
