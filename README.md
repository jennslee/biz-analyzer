# 사업구상 분석 AI

Claude Opus 4.7 기반 사업 아이디어 심층 분석 웹앱

## 기능

- 15개 섹션 심층 분석 (시장/경쟁/수익/MVP/VC 관점 등)
- 실시간 SSE 스트리밍
- 피치덱 슬라이드 뷰 (13슬라이드)
- DOC / PPT 내보내기
- 분석 이력 저장 (SQLite)

## 로컬 실행

```bash
pip install -r requirements.txt
cp .env.example .env
# .env에 ANTHROPIC_API_KEY 입력
py web.py
# http://localhost:8200 접속
```

## Railway 배포

1. [railway.app](https://railway.app) → New Project → Deploy from GitHub repo
2. 이 저장소 선택
3. Variables에 `ANTHROPIC_API_KEY` 추가
4. Deploy
