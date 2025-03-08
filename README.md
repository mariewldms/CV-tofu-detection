# tofu-detection
컴퓨팅 비전 프로젝트: 두부 결함 탐지 서비스

# Introduction 
AI Nation : AWS 컴퓨팅 비전 프로젝트  
개발기간: 2024.11  
역할: AWS 인프라, 프론트엔드   

# Info 
SM 두부 공장에서 생산된 두부 데이터의 불량 여부를 판정해 실시간으로 결과를 반환하는 서비스 페이지 제작 

https://github.com/user-attachments/assets/9b7ad7b9-0b25-4338-83a6-bea6377f0d72



# Role 
[AWS Infra]
- AWS 아키텍처 설계
- 프론트엔드 프로젝트 배포(cloud9, s3)
- lambda, api gateway를 통한 프론트엔드-sagemaker 엔드포인트 통신 
  
[Frontend Developer]
- 시간대별 양불여부 결과 통계 페이지 구현 
- 실시간 이미지 투입 결과에 따른 결과 반환하는 ui,ux 및 api 구현 

# Architecture
![image](https://github.com/user-attachments/assets/74a1d328-3400-4674-9273-75b411600f55)

# Stacks

**Frontend**  
<img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"> <img src="https://img.shields.io/badge/angular.js-DD0031?style=for-the-badge&logo=angularjs&logoColor=white">
  
**Infra**  
<img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> <img src="https://img.shields.io/badge/amazonaws-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"> 
 
# Blog 
[트러블슈팅 및 제작과정]  
https://mariewldms.tistory.com/46

# Presentation
https://www.canva.com/design/DAGXlYKxrF8/izlb2qvIc-BQQxAaGEHvXA/edit


## Build

Run `ng build` to build the project. The build artifacts will be stored in the `dist/` directory.

## Running unit tests

Run `ng test` to execute the unit tests via [Karma](https://karma-runner.github.io).

## Running end-to-end tests

Run `ng e2e` to execute the end-to-end tests via a platform of your choice. To use this command, you need to first add a package that implements end-to-end testing capabilities.
