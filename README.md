# Introduction

엔지니어링 래더 프레임워크는 소프트웨어 엔지니어 매니저가 각각의 직책에 대한 기대치와 커리어 래더를 통해 자신의 직원, 동료들과 다음 단계를 계획하는 방법에 대해 의미있는 대화를 나눌 수 있도록 돕습니다.

엔지니어링 래더는 미국의 기술 산업에서 사용되는 역할과 레벨을 기준으로 사용하고 있지만, 회사별로 조금씩의 차이는 존재할 수 있습니다. 따라서 해당 내용들을 기본 베이스라인으로 생각하고 각자의 상황과 조건에 맞추어 적용하길 바랍니다.

엔지니어링 래더는 주어진 역할에 대한 다양한 관점과 기대치를 시각적으로 보여주기 위해 아래의 레이더 차트에 의존합니다:

![Template Chart](charts/template.png)

# Career Ladders

프레임워크에는 서로 다른 4개의 래더가 있습니다:

* [**Developer**](Developer.md): 높은 수준의 기술적 전문성을 필요로 합니다.
* [**Tech Lead**](TechLead.md): 시스템의 소유자이며, 실무와 아키텍쳐 지식 및 제품(Production) 지원간의 고유한 균형을 요구합니다.
* [**Technical Program Manager**](TechnicalProgramManager.md): 여러 팀을 확장하는 계획들을 조정하고 추진하는 역할을 담당합니다.
* [**Engineering Manager**](EngineeringManager.md): 팀의 일관된 배포, 경력 성장 및 행복 수준을 담당합니다.

만약 [Tech Lead](TechLead.md)와 [Engineering Manager](EngineeringManager.md)의 차이점에 대해서 혼란스러우시다면, [Tech Lead vs Engineering Manager](TechLead-EngineeringManager.md) 에서 비교한 내용을 참조해 주세요.

| Level | Seniority | [Developer](Developer.md) | [Tech Lead](TechLead.md) | [Technical Program Manager](TechnicalProgramManager.md) | [Engineering Manager](EngineeringManager.md) |
| :---: | :---: | :---: | :---: | :---: |  :---: |
| 1 | Junior | [D1](Developer.md#d1---developer-1) | | | |
| 2 | Junior | [D2](Developer.md#d2---developer-2) | | | |
| 3 | Junior | [D3](Developer.md#d3---developer-3) | | | |
| 4 | Senior | [D4](Developer.md#d4---developer-4) | [TL4](TechLead.md#tl4---tech-lead-4) | [TPM4](TechnicalProgramManager.md#tpm4---technical-program-manager-4) | |
| 5 | Senior | [D5](Developer.md#d5---developer-5) | [TL5](TechLead.md#tl5---tech-lead-5) | [TPM5](TechnicalProgramManager.md#tpm5---technical-program-manager-5) | [EM5](EngineeringManager.md#em5---engineering-manager-5) |
| 6 | Senior | [D6](Developer.md#d6---developer-6) | [TL6](TechLead.md#tl6---tech-lead-6) | [TPM6](TechnicalProgramManager.md#tpm6---technical-program-manager-6) | [EM6](EngineeringManager.md#em6---engineering-manager-6) |
| 7 | Senior | [D7](Developer.md#d7---developer-7) | [TL7](TechLead.md#tl7---tech-lead-7) | [TPM7](TechnicalProgramManager.md#tpm7---technical-program-manager-7) | [EM7](EngineeringManager.md#em7---engineering-manager-7) |

(각 포지션의 이름을 클릭하면 자세한 내용을 확인 할 수 있습니다.)

# Axes

위에서 보여지는 차트에 속한 5가지의 축:
* **Technology**: 기술 스택 및 도구에 대한 지식 
* **System**: 시스템의 소유권 수준
* **People**: 팀과의 관계
* **Process**: 개발 프로세스에 대한 참여 수준
* **Influence**: 역할의 영향 범위

**influence** 축은 다른 모든 축에 직교하여 적용되기 때문에 *다른 차원* 으로 볼 수 있습니다.

각각의 축은 5가지의 다른 성과 단계가 있습니다. 모든 레벨은 이전의 내용들을 포함하고 있다는 것은 중요한 부분입니다. 예를 들어, 기술을 *전파(evangelizes)* 하는 사람은 기술을 *전문화(specializes)* 하고 *도입(adopts)* 하는 것 역시 합니다.

각 레벨을 잘 이해하기 위해 계속 읽어주세요.

# Levels

## Technology

1. **Adopts**: 팀이 정의한 기술과 도구를 적극적으로 배우고 적용합니다
2. **Specializes**: 한가지 이상의 기술을 잘 알고 있으며 새로운 기술을 주도적으로 학습합니다
3. **Evangelizes**: 연구 조사, 개념 증명(POC)을 만들고, 새로운 기술을 팀에 소개합니다
4. **Masters**: 시스템의 전체 기술 스택에 대해 매우 깊은 지식을 가지고 있습니다
5. **Creates**: 내부 혹은 외부의 팀이 널리 사용할 신기술을 디자인 하고 만듭니다

## System

1. **Enhances**: 시스템의 개선 및 확장을 위해 새로운 기능을 개발하고 버그를 수정합니다
2. **Designs**: 중형에서 대형 사이즈의 기능을 기술 부채를 제거하면서 디자인하고 구현합니다
3. **Owns**: 프로덕션의 운영 및 모니터링에 대한 책임을 가지며 SLAs 를 알고 있습니다 
4. **Evolves**:미래의 요구사항을 지원할 수 있도록 설계를 발전시키며 SLAs 를 정의합니다
5. **Leads**: 시스템의 기술적 우수성을 주도하고 시스템 중단을 최소화하기 위한 계획을 수립합니다

## People

1. **Learns**: 다른 사람들로부터 빠르게 학습하고 그것들을 필요로 하는 업무들을 지속적으로 수행해 나갑니다
2. **Supports**: 다른 팀원들을 적극적으로 지원하고 성공할 수 있도록 돕습니다
3. **Mentors**: 다른 사람들을 멘토링하여 경력 성장을 가속화하고 참여를 독려합니다
4. **Coordinates**: 효과적인 피드백을 제공하고 토론을 주도합니다
5. **Manages**: 팀원들의 커리어, 기대 수준, 성과, 행복 수준를 관리합니다

## Process

1. **Follows**: 팀 프로세스를 따르고 일관적으로 제품에 기능을 제공합니다
2. **Enforces**: 팀 프로세스를 수행하면서 모든 사람들이 프로세스에 대한 장점과 단점을 이해하는지를 확인합니다
3. **Challenges**: 팀 프로세스를 개선할 수 있는 방법을 찾고 시도해봅니다
4. **Adjusts**: 피드백을 듣고 팀 프로세스를 조정합니다. 그리고 그러한 변화를 통해 팀을 가이드합니다
5. **Defines**: 팀의 성숙도에 맞는 올바른 프로세스를 정의하고, 민첩성과 규율의 균형을 맞춥니다

## Influence

1. **Subsystem**: 하나 이상의 서브 시스템에 영향을 끼칩니다
2. **Team**: 특정 부분만이 아니라 팀전체에 영향을 끼칩니다
3. **Multiple Teams**: 당신의 팀 뿐만 아니라 다른 팀에 영향을 끼칩니다
4. **Company**: 전체 기술 조직에 영향을 끼칩니다
5. **Community**: 기술 커뮤니티에 영향을 끼칩니다

# FAQs

**만약 일부사람들이 모든 포인트를 충족하지 못하는 경우엔 어떻게 될까요?**

그러한 상황은 매우 정상적인 상황이며, 사람들은 일반적으로 일부 영역에는 강하고, 일부 영역에서는 약합니다. 프레임워크는 승진을 위한 체크리스트로 사용되어서는 안되며, 대신 의미있는 경력 대화를 나누기 위한 지침으로써 사용되어야 합니다.

**제가 속한 조직 내의 커리어 래더가 위에서 언급된 내용과 다른 경우에는 어떻게 하나요?**

프레임워크는 오픈소스이기 때문에, 조직에 따라 조정될 수 있습니다. [chart template](charts/template.png)을 사용해 자신의 레벨을 정의해 보세요.

**다음 단계로 넘어갈 준비가 된 때는 언제입니까?**

회사는 일반적으로 한 사람의 승진을 공식화하기 전에 *몇 달 동안 지속적으로* 다음 레벨의 역할을 수행하기를 기대합니다.

**부하 직원과의 토론을 뒷받침하는 증거를 수집하려면 어떻게 해야 합니까?**

각각의 팀들은 각각의 방법으로 증거를 수집합니다. 권장되는 접근 방식은 다음 조합을 사용하는 것입니다:
* 1:1 대화
* 동료 및 다른 팀으로 부터의 피드백
* 자체 평가 (자가 진단)

**프레임워크가 각 레벨을 지원하기 위한 행동 예시들을 제공해 줄 수 있나요?**

구체적인 행동에 대한 예시는 팀의 업무 방식, 시스템 아키텍처와 기술 스택에 대한 지식을 필요로 합니다. 각 팀이 그들만의 예시를 정의할 수 있도록 하는 것을 권장합니다.

**프레임워크 각 단계의 레벨이 7이 끝인 이유는 무엇인가요?**

8 이상의 레벨은 회사마다 크게 다릅니다. 다양한 규모의 조직은 그 조직 구조에서 높은 위치에 있을 수록 다양한 수준의 범위를 할당하는 경향이 있습니다.

**해당 주제에 대한 추가적인 자료가 있나요?**

* [The Manager's Path](http://shop.oreilly.com/product/0636920056843.do): Camille Fournier는 많은 엔지니어링 직책에 대한 기대치와 과제에 대해 잘 설명하고 있습니다. 또한, 그녀는 챕터9에서 커리어 래더에 대한 좋은 조언들에 대해 다룹니다.

* [How to Be Good at Performance Appraisals](https://store.hbr.org/product/how-to-be-good-at-performance-appraisals-simple-effective-done-right/10295): Dick Grote는 직무 책임을 정의하는 방법과 성과 (결과 및 행동)를 평가하는 방법을 간단한 용어로 설명합니다

# Other Pages

* [**Developer**](Developer.md)
* [**Tech Lead**](TechLead.md)
* [**Technical Program Manager**](TechnicalProgramManager.md)
* [**Engineering Manager**](EngineeringManager.md)
* [**Tech Lead vs Engineering Manager**](TechLead-EngineeringManager.md)
* [**Managing Managers**](Managing-Managers.md)
