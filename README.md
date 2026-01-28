# openai-test (uv)

Azure OpenAI 샘플 코드를 `uv`로 관리할 수 있게 기본 프로젝트 구성을 추가했습니다.

## 빠른 시작

1) 가상환경/의존성 설치

```powershell
uv venv
uv sync
```

2) 환경변수 설정

```powershell
Copy-Item .env.example .env
```

`.env`에 값을 채우세요.

3) 실행

```powershell
uv run python main.py
```

## 환경변수

- `AZURE_OPENAI_ENDPOINT`
- `AZURE_OPENAI_API_KEY`
- `AZURE_OPENAI_API_VERSION` (기본값: `2024-12-01-preview`)
- `AZURE_OPENAI_DEPLOYMENT` (기본값: `gpt-5`)

