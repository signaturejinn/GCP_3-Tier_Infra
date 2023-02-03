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
#### CSP
<img src="https://img.shields.io/badge/Google GCP-4285F4?style=for-the-badge&logo=Google Cloud&logoColor=white"> <!--gcp-->

#### OS
<img src="https://img.shields.io/badge/CentOS 7-262577?style=for-the-badge&logo=CentOS&logoColor=white"> <!--CentOS-->
<img src="https://img.shields.io/badge/Rocky Linux-10B981?style=for-the-badge&logo=Rocky Linux&logoColor=white"> <!--rocky linux-->

#### DB
<img src="https://img.shields.io/badge/mysql 8.0-4479A1?style=for-the-badge&logo=mysql&logoColor=white">  <!--mysql-->

#### Team Collabolation Tool
<img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=Notion&logoColor=white"> <!--Notion-->

#### Architecture Drawing Tool
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
![image](https://user-images.githubusercontent.com/117608997/216552572-a28f3d6d-d775-49fc-b2d6-ad99575673f8.png)
```
    Petclinic 소스 코드를 활용해 GCP 서비스로 3-Tier 인프라 구축
```
</br>

### 📌 Admin Architecture
![image](https://user-images.githubusercontent.com/117608997/216553868-cf734345-87ef-4be3-9a11-ce5bce048800.png)
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
#### - [GCP 3-Tier Project](https://glen-party-257.notion.site/GCP-3-Tier-Project-a565d6c1e8d54283b498d73592043545)

### 🔗 Git Link
#### - [Infra](https://github.com/signaturejinn/GCP_Infra_Semi/tree/main/Infra)
- [Web page 접속](https://www.youtube.com/watch?v=65otWWli8Bo)

</br>

![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/117608997/215986339-b08c4f82-9368-4dc0-8c3b-909faabf8a11.gif)

</br>

#### - [Test/Monitoring](https://github.com/signaturejinn/GCP_Infra_Semi/tree/main/Test/Monitoring)
- [Jmeter 부하 Test](https://youtu.be/YRAJHgAo0ZM)

</br>

![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/117608997/215985636-f0048a2c-0d2b-4451-b22d-d96e106404ac.gif)
