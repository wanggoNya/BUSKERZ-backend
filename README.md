# Buskers 스프링 프로젝트 By 일조가일냈조 

  ✔️ 백엔드 작업 파일을 업로드하는 레파지토리 입니다. <br>
  ✔️ 6월 14일 기준, 스프링부트 프로젝트 3tier 중 Persistance를 맡아 진행 중입니다. <br>
  ✔️ 6월 16일 Persistance 파트를 종료했습니다. <br> 
  ✔️ 6월 16일부터 공연예정목록, 실시간공연 페이지의 백엔드 작업을 진행 중입니다. <br>
  
  <br>
  
*********
> ### <b> branch 설명 </b>
#### 

|✔️ 최종|    |
| :------ | ------ |
|    |    |
|🌵 main|➿ 최종 backend 작업물이 올라와있는 브랜치입니다.|
|    |    |
|✔️ per 그룹| Persistance 설계 |
|🌵 per/persistance <br> 🌵 per/Per_ver01 <br> 🌵 per/Per_ver02 <br> | VO 파일을 업로드한 브랜치입니다. <br> 관련 내용을 버전별로 관리한 브랜치입니다. |
|🌵 per/Per_ver03_mapperInterfaceMethod | mapper Interface 설계 파일을 업로드한 브랜치입니다. |
|🌵 per/Per_ver04_mapper.xml| mapper.xml (sql 쿼리문)을 작성하여 업로드한 브랜치입니다. |
|🌵 per/Per_ver05_test| 작업하며 진행한 테스트 파일들을 업로드한 브랜치입니다. |
|||
|✔️ show 그룹| 공연예정, 실시간공연 페이지를 구현하는 브랜치입니다. |
|🌵 show/01_xml| 공연 테이블에 대한 쿼리문을 작성한 xml 파일을 업로드한 브랜치입니다. |
|🌵 show/02_daoService| dao와 service를 작성하고 테스트한 파일을 업로드한 브랜치입니다. |
|🌵 show/03_controllerHtml| 컨트롤러, html 연결 작업 파일을 업로드한 브랜치입니다. |
|🌵 show/04_ajax| REST 방식을 이용한 ajax 코드를 업로드한 브랜치입니다. |
|🌵 show/05_replyAjax| REST 방식을 이용하여 댓글창 구현한 코드를 업도르한 브랜치입니다. |
|🌵 show/06_showIng| 실시간 공연 페이지를 구현한 브랜치입니다. |
|||
|✔️ login 그룹| 로그인, 회원가입 기능을 구현하는 브랜치입니다. |
|✔️ session 그룹| 웹사이트 세션 관리 기능을 구현하는 브랜치입니다. |

*********
> ### <b> wanggoNya 진행 현황 정리 💭 </b>

| DAY      | 팀 보고         | 파트         | 진행 세부사항         |
| :------: | :------: | :------: |------------------------- |
| 6/14 (화) | ⭕ | <b>3-tier 설계 <br> (Persistance 파트)</b> | RDB 생성 <br> mapper Interface 메서드 작성 시작 |
| 6/15 (수) | ⭕ | <b>3-tier 설계 <br> (Persistance 파트)</b> | mapper Interface 메서드 작성 완료 <br> mapper.xml (쿼리문) 작성 시작 |
| 6/16 (목) | ⭕ | <b>3-tier 설계 <br> (Persistance 파트)</b><br><b>공연예정,  <br> 실시간공연</b> | mapper Interface 메서드 수정, mapper.xml 작성 <br> 공연 파트 sql문 작성, mapper 단위 테스트 진행 |
| 6/17 (금) | ⭕ | <b>공연예정, <br>  실시간공연</b> | mapper.xml 동적쿼리 작성, mapper 단위 테스트 진행 |
| 6/18 (토) | ⭕ | <b>공연예정,  <br> 실시간공연</b> | mapper.xml 동적쿼리 작성, <br> mapper 단위 테스트 완료, <br> dao, service 작성 및 단위 테스트 진행 |
| 6/19 (일) | ⭕ | <b>공연예정, <br>  실시간공연</b> | mapper.xml 동적쿼리 등 작성 완료, <br> mapper, dao, service 작성 및 단위 테스트 완료, 공연예정 목록 3-tier연결,  <br> 페이징 처리, simpledateformat으로 d-day 표시 완료 <br> 공연 등록 controller 진행 중 |
| 6/20 (월) | ⭕ | <b>공연예정, <br>  실시간공연</b> | 공연 등록, 수정, 삭제 3-tier 연결 완료 <br> SimpleDateFormat을 이용한 공연 목록 D-day 순 정렬, 사용자에게 D-day 표시 <br> 공연 상세페이지 댓글 프론트 추가 완료, 도로명 주소 카카오맵에 표시 후 커스텀 오버레이 완료 <br>  |
| 6/21 (화) | ⭕ | <b>공연예정</b> | 공연 목록 전체/뮤지션/퍼포먼스 카테고리 변경 REST 처리 완료 <br> REST 이용한 상세페이지 댓글 등록, 페이징, 공연예정목록 페이징 처리 완료 |
| 6/22 (수) | ⭕ | <b>실시간공연</b> | 실시간공연 도로명 주소 좌표 배열에 넣은 후 지역별 분류, <br> 카카오맵에 핀 표시 완료, 핀 배열의 value를 이용해 <br> 상세페이지 연결 완료, REST를 이용해 지역별 목록 뽑기 완료 |
| 6/23 (목) | ⭕ | <b>공연예정, <br>  실시간공연</b> | 실시간 공연 모달창 완료, 댓글 수정, 삭제 기능 완료, <br> 목록/댓글 페이징 오류 및 css 수리, 모달창 블러처리 삭제 |
| 6/24 (금) | ⭕ | <b>공연예정, <br>  실시간공연</b> | db 및 폴더 파일 업로드 진행, <br> 드롭다운 이벤트에 파일 업로드 동시 구현되도록 작업 |
| 6/25 (토) | ⭕ | <b>공연예정, <br>  실시간공연</b> | 폴더와 DB 연결해서 파일 업로드, 수정, 삭제, 파일 출력 구현 완료, <br> 댓글 취소버튼 버그 수리 |
| 6/26 (일) | ⭕ | <b>공연예정, <br>  실시간공연</b> | 실시간공연 링크걸기, 공연 댓글 순위 작업 진행, <br>  신인 아티스트 서버 연결 진행 |
| 6/27 (월) | ⭕ | <b>로그인, <br>  회원가입</b> | 일반 로그인, 카카오톡 로그인, 세션 생성  <br> 아이디, 비밀번호 찾기 진행, 회원가입 진행 |
| 6/28 (화) | ⭕ | <b>공연예정, <br>  실시간공연</b> <br> <b>로그인, <br>  회원가입</b> | 일반회원, 아티스트, 관리자 세션 설정,  <br> 로그인, 회원가입, 아이디/비번찾기 완료 |
| 6/29 (수) | ⭕ | 마무리 | 공연예정, 실시간공연, 로그인, 회원가입 마무리 작업 |
| 6/30 (목) | ⭕ | 마무리 | 프로젝트 마무리 작업 및 더미 데이터 작업 완료 |
| 7/01 (금) | ⭕ | 발표 | 발표, 그리고 프로젝트 종료 😊 |
