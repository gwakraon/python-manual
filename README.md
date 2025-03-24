# python-manual
파이썬 개발 환경 설정
# 파이썬 개발 환경 메뉴얼

## Python 설치
1. [https://www.python.org/downloads/](https://www.python.org/downloads/) 접속
2. 최신 버전 설치
3. 설치할 때 "Add Python to PATH" 꼭 체크!
4. 설치 확인: `python --version`

## VSCode 설치 및 설정
1. [https://code.visualstudio.com](https://code.visualstudio.com) 에서 다운로드
2. Python 확장 프로그램 설치
3. 새 파일 만들고 `.py` 확장자 사용

## 가상환경 만들기
```bash
python -m venv venv
venv\Scripts\activate    # Windows
source venv/bin/activate # Mac
