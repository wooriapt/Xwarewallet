---
title: Environmental Blockchain Incentive Solution White Paper
layout: default
category: [issues]
date: 2018-11-06
description: Environmental Blockchain Incentive Solution EBIS
---

### WhitePaper 
<!--
![_config.yml]({{ site.baseurl }}/assets/img/byc.png) 
-->
Invite Friends   
여러분의 단 한번씩의 조회나 찾기가  
[Naver] [2] 나 [Daum] [3]보다 [Google] [1]에서 트래픽이 10 배나 많아집니다. 

-------------------------------  

  [1]: http://google.com/     "Google"  
  [2]: http://www.naver.com/  "Naver"  
  [3]: http://www.daum.net/   "Daum Search"  

communication Channels  
[![_config.yml]({{ site.baseurl }}/assets/img/join_team_channel.png)](https://xwarewallet.slack.com/messages/C7RPB5D37/)
[#Slack Channels](https://xwarewallet.slack.com/messages/C7RPB5D37/)  

-------------------------------
### WhitePaper Agenda


- [Environmental Blockchain Incentive Solution(EBIS)](#environmental-blockchain-incentive-solution-ebis-)
    + [White Paper](#white-paper)
  * [Environmental Blockchain Incentive Solution Foundation](#environmental-blockchain-incentive-solution-foundation)
    + [Prologue 우리가 해결하려는 문제](#prologue-------------)
  * [1. 블럭체인이 하는 일](#1-----------)
      - [1.1 블럭체인 데이터와 디지털 자산](#11-----------------)
      - [1.2 디지털 자산과 암호화폐](#12-------------)
      - [1.3 암호화폐 발행과 활용](#13------------)
      - [1.3.1  토큰의 발행](#131--------)
      - [1.3.2  EST 발행목적](#132--est-----)
      - [1.3.3  토큰의 지급](#133--------)
      - [1.3.4  EST의 가치](#134--est----)
      - [1.3.5  EST의 활용](#135--est----)
  * [2. EBIS 란?](#2-ebis---)
      - [2.1 환경활동 보상 시스템](#21------------)
      - [2.1.1  환경활동 보상 프로그램 사례](#211-----------------)
      - [2.1.2  디지털 자산에 의한 보상(Blockchain Incentive Solution).](#212----------------blockchain-incentive-solution-)
    + [2. 2  EST(환경화폐)의 가치 근거](#2-2--est-------------)
      - [2.2.1  Kurutila 환경경제학  이론](#221--kurutila----------)
      - [2.2.2  사회적 비용과 경제적 가치](#222----------------)
      - [<환경정책의 비용/편익분석 지침서>, 환경운동연합 [편익추정기법들의 적용 사례]](#--------------------------------------------)
      - [<자전거 관련 경제성 연구 보고서>](#-------------------)
      - [2.2.3  EST 의 사회적 기여와 재원확보](#223--est---------------)
    + [2. 3  EQR 코드 생태(환경재 소비 인센티브)](#2-3--eqr-------------------)
      - [2.3.1  EQR CODE 란?](#231--eqr-code---)
      - [2.3.2  EQR CODE 가 바꾸는 세상](#232--eqr-code---------)
    + [2.4  EBIS 의 활용](#24--ebis-----)
      - [2.4.1  응용 프로그램](#241---------)
      - [2.4.2  광고](#242----)
      - [2.4.3  디지털 수집품](#243---------)
      - [2.4.4  사회 공헌](#244-------)
  * [3. 아키텍처](#3-----)
      - [3.1 합의 레이어(Consensus Layer)](#31--------consensus-layer-)
      - [3.2 보상 레이어(Profit Layer)](#32--------profit-layer-)
      - [3.3 등급 레이어(Grade Layer))](#33--------grade-layer--)
  * [4. 토큰 발행과 유통](#4----------)
      - [4.1  EST 발행 계획](#41--est------)
      - [4.2  EST 유통](#42--est---)
      - [4.3  EST 배분](#43--est---)
  * [5. 주요사업](#5-----)
      - [5.1 블럭체인 기반 공유자전거 개요](#51-----------------)
      - [5.1.1  공유자전거의 유용성](#511------------)
      - [5.1.2  국내 공유자전거 현황](#512-------------)
      - [5.1.3  한국과 중국의 공유자전거 이용실태 비교](#513-----------------------)
      - [5.1.4  도시별 인구대비 공유자전거 운영현황.](#514---------------------)
    + [5.2 공유자전거 운용시스템(www.bikepassport.net)](#52-------------wwwbikepassportnet-)
      - [5.2.1  운행 주정차 관리 시스템](#521---------------)
      - [5.2.2  공유자전거에 대한 사용자 및 관리자 접근](#522------------------------)
      - [5.2.3  모바일 앱 기반 서비스 개요](#523-----------------)
    + [5.3 계정관리(bikepassport )](#53------bikepassport--)
      - [5.3.1  계정관리 서비스](#531----------)
      - [5.3.2  사용인증](#532------)
      - [5.3.3  트랜잭션 서비스](#533----------)
      - [5.3.4  전자지갑 서비스](#534----------)
      - [5.3.5  작업 분배 보상 시스템(인센티브)](#535--------------------)
      - [5.3.6  개방형 플랫폼](#536---------)
      - [5.3.7  블럭체인의 데이터 저장](#537--------------)
      - [5.3.8  누적 보상 토큰 발행 (EST)](#538---------------est-)
      - [5.3.9  생태계의 확장](#539---------)
    + [5.4 자전거 인센티브와 누적 마일리지 활용](#54---------------------)
      - [5.4.1 정부와 지자체의 자전거 이용 인센티브](#541---------------------)
      - [5.4.2  EST 실적을 누적하여 환경활동 등급제 활용 ( ecopassport  활용)](#542--est------------------------ecopassport-----)
      - [5.4.3  프로모션 및 활성화 방안](#543---------------)
  * [6. 자전거 사업전망](#6---------)
      - [6.1 자전거 공급 계획](#61----------)
    + [6.2 손익 전망](#62------)
      - [6.2.1  매출 추정](#621-------)
      - [6.2.2  비용 추정](#622-------)
      - [6.3.3  추정 손익계산서  (단위 : 백만원)](#633----------------------)
  * [7. TEAM](#7-team)
      - [- Founder - CEO 이인형](#--founder---ceo----)
      - [- System Developer - 이름 | 나예준](#--system-developer-----------)
      - [- Management](#--management)
  * [8. Appendix](#8-appendix)
      - [8.1 면책 조항 및 기타 법적 성명](#81-----------------)
      - [8.2 참고문헌](#82-----)


------------------------------------------------------------------------------
