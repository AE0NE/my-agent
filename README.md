# my-agent

Streamlit으로 실행하는 챗봇 프로젝트입니다.

Python 3.11을 사용합니다. 상단 네비게이션은 Streamlit 1.46 이상이 필요합니다.

## 실행 방법 (macOS)

처음 설정할 때 프로젝트 폴더에서 실행합니다.

```bash
uv venv --python 3.11 --seed .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

앱을 실행합니다.

```bash
source .venv/bin/activate
python -m streamlit run app.py
```

브라우저에서 http://localhost:8501 을 엽니다. 종료하려면 터미널에서 `Ctrl+C`를 누릅니다.
