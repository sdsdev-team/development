# Microservice
## Spring boot
## Zuul
## Eureka
## Chaos Monkey
## Hystrix
## Conductor

# Git Hosting
## Gitlab

# Collaboration Tools
## Mattermost
https://about.mattermost.com/

Slack을 On-Premise로 설치하여 사용할 수 있는 Open Source

`Slack Compatible`을 표방하고 있으며, 이미 Slack과 연결하는 기능이 있다면,<br >
service url만 mattermost로 변경하면, 동일한 기능을 제공한다.

계정정보는 자체 서비스를 이용하거나, `Gitlab` OAuth를 사용할 수 있으며<br >
`Enterprise버전`부터는 Google, Office365, Active Directory, LDAP등을 이용한 SSO를 지원한다.


## Phabricator 
https://www.phacility.com/phabricator/

Facebook에서 만든 협업 Tool Set

- Maniphest: 작업관리 소프트웨어. 칸반보드 형태를 지원
- Phriction: Wiki. 수정과 조회를 위한 접근권한 제어가 가능
- Conpherence: 그룹채팅을 위한 시스템
- Differential: 코드리뷰를 위한 시스템
- Diffusion: Git Hosting 시스템
- Herald: Rule 기반 후처리 시스템

## Hubot

# AI / Machine Learning
## TensorFlow

# DB Migration
## Flyway
## Liquibase
http://www.liquibase.org/

Migration정보는 `changelog`파일에 저장되며, `changelog`는 여러개의 `changeset`으로 구성된다.

각 `changeset`은 `author`와 `id`값을 통해 유일하게 식별된다.<br>
liquibase가 실행될 때, `changelog`파일에 있는 모든 `changeset`에 대하여 수행로그를 확인하며 <br >
이 중, 실행되지 않은 `changeset`를 실행한다.


### 실행
Ant, Maven 혹은 Command Line을 통해 명령을 실행할 수 있으며,

Servlet Listener, Spring Listener 등을 통해서 Web App.이 기동될 때 실행될 수 있다.

### Internal
Migration정보는 `DATABASECHANGELOG`와 `DATABASECHANGELOGLOCK` 테이블에서 관리된다.

`DATABASECHANGELOG`는 동작한 migration에 대한 정보를,<br />
`DATABASECHANGELOGLOCK`은 Migration script가 동시에 시작되는 것을 막는다.



# Persistance
## Redis
## Elastic Search
## Consul
## OrientDB

# CI / CD
## Gitlab CI
## Jenkins
## Travis CI
## GoCD

# Configuration Management
## Ansiable

# Container
## Docker
## Kubernetes
## Vagrant

# Lint
## Infer
## esLint
## scss-lint
## check-style

# CSS Preprocessors
## LESS
## SASS
## Stylus
