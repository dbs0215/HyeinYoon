# Dual Chirp-Duration Radar — 비교 분석 사이트

*Dual Chirp-Duration Velocity Ambiguity Resolution for 77 GHz Automotive FMCW Radar* (Hyein Yoon, Chonnam National University) 과제 v2 (교수 피드백 반영) 웹 페이지입니다.

Live site: https://dbs0215.github.io/HyeinYoon/

| 경로 | 내용 |
|---|---|
| `index.html` | 메인: ① 동작 시나리오 재생 ② 선행연구 블록도 ③ 같은 조건 비교 분석 ④ 발표 자료 · 수행 과정 로그 |
| `logic/index.html` | 논리 회로도와 Verilog 구현 (dc_top / pkd / div / comb / seq), 시뮬레이션·합성 결과 |
| `roos/index.html` | 대표 선행연구 Roos et al., ICMIM 2018 (TDM-MIMO 위상 방식) 블록도 |
| `v1/index.html` | 원 시스템 블록도 (2026-10-06 버전) |

비교 시뮬레이션: Python/NumPy 몬테카를로 (단일 표적 4개 방식 × 17 SNR × 600회, 다중 표적 1,500회).
