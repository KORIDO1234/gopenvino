# GOPENVINO
사용자 인식과 손동작 인식을 이용한 모니터 각도조절 시스템

## High Level Design
![poster](./flowchart.jpg)


## Clone code
```
git clone https://github.com/KORIDO1234/gopenvino.git
```

## Prerequite

### desktop 설정
1. clone한 폴더로 이동
```
cd ./gopoenvino
```
2. 가상 환경 생성 (python 버전 3.10.12
```
python3 -m venv .venv
```
3. 가상 환경 실행
```
source .venv/bin/activate
```
4. 요구 패키지 설치
```
pip install -r requirements.txt
```

### H/W 설정
1. arduino UNO에 code.ino 업로드

## Steps to build
* 가상환경 활성화
```
source .venv/bin/activate
```

## Steps to run
* src 폴더로 이동 후 메인파일 실행
```
cd ./src
python main.py
```
## Output
