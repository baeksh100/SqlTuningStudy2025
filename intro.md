# BNK 부산은행 - SQL 튜닝 과정 (1)

2025년 07월 21일 월 ~ 07월 25일 금 / 1일 8시간 총 40시간 재직자 향상과정

# 🧭 SQL튜닝 과정 일자별 수업내용

[일자별 수업진행 내용 정리 자료](https://www.notion.so/23bf8b7e2d15817c8445d8eadd5b43b3?pvs=21)

### ✅ 학습 도우미 - SQL 챗봇

[ChatGPT - 빠르게 배워서 응용하는 SQL 튜닝](https://chatgpt.com/g/g-687dc19c590c8191bf2e3c571e4a6989-bbareuge-baeweoseo-eungyonghaneun-sql-tyuning)

---

## 🎯 **과정 목적**

1. **SQL 튜닝의 이론과 실제를 체계적으로 학습**
    - 단순 문법 중심의 SQL이 아니라, **오라클 옵티마이저 동작 원리**, **I/O 구조**, **실행계획 분석**, **Wait Event 기반의 성능진단**을 포함한 **실무 중심 성능 튜닝 과정**입니다.
2. **실제 문제 해결 역량 강화**
    - **AWR 분석**, **실제 비효율 SQL 사례 해결**, **SwingBench 및 DB 부하 테스트 실습**을 통해 튜닝 기법을 현업에 바로 적용 가능하도록 함.
3. **Oracle 환경의 구조적 이해와 병행 학습**
    - Oracle SGA, PGA 구조, 인덱스 구조, 메모리 튜닝, 힌트 활용 등 **성능을 이해하는 기반 지식 강화**.

## **✅** **과정 학습 자료**

[SQL 튜닝 자료실](https://www.notion.so/SQL-23bf8b7e2d1581fca0fcd05b761a32df?pvs=21)

[오라클 SQL 튜닝 중급 과정 – 일자별 보고서 및 실습자료 정리](https://www.notion.so/SQL-23bf8b7e2d158134b94cf666efa7e31b?pvs=21)

[오라클 SQL 튜닝 핵심 정리 (종합 요약)](https://www.notion.so/SQL-23bf8b7e2d15812397b7ff0a8c404c4f?pvs=21)

[Oracle SQL 튜닝 실무 가이드북](https://www.notion.so/Oracle-SQL-23bf8b7e2d1581c5ba03d576b4304fe2?pvs=21)

## **✅** **과정 실습 환경**

[SQL 튜닝 - 설치관련](https://www.notion.so/SQL-23bf8b7e2d15812ab1ccebfc6f53dc0b?pvs=21)

**✅ 사용자명 입력 시**

```sql
사용자명 입력: sys as sysdba
비밀번호 입력: oracle123! <- 설치시 설정된 비밀번호 / 이후 초기값 (welcome1)로 설정.
```

접속되면 아래와 같은 메시지가 나옵니다:

![image.png](image.png)

## 🧭 전체 커리큘럼 개요 (5일 × 8시간 = 총 40시간) 계획안

| 일차 | 주요 주제 | 목표 |
| --- | --- | --- |
| 1일차 | SQL 처리 구조와 오라클 I/O 구조 이해 | Oracle 내부 처리 구조 및 Block 기반 I/O 구조 이해 |
| 2일차 | 실행계획 분석과 옵티마이저 동작 원리 | 실행계획 읽기, 옵티마이저 유형, 힌트 사용법 학습 |
| 3일차 | 인덱스 전략과 테이블 설계 | B-Tree 인덱스, 클러스터링 팩터, 파티셔닝 활용 실습 |
| 4일차 | SQL 튜닝 실습 및 AWR 분석 | 실전 SQL 튜닝 + AWR Report 분석 실습 |
| 5일차 | Wait Event 기반 진단과 종합 과제 수행 | 튜닝 포인트 진단 및 최적화 시나리오 수립 훈련 |

## 🧭 일자별 교수학습 지도안

[Day01 - SQL 처리 구조와 오라클 I/O 구조 이해](https://www.notion.so/Day01-SQL-I-O-23bf8b7e2d1581bf9a6ed62527adbd6f?pvs=21)

[Day02 - 실행계획 분석과 옵티마이저 동작 원리](https://www.notion.so/Day02-23bf8b7e2d158134b220cbaa19538228?pvs=21)

[Day03 - 인덱스 전략과 테이블 설계](https://www.notion.so/Day03-23bf8b7e2d158185b702e6947588e5cc?pvs=21)

[Day04 - SQL 튜닝 실습 및 AWR 분석](https://www.notion.so/Day04-SQL-AWR-23bf8b7e2d1581429e5cded20676f0d4?pvs=21)

[Day05 - Wait Event 기반 진단과 종합 과제 수행](https://www.notion.so/Day05-Wait-Event-23bf8b7e2d158146b462e69fb6fbb7bf?pvs=21)

---

## 🎯 카카오 오픈톡 : [https://open.kakao.com/o/gbrfK7Hh](https://open.kakao.com/o/gbrfK7Hh)

### ✅ 참고 자료

1. 📘 『SQL 튜닝 중급 커리큘럼(40시간) 0721_0725.pdf』
2. 📗 『sqld 핵심요약집.pdf』 – 기초 이론 보조 교재
3. 📘 『오라클강의_PDF_교재_v1_0.pdf』 – 아키텍처, 실습, 메모리 구조, 실행계획 등 상세 자료
4. 💡 실습 환경: Oracle 23 AI Free Edition

### ✅ 친절한 SQL튜닝 교재 참고자료

[시리즈 | 친절한SQL튜닝 - grit.log](https://velog.io/@tothek/series/%EC%B9%9C%EC%A0%88%ED%95%9CSQL%ED%8A%9C%EB%8B%9D)

- 교재를 온라인 블로그 글에 다 옮겨 놓은 듯 한 velog 입니다.

### ✅ 생성형 인공지능 참고자료

- 생성형AI 활용에 참고하시면 좋을 것 같아 공유 드려요.

[생성형 AI 업무 활용 Tip!](https://www.notion.so/AI-Tip-23bf8b7e2d1581db8784d3da00388d4a?pvs=21)

[[2025 하계 한국항공대 디지털 역량 강화 캠프] 생성형 AI - A to Z 특강](https://padlet.com/aebon/2025-ai-a-to-z-gp73utbyt7mti37a)
