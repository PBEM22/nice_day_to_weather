<div style="text-align: center; display: flex; justify-content: center; flex-direction: column;">
  <!-- Waving Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=auto&height=200&section=header&fontSize=80&text=Nice%20Day%20to%20Wear" style="width: 100%;" />
<p align="center">
  <!-- Image on Top (Centered) -->
  <img src="https://github.com/user-attachments/assets/5594df99-3b11-42c7-beed-1663410da57d" alt="NiceDayToWear" style="margin-top: -10px; width: 250px;" />
</p>
</div>

<br>

## 👩🏻‍💻 제1조1항 🧑🏻‍💻

| [![](https://avatars.githubusercontent.com/u/173455095?v=4)](https://github.com/SANGHYUN0519) | [![](https://avatars.githubusercontent.com/u/158060587?v=4)](https://github.com/ygc1994) | [![](https://avatars.githubusercontent.com/u/173458380?v=4)](https://github.com/JIYOUNG-22) | [![](https://avatars.githubusercontent.com/u/103546300?v=4)](https://github.com/Pangtaek) | [![](https://avatars.githubusercontent.com/u/94957124?v=4)](https://github.com/person76) | [<img src="https://github.com/user-attachments/assets/4d62fcb6-1511-4e22-86da-1704a26180d9" width="450" />](https://github.com/PBEM22) |
|--------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------|
| <p align="center">박상현</p> | <p align="center">연건창</p> | <p align="center">윤지영</p> | <p align="center">임광택</p> | <p align="center">임서연</p> | <p align="center">임채륜</p> |

<br>

## 🛠️ 기술 스택

<img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> <img src="https://img.shields.io/badge/springboot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
<img src="https://img.shields.io/badge/spring data JPA-6DB33F?style=for-the-badge&logo=hibernate&logoColor=white">
<img src="https://img.shields.io/badge/spring%20security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
<br>
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
<img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
<img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img src="https://img.shields.io/badge/vue.js-4FC08D?style=for-the-badge&logo=vue.js&logoColor=white">
<br>
<img src="https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white">
<img src="https://img.shields.io/badge/kubernetes-%23326ce5.svg?style=for-the-badge&logo=kubernetes&logoColor=white">
<img src="https://img.shields.io/badge/jenkins-%232C5263.svg?style=for-the-badge&logo=jenkins&logoColor=white">
<br>
<img src="https://img.shields.io/badge/mariadb-4479A1?style=for-the-badge&logo=mariadb&logoColor=white">
<img src="https://img.shields.io/badge/Amazon%20S3-FF9900?style=for-the-badge&logo=amazons3&logoColor=white">
<br>
<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">

<br>

## 📜 목차
1. [프로젝트 개요](#1-프로젝트-개요)
2. [프로젝트 소개](#2-프로젝트-소개)
3. [프로젝트 배경 및 필요성](#3-프로젝트-배경-및-필요성)
4. [이벤트 스토밍 기반 DDD 설계 문서](#4-이벤트-스토밍-기반-ddd-설계-문서)
5. [요구사항 명세서](#5-요구사항-명세서)
6. [Database 설계](#6-database-설계)
7. [화면 설계서](#7-화면-설계서)
8. [시스템 아키텍처](#8-시스템-아키텍처)
9. [기능 수행 테스트 결과](#9-기능-수행-테스트-결과)
10. [빌드 및 배포 문서](#10-빌드-및-배포-문서)
11. [Jenkins CI/CD 테스트 결과](#11-jenkins-cicd-테스트-결과)

<hr>
<br>

## 1. 프로젝트 개요
> <b>[입기 좋은 날]</b>
> <br>
> 위치, 날씨, 상황, 회원의 선호도에 따라 최적의 아웃핏(의상)을 추천해 주고, 사용자들 간의 소통을 지원하는 아웃핏 추천 웹 애플리케이션

<br>

## 2. 프로젝트 소개
**"입기 좋은 날"** 은 사용자의 위치, 날씨, 그리고 상황 (일상, 여행, 데이트 등)에 맞춘 아웃핏을 추천해 주는 웹 애플리케이션입니다.
웹을 이용하는 회원들에게 맞춤형 아웃핏 추천을 제공하며, 회원 간 소통을 돕는 리뷰 및 게시판 등의 다양한 기능을 포함하고 있습니다.

사용자는 자신의 실시간 위치나 설정한 위치를 바탕으로 날씨 정보를 확인하고, 원하는 시간대에 맞는 날씨 데이터를 얻을 수 있습니다.
그 후, 날씨와 상황에 맞는 아웃핏을 추천 받고, 추천된 아웃핏에 대한 리뷰를 남길 수 있습니다.

아웃핏 추천뿐만 아니라 회원은 리뷰와 게시판을 통해 자신만의 스타일 및 코디를 사진으로 공유하고, 다른 회원들과 소통할 수 있습니다.

<br>

## 3. 프로젝트 배경 및 필요성
### 3-1. 급변하는 기상 조건
최근 몇 년간 우리나라는 예측할 수 없는 기후 변화를 경험하고 있습니다. 무더운 여름과 갑작스러운 한파, 짧아진 봄과 가을 등 날씨가 빠르게 변하고 있습니다.
특히, 지역별 날씨 차이가 커짐에 따라, 동일한 지역 내에서도 날씨가 다른 경우가 빈번해지고 있습니다.
이러한 변화를 반영한 "입기 좋은 날" 은 사용자가 실시간으로 정확한 날씨 정보를 바탕으로 아웃핏을 선택할 수 있게 도와 줍니다.

### 3-2. 다양한 기상 악화에 따른 준비물
미세먼지, 자외선, 무더위 등 기상 악화로 인해 우리는 매일 여러 가지 준비물을 챙겨야 합니다.
미세먼지가 심한 날엔 마스크, 자외선이 강한 날엔 선크림, 예상치 못한 비에는 우산 등이 필요합니다.
그러나 사용자는 종종 이런 다양한 요소들을 고려하지 못해 불편함을 겪습니다.
"입기 좋은 날"은 이런 기상 상황에 맞춰 의상과 함께 준비물까지 추천하여 사용자들이 외출 시 필요한 모든 요소를 놓치지 않도록 도와 줍니다.

### 3-3. 날씨에 따른 선호 의상 분석
날씨에 대한 사람들의 반응은 개개인마다 다를 수 있습니다. <br>
예를 들어, 30℃ 이상 더운 날에는 대부분의 사람들이 가벼운 차림으로 반팔, 반바지를 선택할 것입니다.
그렇다면 15℃ 또는 20℃는 어떨까요? 해당 기온은 사람에 따라 덥다고 혹은 적당하다고 혹은 춥다고 느낄 것입니다.
15℃는 추울 것이라 생각해서 겉옷을 준비했으나 더워서 짐만 되거나, 더울 것이라 생각해서 겉옷을 준비하지 않아 하루 종일 추위에 떨었던 경험도 있을 것입니다.
<br>
"입기 좋은 날"은 회원들의 체질과 스타일에 대한 선호 데이터를 수집하고, 이를 바탕으로 최적의 의상을 추천하여 불편한 경험을 최소화할 수 있도록 도와 줍니다.
사용자 맞춤형 의상 추천 시스템은 향후 지속적으로 개선되어 더욱 정확하고 개인화 된 아웃핏 추천을 제공할 것입니다.

<br>

## 4. 이벤트 스토밍 기반 DDD 설계 문서
<img width="1045" alt="DDD" src="https://github.com/user-attachments/assets/c90b0615-2407-423d-a94e-330b9b3fa4f9">

<br>

## 5. 요구사항 명세서
![SRS](https://github.com/user-attachments/assets/a6372972-b545-4bdf-847c-2120d0c3a905)

<br>

## 6. Database 설계
### 6-1. 논리 모델링
![논리ERD](https://github.com/user-attachments/assets/764e8d1b-16dd-4199-a683-f9e56218cc40)

### 6-2. 물리 모델링
![물리ERD](https://github.com/user-attachments/assets/394ea102-74f3-4b1b-8233-b48a154517c4)

### 6-3. DDL, DML
- [DDL.sql](article1_be/article1-be/src/main/resources/Schema.sql)
- [DML.sql](article1_be/article1-be/src/main/resources/data.sql)

<br>

## 7. 화면 설계서
[화면 설계서 (Figma)](https://www.figma.com/design/vQOctatRdm5PHNETWTKDgY/입기좋은날?node-id=94-810&node-type=symbol&t=Dr1ta4RAMDzX61WH-0)

<br>

## 8. 시스템 아키텍처
![SystemArchitecture](https://github.com/user-attachments/assets/dc71c041-afd3-4488-829a-8cc0d2968b3c)

<br>

## 9. 기능 수행 테스트 결과
### 9-1. 로그인
<details>
<summary>카카오 소셜 로그인</summary>
<div markdown="1">

![카카오로그인](/images/로그인/카카오톡%20소셜%20로그인.gif)

</div>
</details>

<details>
<summary>네이버 소셜 로그인</summary>
<div markdown="1">

![네이버로그인](/images/로그인/네이버%20소셜%20로그인.gif)

</div>
</details>

### 9-2. 의상 추천
<details>
<summary>비로그인 게스트 의상 추천</summary>
<div markdown="1">

![비로그인옷추천](/images/마이페이지/비로그인%20옷%20추천.gif)

</div>
</details>

<details>
<summary>로그인 회원 의상 추천</summary>
<div markdown="1">

![로그인회원의상추천](/images/마이페이지/로그인%20회원%20의상%20추천.gif)

</div>
</details>

### 9-3. 마이페이지
<details>
<summary>회원정보 조회, 수정</summary>
<div markdown="1">

![회원정보수정](/images/마이페이지/회원정보%20수정.gif)

</div>
</details>

<details>
<summary>선호도 조회, 수정</summary>
<div markdown="1">

![선호도수정](/images/마이페이지/선호도%20수정.gif)

</div>
</details>

<details>
<summary>아웃핏 이력 조회</summary>
<div markdown="1">

![아웃핏이력조회](/images/마이페이지/마이페이지%20이력조회.gif)

</div>
</details>

<details>
<summary>아웃핏 통계 조회</summary>
<div markdown="1">

![아웃핏통계조회](/images/마이페이지/마이페이지%20아웃핏%20통계%20조회.gif)

</div>
</details>

<details>
<summary>나의 리뷰 조회</summary>
<div markdown="1">

![나의리뷰조회](/images/마이페이지/마이페이지%20리뷰%20조회.gif)

</div>
</details>

<details>
<summary>나의 게시글 조회</summary>
<div markdown="1">

![아웃핏통계조회](/images/마이페이지/마이페이지%20게시글%20조회.gif)

</div>
</details>

### 9-4. 리뷰
<details>
<summary>전체 리뷰 조회</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/전체%20리뷰%20조회.gif)

</div>
</details>

<details>
<summary>리뷰 조회 - 위치 필터링</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/리뷰%20위치%20필터링.gif)

</div>
</details>

<details>
<summary>리뷰 조회 - 닉네임 필터링</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/리뷰%20닉네임%20필터링.gif)

</div>
</details>

<details>
<summary>아웃핏 리뷰 작성</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/옷%20리뷰%20작성.gif)

</div>
</details>

<details>
<summary>아웃핏 리뷰 수정</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/옷%20리뷰%20수정.gif)

</div>
</details>

<details>
<summary>아웃핏 리뷰 삭제</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/옷%20리뷰%20삭제.gif)

</div>
</details>

<details>
<summary>리뷰 신고</summary>
<div markdown="1">

![리뷰작성](/images/리뷰/리뷰%20신고.gif)

</div>
</details>

### 9-5. 게시판
<details>
<summary>게시판 목록 조회</summary>
<div markdown="1">

![게시글등록](/images/게시판/게시판%20목록%20조회.gif)

</div>
</details>

<details>
<summary>게시글 작성</summary>
<div markdown="1">

![게시글등록](/images/게시판/게시판%20글%20등록.gif)

</div>
</details>

<details>
<summary>게시글 수정</summary>
<div markdown="1">

![게시글수정](/images/게시판/게시글%20수정.gif)

</div>
</details>

<details>
<summary>게시글 삭제</summary>
<div markdown="1">

![게시글수정](/images/게시판/게시글%20삭제.gif)

</div>
</details>

<details>
<summary>게시글 신고</summary>
<div markdown="1">

![게시글수정](/images/게시판/게시물%20신고.gif)

</div>
</details>

<details>
<summary>댓글 등록</summary>
<div markdown="1">

![게시글수정](/images/게시판/게시판%20댓글%20등록.gif)

</div>
</details>

<details>
<summary>댓글 삭제</summary>
<div markdown="1">

![게시글수정](/images/게시판/댓글%20삭제.gif)

</div>
</details>

<details>
<summary>댓글 신고</summary>
<div markdown="1">

![게시글수정](/images/게시판/댓글%20신고.gif)

</div>
</details>

### 9-6. 관리자
<details>
<summary>관리자 로그인</summary>
<div markdown="1">

![관리자로그인](/images/관리자/관리자%20로그인.gif)

</div>
</details>

<details>
<summary>관리자 유저 검색</summary>
<div markdown="1">

![관리자유저검색](/images/관리자/관리자%20유저%20검색.gif)

</div>
</details>

<details>
<summary>관리자 유저 검색(권한)</summary>
<div markdown="1">

![관리자유저검색](/images/관리자/관리자%20유저%20검색(권한).gif)

</div>
</details>

<details>
<summary>관리자 회원 정보 변경</summary>
<div markdown="1">

![관리자유저검색](/images/관리자/관리자%20회원%20상태%20변경.gif)

</div>
</details>

<details>
<summary>관리자 신고 조회</summary>
<div markdown="1">

![관리자유저검색](/images/관리자/관리자%20신고%20조회.gif)

</div>
</details>

<details>
<summary>관리자 신고 상태 변경</summary>
<div markdown="1">

![관리자유저검색](/images/관리자/관리자%20신고%20상태%20변경.gif)

</div>
</details>

<details>
<summary>관리자 리뷰 상태 변경</summary>
<div markdown="1">

![관리자유저검색](/images/관리자/관리자%20리뷰%20상태%20변경.gif)

</div>
</details>

<br>

## 10. 빌드 및 배포 문서
### 10-1. Dockerfile
<details>
  <summary>Dockerfile</summary>

  ```dockerfile
  # 빌드 단계
  FROM openjdk:17-alpine AS builder
  WORKDIR /app
  COPY . .
  RUN ./gradlew bootjar

  # 실행 단계
  FROM openjdk:17-alpine
  WORKDIR /app
  EXPOSE 8080

  # dockerize 설치
  RUN apk add --no-cache curl && \
      curl -sSL https://github.com/jwilder/dockerize/releases/download/v0.6.1/dockerize-alpine-linux-amd64-v0.6.1.tar.gz | tar -C /usr/local/bin -xzv

  # 빌드된 JAR 파일을 복사
  ARG JAR_FILE=build/libs/*.jar
  COPY --from=builder /app/${JAR_FILE} app.jar

  # ENTRYPOINT 설정
  ENTRYPOINT ["java", "-jar", "app.jar"]
  ```
</details>

### 10-2. Kubernetes manifest
<details>
  <summary>backend-dep</summary>

  ```Kubernetes manifest
apiVersion: apps/v1
kind: Deployment
metadata:
  name: backend
spec:
  replicas: 3
  strategy:
    type: RollingUpdate
    rollingUpdate:
      maxUnavailable: 1
      maxSurge: 1
  selector:
    matchLabels:
      app: backend
  template:
    metadata:
      labels:
        app: backend
    spec:
      containers:
        - name: backend
          image: dlacofbs/article1_spring:latest
          imagePullPolicy: Always
          ports:
            - containerPort: 8080
          env:
            - name: SPRING_PROFILES_ACTIVE
              value: aws
            - name: db.host
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: db.host
            # ConfigMap에서 가져온 환경 변수들
            - name: db.port
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: db.port
            - name: db.dbname
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: db.dbname
            - name: open.weather.api.key
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: open.weather.api.key
            - name: open.weather.current.api.url
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: open.weather.current.api.url
            - name: open.weather.5day.api.url
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: open.weather.5day.api.url
            - name: open.weather.air.api.url
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: open.weather.air.api.url
            - name: open.weather.air.forecast.url
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: open.weather.air.forecast.url
            - name: amazon.s3.access-key
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: amazon.s3.access-key
            - name: kakao.api.client_id
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: kakao.api.client_id
            - name: kakao.api.client_secret
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: kakao.api.client_secret
            - name: kakao.api.redirect_uri
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: kakao.api.redirect_uri

            # Secret에서 가져온 환경 변수들
            - name: db.username
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: db.username
            - name: db.password
              valueFrom:
                configMapKeyRef:
                  name: config
                  key: db.password
            - name: root_password
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: root_password
            - name: my_database
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: my_database
            - name: my_user
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: my_user
            - name: my_password
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: my_password
            - name: VITE_KAKAO_API_KEY
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: VITE_KAKAO_API_KEY
            - name: SECRET_KEY
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: SECRET_KEY

          args:
            - "/usr/local/bin/dockerize"
            - "-wait"
            - "tcp://mariadb:3306"     # 환경 변수로 포트 사용
            - "-timeout"
            - "30s"                  # ConfigMap에서 가져온 timeout 값 사용
            - "java"
            - "-jar"
            - "app.jar"
  ```
</details>

<details>
  <summary>backend-ser</summary>

  ```Kubernetes manifest
apiVersion: v1
kind: Service
metadata:
  name: backend
spec:
  ports:
    - port: 8080
      targetPort: 8080
  selector:
    app: backend
  type: ClusterIP
  ```
</details>

<details>
  <summary>frontend-dep</summary>

  ```Kubernetes manifest
apiVersion: apps/v1
kind: Deployment
metadata:
  name: frontend
spec:
  replicas: 3
  selector:
    matchLabels:
      app: frontend
  template:
    metadata:
      labels:
        app: frontend
    spec:
      containers:
        - name: frontend-container
          image: dlacofbs/article1_vue:latest
          imagePullPolicy: Always
          ports:
            - containerPort: 80
          env:
            - name: VITE_KAKAO_API_KEY
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: VITE_KAKAO_API_KEY
            - name: VITE_KAKAO_REST_API_KEY
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: VITE_KAKAO_REST_API_KEY
  ```
</details>

<details>
  <summary>frontend-ser</summary>

  ```Kubernetes manifest
apiVersion: v1
kind: Service
metadata:
  name: frontend
spec:
  type: ClusterIP
  ports:
  - port: 80
    targetPort: 80
  selector:
    app: frontend
  ```
</details>

<details>
  <summary>ingress</summary>

  ```Kubernetes manifest
apiVersion: networking.k8s.io/v1
kind: Ingress
metadata:
  name: article1-ingress
  annotations:
    nginx.ingress.kubernetes.io/ssl-redirect: "false"
    nginx.ingress.kubernetes.io/rewrite-target: /$2
    nginx.ingress.kubernetes.io/proxy-body-size: "3G"                     # 최대 요청 본문 크기 설정
    nginx.ingress.kubernetes.io/client-body-buffer-size: "3G"              # 클라이언트 요청 버퍼 크기 설정
    nginx.ingress.kubernetes.io/affinity: "cookie"                          # 쿠키 기반 세션 스티키니스 활성화
    nginx.ingress.kubernetes.io/session-cookie-name: "teenkiri-session"    # 세션 쿠키 이름
    nginx.ingress.kubernetes.io/session-cookie-hash: "sha1"                 # 쿠키 해시 알고리즘 (SHA-1)
    kubernetes.io/ingress.class: nginx                                       # Ingress 컨트롤러 지정
    cert-manager.io/cluster-issuer: letsencrypt-prod                        # Let's Encrypt 인증서 발급
spec:
  ingressClassName: nginx
  rules:
  - http:
      paths:
      - path: /()(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: frontend
            port:
              number: 80
      - path: /boot(/|$)(.*)
        pathType: ImplementationSpecific
        backend:
          service:
            name: backend
            port:
              number: 8080
  ```
</details>

<details>
  <summary>mariadb-dep</summary>

  ```Kubernetes manifest
apiVersion: apps/v1
kind: Deployment
metadata:
  name: mariadb
spec:
  selector:
    matchLabels:
      app: mariadb
  replicas: 1
  template:
    metadata:
      labels:
        app: mariadb
    spec:
      containers:
        - name: mariadb
          image: mariadb:latest
          env:
            - name: MARIADB_ROOT_PASSWORD
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: root_password
            - name: MYSQL_DATABASE
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: my_database
            - name: MYSQL_USER
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: my_user
            - name: MYSQL_PASSWORD
              valueFrom:
                secretKeyRef:
                  name: secret
                  key: my_password
          ports:
            - containerPort: 3306
          volumeMounts:
            - name: mariadb-storage
              mountPath: /var/lib/mysql
      volumes:
        - name: config-volume
          configMap:
            name: mariadb-config
        - name: mariadb-storage
          persistentVolumeClaim:
            claimName: mariadb-pvc
  ```
</details>

<details>
  <summary>mariadb-ser</summary>

  ```Kubernetes manifest
apiVersion: v1
kind: Service
metadata:
  name: mariadb
spec:
  ports:
    - port: 3306
      targetPort: 3306
  selector:
    app: mariadb
  type: ClusterIP
  ```
</details>

<details>
  <summary>mariadb-pvc</summary>

  ```Kubernetes manifest
apiVersion: v1
kind: PersistentVolumeClaim
metadata:
  name: mariadb-pvc
spec:
  accessModes:
    - ReadWriteOnce
  resources:
    requests:
      storage: 1Gi
  ```
</details>

### 10-3. Jenkins Pipeline Script
<details>
  <summary>Jenkins Pipeline Script</summary>

  ```Jenkins Pipeline Script
pipeline {
    agent any

    tools {
        gradle 'gradle'
        jdk 'openJDK17'
    }

    environment {
        DOCKERHUB_CREDENTIALS = credentials('DOCKERHUB_PASSWORD')
        GITHUB_URL = 'https://github.com/PBEM22/jenkins_article1'
    }


    stages {
        
        stage('Check directory') {
    steps {
        script {
            if (isUnix()) {
                sh "ls -l ./article1_be/article1-be/"
            } else {
                bat "dir article1_be\\article1-be\\"
            }
        }
    }
}
        stage('Preparation') {
            steps {
                script {
                    if (isUnix()) {
                        sh 'docker --version'
                    } else {
                        bat 'docker --version'
                    }
                }
            }
        }
        stage('Add .env') {
            steps {
                script {
                    if (isUnix()) {
                        withCredentials([file(credentialsId: 'application-aws', variable: 'applicationAwsFile')]) {
                            sh 'cp ${applicationAwsFile} article1_be/article1-be/src/main/resources/application-aws.yml'
                        }
                    } else {
                        withCredentials([file(credentialsId: 'application-aws', variable: 'applicationAwsFile')]) {
                            bat "copy %applicationAwsFile% article1_be\\article1-be\\src\\main\\resources\\application-aws.yml"
                        }
                    }
                }
            }
        }

        stage('Source Build') {
            steps {
                git branch: 'develop', url: "${env.GITHUB_URL}"
                script {
                    if (isUnix()) {
                        sh "chmod +x ./article1_be/article1-be/gradlew"
                        sh "./article1_be/article1-be/gradlew clean build -x test"
                    } else {
                        bat "cd article1_be\\article1-be && gradlew.bat clean build -x test"
                    }
                }
            }
        }

        stage('Container Build and Push') {
            steps {
                script {
                    withCredentials([usernamePassword(credentialsId: 'DOCKERHUB_PASSWORD', usernameVariable: 'DOCKER_USER', passwordVariable: 'DOCKER_PASS')]) {
                        if (isUnix()) {
                            sh "docker build -t ${DOCKER_USER}/article1_spring:latest ./article1_be/article1-be/"
                            sh "docker login -u ${DOCKER_USER} -p ${DOCKER_PASS}"
                            sh "docker push ${DOCKER_USER}/article1_spring:latest"
                        } else {
                            bat "docker build -t ${DOCKER_USER}/article1_spring:latest article1_be\\article1-be\\"
                            bat "docker login -u %DOCKER_USER% -p %DOCKER_PASS%"
                            bat "docker push ${DOCKER_USER}/article1_spring:latest"
                        }
                    }
                }
            }
        }
    }

    post {
        always {
            script {
                if (isUnix()) {
                    sh 'docker logout'
                } else {
                    bat 'docker logout'
                }
            }
        }
        success {
            echo 'Pipeline succeeded!'
        }
        failure {
            echo 'Pipeline failed!'
        }
    }
}
  ```
</details>

<br>

## 11. Jenkins CI/CD 테스트 결과
![CI/CD](/images/CICD/CICD.gif)

<br>

