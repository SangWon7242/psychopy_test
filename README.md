# 이미지 비교 실험

## 설치 방법

1. 가상환경 생성 및 활성화

```bash
python -m venv venv
source venv/bin/activate  # macOS/Linux
# 또는
venv\Scripts\activate  # Windows
```

2. 필요한 패키지 설치

```bash
pip install -r requirements.txt
```

## 실행 방법

```bash
python src/test.py
```

## 필요 사항

- Python 3.6 이상
- 필요한 패키지들은 requirements.txt에 명시되어 있습니다.

---

# Image Comparison Experiment

HP DreamColor Z27x 모니터용 이미지 비교 실험 프로그램

## 요구사항

- Python 3.8 이상
- HP DreamColor Z27x 모니터 (2560×1440 해상도)
- 필요한 Python 패키지 (requirements.txt 참조)

## 설치 방법

1. Python 설치 (3.8 이상)
2. 필요한 패키지 설치:
   ```bash
   pip install -r requirements.txt
   ```

## 실행 방법

1. 프로그램 실행:

   ```bash
   python src/test.py
   ```

2. 프로그램 사용법:
   - 참가자 정보 입력
   - 이미지 폴더 선택
   - 실험 시작
   - 키보드로 응답:
     - 왼쪽 화살표(←): 왼쪽 이미지 선택
     - 오른쪽 화살표(→): 오른쪽 이미지 선택
     - ESC: 전체화면 모드 해제

## 주의사항

- HP DreamColor Z27x 모니터에 최적화되어 있습니다
- 이미지는 자동으로 10cm × 10cm 크기로 조정됩니다
- 결과는 CSV 파일로 저장됩니다
