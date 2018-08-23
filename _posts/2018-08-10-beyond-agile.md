---
layout: post
title: "스타트업의 Workflow. Agile? Is that right?"
author: "Tylor Shin"
categories: workflow
tags: [workflow, startup, agile]
image: wrongWorkflow.png
---

# 스타트업의 Workflow. Agile? Is that right?

지난 몇 년 간 IT 스타트업에서는 agile workflow를 적극적으로 도입해왔다. XP든, 스크럼이든, 칸반이든, 여러 방법론은 모두 agile-like한 과정을 만들려는 방법에 대한 고찰이었다.

애자일한 워크플로우 아래서 우리는 공격적이고 짧은 스프린트가 가져오는 압박 아래 고효율의 성과를 만들기 위해 노력해왔다. 소위 말하는 팀(또는 개인)의 퍼포먼스는 포인트, 처리 티켓 수 등으로 **정량화**되었고, 이를 **효과적으로 관리**하려고 했다.

여기서 주목할 점은 이 모든 사고와 방법론의 끝이 생산성 향상과 workflow를 지속적해서 개선하는 데에 집중되었다는 것이다. 이런 방법론들은 소프트웨어 개발 방법론이기 때문에 개발 프로세스에만 초점이 맞춰져 있었다. 이러한 프로세스는 지금까지 제품 개발에 자체에서는 꽤 좋은 효과를 봤다. (여기서 간트 차트의 실패나, 스크럼 포인트 계산의 허구 등을 이야기하면 애자일이 너무 아플 거 같으니 넘어가자.)

그런데 과연 이러한 방식이 스타트업에서 일하는 방식과 맞을까?

스타트업에 몸담고 있는 사람들은 XXX 회사는 프로덕트 팀은 참 좋은데 잘 안 풀리네요- 와 같은 말을 한 번 쯤은 들어봤을 것이다. 그리고 XXX에는 현재 스타트업 대부분이 들어갈 수 있다고 생각한다. 이는 제품을 제대로 만들고, 유지/보수 하는데 뜻대로 돌아가지 않는다는 식으로도 해석이 된다. 이게 맞는 말일까? 진짜 우리는 제대로 제품을 만들고 있는 걸까?

한 번 더 생각해보자.

애자일에서도 워터폴, 혹은 더 전통적인 산업에서와 다를 바 없이 분업과 프로세스 개선, 예측 가능한 업무 단위들을 강조한다. 개인적으로, 경험적으로 위와 같은 가치들을 강조했을 때 개인은 미시적인 프로세스에만 매몰되는 경향이 발생하기 십상이다. 

다시 말해, 애자일하게 돌아가는 팀은 개인(팀)에게 주어진 일을 효율적이고 빠르게 처리해서 고객에게 전달하는 것 하나만 생각하게 되도록 유인된다. 이 프로세스(시스템) 안에는 원인도, 방향도, 왜라는 질문도, 고민도 없다. 어느 순간 이후부터 개발자들은 어떻게 하는게 더 좋은 퍼포먼스를 낼지, 메모리를 아낄 수 있을지, 어떻게 서비스 아키텍쳐를 구성해야 하는지만 생각하게 된다. 물론 이는 당연히 필요한 일이고, 중요한 일이다. 하지만 나는 개발자도 더 깊은 depth까지 고민하고 욕심을 부려야 한다고 생각한다.

개발 과정의 처음부터 끝까지 참여하는 모든 사람이 지금 하고 있는 일이 실제로 왜 필요한 일이며, 어떤 결과를 바라고 있고, 유저에게 어떤 가치를 주고, 어떻게 어느 시점에 완성, 배포되어야 최적의 효과를 볼 수 있을 것인지 등등을 고민하고 끊임없이 되물어야 제대로 된 서비스가 나올 수 있는 확률이 높아질 것이라 생각한다.

이러한 문제를 애자일이나 전통적 방법론에서나 해결하는 방법은 비슷하다. PM이나 기획자가 중간에서 계속 바른 방향으로 유도하고, 오해와 왜곡을 막기 위해 주기적으로 다양한 직군이 모여 스프린트 미팅이나 회고를 한다. 그리고 위 과정이 이상적으로 이루어지지 않는 이상 슬프게도 아래와 같은 결과가 나타난다.

![wrong workflow result example]({{ site.github.url }}/assets/img/wrongWorkflow.png)

커뮤니케이션만으로는 이 문제를 해결할 수 없다고 생각한다. 위와 같은 커뮤니케이션에는 각 role이 가지는 입장이 들어갈 수밖에 없고, 결국 각자의 문제를 해결하는 데로 초점이 맞춰지기 때문이다. PM이나 기획자가 계속해서 상기시키더라도 이상적인 커뮤니케이션이 잘 이루어지기 어려우며, 그들에게 다른 팀원들을 설득시키고 바른 방향으로 유도하는 슈퍼맨이 되기를 강요한다. 

또한 어떤 방식으로 일하든 커뮤니케이션과 미팅은 당연히 해결되어야 하는 문제이다. 이는 본질적으로 왜? 라는 의문을 계속 던지게 하는 시스템과는 다른 차원의 문제다.

문제는 현재 task와 프로젝트 사이의 align과 문제 제기가 끊임없이 이루어져야 한다는 것이다.

스타트업일수록 이 문제는 더 중요하다.

스타트업이 만드는 제품은 기존 시장에서 커버하지 못하던 것을 지원하거나, 아니면 훨씬 뛰어난 가치를 전달해야 한다고 생각한다. 또 프로젝트나 팀에 따라 조금은 다르겠지만, 요즘 스타트업이 하려는 일들은 제품만으로는 되지 않는다. (decentralization 배경이면 더욱 그렇다. 사회 문제를 제품만으로 해결할 수 있을 것으로 생각하지 않는다.). 사회 혹은 시장의 상태, 사회적 변화 촉구와 제품의 사회적 영향력 등에 대한 진지한 고민과 끊임없는 성찰이 무엇보다 중요한 시대가 된 것 같다. 더 이상 제품을 만드는 것, 기획, 전문가, 이런 식으로 RNR을 나누는 것은 좋아 보이지 않는다. 개발자가 개발에만 신경 써서는 안된다는 이야기다.

처음에는 이 문제가 뛰어난 개인의 자질 혹은 적절한 보상으로 해결될 것으로 생각했다. 전통적으로는 프로젝트에 관심이 많고, 역량이 뛰어나거나 key role을 수행하는 사람들에게 스톡옵션과 같은 보상을 주어 흔히 말하는 주인의식을 갖게 하는 방법을 택했다. 

이는 어느 정도 유효한 듯 보였으나, 실패한 시스템이라고 생각한다. ownership과 보상 체계는 다른 차원의 이야기다. 실제로 이는 stock을 가진 사람 중에서도 몇몇 사람들만 주인의식을 갖거나, stock과 관계없이 주인의식을 갖지 못하거나, 갖더라도 미시적 문제 해결에만 매몰되는 결과를 보였다. 아니면, 주인의식을 갖더라도 그 발현이 '난 개발자니깐 집중해서 좋은 성과를 내는 것이 나의 Role을 제대로 하는 거야'로 나타날 수도 있다.

그럼 어떻게 해야 맞는 방향으로 일을 할 수 있을까?

평소 일하고, 피부로 느끼는 workflow system이 개선되면 이러한 문제들이 어느정도 해결되지 않을까 했다. 그리고 전통적인 workflow에서 해답을 찾기보다는 우리가 원하는 조건들을 먼저 생각해보기로 했다.

새로운 workflow는 다음과 같은 조건을 만족해야 한다.

**전제조건**

- 의사결정, 문제해결에 필요한 모든 정보는 '쉽고 투명하게' 공유되어 있어야 한다.
  - 3 depth 이상 내려가는 정보는 공유되어 있다고 보기 어렵다.
  - 특정 권한이 있는 사람만 볼 수 있는 정보는 공유된 정보가 아니다.
  - 팀원 모두가 자신이 경험했던 일들을 공유하고 이러한 행동이 장려되는 시스템이여어야 한다.
  - 팀이 수평적이라는 것은 지위와 호칭의 위계질서가 없다는 것이 아니라, 누구나 필요한 정보에 접근 가능하며, 자유롭게 아이디어를 낼 수 있는 상태를 의미한다.
- 정보가 잘 문서화되어 있고 공유되어 있다면 다음과 같은 이점이 있다.
  - 이전에 했던 삽질을 반복하지 않는다. (다른 누군가가 했던 실패를 반복하지 않는다.)
  - 팀 안에서만 문제를 해결하는 것이 아니라, 관심 있는 누구라도 참여해서 이바지할 수 있다.(decentralization 향을 살짝 첨가...)
- Project vision 과 goal이 명확하게 공유되어 있어야 하며, 적어도 구성원들 모두에게 내재화되어 있어야 한다.
  - 이는 task가 만들어지는 과정부터 task 내의 의사결정에 이르기까지 여러 갈등과 의사 결정의 기준점이 되어준다.

**요구조건**

- 누구나 project에 도움이 되는 idea를 낼 수 있어야 한다.
- idea들은 실제 발제자와 idea에 공감하는 사람들을 중심으로 task로 만들어져야 한다. 그래야 같은 문제의식을 공유한 사람들이 최소한의 커뮤니케이션 비용으로 해당 task를 주체적으로 해결할 수 있을 것이다. 또한, 시스템적으로 이러한 ideation을 장려하는 incentive structure가 필요하다.
- 팀원이 아니라 외부의 누구라도 관심 있고 해결하고 싶은 문제라면 참여할 수 있어야 한다. 만약 팀 내부에서 문제를 해결할 수 있는 사람이 없다면 해당 task를 진행하는 인원들의 합의로 외부 인사를 초청해서 문제를 해결하는데 장벽이 있어서는 안 된다. 이렇게 task를 진행한 사람들은 fair한 보상을 받아야 한다.
- task들은 병렬적으로 진행되어야 하며, 그러한 와중에 우선순위에 맞춰 수행되어야 한다. 또한 이러한 진행 과정은 쉽게 시각화돼서 누구나 알 수 있어야 한다.
- task가 종료되었을 때, task 중 있었던 경험과 성공, 실패와 관련된 것들은 기록되고 공유되어야 한다.

개인의 입장에서도 왜 스타트업에서 일하고 있는가를 한 번 더 생각해보면 좋겠다. 주체적인 문제 해결, 피부로 와닿는 기여, 밀도 있는 개인의 성장 등 우리가 추구했던 것들은 거시적이고 주체적으로 사고할 때 더 얻기 쉬울 것으로 생각한다. 

노파심에 다시 말하지만 이 글은 '주인의식을 갖자!' 같은 의미를 전달하고자 하는 것이 아니다. 문제 해결을 하는 데 있어 시스템적 개선이 필요하다는 것이 주된 내용으로 전달되었으면 좋겠다. 

우리 팀도 아직 완벽하게 개선된 workflow를 만들거나 구체화하지는 못했다. 그렇기 때문에 이렇게 배경과 생각을 공유하고, 이로 말미암아 업계 전반적으로 같은 고민을 하는 사람들이 많아졌으면 좋겠다고 생각한다. 우리 팀을 비롯한 다른 많은 팀이 다양한 시도를 하고, 실패와 교훈을 공유한다면 더 발전된 workflow의 모습이 조금씩 나타나지 않을까 한다.