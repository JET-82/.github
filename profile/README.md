# JET-82
<img src="https://github.com/JET-82/.github/assets/103179265/b94a2fd2-b019-45c7-a2b5-3c66465a0a87" width="200" height="200">

## K-Food 픽업 오더 플랫폼 서비스

### 프로젝트 소개 🐥
  - 세계로 진출하는 기업을 위한 k-food 픽업 오더 플랫폼.

### 팀 소개 🙌
  - 전 세계 리전을 활용한 서비스로 어디서든 당신의 사업이 시작될 수 있도록 Infra부터 application 까지 책임집니다.
  - agile 한 방식으로 time to market 전략에 최적화된 SaaS 솔루션을 제공합니다.
  - 클라우드를 활용하여 인프라를 효율적으로 관리합니다.
  - 개발부터 운영까지 devops 조직을 기반으로 협업하는 팀입니다.
  - 빠른 해외 진출을 원한다면 JET-82
    
|강석구|김경빈|신용호|안예은|최정은|
|:--:|:--:|:--:|:--:|:--:|
|<img align='center' src="https://github.com/seokgoooo.png" width="117" height="156">|<img align='center' src="https://github.com/blight-bin.png" width="117" height="156">|<img align='center' src="https://github.com/gdtknight.png" width="117" height="156">|<img align='center' src="https://github.com/yeeSilver.png" width="117" height="156">|<img align='center' src="https://github.com/jungeun5-choi.png" width="117" height="156">|
|[@seokgoooo](https://github.com/seokgoooo)|[@blight-bin](https://github.com/blight-bin)|[@gdtknight](https://github.com/gdtknight)|[@yeeSilver](https://github.com/yeeSilver)|[@jungeun5-choi](https://github.com/jungeun5-choi)|

### R&R (Role and Responsibility)
#### Infra
    - Provisioning : 김경빈(정) / 최정은(부)
        - Terraform
          - AWS cloud infra
          - EKS Module
             
    - Addons Service : 김경빈(정) / 안예은(부)
        - Load Balancer Controller
        - EBS CSI Driver Controller
        - External DNS Controller
               
#### Development
    - Frontend : 안예은(정) / 최정은(부)
    - Backend : 신용호(정) / 강석구(부)
                 
#### CI
    - CI : 강석구(정) / 신용호(부)
      - Github Actions
    - Language : Java
    - Framework : Spring Boot
    - VCS : GitHub
    - Process
      - Dev / Stage / Prd
      - Branch Strategy : Pull Request
       
    - Build :
        - Source Build : Gradle
        - ECR
          - Image Build
          - Image Scanning
          - Image Registry

#### CD
    - CD : 안예은(정) / 김경빈(부)
    - 3rd Party
      - ArgoCD
        - Multi Cluster Deployment
        - Deployment Strategy : Rolling Update
          - package manager : Helm
          - Deployment code : 
            - manifest : YAML
            - Deployment unit : Application(CRD)
         
#### Monitoring
    - 최정은(정) / 안예은(부)
    - Monitoring
      - Prometheus / Grafana
    - Logging
      - CloudWatch
    - Stress test
      - nGrinder
        - csv

### 프로젝트 규칙 📜
    "남을 Blame 하지 않기!"
    - 작업 이력은 항상 코드 및 화면 캡처해서 관리
      - 화면 캡처 : URL / nav bar 안 보이는 전체 화면
    - 사용되는 바이너리, 라이브러리, 프로그램 등의 버전을 기록하고 동일하게 사용
      - latest 버전 사용 x
    - 맡은 업무는 오너쉽을 가지고 이끌되 정/부 형태로 서로 의견을 공유하면서 진행
    - 잘 못하더라도 같이 도와주고 협업하기🙇‍♂️

    - 맡은 파트는 기본적으로 Markdown으로 작성
    ✅ 목차
    ✅ 톤 & 매너 유의
    ✅ 도구 소개 ex) ArgoCD 란? …
    ✅ 제품 버전 및 설치 가이드

    - MD 문서는 모르는 사람이 봐도 쉽게 따라할 수 있는 사용자 매뉴얼 수준으로 작성
      - 개인 Repository 만들어서 업로드
    - 캡처한 이미지는 네이밍/넘버링 규칙 정해서 작성

## 프로젝트 문서 📃
### 문서 네이밍 / 넘버링 규칙
    - 넘버링
      - 1. 2. 3.
          - 1) 2) 3)
              - (1) (2) (3)
                - 가. 나. 다.
    - 문장 어미
      - ~다.
    - 모든 제품의 version 명시
      - Spec / OS
    - 예시) AWS t2.micro / Amazon Linux 2 ver ~ / 

### 문서 링크
|문서 종류|링크|
|:--:|:--:|
|프로젝트 소개| [link](https://github.com/SeSAC-AWS-Final-Team-2) |
|매뉴얼 (markdown)| [link](https://github.com/SeSAC-AWS-Final-Team-2) |
