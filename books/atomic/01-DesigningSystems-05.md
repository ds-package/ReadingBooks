# Atomic Design by Brad Frost

# `Chapter01.` Designing Systems

## **Design systems save the day(하루를 절약해주는 디자인 시스템)**

그렇다면 강력한 설계 시스템은 어떻게 생겼을까요? 그들은 어떤 형태를 취하나요? 어떻게 그것들을 만들고, 유지하고, 집행하나요?

좋은 디자인 시스템의 초석은 가이드라인, 사용법, 가드레일(보호 난간)을 제공하면서 디자인 자료를 문서화하고 구성하는 스타일 가이드입니다.

브랜드 아이덴티티, 글쓰기(writing), 음성 및 톤(voice and tone), 코드, 디자인 언어(design language), 사용자 인터페이스 패턴 등을 포함한 다양한 종류의 스타일 가이드들이 있습니다.

이 책에서는 스타일 가이드의 모든 범주를 자세히 설명하지는 않겠지만 각 스타일 가이드가 다른 스타일 가이드에 어떤 영향을 미치는지, 웹용 스타일 가이드가 더 큰 생태계에 어떻게 적합한지 이해하기 위해 각 가이드를 살펴보는 것이 중요합니다.

<br/>

### **- Brand identity**

Brand identity 가이드라인은 회사를 고유하게 만드는 자산과 자료를 정의합니다.

로고, 타이포그래피, 색상 팔레트, 메시지(예: 사명 선언문 및 태그라인), 보조 자료(예: 명함 및 PowerPoint 템플릿) 등은 브랜드 아이덴티티 지침에 집계되고 설명됩니다.

![West Virginia University’s brand style guide.](/image/atomic/01-DesigningSystems-01-img07.png) _웨스트 버지니아 대학교의 브랜드 스타일 가이드._

---

브랜드가 점점 더 많은 미디어, 채널 및 접점에서 응집력 있는 방식으로 자신을 표현하는 것은 필수적입니다.

조직 내의 모든 사람이 어떻게 한 목소리로 말하고 단일 개체의 일부라고 느낄 수 있습니까?

타사에서는 어떤 팬톤 색상을 사용할지 그리고 브랜드 로고를 올바르게 사용하는 방법을 어떻게 알 수 있을까요?

브랜드 아이덴티티 가이드라인은 하나의 중앙 허브에서 이러한 근본적인 질문에 대한 답변을 제공합니다.

역사적으로 브랜드 정체성 지침은 하드 커버 책자(페이지와 관련된 내용을 기억하십니까?)에 포함되어 있었지만, 다른 모든 것과 마찬가지로 브랜드 스타일 가이드는 온라인에서 사용되고 있습니다.

<br/>

### **- Design language(디자인 언어)**

브랜드 아이덴티티 가이드라인은 상당히 촉각적이지만 디자인 언어 가이드라인은 파악하기가 조금 더 어렵습니다.

디자인 언어 스타일 가이드는 특정 프로젝트 또는 제품에 대한 일반적인 디자인 방향, 철학 및 접근 방식을 명확하게 설명합니다.

Google은 점점 더 다양한 제품과 미디어에서 응집력 있는 방식으로 자신을 표현하기 위해 [머티리얼 디자인(material design)](https://material.io/design/sound/about-sound.html#principles)이라는 디자인 언어를 개발했습니다.

머티리얼 디자인 스타일 가이드는 중요한 디자인 철학, 목표 및 일반 원칙을 정의하는 동시에 머티리얼 디자인 언어의 특정 응용 프로그램을 제공합니다.

![Google’s material design language.](/image/atomic/01-DesigningSystems-01-img08.png) _Google’s material design language._

---

디자인 언어 스타일 가이드는 높은 수준의 개념을 좀 더 구체화하기 위해 다른 스타일 가이드 범주의 측면을 통합할 수 있습니다.

디자인 언어 지침은 브랜드 지침과 달리 제대로 설정되어 있지 않습니다.

예를 들어, 언젠가 Google은 머티리얼 디자인을 대체할 새로운 디자인 언어를 개발할 것이므로 Google의 전체 브랜드는 그대로 유지되지만 제품을 둘러싼 디자인 용어는 바뀔 것입니다.

<br/>

### **- Voice and tone(목소리와 톤)**

사람들은 다양한 채널과 미디어를 통해 브랜드와 상호작용합니다.

지금까지 논의한 디지털 미디어 외에도, 브랜드는 인쇄, 소매, 아웃도어, 라디오, TV 및 기타 채널에서도 운영됩니다.

브랜드가 매우 다양한 접점을 통해 소통해야 할 때, 통일되고 일관된 방식으로 말하는 것은 브랜드의 성공에 매우 중요합니다.

> A brand’s voice stays the same from day to day, but its tone has to change all the time, depending on both the situation and the reader’s feelings.
>
> 브랜드의 목소리는 매일 똑같지만, 상황과 독자의 감정에 따라 그 음색은 시시각각 변해야 합니다.
>
> [- Kate Kiefer Lee](https://www.slideshare.net/katekiefer/kkl-c-sforum)

목소리는 브랜드 아이덴티티의 기본적인 측면입니다. 그래서 일반적으로 브랜드 아이덴티티 가이드라인은 브랜드의 목소리에 대한 일부 참조를 포함합니다.

그러나 이러한 지침은 일반적으로 매우 뉘앙스가 없기 때문에 목소리 및 톤 지침이 매우 중요합니다.

목소리 및 톤 가이드라인은 회사의 목소리와 톤이 다양한 시나리오에서 어떻게 변화해야 하는지를 명확히 함으로써 문제를 해결합니다.

<br/>

![MailChimp’s voice and tone guidelines2016](/image/atomic/01-DesigningSystems-01-img09.png) _MailChimp’s voice and tone guidelines-2016_

[MailChimp의 훌륭한 목소리와 톤 가이드라인(MailChimp’s brilliant voice and tone guidelines )](https://styleguide.mailchimp.com/voice-and-tone/)은 브랜드의 톤이 콘텐츠 유형에 따라 어떻게 변하는지 정의하며, 따라서 사용자의 신용카드가 거부되었을 때, 작가들은 그들의 일반적으로 건방지고 장난스러운 톤에서 벗어나 대신 더 진지한 톤을 채택할 줄 압니다.

![MailChimp’s voice and tone guidelines2021](/image/atomic/01-DesigningSystems-01-img10.png) _MailChimp’s voice and tone guidelines-2021_

<br/>

### **- Writing(작문, 글쓰기)**

웹 및 콘텐츠 관리 웹 사이트의 증가로 조직 내의 많은 사람들이 콘텐츠를 게시하기가 그 어느 때보다 쉬워졌습니다.

물론, 이것은 양날의 칼이 될 수 있습니다. 왜냐하면 많은 목소리를 가진 조직을 위해 일관된 문체를 유지하는 것은 어려울 수 있기 때문입니다.

작문 스타일 가이드는 모든 작성자에게 콘텐츠 기여에 대한 몇 가지 지침과 보호 난간(가드레일)을 제공합니다.

![The Economist’s writing style guide](/image/atomic/01-DesigningSystems-01-img11.png) _[The Economist’s writing style guide](https://www.economist.com/frequently-asked-questions) : 지금은 이미지와 같은 사이트로 제공되지 않으며 책으라 판매하는 듯 하다ㅠㅠ[판매링크바로가기](https://www.aladin.co.kr/shop/wproduct.aspx?ItemId=129940710)_

작문 스타일 가이드는 구두점과 문법에 대한 세부 사항을 정의하는 등, 매우 세부적일 수 있지만 항상 그렇게 상세할 필요는 없습니다.

[Dalhousie University의 작문 스타일(Dalhousie University’s writing style guide)](https://www.dal.ca/faculty/arts/spanish/for-current-students/writing---style-guides.html) 가이드는 콘텐츠 기고자가 따라야 할 원칙과 모범 사례에 대한 간결한 목록을 제공합니다.

<br/>

### **- Code style guides**

팀이 읽기 쉽고 확장 가능하며 유지 관리 가능한 코드를 작성하는 것은 필수적입니다.

그러나 코드 일관성을 촉진하고 시행할 방법이 없으면 상황이 무너지기 쉽고 모든 개발자가 스스로 해결해야 합니다.

![GitHub’s code style guide](/image/atomic/01-DesigningSystems-01-img12.png) _GitHub의 코드 스타일 가이드는 조직 내에서 HTML, CSS, 자바스크립트, 루비를 작성하기 위한 모범 사례를 제공합니다._

코드 스타일 가이드는 팀이 코드에 접근하는 방법에 대한 규칙, 패턴 및 예를 제공합니다.

이러한 지침과 가드레일은 광기를 억제하는 데 도움이 되므로 팀이 조잡하고 일관성이 없는 코드를 리팩토링하는 대신 함께 훌륭한 작업을 생성하는 데 집중할 수 있습니다.

---

### [이전글 : 01.Designing Systems - Trouble in framework paradise](./01-DesigningSystems-04.md)

### 현재글 : 01.Designing Systems - Design systems save the day

### [다음글 :01.Designing Systems - Pattern Libraries](./01-DesigningSystems-06.md)
