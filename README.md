# 방사광 가속기와 AI로 읽는 2000년 전 두루마리

GitHub Pages: https://dongjinka.github.io/2026-particle-accelerator/

로컬에서는 정적 서버로 열어야 한다(`image-slot`이 fetch를 사용하므로 `file://` 직접 열기는 일부 자산이 제한될 수 있음).

    python3 -m http.server 8000
    # http://localhost:8000

## 구성

- `index.html` — 덱 본체 (10 슬라이드, 1920×1080, Pretendard)
- `deck-stage.js` — 스테이지/네비게이션 (자동 스케일·인쇄·썸네일 레일)
- `image-slot.js` — 이미지 슬롯 컴포넌트
- `scroll.webp` — 슬라이드 2, 탄화 두루마리 사진
- `porphyras-detection.jpg` — 슬라이드 9, ΠΟΡΦΥΡΑΣ 잉크 검출 이미지 (Vesuvius Challenge)
