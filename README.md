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

* 쿼리 작성과 연관된 시스템 변수
  * SQL 모드
  * 영문 대소문자 구분
  * MySQL 예약어
* 메뉴얼의 SQL 문법 표기를 읽는 방법
* MySQL 연산자와 내장 함수
  * 리터럴 표기법 문자열
  * MySQL 연산자
  * MySQL 내장 함수
* SELECT
  * SELECT 절의 처리 순서
  * WHERE 절과 GROUP BY 절, ORDER BY 절의 인덱스 사용
  * WHERE 절의 비교 조건 사용 시 주의사항
  * DISTINCT
  * LIMIT n
  * COUNT()
  * JOIN
  * GROUP BY
  * ORDER BY
  * 서브쿼리
  * CTE (Common Table Expression)
  * 윈도우 함수 (Window Function)
  * 잠금을 사용하는 SELECT
