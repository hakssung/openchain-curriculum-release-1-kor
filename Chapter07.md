# Chapter 7. Avoiding Compliance Pitfalls

## Compliance Pitfalls

This chapter will describe some potential pitfalls to avoid in the compliance process:

1. Intellectual Property (IP) pitfalls
2. License Compliance pitfalls
3. Compliance Process pitfalls

> Compliance 위험

> 이 장에서는 Compliance Process에서 피해야할 몇가지 잠재적인 위험에 대해 설명한다. 

> 1. 지적 재산 (IP) 관련 위험
2. License Compliance 관련 위험
3. Compliance Process 관련 위험

## Intellectual Property Pitfalls

- Type & Description
  - Unplanned inclusion of copyleft FOSS into proprietary or 3rd party code: 
    - This type of failure occurs during the development process when engineers add (or cut and paste) FOSS code into source code that is proprietary (to you to you or to a third party) in conflict with your FOSS policies.
- Discovery
  - This type of failure can be discovered by scanning or auditing the source code for possible matches with:
    - FOSS source code 
    - Copyright notices
  - Automated source code scanning tools may be used for this purpose
- Avoidance
  - This type of failure can be avoided by:
    - Offering training to engineering staff to bring awareness to compliance issues and to the different types and categories of FOSS licenses and the implications of including FOSS source code in proprietary source code
    - Conducting regular source code scans or audits for all the source code in the build environment (proprietary, 3rd party and FOSS)

> 지적 재산 관련 위험
- 유형 및 내용
  - Proprietary 혹은 3rd Party Code내에 의도치 않은 Copyleft FOSS의 포함: 
    - 이러한 유형의 오류는 개발 과정에서 개발자가 FOSS 정책과 맞지 않는 형태로 FOSS Code를 Proprietary Source Code에 추가(혹은 잘라서 붙여넣기)할 때 발생한다. 
- 발견 방법
  - 이러한 유형의 오류는 다음과 일치할 가능성이 있는지 Source Code의 Scanning 혹은 Auditing을 통해 발견할 수 있다. 
    - FOSS Source Code
    - 저작권 고지
  - 이 때, 자동화된 Source Code Scanning Tool이 사용될 수도 있다. 
- 회피 방법
  - 이러한 유형의 오류는 다음과 같은 방법으로 피할 수 있다. 
    - 개발자들이 Compliance 이슈, 다양한 유형/종류의 FOSS License, Proprietary Source Code내에 FOSS Source Code를 포함시키는 것의 결과에 대해 인식할 수 있도록 교육을 제공한다. 
    - Build 환경의 모든 Source Code (Proprietary, 3rd Party, FOSS)에 대해 주기적인 Source Code Scan 및 Audit을 수행한다. 

## Intellectual Property Pitfalls

- Type & Description
  - Unplanned linking of copyleft FOSS into proprietary source code in certain cases  (or vice versa):  
    - This type of failure occurs as a result of linking software (FOSS, proprietary, 3rd party) that have conflicting or incompatible licenses. The legal effect of linking is subject to debate in the FOSS community.
- Discovery
  - This type of failure can be discovered using the dependency tracking tool that allows you to discover linkages between different software components.
- Avoidance
  - This type of failure can be avoided by:
    1. Offering training to engineering staff to avoid linking software components with licenses that conflict with you FOSS policies which will take a position on these legal risks
    2. Continuously running the dependency tracking tool over your build environment

> - 유형 및 내용
  - 의도치 않게 Copyleft FOSS를 Proprietary Source Code에 Linking하는 경우 (혹은 그 반대 경우): 
    - 이런 유형의 오류는 충돌 혹은 호환되지 않는 License의 Software(FOSS< Proprietary, 3rd Party)를 서로 Linking하는 결과로 발생한다. Linking에 대한 법률적 효과는 FOSS Community에서 논쟁의 대상이다. 
- 발견 방법
  - 이런 유형의 오류는 Dependency Tracking Tool(Software Component들 간의 연결관계를 보여주는 Tool)을 이용해 발견할 수 있다. 
- 회피 방법
  - 이런 유형의 오류는 다음과 같은 방법으로 피할 수 있다.: 
    1. 개발자에게 FOSS 정책과 맞지 않는 형태로 Software Component를 linking하는 것을 피할 수 있도록 교육을 제공한다. 
    2. Build 환경에서 Dependency Tracking Tool을 지속적으로 실행한다. 

- Type & Description
  - Inclusion of proprietary code into copyleft FOSS through source code modifications 
- Discovery
  - This type of failure can be discovered using the audits or scans to identify and analyze the source code you introduced to the FOSS component.
- Avoidance
  - This type of failures can be avoided by:
    1. Offering training to engineering staff
    2. Conducting regular code audits

> - 유형 및 내용
  - Source Code 수정을 통해 Proprietary Code를 Copyleft FOSS에 포함
- 발견 방법
  - 이런 유형의 오류는 Audit 혹은 Scan을 이용하여 FOSS Component에 도입한 Source Code를 식별 및 분석하여 발견할 수 있다. 
- 회피 방법
  - 이런 유형의 오류는 다음의 방법을 통해 피할 수 있다. 
    1. 개발자에게 교육 제공
    2. 주기적인 Code Audit 수행

## License Compliance Pitfalls

- Type & Description 
  - Failure to Provide Accompanying Source Code
- Avoidance
  - This type of failure can be avoided by making source code publishing a checklist item in the product release cycle before the product becomes available in the market place.
- Type & Description 
  - Providing the Incorrect Version of Accompanying Source Code
- Avoidance
  - This type of failure can be avoided by adding a verification step into the compliance process to ensure that the accompanying source code for the binary version is being published.
- Type & Description 
  - Failure to Publish Accompanying Source Code for FOSS Component Modifications 
- Avoidance
  - This type of failure can be avoided by adding a verification step into the compliance process to ensure that source code for modifications are published, rather than only the original source code for the FOSS component

> License Compliance 관련 위험

