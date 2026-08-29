# NeuroLoop PWA v0.2

의대생용 신경해부학·신경과 Active Recall + Spaced Repetition 학습 웹앱입니다.

## iPhone에서 쓰는 가장 쉬운 방법
1. 이 폴더 전체를 GitHub Pages, Cloudflare Pages, Vercel 등의 정적 호스팅에 업로드합니다.
2. 생성된 HTTPS 주소를 iPhone Safari에서 엽니다.
3. Safari 공유 버튼 → **홈 화면에 추가** → **추가**.
4. 홈 화면의 NeuroLoop 아이콘을 누르면 독립 앱처럼 실행됩니다.

## 현재 포함 기능
- 9개 기본 모듈
- 57개 핵심 Active Recall 카드
- Tier 기반 우선순위
- 몰랐음/헷갈림/알았음/너무 쉬움 평가
- 간격 반복 일정 자동 계산
- 학습 진도와 장기 유지 카드 집계
- 검색 가능한 커리큘럼
- localStorage 기반 기기 내 진도 저장
- Service Worker 기반 오프라인 캐시

## 주의
- `file://`로 index.html을 직접 열면 Service Worker가 작동하지 않을 수 있습니다. PWA 설치와 오프라인 기능을 위해 HTTPS 호스팅을 권장합니다.
- 학습 기록은 현재 브라우저/기기에 저장됩니다. Safari 데이터 삭제 시 진도가 사라질 수 있습니다.
- 이 버전은 초기 학습용 베이스이며, 향후 Neuroanatomy Core 300 및 임상신경학 전체로 확장할 수 있도록 데이터 구조를 분리했습니다.
