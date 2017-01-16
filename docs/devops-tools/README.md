# Issue Management

<a href="https://en.wikipedia.org/wiki/Comparison_of_issue-tracking_systems" target="_blank">Project 관리시스템 비교표</a>

|                                                           | Platform      | License        | 비고 |
|---                                                        |---            |---             |---  |
| [Phabricator](devops-tools/issue-management/#phabricator) | PHP           | Apache2        | 개발에서 사용하는 여러 tool들의 집합. Kanban 보드 제공 |
| [RedMine](devops-tools/issue-management/#redmine)         | Ruby On Rails | GPL2           | WBS나 gantt 형태의 일감관리 가능 |
| [Tuleap](devops-tools/issue-management/#tuleap)           | PHP           | GPL2           |  |


# Git Hosting / Code Review

|                                                           | Platform      | License        | 비고 |
|---                                                        |---            |---             |---  |
| [Gitlab](devops-tools/git-hosting/#gitlab)                | Ruby          | ..             | Git Hosting기능을 중심으로 여러 기능을 통합 |
| [Gerrit](devops-tools/git-hosting/#gerrit)                | Java          | Apache2        | Pre-comit 코드리뷰를 지원. 리뷰를 위한 git repo.와 결과가 반영되는 git repo.가 분리 |
| [Review Board](devops-tools/git-hosting/#review-board)    | Python        | MIT            | .. |

# CI/CD

|             | Platform      | License        | 비고 |
|---          |---            |---             |---  |
| [Concourse](devops-tools/ci-cd/#concourse)   | Go            | Apache2        | .. |
| [GitlabCI](devops-tools/ci-cd/#gitlabci)     | Ruby          | Apache2        | `8.0`부터 Gitlab에 기능이 통합됨 |
| [Spinnaker](devops-tools/ci-cd/#spinnaker)   | Java          | Apache2        | .. |
| [Jenkins](devops-tools/ci-cd/#jenkins)       | Java          | MIT            | .. |
| [GoCD](devops-tools/ci-cd/#gocd)             | Java, Ruby    | Apache2        | Pipeline기반 빌드관리 시스템. 빌드환경별 agent가 필요. Pipeline에 대한 설정은 Go Server에서 수행 |
| [Bazel](devops-tools/ci-cd/#bazel)           | Java          | Apache2        | Google's own build tool.   | 
| [Catpstrano](devops-tools/ci-cd/#capistrano) | Ruby          | MIT            | Deployment automation tool. |

# Containerize
|                                                   | Platform      | License        | 비고 |
|---                                                |---            |---             |---  |
| [Vagrant](devops-tools/containerize/#vagrant)        | Ruby          | MIT            | .. |
| [Docker](devops-tools/containerize/#docker)          |               |                | .. |
| [Packer](devops-tools/containerize/#packer)          |               |                | .. |
| [Kubernetes](devops-tools/containerize/#kubernetes)  |               |                | .. |
| [Mesos](devops-tools/containerize/#mesos)            |               | Apache2        |    |



# Configuration Management
<a href="http://blog.takipi.com/deployment-management-tools-chef-vs-puppet-vs-ansible-vs-saltstack-vs-fabric/" target="_">Chef vs. Puppet vs. Ansible vs. SaltStack vs. Fabric</a>

|                                                             | Platform      | License        | 비고 |
|---                                                          |---            |---             |---  |
| [Chef](devops-tools/configuration-management/#chef)         | Ruby          | Apache2        | Mater-Client model. ruby와 절차적 개발을 알아야 함. push를 지원하지 않음|
| [Puppet](devops-tools/configuration-management/#puppet)     | Ruby          | Apache2        | Master-Client model. 커뮤니티가 오래되고 성숙함. 고급 기능은 Ruby기반 CLI를 사용해야 함. codebase가 빠르게 커지기 때문에, 배우기 어려움 |
| [Fabric](devops-tools/configuration-management/#fabric)     | Python        |     | agent나 runner 설치 없이 동작(ssh 이용). shell 명령을 전달하여 수행하는 방식 |
| [Ansible](devops-tools/configuration-management/#ansible)   | Python        | GPL            | agent나 runner 설치 없이 동작(ssh, winRm 사용). YAML기반 설정. DSL을 지원하지 않음. module을 node로 전송하여 실행 |
| [CFEngine](devops-tools/configuration-management/#cfengine) | C             | GPL            | ... |

# Service Discovery

|                                                         | Platform      | License        | 비고 |
|---                                                      |---            |---             |---  |
| [Consul](devops-tools/service-discovery/#consul)        |               |                | .. |
| [etcd](devops-tools/service-discovery/#etcd)            |               |                | .. |
| [Zookeeper](devops-tools/service-discovery/#zookeeper)  |               |                | .. |


# Logging / Monitoring
|                                                | Platform             | License        | 비고 |
|---                                             |---                   |---             |---  |
| [ELK Stack](devops-tools/monitor/#elk-stack)   | Java,Ruby,Javascript | Apache2        | ElasticSearch + LogStash + Kibana   |
| [ELG Stack](devops-tools/monitor/#elg-stack)   | Java, Ruby           | GPLv3          | ElasticSearch + LogStash + GrayLog2 + MongoDb. 사용자관리기능 탑재(LDAP, AD연결 가능) |
| [Zipkin](devops-tools/monitor/#zipkin)         | Java                 | Apache2        | Microservice 사이의 latency를 추적하기 위한 시스템 |
| [Glowroot](devops-tools/monitor/#glowroot)     | Java                 | Apache2        | APM tool |
| [Icinga](devops-tools/monitor/#icinga)         | C++                  | GPL2           | Nagios에서 Fork. 네트워크 서비스 (SMTP, HTTP, ...), Host Resource (CPU, Disk, ...), 서버 Component (switch, router, ...) 모니터링   |
| [Prometheus](devops-tools/monitor/#prometheus) | Go + &alpha;         | Apache2        |            |
| [Hygieia](devops-tools/monitor/#hygieia)       | Java                 | Apache2        | DevOps Dashboard           |
| [Zabbix](devops-tools/monitor/#zabbix)         | C, PHP               | GPL2           | Network and application monitoring |
| [Log.io](devops-tools/monitor/#logio)          | node.js              | Apache2        | Realtime log monitoring in your browser |

# Collaboration

<a href="https://stackshare.io/stackups/lets-chat-vs-rocketchat-vs-mattermost" target="_blank">Rocket.chat vs. Mattermost</a>

|                                                         | Platform          | License        | 비고 |
|---                                                      |---                |---             |---  |
| [Mattermost](devops-tools/collaboration/#mattermost)    | Go Lang, React.js | Apache2        | Slack Alternative. Slack Compatible.|
| [Rocket.Chat](devops-tools/collaboration/#rocketchat)   | Meteor            | MIT            | Slack Alternative |
| [Only Office](devops-tools/collaboration/#only-office)  | Mono, .NET        | AGPL 3.0       | 문서공유 및 동시편집  |

