*[English](README.md) ∙ [日本語](README-ja.md) ∙ [한국어](README-ko.md) ∙ [简体中文](README-zh-Hans.md) ∙ [繁體中文](README-zh-TW.md) | [العَرَبِيَّة‎](https://github.com/donnemartin/system-design-primer/issues/170) ∙ [বাংলা](https://github.com/donnemartin/system-design-primer/issues/220) ∙ [Português do Brasil](https://github.com/donnemartin/system-design-primer/issues/40) ∙ [Deutsch](https://github.com/donnemartin/system-design-primer/issues/186) ∙ [ελληνικά](https://github.com/donnemartin/system-design-primer/issues/130) ∙ [עברית](https://github.com/donnemartin/system-design-primer/issues/272) ∙ [Italiano](https://github.com/donnemartin/system-design-primer/issues/104) ∙ [فارسی](https://github.com/donnemartin/system-design-primer/issues/110) ∙ [Polski](https://github.com/donnemartin/system-design-primer/issues/68) ∙ [русский язык](https://github.com/donnemartin/system-design-primer/issues/87) ∙ [Español](https://github.com/donnemartin/system-design-primer/issues/136) ∙ [ภาษาไทย](https://github.com/donnemartin/system-design-primer/issues/187) ∙ [Türkçe](https://github.com/donnemartin/system-design-primer/issues/39) ∙ [tiếng Việt](https://github.com/donnemartin/system-design-primer/issues/127) ∙ [Français](https://github.com/donnemartin/system-design-primer/issues/250) | [Add Translation](https://github.com/donnemartin/system-design-primer/issues/28)*

**이 가이드의 [번역](TRANSLATIONS.md)을 도와줄 사람을 찾고 있다!**

# 시스템 설계 입문

<p align="center">
  <img src="images/jj3A5N8.png">
  <br/>
</p>

## 목적

> 대규모 시스템을 설계하는 방법을 배운다.
>
> 시스템 설계 면접을 준비한다.

### 대규모 시스템 설계 배우기

확장 가능한(scalable) 시스템을 설계하는 법을 익히면 더 나은 엔지니어가 될 수 있다.

시스템 설계(system design)는 범위가 넓은 주제다. 시스템 설계 원칙에 관한 자료는 **웹 곳곳에 방대하게 흩어져 있다**.

이 저장소는 대규모 시스템을 구축하는 방법을 배우는 데 도움이 되는 자료를 **체계적으로 정리한 모음**이다.

### 오픈 소스 커뮤니티에서 배우기

이 프로젝트는 계속 업데이트되는 오픈 소스 프로젝트다.

[기여](#기여하기)는 언제든 환영한다!

### 시스템 설계 면접 준비하기

많은 기술 기업의 **기술 면접 과정**에서 시스템 설계는 코딩 면접과 함께 **필수 항목**이다.

**자주 나오는 시스템 설계 면접 문제를 연습**하고, 결과를 토론·코드·다이어그램이 담긴 **예시 풀이**와 **비교**하라.

면접 준비에 도움이 되는 다른 주제:

* [학습 가이드](#학습-가이드)
* [시스템 설계 면접 문제에 접근하는 방법](#시스템-설계-면접-문제에-접근하는-방법)
* [시스템 설계 면접 문제(**풀이 포함**)](#시스템-설계-면접-문제와-풀이)
* [객체 지향 설계 면접 문제(**풀이 포함**)](#객체-지향-설계-면접-문제와-풀이)
* [추가 시스템 설계 면접 문제](#추가-시스템-설계-면접-문제)

## Anki 플래시카드

<p align="center">
  <img src="images/zdCAkB3.png">
  <br/>
</p>

함께 제공하는 [Anki 플래시카드 덱](https://apps.ankiweb.net/)은 간격 반복(spaced repetition) 방식으로 시스템 설계의 핵심 개념을 오래 기억하도록 돕는다.

* [시스템 설계 덱](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/System%20Design.apkg)
* [시스템 설계 연습 문제 덱](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/System%20Design%20Exercises.apkg)
* [객체 지향 설계 연습 문제 덱](https://github.com/donnemartin/system-design-primer/tree/master/resources/flash_cards/OO%20Design.apkg)

이동 중에 공부하기 좋다.

### 코딩 자료: Interactive Coding Challenges

[**코딩 면접**](https://github.com/donnemartin/interactive-coding-challenges) 준비에 도움이 되는 자료를 찾고 있는가?

<p align="center">
  <img src="images/b4YtAEN.png">
  <br/>
</p>

추가 Anki 덱이 들어 있는 자매 저장소 [**Interactive Coding Challenges**](https://github.com/donnemartin/interactive-coding-challenges)도 살펴보라:

* [코딩 덱](https://github.com/donnemartin/interactive-coding-challenges/tree/master/anki_cards/Coding.apkg)

## 기여하기

> 커뮤니티에서 배운다.

다음과 같은 풀 리퀘스트는 언제든 환영한다:

* 오류 수정
* 기존 섹션 개선
* 새 섹션 추가
* [번역](https://github.com/donnemartin/system-design-primer/issues/28)

다듬어야 할 내용은 [작업 중](#작업-중) 섹션에 모아 두었다.

[기여 가이드라인](CONTRIBUTING.md)을 참고하라.

## 시스템 설계 주제 목차

> 다양한 시스템 설계 주제를 장단점과 함께 요약했다. **모든 것은 트레이드오프(trade-off)다**.
>
> 섹션마다 더 깊이 있는 자료로 가는 링크가 있다.

<p align="center">
  <img src="images/jrUBAF7.png">
  <br/>
</p>

* [시스템 설계 주제: 여기서 시작하기](#시스템-설계-주제-여기서-시작하기)
    * [1단계: 확장성 강의 영상 복습하기](#1단계-확장성-강의-영상-복습하기)
    * [2단계: 확장성 글 복습하기](#2단계-확장성-글-복습하기)
    * [다음 단계](#다음-단계)
* [성능 vs 확장성](#성능-vs-확장성)
* [지연 시간 vs 처리량](#지연-시간-vs-처리량)
* [가용성 vs 일관성](#가용성-vs-일관성)
    * [CAP 정리](#cap-정리)
        * [CP - 일관성과 분할 내성](#cp---일관성과-분할-내성)
        * [AP - 가용성과 분할 내성](#ap---가용성과-분할-내성)
* [일관성 패턴](#일관성-패턴)
    * [약한 일관성](#약한-일관성)
    * [최종적 일관성](#최종적-일관성)
    * [강한 일관성](#강한-일관성)
* [가용성 패턴](#가용성-패턴)
    * [장애 조치](#장애-조치)
    * [복제](#복제)
    * [수치로 본 가용성](#수치로-본-가용성)
* [도메인 네임 시스템](#도메인-네임-시스템)
* [콘텐츠 전송 네트워크](#콘텐츠-전송-네트워크)
    * [푸시 CDN](#푸시-cdn)
    * [풀 CDN](#풀-cdn)
* [로드 밸런서](#로드-밸런서)
    * [액티브-패시브](#액티브-패시브)
    * [액티브-액티브](#액티브-액티브)
    * [4계층 로드 밸런싱](#4계층-로드-밸런싱)
    * [7계층 로드 밸런싱](#7계층-로드-밸런싱)
    * [수평 확장](#수평-확장)
* [리버스 프록시(웹 서버)](#리버스-프록시웹-서버)
    * [로드 밸런서 vs 리버스 프록시](#로드-밸런서-vs-리버스-프록시)
* [애플리케이션 계층](#애플리케이션-계층)
    * [마이크로서비스](#마이크로서비스)
    * [서비스 디스커버리](#서비스-디스커버리)
* [데이터베이스](#데이터베이스)
    * [관계형 데이터베이스 관리 시스템(RDBMS)](#관계형-데이터베이스-관리-시스템rdbms)
        * [마스터-슬레이브 복제](#마스터-슬레이브-복제)
        * [마스터-마스터 복제](#마스터-마스터-복제)
        * [페더레이션](#페더레이션)
        * [샤딩](#샤딩)
        * [비정규화](#비정규화)
        * [SQL 튜닝](#sql-튜닝)
    * [NoSQL](#nosql)
        * [키-값 저장소](#키-값-저장소)
        * [문서 저장소](#문서-저장소)
        * [와이드 컬럼 저장소](#와이드-컬럼-저장소)
        * [그래프 데이터베이스](#그래프-데이터베이스)
    * [SQL 또는 NoSQL](#sql-또는-nosql)
* [캐시](#캐시)
    * [클라이언트 캐싱](#클라이언트-캐싱)
    * [CDN 캐싱](#cdn-캐싱)
    * [웹 서버 캐싱](#웹-서버-캐싱)
    * [데이터베이스 캐싱](#데이터베이스-캐싱)
    * [애플리케이션 캐싱](#애플리케이션-캐싱)
    * [데이터베이스 쿼리 수준 캐싱](#데이터베이스-쿼리-수준-캐싱)
    * [객체 수준 캐싱](#객체-수준-캐싱)
    * [캐시 갱신 시점](#캐시-갱신-시점)
        * [Cache-aside](#cache-aside)
        * [Write-through](#write-through)
        * [Write-behind(write-back)](#write-behindwrite-back)
        * [Refresh-ahead](#refresh-ahead)
* [비동기 처리](#비동기-처리)
    * [메시지 큐](#메시지-큐)
    * [태스크 큐](#태스크-큐)
    * [백프레셔](#백프레셔)
* [통신](#통신)
    * [전송 제어 프로토콜(TCP)](#전송-제어-프로토콜tcp)
    * [사용자 데이터그램 프로토콜(UDP)](#사용자-데이터그램-프로토콜udp)
    * [원격 프로시저 호출(RPC)](#원격-프로시저-호출rpc)
    * [REST(Representational State Transfer)](#restrepresentational-state-transfer)
* [보안](#보안)
* [부록](#부록)
    * [2의 거듭제곱 표](#2의-거듭제곱-표)
    * [모든 프로그래머가 알아야 할 지연 시간 수치](#모든-프로그래머가-알아야-할-지연-시간-수치)
    * [추가 시스템 설계 면접 문제](#추가-시스템-설계-면접-문제)
    * [실제 아키텍처 사례](#실제-아키텍처-사례)
    * [기업별 아키텍처](#기업별-아키텍처)
    * [기업 엔지니어링 블로그](#기업-엔지니어링-블로그)
* [작업 중](#작업-중)
* [감사의 말](#감사의-말)
* [연락처](#연락처)
* [라이선스](#라이선스)

## 학습 가이드

> 면접까지 남은 기간(단기, 중기, 장기)에 맞춰 복습할 주제를 추천한다.

![Imgur](images/OfVllex.png)

**Q: 면접을 준비하려면 여기 있는 내용을 전부 알아야 하는가?**

**A: 아니다. 면접을 준비하는 데 여기 있는 내용을 전부 알 필요는 없다**.

면접에서 어떤 질문을 받는지는 다음과 같은 변수에 달려 있다:

* 경력이 얼마나 되는지
* 어떤 기술 배경을 가졌는지
* 어떤 직무로 지원했는지
* 어느 회사의 면접을 보는지
* 운

경력이 많은 지원자일수록 대체로 시스템 설계를 더 많이 알고 있으리라 기대된다. 아키텍트나 팀 리드라면 개인 기여자(individual contributor)보다 더 많이 알기를 요구받을 수 있다. 최상위 기술 기업은 설계 면접을 한 번 이상 진행할 가능성이 높다.

넓게 시작해서 몇몇 분야를 깊이 파고들어라. 시스템 설계의 여러 핵심 주제를 조금씩 알아 두면 도움이 된다. 남은 기간, 경력, 지원 직무, 면접 볼 회사에 맞춰 아래 가이드를 조정하라.

* **단기** - 시스템 설계 주제를 **폭넓게** 익히는 것을 목표로 하라. 면접 문제를 **일부** 풀어 보며 연습하라.
* **중기** - 시스템 설계 주제를 **폭넓게**, 그리고 **어느 정도 깊이** 익히는 것을 목표로 하라. 면접 문제를 **많이** 풀어 보며 연습하라.
* **장기** - 시스템 설계 주제를 **폭넓게**, 그리고 **더 깊이** 익히는 것을 목표로 하라. 면접 문제를 **대부분** 풀어 보며 연습하라.

| | 단기 | 중기 | 장기 |
|---|---|---|---|
| [시스템 설계 주제](#시스템-설계-주제-목차)를 읽고 시스템이 동작하는 방식을 폭넓게 이해하기 | :+1: | :+1: | :+1: |
| 면접 볼 회사의 [기업 엔지니어링 블로그](#기업-엔지니어링-블로그) 글 몇 개 읽기 | :+1: | :+1: | :+1: |
| [실제 아키텍처 사례](#실제-아키텍처-사례) 몇 개 읽기 | :+1: | :+1: | :+1: |
| [시스템 설계 면접 문제에 접근하는 방법](#시스템-설계-면접-문제에-접근하는-방법) 복습하기 | :+1: | :+1: | :+1: |
| [시스템 설계 면접 문제와 풀이](#시스템-설계-면접-문제와-풀이) 풀어 보기 | 일부 | 많이 | 대부분 |
| [객체 지향 설계 면접 문제와 풀이](#객체-지향-설계-면접-문제와-풀이) 풀어 보기 | 일부 | 많이 | 대부분 |
| [추가 시스템 설계 면접 문제](#추가-시스템-설계-면접-문제) 복습하기 | 일부 | 많이 | 대부분 |

## 시스템 설계 면접 문제에 접근하는 방법

> 시스템 설계 면접 문제를 공략하는 방법.

시스템 설계 면접은 **정해진 답이 없는 열린 대화**다. 대화는 지원자가 이끌어야 한다.

다음 단계를 따라 논의를 이끌 수 있다. 이 과정을 몸에 익히려면 다음 단계에 따라 [시스템 설계 면접 문제와 풀이](#시스템-설계-면접-문제와-풀이) 섹션을 풀어 보라.

### 1단계: 유스 케이스, 제약 조건, 가정 정리하기

요구 사항을 모으고 문제의 범위를 정하라. 질문을 던져 유스 케이스(use case)와 제약 조건을 분명히 하라. 가정을 함께 논의하라.

* 누가 사용하는가?
* 어떻게 사용하는가?
* 사용자는 몇 명인가?
* 시스템은 무엇을 하는가?
* 시스템의 입력과 출력은 무엇인가?
* 처리해야 할 데이터는 얼마나 되는가?
* 초당 요청은 몇 건으로 예상하는가?
* 예상되는 읽기 대 쓰기 비율은 얼마인가?

### 2단계: 상위 수준 설계 만들기

중요한 컴포넌트를 모두 담아 상위 수준 설계(high level design)의 윤곽을 잡아라.

* 주요 컴포넌트와 연결 관계 그리기
* 아이디어의 근거 제시하기

### 3단계: 핵심 컴포넌트 설계하기

핵심 컴포넌트마다 세부 사항을 깊이 파고들어라. 예를 들어 [URL 단축 서비스를 설계하라](solutions/system_design/pastebin/README.md)는 문제를 받았다면 다음을 논의하라:

* 전체 URL의 해시를 생성하고 저장하기
    * [MD5](solutions/system_design/pastebin/README.md)와 [Base62](solutions/system_design/pastebin/README.md)
    * 해시 충돌
    * SQL 또는 NoSQL
    * 데이터베이스 스키마
* 해시된 URL을 전체 URL로 변환하기
    * 데이터베이스 조회
* API와 객체 지향 설계

### 4단계: 설계 확장하기

제약 조건을 고려해 병목(bottleneck)을 찾아 해결하라. 예를 들어 확장성(scalability) 문제를 해결하려면 다음이 필요한가?

* 로드 밸런서(load balancer)
* 수평 확장(horizontal scaling)
* 캐싱(caching)
* 데이터베이스 샤딩(sharding)

가능한 해결책과 트레이드오프를 논의하라. 모든 것은 트레이드오프다. [확장 가능한 시스템 설계 원칙](#시스템-설계-주제-목차)을 활용해 병목을 해결하라.

### 개략적인 계산

손으로 직접 추정해 보라는 요청을 받을 수도 있다. 다음 자료는 [부록](#부록)을 참고하라:

* [Use back of the envelope calculations](http://highscalability.com/blog/2011/1/26/google-pro-tip-use-back-of-the-envelope-calculations-to-choo.html)
* [2의 거듭제곱 표](#2의-거듭제곱-표)
* [모든 프로그래머가 알아야 할 지연 시간 수치](#모든-프로그래머가-알아야-할-지연-시간-수치)

### 출처 및 더 읽을거리

면접에서 무엇을 마주하게 될지 더 잘 알고 싶다면 다음 링크를 살펴보라:

* [How to ace a systems design interview](https://web.archive.org/web/20210505130322/https://www.palantir.com/2011/10/how-to-rock-a-systems-design-interview/)
* [The system design interview](http://www.hiredintech.com/system-design)
* [Intro to Architecture and Systems Design Interviews](https://www.youtube.com/watch?v=ZgdS0EUmn70)
* [System design template](https://leetcode.com/discuss/career/229177/My-System-Design-Template)

## 시스템 설계 면접 문제와 풀이

> 자주 나오는 시스템 설계 면접 문제와 예시 토론, 코드, 다이어그램.
>
> 풀이는 `solutions/` 폴더의 내용으로 연결된다.

| 문제 | |
|---|---|
| Pastebin.com(또는 Bit.ly) 설계하기 | [풀이](solutions/system_design/pastebin/README.md) |
| Twitter 타임라인과 검색(또는 Facebook 피드와 검색) 설계하기 | [풀이](solutions/system_design/twitter/README.md) |
| 웹 크롤러 설계하기 | [풀이](solutions/system_design/web_crawler/README.md) |
| Mint.com 설계하기 | [풀이](solutions/system_design/mint/README.md) |
| 소셜 네트워크의 데이터 구조 설계하기 | [풀이](solutions/system_design/social_graph/README.md) |
| 검색 엔진용 키-값 저장소 설계하기 | [풀이](solutions/system_design/query_cache/README.md) |
| Amazon의 카테고리별 판매 순위 기능 설계하기 | [풀이](solutions/system_design/sales_rank/README.md) |
| AWS에서 수백만 사용자로 확장되는 시스템 설계하기 | [풀이](solutions/system_design/scaling_aws/README.md) |
| 시스템 설계 문제 추가하기 | [기여하기](#기여하기) |

### Pastebin.com(또는 Bit.ly) 설계하기

[문제와 풀이 보기](solutions/system_design/pastebin/README.md)

![Imgur](images/4edXG0T.png)

### Twitter 타임라인과 검색(또는 Facebook 피드와 검색) 설계하기

[문제와 풀이 보기](solutions/system_design/twitter/README.md)

![Imgur](images/jrUBAF7.png)

### 웹 크롤러 설계하기

[문제와 풀이 보기](solutions/system_design/web_crawler/README.md)

![Imgur](images/bWxPtQA.png)

### Mint.com 설계하기

[문제와 풀이 보기](solutions/system_design/mint/README.md)

![Imgur](images/V5q57vU.png)

### 소셜 네트워크의 데이터 구조 설계하기

[문제와 풀이 보기](solutions/system_design/social_graph/README.md)

![Imgur](images/cdCv5g7.png)

### 검색 엔진용 키-값 저장소 설계하기

[문제와 풀이 보기](solutions/system_design/query_cache/README.md)

![Imgur](images/4j99mhe.png)

### Amazon의 카테고리별 판매 순위 기능 설계하기

[문제와 풀이 보기](solutions/system_design/sales_rank/README.md)

![Imgur](images/MzExP06.png)

### AWS에서 수백만 사용자로 확장되는 시스템 설계하기

[문제와 풀이 보기](solutions/system_design/scaling_aws/README.md)

![Imgur](images/jj3A5N8.png)

## 객체 지향 설계 면접 문제와 풀이

> 자주 나오는 객체 지향 설계 면접 문제와 예시 토론, 코드, 다이어그램.
>
> 풀이는 `solutions/` 폴더의 내용으로 연결된다.

>**참고: 이 섹션은 작업 중이다**

| 문제 | |
|---|---|
| 해시 맵 설계하기 | [풀이](solutions/object_oriented_design/hash_table/hash_map.ipynb)  |
| LRU(least recently used) 캐시 설계하기 | [풀이](solutions/object_oriented_design/lru_cache/lru_cache.ipynb)  |
| 콜센터 설계하기 | [풀이](solutions/object_oriented_design/call_center/call_center.ipynb)  |
| 카드 덱 설계하기 | [풀이](solutions/object_oriented_design/deck_of_cards/deck_of_cards.ipynb)  |
| 주차장 설계하기 | [풀이](solutions/object_oriented_design/parking_lot/parking_lot.ipynb)  |
| 채팅 서버 설계하기 | [풀이](solutions/object_oriented_design/online_chat/online_chat.ipynb)  |
| 원형 배열 설계하기 | [기여하기](#기여하기)  |
| 객체 지향 설계 문제 추가하기 | [기여하기](#기여하기) |

## 시스템 설계 주제: 여기서 시작하기

시스템 설계가 처음인가?

먼저 공통 원칙이 무엇인지, 어떻게 쓰이는지, 장단점은 무엇인지 익혀 기본을 다져야 한다.

### 1단계: 확장성 강의 영상 복습하기

[Scalability Lecture at Harvard](https://www.youtube.com/watch?v=-W9F__D3oY4)

* 다루는 주제:
    * 수직 확장(vertical scaling)
    * 수평 확장
    * 캐싱
    * 로드 밸런싱
    * 데이터베이스 복제(replication)
    * 데이터베이스 파티셔닝

### 2단계: 확장성 글 복습하기

[Scalability](https://web.archive.org/web/20221030091841/http://www.lecloud.net/tagged/scalability/chrono)

* 다루는 주제:
    * [Clones](https://web.archive.org/web/20220530193911/https://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
    * [Databases](https://web.archive.org/web/20220602114024/https://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
    * [Caches](https://web.archive.org/web/20230126233752/https://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
    * [Asynchronism](https://web.archive.org/web/20220926171507/https://www.lecloud.net/post/9699762917/scalability-for-dummies-part-4-asynchronism)

### 다음 단계

다음으로 큰 틀의 트레이드오프를 살펴본다:

* **성능**(performance) vs **확장성**
* **지연 시간**(latency) vs **처리량**(throughput)
* **가용성**(availability) vs **일관성**(consistency)

**모든 것은 트레이드오프**라는 점을 기억하라.

그다음 DNS, CDN, 로드 밸런서 같은 더 구체적인 주제를 깊이 살펴본다.

## 성능 vs 확장성

서비스에 자원을 더할수록 그에 비례해 **성능**이 높아진다면 그 서비스는 **확장 가능**하다. 일반적으로 성능을 높인다는 것은 더 많은 작업 단위를 처리한다는 뜻이지만, 데이터셋이 커질 때처럼 더 큰 작업 단위를 처리한다는 뜻일 수도 있다.<sup><a href=http://www.allthingsdistributed.com/2006/03/a_word_on_scalability.html>1</a></sup>

성능과 확장성을 다른 각도에서 보면 이렇다:

* **성능** 문제가 있다면 사용자 한 명에게도 시스템이 느리다.
* **확장성** 문제가 있다면 사용자 한 명에게는 빠르지만 부하가 커지면 느려진다.

### 출처 및 더 읽을거리

* [A word on scalability](http://www.allthingsdistributed.com/2006/03/a_word_on_scalability.html)
* [Scalability, availability, stability, patterns](http://www.slideshare.net/jboner/scalability-availability-stability-patterns/)

## 지연 시간 vs 처리량

**지연 시간**은 어떤 작업을 수행하거나 결과를 만들어 내는 데 걸리는 시간이다.

**처리량**은 단위 시간당 처리하는 작업이나 결과의 수다.

일반적으로 **허용 가능한 지연 시간** 안에서 **최대 처리량**을 목표로 해야 한다.

### 출처 및 더 읽을거리

* [Understanding latency vs throughput](https://community.cadence.com/cadence_blogs_8/b/fv/posts/understanding-latency-vs-throughput)

## 가용성 vs 일관성

### CAP 정리

<p align="center">
  <img src="images/bgLMI2u.png">
  <br/>
  <i><a href="https://robertgreiner.com/cap-theorem-revisited">출처: CAP theorem revisited</a></i>
</p>

분산 컴퓨터 시스템에서는 다음 세 가지 보장 중 두 가지만 지킬 수 있다:

* **일관성** - 모든 읽기는 가장 최근에 쓴 값이나 오류를 받는다
* **가용성** - 모든 요청은 응답을 받지만, 그 응답이 가장 최신 정보라는 보장은 없다
* **분할 내성**(partition tolerance) - 네트워크 장애로 시스템이 임의로 분할되어도 계속 동작한다

*네트워크는 신뢰할 수 없으므로 분할 내성은 반드시 지원해야 한다. 결국 소프트웨어 차원에서 일관성과 가용성 사이의 트레이드오프를 정해야 한다.*

#### CP - 일관성과 분할 내성

분할된 노드의 응답을 기다리다 타임아웃 오류가 날 수 있다. 비즈니스 요구 사항이 원자적인 읽기와 쓰기를 필요로 한다면 CP가 좋은 선택이다.

#### AP - 가용성과 분할 내성

응답은 어느 노드에서든 가장 쉽게 얻을 수 있는 버전의 데이터를 돌려주며, 이는 최신이 아닐 수 있다. 분할이 해소된 뒤 쓰기가 전파되는 데 시간이 걸릴 수 있다.

비즈니스가 [최종적 일관성](#최종적-일관성)을 허용할 수 있거나, 외부 오류가 있어도 시스템이 계속 동작해야 한다면 AP가 좋은 선택이다.

### 출처 및 더 읽을거리

* [CAP theorem revisited](https://robertgreiner.com/cap-theorem-revisited/)
* [A plain english introduction to CAP theorem](http://ksat.me/a-plain-english-introduction-to-cap-theorem)
* [CAP FAQ](https://github.com/henryr/cap-faq)
* [The CAP theorem](https://www.youtube.com/watch?v=k-Yaq8AHlFA)

## 일관성 패턴

같은 데이터의 복사본이 여러 개 있으면, 클라이언트가 일관된 데이터를 보도록 복사본을 어떻게 동기화할지 선택해야 한다. [CAP 정리](#cap-정리)에서 본 일관성의 정의를 떠올려 보라. 모든 읽기는 가장 최근에 쓴 값이나 오류를 받는다.

### 약한 일관성

쓰기 이후의 읽기는 그 값을 볼 수도, 못 볼 수도 있다. 최선의 노력(best effort) 방식을 따른다.

이 방식은 memcached 같은 시스템에서 볼 수 있다. 약한 일관성(weak consistency)은 VoIP, 화상 채팅, 실시간 멀티플레이어 게임 같은 실시간 유스 케이스에 잘 맞는다. 예를 들어 통화 중 몇 초 동안 신호가 끊겼다가 다시 연결되면, 끊겨 있던 동안 오간 말은 들을 수 없다.

### 최종적 일관성

쓰기 이후의 읽기는 결국 그 값을 보게 된다(보통 몇 밀리초 안에). 데이터는 비동기로 복제된다.

이 방식은 DNS나 이메일 같은 시스템에서 볼 수 있다. 최종적 일관성(eventual consistency)은 가용성이 높은 시스템에 잘 맞는다.

### 강한 일관성

쓰기 이후의 읽기는 그 값을 본다. 데이터는 동기로 복제된다.

이 방식은 파일 시스템과 RDBMS에서 볼 수 있다. 강한 일관성(strong consistency)은 트랜잭션이 필요한 시스템에 잘 맞는다.

### 출처 및 더 읽을거리

* [Transactions across data centers](http://snarfed.org/transactions_across_datacenters_io.html)

## 가용성 패턴

높은 가용성을 지원하는 서로 보완적인 패턴이 두 가지 있다. **장애 조치**(fail-over)와 **복제**다.

### 장애 조치

#### 액티브-패시브

액티브-패시브 장애 조치에서는 액티브 서버와 대기 중인 패시브 서버가 하트비트(heartbeat)를 주고받는다. 하트비트가 끊기면 패시브 서버가 액티브 서버의 IP 주소를 넘겨받아 서비스를 이어 간다.

다운타임의 길이는 패시브 서버가 이미 실행 중인 '핫' 대기 상태인지, '콜드' 대기 상태에서 새로 시작해야 하는지에 따라 달라진다. 트래픽은 액티브 서버만 처리한다.

액티브-패시브 장애 조치는 마스터-슬레이브 장애 조치라고도 한다.

#### 액티브-액티브

액티브-액티브에서는 두 서버가 모두 트래픽을 처리하며 부하를 나눠 맡는다.

서버가 외부에 공개되어 있다면 DNS가 두 서버의 공인 IP를 알아야 한다. 서버가 내부용이라면 애플리케이션 로직이 두 서버를 알아야 한다.

액티브-액티브 장애 조치는 마스터-마스터 장애 조치라고도 한다.

### 단점: 장애 조치

* 장애 조치는 하드웨어를 더 늘리고 복잡도를 높인다.
* 새로 쓴 데이터가 패시브 쪽으로 복제되기 전에 액티브 시스템이 죽으면 데이터를 잃을 수 있다.

### 복제

#### 마스터-슬레이브와 마스터-마스터

이 주제는 [데이터베이스](#데이터베이스) 섹션에서 더 자세히 다룬다:

* [마스터-슬레이브 복제](#마스터-슬레이브-복제)
* [마스터-마스터 복제](#마스터-마스터-복제)

### 수치로 본 가용성

가용성은 흔히 서비스가 사용 가능한 시간의 비율, 즉 가동 시간(또는 다운타임)으로 수치화한다. 가용성은 보통 9의 개수로 표현한다. 가용성이 99.99%인 서비스는 '포 나인'이라고 부른다.

#### 99.9% 가용성 - 쓰리 나인

| 기간                | 허용되는 다운타임  |
|---------------------|--------------------|
| 연간 다운타임       | 8시간 45분 57초    |
| 월간 다운타임       | 43분 49.7초        |
| 주간 다운타임       | 10분 4.8초         |
| 일간 다운타임       | 1분 26.4초         |

#### 99.99% 가용성 - 포 나인

| 기간                | 허용되는 다운타임  |
|---------------------|--------------------|
| 연간 다운타임       | 52분 35.7초        |
| 월간 다운타임       | 4분 23초           |
| 주간 다운타임       | 1분 5초            |
| 일간 다운타임       | 8.6초              |

#### 병렬 vs 직렬 가용성

서비스가 장애가 날 수 있는 여러 컴포넌트로 이루어져 있다면, 서비스 전체의 가용성은 컴포넌트가 직렬로 연결되었는지 병렬로 연결되었는지에 따라 달라진다.

###### 직렬

가용성이 100% 미만인 컴포넌트 두 개가 직렬로 연결되면 전체 가용성은 낮아진다:

```
Availability (Total) = Availability (Foo) * Availability (Bar)
```

`Foo`와 `Bar`의 가용성이 각각 99.9%라면, 직렬로 연결했을 때 전체 가용성은 99.8%가 된다.

###### 병렬

가용성이 100% 미만인 컴포넌트 두 개가 병렬로 연결되면 전체 가용성은 높아진다:

```
Availability (Total) = 1 - (1 - Availability (Foo)) * (1 - Availability (Bar))
```

`Foo`와 `Bar`의 가용성이 각각 99.9%라면, 병렬로 연결했을 때 전체 가용성은 99.9999%가 된다.

## 도메인 네임 시스템

<p align="center">
  <img src="images/IOyLj4i.jpg">
  <br/>
  <i><a href=http://www.slideshare.net/srikrupa5/dns-security-presentation-issa>출처: DNS security presentation</a></i>
</p>

도메인 네임 시스템(Domain Name System, DNS)은 www.example.com 같은 도메인 이름을 IP 주소로 변환한다.

DNS는 계층 구조이며, 최상위에는 소수의 권한 있는(authoritative) 서버가 있다. 조회할 때 어느 DNS 서버에 물어볼지는 라우터나 ISP가 알려 준다. 하위 DNS 서버는 매핑을 캐시하는데, DNS 전파 지연 때문에 이 캐시가 오래된 정보가 될 수 있다. DNS 결과는 브라우저나 OS에도 일정 시간 캐시되며, 그 시간은 [TTL(time to live)](https://en.wikipedia.org/wiki/Time_to_live)이 정한다.

* **NS 레코드**(name server) - 도메인이나 서브도메인을 담당하는 DNS 서버를 지정한다.
* **MX 레코드**(mail exchange) - 메일을 받을 메일 서버를 지정한다.
* **A 레코드**(address) - 이름을 IP 주소에 연결한다.
* **CNAME**(canonical) - 이름을 다른 이름이나 `CNAME`(example.com에서 www.example.com으로), 또는 `A` 레코드에 연결한다.

[CloudFlare](https://www.cloudflare.com/dns/)나 [Route 53](https://aws.amazon.com/route53/) 같은 서비스는 관리형 DNS를 제공한다. 일부 DNS 서비스는 여러 방식으로 트래픽을 라우팅할 수 있다:

* [가중 라운드 로빈](https://www.jscape.com/blog/load-balancing-algorithms)
    * 점검 중인 서버로 트래픽이 가지 않게 하기
    * 크기가 다른 클러스터 사이에서 균형 맞추기
    * A/B 테스트
* [지연 시간 기반](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-latency.html)
* [지리적 위치 기반](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy-geo.html)

### 단점: DNS

* DNS 서버에 접근하면 약간의 지연이 생긴다. 다만 앞서 설명한 캐싱이 이를 줄여 준다.
* DNS 서버 관리는 복잡할 수 있으며, 보통 [정부, ISP, 대기업](http://superuser.com/questions/472695/who-controls-the-dns-servers/472729)이 관리한다.
* 최근 DNS 서비스가 [DDoS 공격](http://dyn.com/blog/dyn-analysis-summary-of-friday-october-21-attack/)을 받아, 사용자가 Twitter의 IP 주소를 모르면 Twitter 같은 웹사이트에 접속하지 못한 일이 있었다.

### 출처 및 더 읽을거리

* [DNS architecture](https://technet.microsoft.com/en-us/library/dd197427(v=ws.10).aspx)
* [Wikipedia](https://en.wikipedia.org/wiki/Domain_Name_System)
* [DNS articles](https://support.dnsimple.com/categories/dns/)

## 콘텐츠 전송 네트워크

<p align="center">
  <img src="images/h9TAuGI.jpg">
  <br/>
  <i><a href=https://www.creative-artworks.eu/why-use-a-content-delivery-network-cdn/>출처: Why use a CDN</a></i>
</p>

콘텐츠 전송 네트워크(content delivery network, CDN)는 전 세계에 분산된 프록시 서버 네트워크로, 사용자와 가까운 위치에서 콘텐츠를 제공한다. 보통 HTML/CSS/JS, 사진, 동영상 같은 정적 파일을 CDN에서 제공하지만, Amazon CloudFront처럼 동적 콘텐츠를 지원하는 CDN도 있다. 클라이언트가 어느 서버에 접속할지는 사이트의 DNS 조회 결과가 알려 준다.

CDN에서 콘텐츠를 제공하면 두 가지 면에서 성능이 크게 좋아진다:

* 사용자는 가까운 데이터 센터에서 콘텐츠를 받는다
* CDN이 처리한 요청은 내 서버가 처리하지 않아도 된다

### 푸시 CDN

푸시 CDN은 서버에서 변경이 생길 때마다 새 콘텐츠를 받는다. 콘텐츠를 CDN에 직접 올리고 URL을 CDN을 가리키도록 바꾸는 일까지 전부 내가 책임진다. 콘텐츠가 언제 만료되고 언제 갱신될지 설정할 수 있다. 콘텐츠는 새로 생기거나 바뀔 때만 올라가므로 트래픽은 최소화되지만 저장 공간은 최대로 쓰게 된다.

트래픽이 적거나 콘텐츠가 자주 바뀌지 않는 사이트는 푸시 CDN과 잘 맞는다. 콘텐츠를 주기적으로 다시 가져오지 않고 CDN에 한 번만 올려 두면 되기 때문이다.

### 풀 CDN

풀 CDN은 첫 사용자가 콘텐츠를 요청할 때 서버에서 새 콘텐츠를 가져온다. 콘텐츠는 내 서버에 그대로 두고 URL만 CDN을 가리키도록 바꾼다. 그래서 콘텐츠가 CDN에 캐시되기 전까지는 요청이 느리다.

콘텐츠를 얼마나 오래 캐시할지는 [TTL(time-to-live)](https://en.wikipedia.org/wiki/Time_to_live)이 정한다. 풀 CDN은 CDN의 저장 공간을 최소화하지만, 파일이 실제로 바뀌기 전에 만료되어 다시 가져오게 되면 불필요한 트래픽이 생길 수 있다.

트래픽이 많은 사이트는 풀 CDN과 잘 맞는다. 최근에 요청된 콘텐츠만 CDN에 남으므로 트래픽이 더 고르게 분산된다.

### 단점: CDN

* 트래픽에 따라 CDN 비용이 클 수 있다. 다만 CDN을 쓰지 않을 때 드는 추가 비용과 함께 따져 봐야 한다.
* TTL이 만료되기 전에 콘텐츠가 갱신되면 오래된 콘텐츠를 제공할 수 있다.
* 정적 콘텐츠의 URL을 CDN을 가리키도록 바꿔야 한다.

### 출처 및 더 읽을거리

* [Globally distributed content delivery](https://figshare.com/articles/Globally_distributed_content_delivery/6605972)
* [The differences between push and pull CDNs](https://www.geeksforgeeks.org/system-design/pull-cdn-vs-push-cdn/)
* [Wikipedia](https://en.wikipedia.org/wiki/Content_delivery_network)

## 로드 밸런서

<p align="center">
  <img src="images/h81n9iK.png">
  <br/>
  <i><a href=http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html>출처: Scalable system design patterns</a></i>
</p>

로드 밸런서는 들어오는 클라이언트 요청을 애플리케이션 서버나 데이터베이스 같은 컴퓨팅 자원에 나눠 준다. 어느 경우든 로드 밸런서는 컴퓨팅 자원의 응답을 알맞은 클라이언트에게 돌려준다. 로드 밸런서는 다음에 효과적이다:

* 상태가 나쁜 서버로 요청이 가지 않게 막기
* 자원에 과부하가 걸리지 않게 막기
* 단일 장애 지점(single point of failure) 없애기

로드 밸런서는 하드웨어(비싸다)로 구현할 수도 있고, HAProxy 같은 소프트웨어로 구현할 수도 있다.

다음과 같은 이점도 있다:

* **SSL 종료**(SSL termination) - 들어오는 요청을 복호화하고 서버 응답을 암호화해, 비용이 클 수 있는 이 작업을 백엔드 서버가 하지 않아도 되게 한다
    * 서버마다 [X.509 인증서](https://en.wikipedia.org/wiki/X.509)를 설치할 필요가 없어진다
* **세션 지속성**(session persistence) - 웹 앱이 세션을 추적하지 않는 경우, 쿠키를 발급해 특정 클라이언트의 요청을 같은 인스턴스로 보낸다

장애에 대비해 로드 밸런서를 여러 대 두는 것이 일반적이며, [액티브-패시브](#액티브-패시브) 또는 [액티브-액티브](#액티브-액티브) 방식으로 구성한다.

로드 밸런서는 다음과 같은 여러 기준으로 트래픽을 라우팅할 수 있다:

* 무작위
* 부하가 가장 적은 곳
* 세션/쿠키
* [라운드 로빈 또는 가중 라운드 로빈](https://www.g33kinfo.com/info/round-robin-vs-weighted-round-robin-lb)
* [4계층](#4계층-로드-밸런싱)
* [7계층](#7계층-로드-밸런싱)

### 4계층 로드 밸런싱

4계층 로드 밸런서는 [전송 계층](#통신)의 정보를 보고 요청을 어떻게 분배할지 정한다. 보통 헤더의 출발지·목적지 IP 주소와 포트를 보며, 패킷의 내용은 보지 않는다. 4계층 로드 밸런서는 [네트워크 주소 변환(NAT)](https://web.archive.org/web/20240117134735/https://www.nginx.com/resources/glossary/layer-4-load-balancing/)을 수행하며 업스트림 서버와 네트워크 패킷을 주고받는다.

### 7계층 로드 밸런싱

7계층 로드 밸런서는 [애플리케이션 계층](#통신)을 보고 요청을 어떻게 분배할지 정한다. 헤더, 메시지, 쿠키의 내용까지 볼 수 있다. 7계층 로드 밸런서는 네트워크 트래픽을 종료하고 메시지를 읽어 로드 밸런싱 결정을 내린 뒤, 선택한 서버로 연결을 연다. 예를 들어 동영상 트래픽은 동영상을 호스팅하는 서버로 보내고, 더 민감한 사용자 결제 트래픽은 보안을 강화한 서버로 보낼 수 있다.

4계층 로드 밸런싱은 유연성을 포기하는 대신 7계층보다 시간과 컴퓨팅 자원이 덜 든다. 다만 최신 범용 하드웨어에서는 성능 차이가 미미할 수 있다.

### 수평 확장

로드 밸런서는 수평 확장에도 도움이 되어 성능과 가용성을 높인다. 범용 장비를 늘려 수평으로 확장하는 편이, 단일 서버를 더 비싼 하드웨어로 키우는 **수직 확장**보다 비용 효율이 좋고 가용성도 높다. 또한 특수한 엔터프라이즈 시스템보다 범용 하드웨어를 다룰 인재를 구하기가 더 쉽다.

#### 단점: 수평 확장

* 수평 확장은 복잡도를 높이고 서버 복제가 필요하다
    * 서버는 무상태(stateless)여야 한다. 세션이나 프로필 사진처럼 사용자와 관련된 데이터를 담고 있으면 안 된다
    * 세션은 [데이터베이스](#데이터베이스)(SQL, NoSQL)나 영속적인 [캐시](#캐시)(Redis, Memcached) 같은 중앙 데이터 저장소에 둘 수 있다
* 업스트림 서버가 늘어나면 캐시나 데이터베이스 같은 다운스트림 서버가 더 많은 동시 연결을 처리해야 한다

### 단점: 로드 밸런서

* 자원이 부족하거나 설정이 잘못되면 로드 밸런서 자체가 성능 병목이 될 수 있다.
* 단일 장애 지점을 없애려고 로드 밸런서를 도입하면 복잡도가 높아진다.
* 로드 밸런서가 하나뿐이면 그 자체가 단일 장애 지점이 되고, 여러 대를 두면 복잡도가 더 높아진다.

### 출처 및 더 읽을거리

* [NGINX architecture](https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/)
* [HAProxy architecture guide](http://www.haproxy.org/download/1.2/doc/architecture.txt)
* [Scalability](https://web.archive.org/web/20220530193911/https://www.lecloud.net/post/7295452622/scalability-for-dummies-part-1-clones)
* [Wikipedia](https://en.wikipedia.org/wiki/Load_balancing_(computing))
* [Layer 4 load balancing](https://www.nginx.com/resources/glossary/layer-4-load-balancing/)
* [Layer 7 load balancing](https://www.nginx.com/resources/glossary/layer-7-load-balancing/)
* [ELB listener config](http://docs.aws.amazon.com/elasticloadbalancing/latest/classic/elb-listener-config.html)

## 리버스 프록시(웹 서버)

<p align="center">
  <img src="images/n41Azff.png">
  <br/>
  <i><a href=https://upload.wikimedia.org/wikipedia/commons/6/67/Reverse_proxy_h2g2bob.svg>출처: Wikipedia</a></i>
  <br/>
</p>

리버스 프록시(reverse proxy)는 내부 서비스를 한데 모아 외부에 통합된 인터페이스를 제공하는 웹 서버다. 클라이언트의 요청은 이를 처리할 수 있는 서버로 전달되고, 리버스 프록시는 그 서버의 응답을 클라이언트에게 돌려준다.

다음과 같은 이점도 있다:

* **보안 강화** - 백엔드 서버 정보를 숨기고, IP를 차단 목록에 올리고, 클라이언트당 연결 수를 제한한다
* **확장성과 유연성 향상** - 클라이언트에게는 리버스 프록시의 IP만 보이므로 서버를 늘리거나 설정을 바꾸기 쉽다
* **SSL 종료** - 들어오는 요청을 복호화하고 서버 응답을 암호화해, 비용이 클 수 있는 이 작업을 백엔드 서버가 하지 않아도 되게 한다
    * 서버마다 [X.509 인증서](https://en.wikipedia.org/wiki/X.509)를 설치할 필요가 없어진다
* **압축** - 서버 응답을 압축한다
* **캐싱** - 캐시된 요청에 대한 응답을 돌려준다
* **정적 콘텐츠** - 정적 콘텐츠를 직접 제공한다
    * HTML/CSS/JS
    * 사진
    * 동영상
    * 기타

### 로드 밸런서 vs 리버스 프록시

* 로드 밸런서는 서버가 여러 대일 때 유용하다. 보통 같은 기능을 하는 서버 묶음으로 트래픽을 보낸다.
* 리버스 프록시는 웹 서버나 애플리케이션 서버가 하나뿐이어도 앞 절에서 설명한 이점을 누릴 수 있어 유용하다.
* NGINX나 HAProxy 같은 도구는 7계층 리버스 프록시와 로드 밸런싱을 모두 지원한다.

### 단점: 리버스 프록시

* 리버스 프록시를 도입하면 복잡도가 높아진다.
* 리버스 프록시가 하나뿐이면 단일 장애 지점이 되고, 여러 대를 두면(즉 [장애 조치](https://en.wikipedia.org/wiki/Failover)) 복잡도가 더 높아진다.

### 출처 및 더 읽을거리

* [Reverse proxy vs load balancer](https://www.nginx.com/resources/glossary/reverse-proxy-vs-load-balancer/)
* [NGINX architecture](https://www.nginx.com/blog/inside-nginx-how-we-designed-for-performance-scale/)
* [HAProxy architecture guide](http://www.haproxy.org/download/1.2/doc/architecture.txt)
* [Wikipedia](https://en.wikipedia.org/wiki/Reverse_proxy)

## 애플리케이션 계층

<p align="center">
  <img src="images/yB5SYwm.png">
  <br/>
  <i><a href=http://lethain.com/introduction-to-architecting-systems-for-scale/#platform_layer>출처: Intro to architecting systems for scale</a></i>
</p>

웹 계층과 애플리케이션 계층(플랫폼 계층이라고도 한다)을 분리하면 두 계층을 따로 확장하고 설정할 수 있다. 새 API를 추가할 때 웹 서버를 늘리지 않고 애플리케이션 서버만 늘리면 된다. **단일 책임 원칙**(single responsibility principle)은 작고 자율적인 서비스들이 함께 동작하는 구조를 지향한다. 작은 서비스를 맡은 작은 팀은 빠른 성장에 더 과감하게 대비할 수 있다.

애플리케이션 계층의 워커는 [비동기 처리](#비동기-처리)를 가능하게 하는 데도 도움이 된다.

### 마이크로서비스

이 논의와 관련된 것이 [마이크로서비스](https://en.wikipedia.org/wiki/Microservices)(microservices)다. 마이크로서비스는 독립적으로 배포할 수 있는 작은 모듈형 서비스들의 묶음이라고 할 수 있다. 각 서비스는 고유한 프로세스로 실행되고, 잘 정의된 가벼운 방식으로 통신하며 비즈니스 목표를 달성한다. <sup><a href=https://smartbear.com/learn/api-design/what-are-microservices>1</a></sup>

예를 들어 Pinterest라면 사용자 프로필, 팔로워, 피드, 검색, 사진 업로드 같은 마이크로서비스를 둘 수 있다.

### 서비스 디스커버리

[Consul](https://www.consul.io/docs/index.html), [Etcd](https://coreos.com/etcd/docs/latest), [Zookeeper](http://www.slideshare.net/sauravhaloi/introduction-to-apache-zookeeper) 같은 시스템은 등록된 이름, 주소, 포트를 추적해 서비스끼리 서로 찾을 수 있게 돕는다. [헬스 체크](https://www.consul.io/intro/getting-started/checks.html)는 서비스가 정상인지 확인하는 데 쓰이며, 보통 [HTTP](#하이퍼텍스트-전송-프로토콜http) 엔드포인트로 수행한다. Consul과 Etcd는 모두 [키-값 저장소](#키-값-저장소)를 내장하고 있어 설정 값이나 다른 공유 데이터를 저장하기에 좋다.

### 단점: 애플리케이션 계층

* 느슨하게 결합된 서비스로 애플리케이션 계층을 구성하려면 아키텍처, 운영, 프로세스 측면에서 (모놀리식 시스템과는) 다른 접근이 필요하다.
* 마이크로서비스는 배포와 운영 면에서 복잡도를 높일 수 있다.

### 출처 및 더 읽을거리

* [Intro to architecting systems for scale](http://lethain.com/introduction-to-architecting-systems-for-scale)
* [Crack the system design interview](http://www.puncsky.com/blog/2016-02-13-crack-the-system-design-interview)
* [Service oriented architecture](https://en.wikipedia.org/wiki/Service-oriented_architecture)
* [Introduction to Zookeeper](http://www.slideshare.net/sauravhaloi/introduction-to-apache-zookeeper)
* [Here's what you need to know about building microservices](https://cloudncode.wordpress.com/2016/07/22/msa-getting-started/)

## 데이터베이스

<p align="center">
  <img src="images/Xkm5CXz.png">
  <br/>
  <i><a href=https://www.youtube.com/watch?v=kKjm4ehYiMs>출처: Scaling up to your first 10 million users</a></i>
</p>

### 관계형 데이터베이스 관리 시스템(RDBMS)

SQL 같은 관계형 데이터베이스는 테이블로 조직된 데이터 항목의 모음이다.

**ACID**는 관계형 데이터베이스 [트랜잭션](https://en.wikipedia.org/wiki/Database_transaction)이 갖춰야 할 속성의 모음이다.

* **원자성**(atomicity) - 각 트랜잭션은 전부 수행되거나 전혀 수행되지 않는다
* **일관성** - 어떤 트랜잭션이든 데이터베이스를 유효한 상태에서 다른 유효한 상태로 옮긴다
* **격리성**(isolation) - 트랜잭션을 동시에 실행해도 순차적으로 실행한 것과 결과가 같다
* **지속성**(durability) - 한번 커밋된 트랜잭션은 그대로 유지된다

관계형 데이터베이스를 확장하는 기법은 여러 가지다. **마스터-슬레이브 복제**, **마스터-마스터 복제**, **페더레이션**(federation), **샤딩**, **비정규화**(denormalization), **SQL 튜닝**이 있다.

#### 마스터-슬레이브 복제

마스터는 읽기와 쓰기를 처리하고, 쓰기를 하나 이상의 슬레이브에 복제한다. 슬레이브는 읽기만 처리한다. 슬레이브가 다른 슬레이브로 트리 형태로 복제할 수도 있다. 마스터가 오프라인이 되면, 슬레이브가 마스터로 승격되거나 새 마스터가 준비될 때까지 시스템은 읽기 전용 모드로 계속 동작할 수 있다.

<p align="center">
  <img src="images/C9ioGtn.png">
  <br/>
  <i><a href=http://www.slideshare.net/jboner/scalability-availability-stability-patterns/>출처: Scalability, availability, stability, patterns</a></i>
</p>

##### 단점: 마스터-슬레이브 복제

* 슬레이브를 마스터로 승격하려면 추가 로직이 필요하다.
* 마스터-슬레이브와 마스터-마스터 **모두**에 해당하는 내용은 [단점: 복제](#단점-복제)를 참고하라.

#### 마스터-마스터 복제

두 마스터 모두 읽기와 쓰기를 처리하며, 쓰기는 서로 조율한다. 마스터 하나가 죽어도 시스템은 읽기와 쓰기를 모두 계속 처리할 수 있다.

<p align="center">
  <img src="images/krAHLGg.png">
  <br/>
  <i><a href=http://www.slideshare.net/jboner/scalability-availability-stability-patterns/>출처: Scalability, availability, stability, patterns</a></i>
</p>

##### 단점: 마스터-마스터 복제

* 어디에 쓸지 정하려면 로드 밸런서를 두거나 애플리케이션 로직을 고쳐야 한다.
* 대부분의 마스터-마스터 시스템은 일관성이 느슨하거나(ACID 위반), 동기화 때문에 쓰기 지연 시간이 늘어난다.
* 쓰기 노드가 늘고 지연 시간이 커질수록 충돌 해결이 더 중요해진다.
* 마스터-슬레이브와 마스터-마스터 **모두**에 해당하는 내용은 [단점: 복제](#단점-복제)를 참고하라.

##### 단점: 복제

* 새로 쓴 데이터가 다른 노드로 복제되기 전에 마스터가 죽으면 데이터를 잃을 수 있다.
* 쓰기는 읽기 복제본(read replica)에서 다시 실행된다. 쓰기가 많으면 읽기 복제본이 쓰기를 다시 실행하느라 바빠져 읽기를 그만큼 처리하지 못한다.
* 읽기 슬레이브가 많을수록 복제할 양이 늘어 복제 지연이 커진다.
* 일부 시스템에서는 마스터에 쓸 때 여러 스레드로 병렬 쓰기를 하지만, 읽기 복제본은 단일 스레드로 순차적으로만 쓸 수 있다.
* 복제는 하드웨어를 더 늘리고 복잡도를 높인다.

##### 출처 및 더 읽을거리: 복제

* [Scalability, availability, stability, patterns](http://www.slideshare.net/jboner/scalability-availability-stability-patterns/)
* [Multi-master replication](https://en.wikipedia.org/wiki/Multi-master_replication)

#### 페더레이션

<p align="center">
  <img src="images/U3qV33e.png">
  <br/>
  <i><a href=https://www.youtube.com/watch?v=kKjm4ehYiMs>출처: Scaling up to your first 10 million users</a></i>
</p>

페더레이션(기능별 분할이라고도 한다)은 데이터베이스를 기능별로 나눈다. 예를 들어 하나의 거대한 데이터베이스 대신 **포럼**, **사용자**, **상품** 데이터베이스 세 개를 둘 수 있다. 그러면 데이터베이스마다 읽기·쓰기 트래픽이 줄어 복제 지연도 줄어든다. 데이터베이스가 작아지면 메모리에 올릴 수 있는 데이터가 늘고, 캐시 지역성이 좋아져 캐시 적중이 늘어난다. 쓰기를 직렬화하는 단일 중앙 마스터가 없으므로 병렬로 쓸 수 있어 처리량이 늘어난다.

##### 단점: 페더레이션

* 스키마에 거대한 기능이나 테이블이 필요하다면 페더레이션은 효과적이지 않다.
* 어느 데이터베이스에서 읽고 쓸지 정하도록 애플리케이션 로직을 고쳐야 한다.
* 두 데이터베이스의 데이터를 조인하려면 [서버 링크](http://stackoverflow.com/questions/5145637/querying-data-by-joining-two-tables-in-two-database-on-different-servers)를 써야 해서 더 복잡하다.
* 페더레이션은 하드웨어를 더 늘리고 복잡도를 높인다.

##### 출처 및 더 읽을거리: 페더레이션

* [Scaling up to your first 10 million users](https://www.youtube.com/watch?v=kKjm4ehYiMs)

#### 샤딩

<p align="center">
  <img src="images/wU8x5Id.png">
  <br/>
  <i><a href=http://www.slideshare.net/jboner/scalability-availability-stability-patterns/>출처: Scalability, availability, stability, patterns</a></i>
</p>

샤딩은 데이터를 여러 데이터베이스에 나눠 각 데이터베이스가 데이터의 일부만 관리하게 한다. 사용자 데이터베이스를 예로 들면, 사용자가 늘어날수록 클러스터에 샤드(shard)를 더 추가한다.

[페더레이션](#페더레이션)의 장점과 마찬가지로, 샤딩을 하면 읽기·쓰기 트래픽과 복제가 줄고 캐시 적중이 늘어난다. 인덱스 크기도 줄어 대개 쿼리가 빨라지고 성능이 좋아진다. 샤드 하나가 죽어도 나머지 샤드는 계속 동작하지만, 데이터 손실을 막으려면 어떤 형태로든 복제를 더해야 한다. 페더레이션처럼 쓰기를 직렬화하는 단일 중앙 마스터가 없으므로 병렬로 쓸 수 있어 처리량이 늘어난다.

사용자 테이블을 샤딩하는 흔한 방법은 사용자 성(last name)의 첫 글자나 지리적 위치를 기준으로 나누는 것이다.

##### 단점: 샤딩

* 샤드를 다루도록 애플리케이션 로직을 고쳐야 하며, 그 때문에 SQL 쿼리가 복잡해질 수 있다.
* 데이터가 특정 샤드에 쏠릴 수 있다. 예를 들어 헤비 유저들이 한 샤드에 몰리면 그 샤드에만 부하가 커진다.
    * 리밸런싱은 복잡도를 더 높인다. [일관된 해싱](http://www.paperplanes.de/2011/12/9/the-magic-of-consistent-hashing.html)(consistent hashing) 기반의 샤딩 함수를 쓰면 옮겨야 할 데이터 양을 줄일 수 있다.
* 여러 샤드에 걸친 데이터를 조인하기가 더 복잡하다.
* 샤딩은 하드웨어를 더 늘리고 복잡도를 높인다.

##### 출처 및 더 읽을거리: 샤딩

* [The coming of the shard](http://highscalability.com/blog/2009/8/6/an-unorthodox-approach-to-database-design-the-coming-of-the.html)
* [Shard database architecture](https://en.wikipedia.org/wiki/Shard_(database_architecture))
* [Consistent hashing](http://www.paperplanes.de/2011/12/9/the-magic-of-consistent-hashing.html)

#### 비정규화

비정규화는 쓰기 성능을 조금 희생해 읽기 성능을 높이려는 기법이다. 비용이 큰 조인을 피하려고 같은 데이터를 여러 테이블에 중복해서 쓴다. [PostgreSQL](https://en.wikipedia.org/wiki/PostgreSQL)이나 Oracle 같은 일부 RDBMS는 [구체화된 뷰](https://en.wikipedia.org/wiki/Materialized_view)(materialized view)를 지원해, 중복 정보를 저장하고 중복 사본의 일관성을 유지하는 일을 대신 처리한다.

[페더레이션](#페더레이션)이나 [샤딩](#샤딩) 같은 기법으로 데이터가 분산되면, 데이터 센터를 넘나드는 조인을 관리하느라 복잡도가 더 높아진다. 비정규화를 하면 이런 복잡한 조인이 필요 없어질 수 있다.

대부분의 시스템에서 읽기는 쓰기보다 훨씬 많아서 100:1, 심하면 1000:1에 이른다. 복잡한 데이터베이스 조인이 필요한 읽기는 디스크 작업에 상당한 시간을 써서 비용이 매우 클 수 있다.

##### 단점: 비정규화

* 데이터가 중복된다.
* 제약 조건으로 중복 사본을 동기화할 수 있지만, 그만큼 데이터베이스 설계가 복잡해진다.
* 쓰기 부하가 큰 상황에서는 비정규화한 데이터베이스가 정규화한 데이터베이스보다 성능이 나쁠 수 있다.

###### 출처 및 더 읽을거리: 비정규화

* [Denormalization](https://en.wikipedia.org/wiki/Denormalization)

#### SQL 튜닝

SQL 튜닝은 범위가 넓은 주제이며, 참고할 만한 [책](https://www.amazon.com/s/ref=nb_sb_noss_2?url=search-alias%3Daps&field-keywords=sql+tuning)도 많이 나와 있다.

병목을 재현하고 찾아내려면 **벤치마크**와 **프로파일링**이 중요하다.

* **벤치마크** - [ab](http://httpd.apache.org/docs/2.2/programs/ab.html) 같은 도구로 고부하 상황을 재현한다.
* **프로파일링** - [슬로우 쿼리 로그](http://dev.mysql.com/doc/refman/5.7/en/slow-query-log.html) 같은 도구를 켜서 성능 문제를 추적한다.

벤치마크와 프로파일링을 해 보면 다음과 같은 최적화가 필요하다는 것을 알게 될 수 있다.

##### 스키마 다듬기

* MySQL은 빠른 접근을 위해 연속된 블록으로 디스크에 기록한다.
* 고정 길이 필드에는 `VARCHAR` 대신 `CHAR`를 써라.
    * `CHAR`는 빠른 임의 접근이 가능하지만, `VARCHAR`는 다음 문자열로 넘어가기 전에 현재 문자열의 끝을 찾아야 한다.
* 블로그 글처럼 큰 텍스트에는 `TEXT`를 써라. `TEXT`는 불리언 검색도 지원한다. `TEXT` 필드를 쓰면 텍스트 블록의 위치를 가리키는 포인터가 디스크에 저장된다.
* 2^32(약 40억)까지의 큰 수에는 `INT`를 써라.
* 통화에는 부동소수점 표현 오류를 피하도록 `DECIMAL`을 써라.
* 큰 `BLOBS`를 저장하지 말고, 대신 객체를 가져올 위치를 저장하라.
* `VARCHAR(255)`는 8비트 숫자로 셀 수 있는 최대 문자 수여서, 일부 RDBMS에서는 1바이트를 최대한 활용하는 경우가 많다.
* 가능한 곳에는 `NOT NULL` 제약 조건을 걸어 [검색 성능을 높여라](http://stackoverflow.com/questions/1017239/how-do-null-values-affect-performance-in-a-database-search).

##### 좋은 인덱스 사용하기

* 쿼리에 쓰는 열(`SELECT`, `GROUP BY`, `ORDER BY`, `JOIN`)은 인덱스를 걸면 빨라질 수 있다.
* 인덱스는 보통 자가 균형 [B-트리](https://en.wikipedia.org/wiki/B-tree)로 표현되며, 데이터를 정렬된 상태로 유지하고 검색, 순차 접근, 삽입, 삭제를 로그 시간에 처리한다.
* 인덱스를 두면 데이터를 메모리에 둘 수 있지만 공간이 더 필요하다.
* 인덱스도 갱신해야 하므로 쓰기가 느려질 수 있다.
* 대량의 데이터를 적재할 때는 인덱스를 끄고 데이터를 적재한 뒤 인덱스를 다시 만드는 편이 빠를 수 있다.

##### 비용이 큰 조인 피하기

* 성능상 필요한 곳은 [비정규화하라](#비정규화).

##### 테이블 파티셔닝하기

* 자주 접근하는 부분(핫스팟)을 별도 테이블로 떼어 내 메모리에 남아 있기 쉽게 하라.

##### 쿼리 캐시 튜닝하기

* 경우에 따라 [쿼리 캐시](https://dev.mysql.com/doc/refman/5.7/en/query-cache.html)가 오히려 [성능 문제](https://www.percona.com/blog/2016/10/12/mysql-5-7-performance-tuning-immediately-after-installation/)를 일으킬 수 있다.

##### 출처 및 더 읽을거리: SQL 튜닝

* [Tips for optimizing MySQL queries](http://aiddroid.com/10-tips-optimizing-mysql-queries-dont-suck/)
* [Is there a good reason i see VARCHAR(255) used so often?](http://stackoverflow.com/questions/1217466/is-there-a-good-reason-i-see-varchar255-used-so-often-as-opposed-to-another-l)
* [How do null values affect performance?](http://stackoverflow.com/questions/1017239/how-do-null-values-affect-performance-in-a-database-search)
* [Slow query log](http://dev.mysql.com/doc/refman/5.7/en/slow-query-log.html)

### NoSQL

NoSQL은 **키-값 저장소**, **문서 저장소**, **와이드 컬럼 저장소**, **그래프 데이터베이스** 형태로 표현되는 데이터 항목의 모음이다. 데이터는 비정규화되어 있고, 조인은 보통 애플리케이션 코드에서 한다. 대부분의 NoSQL 저장소는 진정한 ACID 트랜잭션을 지원하지 않으며 [최종적 일관성](#최종적-일관성)을 택한다.

NoSQL 데이터베이스의 속성은 흔히 **BASE**로 설명한다. [CAP 정리](#cap-정리)에 비춰 보면 BASE는 일관성보다 가용성을 택한다.

* **기본적 가용성**(basically available) - 시스템은 가용성을 보장한다.
* **소프트 상태**(soft state) - 입력이 없어도 시스템의 상태는 시간이 지나며 바뀔 수 있다.
* **최종적 일관성** - 일정 기간 입력이 없으면 그동안 시스템은 일관된 상태가 된다.

[SQL 또는 NoSQL](#sql-또는-nosql) 중 무엇을 고를지와 함께, 어떤 종류의 NoSQL 데이터베이스가 내 유스 케이스에 가장 잘 맞는지 이해해 두면 좋다. 다음 절에서는 **키-값 저장소**, **문서 저장소**, **와이드 컬럼 저장소**, **그래프 데이터베이스**를 살펴본다.

#### 키-값 저장소

> 추상화: 해시 테이블

키-값 저장소는 보통 O(1) 읽기와 쓰기를 지원하며, 메모리나 SSD를 기반으로 하는 경우가 많다. 데이터 저장소는 키를 [사전순](https://en.wikipedia.org/wiki/Lexicographical_order)으로 유지할 수 있어 키 범위를 효율적으로 조회할 수 있다. 키-값 저장소는 값과 함께 메타데이터를 저장할 수도 있다.

키-값 저장소는 성능이 높아 단순한 데이터 모델이나 인메모리 캐시 계층처럼 빠르게 바뀌는 데이터에 자주 쓰인다. 제공하는 연산이 제한적이므로, 다른 연산이 필요하면 그 복잡도가 애플리케이션 계층으로 넘어간다.

키-값 저장소는 문서 저장소나, 경우에 따라 그래프 데이터베이스 같은 더 복잡한 시스템의 기반이 된다.

##### 출처 및 더 읽을거리: 키-값 저장소

* [Key-value database](https://en.wikipedia.org/wiki/Key-value_database)
* [Disadvantages of key-value stores](http://stackoverflow.com/questions/4056093/what-are-the-disadvantages-of-using-a-key-value-table-over-nullable-columns-or)
* [Redis architecture](http://qnimate.com/overview-of-redis-architecture/)
* [Memcached architecture](https://adayinthelifeof.nl/2011/02/06/memcache-internals/)

#### 문서 저장소

> 추상화: 값으로 문서를 저장하는 키-값 저장소

문서 저장소는 문서(XML, JSON, 바이너리 등)를 중심으로 하며, 문서 하나에 한 객체의 모든 정보를 저장한다. 문서 저장소는 문서 자체의 내부 구조를 기준으로 질의할 수 있는 API나 쿼리 언어를 제공한다. *참고로 많은 키-값 저장소가 값의 메타데이터를 다루는 기능을 갖추고 있어 두 저장소 유형의 경계가 흐려지고 있다.*

내부 구현에 따라 문서는 컬렉션, 태그, 메타데이터, 디렉터리 단위로 조직된다. 문서를 조직하거나 묶을 수는 있지만, 문서마다 필드가 완전히 다를 수 있다.

[MongoDB](https://www.mongodb.com/mongodb-architecture)나 [CouchDB](https://blog.couchdb.org/2016/08/01/couchdb-2-0-architecture/) 같은 일부 문서 저장소는 복잡한 쿼리를 위한 SQL 비슷한 언어도 제공한다. [DynamoDB](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf)는 키-값과 문서를 모두 지원한다.

문서 저장소는 유연성이 높아 가끔 바뀌는 데이터를 다룰 때 자주 쓰인다.

##### 출처 및 더 읽을거리: 문서 저장소

* [Document-oriented database](https://en.wikipedia.org/wiki/Document-oriented_database)
* [MongoDB architecture](https://www.mongodb.com/mongodb-architecture)
* [CouchDB architecture](https://blog.couchdb.org/2016/08/01/couchdb-2-0-architecture/)
* [Elasticsearch architecture](https://www.elastic.co/blog/found-elasticsearch-from-the-bottom-up)

#### 와이드 컬럼 저장소

<p align="center">
  <img src="images/n16iOGk.png">
  <br/>
  <i><a href=http://blog.grio.com/2015/11/sql-nosql-a-brief-history.html>출처: SQL & NoSQL, a brief history</a></i>
</p>

> 추상화: 중첩 맵 `ColumnFamily<RowKey, Columns<ColKey, Value, Timestamp>>`

와이드 컬럼 저장소의 기본 데이터 단위는 컬럼(이름/값 쌍)이다. 컬럼은 컬럼 패밀리(SQL 테이블과 비슷하다)로 묶을 수 있다. 슈퍼 컬럼 패밀리는 컬럼 패밀리를 다시 묶는다. 각 컬럼은 로우 키로 따로 접근할 수 있으며, 같은 로우 키를 가진 컬럼들이 하나의 로우를 이룬다. 각 값에는 버전 관리와 충돌 해결을 위한 타임스탬프가 들어 있다.

Google은 최초의 와이드 컬럼 저장소로 [Bigtable](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/chang06bigtable.pdf)을 내놓았고, 이는 Hadoop 생태계에서 자주 쓰이는 오픈 소스 [HBase](https://www.edureka.co/blog/hbase-architecture/)와 Facebook의 [Cassandra](http://docs.datastax.com/en/cassandra/3.0/cassandra/architecture/archIntro.html)에 영향을 주었다. BigTable, HBase, Cassandra 같은 저장소는 키를 사전순으로 유지해 원하는 키 범위를 효율적으로 조회할 수 있다.

와이드 컬럼 저장소는 가용성과 확장성이 높다. 아주 큰 데이터셋에 자주 쓰인다.

##### 출처 및 더 읽을거리: 와이드 컬럼 저장소

* [SQL & NoSQL, a brief history](http://blog.grio.com/2015/11/sql-nosql-a-brief-history.html)
* [Bigtable architecture](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/chang06bigtable.pdf)
* [HBase architecture](https://www.edureka.co/blog/hbase-architecture/)
* [Cassandra architecture](http://docs.datastax.com/en/cassandra/3.0/cassandra/architecture/archIntro.html)

#### 그래프 데이터베이스

<p align="center">
  <img src="images/fNcl65g.png">
  <br/>
  <i><a href=https://en.wikipedia.org/wiki/File:GraphDatabase_PropertyGraph.png>출처: Graph database</a></i>
</p>

> 추상화: 그래프

그래프 데이터베이스에서 각 노드는 레코드이고, 각 간선(arc)은 두 노드 사이의 관계다. 그래프 데이터베이스는 외래 키가 많거나 다대다 관계가 많은 복잡한 관계를 표현하도록 최적화되어 있다.

그래프 데이터베이스는 소셜 네트워크처럼 관계가 복잡한 데이터 모델에서 높은 성능을 낸다. 비교적 새로운 기술이라 아직 널리 쓰이지 않아 개발 도구나 자료를 찾기가 더 어려울 수 있다. 많은 그래프 데이터베이스는 [REST API](#restrepresentational-state-transfer)로만 접근할 수 있다.

##### 출처 및 더 읽을거리: 그래프

* [Graph database](https://en.wikipedia.org/wiki/Graph_database)
* [Neo4j](https://neo4j.com/)
* [FlockDB](https://blog.twitter.com/2010/introducing-flockdb)

#### 출처 및 더 읽을거리: NoSQL

* [Explanation of base terminology](http://stackoverflow.com/questions/3342497/explanation-of-base-terminology)
* [NoSQL databases a survey and decision guidance](https://medium.com/baqend-blog/nosql-databases-a-survey-and-decision-guidance-ea7823a822d#.wskogqenq)
* [Scalability](https://web.archive.org/web/20220602114024/https://www.lecloud.net/post/7994751381/scalability-for-dummies-part-2-database)
* [Introduction to NoSQL](https://www.youtube.com/watch?v=qI_g07C_Q5I)
* [NoSQL patterns](http://horicky.blogspot.com/2009/11/nosql-patterns.html)

### SQL 또는 NoSQL

<p align="center">
  <img src="images/wXGqG5f.png">
  <br/>
  <i><a href=https://www.infoq.com/articles/Transition-RDBMS-NoSQL/>출처: Transitioning from RDBMS to NoSQL</a></i>
</p>

**SQL**을 고르는 이유:

* 정형 데이터
* 엄격한 스키마
* 관계형 데이터
* 복잡한 조인이 필요함
* 트랜잭션
* 확장 패턴이 명확함
* 더 성숙함: 개발자, 커뮤니티, 코드, 도구 등
* 인덱스 조회가 매우 빠름

**NoSQL**을 고르는 이유:

* 반정형 데이터
* 동적이거나 유연한 스키마
* 비관계형 데이터
* 복잡한 조인이 필요 없음
* 수 TB(또는 PB)의 데이터를 저장함
* 데이터 처리량이 매우 많은 워크로드
* 매우 높은 IOPS 처리량

NoSQL에 잘 맞는 데이터 예:

* 클릭스트림과 로그 데이터의 빠른 수집
* 리더보드나 점수 데이터
* 장바구니 같은 임시 데이터
* 자주 접근하는('핫') 테이블
* 메타데이터/조회 테이블

##### 출처 및 더 읽을거리: SQL 또는 NoSQL

* [Scaling up to your first 10 million users](https://www.youtube.com/watch?v=kKjm4ehYiMs)
* [SQL vs NoSQL differences](https://www.sitepoint.com/sql-vs-nosql-differences/)

## 캐시

<p align="center">
  <img src="images/Q6z24La.png">
  <br/>
  <i><a href=http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html>출처: Scalable system design patterns</a></i>
</p>

캐싱은 페이지 로드 시간을 줄이고 서버와 데이터베이스의 부하를 낮춘다. 이 모델에서 디스패처는 실제 실행을 아끼기 위해, 먼저 같은 요청이 전에 있었는지 찾아보고 이전 결과를 돌려주려 한다.

데이터베이스는 읽기와 쓰기가 파티션에 고르게 분산될 때 유리한 경우가 많다. 인기 있는 항목이 분포를 한쪽으로 쏠리게 하면 병목이 생긴다. 데이터베이스 앞에 캐시를 두면 고르지 않은 부하와 갑작스러운 트래픽 급증을 흡수하는 데 도움이 된다.

### 클라이언트 캐싱

캐시는 클라이언트 쪽(OS나 브라우저), [서버 쪽](#리버스-프록시웹-서버), 또는 별도의 캐시 계층에 둘 수 있다.

### CDN 캐싱

[CDN](#콘텐츠-전송-네트워크)도 캐시의 한 종류로 본다.

### 웹 서버 캐싱

[리버스 프록시](#리버스-프록시웹-서버)나 [Varnish](https://www.varnish-cache.org/) 같은 캐시는 정적·동적 콘텐츠를 직접 제공할 수 있다. 웹 서버도 요청을 캐시해, 애플리케이션 서버에 묻지 않고 응답을 돌려줄 수 있다.

### 데이터베이스 캐싱

데이터베이스는 보통 기본 설정에 일반적인 유스 케이스에 맞춘 어느 정도의 캐싱을 갖추고 있다. 이 설정을 특정 사용 패턴에 맞게 조정하면 성능을 더 끌어올릴 수 있다.

### 애플리케이션 캐싱

Memcached나 Redis 같은 인메모리 캐시는 애플리케이션과 데이터 저장소 사이에 놓인 키-값 저장소다. 데이터를 RAM에 두므로 디스크에 데이터를 저장하는 일반적인 데이터베이스보다 훨씬 빠르다. RAM은 디스크보다 용량이 한정되어 있으므로, [LRU(least recently used)](https://en.wikipedia.org/wiki/Cache_replacement_policies#Least_recently_used_(LRU)) 같은 [캐시 무효화](https://en.wikipedia.org/wiki/Cache_algorithms) 알고리즘으로 '콜드' 항목을 무효화하고 '핫' 데이터를 RAM에 남긴다.

Redis에는 다음과 같은 기능도 있다:

* 디스크 영속화 옵션
* 정렬된 집합(sorted set)이나 리스트 같은 내장 자료 구조

캐시할 수 있는 수준은 여러 가지이며, 크게 **데이터베이스 쿼리**와 **객체** 두 범주로 나뉜다:

* 로우 수준
* 쿼리 수준
* 완성된 직렬화 가능 객체
* 완전히 렌더링된 HTML

일반적으로 파일 기반 캐싱은 피하는 것이 좋다. 서버 복제와 오토스케일링을 어렵게 만들기 때문이다.

### 데이터베이스 쿼리 수준 캐싱

데이터베이스에 쿼리할 때마다 쿼리를 해시해 키로 삼고 결과를 캐시에 저장한다. 이 방식은 만료 문제를 겪는다:

* 복잡한 쿼리의 캐시된 결과는 지우기 어렵다
* 테이블 셀 하나처럼 데이터 일부가 바뀌면, 바뀐 셀을 포함할 수 있는 캐시된 쿼리를 모두 지워야 한다

### 객체 수준 캐싱

애플리케이션 코드에서 하듯 데이터를 객체로 바라보라. 애플리케이션이 데이터베이스의 데이터셋을 클래스 인스턴스나 자료 구조로 조립하게 하라:

* 바탕이 되는 데이터가 바뀌면 캐시에서 객체를 지운다
* 비동기 처리가 가능하다. 워커가 캐시된 최신 객체를 소비해 객체를 조립한다

캐시할 만한 것:

* 사용자 세션
* 완전히 렌더링된 웹 페이지
* 활동 스트림
* 사용자 그래프 데이터

### 캐시 갱신 시점

캐시에는 한정된 양의 데이터만 저장할 수 있으므로, 유스 케이스에 가장 잘 맞는 캐시 갱신 전략을 정해야 한다.

#### Cache-aside

<p align="center">
  <img src="images/ONjORqk.png">
  <br/>
  <i><a href=http://www.slideshare.net/tmatyashovsky/from-cache-to-in-memory-data-grid-introduction-to-hazelcast>출처: From cache to in-memory data grid</a></i>
</p>

저장소에서 읽고 쓰는 일은 애플리케이션이 책임진다. 캐시는 저장소와 직접 상호 작용하지 않는다. 애플리케이션은 다음을 수행한다:

* 캐시에서 항목을 찾고, 캐시 미스가 난다
* 데이터베이스에서 항목을 읽어 온다
* 항목을 캐시에 추가한다
* 항목을 돌려준다

```python
def get_user(self, user_id):
    user = cache.get("user.{0}", user_id)
    if user is None:
        user = db.query("SELECT * FROM users WHERE user_id = {0}", user_id)
        if user is not None:
            key = "user.{0}".format(user_id)
            cache.set(key, json.dumps(user))
    return user
```

[Memcached](https://memcached.org/)는 보통 이 방식으로 쓰인다.

캐시에 추가된 데이터는 이후 빠르게 읽힌다. Cache-aside는 지연 로딩(lazy loading)이라고도 한다. 요청된 데이터만 캐시하므로 요청되지 않은 데이터로 캐시가 채워지지 않는다.

##### 단점: Cache-aside

* 캐시 미스가 날 때마다 세 번 왕복하므로 눈에 띄는 지연이 생길 수 있다.
* 데이터베이스에서 데이터가 갱신되면 캐시의 데이터가 오래된 것이 될 수 있다. 캐시 항목을 강제로 갱신하는 TTL을 설정하거나 Write-through를 쓰면 이 문제를 줄일 수 있다.
* 노드가 죽으면 비어 있는 새 노드로 교체되어 지연 시간이 늘어난다.

#### Write-through

<p align="center">
  <img src="images/0vBc0hN.png">
  <br/>
  <i><a href=http://www.slideshare.net/jboner/scalability-availability-stability-patterns/>출처: Scalability, availability, stability, patterns</a></i>
</p>

애플리케이션은 캐시를 주 데이터 저장소로 삼아 캐시에서 데이터를 읽고 쓰며, 데이터베이스를 읽고 쓰는 일은 캐시가 맡는다:

* 애플리케이션이 캐시에 항목을 추가하거나 갱신한다
* 캐시가 항목을 데이터 저장소에 동기적으로 쓴다
* 반환한다

애플리케이션 코드:

```python
set_user(12345, {"foo":"bar"})
```

캐시 코드:

```python
def set_user(user_id, values):
    user = db.query("UPDATE Users WHERE id = {0}", user_id, values)
    cache.set(user_id, user)
```

Write-through는 쓰기 작업 때문에 전체적으로 느리지만, 방금 쓴 데이터를 이후에 읽는 것은 빠르다. 사용자는 대개 데이터를 읽을 때보다 갱신할 때의 지연을 더 잘 참는다. 캐시의 데이터는 오래된 것이 되지 않는다.

##### 단점: Write-through

* 장애나 확장으로 새 노드가 생기면, 데이터베이스에서 항목이 갱신될 때까지 새 노드는 그 항목을 캐시하지 않는다. Cache-aside와 Write-through를 함께 쓰면 이 문제를 줄일 수 있다.
* 쓴 데이터 대부분이 한 번도 읽히지 않을 수 있는데, TTL로 이를 줄일 수 있다.

#### Write-behind(write-back)

<p align="center">
  <img src="images/rgSrvjG.png">
  <br/>
  <i><a href=http://www.slideshare.net/jboner/scalability-availability-stability-patterns/>출처: Scalability, availability, stability, patterns</a></i>
</p>

Write-behind에서 애플리케이션은 다음을 수행한다:

* 캐시에 항목을 추가하거나 갱신한다
* 항목을 데이터 저장소에 비동기로 써서 쓰기 성능을 높인다

##### 단점: Write-behind

* 캐시의 내용이 데이터 저장소에 반영되기 전에 캐시가 죽으면 데이터를 잃을 수 있다.
* Write-behind는 Cache-aside나 Write-through보다 구현하기가 더 복잡하다.

#### Refresh-ahead

<p align="center">
  <img src="images/kxtjqgE.png">
  <br/>
  <i><a href=http://www.slideshare.net/tmatyashovsky/from-cache-to-in-memory-data-grid-introduction-to-hazelcast>출처: From cache to in-memory data grid</a></i>
</p>

최근에 접근한 캐시 항목을 만료 전에 자동으로 새로 고치도록 캐시를 설정할 수 있다.

앞으로 어떤 항목이 필요할지 캐시가 정확히 예측할 수 있다면, Refresh-ahead는 Read-through보다 지연 시간을 줄일 수 있다.

##### 단점: Refresh-ahead

* 앞으로 필요할 항목을 정확히 예측하지 못하면 Refresh-ahead를 쓰지 않을 때보다 성능이 떨어질 수 있다.

### 단점: 캐시

* [캐시 무효화](https://en.wikipedia.org/wiki/Cache_algorithms)를 통해 캐시와 데이터베이스 같은 원본 데이터(source of truth) 사이의 일관성을 유지해야 한다.
* 캐시 무효화는 어려운 문제이며, 언제 캐시를 갱신할지에 따른 복잡도가 더해진다.
* Redis나 memcached를 추가하는 등 애플리케이션을 바꿔야 한다.

### 출처 및 더 읽을거리

* [From cache to in-memory data grid](http://www.slideshare.net/tmatyashovsky/from-cache-to-in-memory-data-grid-introduction-to-hazelcast)
* [Scalable system design patterns](http://horicky.blogspot.com/2010/10/scalable-system-design-patterns.html)
* [Introduction to architecting systems for scale](http://lethain.com/introduction-to-architecting-systems-for-scale/)
* [Scalability, availability, stability, patterns](http://www.slideshare.net/jboner/scalability-availability-stability-patterns/)
* [Scalability](https://web.archive.org/web/20230126233752/https://www.lecloud.net/post/9246290032/scalability-for-dummies-part-3-cache)
* [AWS ElastiCache strategies](http://docs.aws.amazon.com/AmazonElastiCache/latest/UserGuide/Strategies.html)
* [Wikipedia](https://en.wikipedia.org/wiki/Cache_(computing))

## 비동기 처리

<p align="center">
  <img src="images/54GYsSx.png">
  <br/>
  <i><a href=http://lethain.com/introduction-to-architecting-systems-for-scale/#platform_layer>출처: Intro to architecting systems for scale</a></i>
</p>

비동기 워크플로는 원래라면 요청 안에서 처리했을 비용이 큰 작업의 요청 시간을 줄여 준다. 데이터의 주기적인 집계처럼 시간이 오래 걸리는 작업을 미리 해 두는 데도 도움이 된다.

### 메시지 큐

메시지 큐는 메시지를 받아서 보관하고 전달한다. 어떤 작업이 요청 안에서 처리하기에 너무 느리다면, 다음 흐름으로 메시지 큐를 쓸 수 있다:

* 애플리케이션이 큐에 작업을 발행하고, 사용자에게 작업 상태를 알린다
* 워커가 큐에서 작업을 가져와 처리한 뒤, 작업이 끝났음을 알린다

사용자는 기다리지 않고, 작업은 백그라운드에서 처리된다. 그동안 클라이언트는 작업이 끝난 것처럼 보이도록 약간의 처리를 할 수도 있다. 예를 들어 트윗을 올리면 내 타임라인에는 바로 보이지만, 모든 팔로워에게 실제로 전달되기까지는 시간이 걸릴 수 있다.

[**Redis**](https://redis.io/)는 간단한 메시지 브로커로 쓸 만하지만 메시지가 유실될 수 있다.

[**RabbitMQ**](https://www.rabbitmq.com/)는 널리 쓰이지만 'AMQP' 프로토콜에 맞춰야 하고 노드를 직접 관리해야 한다.

[**Amazon SQS**](https://aws.amazon.com/sqs/)는 호스팅 서비스지만 지연 시간이 길 수 있고 메시지가 두 번 전달될 가능성이 있다.

### 태스크 큐

태스크 큐는 태스크와 관련 데이터를 받아 실행한 뒤 결과를 전달한다. 스케줄링을 지원할 수 있으며, 계산량이 많은 작업을 백그라운드에서 실행하는 데 쓸 수 있다.

[**Celery**](https://docs.celeryproject.org/en/stable/)는 스케줄링을 지원하며 주로 Python을 지원한다.

### 백프레셔

큐가 크게 불어나면 큐 크기가 메모리보다 커져 캐시 미스와 디스크 읽기가 생기고 성능이 더 떨어질 수 있다. [백프레셔](http://mechanical-sympathy.blogspot.com/2012/05/apply-back-pressure-when-overloaded.html)(back pressure)는 큐 크기를 제한해, 이미 큐에 있는 작업의 높은 처리율과 좋은 응답 시간을 유지하는 데 도움이 된다. 큐가 가득 차면 클라이언트는 서버가 바쁘다는 응답이나 나중에 다시 시도하라는 HTTP 503 상태 코드를 받는다. 클라이언트는 [지수 백오프](https://en.wikipedia.org/wiki/Exponential_backoff)(exponential backoff) 등을 써서 나중에 요청을 다시 시도할 수 있다.

### 단점: 비동기 처리

* 큐를 도입하면 지연과 복잡도가 늘어날 수 있으므로, 비용이 적은 계산이나 실시간 워크플로 같은 유스 케이스에는 동기 처리가 더 나을 수 있다.

### 출처 및 더 읽을거리

* [It's all a numbers game](https://www.youtube.com/watch?v=1KRYH75wgy4)
* [Applying back pressure when overloaded](http://mechanical-sympathy.blogspot.com/2012/05/apply-back-pressure-when-overloaded.html)
* [Little's law](https://en.wikipedia.org/wiki/Little%27s_law)
* [What is the difference between a message queue and a task queue?](https://www.quora.com/What-is-the-difference-between-a-message-queue-and-a-task-queue-Why-would-a-task-queue-require-a-message-broker-like-RabbitMQ-Redis-Celery-or-IronMQ-to-function)

## 통신

<p align="center">
  <img src="images/5KeocQs.jpg">
  <br/>
  <i><a href=http://www.escotal.com/osilayer.html>출처: OSI 7 layer model</a></i>
</p>

### 하이퍼텍스트 전송 프로토콜(HTTP)

HTTP는 클라이언트와 서버 사이에서 데이터를 인코딩하고 전송하는 방법이다. HTTP는 요청/응답 프로토콜이다. 클라이언트가 요청을 보내면 서버는 관련 콘텐츠와 요청의 처리 상태 정보를 담아 응답한다. HTTP는 자기 완결적이어서, 요청과 응답이 로드 밸런싱, 캐싱, 암호화, 압축을 수행하는 여러 중간 라우터와 서버를 거쳐 흐를 수 있다.

기본 HTTP 요청은 동사(메서드)와 리소스(엔드포인트)로 이루어진다. 자주 쓰는 HTTP 메서드는 다음과 같다:

| 메서드 | 설명 | 멱등* | 안전 | 캐시 가능 |
|---|---|---|---|---|
| GET | 리소스를 읽는다 | 예 | 예 | 예 |
| POST | 리소스를 만들거나 데이터를 처리하는 프로세스를 실행한다 | 아니요 | 아니요 | 응답에 신선도 정보가 있으면 예 |
| PUT | 리소스를 만들거나 교체한다 | 예 | 아니요 | 아니요 |
| PATCH | 리소스를 부분적으로 갱신한다 | 아니요 | 아니요 | 응답에 신선도 정보가 있으면 예 |
| DELETE | 리소스를 삭제한다 | 예 | 아니요 | 아니요 |

*여러 번 호출해도 결과가 달라지지 않는다.

HTTP는 **TCP**나 **UDP** 같은 하위 프로토콜에 기반한 애플리케이션 계층 프로토콜이다.

#### 출처 및 더 읽을거리: HTTP

* [What is HTTP?](https://www.nginx.com/resources/glossary/http/)
* [Difference between HTTP and TCP](https://www.quora.com/What-is-the-difference-between-HTTP-protocol-and-TCP-protocol)
* [Difference between PUT and PATCH](https://laracasts.com/discuss/channels/general-discussion/whats-the-differences-between-put-and-patch?page=1)

### 전송 제어 프로토콜(TCP)

<p align="center">
  <img src="images/JdAsdvG.jpg">
  <br/>
  <i><a href=http://www.wildbunny.co.uk/blog/2012/10/09/how-to-make-a-multi-player-game-part-1/>출처: How to make a multiplayer game</a></i>
</p>

TCP는 [IP 네트워크](https://en.wikipedia.org/wiki/Internet_Protocol) 위에서 동작하는 연결 지향 프로토콜이다. 연결은 [핸드셰이크](https://en.wikipedia.org/wiki/Handshaking)로 맺고 끊는다. 보낸 모든 패킷은 다음 장치를 통해 원래 순서대로, 손상 없이 목적지에 도착하도록 보장된다:

* 패킷마다 붙는 순서 번호와 [체크섬 필드](https://en.wikipedia.org/wiki/Transmission_Control_Protocol#Checksum_computation)
* [확인 응답](https://en.wikipedia.org/wiki/Acknowledgement_(data_networks))(ACK) 패킷과 자동 재전송

송신자가 올바른 응답을 받지 못하면 패킷을 다시 보낸다. 타임아웃이 여러 번 나면 연결을 끊는다. TCP는 [흐름 제어](https://en.wikipedia.org/wiki/Flow_control_(data))와 [혼잡 제어](https://en.wikipedia.org/wiki/Network_congestion#Congestion_control)도 구현한다. 이런 보장 때문에 지연이 생기고, 대개 UDP보다 전송 효율이 떨어진다.

높은 처리량을 보장하려고 웹 서버가 TCP 연결을 많이 열어 두면 메모리 사용량이 커진다. 웹 서버 스레드와, 예를 들어 [memcached](https://memcached.org/) 서버 사이에 연결을 많이 열어 두는 것은 비용이 클 수 있다. 가능한 곳에서는 UDP로 바꾸는 것과 함께 [커넥션 풀링](https://en.wikipedia.org/wiki/Connection_pool)이 도움이 된다.

TCP는 신뢰성이 높아야 하지만 시간에는 덜 민감한 애플리케이션에 유용하다. 웹 서버, 데이터베이스 정보, SMTP, FTP, SSH 등이 그 예다.

다음과 같은 경우 UDP 대신 TCP를 써라:

* 모든 데이터가 손상 없이 도착해야 할 때
* 네트워크 처리량을 자동으로 최대한 활용하고 싶을 때

### 사용자 데이터그램 프로토콜(UDP)

<p align="center">
  <img src="images/yzDrJtA.jpg">
  <br/>
  <i><a href=http://www.wildbunny.co.uk/blog/2012/10/09/how-to-make-a-multi-player-game-part-1/>출처: How to make a multiplayer game</a></i>
</p>

UDP는 비연결형이다. 데이터그램(패킷과 비슷하다)은 데이터그램 수준에서만 보장된다. 데이터그램은 순서가 뒤바뀌어 도착하거나 아예 도착하지 않을 수 있다. UDP는 혼잡 제어를 지원하지 않는다. TCP가 지원하는 보장이 없는 대신 UDP는 대체로 더 효율적이다.

UDP는 브로드캐스트로 서브넷의 모든 장치에 데이터그램을 보낼 수 있다. 이는 [DHCP](https://en.wikipedia.org/wiki/Dynamic_Host_Configuration_Protocol)에서 유용하다. 클라이언트가 아직 IP 주소를 받지 못해 TCP로는 IP 주소 없이 통신할 방법이 없기 때문이다.

UDP는 신뢰성이 낮지만 VoIP, 화상 채팅, 스트리밍, 실시간 멀티플레이어 게임 같은 실시간 유스 케이스에 잘 맞는다.

다음과 같은 경우 TCP 대신 UDP를 써라:

* 지연 시간이 가장 짧아야 할 때
* 늦게 도착한 데이터가 데이터 손실보다 나쁠 때
* 오류 정정을 직접 구현하고 싶을 때

#### 출처 및 더 읽을거리: TCP와 UDP

* [Networking for game programming](https://gafferongames.com/post/udp_vs_tcp/)
* [Key differences between TCP and UDP protocols](http://www.cyberciti.biz/faq/key-differences-between-tcp-and-udp-protocols/)
* [Difference between TCP and UDP](http://stackoverflow.com/questions/5970383/difference-between-tcp-and-udp)
* [Transmission control protocol](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)
* [User datagram protocol](https://en.wikipedia.org/wiki/User_Datagram_Protocol)
* [Scaling memcache at Facebook](http://www.cs.bu.edu/~jappavoo/jappavoo.github.com/451/papers/memcache-fb.pdf)

### 원격 프로시저 호출(RPC)

<p align="center">
  <img src="images/iF4Mkb5.png">
  <br/>
  <i><a href=http://www.puncsky.com/blog/2016-02-13-crack-the-system-design-interview>출처: Crack the system design interview</a></i>
</p>

RPC에서 클라이언트는 다른 주소 공간, 보통 원격 서버에서 프로시저가 실행되게 한다. 프로시저는 마치 로컬 프로시저를 호출하듯 작성되며, 서버와 통신하는 방법의 세부 사항은 클라이언트 프로그램에서 추상화된다. 원격 호출은 보통 로컬 호출보다 느리고 신뢰성이 낮으므로, RPC 호출과 로컬 호출을 구분해 두면 좋다. 널리 쓰이는 RPC 프레임워크로는 [Protobuf](https://developers.google.com/protocol-buffers/), [Thrift](https://thrift.apache.org/), [Avro](https://avro.apache.org/docs/current/)가 있다.

RPC는 요청-응답 프로토콜이다:

* **클라이언트 프로그램** - 클라이언트 스텁 프로시저를 호출한다. 로컬 프로시저 호출처럼 매개변수를 스택에 넣는다.
* **클라이언트 스텁 프로시저** - 프로시저 ID와 인자를 요청 메시지로 마샬링(포장)한다.
* **클라이언트 통신 모듈** - OS가 클라이언트에서 서버로 메시지를 보낸다.
* **서버 통신 모듈** - OS가 들어온 패킷을 서버 스텁 프로시저에 넘긴다.
* **서버 스텁 프로시저** - 결과를 언마샬링하고, 프로시저 ID에 맞는 서버 프로시저를 호출해 받은 인자를 넘긴다.
* 서버의 응답은 위 단계를 역순으로 거친다.

RPC 호출 예:

```
GET /someoperation?data=anId

POST /anotheroperation
{
  "data":"anId";
  "anotherdata": "another value"
}
```

RPC는 동작을 노출하는 데 초점을 둔다. 유스 케이스에 맞게 네이티브 호출을 직접 만들 수 있으므로, 성능상의 이유로 내부 통신에 자주 쓰인다.

다음과 같은 경우 네이티브 라이브러리(SDK)를 골라라:

* 대상 플랫폼을 알고 있을 때.
* "로직"에 접근하는 방식을 통제하고 싶을 때.
* 라이브러리 밖에서 오류 제어가 일어나는 방식을 통제하고 싶을 때.
* 성능과 최종 사용자 경험이 가장 중요할 때.

공개 API에는 **REST**를 따르는 HTTP API가 더 자주 쓰인다.

#### 단점: RPC

* RPC 클라이언트가 서비스 구현에 강하게 결합된다.
* 새 작업이나 유스 케이스마다 새 API를 정의해야 한다.
* RPC는 디버깅하기 어려울 수 있다.
* 기존 기술을 그대로 활용하지 못할 수 있다. 예를 들어 [Squid](http://www.squid-cache.org/) 같은 캐싱 서버에서 [RPC 호출이 제대로 캐시되도록](https://web.archive.org/web/20170608193645/http://etherealbits.com/2012/12/debunking-the-myths-of-rpc-rest/) 하려면 추가 작업이 필요할 수 있다.

### REST(Representational State Transfer)

REST는 클라이언트가 서버가 관리하는 리소스 집합에 작용하는 클라이언트/서버 모델을 강제하는 아키텍처 스타일이다. 서버는 리소스의 표현(representation)과, 리소스를 조작하거나 새 표현을 얻을 수 있는 동작을 제공한다. 모든 통신은 무상태이며 캐시 가능해야 한다.

RESTful 인터페이스에는 네 가지 특성이 있다:

* **리소스 식별**(HTTP의 URI) - 어떤 작업이든 같은 URI를 쓴다.
* **표현을 통한 변경**(HTTP의 메서드) - 메서드, 헤더, 본문을 쓴다.
* **자기 서술적 오류 메시지**(HTTP의 상태 응답) - 상태 코드를 쓴다. 바퀴를 다시 발명하지 마라.
* [**HATEOAS**](http://restcookbook.com/Basics/hateoas/)(HTTP를 위한 HTML 인터페이스) - 웹 서비스는 브라우저에서 완전히 접근할 수 있어야 한다.

REST 호출 예:

```
GET /someresources/anId

PUT /someresources/anId
{"anotherdata": "another value"}
```

REST는 데이터를 노출하는 데 초점을 둔다. 클라이언트와 서버의 결합도를 최소화하며 공개 HTTP API에 자주 쓰인다. REST는 URI로 리소스를, [헤더로 표현](https://github.com/for-GET/know-your-http-well/blob/master/headers.md)을, GET, POST, PUT, DELETE, PATCH 같은 메서드로 동작을 노출하는, 더 일반적이고 일관된 방식을 쓴다. 무상태이므로 수평 확장과 파티셔닝에 아주 잘 맞는다.

#### 단점: REST

* REST는 데이터 노출에 초점을 두므로, 리소스가 단순한 계층으로 자연스럽게 조직되거나 접근되지 않는다면 잘 맞지 않을 수 있다. 예를 들어 지난 한 시간 동안 갱신된 레코드 중 특정 이벤트 집합에 맞는 것을 모두 돌려주는 일은 경로로 쉽게 표현되지 않는다. REST로는 URI 경로, 쿼리 매개변수, 경우에 따라 요청 본문을 조합해 구현하게 될 것이다.
* REST는 보통 몇 가지 메서드(GET, POST, PUT, DELETE, PATCH)에 의존하는데, 이것이 유스 케이스에 맞지 않을 때가 있다. 예를 들어 만료된 문서를 보관 폴더로 옮기는 일은 이 메서드들에 깔끔하게 들어맞지 않을 수 있다.
* 중첩된 계층을 가진 복잡한 리소스를 가져오려면, 블로그 글의 내용과 그 글의 댓글을 가져오는 경우처럼 화면 하나를 그리는 데 클라이언트와 서버 사이를 여러 번 왕복해야 한다. 네트워크 상태가 수시로 바뀌는 모바일 애플리케이션에서는 이런 여러 번의 왕복이 매우 바람직하지 않다.
* 시간이 지나면서 API 응답에 필드가 늘어나면, 오래된 클라이언트도 필요 없는 새 데이터 필드까지 모두 받게 된다. 그 결과 페이로드가 커지고 지연 시간이 길어진다.

### RPC와 REST 호출 비교

| 작업 | RPC | REST |
|---|---|---|
| 회원 가입 | **POST** /signup | **POST** /persons |
| 회원 탈퇴 | **POST** /resign<br/>{<br/>"personid": "1234"<br/>} | **DELETE** /persons/1234 |
| 사람 조회 | **GET** /readPerson?personid=1234 | **GET** /persons/1234 |
| 사람의 아이템 목록 조회 | **GET** /readUsersItemsList?personid=1234 | **GET** /persons/1234/items |
| 사람의 아이템 목록에 아이템 추가 | **POST** /addItemToUsersItemsList<br/>{<br/>"personid": "1234";<br/>"itemid": "456"<br/>} | **POST** /persons/1234/items<br/>{<br/>"itemid": "456"<br/>} |
| 아이템 수정 | **POST** /modifyItem<br/>{<br/>"itemid": "456";<br/>"key": "value"<br/>} | **PUT** /items/456<br/>{<br/>"key": "value"<br/>} |
| 아이템 삭제 | **POST** /removeItem<br/>{<br/>"itemid": "456"<br/>} | **DELETE** /items/456 |

<p align="center">
  <i><a href=https://apihandyman.io/do-you-really-know-why-you-prefer-rest-over-rpc/>출처: Do you really know why you prefer REST over RPC</a></i>
</p>

#### 출처 및 더 읽을거리: REST와 RPC

* [Do you really know why you prefer REST over RPC](https://apihandyman.io/do-you-really-know-why-you-prefer-rest-over-rpc/)
* [When are RPC-ish approaches more appropriate than REST?](http://programmers.stackexchange.com/a/181186)
* [REST vs JSON-RPC](http://stackoverflow.com/questions/15056878/rest-vs-json-rpc)
* [Debunking the myths of RPC and REST](https://web.archive.org/web/20170608193645/http://etherealbits.com/2012/12/debunking-the-myths-of-rpc-rest/)
* [What are the drawbacks of using REST](https://www.quora.com/What-are-the-drawbacks-of-using-RESTful-APIs)
* [Crack the system design interview](http://www.puncsky.com/blog/2016-02-13-crack-the-system-design-interview)
* [Thrift](https://code.facebook.com/posts/1468950976659943/)
* [Why REST for internal use and not RPC](http://arstechnica.com/civis/viewtopic.php?t=1190508)

## 보안

이 섹션은 보완이 필요하다. [기여](#기여하기)를 환영한다!

보안은 범위가 넓은 주제다. 경험이 많거나, 보안 분야 배경이 있거나, 보안 지식이 필요한 직무에 지원하는 경우가 아니라면 기본 이상은 알 필요가 없을 것이다:

* 전송 중인 데이터와 저장된 데이터를 암호화하라.
* [크로스 사이트 스크립팅(XSS)](https://en.wikipedia.org/wiki/Cross-site_scripting)과 [SQL 인젝션](https://en.wikipedia.org/wiki/SQL_injection)을 막으려면 모든 사용자 입력과 사용자에게 노출된 입력 매개변수를 정제하라.
* SQL 인젝션을 막으려면 매개변수화된 쿼리를 써라.
* [최소 권한](https://en.wikipedia.org/wiki/Principle_of_least_privilege) 원칙을 따르라.

### 출처 및 더 읽을거리

* [API security checklist](https://github.com/shieldfy/API-Security-Checklist)
* [Security guide for developers](https://github.com/FallibleInc/security-guide-for-developers)
* [OWASP top ten](https://www.owasp.org/index.php/OWASP_Top_Ten_Cheat_Sheet)

## 부록

면접에서는 가끔 '개략적인' 추정(back-of-the-envelope)을 요구받는다. 예를 들어 디스크에서 이미지 썸네일 100개를 만드는 데 얼마나 걸릴지, 어떤 자료 구조가 메모리를 얼마나 차지할지 따져 봐야 할 수 있다. **2의 거듭제곱 표**와 **모든 프로그래머가 알아야 할 지연 시간 수치**는 이럴 때 요긴한 참고 자료다.

### 2의 거듭제곱 표

```
Power           Exact Value         Approx Value        Bytes
---------------------------------------------------------------
7                             128
8                             256
10                           1024   1 thousand           1 KB
16                         65,536                       64 KB
20                      1,048,576   1 million            1 MB
30                  1,073,741,824   1 billion            1 GB
32                  4,294,967,296                        4 GB
40              1,099,511,627,776   1 trillion           1 TB
```

#### 출처 및 더 읽을거리

* [Powers of two](https://en.wikipedia.org/wiki/Power_of_two)

### 모든 프로그래머가 알아야 할 지연 시간 수치

```
Latency Comparison Numbers
--------------------------
L1 cache reference                           0.5 ns
Branch mispredict                            5   ns
L2 cache reference                           7   ns                      14x L1 cache
Mutex lock/unlock                           25   ns
Main memory reference                      100   ns                      20x L2 cache, 200x L1 cache
Compress 1K bytes with Zippy            10,000   ns       10 us
Send 1 KB bytes over 1 Gbps network     10,000   ns       10 us
Read 4 KB randomly from SSD*           150,000   ns      150 us          ~1GB/sec SSD
Read 1 MB sequentially from memory     250,000   ns      250 us
Round trip within same datacenter      500,000   ns      500 us
Read 1 MB sequentially from SSD*     1,000,000   ns    1,000 us    1 ms  ~1GB/sec SSD, 4X memory
HDD seek                            10,000,000   ns   10,000 us   10 ms  20x datacenter roundtrip
Read 1 MB sequentially from 1 Gbps  10,000,000   ns   10,000 us   10 ms  40x memory, 10X SSD
Read 1 MB sequentially from HDD     30,000,000   ns   30,000 us   30 ms 120x memory, 30X SSD
Send packet CA->Netherlands->CA    150,000,000   ns  150,000 us  150 ms

Notes
-----
1 ns = 10^-9 seconds
1 us = 10^-6 seconds = 1,000 ns
1 ms = 10^-3 seconds = 1,000 us = 1,000,000 ns
```

위 수치를 바탕으로 한 유용한 지표:

* HDD 순차 읽기: 30 MB/s
* 1 Gbps 이더넷 순차 읽기: 100 MB/s
* SSD 순차 읽기: 1 GB/s
* 메인 메모리 순차 읽기: 4 GB/s
* 전 세계 왕복: 초당 6~7회
* 데이터 센터 내 왕복: 초당 2,000회

#### 지연 시간 수치 시각화

![](https://camo.githubusercontent.com/77f72259e1eb58596b564d1ad823af1853bc60a3/687474703a2f2f692e696d6775722e636f6d2f6b307431652e706e67)

#### 출처 및 더 읽을거리

* [Latency numbers every programmer should know - 1](https://gist.github.com/jboner/2841832)
* [Latency numbers every programmer should know - 2](https://gist.github.com/hellerbarde/2843375)
* [Designs, lessons, and advice from building large distributed systems](http://www.cs.cornell.edu/projects/ladis2009/talks/dean-keynote-ladis2009.pdf)
* [Software Engineering Advice from Building Large-Scale Distributed Systems](https://static.googleusercontent.com/media/research.google.com/en//people/jeff/stanford-295-talk.pdf)

### 추가 시스템 설계 면접 문제

> 자주 나오는 시스템 설계 면접 문제와 각 문제의 풀이에 도움이 되는 자료 링크.

| 문제 | 참고 자료 |
|---|---|
| Dropbox 같은 파일 동기화 서비스 설계하기 | [youtube.com](https://www.youtube.com/watch?v=PE4gwstWhmc) |
| Google 같은 검색 엔진 설계하기 | [queue.acm.org](http://queue.acm.org/detail.cfm?id=988407)<br/>[stackexchange.com](http://programmers.stackexchange.com/questions/38324/interview-question-how-would-you-implement-google-search)<br/>[ardendertat.com](http://www.ardendertat.com/2012/01/11/implementing-search-engines/)<br/>[stanford.edu](http://infolab.stanford.edu/~backrub/google.html) |
| Google 같은 확장 가능한 웹 크롤러 설계하기 | [quora.com](https://www.quora.com/How-can-I-build-a-web-crawler-from-scratch) |
| Google Docs 설계하기 | [code.google.com](https://code.google.com/p/google-mobwrite/)<br/>[neil.fraser.name](https://neil.fraser.name/writing/sync/) |
| Redis 같은 키-값 저장소 설계하기 | [codecapsule.com](http://codecapsule.com/2012/11/07/ikvs-implementing-a-key-value-store-table-of-contents/)<br/>[allthingsdistributed.com](https://www.allthingsdistributed.com/files/amazon-dynamo-sosp2007.pdf) |
| Memcached 같은 캐시 시스템 설계하기 | [slideshare.net](http://www.slideshare.net/oemebamo/introduction-to-memcached) |
| Amazon 같은 추천 시스템 설계하기 | [hulu.com](https://web.archive.org/web/20170406065247/http://tech.hulu.com/blog/2011/09/19/recommendation-system.html)<br/>[ijcai13.org](http://ijcai13.org/files/tutorial_slides/td3.pdf) |
| Bitly 같은 URL 단축 시스템 설계하기 | [n00tc0d3r.blogspot.com](http://n00tc0d3r.blogspot.com/) |
| WhatsApp 같은 채팅 앱 설계하기 | [highscalability.com](http://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html)
| Instagram 같은 사진 공유 시스템 설계하기 | [highscalability.com](http://highscalability.com/flickr-architecture)<br/>[highscalability.com](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html) |
| Facebook 뉴스 피드 기능 설계하기 | [quora.com](http://www.quora.com/What-are-best-practices-for-building-something-like-a-News-Feed)<br/>[quora.com](http://www.quora.com/Activity-Streams/What-are-the-scaling-issues-to-keep-in-mind-while-developing-a-social-network-feed)<br/>[slideshare.net](http://www.slideshare.net/danmckinley/etsy-activity-feeds-architecture) |
| Facebook 타임라인 기능 설계하기 | [facebook.com](https://www.facebook.com/note.php?note_id=10150468255628920)<br/>[highscalability.com](http://highscalability.com/blog/2012/1/23/facebook-timeline-brought-to-you-by-the-power-of-denormaliza.html) |
| Facebook 채팅 기능 설계하기 | [erlang-factory.com](http://www.erlang-factory.com/upload/presentations/31/EugeneLetuchy-ErlangatFacebook.pdf)<br/>[facebook.com](https://www.facebook.com/note.php?note_id=14218138919&id=9445547199&index=0) |
| Facebook 같은 그래프 검색 기능 설계하기 | [facebook.com](https://www.facebook.com/notes/facebook-engineering/under-the-hood-building-out-the-infrastructure-for-graph-search/10151347573598920)<br/>[facebook.com](https://www.facebook.com/notes/facebook-engineering/under-the-hood-indexing-and-ranking-in-graph-search/10151361720763920)<br/>[facebook.com](https://www.facebook.com/notes/facebook-engineering/under-the-hood-the-natural-language-interface-of-graph-search/10151432733048920) |
| CloudFlare 같은 콘텐츠 전송 네트워크 설계하기 | [figshare.com](https://figshare.com/articles/Globally_distributed_content_delivery/6605972) |
| Twitter 같은 트렌딩 토픽 시스템 설계하기 | [michael-noll.com](http://www.michael-noll.com/blog/2013/01/18/implementing-real-time-trending-topics-in-storm/)<br/>[snikolov .wordpress.com](http://snikolov.wordpress.com/2012/11/14/early-detection-of-twitter-trends/) |
| 무작위 ID 생성 시스템 설계하기 | [blog.twitter.com](https://blog.twitter.com/2010/announcing-snowflake)<br/>[github.com](https://github.com/twitter/snowflake/) |
| 일정 시간 동안의 상위 k개 요청 반환하기 | [cs.ucsb.edu](https://www.cs.ucsb.edu/sites/default/files/documents/2005-23.pdf)<br/>[wpi.edu](http://davis.wpi.edu/xmdv/docs/EDBT11-diyang.pdf) |
| 여러 데이터 센터에서 데이터를 제공하는 시스템 설계하기 | [highscalability.com](http://highscalability.com/blog/2009/8/24/how-google-serves-data-from-multiple-datacenters.html) |
| 온라인 멀티플레이어 카드 게임 설계하기 | [indieflashblog.com](https://web.archive.org/web/20180929181117/http://www.indieflashblog.com/how-to-create-an-asynchronous-multiplayer-game.html)<br/>[buildnewgames.com](http://buildnewgames.com/real-time-multiplayer/) |
| 가비지 컬렉션 시스템 설계하기 | [stuffwithstuff.com](http://journal.stuffwithstuff.com/2013/12/08/babys-first-garbage-collector/)<br/>[washington.edu](http://courses.cs.washington.edu/courses/csep521/07wi/prj/rick.pdf) |
| API 처리율 제한 장치 설계하기 | [https://stripe.com/blog/](https://stripe.com/blog/rate-limiters) |
| 증권 거래소(NASDAQ이나 Binance 같은) 설계하기 | [Jane Street](https://youtu.be/b1e4t2k2KJY)<br/>[Golang 구현](https://around25.com/blog/building-a-trading-engine-for-a-crypto-exchange/)<br/>[Go 구현](http://bhomnick.net/building-a-simple-limit-order-in-go/) |
| 시스템 설계 문제 추가하기 | [기여하기](#기여하기) |

### 실제 아키텍처 사례

> 실제 시스템이 어떻게 설계되었는지 다룬 글.

<p align="center">
  <img src="images/TcUo2fw.png">
  <br/>
  <i><a href=https://www.infoq.com/presentations/Twitter-Timeline-Scalability>출처: Twitter timelines at scale</a></i>
</p>

**다음 글들의 세세한 부분에 집중하지 말고, 대신 다음을 하라:**

* 글들에 공통된 원칙, 기술, 패턴을 찾아라
* 각 컴포넌트가 어떤 문제를 해결하는지, 어디서 통하고 어디서 통하지 않는지 공부하라
* 얻은 교훈을 복습하라

|유형 | 시스템 | 참고 자료 |
|---|---|---|
| 데이터 처리 | **MapReduce** - Google의 분산 데이터 처리 | [research.google.com](http://static.googleusercontent.com/media/research.google.com/zh-CN/us/archive/mapreduce-osdi04.pdf) |
| 데이터 처리 | **Spark** - Databricks의 분산 데이터 처리 | [slideshare.net](http://www.slideshare.net/AGrishchenko/apache-spark-architecture) |
| 데이터 처리 | **Storm** - Twitter의 분산 데이터 처리 | [slideshare.net](http://www.slideshare.net/previa/storm-16094009) |
| | | |
| 데이터 저장소 | **Bigtable** - Google의 분산 컬럼 지향 데이터베이스 | [harvard.edu](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/chang06bigtable.pdf) |
| 데이터 저장소 | **HBase** - Bigtable의 오픈 소스 구현 | [slideshare.net](http://www.slideshare.net/alexbaranau/intro-to-hbase) |
| 데이터 저장소 | **Cassandra** - Facebook의 분산 컬럼 지향 데이터베이스 | [slideshare.net](http://www.slideshare.net/planetcassandra/cassandra-introduction-features-30103666)
| 데이터 저장소 | **DynamoDB** - Amazon의 문서 지향 데이터베이스 | [harvard.edu](http://www.read.seas.harvard.edu/~kohler/class/cs239-w08/decandia07dynamo.pdf) |
| 데이터 저장소 | **MongoDB** - 문서 지향 데이터베이스 | [slideshare.net](http://www.slideshare.net/mdirolf/introduction-to-mongodb) |
| 데이터 저장소 | **Spanner** - Google의 전 세계 분산 데이터베이스 | [research.google.com](http://research.google.com/archive/spanner-osdi2012.pdf) |
| 데이터 저장소 | **Memcached** - 분산 메모리 캐싱 시스템 | [slideshare.net](http://www.slideshare.net/oemebamo/introduction-to-memcached) |
| 데이터 저장소 | **Redis** - 영속화와 값 타입을 지원하는 분산 메모리 캐싱 시스템 | [slideshare.net](http://www.slideshare.net/dvirsky/introduction-to-redis) |
| | | |
| 파일 시스템 | **Google File System (GFS)** - 분산 파일 시스템 | [research.google.com](http://static.googleusercontent.com/media/research.google.com/zh-CN/us/archive/gfs-sosp2003.pdf) |
| 파일 시스템 | **Hadoop File System (HDFS)** - GFS의 오픈 소스 구현 | [apache.org](http://hadoop.apache.org/docs/stable/hadoop-project-dist/hadoop-hdfs/HdfsDesign.html) |
| | | |
| 기타 | **Chubby** - Google의 느슨하게 결합된 분산 시스템용 락 서비스 | [research.google.com](http://static.googleusercontent.com/external_content/untrusted_dlcp/research.google.com/en/us/archive/chubby-osdi06.pdf) |
| 기타 | **Dapper** - 분산 시스템 추적 인프라 | [research.google.com](http://static.googleusercontent.com/media/research.google.com/en//pubs/archive/36356.pdf)
| 기타 | **Kafka** - LinkedIn의 발행/구독(Pub/sub) 메시지 큐 | [slideshare.net](http://www.slideshare.net/mumrah/kafka-talk-tri-hug) |
| 기타 | **Zookeeper** - 동기화를 가능하게 하는 중앙 집중식 인프라와 서비스 | [slideshare.net](http://www.slideshare.net/sauravhaloi/introduction-to-apache-zookeeper) |
| | 아키텍처 추가하기 | [기여하기](#기여하기) |

### 기업별 아키텍처

| 회사 | 참고 자료 |
|---|---|
| Amazon | [Amazon architecture](http://highscalability.com/amazon-architecture) |
| Cinchcast | [Producing 1,500 hours of audio every day](http://highscalability.com/blog/2012/7/16/cinchcast-architecture-producing-1500-hours-of-audio-every-d.html) |
| DataSift | [Realtime datamining At 120,000 tweets per second](http://highscalability.com/blog/2011/11/29/datasift-architecture-realtime-datamining-at-120000-tweets-p.html) |
| Dropbox | [How we've scaled Dropbox](https://www.youtube.com/watch?v=PE4gwstWhmc) |
| ESPN | [Operating At 100,000 duh nuh nuhs per second](http://highscalability.com/blog/2013/11/4/espns-architecture-at-scale-operating-at-100000-duh-nuh-nuhs.html) |
| Google | [Google architecture](http://highscalability.com/google-architecture) |
| Instagram | [14 million users, terabytes of photos](http://highscalability.com/blog/2011/12/6/instagram-architecture-14-million-users-terabytes-of-photos.html)<br/>[What powers Instagram](http://instagram-engineering.tumblr.com/post/13649370142/what-powers-instagram-hundreds-of-instances) |
| Justin.tv | [Justin.Tv's live video broadcasting architecture](http://highscalability.com/blog/2010/3/16/justintvs-live-video-broadcasting-architecture.html) |
| Facebook | [Scaling memcached at Facebook](https://cs.uwaterloo.ca/~brecht/courses/854-Emerging-2014/readings/key-value/fb-memcached-nsdi-2013.pdf)<br/>[TAO: Facebook’s distributed data store for the social graph](https://cs.uwaterloo.ca/~brecht/courses/854-Emerging-2014/readings/data-store/tao-facebook-distributed-datastore-atc-2013.pdf)<br/>[Facebook’s photo storage](https://www.usenix.org/legacy/event/osdi10/tech/full_papers/Beaver.pdf)<br/>[How Facebook Live Streams To 800,000 Simultaneous Viewers](http://highscalability.com/blog/2016/6/27/how-facebook-live-streams-to-800000-simultaneous-viewers.html) |
| Flickr | [Flickr architecture](http://highscalability.com/flickr-architecture) |
| Mailbox | [From 0 to one million users in 6 weeks](http://highscalability.com/blog/2013/6/18/scaling-mailbox-from-0-to-one-million-users-in-6-weeks-and-1.html) |
| Netflix | [A 360 Degree View Of The Entire Netflix Stack](http://highscalability.com/blog/2015/11/9/a-360-degree-view-of-the-entire-netflix-stack.html)<br/>[Netflix: What Happens When You Press Play?](http://highscalability.com/blog/2017/12/11/netflix-what-happens-when-you-press-play.html) |
| Pinterest | [From 0 To 10s of billions of page views a month](http://highscalability.com/blog/2013/4/15/scaling-pinterest-from-0-to-10s-of-billions-of-page-views-a.html)<br/>[18 million visitors, 10x growth, 12 employees](http://highscalability.com/blog/2012/5/21/pinterest-architecture-update-18-million-visitors-10x-growth.html) |
| Playfish | [50 million monthly users and growing](http://highscalability.com/blog/2010/9/21/playfishs-social-gaming-architecture-50-million-monthly-user.html) |
| PlentyOfFish | [PlentyOfFish architecture](http://highscalability.com/plentyoffish-architecture) |
| Salesforce | [How they handle 1.3 billion transactions a day](http://highscalability.com/blog/2013/9/23/salesforce-architecture-how-they-handle-13-billion-transacti.html) |
| Stack Overflow | [Stack Overflow architecture](http://highscalability.com/blog/2009/8/5/stack-overflow-architecture.html) |
| TripAdvisor | [40M visitors, 200M dynamic page views, 30TB data](http://highscalability.com/blog/2011/6/27/tripadvisor-architecture-40m-visitors-200m-dynamic-page-view.html) |
| Tumblr | [15 billion page views a month](http://highscalability.com/blog/2012/2/13/tumblr-architecture-15-billion-page-views-a-month-and-harder.html) |
| Twitter | [Making Twitter 10000 percent faster](http://highscalability.com/scaling-twitter-making-twitter-10000-percent-faster)<br/>[Storing 250 million tweets a day using MySQL](http://highscalability.com/blog/2011/12/19/how-twitter-stores-250-million-tweets-a-day-using-mysql.html)<br/>[150M active users, 300K QPS, a 22 MB/S firehose](http://highscalability.com/blog/2013/7/8/the-architecture-twitter-uses-to-deal-with-150m-active-users.html)<br/>[Timelines at scale](https://www.infoq.com/presentations/Twitter-Timeline-Scalability)<br/>[Big and small data at Twitter](https://www.youtube.com/watch?v=5cKTP36HVgI)<br/>[Operations at Twitter: scaling beyond 100 million users](https://www.youtube.com/watch?v=z8LU0Cj6BOU)<br/>[How Twitter Handles 3,000 Images Per Second](http://highscalability.com/blog/2016/4/20/how-twitter-handles-3000-images-per-second.html) |
| Uber | [How Uber scales their real-time market platform](http://highscalability.com/blog/2015/9/14/how-uber-scales-their-real-time-market-platform.html)<br/>[Lessons Learned From Scaling Uber To 2000 Engineers, 1000 Services, And 8000 Git Repositories](http://highscalability.com/blog/2016/10/12/lessons-learned-from-scaling-uber-to-2000-engineers-1000-ser.html) |
| WhatsApp | [The WhatsApp architecture Facebook bought for $19 billion](http://highscalability.com/blog/2014/2/26/the-whatsapp-architecture-facebook-bought-for-19-billion.html) |
| YouTube | [YouTube scalability](https://www.youtube.com/watch?v=w5WVu624fY8)<br/>[YouTube architecture](http://highscalability.com/youtube-architecture) |

### 기업 엔지니어링 블로그

> 면접 볼 회사의 아키텍처.
>
> 면접에서 받는 질문이 같은 분야에서 나올 수 있다.

* [Airbnb Engineering](http://nerds.airbnb.com/)
* [Atlassian Developers](https://developer.atlassian.com/blog/)
* [AWS Blog](https://aws.amazon.com/blogs/aws/)
* [Bitly Engineering Blog](http://word.bitly.com/)
* [Box Blogs](https://blog.box.com/blog/category/engineering)
* [Cloudera Developer Blog](http://blog.cloudera.com/)
* [Dropbox Tech Blog](https://tech.dropbox.com/)
* [Engineering at Quora](https://www.quora.com/q/quoraengineering)
* [Ebay Tech Blog](http://www.ebaytechblog.com/)
* [Evernote Tech Blog](https://blog.evernote.com/tech/)
* [Etsy Code as Craft](http://codeascraft.com/)
* [Facebook Engineering](https://www.facebook.com/Engineering)
* [Flickr Code](http://code.flickr.net/)
* [Foursquare Engineering Blog](http://engineering.foursquare.com/)
* [GitHub Engineering Blog](https://github.blog/category/engineering)
* [Google Research Blog](http://googleresearch.blogspot.com/)
* [Groupon Engineering Blog](https://engineering.groupon.com/)
* [Heroku Engineering Blog](https://engineering.heroku.com/)
* [Hubspot Engineering Blog](http://product.hubspot.com/blog/topic/engineering)
* [High Scalability](http://highscalability.com/)
* [Instagram Engineering](http://instagram-engineering.tumblr.com/)
* [Intel Software Blog](https://software.intel.com/en-us/blogs/)
* [Jane Street Tech Blog](https://blogs.janestreet.com/category/ocaml/)
* [LinkedIn Engineering](http://engineering.linkedin.com/blog)
* [Microsoft Engineering](https://engineering.microsoft.com/)
* [Microsoft Python Engineering](https://blogs.msdn.microsoft.com/pythonengineering/)
* [Netflix Tech Blog](http://techblog.netflix.com/)
* [Paypal Developer Blog](https://developer.paypal.com/community/blog/)
* [Pinterest Engineering Blog](https://medium.com/@Pinterest_Engineering)
* [Reddit Blog](http://www.redditblog.com/)
* [Salesforce Engineering Blog](https://developer.salesforce.com/blogs/engineering/)
* [Slack Engineering Blog](https://slack.engineering/)
* [Spotify Labs](https://labs.spotify.com/)
* [Stripe Engineering Blog](https://stripe.com/blog/engineering)
* [Twilio Engineering Blog](http://www.twilio.com/engineering)
* [Twitter Engineering](https://blog.twitter.com/engineering/)
* [Uber Engineering Blog](http://eng.uber.com/)
* [Yahoo Engineering Blog](http://yahooeng.tumblr.com/)
* [Yelp Engineering Blog](http://engineeringblog.yelp.com/)
* [Zynga Engineering Blog](https://www.zynga.com/blogs/engineering)

#### 출처 및 더 읽을거리

블로그를 추가하고 싶은가? 중복 작업을 피하려면 다음 저장소에 회사 블로그를 추가하는 것을 고려하라:

* [kilimchoi/engineering-blogs](https://github.com/kilimchoi/engineering-blogs)

## 작업 중

섹션을 추가하거나 작업 중인 섹션을 완성하고 싶다면 [기여](#기여하기)를 환영한다!

* MapReduce를 이용한 분산 컴퓨팅
* 일관된 해싱
* 스캐터-개더(scatter gather)
* [기여하기](#기여하기)

## 감사의 말

출처와 감사의 말은 이 저장소 곳곳에 밝혀 두었다.

특히 다음 분들께 감사한다:

* [Hired in tech](http://www.hiredintech.com/system-design/the-system-design-process/)
* [Cracking the coding interview](https://www.amazon.com/dp/0984782850/)
* [High scalability](http://highscalability.com/)
* [checkcheckzz/system-design-interview](https://github.com/checkcheckzz/system-design-interview)
* [shashank88/system_design](https://github.com/shashank88/system_design)
* [mmcgrana/services-engineering](https://github.com/mmcgrana/services-engineering)
* [System design cheat sheet](https://gist.github.com/vasanthk/485d1c25737e8e72759f)
* [A distributed systems reading list](http://dancres.github.io/Pages/)
* [Cracking the system design interview](http://www.puncsky.com/blog/2016-02-13-crack-the-system-design-interview)

## 연락처

이슈, 질문, 의견이 있으면 언제든 연락해 달라.

내 연락처는 [GitHub 페이지](https://github.com/donnemartin)에서 찾을 수 있다.

## 라이선스

*이 저장소의 코드와 자료는 오픈 소스 라이선스로 제공한다. 이 저장소는 개인 저장소이므로, 내 코드와 자료에 대한 라이선스는 고용주(Facebook)가 아닌 내가 부여하는 것이다.*

    Copyright 2017 Donne Martin

    Creative Commons Attribution 4.0 International License (CC BY 4.0)

    http://creativecommons.org/licenses/by/4.0/
