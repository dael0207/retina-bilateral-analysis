# Data boundary

이 저장소는 원본·소스 해상도의 개별 안저 사진, 원본 라벨 CSV, 환자별 분석표를 포함하지 않습니다.

- 입력 자료: 사용자가 제공한 EyePACS 형식의 `trainLabels.csv`
- 확인한 열: `image`, `level`
- 파일명 규칙: `{patient_id}_left`, `{patient_id}_right`
- 등급: 0–4 당뇨망막병증 단계
- 관련 공개 설명: [Kaggle Diabetic Retinopathy Detection](https://www.kaggle.com/competitions/diabetic-retinopathy-detection/data)

원본 데이터의 이용 및 재배포 조건은 원 제공처의 약관을 따릅니다. 이 저장소는 데이터 사용권을 새로 부여하지 않습니다. `results/`에는 개인 이미지를 포함하지 않는 집계 JSON과 차트만 있습니다.

`docs/images/overview.png`는 과제 결과를 설명하기 위한 화면 캡처이며, 비식별 안저 예시 두 장과 데이터셋 내부 예시 ID가 축소된 형태로 포함되어 있습니다. 원본 이미지 파일과 환자별 원시 레코드는 저장소에 포함하지 않았습니다. 저장소를 공개로 전환하거나 캡처를 다른 목적으로 재배포하기 전에는 원 데이터 약관과 권리 범위를 다시 확인해야 합니다.
