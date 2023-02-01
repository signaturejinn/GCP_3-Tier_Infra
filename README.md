## GCP를 활용한 Petclinic 예약 웹 서비스
### - GCP 서비스를 활용한 Petclinic 웹 서비스 인프라 구축
### - Apache Web server 구축
### - Apache Tomcat Was Server 구축
### - Cloud Monitoring을 활용해 지속적인 모니터링

</br>

## 🗓️ 진행 기간
- 2022.08.29 ~ 2022.09.16

</br>

## 👥 팀 구성
- Infra 구축 5명

</br>

## ⚙️ 사용 기술
### CSP
<img src="https://img.shields.io/badge/Google GCP-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <!--gcp-->

### OS
<img src="https://img.shields.io/badge/CentOS 7-262577?style=for-the-badge&logo=CentOS&logoColor=white"> <!--CentOS-->
<img src="https://img.shields.io/badge/Rocky Linux-10B981?style=for-the-badge&logo=Rocky Linux&logoColor=white"> <!--rocky linux-->

### DB
<img src="https://img.shields.io/badge/mysql 8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <!--mysql-->

### Team Collabolation Tool
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <!--Notion-->

### Architecture Drawing Tool
<img src="https://img.shields.io/badge/Drawio-000000?style=for-the-badge&logo=Drawio&logoColor=white"> <!--Draw.io-->

</br>

## 🙋🏻‍♂️ 담당 업무
- VPC 구성
- 보안 그룹 구성
- IAM & IAP | 접근 권한 관리
- Web, WAS, DB 구성 및 연동
- Cloud SQL | MySQL 8.0
- Cloud DNS를 활용해 HTTPS 리다이렉션 구성 및 SSL 인증서 추가
- Cloud CDN을 활용한 캐싱
- Internal LB & External LB 구축
- Cloud Monitoring을 활용한 지속적인 모니터링 구현
- Cloud Storage를 활용한 캐싱 데이터 저장

</br>

## 📝 상세 내용 
### 📌 Infra Architecture
![GCP_3-Tier Archi](https://user-images.githubusercontent.com/117608997/215586587-744e29e8-8cd3-46c4-92ec-9ece0faee6e3.jpg)
```
    Petclinic 소스 코드를 활용해 GCP 서비스로 3-Tier 인프라 구축
```
</br>

### 📌 Admin Architecture
![GCP_3-Tier admin_Archi](https://user-images.githubusercontent.com/117608997/215586606-45eb6bf8-e740-4ab9-b79b-07f742850f0c.jpg)
```
    Admin은 Cloud IAP를 통해 Web, Was서버를 관리하고 Bastion을 통해 DB 관리
    Cloud SQL을 활용해 DB를 서버를 구축하고 이중화를 통해 고가용성 인프라 구축
    Cloud Monitoring을 활용한 지속적인 모니터링
```
</br>

### 📌 User Architecture
![GCP_3-Tier admin_User_Archi](https://user-images.githubusercontent.com/117608997/215586615-9d756b33-cdee-429f-96b0-f2fe8c9b16cd.jpg)
```
    User는 도메인을 통한 접근으로 웹서비스 이용
```

### 📌 요구 사항
![image](https://user-images.githubusercontent.com/117608997/215590440-a27d9469-42d4-4775-ab53-d5c7f1095402.png)
```
    고가용성을 바탕으로 한 인프라 구축 & 지속적인 모니터링 가능
```

</br>

## ⛓️ 구축 과정
### 🔗 Notion Link
#### - [GCP 3-Tier Project](https://glen-party-257.notion.site/GCP-3-Tier-45aa9757dff04334bc25a0c03d925c62)

### 🔗 Git Link
#### - [Infra](https://github.com/signaturejinn/GCP_3-Tier_Infra/tree/main/Infra)
- [Web page 접속](https://www.youtube.com/watch?v=65otWWli8Bo)

</br>

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/117608997/215984714-70b815e9-62cc-4d30-8700-c691d1dc3ad1.gif)
![ezgif com-gif-maker](https://user-images.githubusercontent.com/117608997/215984721-e3ed0c08-ad08-49f4-bc1a-7a06d6ee2653.gif)

#### - [Test/Monitoring](https://github.com/signaturejinn/GCP_3-Tier_Infra/blob/main/Test/Monitoring/README.md)
- [Jmeter 부하 Test](https://youtu.be/YRAJHgAo0ZM)

</br>

![ezgif com-gif-maker](https://user-images.githubusercontent.com/117608997/215985570-0919439c-fa76-4c1b-b3ed-a679163c0781.gif)
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/117608997/215985636-f0048a2c-0d2b-4451-b22d-d96e106404ac.gif)
