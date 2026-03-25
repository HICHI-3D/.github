# HAICHI

기존 가구를 스캔하여 **새로운 공간에서의 배치를 시뮬레이션할 수 있는 서비스**

사용자가 현재 보유한 가구를 기반으로 새로운 공간에서의 배치를 미리 확인할 수 있도록 하여  
이사, 자취, 기숙사 생활 등에서 공간 활용을 돕는 것을 목표로 합니다.

---

# ✨ Features

## 🏠 Room Layout Upload
- 방 도면 이미지를 업로드하여 작업 공간 생성
- 도면 비율 설정 및 공간 편집

---

## 🪑 Furniture Scan
- 사용자가 가구를 여러 각도에서 촬영
- 가구 형태를 분석하여 **3D 모델 생성**
- 색상, 무늬, 스티커 등 **표면 텍스처 반영**

---

## 📋 Furniture List
- 스캔된 가구 목록 관리
- 가구 이름 및 크기 확인
- 가구 수정 및 삭제
- 선택한 가구를 도면에 배치

---

## 🧩 Furniture Placement Simulation
2D 도면 기반 가구 배치 시스템

- 드래그 앤 드롭 배치
- 가구 이동
- 가구 회전
- 가구 크기 조정
- 벽면 배치 제한
- 가구 충돌 방지

---

## 🧊 3D Preview
2D 편집 결과를 **3D 공간에서 확인**

- 실제 공간감 확인
- 가구 높이 및 부피 확인
- 배치 결과 검토

---

## 🤖 AI Layout Recommendation
공간 구조와 가구 정보를 기반으로 **추천 배치 제공**

추천 기준
- 벽면 활용
- 동선 확보
- 공간 활용 최적화

---

# 🖥 UI Layout
| Furniture List | Workspace | Properties Panel |
|---------------|-----------|------------------|
| 가구 목록 | 2D / 3D 작업 공간 | 속성 설정 |


---

# ⚙ Tech Stack

## Frontend
- React
- TypeScript
- Konva (2D editor)
- React Three Fiber (3D rendering)
- Styled Components

## Backend
- FastAPI
- Python

## AI / Computer Vision
- YOLO (object detection)
- OpenCV (image processing)

## Database
- PostgreSQL

---

# 📸 Furniture Scanning Strategy

사용자가 가구를 여러 각도에서 촬영하여 3D 모델을 생성합니다.

촬영 예시

- front
- back
- left
- right
- diagonal

초기 단계
- 단순화된 3D 모델 생성

확장 단계
- **Photogrammetry 기반 정밀 모델 생성**

---

# 📅 Development Plan

| Week | Task |
|-----|-----|
| 1~2 | Project planning & UI design |
| 3~4 | Room layout upload system |
| 5~6 | Furniture list & placement system |
| 7~8 | 3D preview system |
| 9 | AI layout recommendation |
| 10 | Testing & final presentation |

---

# 🚀 Future Work

- Photogrammetry 기반 가구 정밀 스캔
- AR 기반 공간 배치
- 자동 공간 스캔 기능
- AI 인테리어 추천 시스템

---

# 💡 Motivation

기존 인테리어 서비스는 **새로운 가구 구매 중심**으로 설계되어 있습니다.

HAICHI는 **사용자가 이미 보유한 가구를 활용하여 새로운 공간을 미리 배치해볼 수 있는 서비스**를 목표로 합니다.

> "Arrange your real furniture in a new space."
