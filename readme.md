
## 왜 Markdown 문서인가

사실 Markdown 같은 도구가 중요하다기보다는 Markdown을 통해 개발자들이 쉽게 위키 문서를 생산해 낼 수 있다는 것이다. 2014년에 NHN으로 이직 후에 놀라웠던 점은 개발환경에 대한 표준 가이드가 있다는 것, 빌드&배포, 모니터링 등을 돕는 사내 플랫폼과 협업을 위한 프로세스 등이 이전에 근무하던 회사와 비교했을 때 잘 갖추어져 있었다는 것이었다. 

> 이전 근무지였던 JCE에서는 이런 부분들이 왜 필요한지에 대한 경험을 뼈저리게 할 수 있어서 역시나 좋았지만...

하지만 그 무엇보다도 가장 관심이 갔던 것은 사내의 Wiki 서비스였다. 그 이유는 평소에 회사에서 업무를 하면서 내가 가장 치열하게 했던 고민을 아주 쉬운 방법으로 해결하고 있었다는 것이다.

> 바로 이거야! 

다양한 구성원들과 협업을 할 때에는 프로젝트를 시작하기에 앞서 우리가 하는 일이 왜 필요한지에 대해 서로 이해하고 의견을 좁혀나가는 것이 가장 중요하다고 생각한다. 이전의 경험에서는 여기에 대한 갈증이 많은 상태였는데 Wiki 서비스를 통해서 개발자들이 자신의 경험을 손쉽게 정리하고 자연스럽게 다른 사람들이 볼 수 있는 구조를 통해 소통하고 있었다. 

그래서 이후부터는 업무에 필요한 정보를 Wiki 페이지에 정의하고 함께 Overview & Review 하는 것을 시작으로 하위에 필요한 업무 및 기술적 요소들을 점진적으로 정리해 나아가는 습관을 기를 수가 있었다.

---

**Markdown이 무엇이죠?**

Markdown은 마크업 언어의 일종인, 존 그루버(John Gruber)와 아론 스워츠(Aaron Swartz)가 만들었다. 읽기도 쓰기도 쉽다는 장점이 있다. 확장자는 .md를 쓴다. 간단히 말해 문서를 쓰는 하나의 방법이라고 해두자. 아래의 페이지를 보면 쉽게 이해 할 수 있다.

**Github Markdown Guide**
- https://guides.github.com/features/mastering-markdown/

<br>

## 왜 Github에서 문서를 관리하기로 하였나

- 먼저 문서관리에 대한 즉 정보의 단절에 대한 문제이다. 사내에서 작성한 문서는 기본적으로 회사의 자산이지만, 사내에서 진행한 프로젝트를 통해 얻은 경험을 개인적으로도 지속적으로 리마인드 할 수 있었으면 했다. 프로젝트 진행을 하면서 학습한 내용부터 운영 노하우까지.. 미련하게 문서를 제대로 관리하지 못해 정말 너무 아쉽다 (..)


- 가장 중요한 요소는 이렇게 쌓인 Reference는 나와 같은 Junior 개발자에게 본인이 스스로 성장하기 위한 발판을 마련해 줄 수 있다는 것이다.


- 프로젝트만 레거시 시스템이 있는 것은 아니라고 생각한다. 지속적인 리마인드를 위해서는 이전 글에서 현재까지의 경험을 반영하여 더 나은 문서를 생산해 나아가야 한다.

- 혼자 하는 것이 아니라 Github에서 문서를 관리하고 공유해서 다른 개발자들의 참여를 이끌어 낼 수 있지 않을까?

<br>

## 그래서 어떤 주제를 다루지?

Swift를 통해 iOS 개발을 하면서 겪는 경험을 시작으로 기술문서를 작성할 예정이다. 그 이외에 관심 있는 카테고리를 미리 정해놓고 순차적으로 기술문서를 작성하고 다른 개발자들이 문서를 작성할 수 있도록 오픈한다. 

각 주제에 대해 처음 접근하는 개발자를 위한 내용이 대다수가 될 것이며, Wiki 페이지의 구조는 크게 **카테고리**와 **문서**로 이루어져 있다.

| Category | Description |
| --- | --- |
| [AWS](https://github.com/wjdsupj/stunstun-wiki/tree/master/AWS) | AWS 및 인프라 전반에 관한 지식 |
| [Android](https://github.com/wjdsupj/stunstun-wiki/tree/master/Android) | Android 개발에 관한 지식 |
| [BugFixedDiary](https://github.com/wjdsupj/stunstun-wiki/tree/master/BugFixedDiary)| 버그 픽스 기록을 남긴다기보다는 어떻게 문제를 인식하고 해결해 나아갔는지를 중점으로 기술한다. |
| [Fundamentals](https://github.com/wjdsupj/stunstun-wiki/tree/master/Fundamentals) | 개발자에게 밑천이 되는 소프트웨어 공학 전반 |
| [Git](https://github.com/wjdsupj/stunstun-wiki/tree/master/Git) | Git에 대한 사용 경험과 그 밖의 협업도구에 대한 이야기 |
| [Java](https://github.com/wjdsupj/stunstun-wiki/tree/master/Java) | Java의 기본지식 및 Java8에 대한 내용 |
| [Spring Framework](https://github.com/wjdsupj/stunstun-wiki/tree/master/Spring) | Spring Framework에 대한 지식, Spring Boot과 Spring 5.0 에 대한 인사이트 |
| [iOS](https://github.com/wjdsupj/stunstun-wiki/tree/master/iOS) | Swift를 통한 iOS 개발에 관한 지식 |

<br>

## 어떻게 참여할 수 있나요?

이 문서의 내용에 대해 공감하시는 모든 분들은 카테고리 또는 문서를 추가하거나 수정할 수가 있습니다. 언제든지 가벼운 마음으로 Pull Request 해주시면 됩니다.
- https://github.com/wjdsupj/stunstun-wiki/

> 누구나 새로운 주제나 문서를 생성할 수 있습니다.

**Requried**

- 최상단의 폴더명은 다루고 싶은 주제에 대한 카테고리명을 뜻한다.
- 모든 카테고리는 이 주제가 왜 필요한지에 대한 readme.md 문서를 포함해야 한다.
- 모든 문서의 파일명은 영문 소문자로 이루어지고 확장자는 md이다. 파일명에 띄어쓰기가 필요할 때에는 **'-'** 을 사용합니다. 
- 그 이외에 문서에 대한 제약사항은 없습니다 :)

<br>
