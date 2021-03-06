# 자취는 템빨
자취생들이 모여 중고거래를 하거나, 자취 꿀팁을 공유하고 지역 친구를 사귈 수 있는 종합 사이트입니다.

# [개발일정]
2021.09.15 ~ 10.01 프로젝트 기획(요구사항 정의서, 프로세스맵, 기획발표)

2021.10.02 ~ 10.13 UI 설계(스토리보드)

2021.10.14 ~ 10.30 DB 설계 & UI 구현 (ERD, 테이블 정의서)
 
2021.11.01 ~ 11.16 기능 구현 개발

2021.11.17 프로젝트 발표

# [구현기능]
사용자

- 회원 : 로그인,회원가입,아이디/비밀번호 찾기, 회원 탈퇴, 회원정보수정, 좋아요, 댓글)

- 메인 페이지 : 베스트 상품 모아보기, 베스트 글 모아 보기, 광고베너

- 정보공유 게시판(꿀팁게시판) : 게시물 등록, 좋아요, 신고, 댓글, 카테고리별 조회, url 내보내기, 해당 게시판 베스트글 모아보기

- 중고거래 게시판(꿀템게시판) : 게시물 등록, 찜, 신고, 댓글, 연관상품 모아보기, 장터아이템 카테고리 별/최신순/ 가격순 조회)

- 커뮤니티 게시판(꿀친게시판) : 게시물 등록, 좋아요, 신고, 댓글, 카테고리별 조회, 지역 카테고리 셀렉트

- 마이 페이지:프로필, 찜 상품 내역, 좋아요한 상품 내역, 회원 정보 수정/ 탈퇴

- 쪽지 : 수신/송신 쪽지 조회, 작성, 수신 여부 확인, 신고, 쪽지(제목, 내용) 검색
 
- 헤더 : 검색/ 푸터: 광고문의
 
관리자

- 회원 관리(정보 조회, 강퇴 여부)

- 신고 내역 (쪽지, 댓글, 게시물) 조회

- 광고 문의 조회
 
# [설계의 주안점]
- 현재 상용되는 사이트중 자취생을 위한 '자취 전용 사이트'가 존재하지 않아 자취생이 필요한 정보만 있는 사이트를 구현하면 비즈니스적 가치가 있다고 생각해 구현하였다.

- 나와 비슷한 관심사를 갖고있는 자취생 친구들과 친목을 도모할 수있고, 중고거래와 소소한 팁들을 얻을수 있는 다향한 기능이 있는 사이트이다.

# [사용 기술 및 개발환경]
HTML , CSS , JAVASCRIPT , JQUERY , Oracle , GITHub , JAVA , Tomcat , Servlet , Bootstrap , Smtp , JSTL , Json , summermote 

# [역할 분담]
- 김정훈 : 

          [회원 관련 기능]
          
               : 회원가입, 로그인, 아이디 찾기, 임시비밀번호 발송
               
          [메인 페이지]
          
               : 전체 게시글 조회, 전체 게시글 검색, 메인화면 인기 게시글 목록
               
- 문예찬 : 
          [장터(꿀템)게시판]
          
               : 게시글 작성/수정/삭제, 카테고리 별/가격순/최신순 게시글 조회, 댓글 작성/삭제, 연관상품조회, 동적 슬라이드 뷰, 페이징 처리
          [쪽지]
          
               : 쪽지 작성/삭제, 송/수신 쪽지 조회, 쪽지 수신여부 확인, 쪽지(제목, 내용, 작성자) 검색, 페이징 처리
               
          [슬라이드 광고배너](5초마다 슬라이드 형식으로 광고 전환 또는 좌우 화살표 버튼을 통해 광고를 전환할 수 있는 기능)
          
- 이예림 : 
 
          [커뮤니티(꿀친)게시판]
          
               : 글작성/수정/삭제, 댓글.대댓글 작성/삭제, 카테고리별 조회, 페이징 처리, 사진 등록 개수에 따라 변화하는 동적 슬라이드 뷰
               
- 박진희 : 

           [정보공유(꿀팁) 게시판]
           
               : 사진업로드, 글작성/수정/삭제, 댓글 작성, 카테고리별 조회, 해당 게시판 인기 게시글 목록, url내보내기, 페이징 처리
               
- 추현정 :

          [관리자 게시판]
          
               : 광고문의조회,신고내역조회.회원정보검색 및 회원관리
               
          [마이 페이지]
          
               : 간단 프로필, 프로필수정,찜한 상품 목록, 좋아요한 게시물 목록
               
          [광고문의, 회원신고]


