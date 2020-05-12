# sqlserver
sqlserver 2016

sqlserver 2016 설치
https://dololak.tistory.com/322

--sample data--
https://github.com/microsoft/sql-server-samples/releases/tag/adventureworks

1. 이하중 연도에 맞는 *.bak 파일을 다운 받는다.
AdventureWorks (OLTP) full database backups
AdventureWorksLT (Lightweight) full database backups
AdventureWorksDW (Data Warehouse) full database backups

2. *.bak 파일을 이하 경로에 복사
"C:\Program Files\Microsoft SQL Server\MSSQL12.$서비스명\MSSQL\Backup"

3. sql server에서 SSMS 접속
좌측텝 -> 데이터베이스항목 우클릭 -> 데이터베이스 복원 -> 장치 선택 -> ... 선택 -> 추가 클릭 후 *.bak 추가 및 확인

4. 새로 고침 후 잘 들어갔는지 확인
좌측 탭 -> 데이터베이스 이하에 해당 데이터베이스 들어갔는지확인
