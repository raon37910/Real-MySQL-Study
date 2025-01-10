1. employees.sql 파일을 리얼 마이에스큐엘 저장소에서 다운로드 받아야한다.

```shell
# 스키마 세팅
docker exec -i study-mysql mysql -uroot -pqwer1234 employees < employees.sql
```