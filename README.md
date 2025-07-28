# 🚀 AI3 서버 (Backend)

> Clova AI를 활용한 요약·분석 API 서버  
> Flask 기반으로 구현되었으며, AI3 클라이언트와 연동됩니다.

---


## 📌 프로젝트 소개
AI3 클라이언트가 전송한 텍스트 데이터를 Naver Clova Studio API로 요약·분석하여  
결과를 JSON 형태로 반환하는 백엔드 서버입니다.  
- Flask + Flask-CORS  
- `.env`에 저장된 `CLOVA_API_KEY` 로 인증  

---

## 🛠️ 기술 스택

| 분류           | 기술                                                                                              |
| -------------- | ------------------------------------------------------------------------------------------------- |
| **언어**         | ![Python](https://img.shields.io/badge/Python-343422.svg?logo=Python&style=for-the-badge&logoColor=3776AB) |
| **웹 프레임워크** | ![Flask](https://img.shields.io/badge/Flask-343422.svg?logo=Flask&style=for-the-badge&logoColor=white)       |


---

## 🔑 환경 변수

프로젝트 루트에 `.env` 파일을 생성하고, 아래 내용을 추가하세요:

```env
CLOVA_API_KEY=your-api-key-here
```

## 🏃 설치 및 실행

1. 가상환경 생성 & 활성화
```
python3 -m venv venv
source venv/bin/activate    # macOS/Linux
# venv\Scripts\activate     # Windows
```
2. 의존성 설치
```
pip install -r requirements.txt
```

3. 서버 실행
```
python3 server.py
```
- 기본 포트: 4000
- 디버그 모드 활성화
