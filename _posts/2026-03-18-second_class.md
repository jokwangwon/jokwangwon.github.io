---
title: "[TIL] 부트캠프 두번째 복습시간"
date: 2026-03-19 18:00:00 +0900
categories: [Bootcamp, TIL]
tags: [til ,SQL, github, blog]
---

## 📚 학습 내용
오늘은 두번째 수업이다.
본격적으로 SQL 개발자가 되었다고 생각하고 수업을 들었다.

오전에는 DB 연결에서 사용되는 서비스들에 대해 살짝 배우고 OracleXETNSListener에 대해서도 DB 서버 접속하기 위한 필요한 서비스라고 살짝 알게 되었다 
client 측에서 sql 문을 보내면 sever process가 받아서 처리하고 그 결과를 다시 client 측으로 보내주는 방식이라고 한다 

추가적으로 해당 설명을 하시면서 
혼자공부하는 운영체제 
[https://www.youtube.com/results?search_query=혼자+공부하는+컴퓨터+구조%2B운영체제](https://www.youtube.com/results?search_query=%ED%98%BC%EC%9E%90+%EA%B3%B5%EB%B6%80%ED%95%98%EB%8A%94+%EC%BB%B4%ED%93%A8%ED%84%B0+%EA%B5%AC%EC%A1%B0%2B%EC%9A%B4%EC%98%81%EC%B2%B4%EC%A0%9C)

이 유튜브 채널을 추천해주셨다. 

이후 문제들을 내주셨는데 간단하게도 어제 했던 연결 연산자를 사용한 문제들이었다. 

중복행 제거, where 절을 사용한 조건절 등 수업을 하시고 해당 주제 관련하여 문제들을 내주셨는데 기억나는 문제들이 몇가지 있다.

date 타입에 관한 문제에서 문자열과 비교를 하는데 서로 다른 타입이지만 암시적으로 오라클에서 형 변환을 해주어서 비교가 가능하다는 점이였다.

추가적으로 문자 함수에 대해서도 배웠는데 조건절에서 컬럼에 함수를 씌우면 Full table scan이 발생하여 성능이 저하될 수 있다는 점을 배웠다.

concat,length, lengthb 등 정도 까지 배우고 수업이 끝났다.

## 🎯 오늘 배운 핵심 내용
- date 타입과 문자열 타입은 암시적으로 형 변환이 가능하여 비교가 가능하다.
- where 절에서 컬럼에 함수를 씌우면 Full table scan이 발생하여 성능이 저하될 수 있다. 주의하자

## 🤔 오늘의 회고
점차적으로 수업 내용이 많아지고 있다. 
잘 정리하고 복습도 잘하자!