# 팀 이름

## 주제 or 서비스 이름 - K-Food 스마트 오더 서비스 or 주문 플랫폼
![tmp_img](https://github.com/SeSAC-AWS-Final-Team-2/.github/assets/103179265/7bd2e01c-faed-4917-9d64-2394040bfa23)
    - 이런 느낌의 우리 서비스 사진
    
### 프로젝트 소개 🐥
    - 세계로 진출하는 안정적인 k-food 주문 플랫폼. ~~~ 스마트 오더 서비스
    - 세계 어느 곳에서도 안정적인 서비스를 제공합니다. 전 세계 리전을 활용한 서비스로 을 책임집니다.
    - 수정 예정

### 팀 소개 🙌

|강석구|김경빈|신용호|안예은|최정은|
|:--:|:--:|:--:|:--:|:--:|
|<img src="https://github.com/seokgoooo.png" width="100" height="100">|<img src="https://github.com/blight-bin.png" width="100" height="100">|<img src="https://github.com/gdtknight.png" width="100" height="100">|<img src="https://github.com/yeeSilver.png" width="100" height="100">|<img src="https://github.com/jungeun5-choi.png" width="100" height="100">|
|[@seokgoooo](https://github.com/seokgoooo)|[@blight-bin](https://github.com/blight-bin)|[@gdtknight](https://github.com/gdtknight)|[@yeeSilver](https://github.com/yeeSilver)|[@jungeun5-choi](https://github.com/jungeun5-choi)|

### R&R (Role and Responsibility)
#### 개발
    - Backend(비즈니스 로직) : 신용호(정) / 강석구(부)
    - Frontend(프론트) : 안예은(정) / 최정은(부)
#### 파이프라인 자동화
    - CI : 강석구(정) / 신용호(부)
      - Jenkins or Github Action
    - Language : Java
    - VCS : GitHub
    - Dev / Stage / Prd
    - Branch Strategy : Pull Request
    - Test : Sonarqube / Junit (Optional)
    - Build : 
        - Source Build : Maven / Gradle
        - Artifact : Jfrog / Nexus 
        - Image Build
        - Image Scanning
        - Image Registry
        - ECR / Harbor
    - CD : 강석구(정) / 신용호(부)
        - ArgoCD
            - Multi Cluster Deployment
            - Deployment Stratey : Blue/Green, Canary
#### 아키텍처 설계 / 구축
    - Provisioning 도구 : 김경빈(정) / 최정은(부)
        - Terraform
            - EKS Module
            - EKS Blueprint
    - Addons Service : 안예은(정) / 김경빈(부)
        - LoadBalancer Controller
        - EBS CSI Driver Controller
        - External DNS Controller
        - ACM
    - 3rd Party : 안예은(정) / 김경빈(부)
        - ArgoCD
            - 설치 : Helm
            - 배포코드 : 
                - 메니페스트 : YAML
                - 배포단위 : Application(CRD)
#### 모니터링(운영)
    - 최정은(정) / 안예은(부)
    - Prometheus / Grafana / APM(솔루션 채택)
    - ELK or CloudWatch
    - 부하테스트
        - ngrinder
            - csv 추출
    - 로깅 / 모니터링

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
    ✅ 톤 & 매너는 유의
    ✅ 도구 소개 ex) ArgoCD 란? …
    ✅ 제품 버전 및 설치 가이드

    - MD 문서는 모르는 사람이 봐도 쉽게 따라할 수 있는 사용자 매뉴얼 수준으로 작성
      - 개인 Repository 만들어서 업로드
    - 캡처한 이미지는 네이밍/넘버링 규칙 정해서 작성

## 프로젝트 문서 📃
### 문서 네이밍 / 넘버링 규칙
    - 
### 문서 링크
|문서 종류|링크|
|:--:|:--:|
|프로젝트 소개| [link](https://github.com/SeSAC-AWS-Final-Team-2) |
