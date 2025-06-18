# DanParking YOLOv5

YOLOv5 객체 인식 기반의 주차장 공간 인식 시스템입니다.

## 주요 기능
- 주차된 차량 인식
- 주차 공간 점유 상태 감지
- 실시간 영상 처리
- 다양한 날씨 조건에서의 차량 인식

## 실행 방법

### 1. 개발 환경 설정
```bash
# Python 3.8 이상 설치

# 필요한 패키지 설치
pip install -r requirements.txt
```

### 2. 모델 실행

#### 주차 공간 감지
```bash
python detect_parking.py --source [이미지/비디오/카메라ID] --weights [모델경로] --conf 0.25
```

#### ROI(관심영역) 지정
```bash
python annotate_roi.py --source [이미지경로]
```

### 3. 모델 학습 (선택사항)
```bash
# 기본 학습
python train.py --data models/data.yaml --weights yolov5s.pt --epochs 100

# 세분화 학습
python segment/train.py --data models/data.yaml --weights yolov5s-seg.pt --epochs 100
```

## 데이터셋 구조
- `custom_dataset/`: 학습에 사용된 커스텀 데이터셋
  - `images/`: 학습 및 검증 이미지
  - `labels/`: 바운딩 박스 레이블

## 모델 파일
- YOLOv5 사전 학습 모델 사용
- 주차장 환경에 맞게 fine-tuning

## 의존성
- PyTorch
- OpenCV
- NumPy
- Pandas
- Matplotlib
- PyYAML 