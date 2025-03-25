# :shield: CPR: Cyber Pentest & Reporting

**웹 공격 탐지 우회 시뮬레이션 프로젝트**

## :round_pushpin: 소개

WAF(ModSecurity)를 적용한 환경에서 SQL Injection, XSS 등의 웹 공격을 시뮬레이션하고,  
탐지 필터를 우회하는 기법들을 실험하고 분석하는 프로젝트입니다.

## :test_tube: 실험 흐름

1. 정보 수집 (`nmap`, `nikto`, `whatweb` 등)
2. 기본 공격 실험 (SQLi, XSS)
3. 우회 기법 테스트 (인코딩, 필터 우회)
4. WAF 탐지 여부 로그 분석
5. 자동화 및 리포트 작성

## :file_folder: 폴더 구성

- `payloads/`: 사용된 공격 페이로드 정리
- `scripts/`: 자동화 Python 코드
- `logs/`: 탐지 로그 (가공된 샘플)
- `report/`: 분석 보고서 PDF 및 그래프
- `demo/`: 시연 영상 및 화면 캡처

## :link: 결과물 미리보기

- [시연 영상 보기](demo/업로드 예정)
- [보고서 다운로드](report/업로드 예정)

## :computer: 사용 기술

- Python, Apache, ModSecurity, Burp Suite, Docker, Matplotlib
