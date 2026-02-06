## 데이터베이스

- 데이터베이스 종류
  - 관계형 데이터베이스(RDBMS)
    - MySQL, 오라클, PostgreSQL 등
    - 조인 연산 지원
  - 비관계형 데이터베이스(NoSQL)
    - CouchDB, Neo4j, Cassandra, HBase, Amazon DynamoDB
    - 분류
      1. 키-값 저장소
      2. 그래프 저장소
      3. 칼럼 저장소
      4. 문서 저장서
    - 조인 연산 미지원

- 비관계형 데이터베이스가 바람직한 경우
  - 아주 낮은 응답 지연시간(latency)이 요구됨
  - 다루는 데이터가 비정형(unstructured)이라 관계형이 아님
  - 데이터(JSON, YAML, XML 등)를 직렬화하거나 역직렬화할 수 있기만 하면 됨
  - 아주 많은 양의 데이터를 저장할 필요가 있음
