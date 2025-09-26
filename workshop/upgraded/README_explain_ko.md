# 업그레이디드 폴더 구조 설명# 업그레이디드 폴더 구조 설명



이 폴더는 레거시 프로젝트의 모든 파일과 디렉터리를 최신 환경에서 작업할 수 있도록 복사한 공간입니다.이 폴더는 레거시 프로젝트의 모든 파일과 디렉터리를 최신 환경에서 작업할 수 있도록 복사한 공간입니다.



## 주요 폴더 및 파일## 주요 폴더 및 파일



- `MANIFEST.in`, `README.rst`, `distribute-0.6.10.tar.gz`, `distribute_setup.py`, `setup.py`: 레거시 패키징 및 설치 관련 파일- `distribute_setup.py`, `MANIFEST.in`, `distribute-0.6.10.tar.gz`, `README.rst`, `setup.py`: 레거시 패키징 및 설치 관련 파일

- `docs/`: 프로젝트 문서 및 빌드 산출물- `docs/`: 프로젝트 문서 및 빌드 산출물

- `guachi/`: 주요 Python 모듈 및 테스트 코드  - `Makefile`: 문서 빌드용 Makefile

- `guachi.egg-info/`: 패키징 메타데이터  - `build/`: Sphinx로 빌드된 문서 결과물

    - `doctrees/`: Sphinx 내부 문서 트리

## 활용 방법    - `html/`: HTML 문서 및 정적 파일

      - `_sources/`, `_static/`: 원본 문서와 정적 리소스

이 폴더의 모든 파일은 Python 최신 버전으로 포팅 및 리팩토링, 테스트, 문서화, 패키징 개선 등 다양한 작업을 진행할 수 있습니다. 각 하위 폴더와 파일은 레거시 프로젝트의 기능별로 분리되어 있으니, 목적에 따라 필요한 부분을 선택해 작업하세요.  - `source/`: Sphinx 문서 원본(rst, conf.py 등)

- `guachi/`: 주요 Python 모듈 및 테스트 코드
  - `__init__.py`, `config.py`, `database.py`: 핵심 모듈
  - `tests/`: 유닛 및 통합 테스트
- `guachi.egg-info/`: 패키징 메타데이터
  - `PKG-INFO`, `SOURCES.txt` 등

## 활용 방법

이 폴더의 모든 파일은 Python 최신 버전으로 포팅 및 리팩토링, 테스트, 문서화, 패키징 개선 등 다양한 작업을 진행할 수 있습니다. 각 하위 폴더와 파일은 레거시 프로젝트의 기능별로 분리되어 있으니, 목적에 따라 필요한 부분을 선택해 작업하세요.
