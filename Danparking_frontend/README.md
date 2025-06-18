# DanParking 프론트엔드

React Native 기반의 주차장 관리 시스템 모바일 애플리케이션입니다.

## 주요 기능
- 지도 기반 주차장 정보 시각화
- 주차 가능 공간 실시간 표시
- 사용자 인증 및 계정 관리
- 즐겨찾기 주차장 관리

## 실행 방법

### 1. 개발 환경 설정
```bash
# Node.js 및 npm 설치 (16.x 이상 권장)
# yarn 설치 (선택 사항)
npm install -g yarn
```

### 2. 의존성 설치
```bash
# npm 사용 시
npm install

# yarn 사용 시
yarn install
```

### 3. 애플리케이션 실행
```bash
# 개발 서버 실행
npm run start
# 또는
yarn start

# Android 앱 실행
npm run android
# 또는
yarn android

# iOS 앱 실행 (Mac 환경에서만 가능)
npm run ios
# 또는
yarn ios
```

## 주요 컴포넌트
- **MainMap**: 지도 기반 주차장 시각화
- **HomePanel**: 메인 화면 패널
- **SearchBar**: 주차장 검색 기능
- **HomeContent**: 홈 화면 컨텐츠
- **MyPageContent**: 마이페이지 화면

## 의존성
- React Native
- React Navigation
- React Native Maps
- Axios 