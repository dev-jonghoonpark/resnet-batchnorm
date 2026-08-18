# ResNet의 BatchNorm — 깊은 네트워크는 왜 배치 정규화가 필요한가

ResNet에서 Batch Normalization이 하는 역할을 다루는 단일 페이지 교육 자료입니다.

- BN이 필요한 이유 — 깊은 네트워크에서 신호 분포가 무너지는 문제
- BN의 수식 (μ, σ², 정규화, γ·β)과 인터랙티브 분포 데모
- ResNet 블록 안에서 BN의 위치 (post-activation vs pre-activation)
- 브라우저에서 직접 계산하는 30층 신호 전파 시뮬레이션 (BN / skip connection 토글)
- 학습 vs 추론 모드, BN folding, BN의 한계와 대안 (GroupNorm, LayerNorm, NFNet)

## 보기

https://dev-jonghoonpark.github.io/resnet-batchnorm/

## 구성

- `index.html` — 외부 의존성 없는 단일 HTML 파일 (CSS·JS 인라인)

로컬에서 볼 때는 파일을 브라우저로 바로 열면 됩니다.
