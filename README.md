# 2023 Fall Portfolio by JiHwan Moon

## General
- Github Profile    
(https://github.com/kumass2020)  
- CV  
(https://kumass2020.github.io/2023-Fall-CV/)  

## Projects

### Federated Learning (+ Kubernetes)
> Kubernetes와 컨테이너 기술을 사용해 Cloud 기반 연합학습 플랫폼을 구현.   
> 플랫폼은 서버 클러스터의 배치부터 클라이언트 처리, 모델 처리 파이프라인, 로그 처리 파이프라인까지 end-to-end 관리 및 시각화가 가능.

- **FedOps Web**  
(http://ccljhub.gachon.ac.kr:40020/)
  - FedOps Platform을 Web에 배포.
  - FL-Client 관리, FL-Server 상태 확인, FL 학습, 결과 성능 모니터링을 손쉽게 Web에서 확인가능.
  - AWS S3, WandB API를 사용해 모니터링 및 시행 별 Global Model 다운로드 지원.
  - React와 Node.js(Koa, SocketIO)를 통해 Web 전반을 구현하였음.
 
- **FedOps**  
(https://github.com/gachon-CCLab/FedOps)
  - FedOps Open-source Project.
  - 모든 fl-client와 server 코드가 담겨있으며 라이브러리로 쉽게 설치-사용 가능.
  - client, server 코드 구현 전반에 관여하였음.

- **FedOps Paper works**  
(https://github.com/kumass2020/FedOps-Chunk-Benchmark)
  - FL Client Simulation <- Kubernetes Job을 통한 Pod 배치 / CPU 성능 분포 시뮬레이션.
  - FL Client Docker Image Build를 위한 Dockerfile.
  - FL Server / Client Code (+ Dataset, DataLoader, Model, Evaluator, ...)
  - FL 결과 시각화.
  - Flower Framework를 Client Selection / Training & Communication Time Measurement를 위해 대폭 수정.

- **FL Client**  
(https://github.com/gachon-CCLab/fl-client)
  - 연합학습 클라이언트의 배포판.
  - Docker ver.와 Shell ver.로 구분.
  - 설치를 위한 Document 지원.

- FL Server  
(https://github.com/gachon-CCLab/Flower_Server)
  - FL Aggregation, Global Model Optimization 수행.

- FedOps Web (Working)  
(https://github.com/kumass2020/FedOps-Web)  
  - 연합학습 플랫폼을 웹으로 지원.

- Kubernetes Resources Collector  
(https://github.com/kumass2020/K8s-Resource-Collector)
  - Kubernetes 클러스터의 모든 자원 정보를 수집.

### Energy
- In/Out Management Server  
(https://github.com/kumass2020/InOutManagement-Server)
  - 사용자가 재실 상태인지 여부를 구분해주는 프로그램.
  - 재실 상태가 아닐 경우 필요 없는 기기를 종료해주는 식으로 작동 가능.

- In/Out Management Client (Android) (BLE ver.)  
(https://github.com/gachon-CCLab/KEICO-RP-BLE-inoutManagement)
  - BLE 통신을 사용해 사용자가 재실 상태인지 여부를 구분해주는 클라이언트.

- In/Out Management Client (Android) (WiFi ver.)  
(https://github.com/kumass2020/WiFi-InOutManagement-Android)
  - WiFi 통신을 사용해 사용자가 재실 상태인지 여부를 구분해주는 클라이언트.

- **Electricity Bill Calculator**  
(https://github.com/gachon-CCLab/KEICO-Electricity-Bill-Calculator)
  - 전력 사용량 데이터로부터 실시간으로 요금을 계산하고 서버로 값을 전송.
  - 한국전력 사이트 크롤링을 통해 요금을 동기화.

- Electricity Rates Comparison Web Server    
(https://github.com/kumass2020/KEICO-Electric-Rates-Comparison-Web-Server)
  - 요금제에 따른 유불리를 비교하는 웹 시각화와 서버를 구현.
  
- Electricity Prediction    
(https://github.com/kumass2020/Electricity-Prediction-RNN-LSTM)
  - RNN, LSTM 모델과 전력 사용량 데이터를 활용해 다음 전력 사용량을 예측.

- Energy Monitoring Web  
(https://github.com/kumass2020/energy-monitoring-system)
  - 전력 사용량 시각화.

### Digital Healthcare
- Person Recognition  
(https://github.com/kumass2020/Multi-Modality-Person-Recognition)
  - ECG와 PPG 파형 데이터와 XGBoost 모델을 활용해 개인 인식.

## etc.

### Study
- Algorithms  
(https://github.com/kumass2020/Algorithms-Problems)

- Deep Learning + Computer Vision  
(https://github.com/kumass2020/2023-1-PyTorch-Lecture)

- PyTorch Playground  
(https://github.com/kumass2020/PyTorch-Playground)

- Multi Layer Perceptron (MLP)  
(https://github.com/kumass2020/NeuralNetwork-MultiLayer-Perceptron)

- Genetic Algorithm  
(https://github.com/kumass2020/GA-Maximum-fx-Algorithm)

- React Programming  
(https://github.com/kumass2020/react-app-test)

- Bigdata  
(https://github.com/kumass2020/2022-1-Bigdata)

- Raspberry Pi Sensors  
(https://github.com/kumass2020/RaspberryPi-Sensors-Nodejs/settings)

- Android Programming  
(https://github.com/kumass2020/Android-JAVA-Programming)  
(https://github.com/kumass2020/Android-Fundamental)

- JSP Programming  
(https://github.com/kumass2020/jsp-health-platform)

- Capstone Project  
(https://github.com/dev-yun/health_partner)  
  - 졸업 프로젝트로 진행한 온라인 헬스 PT 매칭 플랫폼.  

### Toy Projects
- Melon Ticketing Bot (사이트 취약점 및 보안 문제로 Private)  
  - Captcha 문제를 Image Processing (noise reduction)과 ML 라이브러리로 해결.  
- Interpark Ticketing Bot (Private)  
  - Captcha 문제를 Image Processing (noise reduction)과 ML 라이브러리로 해결.  
- Naver Smartstore Alert  
(https://github.com/kumass2020/Naver-Smartstore-Alert/tree/main)  

### Contribution to Open-Source Project
- Screen To Gif  
(https://github.com/NickeManarin/ScreenToGif)
