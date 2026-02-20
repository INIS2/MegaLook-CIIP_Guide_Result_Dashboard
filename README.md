# MegaLook-CIIP_Guide_Result_Dashboard

CIIP 점검 스크립트 결과를 한눈에 보기 위한 대시보드 프로젝트입니다. MegaLook 기반 점검 결과(CSV)를 수집하고, 항목별 준수 여부와 요약 지표를 시각화하는 것을 목표로 합니다.

## Goals
- 점검 결과를 표/요약 지표 형태로 빠르게 확인
- 대분류/중분류/항목별 상태 집계
- 장비/시스템별 결과 비교
- 리포팅을 위한 데이터 정리 및 재사용 가능 구조

## Structure
- `Content/`: 기준 체크리스트 및 기준 데이터
- `Result/`: 점검 결과 CSV

## Expected Input
- MegaLook 점검 결과 CSV (시스템/장비별)
- CIIP 체크리스트 CSV

## Output (Planned)
- 통합 요약 대시보드
- 항목별 준수/미준수 현황
- 시스템별 비교/필터링

---

## Version History
- v0.1: 초기 구조 구성 및 데이터 수집 준비
