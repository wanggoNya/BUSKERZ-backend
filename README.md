# Buskers 스프링 프로젝트 By 일조가일냈조 

  ✔️ 백엔드 작업 파일을 업로드하는 레파지토리 입니다. <br>
  ✔️ 6월 14일 기준, 스프링부트 프로젝트 3tier 중 Persistance를 맡아 진행 중입니다. <br>
  ✔️ 6월 16일 Persistance 파트를 종료했습니다. <br> 
  ✔️ 6월 16일부터 공연예정목록, 실시간공연 페이지의 백엔드 작업을 진행 중입니다. <br>
  
  <br>
  
*********
> ### <b> branch 설명 </b>
#### 

|✔️ 최종||
| :------ | ------ |
|||
|🌵 master|➿ 최종 backend 작업물이 올라와있는 브랜치입니다.|
|||
|✔️ per 그룹||
|🌵 per/Per_ver01||
|🌵 per/Per_ver02||
|🌵 per/Per_ver03_mapperInterfaceMethod||
|🌵 per/Per_ver04_mapper.xml||
|🌵 per/Per_ver05_test||
|🌵 per/persistance||
|||
|✔️ show 그룹||
|🌵 show/01_xml||
|🌵 show/02_daoService||
|🌵 show/03_controllerHtml||
|🌵 show/04_ajax||
|🌵 show/05_replyAjax||
|🌵 show/06_showIng||

*********
> ### <b> wanggoNya 진행 현황 정리 💭 </b>

| DAY      | 팀 보고      |  파트      | 진행 세부사항         |
| :------: | :------: | :------: |------------------------- |
| 6/14 (화) | ⭕ | <b>3-tier 설계(Persistance 파트)</b> | RDB 생성 <br> mapper Interface 메서드 작성 시작 |
| 6/15 (수) | ⭕ | <b>3-tier 설계(Persistance 파트)</b> | mapper Interface 메서드 작성 완료 <br> mapper.xml (쿼리문) 작성 시작 |
| 6/16 (목) | ⭕ | <b>3-tier 설계(Persistance 파트)</b><br><b>공연예정, 실시간공연</b> | mapper Interface 메서드 수정, mapper.xml 작성 <br> 공연 파트 sql문 작성, mapper 단위 테스트 진행 |
| 6/17 (금) | ⭕ | <b>공연예정, 실시간공연</b> | mapper.xml 동적쿼리 작성, mapper 단위 테스트 진행 |
| 6/18 (토) | ⭕ | <b>공연예정, 실시간공연</b> | mapper.xml 동적쿼리 작성, <br> mapper 단위 테스트 완료, <br> dao, service 작성 및 단위 테스트 진행 |
| 6/19 (일) | ⭕ | <b>공연예정, 실시간공연</b> | mapper.xml 동적쿼리 등 작성 완료, <br> mapper, dao, service 작성 및 단위 테스트 완료, 공연예정 목록 3-tier연결,  <br> 페이징 처리, simpledateformat으로 d-day 표시 완료 <br> 공연 등록 controller 진행 중 |
| 6/20 (월) | ⭕ | <b>공연예정, 실시간공연</b> | 공연 등록, 수정, 삭제 3-tier 연결 완료 <br> SimpleDateFormat을 이용한 공연 목록 D-day 순 정렬, 사용자에게 D-day 표시 <br> 공연 상세페이지 댓글 프론트 추가 완료, 도로명 주소 카카오맵에 표시 후 커스텀 오버레이 완료 <br>  |
| 6/21 (화) | ⭕ | <b>공연예정</b> | 공연 목록 전체/뮤지션/퍼포먼스 카테고리 변경 REST 처리 완료 <br> REST 이용한 상세페이지 댓글 등록, 페이징, 공연예정목록 페이징 처리 완료 |
| 6/22 (수) | ⭕ | <b>실시간공연</b> | 실시간공연 도로명 주소 좌표 배열에 넣은 후 지역별 분류, <br> 카카오맵에 핀 표시 완료, 핀 배열의 value를 이용해 <br> 상세페이지 연결 완료, REST를 이용해 지역별 목록 뽑기 완료 |
| 6/23 (목) | ⭕ | <b>공연예정, 실시간공연</b> | 실시간 공연 모달창 완료, 댓글 수정, 삭제 기능 완료, <br> 목록/댓글 페이징 오류 및 css 수리, 모달창 블러처리 삭제 |
| 6/24 (금) | ⭕ | <b>공연예정, 실시간공연</b> | db 및 폴더 파일 업로드 진행, <br> 드롭다운 이벤트에 파일 업로드 동시 구현되도록 작업 |
| 6/25 (토) | ⭕ | <b>공연예정, 실시간공연</b> | 폴더와 DB 연결해서 파일 업로드, 수정, 삭제, 파일 출력 구현 완료, <br> 댓글 취소버튼 버그 수리 |
| 6/26 (일) |  |  |  |
| 6/27 |  |  |  |
| 6/28 |  |  |  |
| 6/29 |  |  |  |
| 6/30 |  |  |  |
| 7/01 |  |  |  |
