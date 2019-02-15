# Github tutorial
Github를 활용하자.

## 1. Git & Github 란
* Git이란 분산 버전 관리 시스템이다. 즉, 파일의 변경 내역을 계속 추적하도록 개발 된 소프트웨어이다.
* Github란 Git repository를 업로드 할 수 있는 웹사이트 이다.

#### 1.1 Git & Github는 왜 사용할까?
1. 모든 변경에 대한 완벽한 기록
2. 여러 갈래의 히스토리 및 독립된 히스토리
3. 진행 중인 작업 검토
4. 팀의 작업 진척 상황 확인

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
#### 2.1 README.md 파일 보기
* 이 파일은 프로젝트에 대한 소개와 협력자들에게 유용한 추가 정보(소프트웨어 설치 방법, 코드 사용 방법 등)를 제공한다.