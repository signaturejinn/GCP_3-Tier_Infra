## GCP_3-Tier_Infra
### - GCP 서비스를 활용한 3-Tier Petclinic Web Service 인프라 구축
### - Apache Web server 구축
### - 내장 Apache Tomcat Was Server 구축
### - Cloud Monitoring을 활용해 지속적인 모니터링

</br>

## 🗓️ 진행 기간
- 2022.08.29 ~ 2022.09.16

</br>

## 👥 팀 구성
- Infra 구축 5명

</br>

## ⚙️ 사용 기술
#### CSP
<img src="https://img.shields.io/badge/Google GCP-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <!--gcp-->

#### OS
<img src="https://img.shields.io/badge/CentOS 7-262577?style=for-the-badge&logo=CentOS&logoColor=white"> <!--CentOS-->
<img src="https://img.shields.io/badge/Rocky Linux-10B981?style=for-the-badge&logo=Rocky Linux&logoColor=white"> <!--rocky linux-->

#### DB
<img src="https://img.shields.io/badge/mysql 8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <!--mysql-->

#### Team Collabolation Tool
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <!--Notion-->
<img src="https://img.shields.io/badge/Drawio-000000?style=for-the-badge&logo=Drawio&logoColor=white"> <!--Draw.io-->

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
    Admin은 Cloud IAP를 통해 Web, Was서버를 관리하고 Bastion을 통해 Cloud SQL DB를 관리
```
</br>

### 📌 User Architecture
![GCP_3-Tier admin_User_Archi](https://user-images.githubusercontent.com/117608997/215586615-9d756b33-cdee-429f-96b0-f2fe8c9b16cd.jpg)
```
    User는 도메인을 통한 접근으로 웹서비스 이용
```

</br>

## ⛓️ 구축 과정
### 🔗 Notion Link
#### - [GCP 3-Tier Project](https://glen-party-257.notion.site/GCP-3-Tier-Project-a565d6c1e8d54283b498d73592043545)

### 🔗 Git Link
#### - 

</br>

## 🙋🏻‍♂️ 담당 업무
- VPC 구성
- 보안 그룹 구성
- IAM & IAP | 접근 권한 관리
- Web, WAS, DB 구성 및 연동
- Cloud SQL | MySQL 5.7
- Cloud DNS를 활용해 HTTPS 리다이렉션 구성 및 SSL 인증서 추가
- Cloud CDN을 활용한 캐싱
- Internal LB & External LB 구축
- Cloud Monitoring을 활용한 지속적인 모니터링 구현