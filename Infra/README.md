## Infra 세부 사항
### - VPC
- VPC & Subnet

![image](https://user-images.githubusercontent.com/117608997/215594116-57086de6-dfd8-49cb-b481-0eb880002272.png)

</br>

- Firewall

![image](https://user-images.githubusercontent.com/117608997/215594180-a4d94adc-11b5-43f5-94fb-ddcc8fcd3bcd.png)

</br>

- Cloud SQL

![image](https://user-images.githubusercontent.com/117608997/215594232-a78f87f3-b202-4c2e-a83f-99dbfbf5addf.png)
```
가용영역 이중화를 통한 고가용성
```
</br>

- Compute Engine

![image](https://user-images.githubusercontent.com/117608997/215594320-aed7686c-146c-4e81-85dd-0a666c998f9a.png)
```
네트워크 태그로 Web/Was 방화벽 관리
```

</br>

### - Snapshot, Image, Template
![image](https://user-images.githubusercontent.com/117608997/215594791-52a2c915-09b4-4115-bf1d-19404d5371c1.png)
```
Instance Group 생성을 위한 Snapshot, Image, Template 생성
```

</br>

### - Instance Groups
![image](https://user-images.githubusercontent.com/117608997/215595009-2f530c70-70c2-4631-8ff0-7d39c84ac67f.png)
```
Instance Group을 통해 Auto Scaling 관리
```

</br>

### - Internal Load Balancer 
![image](https://user-images.githubusercontent.com/117608997/215595113-5dcac99e-cb66-42d0-8783-63ba6afa3917.png)
```
리전 내부 TCP LB 서비스를 활용한 네트워크 내부 부하분산 관리
```

</br>

### - External Load Balancer
![image](https://user-images.githubusercontent.com/117608997/215595396-01bdec88-474c-416f-a826-629581f557e4.png)
```
전역 외부 HTTP(S) LB 서비스를 활용한 네트워크 외부 부하분산 관리
```

</br>

### - Cloud DNS
![image](https://user-images.githubusercontent.com/117608997/215595578-23693bc1-84fb-43a1-970b-def0fe3eefb4.png)
```
Cloud DNS 서비스를 활용한 도메인 접속 관리
```
</br>

### - GCS
![image](https://user-images.githubusercontent.com/117608997/215595779-58711808-7dce-41cd-9ca9-fa25d64e9948.png)
```
GCS를 활용한 캐싱 데이터 저장
```
