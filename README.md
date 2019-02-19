# Github tutorial

Github 사용에서 가장 기본이 되는 내용을 정리!!

## 1. Git & Github 란

Git이란 분산 버전 관리 시스템이다. 즉, 파일의 변경 내역을 계속 추적하도록 개발 된 소프트웨어다.
Github란 Git repository를 업로드 할 수 있는 웹사이트다.

#### 1.1 Git & Github는 왜 사용할까?

* 모든 변경에 대한 완벽한 기록
* 여러 갈래의 히스토리 및 독립된 히스토리
* 진행 중인 작업 검토
* 팀의 작업 진척 상황 확인

#### 1.2 주요 개념

* commit : 파일에 변경 내용을 저장할 때마다 새로운 commit 생성
* branch : 테스트를 하거나 새로운 기능을 개발하기 위해 사용할 수 있는 독립적인 commit
* master branch : 배포할 준비가 되면 최종적으로 마무리 하는 branch
* feature branch : 새로운 기능을 개발할 때마다 만드는 작업 branch
* release branch : 직접 QA 작업을 하거나 이전 소프트웨어를 지원해야 할때 쓰이는 작업 branch
* marge : 한 branch에서 완성된 작업을 가져와 다른 branch에 포함하는 방법
* tag : 특정 이력이 있는 commit에 대한 참조
* check out : hitory의 다른 버전으로 이동해 해당 시점의 파일을 보기 위한 작업
* pull request : branch에서 완료된 작업을 다른 사람이 리뷰 하고 master로 병합하도록 요청 하는 작업
* issue : github 기능에 대해 논의하거나 버그를 추척하거나 두 가지 경우 모두 사용
* wiki : 링크들 간을 연결해 간단하게 웹 페이지를 만드는 방법
* clone : local로 작업하기 위해 프로젝트 복사본을 다운로드 하는 방법
* fork : 오픈 소스 프로젝트를 변경하고 싶을 때 먼저 사용자 계정의 github로 복사 해야 되는데 이때 복사하는 작업

## 2. 프로젝트 보기

프로젝트의 상태를 확인할 수 있는 방법을 나타낸다.

#### 2.1 README.md 파일

* 이 파일은 프로젝트에 대한 소개와 협력자들에게 유용한 추가 정보(소프트웨어 설치 방법, 코드 사용 방법 등)를 제공한다.
* 배지(badges)를 통해 프로젝트의 현 상태를 알려주기도 한다.

* README.md

![Readme.md](https://dytjq.files.wordpress.com/2019/02/image-10.png?w=660)

#### 2.2 Commit History

* 특정 branch에서 작업이 완료되었을 때 가장 최근 작업이 무엇인지 알아보는 좋은 방법이다.
* commit 메세지를 보고 변경이 된 이유를 확인한다.

* Commit History

![Commit History](https://dytjq.files.wordpress.com/2019/02/image-11.png?w=660)

#### 2.3 Pull requests

* 프로젝트를 협력하는 사람들이 현재 무슨 작업을 하고 있으며, 각각의 변경 사항에 대해 어떤 역활을 하고 있는지 확인이 가능하다.

* Pull requests

![Pull requests](https://dytjq.files.wordpress.com/2019/02/image-12.png?w=660)

#### 2.4 Issue

* Pull request를 통해 현재 진행사항을 알 수 있는 반면, issue를 통해서는 프로젝트에 필요한 작업을 넓은 관점에서 볼 수 있다.
* 프로젝트의 현재 issue의 목록을 보고 확인한다.


* Issue 목록

![Issue 목록](https://dytjq.files.wordpress.com/2019/02/image-13.png?w=660)

#### 2.5 Pulse

* pulse는 프로젝트의 대한 최근의 활동 내용을 볼 수 있다.
* 기간을 최종일, 3일, 1주, 또는 한달 등의 기간으로 설정하여 기간 내의 프로젝트 진척도 확인이 가능하다.

* Pulse

![Pulse](https://dytjq.files.wordpress.com/2019/02/image-14.png?w=660)

#### 2.6 Github 그래프

* 그래프 화면을 통해 긴 기간 동안의 프로젝트에 행한 작업을 알 수 있다. insights를 누르고 상황에 맞는 그래프를 보면 된다.
* contributor, commit, code frequency, punch card, network, members, traffic 의 그래프 확인이 가능하다.

## 3. 작성하기

프로젝트에 어떻게 기여할 수 있는지 확인한다. fork와 pull request, github에 파일을 추가하고 작성, 삭제 등 github에 작성하고 사용하는데 필요한 내용이다.

#### 3.1 Fork 와 Pull request

* 프로젝트에 직접 기여하고 싶으면 그 프로젝트를 소유하거나 협력자로 포함되어야 한다. 프로젝트를 fork 하면 복사본을 원하는 대로 변경할 수 있고 pull request를 사용하여 프로젝트에 변경 내용을 반영할 수 있다.

1. fork : repository를 fork 할 장소를 선택한 다음 새로운 프로젝트 페이지로 이동한다.

* ddytjq/AWS를 fork

![ddytjq/AWS를 fork](https://dytjq.files.wordpress.com/2019/02/image-15.png?w=660)

2. 파일 추가 : 프로젝트에 새로운 소스코드를 올리거나 파일을 추가한다.

* fork 후 새로운 프로젝트에 파일 추가

![fork 후 새로운 프로젝트에 파일 추가](https://dytjq.files.wordpress.com/2019/02/image-16.png?w=660)

3. Pull request : 프로젝트의 fork를 변경했지만 초기 프로젝트에는 아직 반영되지 않았다. pull request를 통해 프로젝트 소유자의 허가를 받고 프로젝트를 변경한다.

* 초기 프로젝트에 pull request

![초기 프로젝트에 pull request](https://dytjq.files.wordpress.com/2019/02/image-17.png?w=660)

* pull request 전송 (merge 전)

![pull request 전송 (merge 전)](https://dytjq.files.wordpress.com/2019/02/image-19.png?w=660)

4.  Pull request 병합 : pull request 메세지와 commit이 나타나므로 병합을 한다. 그럼 원본 프로젝트로 포함된 새로운 merge commit이 추가된다.

* pull request 메세지 merge

![pull request 메세지 merge](https://dytjq.files.wordpress.com/2019/02/image-20.png?w=660)

* test.do 파일이 추가된 것을 확인

![test.do 파일이 추가된 것을 확인](https://dytjq.files.wordpress.com/2019/02/image-21.png?w=660)

#### 3.2 파일 편집

* Edit 옵션을 통해 파일의 콘텐츠를 변경한다.
* 파일명의 텍스트 상자를 통해 파일 이름 및 디렉토리 변경 가능하다.
* 폴더 생성, 폴더 편집 등 가능하다.

## 4. 협력하기

fork를 이용하지 않고 하나의 repository에서 직접 협력하는데 필요한 내용이다.

#### 4.1 Branch로 Commit

* 파일을 확장하고 싶으면 가장 먼저 branch를 생성하는 것이다. branch를 통해 변경 내용을 별도로 보관할 수 있다.
* master branch 와 생성 branch로 나누어져 있으며 branch에 따라 commit 구분이 가능하다.

* test_branch 생성

![test_branch 생성](https://dytjq.files.wordpress.com/2019/02/image-22.png?w=660)

* branch에 따라 commit이 구분된 것을 확인

![branch에 따라 commit이 구분된 것을 확인](https://dytjq.files.wordpress.com/2019/02/image-23.png?w=660)


#### 4.2 Branch에서 Pull request 생성

* Branch에 따라 코드를 변경했으면 마찬가지로 pull request를 통해 merge를 해야 한다.
* 설정을 통해 base와 compare를 설정하여 pull request를 한다.
* compare branch 에서 base branch로 요청을 하며 base branch에서 merge를 하면 된다.


* base: master <- compare: test_branch 로 pull request

![base: master <- compare: test_branch 로 pull request](https://dytjq.files.wordpress.com/2019/02/image-25.png?w=660)

* master branch 에서 merge

![master branch 에서 merge](https://dytjq.files.wordpress.com/2019/02/image-26.png?w=660)

* master branch에서 코드가 변경된 것을 확인

![master branch에서 코드가 변경된 것을 확인](https://dytjq.files.wordpress.com/2019/02/image-28.png?w=660)

#### 4.3 Pull request 기능

* Pull request를 생성 후 특정인의 피드백을 원하면 특정인을 @mention 으로 추가하면 된다. 호출된 프로젝트의 협력자는 변경된 사항에 대해 피드백을 댓글을 통해 작성할 수 있다.
* 프로젝트 협력자나 호출이 되지 않더라도 누구나 댓글을 달거나 꾸밀 수 있다.

#### 4.4 Issue 관리

* Issue는 수정해야 하는 버그나 새로 개발해야 하는 기능을 관리하는 가볍고 쉬운 도구이다. 설명하고자 하는 내용을 쉽게 작성하고 확인할 수 있다.
* Issue의 milestone을 활용하여 마감날짜나 스프린트(반복적인 개발 주기, 계획 회의 등)를 정할 때 편리하게 사용할 수 있다.
* Issue의 Label 관리를 통해 wontfix, quesition, bug 등 다양한 issue들을 색별로 나눌 수 있다.

#### 4.5 Wiki

* Wiki는 협력자들 간 다량의 연결된 페이지를 개발하기 쉽게 해주는 간단한 컨텐츠 관리 시스템이다.
* 사용자 문서, 개발자 문서 또는 프로젝트 관련 모든 정보가 wiki를 활용하여 github를 통해 접근 가능하도록 하는데 사용된다.

## 5. Repository 생성 및 구성

Github의 repository를 생성하고 구성하는 과정을 나타낸다.

#### 5.1 Repository 생성

* 신규 리포지토리 생성은 owner와 name, public 과 private, organization을 결정 후 생성한다.

* 각각의 설정 후 repository를 생성한다.

![각각의 설정 후 repository를 생성한다.](https://dytjq.files.wordpress.com/2019/02/image-29.png?w=660)

#### 5.2 협력자 추가

* 공개 repository를 생성하면 협력자를 추가하지 않아도 fork하고 pull request를 보내면 된다. 하지만 비공개 repository를 생성하였거나 프로젝트에 정기적으로 함께 일하는 사람들이 있다면 협력자로 추가해야 한다.

* Settings를 클릭 후 collaborators를 통해 협력자를 추가하면 된다.

![Settings를 클릭 후 collaborators를 통해 협력자를 추가하면 된다.](https://dytjq.files.wordpress.com/2019/02/image-30.png?w=660)

#### 5.3 Organization 생성

* Organization을 생성 후 협력자를 프로젝트에 추가를 하여 team을 만들 수 있다.
* 기본적으로 owners 권한과 team 권한이 있으며, 다른 사람에게 접근권한을 부여하고 싶으면 team을 추가하면 된다.

## 6. 참고 자료

* Github를 다른 소프트웨어에 연결이 가능하다. Github API를 다운로드 하여 repository 관련된 많은 작업을 자동화 할 수 있다.
* Git repository 관리는 github가 제공하는 GUI를 통해 쉽게 관리가 가능하다.
