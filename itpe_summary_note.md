

프로세스

- 폭포수
- 프로토타이핑
- 나선형모델 - Spiral
- 반복적 개발 모델
  - incremental (증분형)
  - evolutional (진화형)
- RAD 모델
  - Rapid/Application/Development
  - Agile 방법론



SW,SI -> Methodology -> 개발 방법론. 

- 구조적 개발 방법론

- IE (정보공학)

- CBD

- Product Line(PL)

- Agile Process

  - Extreme programming
  - Scrum
  - Kanban
  - lean

  

사업수행 계획서 ( 프로젝트 관리 계획서 )

[13차시]

## SDLC

소프트웨어 개발 생명주기

타당성조사 / 분석 / 설계 / 개발 / 테스트 / 유지보수

생명주기 모델 선정 기준



## 폭포수 모델

고전전

순차적

후반에 가시화/구체화, 중요 문제점이 나중에 발견

테스트 

- 단 통 시 인 설 

## 프로토타이핑

의사소통을 통한 개발 모델 

요구사항 수집 기법 



## 나선형모델

계획및 정의 / 위험 분석 / 개발 / 고객 평가 ( 계위개고)



## 반복적 개발 모델

증분개발 모델 

진화형 개발 모델 



## RAD

소요일 : 60~90일 정도의 짧은 기간으로 기술적 위험이 적고 빠른 개발이 요구 될 때 적합 

**JRP (Joint Requirement Planning)I**

**JAD(Joining Application Design/Development)**

프로세스 

- Planning -> User Design / Construction -> Cutover (릴리즈)

XP / Scrum

TimeBoxing 



[14차시]

## SW개발 방법론

소프트웨어 개발/분석/설계/구축에 대한 정형화된 방법과 절차,도구 등이 공학적인 기법으로 체계적으로 정리하여 표준화한 이론 

구조적 기법 / 정보공학 기법 / 객체지향 기법 / CBD 기법 / Agile,XP,PL



## 정보공학 개발방법론(IE)

정보전략계획(ISP)

전사적 차원의 대규모 시스템 구축

절차

- ISP
- BAA
- BSD
- SC



## 객체지향 기법(OO)

실세계의 개체를 속성과 메소드의 결합된 형태의 객체로 표현하는 개념 

특징

- 캡추다정상



## 객체지향 설계 원칙

SOLID

- SRP
- OCP
- LSP(Liskov Substitution Principle)
  - 자식 타입들은 부모 타입들이 사용되는 곳에 대체 될 수 있어야 함. 
  - 자식 타입은 자신의 부모 타입으로 교체 될 수 있도록 설계해야 함. 
- ISP ( Inversion Segregation Principle)
- DIP

## 컴포넌트

실행 가능한 SW요소의 집합

COM ,CORBAR, EJB

COTS : 상업용 독립 컴포넌트 Commercial off-the-shelf

컴포넌트 추출 방법

- 핵심 클래스 기반 - Class Diagram
- 유즈케이스 시나리오 기반 

모듈 < 컴포넌트

플랫폼 독립적



## CBD



## Product Line

CBD의 연장선

**Core Asset**개발 -> Plug & Play -> Product Development

 

## 도메인 공학

= Product Line 



## 요구공학

요구 사항들이 각 Phase에 적용이 되었는지 검증하는 기법

초기에 정한 개발 요구사항들은 물론 이후 상세 요구 사항들이 제품 설계와 구현 단계에서 제대로 지켜지고 있는지를 **검증**해 나가는 기법 

요구사항 추출 주요 기법 

- 인터뷰 기법 
- 프로토타이핑 기법
- 브레인스토밍 기법
- 문서 분석 기법 
- 사용자 업무관찰 기법 
- 사회자 회의 기법  

요구사항 정의

- 요구사항 명세화
  - 원리
    - 명확/완전/검증가능/일관/ .. 
  - 명세 기술
    - 기능적 요구사항
    - 비기능 요구사항 - 신뢰성 / 보안성, 사용가능성 .. 

**요구사항 추적성**

- 요구사항 추적표
  - RFP ID - 시나리오테스트 ID 매핑



## AOP

OOP의 한계 극복

스프링프레임워크

등장배경 

- SRP는 현실에서 지키기 어려움. 
- 기능 개발 시 보통 여러가지 기능이 복합적으로 존재

부가적인 기능은 밖으로 빼서 필요할때 넣어줌(Weaving)

핵심관심(Core Concern) - 횡단관심(Crosscutting Concern) 분리 

핵심관심에 횡단 관심을 Weaving







## Agile

애자인 선언문 

애자일 12원칙 

Self-Organizing, Cross Functional Team



[16차시]

## XP

용단커피존

5개 핵심가치

- 용기/단순성/커뮤니케이션/피드백/존경

12 프렉티스

개발절차



## SCRUM

럭비의 진형을 스크럼이라 함. 

Product Backlog - Sprint Planning Meeting - Sprint Backlog - Sprint Iteration (2~4week)-Sprint Review & Sprint Retrospective

Scrum Master, PO, member

Daily Scrum 

BurnDown Chart



## KANBAN

workflow 시각화

WIP(work in process)



## LEAN

7가지 원칙

- **Eliminate waste**
- Amplify Learning
- Decide as Late as Possible
- Deliver as Fast as Possible
- Build Integrity In
- See the Whole



##CI/CD



## RFI, RFP



## SW분리발주

5억원 이상

<>일괄발주

의무화가 아님. 



## 소프트웨어 진흥법 개정안

정부가 발주하는 시스템 통합  사업에 대해 금액과 관계없이 공정거래법상 상호출자제한

- 국방-외교-치안-전력-국가안보와 관련된 것은 예외



[17차시]

**지식영역 10가지**

​	1 - 통합관리

​	3 - 범위관리, 일정관리, 비용관리

​	1 - 품질관리

​	H - 인력 관리 

​	C - 의사소통 관리

​	R - 위험관리

​	P - 조달관리

​	S - 이해관리자 과리 



**PMO** - Project Management Office

**포트폴리오 관리**

- 프로그램 관리 
- 프로젝트 관리 

**위험관리 절차**

- 위험 계획수립
- 위험 식별 
- 정성적 위험 분석 
- 정량적 위험 분석
- 위험 대응계획 수립 
- 위험 통제

**RACI** 매트릭스



##Project Management

**프로젝트의 특징 **

- 유일성
- 일시성
- 목적성
- 점진적 상세화

**프로젝트 관리 구성도**

**지식영역별 문제점과 해결방안**

- 통합관리 / 문제점 / 해결 방안 등 10가지 모두 





## 범위관리

범위관리 계획 수립 

요구 사항 수집 

- 요구사항 수집 5가지 
  - 인터뷰
  - ..

범위 정의 

작업 분할 체계(WBS)

-  인도물
- Scope Baseline 제시 

범위 확인(Validaion) -  V모델 참고 

범위 통제



[18차시]

## VV모델

검증 및 확인 



## 일정관리

1. 일정관리계획수립 : 진행률, 0/100, 50/50
2. 활동 정의(Activity == Task)
3. 활동 순서 배열 
   1. 관계 정의. eg : FS, SS, SF, 
4. 활동 자원 산정 -> 담당자 정함
5. 활동 기간 산정 ( == 원가 산정 기법 )
   1. 전문가 판단 방법 
   2. 3-point Estimation.
      1. P(pasmistinc), M, O(optimistic)
6. 일정 개발 
   1. 일정단축 기법
      1. Crashing
         1. 자원 추가 ( 사람 추가 또는 야근 )
      2. Fast Tracking
         1. 병행추진 
7. 일정 통제
   1. 감시 및 통제 프로세스에 속함. 



## CCM

Critical Chain Management

자원에 현실적인 제약조건을 포함시켜 현실적인 일정 관리를 하는 것



## 프로젝트 버퍼 

프로젝트가 성공하기 위해 반드시 필요함. 



## 원가관리

원가 산정 계획수립 - 원가 산정 - 예산 - 원가 통제 ( **EVM** )

EVM 반드시 이해



[19차시]

## SW형상관리 (SCM)

Software configuration management

BaseLine

- 계획 - 기능적 기준선
- 설치및 운영 - 운영 기준선

식통감기 

CCB 

- 갑을 간 형상관리 통제 



## 형상관리

Client-Server Model

- Commit/update 

Distributed Model

- push/pull



## Resource Management

####터크만 5단계 팀 개발 모델 

- 형성(forming)
- 스토밍(storming)
- 표준화(Norming)
- 수행(performing)
- 해산 (adjourning)



WBS <-> OBS ( 조직을 상하구조로 분류, 조직분류체계라고 함)

####프로젝트 관리자의 권력

역할이 부여하는 권력

- Formal Power :  의사결정할 수 있는 권력 
- Penalty Power : 불이익을 줄 수 있는 권한 

개인의 고유 권력

- Referent Power : 사람들이 따르고 존경하는데서 생겨남 
- Expert Power : 주요 분야에서의 기술력을 인정받는데서 생김 



####동기부여 이론 - 메슬로우의 욕구5단계 이론 

1. 생리적 욕구 - 의식주 
2. 안전의 욕구 - 신체적/감정적 안전에 대한 욕구
3. 소속감과 애정 욕구 - 사회적,인정받고 싶은 욕구
4. 존경 욕구 - 자기 만족, 내적/외적 성취감 욕구
5. 자아 실현의 욕구 - 자기발전, 자기 완성에 대한 욕구



#### 갈등해결기법

Problem Solving : 문제 해결

Forcing : 압박

Smoothing : 양보

Compromising : 서로 절충. 

Withdrawing : 회피





## Resource Leveling

소프트웨어 개발 단계별 드는 리소스가 다르다. 

이를 각 단계별 리소스가 비슷한 수준으로 되도록 리소스나

일정을 배치하는 것. 

- 자원 평준화는 위의 그림과 같이 특정기간에 과부하 된 자원을 활용가능한 범위 내에 분포하도록 자원을 분산하는 작업을 의미함. 



## Risk Management

1. Risk 관리**계획 수립** 
   1. 결과물 : 위험 등록
2. 위험 식별 : Risk Identification 
   1. 결과물 : 위험관리 대장 (Risk Register)
3. P*I 분석 - 정성적 위험 분석
   1. P : Provablity , I : Impact
4. 정량적 위험 분석
5. 대응 계획 수립



####Negative Risk 해결방안

- ATMA
  - A : Avoid 
  - T : Transform - 전가, 덮어씌움, 보험 
  - M : Mitigation : 완화, 수치를 다운시킴. 
  - A : Accept : 수용 

파생위험

잔여위험 



## PMO

####Project Management Office 

- Project / Program / Portfolio Management Office
- Type
  - Internal/External/Combined 
- R&R
  - The Weather Station Model ( 기상대 모델 )
  - Coach Model ( 지도 모델 )
  - Control Tower Model ( 관제탑 모델 )
- Position : PM의 투여시간 및 직위 구분 유형
  - Part-time PMO
  - Full-time PMO
  - PMO Director
  - President
- PMO Skill
  - 컨설팅, Developer, ...



####기능조직

#### Matrix 조직

- PM권한이 강함 - Strong Matrix
- PM권한이 약한 - Weak Matrix 

####Projectized 조직



## SOA

Service Oriented Architecture

- 기존 어플리케이션의 서비스를 조합함으로 새로운 어플리케이션을 구현할 수 있도록 한 통합 기술 및 아키텍쳐. 기반기술 -> REST
- 특징 (프플루협)
  - 프로세스 중심
  - 플랫폼 독립적
  - 루즈 커플링
  - 협업과 재사용
- ESB
  - Enterprise Service Bus
  - A-B 서비스 간 중개하는 서비스  
- EAI

모듈화 -> SOA -> Cloud Computing ( IT -> Servce 기반,  Xaas)

ESB -> CSB



SOA , CBD 비교 

[21차시]

## SW Architecture

#### 특징1

- 간략성
- 추상화
- 가시성

#### 특징2(2교시형)

- 비즈니스 측면
  - 변화민첩성
  - 비용절감
  - 표준화
- 기술적 측면



#### 등장배경, 필요성 템플릿



#### ISO/IEC/IEEE 42010  ( 구 IEEE1471 )

구성요소

- AD
- Concern
- ViewPoint
- View
  - 4+1 View
    - Implementation View
    - Deployment View
    - Process View
    - Logical View
    - Use-case View

#### 소프트웨어 아키텍쳐 프로세스

#### 소프트웨어 아키텍쳐 Docuement - SAD

#### 소프트웨어 아키텍쳐 스타일

- 저장소 구조 (Repository Architecture) :eg. 데이터베이스 시스템
- MVC 구조
- Client/Server 구조
- Data Flow 스타일
  - 서브시스템이 입력 데이터를 받아 처리하고 결과를 다른 시스템에 보내는 작업이 반복
- 계층구조 : eg. osi7 layer

#### SW아키텍쳐 평가방법

- Scenario based
- Simulation based

####SW아키텍쳐 평가 유형

- ####ATAM

  - Architecture trade off Analysis method 

- ####CBAM

  - Cost Benefit Analysis Method 
  - 평가까지 하여 수익이 최대가 될 수 있도록 의사결정을 도와주는 SW아키텍쳐 평가 모델 

- SAAM

- ARID



#### SW Architect



[22차시]

## UML

OMG에서 만들었고개발 언어와 상관없이 설계를 위한 Notation



##### UML 2.2

- UseCase Diagram
- Class Diagram
- Sequence Diagram
- Object Diagram
- Activity Diagram
- State Machine Diagram

정적 처리/동적 처리 구분 확인 

의존/연관/일반화/실체화 

의존관계

- 연관관계 - has a 관계
  - Aggregation - 전체/부분 관계
    - 부서 - 직원의 관계 같이 전체와 부분이지만 생명주기가 다름 
  - Composition - 전체/부분 관계
    - 생명주기가 같음. 
    - 차와 엔진의 관계 , 사람과 심장



####스테레오 타입(기술사 시험으로 나오지는 않음)

- boundary
- Include
- Control
- entitiy

####Sequence Diagram

- Actor
- Object(활성 객체)
- Message(메시지)
- Control Rectangle(제어사각형)

#### State Diagram

- 시작 / 종료 표시 주의 

#### Class Diagram

- 클래스의 정적 구조 표현 



#### Activity Diagram

활동의 흐름 표시 

분기는 마름모, 

시작, 종료, 분할(Fork), 구획면(Swim lane), 합류(join)

Event Trace라고도 함. 



컴포넌트 다이어그램 , 배치 다이어그램 

MOF모델



[23차시]

## 디자인패턴

에릭감마, 1990년대 초반

GoF의 분류가 많이 활용. 

소프트웨어 설계/구현에 있어 확장/재사용 성이 좋아지는 

생성/행위/구초 패턴으로 

5가지 원칙



## 생성패턴

#####추상팩토리

- 

빌더

프로토타입

싱글톤

팩토리 메소드 



#####Factory Method Pattern

- 부모에서 추상메소드 만들고 
- 자식에서 구현



##### 메멘토

- Snapshot , 별도보관 
- 객체를 이전의 상태로 복구시켜야하는 경우 사용. 



#### 템플릿 메소드

- 추상 클래스에서 메소드 ,알고리즘 골격 정의 



## TDD



## McCabe

복잡도를 계산하는 방법 

맥케스 회전복잡도 

v = e - n + 2 ( e는 간선, n는 객체)



[24차시]

## Test 

테스트 단계

- 단통시인설
- 단위 / 통합 / 시스템 / 인수 /설치 테스트 



명세기반테스트 = 블랙박스 테스트 

구조기반 테스트 = 화이트박스 테스트 

리스크 기반 테스트 

- 발생가능성 - Provablity , 영향-Impact 
- 즉 PI를 따져서 중요도가 높은것 먼저 테스트

테스트 오라클 : 참/거짓 판단하기 위한 미리 정의된 참값 대입하여 비교 하는 기법 

- 참 오라클
- 샘플링 오라클 
- 휴리스틱 오라클

PairWise Test 

Compliance Test - 준거성 테스트 

Substantive Test 

경험기반 테스트 (경탐오체분)

- 탐색적 테스트 
- 오류 추정 
- 체크리스트 기반 테스트 
- 분류트리 기법 

테스트 시각에 따른 분류

- V&V모델 
  - Verification
    - 개발자 혹은 시험자의 시각 
  - Validation 
    - 소비자 시각 

다중V-모델의 테스트 활동 



블랙박스 테스트 

- 동등분할 기법 
- 경계값 분석 기법 
- 의사결정 테이블 테스팅 
- 상태전이 테스팅 
- 유스케이스 
- 오류예측 기법 
- 원인-결과 그래프 기법 

화이트박스 테스트 

- 제어구조 시험.
  - 맥케프. V = E - N + 2
- 루프시험 



## Test Charter

Lessons Learned ( 스크럼의 회고 미팅)



## 성능테스트

TPS (Transactions per Second)

- 초당 트랜젝션 처리

#####Little's Law

- TPS = AU/MRT
- TPS = AU(Active User)/평균처리시간(Mean Response Time)
- TAM 으로 암기



유형

- 부하테스트
- 과부하 테스트
- 용량테스트





## 테스트 자동화

테스트 관리, 소스코드, 등 소프트웨어적으로 자동화 하는 것. 

테스트를 위한 업무파악으로 프로젝트 공정 지연 이슈

- 기획자가 직접 테스트
- 보안 테스트는 테스터가 하자. 



## Back to Back Test 

여러 프로그램을 만들고 동일한 입력을 넣었을 때 동일한 결과가 나오는데 확인

- 자동차, 항공기 분야 

## Test Coverage

#####테스트 계획서 

- Coverage

  - 얼마나 테스트가 충분한가를 나타내는 지표

- Statement 

- Condition 

- Decision

    

1. 커버리지 유형 

   1. Statement Coverage
      1. 가장 작은 수행 거버리지
   2. Decision Coverage
   3. Condition Coverage
   4. Condition / Decision Coverage
   5. Mutiple Condition Coverage - 모든 조건을 테스트
   6. MC/DC 

2. #####Multiple Condition Coverage, MC/DC 암기필요. 



## PoC ( Proof of Concept )

제품이 정말 유용한 것인지 시연하는 것 



[26차시]

## 응집도 / 결합도 

응집도

- 우논시절통순기
- 우연적/논리적/시간적/절차적

결합도

- 내용외제스자



## 3R

유지관리의 하위 토픽



- 역공학 : reverse engineering
- 재공학 : reengineering
- 재사용 : reuse

## SW유지관리

소프트웨어의 수명연장 목적 

개발비보다 유지관리비가 7,80 프로

분류

- 시점
- 원인 (수적완예)
  - 수정적 유지보수 : 프로그램 오류로 수정 
  - 적응적 유지보수 : 프로그램 환경변화에. S/W적응
  - 완전적 유지보수 : 특성변경, 기능추가에 따른 적응 
  - 예방적 유지보수 : 프로그램의 예측되는 오류 미리 처리 

유지보수 영역에서 가장 많이 수행되는 활동 

- 완전적 유지보수

리만의 S/W변과 원리

- 계속적 변경
- 복잡도 증가
- 대구모 프로그램 진화
- 조직의 안정화
- 친근성의 유지



## 리팩토링

마틴파울러 

소프트웨어를 보다 쉽게 이해할 수있고 적은 비용으로 수정할 수 있도록 겉으로 보이는 동작의 변화없이 내부 구조를 변경하는 방법. 

결과의 변경없이 코드의 구조를 재조정



시점

- 삼진추가
- 기능 추가 시 
- 버그 수정 시 
- 코드 리뷰 

Bad Smell

- 소프트웨어 품질속성을 저해하는 리팩토링이 필요한 코드의 패턴 혹은 코드 부분 
  - 중복코드
  - 긴 매쏘드 
  - 큰 클래스 

유형

- Inline Method 
  - 메서도 몸체가 메서드의 이름만큼이나 명확할 때 메서도 몸체를 필요한 곳에 바로 넣고 메소드는 삭제 
- Extract Method
  - 그룹으로 함께 묶을 수 있는 코드 조각이 있으면, 코드의 목적이 잘 드러나도록 이름을 지어 별도 메소드 분리 
- Extract Interface 
  - 인터페이스가 같은 부분을 사용하면, 인터페이스의 같은 부분은 추출하여 인터페이스를 통합 추출 적용 
- Move Method 
  - 메소드A가 자신이 정의된 클래스보다 **다른 클래스 CB의 기능을 더 많이 사용할 때** 이 메소드를 가장 많이 사용하고 있는 클래스에 비슷한 몸체를 가진 새로운 메소드CA를 만들고, 이전 메소드A는 간단한 위임으로 바꾸거나 제거



## 소프트웨어 난독화

Obfuscation



Layout

- Formatting Chagne
- Remove Comments
- Scramble Identifiers

Data

- Storage
- Aggregation - 하나의 클래스를 두개 이상으로 분리

Control

- 여러 루프를 나누거나 합침 
- 루프를 역순으로 사용 

Preventive

- 역난독화를 사용하지 못하게 만듦



[27차시]

## SW품질 관리

1+3+1+HCR + P + S



품질관리(Quality Management)

- 품질관리 계획 수립
  - 기신사요유희
    - ISO9126
  - CMMI - 북미방식
  - SPICE - 유럽방식
- 품질 보증 ( QA )
- 품질 통제 ( QC )





[28차시]

## 정보시스템 감리

#####정의 

- 감리발주자 및 피감리인의 이해관계자로부터 독립된 자가 정보시스템의 효율성을 향상 시키고 안전성을 확보하기 위해 제 3자적 관점에서 정보시스템의 구축(및 운영)에 관한 사항을 종합적으로 점검하고 문제점을 개선하도록 하는 제도 
- 발주자가 정보시스템의 **효율성 / 안정성**을 위해 3자적 관점에서 **시스템의 운영/구축**에 관한 사항을 점검/개선 

#####감리기준

- 공공기관에만 존재 
- 대국민 서비스 / 여러 행정기관 공동 구축 
- 정보시스템 구축비가 5억원 이상 경우 
  - 단순구입비 여부는 행정기관장 판단하며 단순구입비는 감리 기준 예산에 미포함 



##### 시행절차

- 감리법인 
- 발주기관
- 피감리인
- 산출물



기술사 또는 감리사만 수석 총괄감리원이 됨. 

상주감리원 - 프로젝트가 큰 경우

3단계 감리 / 2단계 감리

종합평가 -> 적합/부적합



## 감리관련 법제도 및 관련 기술

정보시스템 감리 기준 

감리기준 조문별 해설서



프레임워크 (암기필)

- 사업유형
  - EA/**SD**/DB/OP/MA
- 감리영역
- 감리관점/점검기준
  - 절차
  - 산출물
  - 결과

감리수행가이드

감리 단계 

**감리평가**

- 필수 / 협의 / 권고 



## OSS

- 조건 
  - 자유배포 / 소스코드 / 파생 저작물 (Derived Work)

 종류

- 저작권
  - GNU  General Public License 2.0
    - 자유소프트웨어 재단(Free Software Foundation, FSF)이 자신의 소프트웨어에 대한 저작권을 확보한 뒤, 이러한 권리를 전제로한 소프트웨어의 자유로운 공유 및 수정을 보장하기 위해 만들어진 License
    - **GPL을 가진 프로그램을 유료로 판매하는 것은 가능하지만, 반드시 전체 소스코드는 무료로 공개해야함**
    - 소프트웨어에 대한 자유로운 사용, 복제, 배포 및 수정을 허용.
    - 소프트웨어를 배포하는 경우, 저작권 표시, 보증 책임이 없다는 표시 및 GPL에 의해 배포 된다는 사실 명시
    - Linux를 기반으로 개발된 Application은 소스 공개할 필요 없음. 
    - 파생물 재공개해야함. 
  - **BSD**
    - 라이브러리 수정해도 소스 공개안해도 됨. 
    - 상용소프트웨어와 연결 가능성 
  - **LGLP**
    - 라이브러리 수정 시 라이브러리 소스는 공개해야함. 
    - 개발자가 만든 부분은 공개안해도 됨. 
    - 상용소프트웨어와 연결가능성. 



장점/단점 



OSHW - Open Source Hardware

- 아두이노
- 라즈베리파이



[29차시]

## SW비용산정

원가관리 프로세스

- 원가 관리 계획 > 원가 산정 > 예산 결정 > 원가 통제(EVM)



원가산정

- 3-point estimation. PERT방식(O, P, M)
- M/M, M/D, M/Y -> 민간기업
- Function Point - only IT에서만 사용, 공공에서 사용
- 계약전에 원가 산정 > 간이법
- 테이블까지 나오고난 후 > 정규법



계약방법

- 고정가 계약방식
- 원가정산 계약
  - 원가 이익 확보
  - 환율 등 변동가 고려
- T&M (Time & Material ) 계약 

예산결정

- 간접비, 기술비 포함. 



## Function Point 

기능점수 방식에 의한 소프트웨어 개발비 절차

1. 사전준비
2. 기능점수 산정 
3. 보정전 개발원가 산정 
4. 보정후 개발원가 산정 
   1. 보정요소 : 규모, 개발언어, 어플리케이션 유형, 품질, 특성
5. 직접 경기 및 이윤 산정
6. 소프트웨어 개발비 산정 



소프트웨어 규모 산정 방법

- 하향식 산정
  - 전문가 감정과 델파이 방식
- 상향식 산정
- 수학적 산정방법



#####국제 표준

- ISO/IEC 14143



FP절차

1. 측정유형 결정
   1. 개발/개선/어플리케이션
2. 측정 **범위**와 어플리케이션 **경계** 식별
3. 데이터 기능 측정
   1. 내부 논리 파일(ILF, Internal Logical File)
   2. 외부 인터페이스 파일(EIF, External Interface File)
4. 트랜젝션 기능 측정
   1. 외부 입력(EI, External Input)
      1. 디비 Query갯수
   2. 외부 출력(External Output)
   3. 외부 조회 (EQ, External Query)
5. 미조정 기능점수 결정
   1. 데이터 기능점수와 트랜젝션 점수의 합
   2. 미조정 기능 점수 * 조정인자 값(VAF)
   3. 합이 300보다 작으면 사용하는 공식 
      1. =>
   4. 합이 300보다 크면 사용하는 공식 
      1. =>



[30차시]

ILF

EIF

조회와 출력 -> EO, EQ

VAF 조정인자

정규법

- RET
- DET



## SW사업 대가산정 가이드 

개발원가의 25% => 이윤 



예비비 분석

- 프로젝트 예산 = 원가기준선 + 관리 예비비







[31차시]

## Web2.0

- 키워드 : 공유, 개방, 참여
  - SOA, 웹서비스
  - AJAX
    - 보안 취약점 있음. 
    - 7계층 프로토콜. http protocol 
  - WA(Web Accessiblity) : 웹접근성
    - 노인, 장애인 등 누구나 사용하기 편리한 성질 
    - WCAG : web contents access guide 
    - Mesh-up 서비스 : 다양한 서비스의 Open API를 혼합하여 새로운 서비스 창출
    - 서비스 API 사용 시 XML, SOAP, WSDL등 여러가지 프로토콜이 있는데 이를 사용하는 것이 아닌 http기반  get,post, form를 이용하는 것이 REST API임. 
- Web3.0
  - web2.0 + a
  - **Cloud 서비스**
    - Xaas
      - SaaS
      - IaaS
      - BaaS
    - 가상화 기술
      - Storage, Network, Computing
      - 하이퍼바이저
      - OpenStack - project또는 community
        - Nova
        - Keystone
        - 뉴턴
        - SDN. Software define network
      - Docker
  - 의미기반 검색
    - RDF ( Resource Description Framework)
    - 온톨로지 사전
  - 상황인식 컴퓨팅



[33차시]

전장장치

산업 소프트웨어 안전 기준

- IEC61508
- 자동차 : ISO26261
  - ASIL(A~D 등급)
    - Automative
    - Software
    - Integrity
    - Level

스마트 그리드

- AMI - Advanced Metering Infra

3D Prining 

4차 산업 혁명 : Industry 4.0 

- 기존 공장 + ICT + AI + IoT + Big Data
  - Smart Factory
    - CPS (Cyber Physical System)
      - ESS (Energe Storage System)

Computer Vision 

- Image processing
- 지능형 컴퓨터
- HDR



[34 차시]

## Web2.0

공유/ 개방/ 참여

## 웹접근성

4가지 특성 

- 인식의 용이성
- 운용의 용이
- 이행의 굥이 
- 견고성

WCAG 



## Mashup Service

A서비스, B서비스 연동해 하나의 새로운 서비스 만듦. 



##REST

Representational Sate Transfer

복잡한 RPC 대신 get, post ,put, delete이용



[35 차시]

## UX

사용자가 시스템 제품, 서비스를 직,간접적으로 이용하면서 느끼고 생각하게 되는 지각과 반응, 행동 등 총체적 경험 

페르소나



햅틱스

멀티 터치

멀티 모달 

ISO 9241-210 UX표준 



## 검색엔진

구글. 전세계 1위

중국 - 바이두

일본 - 야후 제팬

러시아 - 얀덱스

국내 - 네이버 / 다음 



웹크롤러(에이젼트) / 온톨로지 사전 / 시멘틱 검색/RDF



##RDF

rdf tag로 지정가능

1교시형 준비 



## Ontology 

웹상의 사전



## Semantic Web

의미기반의 검색 기술

시멘틱웹의 계층구조 암기 



## XML

XML의 구성도 암기. 

DOM, SAX

DTD && XML Schema



## DOM

XML문서 전체를 트리구조로 메모리에 로드 

SAX는 변수별로 Event Driven 구조. 

DOM / SAX 비교표 구조 



## DTD

Data Type Definition 



## XML Schema

- Name Space 지원
- xsd확장자
- Data Type만들기를 제공



## HTML5

2009년도

리치웹 응용 가능하게 해주는 HTML표준 

주요 기능

- 다양한 웹폼
- Canvas
- Geolocation API 지원 
- Local Storage, Cookie 의 4KB 제한 극복, 5M~15M까지 
- Web Workers
- Video/Audio
- 웹소켓



## 유틸리티 컴퓨팅

구성기술

- 클러스터
- 가상화
- 분할
- 프로비져닝
- 자율 컴퓨팅
- 그리드 



## 클라우드 컴퓨팅

인터넷을 통한 IT자원의 **On-Demand**  서비스

IT자원 + Xaas + Utility Computing + on Demand

**XaaS(Everything as as Service)**

- AaaS
- PaaS
  - DaaS
  - IaaS
- MBaaS



서비스 형태

- Public / Private / Community / Hybrid



Cloud PVR(Personal Video Recoder)

클라우드 발전법 정의

인터클라우드 (컴퓨팅)

- 클라우드와 클라우드를 연결

메타클라우드

- 클라우드 서비스를 사용자(개발자)에 맞게 개발,실행환경,환경 설정 등을 개발자의 요구 조건에 맞게 자유롭게 구성할 수 있도록 제시하는 통합 클라우드 시스템 모델 
- 등장배경
  - Lock In 문제
  - 통합 클라우드 시스템 모델 



## OpenStack

IaaS 형태의 클라우드 컴퓨팅 오픈소스 프로젝트

is a cloud operating system that controls large pools of Compute, storage, networking resources throughout a datacenter 

- 서버 관련 :  
  - Nova - 하이퍼바이저, VMWare
  - Glance - 
- 스토리지 : Swift, Cinder
- 사용자 : KeyStone, 중앙집중식 인증과 서비스 카탈로그 시스템 
- 네트워크 : Neutron : 가상네트워크 관리 SDN(Software Define Network)



**CSB - Cloud Service Broker**



## Meta Cloud (숙제) 



##서버 가상화

- 서버 가상화의 정의 
  - 서버를 가상 머신 형태로 제공 
  - 서버에 설치된 OS > 하이퍼바이저 > Guest OS
    - Guest OS - 전가상화 / 반가상화

## 데스크탑 가상화

- OpenStack
- Docker
- KVM

도커

- LXC
- 이미지 관리
- Container 

[37 차시]

## Fog Computing ( MEC mobile edge computing)

사용자가 원하는 근처에 서비스를 위치 시킴. 

네트워크 Edge 위치 시킴

마치 CDN과 같음. 

클라우드 컴퓨팅을 네트워크 Edge에 위치시킴. 네트워크 Edge를 Fog Nodes라 함. 



## 상황인식 컴퓨팅

상위 토픽 - 웹3.0

온도/습도 등 주위 환경

지능형 Agent, 신경망 



## 자율컴퓨팅

주요 기능 

- 자기구성
- 자기 치유
- 자기 방어
- 자기 최적화 



## Converged Infrastructure

컨버지드 인프라



## RFID

Radio Frequency Identification 



Tag - Reader(Active/Passive) - Server

Reader

- Active
- Passive



미들웨어 기술 

- Savant
- ONS
- PML Server



프라이버시 침해 이슈

[40 차시]

## ADAS(Advanced Driver Assistance System)

지능형 운전자 보조 시스템 

센서, 지피에스, 통신 장비 등 IT기술 접복 

요소기술

- 인지 / 판단 /제어 

차량용 임베디드 운영체제 OSEK

- 선점형 커널 .. 

AUTOSAR

-  구성요소
  - Software Component

IOV

- 커넉티드 카
- V2X 통신
  - WAVE
  - 클라우드 서비스 

스마트가 인포테인먼트 플랫폼의 주요 동향 

-  Android
  - OAA
- CarPlay
- Window in the Car
- AGL(Tizen)

자율주행 1~4단계

1단계 : 직접 운전

2단계 : 손,발 off, 눈 on

3단계 : 손,발,눈(conditionally) off

4단계 : 손,발,눈 off



## ASIL

IEC61508 - 산업 안전규격 

-  IOS26262 - 자동차 관련 



평가지표

- SEC
- S : Severity - 위험의 잠재적 심각도
- E : Exposure - 재난 상황에 노출 가능성 
- C : Controllablity - 통제 가능성 

SEC에 따라 등급을 A~D까지 정의해 놓은 표



## 텔레메틱스

통신기술과 정보과학의 합성어 

자동차와 외부와의 통신 기술 

무선 망을 통해 데이터/통신

11p, GIS/LBS, IPv6, WAVE



## u-Health

 PACS(Picture Archving and Communication System)

- 디지털 의료 저장/전송 시스템 

DICOM

- 진료 정보 데이터 수신/저장/전송에 대한 표준 

PHR

- 개인의 건강정보의 관리

HL7

- OSI 7과 같이 메시징 프로토콜 표준 



## Smart Grid

에너지 효율의 최적화

기존 발전소 - 게이트웨이 - IT망 연동(스마트 미터)

**AMI** - Advanced Metering Infrastructure

EMS

HAN

- Home Area Network

수요반응

보안



## 3D Printing

첨삭가공 생산방식

- 3D모델링
- STL Format변환
- Layer Slicing

재료

- SLA ( 액체 )
- SLS 파우더 기반
- FDM( Fuse Deposition Modeling )고체 기반



## BEMS

Building Energy Monitoring System

BAS



## ESS

에너지 스토리지 시스템 



[41차시]

## Industry 4.0 

스마트 팩토리

- 기존 설비 + 관리 시스템 
- IoT - Cyber Physical System - 

오프쇼어링 : 생산기지 해외 이전을 일컬음 

리쇼어링 : 해외 나간 기업을 다시 불러들이는 정책 



## CPS(Cyber Physical System)

사이버 세계와 물리적 세계의 통합 시스템

- 대규모 센서/액츄에이터를 가지는 물리적 요소와의 통신 / 응용S/W -> 실시간 사물 제어

사물들이 서로 소통하여 자동/지능적으로 제어되는 시스템 

연상,통신 제어가 결합되고 융합된 복합 시스템의 성격 + 와해성 기술의 특성

현재 산업을 재구성, 새로운 산업의 창출이 가능 



스마트 공장의 핵심 기술



## FEMS ( Factory Energy ManageMent System)

공장의 에너지 관리 시스템 

효율적 에너지 운용



## 산업 제어 시스템 

SCADA

- Supervisory Control and Data Acqusition
- 한국형 K-SCADA

한국전력

원격으로 산업시설 제어.



DCS

- 근접 시설 제어



PLC

- 소규모 산업 제어 시스템 



## 영상처리 도메인 

컴퓨터 비젼 / HDR / 영상처리 / 지능형 영상처리



## 컴퓨터 비젼

기술

- 영상처리 / 컴퓨터 비젼 / OpenCV ( 인텔에서 만듦)

## 영상처리

기법

- 확대/축소/회전
- 색보정합성
- 베이어 패턴
- 정합/변형/인식/분할
- HDR : 다수의 영상을 합쳐 새로운 영상 창출

지능형 영상분석

- 객체 추척
- 이벤트 탐지



## HDR

High Dynamic Range Imaging 

자연스러운 영상 보정 기술 

영상 합성 기술 



## 360도 카메라

전체 경치, 360도 방향의 모든 경지를 담아낼 수 있는 장치 



영상 획득 - 영상 생성 - 영상 재생 



## OLED (Organic Light Emitting Diode)

유기발광 다이오드

형광성 유기화합물에 전류가 흐르면 빛을내는 자체 발광현상을 이용하여 스스로 빛을 내는 디스플레이 기술 



특징

- 박막화(얇게 만드는 성질) 가능 
- 가벼움
- 야외에서 선명한 가독성 제공 
- 자체 발광이기에 명암비/색 재현력 우수
- 발광소자의 수명이 짧음 -> 번인 현상 발생 

번인 현상

- 특정한 화소가 타 버리면서 보기 싫은... 



구조

앞 - 유기재로 - 유리/폴리이미드 기관

[42차시]

## Gamification

게임화

게임이 아닌 영역에서 게임적 요소를 통하여 목적 달성을 위한 동기부여와 몰입을 극대화하는 제반 기술과 기법 

게임화의 부각배경

- 시장 - 체험재 수요 증가
- 기업 - 창의성/자율성 중시
- 기술 - 스마트폰/증강현실
- 인구 - 밀레니엄세대 부상 

구성요소

- 도전과제
- 피드백/보상
- 소셜 커넥션
- 인터페이스 

MMORPG

엔진 유형

- 렌더링 엔진
  - OpenGL / Direct3D
- 애니메이션 엔진
- 물리엔진
- 인공지능 엔진

기능성게임



## 금융기술 모데인

FinTech, 로보어드바이저, 블로겣인, 비트코인, 간편 결제



##로보어드바이저

로봇의 인공지능 어드바이저 역할 통해 투자관리 서비스 

투자자의 성향 분석



## 비트코인

Proof-of-Work => 채굴(Mining)

P2P키반의 가상화폐

분산 원장

P2P기반 분산 데이터베이스, 공개키 기반 방식의 거래구조

비트코인 개념도 

- 현재 트랜잭션의 타당성은 이전 트랜잭션의 공개키로 검증



## 블록체인

블럭체인의 구조

- 블럭헤더
  - 버젼
  - 이전 블록 해쉬
  - 타임 스탬프 : 블록이 생성된 시간
  - 머클루트 : 해당 블록이 포함된 거래로부터 생성된 트리의 루트에 대한 해쉬값
  - Nonce : 작업 증명을 위해 사용하는 카운터 값(4byte)
- 블럭 바디
  - 버다(거래내역) : 모든 거래 내역으로 이뤄진 트랜젝션값
  - 머클트리 : 거래 내역의 변조를 막기 위해 거래 내역을 해쉬로 만든 후 이것을 트리 형태로 만든 트리 = 해쉬 트리 

블록 바디의 크기가 커지는 문제점이 발생될 수 있음. 



Proof-of-work

- 특정 조건에 맞는 해쉬값을 찾는 과정이며 이때 해쉬 함수에 입력하는 것을 nonce라고 함. 
- 즉 즉정조건을 맞존 시키는 nonce값을 찾는 과정을 PoW라함. 
- 특정 조건에 맞는 해쉬값을 찾는 것이 쉽지 않으며 큰 Compute Power가 필요한 일이므로 이것이   일을 했다는 증명(Proof-of-work)가 되는 것
- PoW로 nonce로 찾아냄으로 코인을 획득하게 되므로 마이닝이라고도 함. 





## 드론

정보 수집.감시,정찰 활동의 새로운 패러다임 

주파수 대역 5000~5030MH, 15.4~15.7GH

가시선(Line of sight)

사람이 타지 않은 항공 기기 통칭 

기반 기술

- IMU
- ..

활용 사례

국내 드론 산업 규제

- 항공법 제23조
  - 12키로 이하는 신고 없음 
  - 150키로 초과는 등록 의무



## 가상현실 (VR)

## Docker

## BlockChain

## OLED 

## 컴퓨터비젼

## 디지털 트윈 



[52차시]

## MQTT

통신 대역폭이 한정적인 환경에서 동작 

모바일에 최적화된 Publish-Subscribe방식의 경량 메시지 프로토콜, 

Topic/Data 전송

TCP/UDP 레이어 

센서(Publisher)는 측정 데이터를 브로커에게 보낼 때 Topic 태그를 같이 보냄 

eg. "온습도센서/OO아파트/OOOO동/OOO호/거실/5번"





[53차시]

## CoAP

사물 인터넷 연결의 대표

M2M요구사항을 만족시키는 REST기반

저성능/저전력 

응용계층 프로토콜



## XMPP

XML기반의 실시간 메시지 교환 프로토콜



## LPWAN

IoT의 저성능, 저전력 설계 LPWAN

- 비전용망 방식
- 전용망 방식(ISM 대영)



## WoT(Web of Things)

웹으로 사물을 제어하겠다. 



## IoE



## 비콘

블루투쓰 4.0 프로토콜 기반으로 정확한 실내 위치 기반 차세대 근거리 무선 통신 기술 

동작원리 확인 



## WBAN(Wireless Body Area Network)

건강보조 의로 목적으로 인체에 장착된 디지털 기기들을 무선으로 연결, 인체를 중심으로 내외부 3M내에 자유로운 통신을 지원하는 근거리 무선 통신 기술 



## SDN

하드웨어와 소프트웨어를 분리 

OpenFlow



## SDx

SDN

SDS

SDDC

## OpenFlow ( 1교시형 준비 )

미래네트워크 제어 기술

구성요소

- 제어장치
- OpenFlow스위치
  - Flow Table	
    - **헤드 필드 / 액션 / 카운터 **
  - OpenFlow 프로토콜
  - 보안 채널 



## Supernetting / Subnetting





[56차시] 

## 디지털 시큐리티

개인정보 보호법 제30조에 따른 "개인정보 처리방침"에 반드시 포함되어야 하는 사항 5가지

- 개인정보 유효기관 

LEA(Light Enc~ Algorithm)

- 국산 암호화 알고리즘 



암호화

- 분류
- 블럭 / 스트림 암호화 
- DES / D-DES, Triple

AES

AAA

해쉬함수

접근제어

- Mac/Dec/RBac

XML보안 

OWASP10

- SQL-Injection 
- XSS
- CSRF

터널링

- 기밀성 제공 , 암호화 , 방화벽, NAT 

IP Masquerade

DMZ - DeMilitary Zone

IDS - Intrusion Detection System - 침입 탐지 시스템 

IPS - Intrusion Proejction System

internet - IDS - IPS -gateway - DMZ



[57차시]

보안의 3요소 :CIA 

- Confidential
- Integrity
- Availavility



SSO -> EAM -> IAM 

DLP - Data Loss Prevention 

공인인증서 

PKI

- RA : Registlation Authority
- CA : Certification Authority
- OCSP : 인증서 폐기관련 Protocol 

UTMS

- Unified Thtrats Manage System 
- 위헙으로부터 보호하는 관제 시스템 

생체 인식 - BioMetric Identification 

- FIDO

  - Online으로 빠르게 생체 인식으로 이용해 인증을 빠르게 해보자. 
    - UAF / U2F / CTAP

  

Common Criteria 

- 국제 보안 인증 레벨을 맞추기 위한 규격 

ISO27001 

ISMS - Infomation Security Manage System

- 정보보안 관리 시스템 

OAuth

- 제 3의 업체에 인증을 대행하는 서비스 

프로젝트 위험관리 프로세스

- 계획수립
- 위험 식별 
- 정성적 위험 분석
- 정량적 위험 분석 
- 위험 대응 계획 수립 
  - Negative Risk
    - ATMA
      - Avoid
      - Translate
      - Meetigation
      - A

PIMS

End Point 보안 

Hacking 

- 유형 : 
- Malware
  - Phishing
  - Pharming
  - APT (지능형 지속 위험 )
- Web Shall 
  - Hosting 
- Exploit공격
  - 설계상의 헛점을 이용한 공격 
- Ransomeware

Water Marking 

Finger Printing

- 유니크한 ID를 이용해 범죄자 추적 

DRM - Digital Right Management

PET - Privacy Enhancing Technology 개인정보 보호 기술

PIT - Privacy .. Technology 개인정보 침해 기술 



#####개인정보 영향 평가 

- Privacy Impact 

Digital Forensic 

신지식재산권

- 잊혀질 권리

NTP

- Network Time Protocol 



ICS ( Industry Control System)

- SCADA 
- DCS ( Distribute Control System)
- PLC ( Programmable Logic Controller )

Stuxnet 

- ICS같은 산업 제어 시스템을 파괴하기 위해 이스라엘/미국에서 만든 시스템 

오픈소스 보안 취약점 

SmartHome 보안 취약점 대응방안 

Quantum Encryption 

- QKD 

 AC - MAC / DEC / RBAC

OTP - One Time Password

LEA

얼굴인식 알고리즘 

프라이버시 보호 모델 

원격제어시스템(RCS)

공공아이핀 



[58차시]

## 암호화

 Feistel - SEED, DES

소인수 분해- RSA, 140자리 이상 

SPN 

타원곡선 - ECC 

이산대수

해시알고리즘  

-  MD-5 / SHA-1 / SHA-2
- 단방향성
- 보안강도는 충돌회피성에 의해 결정 

LEA - Lightweight Encrytion Alogorithm -  ARX

## 블럭암호화 알고리즘

E - ECB

C - CBC

C - 

O

C



###ECB

- Electronic Code Book
- P - BCE<Key> - C 
- C - BCE<Key> - P
- 구현간단/병렬처리 <> 

####CBC

- Cipher-Block Chaining
- **매 암호화마다 다른 "초기화 벡터"를 사용**
- 초기화를 위한 Vector값. 
- 출력값을 다른 P의 초기화 벡터로 사용. 

####CFB, OFB, CTR 





## DES

## SEED

128비트 평문 블록 - 16비트 블록으로 나눔 - 16회 라운딩 - 블록조합 - 암호문 

차분 해독법

선형 해독법 

SPN구조 

현재 256비트 

## AES

현재 민간 부분 상업 거래용의 사실상 표준 

미국에서 주로 사용 

레인달 알고리즘 

S-BOX

- 평문을 xor한 값을 가지고 BCF를 만들기 위한 표 

P-BOX

- BCF를 가지고 라운딩



##AAA

Authentication, Authorization, Account





[59차시]

## 해시함수

고정된 길이의 결과



#####압축성

#####제1 역상 저항성

- y값을 만드는 x를 알수 없음.

#####제2 역상 저항성

- y값을 만드는 x`도 알수 없음 

#####충돌저항성



## 접근제어

MAC

- 군대 계급별 인가 

DAC

- 사용자 본위로 접근권한
- 각 사용자별 권한 지정 방식

RBAC

- MAC , DAC의 혼합모델
- 권한관리,최소권한 모델 



##OWASP

Open Web Application Service ..



1. Injection
   1. SQL Injection
   2. 입력값에 대해 적절히 처리하지 않는 것이 원인 
2. 인증 및 세션관리 취약, Broken Authentication and Session Management
3. XSS
   1. Cross-Site Scripting 
4. 취약한 접근제어 Broken Access Control
   1. 인증된 사용자가 수행할 수 있는 작업에 대한 제한이 제대로 적용되지 않음
5. 보안 설정 오류 ,Security Misconfiguration
6. 민감데이터 노출 ,Sensitive Date Exposure
7. 공격방어 취약점
8. CSRF (Cross Site Request Forgery)
   1. 게시물을 서버에 등록하고, 로그인된 사용자가 자신의 의지와는 무관하게 공격자가 의도한 행위를 하게 만드는 공격
9. 알려진 취약점이 있는 컴포넌트 사용 
10. 취약한 API



## 터널링

송신자가 보내는 데이터를 캡슐화



## 방화벽

- 기능 
  - 접근제어
  - 프록시
  - 주소변환 

방화벽 구축 유형 

- 듀얼홈드 게이트 웨이 
- 스크린드 호스트 게이트웨이 
- DMZ
  - 내부/외부 망분리 

방화벽의 한계

- 침입 알람기능 
- 백도어 - 정상적인 포트 통해 들어오는 경우 막을 수 없음 
- 내부 사용자에 의한 취약점 



####웹방화벽 개념 -  WAF

- 웹 어플리케이션 보안에 특화 

- 주요기능
  - 사용자 요청검사
  - 컨텐츠 보호
  - 위장 
  - 다야한 웹 환경 지원 

##NAT

Dynamic NAT

- 주소풀에서 가져와서 사용 

Static NAT 

PAT이용한 NAT Overload 



### IP Masquerade

linux 최신버젼에서 지원 

###Port Fowarding 



## IDS

호스트 기반 HIDS

네트워크 기반 NIDS



탐지

- 오용침입탐지
  - 오류 패턴 기반으로 오류 확인 
- 이상침입탐지
  - 정상 패턴 이외에 모두 오류





[60차시]

## IPS

침입보호 시스템 

호스트기반/네트워크기반 

무선 -> WIPS 



## VPN

가상사설망

터널링을 통해 기밀성 제공 

- IPSec
- SSL 

구현기술

- 인증/터널링/암호화/키관리(eg. IKE. Internet Key Exchange)



## SSL

웹브라우저와 서버간에 안전한 데이터 전송 

https:// , 443포트 

SSL Record Protocol

- 기밀성제공, 암호화 메시지 인증

SSL Handshake Protocol 

- 세션키, 암호 알고리즘, 인증서 등의 파라미터 협상 

SSL Change Cipher Spec Protol

- 지금부터 SSL Handshake Protocol 에 정의된 대로 통신하는 것이라는 것을 알림 



#####SSL동작 원리 



## IPSec

AH - 인증 담당 

ESP - 기밀성 담당



모드 

- 전송모드
- 터널모드



## DLP

Data Loss Prevention 







[62차시]

## TRL (Technology Readlness Level)

IoT 관련 미국에서 사용하는 기술 성숙도

Level 1~ 9 

## MQTT

IoT 의 데이터 전송 기술

Messqge queuing telemetry transport

text 기반 

Publisher - broker - subscriber

Publisher 

- 센서로 측정한 데이터를 전송 
- topic 이라는 tag이용해서 전송 .

네트워크 4계층, TCP/UDP



## CoAP

7계층 기반 

Senser - proxy - server - client 



[64차시]

## FDS - 이상금융거래 탐지시스템

오미공패

이상탐지 모델 



## 잊혀질 권리 

잊혀질 관리 가이드 라인

사이버 망명 유사. 



## Kerberos

1,2,3 단계 인증 체계



## NTP

네트워크 타임 동기화 프로토콜

DoS에 취약함. monlist 로 취약점 패치





## 클라우드 서비스 취약점 및 대응 ( 숙제 )

관 -

물 - 

기 - AAA , AC, Enc, Network Security



클라우드 컴퓨팅 서비스의 보안 표준화 동향

- ISO/IEC 27017



## 산업재해 시스템

Stuxnet



## 오픈소스 보안 취약점

NTP

OpenSSL

- **Heart Bleed**
  - heartbeat이용

BashShell

- **Shell Shock**



## IoT 보안과 취약점





[65 차시]

## 양자암호화

Quantum Crytography



- 키 송수신전용 채널(Quantum Channel)을 이용하고 이때  키 분배 장치와 암호 장비가 필요.  
- 키 분배를 하고 키로 암호화된 데이터는 일반망 사용.
- 양자 암호통신 구성 
  - PC - [암호 장비 - 키분배장비(QKD)] - Quantum Channel - [암호 장비 - 키분배장비] - PC 
  - 암호장비간에는 암호화된 데이터 통신
  - 키분배 장비 간에는  키 송수신 채널(Quantum Channel) 이용
- SKT, KT상용화 단계 





## 128비트 경량블록 암호화LEA

ARX - Addition, Rotation, XOR 연산만으로 구성

암호화키 스케줄에 의해 암호화 

IoT연관 





## 얼굴인식 알고리즘 

PCA - 주성분 분석

FDA

ICA



## 프라이버시 보호모델 (중요)

K-익명성

- 주어진 데이터 집합에서 준식별자 속성값들이 동일한 레코드가 적어도 K개 존재 해야함. 
- 동질집합
  - 같은 준식별자 속성 값들로 익명화된 레코드들의 모임 

L다양성

t근접성

- 민감한 정보의 분포가 전체 데이터 집합의 그것과 너무 특이하지 않도록 함. 



## Buffer Overflow (출제 예상)



## 암호 공격기법 ( 1교시 출제 예상)

인지 기반 공격기법 분류 4가지

- 암호문 단독 공격 COA (Chphertext Only Attack)
  - 암호문을 가지고 평문이나 키 추적
- 알려진 평문 공격 KPA (Known Plaintext Attack)
  - 일정량 이상의 평문, 암호문을 가지고 공격
- 선택된 평문 공격 CPA (Choosen Plaintext Attack)
  - 평문 선택 시 암호문을 얻을 수 있음. 
- 선택 암호문 CCA (Choosen Ciphertext Attack)
  - 암호문 선택 시 평문을 얻을 수 있음