### **무비메이트 🍿**

**서비스 설명:** 
무비메이트는 수많은 영화 콘텐츠 중 자신의 취향을 반영한 콘텐츠를 찾고싶어하는 유저들을 위한 웹페이지로, 2시간짜리 콘텐츠를 관람하기 위해 검색에 상당한 노력과 시간을 소비하는 사람들의 불편함을 해소하기 위해 제작되었습니다.

**제작 목적:** 
무비메이트는 영화를 즐기는 데 필요한 다양한 정보들을 한눈에 제공하여 사용자들이 효율적으로 원하는 영화를 찾을 수 있도록 돕습니다. 제작 기간은 4월 10일부터 5월 15일까지로 진행되었으며, 다양한 기능을 구현하여 사용자들에게 최적의 서비스를 제공하고자 했습니다.

**맡은 역할:**
1. 메인 화면의 임의의 기준으로 인플루언서를 뽑아 추천한 영화 데이터 가져오기 🎬
2. 메인 화면의 박스오피스 기준 영화 데이터 가져오기 🎥
3. 메인 화면의 명작 영화 데이터 가져오기 🌟
4. 메인 화면의 임의의 기준으로 배우를 뽑아 배우가 출연한 영화 데이터 가져오기 🌟
5. 마이 페이지 기능 구현 🔄
6. 로그인 네이버 Open API 구현 🔐
7. 더 보기 영화의 모든 정보 출력 📜
8. 로그인 화면의 자체 회원 기능 구현 🔐
9. 풋터(footer)에 개발자 정보 담은 링크 배열 출력 📎

![무비메이트 이미지](https://github.com/TaskerJang/movie_mate_project/assets/124780552/c704cfe9-33c1-47de-a2f1-a0fe9df09e23)

![무비메이트 이미지](https://github.com/JJangcoding/movie_mate_project/assets/124780552/d27e47a7-44d5-4838-a23d-29d716e27e6a)

![무비메이트 이미지](https://github.com/JJangcoding/movie_mate_project/assets/124780552/c1711cf0-eaed-409f-a4c8-097e5d48e327)

![무비메이트 이미지](https://github.com/JJangcoding/movie_mate_project/assets/124780552/bbe1e575-16dd-4716-9983-201c34e63fe1)

#### **주요 기능**

1. **메인메뉴 - 영화목록**
   - **박스오피스 순위:** 특정 시점 기준 최신작 목록 출력
   - **왓챠 Top10 영화:** 평균 별점이 높은 최신작 목록 출력
   - **무비메이트 명작 영화:** 특정 시점 이전의 평균 별점이 높은 작품 목록 출력
   - **무비메이트 화제의 감독:** 해당 감독의 작품 목록 출력
   - **무비메이트 이주의 배우:** 해당 배우의 작품 목록 출력
   - **평균 별점이 높은 영화:** 평균 별점이 높은 작품 목록 출력
   - **무비메이트 이주의 추천 장르:** 해당 장르의 작품 목록 출력
   - **이주의 인플루언서 추천 영화:** 평균 별점이 높은 추천 작품 목록 출력

2. **선택한 영화 화면**
   - **코멘트 미리보기, 좋아요, 댓글수, 삭제하기:** 해당 영화 정보 표시
   - **댓글 작성:** 내가 작성한 댓글이 해당 영화에 표시
   - **별점, 보고싶어요:** 부여한 별점과 보고싶어요 표시
   - **제작진 정보:** 해당 영화에 부합하는 제작진 정보 표시
   - **기본 정보 더보기:** 원제, 개봉년도, 국가, 장르, 상영시간, 연령 등급, 내용 표시
   - **비슷한 작품:** 해당 영화와 비슷한 장르의 작품 목록 출력
   - **왓챠 광고 링크:** 왓챠 이벤트 광고를 링크에 연결

3. **코멘트 목록 화면**
   - **코멘트 내용, 좋아요, 댓글수:** 내가 작성한 코멘트 정보 표시

4. **코멘트 자세히 보기**
   - **댓글 삭제:** 내가 작성한 댓글을 작성자만 삭제 가능
   - **대댓글 작성:** 댓글에 대한 댓글 작성 기능
   - **대댓글 수정, 삭제:** 대댓글 수정, 삭제 기능
   - **대댓글 좋아요:** 대댓글에 대한 좋아요 버튼 활성화
   - **댓글을 작성한 유저 정보:** 댓글 작성자의 이름 표시
   - **댓글을 작성한 영화 정보:** 댓글에 해당하는 영화 정보 표시
   - **댓글 작성자의 별점:** 댓글 작성자의 별점 표시
   - **악성 댓글 감지 클린봇:** 댓글에 비속어가 포함되어 있을 시 클린봇이 작동하여 필터링

5. **로그인**
   - **카카오 로그인:** 카카오 로그인 API를 이용하여 계정 연동
   - **네이버 로그인:** 네이버 로그인 API를 이용하여 계정 연동

6. **회원가입**
   - **이름 중복 체크:** 중복된 이름이 가입되지 않도록 중복성 체크
   - **유효성 체크:** 이름, 이메일, 비밀번호 유효성 체크 조건에 맞도록 검사
   - **네이버 및 카카오 회원가입:** 네이버 & 카카오의 프로필 이미지, 이름, 이메일 가져오기

7. **마이페이지**
   - **정보 수정:** 이미지 변경, 이름 변경, 비밀번호 변경, 뒤로가기, 변경된 이름 & 비밀번호 저장
   - **취향 분석:** 평가한 영화들의 평균 별점과 통계 시각적으로 표현
   - **평가한 영화:** 평가한 영화 및 보고싶어요를 누른 영화들 표시

8. **검색**
   - **유저 검색:** 입력한 검색어에 부합하는 유저 검색
   - **배우, 영화 검색:** 입력한 검색어에 부합하는 배우 및 영화 검색

9. **다크모드**
   - **어두운 스킨 적용:** CSS를 변경하여 어두운 스킨 적용

10. **풋터**
   - **각종 링크 (팝업):** 풋터에 링크 연결하여 정보 창 띄우기
   - **평가한 영화수:** DB에 연동하여 평가 및 코멘트 개수 표시

