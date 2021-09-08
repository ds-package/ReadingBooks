# Atomic Design by Brad Frost

# `Chapter01.` Designing Systems

## An iterative process (반복 프로세스)

일부 이해 관계자가 "우리는 더 민첩하게 노력하고 있습니다"라고 선언하는 것을 분기마다 들어야한다면 이 책을 쓰는 대신 개인 우주선을 타고 지구를 공전할 것입니다.

더 민첩해지고 싶은 것은 칭찬할 만합니다.

그러나 애자일(agile)은 자본 A 애자일과 소문자 애자일(agile) 사이에 큰 차이가 있는 로드 용어입니다.

Capital-A Agile은 소프트웨어 개발을 위한 특정 방법론으로, Scrum 및 Lean과 같은 선언문과 그에 수반되는 프레임워크를 갖추고 있습니다.

소문자-a Agile은 효율적인 프로세스를 만들고자 하는 비공식적인 욕구에 가깝습니다.

이러한 바람에는 분명 자본 A 애자일의 일반 원칙을 채택해야 할 수도 있지만 애자일 프로세스 전체를 채택해야 하는 것은 아닐 수도 있습니다.

프로젝트 매니저 Brett Harned가 설명합니다.

>We want to be more agile; we’re embracing change, continuing improvement, being as flexible as possible, and adapting as we see fit. The thing is, we won’t ever truly be Agile, as the Manifesto states. That’s okay, as long as we say what we will be. 
>
>우리는 보다 민첩해지고자 합니다. 변화를 수용하고, 지속적으로 개선하며, 최대한 유연해지고, 적합하다고 생각하는 대로 적응하고 있습니다.중요한 것은, 우리는 결코 매니페스토에서 말한 것처럼 민첩하게 행동하지 않을 것이라는 것입니다. 괜찮아요, 우리가 될 거라고만 말하면 돼요.
>
> [Brett Harned](https://cognition.happycog.com/article/diy-process)


조직 구조, 고객 관계, 성격 등은 프로젝트의 프로세스를 결정하는 데 중요한 역할을 합니다.

비결은 귀사에 가장 적합한 프로세스, 즉 조직의 제약 조건 및 기회를 찾는 것입니다.

애자일 프로세스를 채택하는 것은 불가능할지라도, 여러 분야의 팀에서 작업하여 최종 환경에 더 빨리 진입하고, 자주 일찍 배포하고, 큰 작업을 더 작은 구성요소로 분할하는 것은 여전히 현명한 생각입니다.

4장에서는 효과적인 패턴 기반 워크플로우를 설정하는 방법에 대해 자세히 설명합니다.

<br/>
<br/>

## Modularizing content: I’m on Team Chunk (콘텐츠 모듈화: 저는 한 팀에 있습니다.)

>Get your content ready to go anywhere, because it’s going to go everywhere.
>
>콘텐츠는 어디든 갈 수 있습니다. 그러니 어디든 갈 준비를 해놓으세요.
>
> [For A Future-Friendly Web](https://bradfrost.com/blog/post/for-a-future-friendly-web/)


어디서나 컨텐츠를 사용할 수 있으므로 어디서나 컨텐츠를 사용할 수 있습니다.

예전에는 웹용 콘텐츠를 게시하는 것이 꽤 쉬운 일이었습니다. 데스크톱 웹이 시내에서 유일한 게임이었기 때문입니다.

자, 상황이 어떻게 바뀌었습니까?

오늘날 우리의 컨텐츠는 수많은 스마트폰, 멍청한 전화, 넷북, 노트북, 태블릿, 전자책, 스마트워치, TV, 게임 콘솔, 디지털 간판, 자동차 대시보드 등에 의해 소비되고 있습니다.

점점 더 다양해지고 다양한 디지털 환경을 적절히 해결하기 위해서는 컨텐츠에 대한 인식과 컨텐츠 관리에 사용하는 도구를 대폭 재검토해야 합니다.

앞으로 더 나은 콘텐츠 관리 및 콘텐츠 게시 도구를 갖게 될 것이라고 생각합니다.

>In the future, what I believe is that we are going to have better content management and content publishing tools. We are going to have ways to take well-structured content, welldesigned chunks of content that we can then figure out how we want to restructure and publish and display in a way that’s going to be right for the appropriate platform. 
>
>미래에는 더 나은 컨텐츠 관리 및 컨텐츠 퍼블리싱 도구가 개발될 것으로 생각합니다.
>
>우리는 잘 짜여진 컨텐츠와 잘 디자인된 컨텐츠 덩어리를 취할 수 있는 방법을 찾을 것입니다. 
>
>그런 다음 적절한 플랫폼에 적합한 방식으로 재구성하고 게시하고 표시할 방법을 찾을 수 있을것입니다.
>
>[Karen McGrane]()

다행히도, 이 미래는 형성되기 시작하고 있습니다.

조직은 고객이 어디에 있든 보다 효과적으로 고객에게 다가갈 수 있도록 모듈화된 콘텐츠를 제작해야 할 필요성을 인식하고 있습니다.

또한 컨텐츠 관리 시스템은 웹 퍼블리싱 플랫폼의 뿌리를 넘어 모듈형 컨텐츠를 우아하게 만들고 유지관리할 수 있는 도구로 발전하고 있습니다.

[NPR의 COPE(Create Once, Publish Everywhere) 플랫폼](https://www.programmableweb.com/news/cope-create-once-publish-everywhere/2009/10/13)과 같은 맞춤형 솔루션 형태로 정교한 콘텐츠 관리 시스템이 수년간 존재해 왔지만, 스마트 모듈식 사고는 주류 콘텐츠 관리 시스템으로 발전하고 있습니다.

<br/>
<br/>

## Classy code (세련된 코드)

앞에서 논의한 바와 같이, 모듈화는 컴퓨터 과학의 세계에서 오랫동안 주요 원칙이었습니다. 

웹이 발명되기 훨씬 전에 이 원칙이 존재했지만, 모듈화가 웹 개발자들의 마음과 가슴에 새겨지는 데는 시간이 좀 걸렸습니다.

1995년 이래로 웹의 프로그래밍 언어인 JavaScript는 오늘날과 같이 유능하고 존경받는 언어로 성숙하기 위해 몇 가지 성장통을 견뎌야 했습니다.

JavaScript가 성장함에 따라 개발자들은 이러한 검증된 컴퓨터 과학 원리를 웹 개발 워크플로우에 적용할 수 있습니다.

그 결과, 우리는 사람들이 정교한 [자바스크립트 패턴 ( JavaScript patterns )](https://addyosmani.com/resources/essentialjsdesignpatterns/book/)과 아키텍처를 개발하는 것을 목격하고 있습니다.

자바스크립트는 그 자체가 프로그래밍 언어이기 때문에 모듈식 프로그래밍 원리를 자바스크립트에 적용하는 것은 쉬운 일입니다.

그러나 객체지향적 사고는 웹의 스타일링 언어인 CSS를 포함한 웹의 다른 측면에도 영향을 미치고 있습니다.

[OOCSS](http://oocss.org/), [SMACSS](http://smacss.com/) 및 [BEM](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/)과 같은 방법론은 웹 디자이너가 모듈형 CSS 아키텍처를 만들고 유지 관리하는 데 도움이 됩니다.

<br/>
<br/>
<br/>


---

### [이전글 : 01.Designing Systems - 개요와 개념적인 내용](./01-DesigningSystems-01.md)

### 현재글 : 01.Designing Systems - An iterative process

### [다음글 :01.Designing Systems - Visually repaired](./01-DesigningSystems-03.md)