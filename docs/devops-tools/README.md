# Issue Management

<a href="https://en.wikipedia.org/wiki/Comparison_of_issue-tracking_systems" target="_blank">Project 관리시스템 비교표</a>

|                                                           | Platform      | License        | 비고 |
|---                                                        |---            |---             |---  |
| [Phabricator](issue-management/#phabricator) | PHP           | Apache2        | 개발에서 사용하는 여러 tool들의 집합. Kanban 보드 제공 |
| [RedMine](issue-management/#redmine)         | Ruby On Rails | GPL2           | WBS나 gantt 형태의 일감관리 가능 |
| [Tuleap](issue-management/#tuleap)           | PHP           | GPL2           |  |


# Git Hosting / Code Review

|                                                           | Platform      | License        | 비고 |
|---                                                        |---            |---             |---  |
| [Gitlab](git-hosting/#gitlab)                | Ruby          | ..             | Git Hosting기능을 중심으로 여러 기능을 통합 |
| [Gerrit](git-hosting/#gerrit)                | Java          | Apache2        | Pre-comit 코드리뷰를 지원. 리뷰를 위한 git repo.와 결과가 반영되는 git repo.가 분리 |
| [Review Board](git-hosting/#review-board)    | Python        | MIT            | .. |

# CI/CD

|             | Platform      | License        | 비고 |
|---          |---            |---             |---  |
| [Concourse](ci-cd/#concourse)   | Go            | Apache2        | .. |
| [GitlabCI](ci-cd/#gitlabci)     | Ruby          | Apache2        | `8.0`부터 Gitlab에 기능이 통합됨 |
| [Spinnaker](ci-cd/#spinnaker)   | Java          | Apache2        | .. |
| [Jenkins](ci-cd/#jenkins)       | Java          | MIT            | .. |
| [GoCD](ci-cd/#gocd)             | Java, Ruby    | Apache2        | Pipeline기반 빌드관리 시스템. 빌드환경별 agent가 필요. Pipeline에 대한 설정은 Go Server에서 수행 |
| [Bazel](ci-cd/#bazel)           | Java          | Apache2        | Google's own build tool.   | 
| [Catpstrano](ci-cd/#capistrano) | Ruby          | MIT            | Deployment automation tool. |

# Containerize
|                                                   | Platform      | License        | 비고 |
|---                                                |---            |---             |---  |
| [Vagrant](containerize/#vagrant)        | Ruby          | MIT            | .. |
| [Docker](containerize/#docker)          |               |                | .. |
| [Packer](containerize/#packer)          |               |                | .. |
| [Kubernetes](containerize/#kubernetes)  |               |                | .. |
| [Mesos](containerize/#mesos)            |               | Apache2        |    |



# Configuration Management
<a href="http://blog.takipi.com/deployment-management-tools-chef-vs-puppet-vs-ansible-vs-saltstack-vs-fabric/" target="_">Chef vs. Puppet vs. Ansible vs. SaltStack vs. Fabric</a>

|                                                             | Platform      | License        | 비고 |
|---                                                          |---            |---             |---  |
| [Chef](configuration-management/#chef)         | Ruby          | Apache2        | Mater-Client model. ruby와 절차적 개발을 알아야 함. push를 지원하지 않음|
| [Puppet](configuration-management/#puppet)     | Ruby          | Apache2        | Master-Client model. 커뮤니티가 오래되고 성숙함. 고급 기능은 Ruby기반 CLI를 사용해야 함. codebase가 빠르게 커지기 때문에, 배우기 어려움 |
| [Fabric](configuration-management/#fabric)     | Python        |     | agent나 runner 설치 없이 동작(ssh 이용). shell 명령을 전달하여 수행하는 방식 |
| [Ansible](configuration-management/#ansible)   | Python        | GPL            | agent나 runner 설치 없이 동작(ssh, winRm 사용). YAML기반 설정. DSL을 지원하지 않음. module을 node로 전송하여 실행 |
| [CFEngine](configuration-management/#cfengine) | C             | GPL            | ... |

# Service Discovery

|                                                         | Platform      | License        | 비고 |
|---                                                      |---            |---             |---  |
| [Consul](service-discovery/#consul)        |               |                | .. |
| [etcd](service-discovery/#etcd)            |               |                | .. |
| [Zookeeper](service-discovery/#zookeeper)  |               |                | .. |


# Logging / Monitoring
|                                                | Platform             | License        | 비고 |
|---                                             |---                   |---             |---  |
| [ELK Stack](monitor/#elk-stack)   | Java,Ruby,Javascript | Apache2        | ElasticSearch + LogStash + Kibana   |
| [ELG Stack](monitor/#elg-stack)   | Java, Ruby           | GPLv3          | ElasticSearch + LogStash + GrayLog2 + MongoDb. 사용자관리기능 탑재(LDAP, AD연결 가능) |
| [Zipkin](monitor/#zipkin)         | Java                 | Apache2        | Microservice 사이의 latency를 추적하기 위한 시스템 |
| [Glowroot](monitor/#glowroot)     | Java                 | Apache2        | APM tool |
| [Icinga](monitor/#icinga)         | C++                  | GPL2           | Nagios에서 Fork. 네트워크 서비스 (SMTP, HTTP, ...), Host Resource (CPU, Disk, ...), 서버 Component (switch, router, ...) 모니터링   |
| [Prometheus](monitor/#prometheus) | Go + &alpha;         | Apache2        |            |
| [Hygieia](monitor/#hygieia)       | Java                 | Apache2        | DevOps Dashboard           |
| [Zabbix](monitor/#zabbix)         | C, PHP               | GPL2           | Network and application monitoring |
| [Log.io](monitor/#logio)          | node.js              | Apache2        | Realtime log monitoring in your browser |

# Collaboration

<a href="https://stackshare.io/stackups/lets-chat-vs-rocketchat-vs-mattermost" target="_blank">Rocket.chat vs. Mattermost</a>

|                                                         | Platform          | License        | 비고 |
|---                                                      |---                |---             |---  |
| [Mattermost](collaboration/#mattermost)    | Go Lang, React.js | Apache2        | Slack Alternative. Slack Compatible.|
| [Rocket.Chat](collaboration/#rocketchat)   | Meteor            | MIT            | Slack Alternative |
| [Only Office](collaboration/#only-office)  | Mono, .NET        | AGPL 3.0       | 문서공유 및 동시편집  |

