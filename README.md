# DanParking 프로젝트

이 프로젝트는 딥러닝 기반 주차 관리 시스템입니다.

## 프로젝트 구조

### 1. 백엔드 (DanParking_BACKEND)
- Spring Boot 기반 백엔드 API 서버
- 사용자 인증, 주차장 관리, 즐겨찾기 기능 등 제공

### 2. 프론트엔드 (Danparking_frontend)
- React Native 기반 모바일 애플리케이션
- 주차 공간 시각화, 사용자 인터페이스 등 제공

### 3. 영상처리 모델 (DanParking_YOLOv5)
- YOLOv5 객체 인식 모델을 활용한 주차 공간 인식 시스템
- 차량 및 주차 공간 인식 알고리즘 포함

## 개발 환경
- 백엔드: Java 11, Spring Boot 2.7.x
- 프론트엔드: React Native
- 영상처리: Python 3.8, PyTorch, YOLOv5
