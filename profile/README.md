# 약국 약 재고 확인 및 예약 서비스, 어디약?! <img alt="image" width="100" src="https://github.com/user-attachments/assets/f9d69fca-9b76-4df0-af0a-4c7d6950479d" align="left"> 

_약국 약 재고 확인 및 예약 웹 서비스_

<br>

> [!Note]
> 구릅 PROFECT 1기 클라우드 엔지니어링 프로젝트 과정 - 2조 Clover 프로젝트입니다

## 1. 개요
📆 개발기간: _2025.1.31 ~ 2025.4.3_

<br>

## 2. 팀원 소개
<table align="center">
   <tr>
     <td align="center">
       <a href="https://github.com/1006lem">
         <img src="https://avatars.githubusercontent.com/u/68532437?v=4" width="140px" /><br/>
       </a>
     </td>
     <td align="center">
       <strong>김규민</strong><br/>
     </td>
     <td>
      - 백엔드 (Java Springboot) 개발 <br>
      - 백엔드, 프론트엔드 Dockerfile 작성 <br>
      - 온프레미스 인프라 환경 구축 <br>
      - 온프레미스 Kubernetes 구축, 관리 <br>
      - 온프레미스/EKS Kubernetes manifest 파일 작성(yaml) <br>
     </td>
   </tr>
   <tr>
     <td align="center">
       <a href="https://github.com/Hansilverline">
         <img src="https://avatars.githubusercontent.com/u/158063910?v=4" width="140px" /><br/>
       </a>
     </td>
     <td align="center">
       <strong>한은선</strong><br/>
     </td>
     <td>
      - AWS 관리 (Organization) <br>
      - AWS 아키텍처 구성 (RDS, AZ, VPC, Subnet, EKS, ALB, Route53, ...) <br>
      - Terraform을 이용한 AWS 환경 구축 <br>
      - EKS (Kubernetes) 구축, 관리 <br>
      - Helm Chart를 이용한 EKS 내 서비스 배포 <br>
     </td>
   </tr>
   <tr>
     <td align="center">
       <a href="https://github.com/Joohyuk-Lee">
         <img src="https://avatars.githubusercontent.com/u/54299329?v=4" width="140px" /><br/>
       </a>
     </td>
     <td align="center">
       <strong>이주혁</strong><br/>
     </td>
     <td>
      - 프론트엔드 개발 (HTML, CSS, Javascript) <br>
      - Jenkins CI pipeline 작성 <br>
      - Jenkins CI 서버 구축, EKS/온프레미스 설치 <br>
      - Amazon ECS 구성 <br>
      - Argo CD Rolling Update 구현  <br>
      - Argo CD 서버 구축, EKS/온프레미스 설치 <br>
     </td>
   </tr>
   
</table>



<br>

## 3. 링크
### 1. 착수보고서

> 서비스 기획, 아키텍처 설계, 트러블슈팅 등 프로젝트 보고서(pdf)입니다.

[어디약?! 최종 착수 보고서](https://drive.google.com/file/d/169lGmHzovazckrr-rE3chN81GAp3HXT_/view?usp=sharing)

<br>

### 2. 트러블슈팅

> 겪은 주요한 트러블슈팅을 기록한 노션 페이지입니다.

[어디약?! 트러블슈팅 페이지](https://www.notion.so/19fd6d3f177080aeaf6af3393aad0dce)




<br>

## 4. 기술스택

### 1. DevOps 기술스택

🛠️ **EKS** |  _✅ Terraform, ✅ AWS(EKS, RDS, Route53, Organizations, ECS, Lambda), ✅ Helm_ <br>
🛠️ **온프레미스** | _✅ VMware Fusion, ✅ Kubernetes(Kubespray)_ <br>
🛠️ **CI/CD** | _✅ Jenkins, ✅ ArgoCD_

<p align="center">
    <img src="https://img.shields.io/badge/Terraform-844FBA?style=for-the-badge&logo=Terraform&logoColor=white">
    <img src="https://img.shields.io/badge/Helm-0F1689?style=for-the-badge&logo=Helm&logoColor=white">
    <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazonwebservices&logoColor=white">
</p>
<p align="center">
    <img src="https://img.shields.io/badge/VMware-607078?style=for-the-badge&logo=VMware&logoColor=white">
    <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=Kubernetes&logoColor=white">
    <img src="https://img.shields.io/badge/Kubespray-3D647F?style=for-the-badge&logo=Kubernetes&logoColor=white">
</p>

<p align="center">
    <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=Jenkins&logoColor=white">
    <img src="https://img.shields.io/badge/Argo-EF7B4D?style=for-the-badge&logo=Argo&logoColor=white">
</p>


### 2. 서비스 개발 기술스택
🛠️ **BE** | _✅ Java, ✅ SpringBoot, ✅ MySQL_<br>
🛠️ **FE** | _✅ HTML, ✅ CSS, ✅ Javascript_

<p align="center">
 <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white">
 <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" />
 <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" />
</p>
<p align="center">
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white">
 <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white">
 <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
</p>


<br>

## 5. 아키텍처

<img src="https://github.com/user-attachments/assets/515754bc-2bb7-4667-8b6e-ecbb9278e34a" />

### 인프라 주요 특징

**1. 하이브리드 클라우드 (DR)** <br>
기본 서비스 제공은 EKS에서 하며, <br>
EKS 장애 발생 시 (동일한 구조를 지닌) 온프레미스에서 서비스를 제공한다.

<br>

VPC Route Table 교체를 통한 DR 제공을 목적으로 하였으나 (미구현), <br>
현재 EKS, 온프레미스 각각 배포 완료했다.

<br>



<br>

## 6. 서비스 주요 기능
> **약 재고 검색**
- 사용자 위치 1km 이내의 약국의 의약품 재고 정보 제공

> **약 예약 기능 (부분 구현)**
- 사용자가 원하는 의약품 예약

> **약 재입고 알림 기능 (부분 구현)**
- 특정 의약품 재입고 알림 신청


<br>


## 7. 서비스 스크린샷

<img src="https://github.com/user-attachments/assets/4106f5cb-3909-44f8-aa0f-02a49094bfda" alt="Image 1" width="70%">
<img src="https://github.com/user-attachments/assets/b0897d47-6523-4104-9d1d-9c6293842837" alt="Image 2" width="70%">
<img src="https://github.com/user-attachments/assets/acf9ea42-f27b-42e2-8fd4-7a44cc790286" alt="Image 3" width="70%">




<br>
<br>




---



