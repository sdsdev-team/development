# Phabricator

## Overview
https://www.phacility.com/phabricator/

Facebook에서 만든 협업 Tool Set.
SaaS 형태로 서비스를 이용하거나, On-Premise 형태로 설치하여 사용할 수 있다.

설치형으로 사용할 경우, 도메인을 이용하여 설정하는 것을 권장.
코드에서 Redirect로 이동하는 경우가 종종 있기 때문에, 80포트에 relative path없이 사용해야 한다.

구성하는 개별 요소별로 별도의 도메인을 가지고 있는 구조를 추천한다.


* Diffusion
 * Git, SVN, Mercurial 등을 호스팅 할 수 있는 서비스
 
* Differential
 * 코드리뷰를 위한 시스템
 * 여러명의 코드 리뷰어를 지정할 수 있으며, 리뷰 의견에 대한 결과를 입력해야 함
 
* Herald
 * Post-Commit Audit을 위한 rule engine
 
* Maniphest
 * 일감관리 시스템
  
* Workboard
 * Kanban 형태의 일감관리 기능 제공
  
* Phriction
 * Wiki 시스템
  
* Conpherence
 * Chat 기반 협업시스템

