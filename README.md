# SQL-Practice
## 📚 References
| Category | Detail |
| :------: | :------------: |
| Site | 출처: 프로그래머스 코딩 테스트 연습, https://programmers.co.kr/learn/challenges |


## ✏️ Study Review
### 1. MySQL 날짜, 시간 계산 (YYYY-MM-DD HH:MM:SS)
```
# 두 기간 사이의 일수를 계산하는 함수
DATEDIFF(시작일, 종료일)

# 두 기간 사이의 시간을 계산하는 함수
TIMEDIFF(시작일, 종료일)

# 두 기간 사이의 개월 수 차이를 계산하는 함수
PERIOD_DIFF(시작 년월, 종료 년월)

# 날짜 데이터에서 일부 정보만 추출하는 함수
YEAR(기준 날짜)
MONTH(기준 날짜)
DAY(기준 날짜)
HOUR(기준 날짜)
MINUTE(기준 날짜)
```
### 2. MySQL 사용자 정의 변수 선언
```
SET @변수이름 = 대입값 (or) SET @변수이름 := 대입값;
SELECT @변수이름 := 대입값;

# 예시: 입양 시각 구하기(2).sql
```
### 3. GROUP BY한 결과에 조건을 붙이는 법
```
HAVING()
```
