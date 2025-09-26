# 업그레이디드 폴더 실제 구조 설명

이 폴더는 레거시 프로젝트의 모든 파일과 디렉터리를 최신 환경에서 작업할 수 있도록 복사한 공간입니다.

## 주요 폴더 및 파일

- MANIFEST.in, README.rst, distribute-0.6.10.tar.gz, distribute_setup.py, setup.py: 레거시 패키징 및 설치 관련 파일
- docs/: 프로젝트 문서 및 빌드 산출물
- guachi/: 주요 Python 모듈 및 테스트 코드
- guachi.egg-info/: 패키징 메타데이터
- .keep: 빈 디렉터리 유지를 위한 파일
- README_explain_ko.md, README_structure.txt: 폴더 구조 및 설명 파일

## 활용 방법

이 폴더의 모든 파일은 Python 최신 버전으로 포팅 및 리팩토링, 테스트, 문서화, 패키징 개선 등 다양한 작업을 진행할 수 있습니다. 각 하위 폴더와 파일은 레거시 프로젝트의 기능별로 분리되어 있으니, 목적에 따라 필요한 부분을 선택해 작업하세요.
