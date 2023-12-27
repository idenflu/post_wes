# Overview

Warehouse Execution System(WES)와 Warehouse Control System(WCS)은 물류 업계에서 창고 운영을 최적화하는 데 사용되는 두 가지 주요 시스템입니다. 각 시스템은 고유한 역할을 수행하여 창고의 효율성을 향상시킵니다.
먼저, WES는 창고 내 작업을 중심으로 최적화를 수행합니다. 주문 처리, 피킹, 상품 이동과 같은 작업을 자동화하고 조율하여 창고 작업을 효율적으로 관리합니다. 자동화된 장비와의 원활한 통합, 작업 일정 관리, 작업 경로 최적화 등의 기능을 제공하여 전반적인 운영을 최적화합니다.
한편, WCS는 창고 내의 자동화 장비를 직접적으로 제어하고 관리합니다. 컨베이어 시스템, 로봇, AS/RS와 같은 자동화 장비의 동작을 조율하며, 이들이 효과적으로 작동할 수 있도록 지원합니다. 주로 하드웨어 제어와 관련된 작업에 중점을 두어 창고 내 자동화 시스템을 효율적으로 운영합니다.
두 시스템은 상호 보완적으로 협력하여 창고 운영의 효율성을 극대화하는 데 기여합니다.

![](wmsweswcs.png)

## WES / WCS
- WES : WES는 AS/RS(자동창고)와 로봇을 조율하여 상품의 위치를 최적화하고, 주문에 따른 작업 일정을 효율적으로 관리합니다.

- WCS : WCS는 AS/RS와 로봇의 동작을 직접적으로 제어하며, 상품을 보관 및 이동시키는 과정을 효율적으로 관리합니다. 또한, 자동화된 시스템 간의 통합을 지원하여 전체적인 창고 운영을 최적화합니다.

## WES with IDENFLU
상황에 따라 WES(Warehouse Execution System)와 WCS(Warehouse Control System)의 기능이 혼합되어 하나의 시스템으로 구성되기도 한다.

### 설비유형 구분
1. 보관
   - AS/RS(미니로드, 셔틀, 플로우, 모바일, 캐로젤)
   - 선반-렉
1. 이송
    - 컨베이어
    - AGV/AMR
    - OHT
1. 분류
   - 소터류(틸트, 크로스벨트, 볼/휠)
   - DAS
1. 피킹/패킹
   - 팔렛타이저/디-팔렛타이저
   - DPS
   - 인케이싱
   - 제함기
   - 봉함기
1. 지원
   - BCR
   - 오토라벨러
   - 바코드프린터
   - 무게측정기
   - 단-적재/분리기