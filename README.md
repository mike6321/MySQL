# MySQL
MySQL 스터디를 위한 repository 입니다.

# MySQL 아키텍쳐

* [MySQL 엔진 아키텍쳐](https://jwdeveloper.tistory.com/308)
* [InnoDB 스토리지 엔진 아키텍쳐](https://jwdeveloper.notion.site/InnoDB-6499151f9ae148e180f1dd57ae6e0d00)
  * [InnoDB 버퍼풀](https://jwdeveloper.notion.site/InnoDB-53642ddac15b4a26a63aba9e46e7104d)
    * [버퍼 풀과 리두로그](https://jwdeveloper.notion.site/bb364144032241e89d9b0c5ea0fd59ef)
    * [버퍼 풀 플러시](https://jwdeveloper.notion.site/45a299bbc3e247758f5c11da5e19fb98)
    * [버퍼 풀 상태 백업 및 복구](https://jwdeveloper.notion.site/4213a86203fa4ff8893988d3845a7331)
    * [Double Write Buffer](https://jwdeveloper.notion.site/Double-Write-Buffer-84b8deb06487464fb41f444ad3439baf)
  * [언두로그](https://jwdeveloper.notion.site/b12ba0ccdd4344fcb589a8a1d1d69728)
  * [언두 테이블스페이스 관리](https://jwdeveloper.notion.site/1546e76a012446f584e38eeb82f60ea6)
  * [체인지 버퍼](https://jwdeveloper.notion.site/b017617141ca4efbb566a99619bc5118)
  * [리두 로그 및 로그 버퍼](https://jwdeveloper.notion.site/63b26c267c22480f8f1af20b6b84f63c)
  * [어댑티브 해시 인덱스](https://jwdeveloper.notion.site/dee624e65cc54bf1995858d66a547245)
* [MyISAM 스토리지 엔진 아키텍쳐](https://jwdeveloper.notion.site/MyISAM-013b7ab7b7cc435b81374b423340ca81)

# 트랜잭션과 잠금

* [트랜잭션](https://jwdeveloper.notion.site/dcbea2dea75b4fd6a2dfd613e3680496)
  * [MySQL 에서의 트랜잭션](https://jwdeveloper.notion.site/MySQL-c8f7aa1be431438ca3efd7752924bede)
  * [주의사항](https://jwdeveloper.notion.site/15aae72963ba498bab62ac3f1e86c6c4)
* [MySQL 엔진의 잠금](https://jwdeveloper.notion.site/MySQL-505725258efc4955a40e26f8ceb631cb)
  * [MySQL 엔진의 잠금](https://jwdeveloper.notion.site/MySQL-f62ce5051a874692994db70e52337754)
    * [글로벌 락 & 백업 락](https://jwdeveloper.notion.site/5cf4fbce5fdf44aea3876dc46d1b0aef)
    * [테이블 락](https://jwdeveloper.notion.site/f5090941a91f400692acfb7b7c2909da)
    * [네임드 락](https://jwdeveloper.notion.site/d24b83de11ab49999d065c4cc7f598d4)
    * [메타데이터 락](https://jwdeveloper.notion.site/9a3ec3052b264fe9bddce14123d900d7)
  * [InnoDB 스토리지 엔진 잠금](https://jwdeveloper.notion.site/InnoDB-11099321a2d94218876d2afe39dcef88)
  * [인덱스와 잠금](https://jwdeveloper.notion.site/7fe5ece8c85648b3af63315d5a623682)
  * [레코드 수준의 잠금 확인 및 해제](https://jwdeveloper.notion.site/150b037bb88d43fb99f304105134707f)

# 인덱스

* [디스크 읽기 방식](https://jwdeveloper.notion.site/dc7f2a8dc9eb4921a0781cd4fa674311)
  * [하드 디스크 드라이브(HDD)와 솔리드 스테이트 드라이브(SSD)](https://jwdeveloper.notion.site/HDD-SSD-2da319d4bbdd4c9ca2bae3927ffc20a0)
  * [랜덤 I/O 와 순차 I/O](https://jwdeveloper.notion.site/I-O-I-O-353c103270074dd3b9b721a416ab7a4a)
* [인덱스란?](https://jwdeveloper.notion.site/5bf6dd2a44184373a64098d5435a8d2e)
* [B-Tree 인덱스](https://jwdeveloper.notion.site/B-Tree-25a68f57346345c9aa14b1d9064c8ac5)
  * [B-Tree 인덱스 - 구조 및 특성](https://jwdeveloper.notion.site/B-Tree-dbf53c127ed946f79bd292ee77eabd8b)
  * [B-Tree 인덱스 키 추가 및 삭제](https://jwdeveloper.notion.site/B-Tree-74848804e6f84cbb85a27f447039957c)
  * [B-Tree 인덱스 사용에 영향을 미치는 요소](https://jwdeveloper.notion.site/B-Tree-629fcfff724947f9bfe8682ac6ea07be)
  * [B-Tree 인덱스 - 인덱스를 통한 데이터 읽기](https://jwdeveloper.notion.site/B-Tree-4fdf31277a704143aa424136f7b40126)
  * [다중 컬럼 인덱스](https://jwdeveloper.notion.site/84fd7e6f3b5e4e9f8171a4039927b4fe)
  * [B-Tree 인덱스 정렬 및 스캔 방향](https://jwdeveloper.notion.site/B-Tree-0aec7bd7c32f46b1aa5cdb2f6093f0ab)
  * [B-Tree 인덱스 - 가용성과 효율성](https://jwdeveloper.notion.site/B-Tree-6a5fbde198924095bae0233a4c0cc2a0)
* [함수 기반 인덱스](https://jwdeveloper.notion.site/77a8ae8295364789830a80448f236a88)
* [멀티 밸류 인덱스](https://jwdeveloper.notion.site/ef5142ec47ac45d9b0c1375c33a48d49)
* [클러스터링 인덱스](https://jwdeveloper.notion.site/ecea385e40944cfaae20cefdca5da187)
* [유니크 인덱스](https://jwdeveloper.notion.site/0bdb9b5cf8d44ec4aa4f96ebafad5a67)
* [외래키](https://jwdeveloper.notion.site/6805e2c6d3de48439ca3c9b0d9f3b023)

# 쿼리 작성 및 최적화

* [SELECT](https://jwdeveloper.notion.site/SELECT-e6039ed47580474ca65609bae45c12c5)
  * [SELECT 절의 처리 순서](https://jwdeveloper.notion.site/SELECT-810897e3266d4ed8954fe3f5853d2c3a)
  * [WHERE 절과 GROUP BY 절, ORDER BY 절의 인덱스 사용](https://jwdeveloper.notion.site/WHERE-GROUP-BY-ORDER-BY-576cc6a3e508444f953cb824e740b410)
    * [인덱스를 사용하기 위한 기본 규칙](https://jwdeveloper.notion.site/f90f44386f1a491eb65d57eff4924e71)
    * [WHERE 절의 인덱스 사용](https://jwdeveloper.notion.site/WHERE-8710936989034d0fb72749eb90fdf8ac)
    * [GROUP BY 절의 인덱스 사용](https://jwdeveloper.notion.site/GROUP-BY-0fa8f256a65d4d009e30a5a6d1bbe1e8)
    * [ORDER BY 절의 인덱스 사용](https://jwdeveloper.notion.site/ORDER-BY-ee7e2692766940629b0c0c0c7b2dc3e7)
    * [WHERE 조건과 ORDER BY(GROUP BY) 절의 인덱스 사용](https://jwdeveloper.notion.site/WHERE-ORDER-BY-GROUP-BY-132b711c215445fc99a8b37400ac2be5)
    * [GROUP BY 절과 ORDER BY 절의 인덱스 사용](https://jwdeveloper.notion.site/GROUP-BY-ORDER-BY-c3e0a98ae91d4a64b7924c6f0b856d8e)
    * [WHERE 조건과 ORDER BY 절, GROUP BY 절의 인덱스 사용](https://jwdeveloper.notion.site/WHERE-ORDER-BY-GROUP-BY-7eda995c2ba64592bb6729ed82e640c4)
  * [WHERE 절의 비교 조건 사용 시 주의사항](https://jwdeveloper.notion.site/WHERE-e41c41c563c846aaa2428af09b4ddb89)
    * [NULL 비교](https://jwdeveloper.notion.site/NULL-be774cf8276d449d8ccdbbad47353e19)
    * [문자열이나 숫자 비교](https://jwdeveloper.notion.site/e6e351afde024982ba4c986bb6bbe8d0)
    * [날짜 비교](https://jwdeveloper.notion.site/140df3b9805c4a988566d1e365bd443c)
    * [Short-Circuit Evaluation](https://jwdeveloper.notion.site/Short-Circuit-Evaluation-9c4613801cf24b8dbb04130101089c74)
  * [LIMIT](https://jwdeveloper.notion.site/LIMIT-84ac13e124d740b390382ede890f114a)
  * [COUNT](https://jwdeveloper.notion.site/COUNT-a33135ce0efe480195a08b63fb7a62e5)
  * [JOIN](https://jwdeveloper.notion.site/JOIN-0323ab6c15dc4448bc5ff7007a220204)
  * [JOIN의 순서와 인덱스](https://jwdeveloper.notion.site/JOIN-4a3369414e7e4812885532b587b06465)
  * [JOIN 컬럼의 데이터 타입](https://jwdeveloper.notion.site/JOIN-745b9b4d866a4879a7895786b0561371)
  * [OUTER JOIN의 성능과 주의사항](https://jwdeveloper.notion.site/OUTER-JOIN-3499ca6f6bbb47d1a0760efa6dff40e6)
  * [지연된 조인](https://jwdeveloper.notion.site/0f7de544d10a482387b5feb5444abbf3)
  * [래터럴 조인](https://jwdeveloper.notion.site/ae07afaff4084f879814fd41d4c58842)
  * [실행 계획으로 인한 정렬 흐트러짐](https://jwdeveloper.notion.site/1f4eb7a60b654421a64ef1e205f8ca83)
  * [GROUP BY](https://jwdeveloper.notion.site/GROUP-BY-b8d7078e1c1245779926e2833b3af2b9)
  * [WITH ROLLUP](https://jwdeveloper.notion.site/WITH-ROLLUP-b5d91e95ad614204a309fcc8c82e0447)
  * [ORDER BY](https://jwdeveloper.notion.site/ORDER-BY-cefaace530e74756ac67f6c6b94e39d3)
    * [ORDER BY 사용법 및 주의사항](https://jwdeveloper.notion.site/ORDER-BY-59388548c8ed4d6c9e9426e6864bca40)
    * [여러 방향으로 동시 정렬](https://jwdeveloper.notion.site/403f933a6a924711b58a07278b21c5d1)
  * 서브쿼리
    * [SELECT 절에 사용된 서브쿼리](https://jwdeveloper.notion.site/SELECT-7dff4e9d11134b59b1fc56134932d865)
    * [WHERE 절에 사용된 서브쿼리](https://jwdeveloper.notion.site/WHERE-d8239a5e5b434ea8b42a7fbdede60b4c)
  * [잠금을 사용하는 SELECT](https://jwdeveloper.notion.site/SELECT-85edb9d20dd44e5c806d207484dc9399)
  * [NOWAIT & SKIP LOCKED](https://jwdeveloper.notion.site/NOWAIT-SKIP-LOCKED-ab14e4254ff246f9afcd7b55f4ea4ae4)
* [INSERT](https://jwdeveloper.notion.site/INSERT-600d96f7f80747bda03d3eb7535aa15b)
  * [고급 옵션](https://jwdeveloper.notion.site/8728b82ae4854540a16d7d8b7aeecd2c)
  * [LOAD DATA 명령 주의 사항](https://jwdeveloper.notion.site/LOAD-DATA-749b0c44492f43cf81d06e1702459805)

# 옵티마이저와 힌트

* [개요](https://jwdeveloper.notion.site/8d2bf51ce6fc475a9ad42ad6b96b836f)
* [기본 데이터 처리](https://jwdeveloper.notion.site/03977967fd8d4f17aeb87f890125615d)
  * [풀 테이블 스캔과 풀 인덱스 스캔](https://jwdeveloper.notion.site/23e7c240f2e34b8eafa2649561a41bdf)
  
  * [병렬처리](https://jwdeveloper.notion.site/611beaf9c1ae4f59a3e21b564f2a73f9)
  
  * [ORDER BY 처리](https://jwdeveloper.notion.site/ORDER-BY-24bfacf9820a41cdb62421ea22922143)
    * [소트 버퍼](https://jwdeveloper.notion.site/2356405e3bed47888f8a377d2711a763)
    * [정렬 알고리즘](https://jwdeveloper.notion.site/9c095d84df8c4489b6c329f891f65fb5)
      * [옵티마이저 트레이스 활성화 및 보기](https://jwdeveloper.notion.site/e13b62aeb9a547438371b571810f3b14)
      * [정렬 알고리즘의 종류](https://jwdeveloper.notion.site/f16ce4773b9743f5b13dfa8bb0e4f858)
      * [싱글 패스 정렬 방식](https://jwdeveloper.notion.site/8112ef6f04044cbbbdb34b1c7bba8de9)
      * [투 패스 정렬 방식](https://jwdeveloper.notion.site/8f75678442974b9ab8f8e8927516f8ab)
      * [싱글 패스 정렬 방식 VS 투 패스 정렬 방식](https://jwdeveloper.notion.site/VS-2fca8f9726504e3b88898d43dee1d1f4)
      * [정렬 처리 방법](https://jwdeveloper.notion.site/5606b84b4cfb4d93b152d168a03f98ca)
      * [정렬 처리 방법의 성능 비교](https://jwdeveloper.notion.site/fe61116c5e1b4a9b94918783fa8129c6)
  
  * [GROUP BY 처리](https://jwdeveloper.notion.site/GROUP-BY-2c733ec67c5c461aac958f022556665f)
  
    * [인덱스 스캔을 이용하는 GROUP BY](https://jwdeveloper.notion.site/GROUP-BY-b8534353c8ba412ea5bf4046ae83f9fd)
    * [루스 인덱스 스캔을 이용하는 GROUP BY](https://jwdeveloper.notion.site/GROUP-BY-fe8da93d016b422aa6a7970c3ac92907)
    * [임시 테이블을 사용하는 GROUP BY](https://jwdeveloper.notion.site/GROUP-BY-006ba58a80164ac4aba6fb755efb1739)
  
  * [DISTINCT 처리](https://jwdeveloper.notion.site/DISTINCT-7f372d075e3549b79cd105878a812682)
  
    * [단순 DISTINCT SELECT](https://jwdeveloper.notion.site/DISTINCT-SELECT-bfcac934544b403695053a3831231402)
    * [집합 함수와 함께 사용된 DISTINCT](https://jwdeveloper.notion.site/DISTINCT-cfa676cee4f3465d9530b940afba0c3a)
  
  * [내부 임시 테이블 활용](https://jwdeveloper.notion.site/4b48649e72f44d54a6f96213f13419d4)
  
    * [메모리 임시 테이블과 디스크 임시 테이블](https://jwdeveloper.notion.site/eca77e881b744c808e1defdf7c2ebeac)
    * [임시 테이블이 필요한 쿼리](https://jwdeveloper.notion.site/ea6ae53f6af6440dad60e207790ffdb8)
    * [임시 테이블이 디스크에 생성되는 경우](https://jwdeveloper.notion.site/71076c23de5c4f86900fd09543e215bf)
    * [임시 테이블 구체적인 정보 조회](https://jwdeveloper.notion.site/52ba08193fac4447b916f5f000a51753)
  
* [고급 최적화](https://jwdeveloper.notion.site/a25ea0cbf058415486558e73d1c76fb8)
  * [MRR과 배치 키 엑세스](https://jwdeveloper.notion.site/MRR-f3c6f2c97f01404891a99d779f6ca5e6)
  * [네스티드 루프 조인과 블록 네스티드 루프 조인](https://jwdeveloper.notion.site/6df7c45097134c04997e5d6baea8a23a)
  * [인덱스 컨디션 푸시다운](https://jwdeveloper.notion.site/d4e3f90dc3f047eb932add92be696b32)
