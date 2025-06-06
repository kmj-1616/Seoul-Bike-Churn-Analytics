# 프로젝트 작업 항목 (Tasks)

## 1. 프로젝트 초기 설정
- [x] GitHub 저장소 설정
- [x] 프로젝트 문서화 (README.md, PRD)
- [ ] MIT 라이선스 추가
- [ ] .gitignore 파일 설정
- [ ] 개발 환경 설정 (requirements.txt 생성)
  - Python 3.x
  - 필요한 라이브러리: pandas, scikit-learn, matplotlib, seaborn
- [ ] GCP 프로젝트 설정
  - BigQuery 활성화
  - Data Studio 설정
  - 서비스 계정 및 인증 설정

## 2. 데이터 수집 및 전처리 (FR1, FR2, FR3)
- [ ] 서울열린데이터광장 API 키 발급
- [ ] 데이터 수집 스크립트 작성
  - [ ] API 연동 모듈 개발
  - [ ] 월간 이용 데이터 수집 자동화
- [ ] 데이터 전처리 파이프라인 구축
  - [ ] 결측값 처리
  - [ ] 이상치 탐지 및 처리
  - [ ] 중복 데이터 제거
- [ ] BigQuery 테이블 스키마 설계
- [ ] 데이터 적재 자동화 스크립트 작성

## 3. 데이터 분석 (FR4, FR5, FR6)
- [ ] SQL 분석 쿼리 작성
  - [ ] 연령대별 이용 패턴 분석
  - [ ] 시간대별 이용 패턴 분석
  - [ ] 이탈 사용자 정의 및 식별
- [ ] 사용자 군집화 분석
  - [ ] 특성 엔지니어링
  - [ ] K-Means 군집화 모델 개발
  - [ ] 군집 프로파일링
- [ ] 이탈 패턴 분석
  - [ ] 30일 이상 미사용 사용자 분석
  - [ ] 이탈 예측 지표 개발

## 4. 전략 개발 (FR7, FR8)
- [ ] A/B 테스트 설계
  - [ ] 테스트 가설 수립
  - [ ] 실험군/대조군 설정
  - [ ] 성공 지표 정의
- [ ] 유지 전략 개발
  - [ ] 타겟 프로모션 전략
  - [ ] 앱 UX 개선 제안
  - [ ] 리텐션 향상 전략

## 5. 시각화 및 보고서 (FR9, FR10)
- [ ] 데이터 시각화
  - [ ] 이탈률 트렌드
  - [ ] 군집 프로필 시각화
  - [ ] 사용자 행동 패턴 시각화
- [ ] 대시보드 개발
  - [ ] GCP Data Studio 대시보드 구축
  - [ ] 주요 KPI 모니터링 설정
- [ ] 최종 보고서 작성
  - [ ] 분석 결과 요약
  - [ ] 전략 제안 상세 설명
  - [ ] 시각화 자료 통합

## 6. 품질 관리
- [ ] 코드 품질 관리
  - [ ] 코드 문서화
  - [ ] 단위 테스트 작성
  - [ ] 코드 리뷰
- [ ] 성능 최적화
  - [ ] 데이터 처리 성능 개선
  - [ ] 쿼리 최적화
- [ ] 보안 검토
  - [ ] API 키 관리
  - [ ] 데이터 접근 권한 설정

## 7. 프로젝트 완료
- [ ] 최종 테스트
- [ ] 문서 완성
- [ ] 결과 발표 자료 준비
- [ ] GitHub 저장소 정리

## 타임라인
- 총 기간: 6주
- 주당 작업 시간: 10시간
- 1-2주차: 초기 설정 및 데이터 수집/전처리
- 3-4주차: 데이터 분석 및 전략 개발
- 5-6주차: 시각화, 보고서 작성 및 마무리 