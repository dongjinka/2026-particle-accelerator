# 방사광 가속기와 AI로 읽는 2000년 전 두루마리

입자가속기 강의 기말 발표 슬라이드. 베수비오 화산에 묻힌 헤르쿨라네움 두루마리를
방사광 가속기와 AI로 펴지 않고 읽어내는 과정(Vesuvius Challenge)을 10장으로 정리했다.

발표자: 컴퓨터소프트웨어학과 2022270624 가동진

## 보기

GitHub Pages: https://dongjinka.github.io/2026-particle-accelerator/

로컬에서는 정적 서버로 열어야 한다(`image-slot`이 fetch를 사용하므로 `file://` 직접 열기는 일부 자산이 제한될 수 있음).

    python3 -m http.server 8000
    # http://localhost:8000

## 조작

- 좌우 화살표 · PgUp/PgDn · Space: 이전 / 다음
- 화면 좌우 절반 클릭(터치): 이전 / 다음
- R: 처음으로
- 브라우저 인쇄 → PDF로 저장: 슬라이드당 1페이지(1920×1080)로 출력

## 구성

- `index.html` — 덱 본체 (10 슬라이드, 1920×1080, Pretendard)
- `deck-stage.js` — 스테이지/네비게이션 (자동 스케일·인쇄·썸네일 레일)
- `image-slot.js` — 이미지 슬롯 컴포넌트
- `scroll.webp` — 슬라이드 2, 탄화 두루마리 사진
- `porphyras-detection.jpg` — 슬라이드 9, ΠΟΡΦΥΡΑΣ 잉크 검출 이미지 (Vesuvius Challenge)
