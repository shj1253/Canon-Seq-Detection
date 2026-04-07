# Canon-Seq-Detection

project-root/
│
├── src/                        # 핵심 소스 코드
│   ├── detection/              # Target 스크린 검출 로직
│   ├── streaming/              # 실시간 영상 스트림 처리
│   ├── notification/           # 알림 시스템
│   └── api/                    # REST API or gRPC 엔드포인트
│
├── models/                     # AI 모델 관련
│   ├── weights/                # 학습된 가중치 (.pt, .onnx 등)
│   └── configs/                # 모델 설정 파일
│
├── notebooks/                  # 실험 및 프로토타이핑
│   ├── eda/                    # 데이터 탐색
│   └── experiments/            # 모델 실험
│
├── data/                       # 데이터 관리
│   ├── raw/                    # 원본 이미지/영상
│   ├── processed/              # 전처리된 데이터
│   └── samples/                # 테스트용 샘플
│
├── utils/                      # 공통 유틸리티
│   ├── image_utils.py          # 이미지 전처리 헬퍼
│   ├── video_utils.py          # 영상 처리 헬퍼
│   └── logger.py               # 로깅
│
├── tests/                      # 테스트 코드
│   ├── unit/
│   └── integration/
│
├── configs/                    # 환경별 설정
│   ├── dev.yaml
│   └── prod.yaml
│
├── scripts/                    # 실행 스크립트
│   ├── train.sh
│   └── deploy.sh
│
├── docs/                       # 문서
│
├── docker/                     # 컨테이너 설정
│   ├── Dockerfile
│   └── docker-compose.yml
│
├── .github/                    # CI/CD 워크플로우
│   └── workflows/
│
├── requirements.txt
├── .env.example
├── .gitignore
└── README.md
